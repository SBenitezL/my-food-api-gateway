# API GATEWAY

Aplicación que sirve como gateway de los microservicios desarrollados, se encargará del manejo de autenticación y autorización de los endpoints utilizando keycloak.

> [!NOTE]
> para ejecutar correctamente el Dockerfile debe ejecutar el commando:
>
> ```sh
>    mvn clean package -DskipTests
>    docker build -t api-gateway .
>
> ```
