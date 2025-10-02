## Функции приложения
1. отвечает на порту 8000
2. имеет http-метод:  
GET /health/  
RESPONSE: {"status": "OK"}

## Создание docker образа
mvn clean package spring-boot:build-image

## Запуск docker контейнера локально
docker-compose up -d

## Отправка образа на docker hub
docker push andrewmv12/microservices:0.0.1