# Cookiecuter Data Science

<!-- badges: start -->

<!-- badges: end -->

Crear tu propia plantilla personalizada utilizando cookiecutter.

## Requiremientos

- [Anaconda](https://www.anaconda.com/download/) >= 4.x
- [git](https://git-scm.com/) >= 2.x
- [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0:
    Esto puede ser instalado con `pip` o `conda` dependiendo cómo tú manejas tus paquetes de Python:
    
## Instalación
Ve al directorio donde quieres crear el proyecto y crea un entorno virtual

``` bash
python3 -m venv .env
```
Activa el entorno virtual

``` bash
source .env/bin/activate
```
Installa cookiecutter

``` bash
pip install cookiecutter
```
o

``` bash
conda install -c conda-forge cookiecutter

```

## Crear un nuevo proyecto

En el directorio en el que creaste guarda tu proyecto generandolo con:

``` bash
cookiecutter https://github.com/cchnoe/coockiecutter_data_science.git
```

## Estructura de directorios y archivos resultantes

    {{ cookiecutter.project_slug }}
        ├── data
        │   ├── processed      <- The final, canonical data sets for modeling.
        │   └── raw            <- The original, immutable data dump.
        │
        ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
        │                         the creator's initials, and a short `-` delimited description, e.g.
        │                         `1.0-jvelezmagic-initial-data-exploration`.
        │
        ├── .gitignore         <- Files to ignore by `git`.
        │
        ├── environment.yml    <- The requirements file for reproducing the analysis environment.
        │
        └── README.md          <- The top-level README for developers using this project.

---
Proyecto creado con fines de productividad para la creación de un entorno de trabajo profesional para data sience" por [@cchnoe](https://twitter.com/cchnoe).