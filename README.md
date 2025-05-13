# ejemplos de programacion orientada a objetos

## 1. crear el archivo **.gitignore**


```shell
*.pyc
__pycache__/
.venv/
```

## 2. crear el **virtual environment**

se crea el ambiente virtual del trabajo

````shell
python3 -m venv .venv
````

## 3. iniciar el **virtual enviroment** 

se activa el **virtual enviroment** para instalar las librerias necerias para el pryecto

````shell
source .venv/bin/activate
````

## 4. actualizar pip dentro del **virtual enviroment**

se actualiza la version instalada de **pip** para poder descargar las ultimas versiones de las librerias.

````shell
pip install --upgrade pip
````

## 5. verificar las librerias instaladas 

se verrifica que librerias se tiene instaladas

````shell
pip freeze
````
## 6. instalar libererias necesarias para el proyecto

se instala las librerias que se utilizaran en el proyecto

````shell
pip install web.py
````


