# Resume-Back-End

Back End adalah bagian dari website yang berfungsi untuk menjalankan web dari balik layar dan memiliki banyak API (Application Programming Interface) yang digunakan. Rest API adalah salah satunya.

Apa Itu REST API?
REST API adalah cara aplikasi berbicara dengan aplikasi lainnya lewat internet. “REST” sendiri singkatan dari Representational State Transfer, yang merupakan cara untuk merancang sistem yang saling terhubung menggunakan jaringan. Sementara API adalah singkatan dari Application Programming Interface, yaitu antarmuka yang memungkinkan dua aplikasi berbicara satu sama lain, bertukar data, dan menjalankan tugas tertentu.

Jadi, REST API adalah jenis API yang mengikuti aturan-aturan tertentu dalam desain sistem yang disebut REST, yang dirancang agar lebih mudah digunakan, ringan, dan fleksibel.

Mengapa REST API Digunakan?
REST API digunakan oleh pengembang untuk memungkinkan aplikasi yang berbeda berinteraksi satu sama lain. Misalnya, jika menggunakan suatu aplikasi di ponsel, aplikasi tersebut bisa mengakses data dari server lain melalui REST API. Tanpa REST API, aplikasi tersebut tidak bisa mendapatkan data tanpa membangun sistem mereka sendiri dari awal.

Contoh lain adalah saat login ke suatu situs menggunakan akun Google atau Facebook. Di balik layar, situs tersebut menggunakan REST API untuk berkomunikasi dengan server Google atau Facebook, sehingga bisa masuk tanpa perlu membuat akun baru.

Apa yang Dilakukan oleh REST API?
REST API bekerja dengan cara menghubungkan dua aplikasi melalui protokol HTTP (yang biasa digunakan untuk mengakses halaman web). Aplikasi yang membutuhkan data akan mengirimkan permintaan ke server menggunakan metode HTTP tertentu, dan server akan mengirimkan respons kembali, yang berisi data yang diminta.

Ada beberapa hal yang REST API lakukan, seperti:
  1. Mengambil Data: Misalnya, aplikasi ingin menampilkan suatu data, maka aplikasi akan mengirimkan permintaan GET untuk mendapatkan data tersebut dari server.
  2. Menambahkan Data: misalnya menambah data seseorang yang memerlukan login ke dalam aplikasi, REST API akan mengirim permintaan POST untuk mengirim data ke server
  3. Mengubah Data: Jika ada data yang perlu diperbarui, misalnya mengganti alamat email, REST API akan mengirim permintaan PUT untuk memperbarui data yang sudah ada.
  4. Menghapus Data: Jika ada data yang perlu dihapus, misalnya menghapus akun pengguna, REST API akan mengirim permintaan DELETE ke server.

Mengapa REST API Populer?
REST API sangat populer karena kesederhanaannya. Dengan menggunakan standar HTTP yang sudah ada, REST API membuat aplikasi lebih mudah berkomunikasi satu sama lain. Pengembang tidak perlu khawatir tentang protokol yang rumit, dan cukup mengikuti prinsip REST, seperti:

- Menggunakan URL untuk mewakili sumber daya (data).
- Menggunakan metode HTTP standar seperti API yang lainnya seperti Get, Post, Put, Delete
- Setiap permintaan yang dibuat adalah stateless (tidak ada informasi yang disimpan dari permintaan sebelumnya).

