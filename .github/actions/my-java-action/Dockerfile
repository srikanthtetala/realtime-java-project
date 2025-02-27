FROM maven:3.8.6-eclipse-temurin-17


WORKDIR /app

COPY pom.xml .

COPY script.sh /script.sh
RUN chmod +x /script.sh

CMD ["/script.sh"]
