# Final Project Riset  

Nama : Faris Syaifulloh
NIM :20081010078

**__SISTEM MONITORING KAPASITAS SAMPAH BERBASIS IOT UNTUK MENGATASI RISIKO BANJIR DI SUNGAI TANGKIS WAGE, KABUPATEN SIDOARJO__**

Penelitian ini bertujuan mengatasi risiko banjir di Sungai Tangkis Wage, Kabupaten Sidoarjo, dengan mengimplementasikan Sistem Monitoring Kapasitas Sampah berbasis Internet of Things (IoT). Melalui teknologi ini, penelitian fokus pada pemantauan real-time kapasitas sampah di sungai untuk mengoptimalkan manajemen sampah, dengan harapan dapat mengurangi potensi banjir yang disebabkan oleh penumpukan sampah. Solusi ini diarahkan untuk meningkatkan efisiensi pengelolaan sampah dan memberikan respons yang lebih cepat terhadap permasalahan lingkungan yang dapat menyebabkan risiko banjir di daerah tersebut.

**__Metode__**

Pengembangan sistem dilakukan dengan beberapa langkah. Pertama, digunakan sensor ultrasonik HC-SR04 untuk mendeteksi tingkat atau ketinggian sampah dalam tempat sampah. Kedua, proses pengumpulan data dari sensor dimulai dari NodeMCU sebagai mikrokontroler, dan data dikirimkan melalui jaringan Wi-Fi. NodeMCU ini ditenagai oleh powerbank yang mendapat pasokan daya dari sistem fotovoltaik atau secara mandiri mengisi daya dari sumber cahaya matahari jika diperlukan. Langkah ketiga melibatkan proses pengumpulan data sensor secara online dan real-time, menggunakan protokol MQTT broker sebagai bagian dari Internet of Things (IoT). Keempat, sebuah aplikasi berbasis Android dikembangkan dan diinstal pada smartphone untuk menampilkan data tingkat sampah dan memberikan notifikasi jika tempat sampah sudah penuh.

**__Refrensi__**

1. Budioko, T. (2016). SistemMonitoringSuhuJarak Jauh Berbasis Internet Of ThingsMenggunakan Protokol Mqtt. In Seminar
2. Aritonang, P. L. E., Bayu, E. C., K, S. D., &Prasetyo, J. (2017). Rancang BangunAlat Pemilah Sampah Cerdas Otomatis. InProc. SNITT Poltekba (pp. 375–381). POliteknikNegeri Balikpapan.
3. Ermawati, Y. (2012). Sistempendeteksi kapasitas tempat smpah secara otomatispada kompleks perumahan. Teknika, 2(3), 1–7.

**__Dataset__**

Data yang saya gunakan adalah data kapasitas sampah yang ada di sekitar lingkungan Sungai Tangkis untuk dilakukan tes

**__Analisis Pengujian__**
1. Pengujian Fungsionalitas hardware
   a. Integrasi NodeMCU dengan Sensor HC-SR04
   b. NodeMCU dapat terkoneksi dengan jaringan interne
   c. Sensor dapat mendeteksi ketinggian sampah
   d. NodeMCU dapat mengirimkan data dari sensor ke MQTT broker
3. Pengujian fungsionalitas software
   a. MQTT broker dapat menerima data yang dipublish oleh NodeMCU
   b. MQTT broker dapat meneruskan data yang didapat sampai aplikasi
   c. Aplikasi dapat menerima data yang diteruskan oleh MQTT broker
   d. Aplikasi dapat memberi notifikasi saat batas ketinggian sudah mencapai batas

**__Draft Paper Publikasi__**

![image](https://github.com/faris-studio/TugasRiset/assets/103984227/859ee4e8-3ada-4147-be25-30c482e14cad)

