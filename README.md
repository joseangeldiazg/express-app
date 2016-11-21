#Repositorio para ubicación de aplicaciones de prueba. 

En este repositorio ubicaremos una aplicacion de prueba basada en Express para poder usar en los distintos ejercicios de la asignatura Cloud Computing del máster en ingeniería informática. El uso es el siguiente:

1. Instalamos express-generator para ello usamos el siguiente comando ``npm install express-generator -g``.
2. Tras esto ejecutamos el comando ``express myapp`` que nos creara todo lo necesario para ejecutar la aplicación. 
3. El siguiente paso es instalar las dependencias para ello entramos dentro del directorio y introducimos `` npm install``.
4. Tras esto podemos ejecutar la aplicacion, en mi caso que uso Mac OS X lo hacemos con el comando, ``DEBUG=myapp:* npm start``.
5. El siguiente paso es acceder a a la aplicacion que se ejecuta por defecto en el puerto 3000. asi que accedemos a ``localhost:3000``. Con lo que veremos el resultado de la app. 