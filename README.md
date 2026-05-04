# Repositorio para subir recetas 

- Es público, puedes subir tus propias recetas.

## Cómo funciona

Te clonas localmente el repositorio, este crea la carpeta TomaRecetas donde tienes
- carpeta /docs/ dentro estan los archivos .md y las fotos                                                                                                                                    
- carpeta /site/ es una carpeta que genera y gestiona mkdocs cuando ejecutas el comando mkdocs gh-deploy.
- archivo /mkdocs.yml, donde esta la estructura de la web.
-  LICENSE y .gitignore creados por git al crear el repo.

Necesitas los paquetes python mkdocs y mkdos-material, te recomiendo crearte un entorno virtual:
- python -m venv mkdocs
- .\mkdocs\Scripts\activate
- pip install mkdocs
- pip install mkdocs-material

Finalmente para crear una nueva entrada:
- Archivo en /docs/
- Poner la nueva entrada en mkdocs.yml y en index.md
- Subes los cambios a git
- Ejecutas mkdocs gh-deploy