# Module 09
###### Deanita Sekar Kinasih
###### 2306229405

## a. What is amqp?

AMQP (Advanced Message Queuing Protocol) adalah protokol open-standard communication yang dirancang untuk message-oriented middleware. Protokol ini memungkinkan aplikasi untuk melakukan pertukaran pesan secara asynchronous, aman, dan efisien melalui message broker, seperti RabbitMQ. AMQP memisahkan sistem sender dan receiver, memungkinkan keduanya berkomunikasi meskipun beroperasi pada waktu atau kecepatan yang berbeda. Protokol ini menstandardisasi proses messaging, memastikan interoperabilitas di berbagai platform dan teknologi yang berbeda sambil mempertahankan reliability dalam data delivery. AMQP sangat bermanfaat dalam sistem terdistribusi dimana komponen-komponen membutuhkan komunikasi yang scalable, flexible, dan fault-tolerant, seperti dalam microservices architectures. 

## b. What does it mean? `guest:guest@localhost:5672`, what is the first guest, and what is the second guest, and what is localhost:5672 is for?

`guest:guest@localhost:5672` adalah format URL koneksi standar untuk mengakses AMQP message broker, seperti RabbitMQ.

- `guest:guest` adalah format username:password untuk login dengan first guest adalah username autentikasi dan second guest adalah password milik username tersebut.

- `localhost` adalah hostname yang menunjukkan bahwa broker berjalan di local machine.

- `5672` adalah port number yang digunakan secara default untuk menerima koneksi AMQP.

Secara ringkas, URL ini berarti kita sedang terhubung ke AMQP message broker menggunakan username/password default dan port AMQP standar. 