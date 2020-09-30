# Build
mvn clean package && docker build -t gt.com.kinal/hola-mundo .

# RUN

docker rm -f hola-mundo || true && docker run -d -p 8080:8080 -p 4848:4848 --name hola-mundo gt.com.kinal/hola-mundo 

# Adding new comment to README
This is the development branch

# Feature 001: Adding REST service
REST service will implement GET, POST, PUT and DELETE
