# helloworld示例项目

1.To build
--------
mvn clean package -Dmaven.test.skip=true

2.To Dockerfile build
--------

docker build -t helloworld:0.1 .

3.To run
--------
docker run --name helloworld  -d -p 8080:8080 -it helloworld:0.1

4.To kubernetes
--------
kubectl apply -f helloworld.yaml
