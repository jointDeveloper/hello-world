## Instalar Git en Linux y Windows

### Linux

Para instalar Git en un sistema operativo Linux Ubuntu:

1. Abrir la terminal de Linux mediante 
	* Ctrl + Alt + T
	* Buscar en el menú "Terminal"

2. Escribir el siguiente comando:

	```
	sudo apt-get update
	sudo apt-get install git
	```

3. Verificar la versión de Git.it 

	```
	git --version
	```

3. Configurar el nombre

	```
	git config --global user.name "<Your Name>"
	```
	
	Es posible visualizar el nombre de la siguiente manera
	
	```
	git config --global user.name
	```

	Si nos equivocamos o queremos cambiar el nombre simplemente escribimos:

	```
	git config --global user.name "<Your Name New>"
	```

4. Configurar el e-mail

	```	
	git config --global user.email "<youremail@example.com>"
	```

Para ver nuestras configuraciones utilizamos el siguiente comando, este nos dará la lista de configuraciones realizadas

```
git config --global --list Esto
```

### Windows

Instalar Git en Windows es posible mediante la instalación de GitHub para Windows, este permite tener la interfaz de usuario de Git además de manejarlo por medio de lineas de comando, el instalador puede ser descargado desde [GitHub Desktop](https://desktop.github.com)


By [Oriana Cadavid](https://github.com/OrianaCadavid)

<p style="text-align: center;">
[Volver](./README.md)
</p>