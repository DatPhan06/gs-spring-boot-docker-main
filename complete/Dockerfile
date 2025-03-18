# Sử dụng OpenJDK 17
FROM openjdk:17-jdk-alpine

# Đặt tên cho file JAR nếu không xác định rõ
ARG JAR_FILE=target/*.jar

# Sao chép file JAR vào container
COPY ${JAR_FILE} app.jar

# Thiết lập lệnh ENTRYPOINT để chạy ứng dụng Spring Boot
ENTRYPOINT ["java", "-jar", "/app.jar"]
