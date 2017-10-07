## ¿Qué es un sistema de control de versiones?

El control de versiones es un sistema que registra los cambios realizados sobre un archivo o conjunto de archivos a lo largo del tiempo de tal manera que sea posible recuperar versiones específicas más adelante. Existen muchos Sistemas de Control de Versiones siendo algunos de los más conocidos CVS, Git, Subversion, Mercurial y Baazar.

## ¿Qué es Git?

Git es un sistema de control de versiones diseñado en el 2005 por Linus Torvalds. Git monitorea los cambios realizados en nuestro proyecto si agregamos o cambiamos líneas de código

### Ventajas

* __Velocidad y eficiencia:__ Git es capaz de gestionar desde pequeños hasta
grandes proyectos de software.
* Git es fácil de aprender
* No genera copias del último estado del código, sino que realiza un clon completo del repositorio.
* Git es libre y de código abierto

## Estados de los archivos en Git

* __Commited:__ Archivos que se encuentran almacenadas de manera segura en la base de datos local.
* __Modified:__ Archivos que han sufrido cambios pero a´un no han confirmados para guardarse en la base de datos local.
* __Staged:__ Archivos modificados que han sido marcados en su versión actual para que vayan a la próxima confirmación (commit) y se pueden almacenar en la base de datos

## Secciones principales de trabajo en Git
* __Working Directory:__ Donde se edita y trabajan los proyectos
* __Staging area:__ Donde se escoge que archivos están listos para pasar al tercer estado; también se elijen los que no están listos.
* __Repository:__ Donde se registra todo nuevo proyecto.
