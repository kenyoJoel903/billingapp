## BACKEND JAVA
## FRONTEND ANGULA


## DOCKERFILE
### Construir imagen a partir de un docker file
`docker build -t billingapp:0.0.1 --build-arg JAR_FILE=target/*.jar .`

## Iniciar contenedor
`docker run -dti -p 80:80 -p 8081:8081 --name billingapp billingapp:0.0.1`

### Frontend: http://localhost
###B ackend: http://localhost:8081/swagger-ui/index.html