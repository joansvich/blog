## Cómo empezar con Git


### En este documento os intentaré explicar resumidamente lo básico que tenemos que saber para empezar a usar Git


Antes de todo aclarar que Git y Github son cosas distintas: Github usa el software de control de versiones Git. Es decir, Git es la parte de software y Github es la plataforma donde da cabida a nuestros proyectos usando Git para poder colaborar con los diferentes usuarios.
En mi caso voy a usar Github.


- Primero de todo tenemos que configurarnos nuestro entorno Git, en mi caso uso Github.
- Una vez configurado, nos vamos a la consola y inicializamos git con la comanda **git init**


> En Github podemos usar tanto la interfaz gráfica para hacer todos los cambios como la consola de nuestro sistema operativo. En mi caso me gusta más usar la consola ya que voy más rápido, pero eso es una cuestión de gustos y costumbres.


- Para empezar a hacer cambios, tendremos que hacer un clonaje del repositorio (si tenemos creado uno) a nuestro sistema local. En este caso lo haremos con la comanda **git clone /rutaDirectorio


Llegados a este punto, tenemos que saber una cosa muy importante sobre el funcionamiento de Git:
Git se divide en tres partes: Directorio de trabajo, Index y Head. 
-- **Directorio de trabajo**: donde tenemos los archivos con los que estamos trabajando.
-- **Index**: es la zona intermedia donde podemos hacer commits para posteriormente subirlo al head.
-- **Head**: es la última zona donde tendrás tus archivos preparados para ser enviados a tu branch.


- Para añadir archivos al Index usaremos la comanda **git add nombreArchivo**. También podemos subir varios archivos del mismo tipo de archivo haciendo uso de la comanda **git add ".txt"**. Así subiríamos todos los archivos .txt al head.
- Si queremos hacer commit a esos cambios usaremos la comanda **git commit -m "Mensaje Commit"** y así tendremos constancia de lo que hemos hecho.


- Por último, si queremos enviar los cambios que tenemos hechos en Head será tan fácil como usar la comanda **git push origin master** donde master nos referimos a la rama (o branch) que queramos subirlo.
