# Springboot application on docker

### Build project
mvn clean install

### Build docker image

docker build -t byservices/springboot .

### Run docker 

docker run -d -p 8085:8085 byservices/springboot

### Testing
Open URL http://localhost:8085/serverip



