# TrabajoIndividual-AS
Repositorio para la entrega individual de Administración de Sistemas.

Contiene todos los ficheros necesarios para la realización del trabajo.
Se puede realizar un despliegue de contenedores con

> docker compose up

(Hay que añadir "sudo" si no se tienen permisos de root)

Las imágenes que se utilizan al hacer el compose (especificadas en el fichero docker-compose.yml) son las creadas utilizando los Dockerfile, que se encuentran alojadas en repositorios de Docker Hub.
Los Dockerfile se encuentran en servidor-lightstreamer y apache-web.

También he copiado los ficheros generados tras crearse el volumen especificado en el fichero docker-compose.yml. Se encuentran en el directorio "volumen".
