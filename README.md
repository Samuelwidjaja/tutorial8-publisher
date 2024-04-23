**Reflection**

a. The number of data that your publisher program will send to the message broker in one run depends on the specific implementation and requirements of your application. It could be a single message, multiple messages, or even a continuous stream of messages.

b. If the URL "amqp://guest:guest@localhost:5672" is used in both the publisher and subscriber programs, it means they are connecting to the same AMQP message broker.

**RabbitMQ**

1. RabbitMQ as message broker
   ![image](https://github.com/Samuelwidjaja/tutorial8-publisher/assets/119392779/249fa54e-31b0-4c92-bc2d-2d26a47599ca)

2. Sending and processing event
   *publisher terminal*
   ![image](https://github.com/Samuelwidjaja/tutorial8-publisher/assets/119392779/ecf12674-7935-4837-a9bb-e61b90d746ee)
   *subscriber terminal*
   ![image](https://github.com/Samuelwidjaja/tutorial8-publisher/assets/119392779/87144709-fd18-40d9-8d30-1e8f3677af53)
   *RabbitMQ process*
   ![image](https://github.com/Samuelwidjaja/tutorial8-publisher/assets/119392779/06080284-86e7-4c5f-b011-aa65198c1b40)

3. Monitoring chart based on publisher
   ![image](https://github.com/Samuelwidjaja/tutorial8-publisher/assets/119392779/2c7b1077-a506-45e1-9dcb-a55e26f9389e)





