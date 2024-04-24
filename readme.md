Nama: Isa Citra Buana (2206081465)

a. What is amqp?

Jawab: AMQP adalah protokol komunikasi yang digunakan untuk pertukaran pesan antara aplikasi atau layanan yang berbeda. Ini dirancang untuk mendukung komunikasi yang andal, skalabilitas, dan interoperabilitas antara berbagai sistem. AMQP adalah protokol terbuka dan banyak digunakan dalam sistem yang memerlukan antrian pesan, seperti sistem antrean pesan, komunikasi antar mikro, dan integrasi antar aplikasi.

b. what it means? guest:guest@localhost:5672 , what is the first quest, and what is
the second guest, and what is localhost:5672 is for? 

Jawab: 

`guest:guest:` Ini adalah cara untuk mengidentifikasi nama pengguna dan kata sandi saat mengakses server AMQP. Dalam contoh ini, "guest" adalah nama pengguna dan "guest" adalah kata sandi. Ini adalah nilai default yang sering digunakan dalam konfigurasi lokal atau pengembangan.

`localhost:5672:` Ini adalah alamat dan port dari server AMQP. "localhost" merujuk pada alamat loopback lokal, yang berarti server AMQP berjalan di mesin yang sama dengan klien yang mengaksesnya. "5672" adalah nomor port standar yang digunakan oleh server RabbitMQ (sebuah server AMQP yang populer). Port 5672 adalah port default yang digunakan untuk koneksi AMQP.
