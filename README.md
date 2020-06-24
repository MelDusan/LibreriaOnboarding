# LibreriaOnboarding
PASOS PARA CREAR UNA LIBRERIA EN ANDROID STUDIO MEDIANTE GITHUB

1.- Crear una nueva aplicacion elegir aplicacion blank.
2.- Una vez dentro de la aplicacion abrir la pestaña File/Archivo en la esquina superior izquierda.
3.- Le damos a new y new modulo eligimos la opcion Android Library.
4.- Le damos un nombre a nuestra Libreria y le damos en finalizar.
5.- Trabajamos todo el codigo en la vista Android en el apartado de nuestra libreria no en App.
6.- Cuando hayamos finalizado el codigo que queremos que este en nuestra libreria nos dirigimos a la esquina superior derechar y abrimos el gradle.
8.- Dentro del gradle abrimos nuestra libreria luego desplegamos Build y le damos doble clik en Assamble.
9.- El assamble nos generara el archivo AAR dentro de la aplicacion el cual corresponde a nuestra libreria hecho esto nuestra libreria ya esta creada.
10.- El siguiente paso es usar nuestra cuenta de Github desde android studio con nuestro proyecto y subir el proyecyto a un repositorio desde android.
11.- Una  vez que comprobemos que el repositorio se subio correctamente a Githhub debemos copiar el link del repositorio y pegarlo en la siguiente pagina https://jitpack.io/
12.-JItpack lo que hara es crear dos codigos para su implementacion.
13.- Para probar nuestra libreria en otras aplicaciones creamos una una nueva aplicacion de android studio.
14.- Una vez creada la aplicacion ir a la esquina superior izquierda y desplegamos el gradle scripts.
15.- Pegamos los codigos que nos genero Jitpack dentro de los archivos build.gradle(Proyect) y build.gradle(module app)
16. Sincronizar el proyecto de nuevo con los cambios realizados.
17. Nuestra librearia ya esta automaticamente implementada en la nueva aplicacion.
