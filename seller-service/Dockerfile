FROM gradle:8.10.2-jdk21
WORKDIR /app
COPY . .
RUN gradle --no-daemon installDist
EXPOSE 8080
CMD ["./build/install/seller-service/bin/seller-service"]