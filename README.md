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

## 7. crear el archivo **requirements.txtx**

se crea el archivo requirements con las librerias y el numero de version utilizadas

````shell
pip freeze > requirements.txt
````

## 8. crear el archivo **runtime.txt**

se crea el archivo runtime.txt para saber la verson de python3 que se esta utilizando

````shell
python3 -V runtome.txt
````

## 9. indexar los archivos creados con ***git**
 se indexa los archivos y cambios realizados e el proyecto

 ````shell
 git add .
 ````

 ## 10. generacion de commit

 se genera un **commit** con un texto que describa los cambios realizados en el proyecto

 ````shell
 git commit -m "CREATED configuracion basica"
 ````

 ## 11. realizar un **push** 
 
 se realiza un **push** para subir los cambios realizados al repositorio **github**

 ````shell
 git push -u origin main
 ````