# EntregaDockerExam


Primero clonaremos la imagen del profesor
![imagen](https://github.com/R4F31/EntregaDockerExam/blob/main/ExamenSistemas/1.PNG)

Una vez clonado el repositorio nos dirigimos al archivo docker-compose.yml y le daremos click derecho y docker compose up
![imagen](https://github.com/R4F31/EntregaDockerExam/blob/main/ExamenSistemas/2.PNG)

Una vez hecho se nos iniciaran los tres contenedores
![imagen](https://github.com/R4F31/EntregaDockerExam/blob/main/ExamenSistemas/3.PNG)

En el puerto 8081 estara alojado phpMyAdmin
![imagen](https://github.com/R4F31/EntregaDockerExam/blob/main/ExamenSistemas/4.PNG)

Y nos logeamos con estas credenciales
![imagen](https://github.com/R4F31/EntregaDockerExam/blob/main/ExamenSistemas/5.PNG)

En el puerto 8082 se habra desplegado tomcat y accedemos a traves de la ruta http://localhost:8082/LoginWebApp/registrer.jsp

![imagen](https://github.com/R4F31/EntregaDockerExam/blob/main/ExamenSistemas/6.PNG)

Para que todo funcione tenemos que añadir en la base de datos la columna regdate
![imagen](https://github.com/R4F31/EntregaDockerExam/blob/main/ExamenSistemas/7.PNG)

Una vez introducida la nueva columna en la pagina web introducimos datos para verificar que todo funciona y luego lo comprobaremos en la base de datos
![imagen](https://github.com/R4F31/EntregaDockerExam/blob/main/ExamenSistemas/8.PNG)
![imagen](https://github.com/R4F31/EntregaDockerExam/blob/main/ExamenSistemas/9.PNG)

Una vez que vemos que todo funciona subiremos nuestro docker-compose.yml a dockerhub
![imagen](https://github.com/R4F31/EntregaDockerExam/blob/main/ExamenSistemas/10.PNG)

Y revisaremos que se haya subido correctamente a nuestro repositorio
![imagen](https://github.com/R4F31/EntregaDockerExam/blob/main/ExamenSistemas/11.PNG)


