Hector Otero Caballero 

Edad: 19 años

![Yo](YO.jpg)

[Practicas](Practica5.md)


**////////////////////////////**

Materia: Sistemas Operativos
Profesor: Osiel Morales
La materia trata de como comunicarse y manejarse con el sistema operativo de la computadora.

**////////////////////////////**

Materia: Proyecto de App
Profesor: Sebastian Mejia
Es esta materia nos enfocaremos en programar y realizar una aplicacion. 

**////////////////////////////**

Materia: Diseño de Videojuegos
Profesor: Hector Guerrero
En esta materia vemos la mejor forma de planear la forma de crear un videojuego, que aspectos debemos buscar primero y como debemos hacer sentir al jugador.

**///////////////////////////**

Materia: Composicion y Diseño
Profesor: Roberto Melo
Aqui conocemos sobre como debe ser un buen diseño, que debe de llevar y como debe estar compuesto.

**//////////////////////////**

Materia: Lenguajes Interpretados
Profesor: Jonathan Mircha
Conocemos el correcto manejo de Git, de terminales de codigo usando Visual Studio Code.


Agregando Nuevos Comandos 

Aprendiendo a crear etiquetas


**///////////////////////////////**

¿Cómo se inicializa un repositorio en Git?
R= Se inicializa abriendo una terminal, seleccionando la terminal de bash y escribiendo ```bash git init. ```

¿Cómo creas un repositorio en GitHub?
R= Ya que estes dentro de Github te saldra la opcion de crear un nuevo repositorio en un recuadro verde, ahi podras escoger la cuenta, nombre y descripcion del repositorio. 

¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?
R=Una vez que hayas inicializado con git init, necesitas configurar tu nombre, correo electronico, etc y tendras que usar estos codigos:
 ```bash
git config --global user.name "Nombre"
git config --global user.email correo
git config --global user.ui true
git config --global init.defaultBranch main
git config --global core.editor "code --wait"
git config --global -e
```
(Si no es tu computadora deberas usar local en vez de global)
Ya que terminaste de trabajar, en la terminal usa el codigo ```bash git add . ```

Luego escogeras el nombre de tu cambio con  ```bash git commit -m "mensaje descriptivo del cambio" ```

Para subirlo a tu repositorio de Github debes usar el siguiente codigo, para el link debes irte a github, en code y ahi saldra.
```bash git remote add origin https://github.com/usuario/repositorio.git  ``` 

Como es la primera vez que subimos un cambio debemos usar git push -u origin master, ya las siguientes veces podremos usar git push. 

¿Cuál es el flujo básico de trabajo en Git y GitHub?
R= (Working Directory) Primero esta el archivo local de tu computadora, en donde estes trabajando en ese momento. 
(Staging Area) Despues viene cuando se le implementan los cambios al repositorio.
(Local Repository) Aqui los cambios ya se agregaron a tu repositorio o tu Head.
(Remote Repository) Aqui es donde se guarda el repositorio de manera remota y es donde se almacenan todos los archivos que hayamos subido al repositorio.   