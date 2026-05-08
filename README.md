# Proyecto Entorno S5 — Git y Documentación Técnica

Este proyecto fue desarrollado como práctica de configuración de entorno de programación utilizando Python, Visual Studio Code y Git.

## Objetivo

Aprender el manejo básico de Git, documentación técnica y control de versiones mediante commits descriptivos.



# Herramientas utilizadas

- Python 3.11
- Visual Studio Code
- Git
- GitHub



# Crear entorno virtual

Ejecutar el siguiente comando:

python -m venv .venv

#Activar entorno virtual
.venv\Scripts\activate

# Instalar Dependencias
pip install -r requirements.txt

# Ejecutar el proyecto
python leer_env.py

 ## Comandos basicos de Git
 # Ver estado del repositorio
 git status

# Agregar cambios 
git add .

# Agregar commit
git commit -m "feat: configuracion inicial del proyecto"

# Ver historial de commits
git log --oneline

# Ver historial mas detallado
git log --oneline --graph --all

# Ver quien hizo cada cambio y cuando 
git log --pretty=format:"%h %an %ad %s" --date=short

## Conventional Commits
Este proyecto utiliza mensajes descriptivos para los commits.

    # Prefijos
-feat: nueva funcionalidad
-fix: corrección de errores
-docs: documentación
-chore: mantenimiento
-refactor: reorganización del código

 Ejemplos:
# git commit -m "docs: agrega instrucciones de instalacion"
# git commit -m "feat: agrega lectura de variables .env"

## Como clonal el repositorio, hay dos opciones:
# 1: Por HTTPS: git clone https://github.com/USUARIO/NOMBRE_REPOSITORIO.git
# 2: Por SSH: git clone git@github.com:USUARIO/NOMBRE_REPOSITORIO.git
