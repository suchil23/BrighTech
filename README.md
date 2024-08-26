# ¿Qué es Github?

- GitHub es una plataforma donde puedes almacenar, compartir y trabajar junto con otros usuarios para escribir código
- Con Github puedes almacenar tu código pero también tienes las siguientes ventajas.

<ul>
    <li> Presentar o compartir el trabajo. </li>
    <li> Seguir y administrar los cambios en el código a lo largo del tiempo. </li>
    <li>Dejar que otros usuarios revisen el código y realicen sugerencias para mejorarlo. </li>
    <li>Colaborar en un proyecto compartido, sin preocuparse de que los cambios afectarán al trabajo de los colaboradores antes de que esté listo para integrarlos. </li>
</ul>

## Creación de cuenta Github
Para empezar a trabajar con GitHub, deberás crear una cuenta personal gratuita en GitHub.com <p>Abre tu navegador y accede al siguiente enlace <a href="https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2Flogos&source=header">Crea tu cuenta en Github</a></p> y comprobar la dirección de correo electrónico.

* Durante el registro, se te pedirá que verifiques tu dirección de correo electrónico. Sin una dirección de correo electrónico verificada, no podrás completar algunas tareas básicas de GitHub, como crear un repositorio.

* Ahora crea un nombre de usuario, es importante ya que en un futuro haremos referencia a ese nombre de usuario.

* Una vez creada la cuenta tendremos la siguiente pantalla, para esta sesión tienes que dirigirte a la sección de repositorios.

* En la sección de repositorios puedes crear un repositorio nuevo, ahora tienes que elegir un nombre **sin espacios** para poder continuar.

* Debes elegir la opción de que tu repositorio sea público y por último presionar el boton verde en la parte inferior derecha y crear el repositorio.

* Genial ahora ya creaste tu primer repositorio , vamos a poner una pausa y no cierres esta ventana, por favor continua ahora con la instalación de Git.

## Instalación GIT

<p>Abre tu navegador y accede al siguiente enlace <a href="https://git-scm.com/download/win">Descarga Git</a></p> y selecciona la opción de 64 bit de esta manera un archivo comenzará su descarga, basta con ejecutarlo e instalarlo.

Ahora vamos a abrir una terminal desde nuestro escritorio y vamos a escribir **git --version** 

## Comprobar versión Instalada
Ahora te vas a dirigir a Android Studio y vamos a abrir una nueva terminal para que puedas subir tu práctica y cambios a un repositorio de GitHub. Lo que sigue es escribir la siguiente linea **git init** este comando crea un nuevo repositorio de Git

* Una vez que inicializamos el repositorio tienes que escribir **git add .** para mover los cambios del directorio de trabajo al área del entorno de ensayo.

* Continua escribiendo **git commit -m "Primer commit"** este comando es una confrmación, las confirmaciones representan hitos dentro del proyecto de Git.
Para tener acceso a estas confirmaciones, es necesario el comando git commit . Sirve para capturar exactamente el estado del proyecto en un momento concreto, después de realizar la captura, las confirmaciones instantáneas son almacenadas en el repositorio local de Git.

* Ahora escribe **git branch gh-pages** El comando git branch permite crear una rama nueva.
Una rama o branch es una versión del código del proyecto sobre el que estás trabajando.


* Ahora escribe **git checkout gh-pages** esto te permite desplazarte entre las ramas creadas por git branch.

* Recuerda que creaste un repositorio en github donde vamos a subir esta práctica, por favor dirigete a Github y copia la siguiente linea de comando. 

* Ahora pega esa linea de comando en la terminal de esta manera. git remote origin "enlace del repositorio creado"

* Por último lo que tienes que hacer es un **git push -u origin gh-pages** con esta linea de comando lograremos subir todo lo que se ha agregado.

## Felicidades
 Acabas de crear un repositorio en Github y haz manejado un control de versiones.