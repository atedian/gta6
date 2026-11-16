# Sincronización automática con GitHub

Este directorio está enlazado con **https://github.com/atedian/gta6** y se publica solo.

- **Web en vivo (GitHub Pages):** https://atedian.github.io/gta6/
- **Qué hace:** cada minuto, el planificador de Hermes ejecuta
  `~/.hermes/scripts/gta6-autosync.sh`. Si hay cambios sin commitear, hace
  `git add -A` + un commit (`sync: actualización automática`) y push a `main`.
  Si no hay nada pendiente, no hace nada y no avisa.
- **Qué NO hace:** no reescribe ni formatea el código; no toca otras ramas.
- **Registro:** `~/Library/Logs/atedian-gta6-autosync.log` (rotación a 512 KB).
- **Credenciales:** token de la cuenta `atedian` leído de `gh` en cada pasada
  (`gh auth token --user atedian`); no hay tokens escritos en el repo.
- **Pausar / reanudar:** `hermes cron` → trabajo `gta6-github-autosync`.
- **Publicación:** al llegar el push, GitHub Pages reconstruye
  `https://atedian.github.io/gta6/` en ~1 minuto.

> Un `git push` manual no es necesario: basta con guardar los archivos.<br>
> Los `commit`s conviene escribirlos cuando se quiera un mensaje propio; el
> sincronizador solo añade los que falten.
