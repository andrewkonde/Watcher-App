# Watcher-App
A LoRa gateway logging service that uses MQTT to report on the uptime of the network connection.
Watcher App
Introduction
A LoRa gateway logging service that uses MQTT to report on the uptime of the network connection.
The application enables you to
1.	Know the status of the network connection of the Lora gateway
2.	Health status of the LoRa gateway.

Tools:
i.	Public MQTT broker
ii.	Host: broker.emqx.io
iii.	Port: 1883


Language: Python
IDE: Pycharm

The following steps were followed in developing the watcher app:
1.	Setting up MQTT broker.
The figure below shows the EMQX dashboard.

 ![image](https://user-images.githubusercontent.com/54850472/215862475-f65c3d98-4e13-4f84-8cff-32bd7584e76f.png)


2.	After the above step, two programs were developed, that is ‘watcherPublisher.py’ and ‘watcherSubscriber.py’.
i.	watcherPublisher.py
The figure below shows the running of watcherPublisher.py:
 
 ![image](https://user-images.githubusercontent.com/54850472/215862482-da65b205-6016-49b7-8fa4-a347b4276616.png)

 
ii.	watcherSubscriber.py
The figure below shows the running of watcherSubscriber.py

![image](https://user-images.githubusercontent.com/54850472/215862549-da10393a-0b16-4397-90d8-eb85d52d4d3f.png)
