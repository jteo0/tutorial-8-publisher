a. How many data your publlsher program will send to the message broker in one run?<br/>
Program publisher akan menyampaikan 5 <i>message</i> kepada message broker pada satu run. Ini bisa dilihat dari adanya lima UserCreatedEventMessage pada main.rs.

b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?<br/>
Ini berarti bahwa program subscriber dan publisher berhubungan (connect) dengan message broker yang sama.<br/>

Screenshot RabbitMQ:
![Screenshot RabbitMQ](img/RabbitMQ_1.png)

Screenshot console subscriber:
![Screenshot console subscriber](img/img_2.png)
Setiap kali cargo run dijalankan pada publisher, dimunculkan 5 message pada terminal subscriber. .