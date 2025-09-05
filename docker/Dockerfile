FROM openjdk:17-jdk-slim
WORKDIR /app
COPY target/shop-cart-0.0.1-SNAPSHOT.jar shop-cart.jar
ENTRYPOINT ["java", "-jar", "/app/shop-cart.jar"]
