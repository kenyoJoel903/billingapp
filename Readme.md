## BACKEND JAVA (SPRING BOOT)
## FRONTEND ANGULAR

### Construir imagen a partir de un dockerfile
`docker build -t billingapp:0.0.1 --build-arg JAR_FILE=target/*.jar .`

## Iniciar contenedor
`docker run -dti -p 80:80 -p 8081:8081 --name billingapp billingapp:0.0.1`

### Frontend: http://localhost
### Backend: http://localhost:8081/swagger-ui/index.html