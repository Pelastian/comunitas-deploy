FROM openjdk:13
VOLUME /tmp
ADD ./target/springboot-servicio-usuarios-0.0.1-SNAPSHOT.jar servicio-usuarios.jar
ENTRYPOINT ["java", "-jar", "/servicio-usuarios.jar"]