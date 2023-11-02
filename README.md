# ConvertirPythonEnExe
Cambiar de archivo Python o Jupyter Notebook a .EXE

```markdown
# Conversión de archivos .py y .ipynb a .exe

Este repositorio proporciona instrucciones y ejemplos sobre cómo convertir archivos Python (.py) y Jupyter Notebook (.ipynb) en archivos ejecutables (.exe) utilizando la herramienta `pyinstaller`. Esto puede ser útil para distribuir aplicaciones o scripts de Python de manera más conveniente.

## Requisitos previos

Antes de comenzar, asegúrate de tener instalado lo siguiente en tu sistema:

- Python: Asegúrate de tener una instalación de Python funcional en tu sistema.

- PyInstaller: Instala PyInstaller utilizando pip. Puedes hacerlo ejecutando el siguiente comando:

```bash
pip install pyinstaller
```

## Convertir un archivo .py a .exe

1. Abre una terminal y navega hasta el directorio que contiene el archivo `.py` que deseas convertir.

2. Ejecuta el siguiente comando para crear un archivo ejecutable `.exe`:

```bash
pyinstaller --onefile tu_script.py
```

3. El archivo ejecutable se generará en la carpeta `dist` dentro del directorio de tu proyecto.

## Convertir un archivo .ipynb a .exe

1. Asegúrate de tener Jupyter Notebook instalado. Si aún no lo tienes, puedes instalarlo con el siguiente comando:

```bash
pip install jupyter
```

2. Convierte tu archivo `.ipynb` en un archivo Python utilizando el comando `jupyter nbconvert`:

```bash
jupyter nbconvert --to script tu_notebook.ipynb
```

3. Ahora puedes seguir los pasos anteriores para convertir el archivo Python generado en un archivo `.exe`.

## Notas adicionales

- Asegúrate de que tu código esté libre de errores y que todas las bibliotecas necesarias estén instaladas antes de la conversión.

- Ten en cuenta que los archivos ejecutables generados pueden ser más grandes que los archivos de origen, ya que incluyen el intérprete de Python y las bibliotecas necesarias.

- El proceso de conversión puede variar según la complejidad de tu proyecto y las bibliotecas utilizadas. Es posible que debas ajustar las opciones de PyInstaller según tus necesidades específicas.

Esperamos que estas instrucciones te logren ayuden a convertir tus archivos .py o .ipynb en archivos .exe
