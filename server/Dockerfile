FROM openjdk:11
ENV TZ="America/Denver"

EXPOSE 8080

WORKDIR /usr/src/app

COPY chessdynamics /usr/src/app/

#RUN ls

RUN ./mvnw test

CMD ["./mvnw", "spring-boot:run"]
