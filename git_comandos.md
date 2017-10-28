By [Oriana Cadavid](https://github.com/OrianaCadavid)

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

5. Hacer más cambios: Ahora agregua otra lı́nea para readme.txt y guarda. En la terminal, puedes ver la diferencia entre el archivo ahora y cómo fue en su última confirmación:

	```
	git diff

	```
	Notas:

	Para agregar todos los archivos:
	```
	git Add -a

	```
	Para ver una lista de todos los commits con su respectiva información:

	```
	git log

	```

	Comando para viajar a través de nuestros
	commits o nuestras ramas:

	```
	git checkout

	```

## GitHubbin

1. Visita github.com y regístrate para obtener una cuenta gratuita.

2. Añade tu nombre de usuario GitHub y configura:

	```
	git config --global user.username <USerNamE>

	```


## Fork and Clones

Bifurca un proyecto de GitHub.com y clónalo localmente.

Ahora has hecho un proyecto a nivel local y lo enviaste a GitHub, pero eso
es sólo la mitad de la diversión. La otra mitad es trabajar con otras personas y
proyectos.

Cuando bifurcas (Fork) un repositorio, estás creando una copia de él en su
cuenta de GitHub. Su fork comienza su vida como un repositorio remoto.

Las horquillas (forks) se utilizan para crear tu propia versión de un proyecto o para contribuir con correcciones o caracterı́sticas al proyecto original.

Una vez que un proyecto se bifurca, a continuación, tu clon de GitHub queda
en tu computadora para trabajar localmente.




## Ejercicio

Resolver el problema de URIJudge llamado ["Extremadamente Básico"](https://www.urionlinejudge.com.br/judge/es/problems/view/1001) y crear un repositorio en GitHub en donde se guarde la solución ya aprobada por el juez.


<h3><p align="center">
	<a href="./README.md">Volver</a>
</p></h3>
