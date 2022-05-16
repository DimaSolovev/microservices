<b>Microservices and Distributed Systems application</b><p>
-Микросервисное приложение, состоящее из 3-х микросервисов Customer, Fraud и Notification<p>
-Postgres и SpringJPA для хранения данных <p>
-Для регистрации сервисов используется Eureka <p>
-Zipkin и Slueth для визуализации деталей трассировки <p>
-API Gateway как точка входа<p>
-В качестве брокера RabbitMQ <p>
-Docker и Docker-compose<p>
-Контейнеризация с помощью JIB и maven-jib-plugin<p>
-Далее деплой в Kubernates и использование service и Loadbalancer вместо Eureka<p>

Для скачивания контейнеров : docker compose pull<p>
Для запуска : docker compose up<p>

Для деплоя в kubernates : kubectl apply -f k8s/minikube/...

<b>Microservices scheme</b>
![Micro](https://user-images.githubusercontent.com/76641018/168600974-388146f5-9b16-4f96-be27-7f511c0733f5.png)

<b>Kubernates scheme</b>
![Kube](https://user-images.githubusercontent.com/76641018/168601191-8cbdfeac-7ddd-41cb-8883-25a686e59d3d.png)

