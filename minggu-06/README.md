Kubernetes untuk Pemula

Dalam lokakarya ini mempelajari konsep dasar Kubernetes.Melakukannya melalui berinteraksi dengan Kubernetes melalui terminal baris perintah di sebelah kanan. Pada akhirnya akan menggunakan contoh aplikasi Dockercoins di kedua node pekerja.

- Konsep Kubernetes

1.Kubernetes adalah sistem manajemen wadah 

2.Ini berjalan dan mengelola aplikasi kemas pada sebuah cluster Sumber daya Kubernetes

- API Kubernetes mendefinisikan banyak objek yang disebut sumber daya

 Beberapa jenis sumber daya umum adalah:
 
     1.simpul (mesin - fisik atau virtual - di cluster kami)
     
     2.pod (sekelompok kontainer yang berjalan bersama pada sebuah node)
     
     3.layanan (titik akhir jaringan yang stabil untuk terhubung ke satu atau beberapa kontainer)
     
     4.namespace (kelompok hal yang kurang lebih terisolasi)
     
     5.rahasia (bundel data sensitif untuk diteruskan ke wadah)
     
Arsitektur Kubernetes

Logika Kubernetes ("otak" -nya) adalah kumpulan layanan: 

  1.server API (titik masuk kami ke semuanya!) 

  2.layanan inti seperti scheduler dan manajer pengontrol 

  3.etcd (toko kunci / nilai yang sangat tersedia; "database" Kubernetes)
