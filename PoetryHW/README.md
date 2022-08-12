# PoetryHW

Probando el sabor de esta gran herramienta que soluciona algunos problemas que puede traernos el viejo y amigable
`pip freeze requirements.txt`. Algunos estan muy bien explicados por <a href="https://prakharrathi.medium.com/" target="_blank">Prakhar Rathi</a> en [Stop using “pip freeze” for your Python projects](https://towardsdatascience.com/stop-using-pip-freeze-for-your-python-projects-9c37181730f9).

## Pasos para usar poetry

1. Crear carpeta que contendrá poetry `mkdir folder_with_poetry`
2. Ir a folder_with_poetry `cd folder_with_poetry`
2. Crear un ambiente virtual `python3 -m venv venvpoetry`
3. Activar ambiente virtual `source venvpoetry/bin/activate`
- NOTA: asegurate que tu archivo .gitignore descarte el ambiente virtual
4. Actualizar pip `pip install --uprade pip`
5. Actualizar setuptools `pip install --upgrade setuptools`
6. (Instalar poetry)[https://python-poetry.org/docs/master/#installing-manually] `pip install poetry`
7. Iniciar proyecto con poetry `poetry new our_project`
8. Trabajar en el proyecto
9. Instalar librerias `poetry add pandas`
10. Al terminar no olvides correr `deactivate`


**IMPORTANE: Si quieres inicializar un proyecto que uso poetry sigue en el paso 7 debes correr: `poetry install`**