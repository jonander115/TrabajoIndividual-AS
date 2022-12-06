# TrabajoIndividual-AS
Repositorio para la entrega individual de Administración de Sistemas.

Contiene todos los ficheros necesarios para la realización del trabajo.
Se puede realizar un despliegue de contenedores con

> docker compose up

(Hay que añadir "sudo" si no se tienen permisos de root)

Las imágenes que se utilizan al hacer el compose (especificadas en el fichero docker-compose.yml) son las creadas utilizando los Dockerfile, que se encuentran alojadas en repositorios de Docker Hub.

Imagen del servidor: https://hub.docker.com/r/jonanderlda/servidor-entrega-individual-as

Imagen del cliente: https://hub.docker.com/r/jonanderlda/cliente-entrega-individual-as

Los Dockerfile se encuentran en servidor-lightstreamer y apache-web, junto con el resto del código.

También he copiado el contenido de los ficheros creados tras crearse el volumen especificado en el fichero docker-compose.yml. Se encuentran en el directorio "volumen".
