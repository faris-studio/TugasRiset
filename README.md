# Tugas Riset 1 
Mencari Topik Penelitian

Nama : Faris Syaifulloh
NIM :20081010078

**__Topik Penelitian__**

Topik : Penggunaan Internet of Things (IoT) dalam Sistem Pemantauan Lingkungan
		
  Penelitian ini membahas penggunaan Internet of Things (IoT) dalam sistem pemantauan lingkungan untuk memahami, melindungi, dan mengelola lingkungan alam kita. IoT telah mengubah cara kita mengumpulkan data lingkungan dengan mengintegrasikan sensor-sensor canggih ke dalam infrastruktur kota dan alam. Penelitian ini mencakup implementasi sensor-sensor IoT dalam pengukuran kualitas udara, suhu, kelembaban, tingkat polusi air, dan faktor-faktor lingkungan lainnya. Data yang dikumpulkan secara real-time dari sensor-sensor ini disalurkan melalui jaringan IoT dan dianalisis untuk memberikan wawasan yang mendalam tentang perubahan lingkungan dan dampaknya.
		Identifikasi persoalan praktis yang perlu diselesaikan melalui penelitian dalam penggunaan Internet of Things (IoT) dalam sistem pemantauan lingkungan adalah sebagai berikut:
1.	Kualitas Udara dan Pencemaran udara menjadi isu serius di banyak kota di seluruh dunia. Penelitian perlu mengatasi bagaimana IoT dapat digunakan untuk mengumpulkan data kualitas udara dengan akurat dan real-time, serta bagaimana data ini dapat digunakan untuk memberikan peringatan dini dan tindakan mitigasi yang efektif untuk mengatasi pencemaran udara.
2.	Manajemen sampah yang efisien dan pengurangan limbah menjadi kunci untuk menjaga lingkungan yang bersih dan berkelanjutan. Penelitian perlu fokus pada penggunaan IoT dalam mengelola dan mendaur ulang sampah dengan lebih efektif, termasuk pemantauan level sampah, pengelolaan rute pengumpulan sampah, dan manajemen fasilitas pengolahan limbah.
3.	Integrasi Data dan Interoperabilitas. Dengan banyaknya sensor dan perangkat yang berbeda dalam ekosistem IoT, tantangan utama adalah bagaimana mengintegrasikan data dari berbagai sumber dan memastikan interoperabilitas yang mulus.

Berdasarkan persoalan praktis yang telah diidentifikasi dalam penggunaan Internet of Things (IoT) dalam sistem pemantauan lingkungan, berikut adalah beberapa pertanyaan penelitian (research questions) yang dapat diajukan: 
1.	Bagaimana IoT dapat digunakan untuk memantau dan mengukur kualitas udara dengan akurat dan real-time di lingkungan perkotaan?
2.	Bagaimana sistem pemantauan IoT dapat memberikan peringatan dini terkait polusi udara yang dapat membahayakan kesehatan manusia?
3.	Bagaimana IoT dapat digunakan untuk pemantauan iklim yang lebih efektif dan memberikan informasi lebih awal tentang potensi bencana alam seperti banjir atau kebakaran hutan?
4.	Bagaimana IoT dapat digunakan dalam manajemen sampah untuk mengoptimalkan rute pengumpulan sampah dan mengurangi dampak lingkungan?
5.	Bagaimana teknologi IoT dapat membantu dalam pengelolaan sumber daya air yang lebih efisien dan melindungi daerah-daerah yang mengalami kekeringan?

Tinjauan kepustakaan merupakan langkah penting dalam penelitian tentang penggunaan Internet of Things (IoT) dalam sistem pemantauan lingkungan. Berikut adalah beberapa teori dan kerangka kerja yang memiliki keterkaitan dengan topik ini:
1.	Teori IoT dan Sensor Networks: Menjelaskan prinsip-prinsip dasar IoT, seperti konsep konektivitas, pengumpulan data sensor, dan jaringan sensor nirkabel. Teori ini juga membahas berbagai jenis sensor yang digunakan dalam pemantauan lingkungan.
2.	Teori Pemrosesan Data Real-Time: IoT seringkali melibatkan pengumpulan data real-time dari sensor. Teori ini mencakup teknik-teknik pemrosesan data real-time, seperti pengolahan aliran data (stream processing) dan analisis cepat.

**__Metode Penelitian Menggunakan Arduino IDE__**

Metode Menggunakan Arduino IDE adalah pendekatan untuk mengembangkan proyek dengan mikrokontroler seperti ESP32 dengan menggunakan lingkungan pengembangan terpadu (IDE) yang disebut Arduino IDE. Arduino IDE adalah perangkat lunak yang dirancang untuk memudahkan pemrograman mikrokontroler dengan bahasa pemrograman Arduino yang relatif mudah dipahami.

1. Persiapan Perangkat dan Sensor: Siapkan ESP32 dan sensor-sensor lingkungan seperti sensor suhu, kelembaban, atau kualitas udara yang akan digunakan untuk pemantauan. Hubungkan sensor-sensor tersebut ke pin GPIO pada ESP32.

2. Instalasi ESP32 Board Support: Buka Arduino IDE dan instal pustaka (board support package) untuk ESP32. Anda dapat melakukannya melalui "Pengaturan (Preferences)" dan menambahkan URL pustaka ESP32 ke "Pengaturan Tambahan (Additional Boards Manager URLs)".

3. Pemrograman ESP32: Tulis kode Arduino yang akan mengumpulkan data dari sensor-sensor lingkungan dan mengirimnya ke server atau platform IoT yang Anda tuju. Pastikan Anda menggunakan WiFi atau protokol komunikasi yang sesuai.

4. Unggah Kode ke ESP32: Hubungkan ESP32 ke komputer Anda melalui kabel USB dan unggah kode yang telah Anda tulis ke dalam mikrokontroler menggunakan Arduino IDE.

5. Koneksi ke Platform IoT: Anda dapat menghubungkan ESP32 ke platform IoT seperti ThingSpeak, Adafruit IO, atau platform kustom Anda. Platform ini akan memungkinkan Anda untuk menerima, menyimpan, dan memvisualisasikan data lingkungan yang dikumpulkan oleh ESP32.

