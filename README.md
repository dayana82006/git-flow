# 🚀 Git Flow - Resumen de Comandos

### Instalar

` sudo apt update
sudo apt install git-flow -y `

Verificar version
`git flow version`


## 🔹 Inicializar
- `git flow init` → Inicializa la estructura de ramas (`main`, `develop`, etc.).

## 🔹 Features (Nuevas funcionalidades)
- `git flow feature start nombre-feature` → Crea rama `feature/nombre-feature` desde `develop`.
- `git flow feature finish nombre-feature` → Fusiona en `develop` y elimina la rama.
- `git flow feature publish nombre-feature` → Publica la rama en remoto.
- `git flow feature pull origin nombre-feature` → Descarga la rama publicada.

## 🔹 Releases (Preparar versión estable)
- `git flow release start 1.0.0` → Crea rama `release/1.0.0` desde `develop`.
- `git flow release finish 1.0.0` → Fusiona en `main` y `develop`, añade tag y elimina la rama.
- `git flow release publish 1.0.0` → Sube la release al remoto.
****
