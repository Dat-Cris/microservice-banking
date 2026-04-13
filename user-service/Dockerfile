# Sử dụng image JDK 17 chính thức
FROM eclipse-temurin:17-jdk-alpine

# Tạo thư mục ứng dụng trong container
WORKDIR /app

# Sao chép file JAR vào thư mục làm việc trong container
COPY target/user-service-0.0.1-SNAPSHOT.jar /app/user-service-0.0.1-SNAPSHOT.jar

# Chạy ứng dụng khi container khởi động
ENTRYPOINT ["java", "-jar", "user-service-0.0.1-SNAPSHOT.jar"]
