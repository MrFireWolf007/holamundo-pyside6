# holamundo-pyside6

Hola mundo con PySide6.

Para ejecutar el *hola mundo*, necesitamos instalar antes Python3 y sus dependencias.

## Clonamos el proyecto en local y entramos en la carpeta del proyecto

```bash
$ git clone https://github.com/di-mcgrawhill/holamundo-pyside6.git
$ cd holamundo-pyside6/
```

## Instalación de Python3

![Python Logo](https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg)

### Linux
Python3 viene preinstalado en la mayoría de distribuciones Linux, se puede comprobar si está instalado ejecutando la siguiente orden en una terminal:

```bash
$ python3 --version
```

De no estar instalada, se puede descargar desde [aquí](https://www.python.org/downloads/).

Para más información de cómo instalar, consultar la [documentación](https://docs.python.org/3/).

### Windows
Descargar el instalador haciendo clic [aquí](https://www.python.org/downloads/windows/) y seguir las instrucciones en pantalla.

Se dispone de más información sobre su instalación en el siguiente [enlace](https://docs.python.org/3/using/windows.html).

### macOS
Se dispone del binario ejecutable en el siguiente [enlace](https://www.python.org/downloads/mac-osx/).

Se dispone de más información sobre su instalación en el siguiente [enlace](https://docs.python.org/3/using/mac.html).

## Creación de un entorno virtual (venv)

Para crear un entorno virtual y poder aislar la ejecución del resto del sistema (*sandbox*), ejecutamos la siguiente instrucción en una terminal.

```bash
$ python3 -m venv venv
```

## Activación del entorno virtual

### Linux y macOS
```bash
$ source venv/bin/activate
```

### Windows
```bash
$ venv\Scripts\activate.bat
```

## Instalación de dependencias
```bash
$ pip install -r requirements.txt
```

## Ejecución
```bash
$ python3 src/holamundo_pyside6/holamundo.py
```

Nos mostrará la aplicación *holamundo_pyside6* en ejecución.

![PySide6 Ejemplo](https://upload.wikimedia.org/wikipedia/commons/8/8a/PySide_logo.png)
