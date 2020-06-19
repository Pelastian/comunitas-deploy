FROM openjdk:13
VOLUME /tmp
ADD ./target/springboot-servicio-cargos-0.0.1-SNAPSHOT.jar servicio-cargos.jar
ENTRYPOINT ["java", "-jar", "/servicio-cargos.jar"]