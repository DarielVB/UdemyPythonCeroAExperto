# UdemyPythonCeroAExperto
Mi repositorio en el cual realizare el curso De Cero a Experto en Python: PySide, Tkinter, POO, Web con Django, Flask, Jinja, SQL Alchemy, Postgresql y PyCharm!

#   Seccion 1 comienzo

- Descargar python, de forma personalizada, y a la vez agragarlo al path (en las opciones personalizadas, se dejan todas las opciones ademas de agregar a todos los usuarios)

- Instalar PyCharm (en mi caso usare Visual Studio) brew install --cask pycharm-ce

- Se recomienda hacer el curso "Universidad de Lógica de Programación"

- Pytho se usa en, Web Development, Software Development, Desktop Application, Education, Database Access, Network programming, Game Development, 3D Graphi. Sirve en muchos sistemas y tiene un sintaxis facil de entener. Es un lenguaje interpretado.

- Virtualenv: entornos virtuales o ambiente de trabajo. Para administrar los paquetes, librerias, que estan ligados al proyectos. Dentro de estos entornos se agregaran los paquetes que usaremos para nuestro desarrollo en python. 
    - La version python 2 no es retro compatible con la 3
    - python3 (si no sirve, usar pip) pip3 install virtualenv
    - virtualenv .env (el nombre es: env, .env, enviroment, por standares para que cuando se trabaje con git, no toque versionar, salvando espacio en el repositorio y tiempo de copiado)
    - Se puede usar python3 -m venv venv, para usar envez de virtualenv la herramienta venv de python
    - Para activar en mac podemos usar . venv/bin/activate, en windows usamos source env/Scripts/activate (usando el git bash)

- Instalamos flask (lo agregamos al paquete env) pip install flask

- Para volver a tener nuestras dependencias hacemos un archivo de requeriments (ejemplo requirements/dev.txt) y para volver a ejecutarlo podemos ejecutar "
python3 -m pip install -r "requirements/dev.txt"

# Seccion 2 Variables

- Variables, no hay que especificar el tipo

- Direccion de memoria en la ram, se almacenan las variables, (son hexadeciomales), no siempre son los mismos, cada vez que se ejecuta nuestro programa se cambia su direccion de memoria, tambien se les dice referencia

# Seccion 3 Tipos de datos

- Las variables en python son dinamicas, si definimos una en str (hint), igual se le puede agregar un tipo int