## Crear un repositorio

Se va a crear una nueva carpeta e inicializarla como un repositorio Git desde nuestra computadora:

1. Crear una nueva carpeta:

	```
	mkdir hello-world
	```
2. Para entrar en esa nueva carpeta:

	```
	cd hello-world
	```

3. Marcar el inicio de nuestro proyecto o ini

	```
	git init
	```
	Nota: $ git init Este comando siempre se debe usar sólo una vez, al
	iniciar nuestro proyecto.

4. Estado del proyecto o repositorio

	```
	git status
	``` 

	Nos da el estado de nuestro proyecto. Por ejemplo si en nuestra carpeta tenemos algún archivo que no hayamos agregado a nuestro proyecto, con este comando veremos cuál es.

Otra forma de crear un repositorio es de la siguiente manera:

1. Ve a github.com, inicia sesión y haz click en ’+’ en la parte superior derecha para crear un nuevo repositorio.

2. Dale un nombre a tu repositorio y una breve descripción.

3. Hazlo público e inicializa con un README

5. Deja el .gitignore y haz click en crear repositorio

6. Clona el repositorio en tu computadora

A continuación se explican algunos terminos usados

### README
Un readme explica qué es el proyecto, cómo usarlo, y a menudo cómo contribuir (aunque a veces hay un archivo adicional, CONTRIBUTING.md, para esos detalles).

### .gitingnore

Un .gitignore es una lista de archivos que Git no debe rastrear, por ejemplo,
archivos con contraseñas.

### licencia

Un archivo de licencia es el tipo de licencia que pones en tu proyecto. La información sobre los tipos está aquí [choosealicense.com](https://choosealicense.com)

## Clonar un repositorio

1. Buscar el repositorio creado en GitHub y da click en el botón "Clone or download"

2. Copiar el link que aparece al hacer click

3. Abrir la terminal y usar el siguiente comando 

	```
	git clone <link copiado>
	``` 

## Hacer un commit

1. Crear un nuevo archivo

	Abrir un editor de texto (block de notas, sublime, atom, etc) y escribir un par de líneas de texto, tal vez decir hola, y guardar el archivo con el nombre que prefiera
2. Comprobar el estado del repositorio
3. Añadir el archivo: 

	```
	git add <nombre de archivo>
	```

	Para añadir todos los archivos de la carpeta se debe escribir:

	```
	git add .
	```
4. Breve descripciónn de las actualizaciones y guarda los cambios hechos:

	```
	git commit -m "<your commit message>" 

	```
    Nota: Como recomendación es importante que el mensaje sea claro, y contundente.

