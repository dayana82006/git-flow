# 🚀 Git Flow - Resumen de Comandos

## 🔹 Inicializar
```bash
git flow init

🔹 Features (Nuevas funcionalidades)
git flow feature start nombre-feature
git flow feature finish nombre-feature
git flow feature publish nombre-feature
git flow feature pull origin nombre-feature

start → crea rama feature/nombre-feature desde develop.

finish → fusiona en develop y elimina la rama.

publish → publica en remoto.

pull → descarga la rama publicada.


🔹 Releases (Preparar versión estable)
git flow release start 1.0.0
git flow release finish 1.0.0
git flow release publish 1.0.0


start → crea rama release/1.0.0 desde develop.

finish → fusiona en main y develop, añade tag y elimina la rama.

publish → sube la release al remoto.
