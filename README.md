a. What is AMQP?
AMQP (Advanced Message Queuing Protocol) adalah protokol komunikasi jaringan yang memungkinkan aplikasi untuk bertukar pesan secara asynchronous melalui message broker. AMQP mendefinisikan cara pesan dikirim, diantrekan, dan diterima antar program yang berbeda, bahkan jika ditulis dalam bahasa pemrograman berbeda.

b. What does "guest:guest@localhost:5672" mean?
- guest (pertama) = username untuk login ke RabbitMQ
- guest (kedua) = password untuk login ke RabbitMQ
- localhost:5672 = alamat dan port tempat RabbitMQ berjalan. localhost berarti server berjalan di komputer yang sama, dan 5672 adalah port default yang digunakan RabbitMQ untuk menerima koneksi AMQP.