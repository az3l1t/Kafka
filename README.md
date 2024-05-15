# Kafka
Была реализована система брокера сообщений Kafka. Написана логика работы Consumer и Producer. Создан топик "norair" и через API можно отправлять сообщения, данные.
В будущем будет использовано для моих проектов для общения между микросервисами.
![image](https://github.com/az3l1t/Kafka/assets/126178814/308e0518-7ec6-4362-8097-b9becf08a451)
![image](https://github.com/az3l1t/Kafka/assets/126178814/2507ba7a-5df6-4653-a20b-03bc40b4e0fb)

# Как использовать
Во-первых, нужен установленный JAVA на машине.
Во-вторых, нужно установить Kafka с официального сайта:
https://kafka.apache.org/downloads
Заходим в папку с установленными файлами.
Дальше, нужно запустить zookeeper:
```
C:\kafka> bin/zookeeper-server-start.sh config/zookeeper.properties
```
После этого запускаем непосредственно сам kafka:
```
C:\kafka> bin/kafka-server-start.sh config/server.properties
```
