FROM openjdk

WORKDIR /app

COPY ByXmlFile2-1.0-SNAPSHOT.jar /app/

COPY mapping.xml /app/

EXPOSE 5433
EXPOSE 5432

CMD ["java", "-jar", "ByXmlFile2-1.0-SNAPSHOT.jar"]


