FROM java:8
COPY maven /maven/
ENTRYPOINT sleep 20 && java -Dfile.encoding=UTF-8 -Djava.security.egd=file:/dev/./urandom -jar /maven/product-service-0.0.1-SNAPSHOT.jar && java -jar /maven/product-service-0.0.1-SNAPSHOT.jar
