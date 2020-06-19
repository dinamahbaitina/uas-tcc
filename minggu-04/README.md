Praktek Orkestrasi Docker

Pada materi ini menjelaskan fitur orkestrasi wadah Docker.
Menggunakan aplikasi sederhana ke satu host dan mempelajari cara kerjanya, mengkonfigurasi Docker Swarm Mode, dan belajar untuk menggunakan aplikasi sederhana yang sama di beberapa host.

1 Apa itu Orkestrasi

orkestrasi mungkin paling baik digambarkan menggunakan contoh. Katakanlah Anda memiliki aplikasi yang memiliki lalu lintas tinggi bersama dengan persyaratan ketersediaan tinggi. Karena persyaratan ini, Anda biasanya ingin menggunakan setidaknya 3+ mesin, sehingga jika tuan rumah gagal, aplikasi Anda masih dapat diakses dari setidaknya dua lainnya. Jelas, ini hanya sebuah contoh dan kasus penggunaan Anda kemungkinan akan memiliki persyaratan sendiri, tetapi Anda mendapatkan idenya.

2 Konfigurasikan Mode Gerombolan

Aplikasi dunia nyata biasanya digunakan di beberapa host seperti yang dibahas sebelumnya. Ini meningkatkan kinerja aplikasi dan ketersediaan, serta memungkinkan komponen aplikasi individu untuk skala secara mandiri. Docker memiliki alat asli yang tangguh untuk membantu melakukan ini.
