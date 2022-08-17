# eureka-dockerfile

chmod 777 mvnw      

./mvnw clean package

docker build -t eureka-serverv2 .  

docker tag eureka-serverv2 arturo090/eureka-serverv2:eureka-serverv2

docker login

docker push arturo090/eureka-serverv2:eureka-serverv2



https://github.com/Arturo-Hdz/eureka-dockerfile

docker hub https://hub.docker.com/r/arturo090/eureka-serverv2


