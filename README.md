1. Pembahasan :
Aplikasi Client Server Sederharna (Single Thread) ini menggunakan protokol TCP metode
“socket.SOCK_STREAM” dengan port 12345. Dengan menggunakan “socket.SOCK_STREAM” koneksi antara sever dan client akan stabil, dan data yang disampaikan dalam urutan yang benar
Aplikasi Client Server Sederharna (Single Thread) ini menggunakan metodemeskipun mungkin
dengan sedikit overhead karena kehandalan yang lebih tinggi. Saat server dijalankan dan tidak menerima koneksi atau terhubung dengan client maka server
akan menampilkan pesan “WAITING” sampai client terhubung dengan server, setelah terhubung
server akan menampilkan pesan IP client dan akan mengirimkan permintaan dari client yang
sudah terinputkan. Pesan berupa informasi apakah bilangan yang diinputkan adalah ganjil atau
genap

2 & 3. Pembahasan :
Berbeda dengan nomer satu yang menggunakan server_socket nomer 2 dan 3
menggunakan “client_socket” yang dimana cara bekerjanya client meminta komunikasi
dengan server, sementara “server_socket” sever meminta komunikasi masuk dari client. Program diatas meminta client untuk memasukan karakter (kalimat) yang akan dikoneksikan
ke pada sever sehingga sever akan menghitung banyaknya huruf dari inputan client
