![](https://user-images.githubusercontent.com/112606990/190147579-49ee998b-3305-4338-9889-ae661eb20967.png)

## `BAB` 1
# PENGENALAN

`TUJUAN BAB`

Untuk belajar tentang komputer dan pemrograman

Untuk mengkompilasi dan menjalankan program

Java pertama Anda
Untuk mengenali kesalahan waktu kompilasi dan run-time

Untuk menggambarkan suatu algoritma dengan pseudocode

`ISI BAB`

**1.1 PROGRAM KOMPUTER** 2

**1.2 ANATOMI KOMPUTER** 3
##### C&S Komputer Ada Dimana-mana 5

**1.3 PEMROGRAMAN JAVA BAHASA** 6

**1.4 MENJADI AKRAB DENGAN LINGKUNGAN PEMROGRAMAN ANDA** 7
#### PT1 Salinan Cadangan 10

**1.5 MENGANALISIS PROGRAM PERTAMA ANDA** 11
#### Program Java 12
#### Menghilangkan Titik Koma 13

**1.6 KESALAHAN** 14
#### Kata0kata yang salah eja 15

**1.7 PENYELESAIAN MASALAH: DESAIN ALGORITMA** 15
#### Mendeskripsikan Algoritma dengan kode semu 19
#### Kode semu 19 WE1 Menulis untuk Ubin Lantai 21

Sama seperti Anda mengumpulkan alat, mempelajari proyek, dan membuat rencana untuk
mengatasinya, dalam bab ini Anda akan mengumpulkan dasar-dasar yang Anda
perlukan untuk mulai belajar memprogram. Setelah perkenalan singkat
perangkat keras komputer, perangkat lunak, dan pemrograman dalam
umum, Anda akan belajar cara menulis dan menjalankan yang pertama
program Java. Anda juga akan belajar cara mendiagnosis dan
memperbaiki kesalahan pemrograman, dan cara menggunakan kode semu untuk
menggambarkan suatu algoritme—deskripsi langkah demi langkah tentang bagaimana
untuk memecahkan masalah—saat Anda merencanakan program komputer Anda.

## 1.1 Program Komputer
---
Anda mungkin pernah menggunakan komputer untuk bekerja atau bersenang-senang. Banyak orang menggunakan komputer untuk tugas sehari-hari seperti perbankan elektronik atau menulis makalah. Komputer adalah baik untuk tugas-tugas seperti itu. Mereka dapat menangani tugas berulang, seperti menjumlahkan angka atau menempatkan kata-kata di halaman, tanpa merasa bosan atau lelah.

Fleksibilitas komputer adalah fenomena yang cukup menakjubkan. Mesin yang sama dapat menyeimbangkan buku cek Anda, meletakkan kertas istilah Anda, dan bermain game. Sebaliknya, mesin lain melakukan berbagai tugas yang jauh lebih sempit; mobil yang dikendarai dan pemanggang roti bersulang. Komputer dapat melakukan berbagai tugas karena mereka menjalankan tugas yang berbeda program, yang masing-masing mengarahkan komputer untuk bekerja pada tugas tertentu.

Komputer itu sendiri adalah mesin yang menyimpan data (angka, kata-kata, gambar), berinteraksi dengan perangkat (monitor, sistem suara, printer), dan menjalankan program. Sebuah program komputer memberi tahu komputer, secara rinci, urutan langkah-langkah yang diperlukan untuk memenuhi tugas. Komputer fisik dan perangkat periferal secara kolektif disebut perangkat keras. Program yang dijalankan komputer disebut barang lunak.
Program komputer saat ini sangat canggih sehingga sulit dipercaya bahwa mereka terdiri dari instruksi yang sangat primitif. Instruksi tipikal mungkin satu dari berikut ini:

- Letakkan titik merah pada posisi layar tertentu.
- Tambahkan dua angka.
- Jika nilai ini negatif, lanjutkan program pada instruksi tertentu.

Pengguna komputer memiliki ilusi interaksi yang lancar karena sebuah program berisi sejumlah besar instruksi semacam itu, dan karena komputer dapat mengeksekusinya di kecepatan luar biasa.

Tindakan merancang dan mengimplementasikan program komputer disebut pemrograman. Dalam buku ini, Anda akan belajar cara memprogram komputer yaitu cara mengarahkan komputer untuk menjalankan tugas.
Untuk menulis game komputer dengan efek gerakan dan suara atau pengolah kata yang mendukung font dan gambar mewah adalah tugas kompleks yang membutuhkan tim yang terdiri dari banyak orang programmer yang sangat terampil. Upaya pemrograman pertama Anda akan lebih biasa. Konsep dan keterampilan yang Anda pelajari dalam buku ini membentuk fondasi penting, dan Anda tidak boleh kecewa jika program pertama Anda tidak menyaingi sophis ticated perangkat lunak yang akrab bagi Anda. Sebenarnya, Anda akan menemukan bahwa ada sensasi yang luar biasa bahkan dalam tugas pemrograman sederhana. Ini adalah pengalaman yang luar biasa untuk melihat komputerdengan tepat dan cepat melaksanakan tugas yang akan memakan waktu berjam-jam kerja keras, untuk membuat perubahan kecil dalam program yang mengarah pada perbaikan segera, dan untuk melihat komputer menjadi perpanjangan dari kekuatan mental Anda.

1. Apa yang diperlukan untuk memutar musik di komputer?
2. Mengapa pemutar CD kurang fleksibel dibandingkan komputer?
3. Mengapa pemutar CD kurang fleksibel dibandingkan komputer?

## 1.2 Anatomi Komputer

Untuk memahami proses pemrograman, Anda harus memiliki pemahaman dasar dari blok bangunan yang membentuk komputer. Kami akan melihat secara pribadi komputer. Komputer yang lebih besar memiliki komponen yang lebih cepat, lebih besar, atau lebih kuat, tetapimereka pada dasarnya memiliki desain yang sama.

Di jantung komputer terletak pusatnyaunit pemrosesan (CPU) (lihat Gambar 1). Bagian dalam pengkabelan CPU sangat rumit.Misalnya, prosesor Intel Core (populer CPU untuk per komputer pribadi pada saat tulisan ini) terdiri dari beberapa ratus juta elemen struktural, yang disebut transistor.

CPU melakukan kontrol program dan data pengolahan. Artinya, CPU menempatkan dan mengeksekusi instruksi program; itu melaksanakan operasi aritmatika seperti penjumlahan, pengurangan,perkalian, dan pembagian; itu mengambil datadari memori eksternal atau perangkat dan tempatdata yang diproses ke dalam penyimpanan.

Ada dua macam penyimpanan. Penyimpanan utama,atau memori, dibuat dari sirkuit elektronik yang dapat menyimpan data, asalkan:disuplai dengan tenaga listrik. Penyimpanan sekunder, biasanya hard disk (lihat Gambar 2)atau solid-state drive, menyediakan penyimpanan yang lebih lambat dan lebih murah yang bertahan tanpa listrik. Sebuah hard disk terdiri dari piringan berputar, yang dilapisi dengan magnetnbahan. Solid-state drive menggunakan komponen elektronik yang dapat menyimpan informasitanpa daya, dan tanpa bagian yang bergerak.

Untuk berinteraksi dengan pengguna manusia, komputer membutuhkan perangkat periferal. Komputer mentransmisikan informasi (disebut output) kepada pengguna melalui layar tampilan, speaker, dan printer. Pengguna dapat memasukkan informasi (disebut input) untuk komputerdengan menggunakan keyboard atau alat penunjuk seperti mouse.

Beberapa komputer adalah unit mandiri, sedangkan yang lain saling berhubungan melalui jaringan. Melalui kabel jaringan, komputer dapat membaca data dan program dari lokasi penyimpanan pusat atau mengirim data ke komputer lain. Untuk penggunadari komputer jaringan, bahkan mungkin tidak jelas data mana yang berada di komputeritu sendiri dan yang ditransmisikan melalui jaringan.

Gambar 3 memberikan gambaran skematis arsitektur komputer pribadi. Instruksi dan data program (seperti teks, angka, audio, atau video) berada di sekunder penyimpanan atau di tempat lain di jaringan. Ketika sebuah program dimulai, instruksinyadibawa ke memori, di mana CPU dapat membacanya. CPU membaca dan mengeksekusi satu instruksi pada suatu waktu. Seperti yang diarahkan oleh instruksi ini, CPU membacadata, memodifikasinya, dan menulisnya kembali ke memori atau penyimpanan sekunder. Beberapa programinstruksi akan menyebabkan CPU menempatkan titik-titik pada layar tampilan atau printer atau kegetaran speakernya. Karena tindakan ini terjadi berkali-kali dan dengan kecepatan tinggi,pengguna manusia akan melihat gambar dan suara. Beberapa instruksi program membaca penggunamasukan dari keyboard, mouse, sensor sentuh, atau mikrofon. Analisis programsifat input ini dan kemudian mengeksekusi instruksi yang sesuai berikutnya.

4. Di mana program disimpan saat sedang tidak berjalan?
5. Bagian komputer mana yang melakukan operasi aritmatika, seperti penjumlahan dan perkalian?
6. Smartphone modern adalah komputer, sebanding dengan komputer desktop. Yang komponen smartphone sesuai dengan yang ditunjukkan pada Gambar 3?

### _Komputasi & Masyaakat 1.1_ ** Komputer Dimana-mana
---
Ketika komputer pertama kali ditemukan pada tahun 1940-an, komputer memenuhi seluruh ruangan.  Foto di bawah menunjukkan ENIAC (integrator numerik elektronik dan komputer), selesai pada tahun 1946 di University of Pennsylvania.  ENIAC digunakan oleh militer untuk menghitung lintasan proyektil.  Saat ini, fasilitas komputasi mesin pencari, toko internet, dan jejaring sosial memenuhi gedung-gedung besar yang disebut pusat data.  Di ujung lain spektrum, komputer ada di sekitar kita.  Ponsel Anda memiliki komputer di dalamnya, seperti halnya banyak kartu kredit dan kartu tarif untuk angkutan umum.  Sebuah mobil modern memiliki beberapa komputer––untuk mengontrol mesin, rem, lampu, dan radio.

Munculnya komputasi di mana-mana berubah banyak aspek dari kami hidup.  Pabrik digunakan mempekerjakan orang untuk lakukan perakitan berulang tugas-tugas yang hari ini dilakukan oleh komputer- robot yang dikendalikan, operasi dimakan oleh segelintir orang siapa yang tahu caranya bekerja dengan komputer.  Buku, musik, dan film saat ini sering dikonsumsi di komputer, dan komputer hampir selalu terlibat dalam produksi mereka.  Buku yang sedang Anda baca sekarang tidak mungkin ditulis tanpa komputer. 

Mengetahui tentang komputer dan cara memprogramnya telah menjadi keterampilan penting dalam banyak karier.  Insinyur merancang mobil yang dikendalikan komputer dan peralatan medis yang menyelamatkan nyawa.  Ilmuwan komputer mengembangkan program yang membantu orang berkumpul untuk mendukung tujuan sosial.  Misalnya, para aktivis menggunakan jejaring sosial untuk berbagi video yang menunjukkan pelecehan oleh rezim yang represif, dan informasi ini berperan penting dalam mengubah opini publik. 

Ketika komputer, besar dan kecil, menjadi semakin tertanam dalam kehidupan kita sehari-hari, semakin penting bagi setiap orang untuk memahami cara kerjanya, dan cara bekerja dengannya.  Saat Anda menggunakan buku ini untuk mempelajari cara memprogram komputer, Anda akan mengembangkan pemahaman yang baik tentang dasar-dasar komputasi yang akan membuat Anda menjadi warga negara yang lebih berpengetahuan dan, mungkin, seorang profesional komputasi.

## 1.3 Bahasa Pemrogramman Java
---
Untuk menulis program komputer, Anda perlu memberikan urutan instruksi yang dapat dieksekusi oleh CPU. Sebuah program komputer terdiri dari sejumlah besar program instruksi CPU sederhana, dan membosankan juga rawan untuk kesalahan untuk menentukannya satu persatu. Karena alasan itu, bahasa pemrograman tingkat tinggi telah dibuat. Dalam bahasa tingkat tinggi, Anda menentukan tindakan yang harus dilakukan programnya. Penyusun menerjemahkan instruksi tingkat tinggi ke dalam instruksi yang lebih rinci (disebut kode mesin) yang dibutuhkan oleh CPU. Banyak bahasa pemrograman yang berbeda telah dirancang untuk tujuan yang berbeda.

Pada tahun 1991, sebuah kelompok yang dipimpin oleh James Gosling dan Patrick Naughton di Sun Microsystems merancang sebuah bahasa pemrograman, berkode nama “Green”, untuk kegunaan di perangkat konsumen, seperti “set-top” televisi cerdas. Bahasanya dirancang untuk sederhana, aman, dan dapat digunakan oleh berbagai tipe prosesor yang berbeda. Tidak ada pelanggan yang pernah ditemukan untuk teknologi ini.

Gosling menceritakan pada tahun 1994 tim menyadari “Kita bisa menulis browser yang sangat keren. Itu adalah salah satu dari sedikit hal dalam arus utama klien/server yang membutuhkan beberapa hal aneh yang telah kami lakukan: arsitektur netral, waktu nyata, andal, aman.” Java diperkenalkan kepada orang banyak yang antusias di pameran SunWorld pada tahun 1995, bersama dengan browser yang menjalankan applet—kode Java yang dapat ditemukan di mana saja di Internet. Gambar di sebelah kanan menunjukkan contoh khas applet.

Sejak saat itu, Java telah berkembang dengan kecepatan yang fenomenal. Programmer telah menggunakan bahasa ini karena lebih mudah digunakan daripada saingan terdekatnya, C++. Selain itu, Java memiliki perpustakaan yang kaya yang memungkinkan untuk menulis program portabel yang dapat melewati sistem operasi berpemilik—fitur yang sangat dicari oleh mereka yang ingin menjadi independen dari sistem berpemilik tersebut dan diperjuangkan dengan sengit oleh vendor mereka.

Karena Java dirancang untuk internet, ia mempunyai dua atrbut yang membuatnya sangat cocok untuk pemula: keamanan dan portabilitas.

![]()

Java dirancang sehingga siapapun dapat menjalankan program di browser mereka tanpa takut. Fitur keamanan bahasa Java memastikan program dihentikan apabila mencoba untuk melakukan sesuatu membahayakan. Memiliki lingkungan yang aman juga membantu bagi siapapun yang mempelajari Java. Disaat Anda melakukan error yang mengakibatkan perilaku membahayakan, program Anda dihentikan dan Anda menerima laporan eror yang akurat.

Manfaat lain dari Java adalah portabilitas. Program Java yang sama akan jalan, tanpa perubahan, pada Windows, UNIX, Linux, atau Macintosh. Untuk mencapai portabilitas, penyusun Java tidak menerjemahkan program-program Java langsung ke dalam instruksi CPU. Melainkan, program Java yang tersusun memuat instruksi untuk mesin virtual Java, sebuah program yang menyimulasikan CPU nyata. Portabilitas adalah manfaat lain untuk murid pemula. Anda tidak harus belajar bagaimana cara menulis program untuk platform yang berbeda.

Saat ini, Java telah ditetapkan sebagai salah satu bahasa yang paling penting untuk pemrograman umum serta untuk instruksi ilmu komputer. Namun, meskipun Java adalah bahasa yang baik untuk pemula, tapi tidak sempurna, karena tiga alasan.

Karena Java tidak dirancang khusus untuk siswa, tidak ada pemikiran yang diberikan untuk membuatnya sangat sederhana untuk menulis program dasar. Sejumlah mesin teknis diperlukan untuk menulis bahkan program yang paling sederhana. Hal ini bukan masalah bagi programmer profesional, tetapi bisa menjadi gangguan bagi pelajar pemula. Saat Anda mempelajari caranya untuk memprogram di Java, akan ada saatnya Anda akan diminta untuk puas dengan penjelasan awal dan menunggu detail yang lebih lengkap di bab selanjutnya.

Java telah diperpanjang berkali-kali selama masa pakainya—lihat Table 1. Dalam buku ini, kami menganggap bahwa Anda memiliki Java versi 8 atau yang lebih baru.

Pada akhirnya, Anda tidak dapat berharap untuk mempelajari keseluruhan dari Java dalam satu pembelajaran. Bahasa Java itu sendiri relatif sederhana, tapi Java berisi sekumpulan library packages yang diperlukan untuk menulis program yang berguna. Ada paket untuk grafik, desain antarmuka pengguna, kriptografi, jaringan, suara, penyimpanan basis data, dan banyak kegunaan lainnya. Bahkan programmer Java yang ahli sekalipun tidak dapat berharap untuk mengetahui isi semua paket—mereka hanya menggunakan yang mereka perlukan untuk proyek tertentu.

Dengan  menggunakan buku ini, Anda diharapkan untuk belajar banyak tentang bahasa Java dan tentang paket yang paling penting. Camkan selalu bahwa tujuan utama dari buku ini bukan untuk Anda mengingat detail kecil Java, tapi untuk mengajari Anda cara berpikir tentang pemrograman.

7. Apa dua manfaat terpenting dari bahasa Java?
8. Berapa lama untuk mempelajari seluruh perpustakaan Java?

## 1.4 MENJADI AKRAB DENGAN LINGKUNGAN PEMROGRAMAN ANDA

Banyak siswa menemukan bahwa alat yang mereka butuhkan sebagai pemrogram sangat berbeda dari perangkat lunak yang mereka kenal. Anda harus meluangkan waktu untuk membiasakan diri dengan lingkungan pemrograman Anda. Karena sistem komputer sangat bervariasi, buku ini hanya dapat memberikan garis besar langkah-langkah yang perlu Anda ikuti. Merupakan ide bagus untuk Anda berpartisipasi dalam lab praktik, atau meminta teman yang berpengetahuan luas untuk memberi Anda penjelasan.

Langkah1 Mulai lingkungan pengembangan Java.

Sistem komputer sangat berbeda dalam hal ini. Pada banyak komputer terdapat lingkungan pengembangan terintegrasi di mana Anda dapat menulis dan menguji program Anda.

Di komputerAnda pertama kali meluncurkan editor, sebuah program yang berfungsi seperti pengolah kata, di mana Anda dapat memasukkan instruksi Java Anda; Anda kemudian membuka jendela konsol dan ketik perintah untuk menjalankan program Anda. Anda perlu mencari tahu bagaimana memulai dengan lingkungan Anda.

Langkah2Tulis sebuah program yang sederhana.

Pilihan tradisional untuk program pertama dalam bahasa pemrograman baru adalah program yang menampilkan sapaan sederhana: 

“Halo, Dunia!”. Mari kita ikuti tradisi itu. Inilah "Halo, Dunia!" program di java:

publicclassHelloPrinter

{

publicstaticvoidmain(String[]args)

{

System.out.println("Hello,World!");

}

}

Kami akan memeriksa program ini di bagian selanjutnya.

Apa pun lingkungan pemrograman yang Anda gunakan, Anda memulai aktivitas Anda dengan mengetikkan pernyataan program ke dalam jendela editor.

Buat file baru dan beri namaHelloPrinter.java, menggunakan langkah-langkah yang sesuai untuk lingkungan Anda. (Jika lingkungan Anda mengharuskan Anda memberikan nama proyek selain nama file, gunakan namahello untuk proyek tersebut.) Masukkan instruksi program persis seperti yang diberikan di atas. Atau, temukan salinan elektronik dalam kode pendamping buku ini dan tempelkan ke editor Anda.

Saat Anda menulis program ini, perhatikan baik-baik berbagai simbol, dan ingatlah bahwa Java sensitif terhadap huruf besar-kecil. Anda harus memasukkan huruf besar dan kecil persis seperti yang muncul dalam daftar program. Anda tidak dapat mengetikMAIN atauPrintLn. Jika Anda tidak hati-hati, Anda akan mengalami masalah—lihat Kesalahan Umum 1.2.

Langkah3 Jalankan programnya.

Proses untuk menjalankan program sangat bergantung pada lingkungan pemrograman Anda. Anda mungkin harus mengklik tombol atau memasukkan beberapa perintah. Saat Anda menjalankan program pengujian, pesannya.

Hello,World!

akan muncul di suatu tempat di layar (lihat Gambar 4 dan Gambar 5).

Untuk menjalankan program Anda, kompiler Java menerjemahkan file sumber Anda (yaitu, pernyataan yang Anda tulis) ke dalam file kelas. (Sebuah file kelas berisi instruksi untuk mesin virtual Java.) Setelah kompilator menerjemahkan kode sumber Anda ke dalam instruksi mesin virtual, mesin virtual akan mengeksekusinya. Selama eksekusi, mesin virtual mengakses pustaka kode yang telah ditulis sebelumnya, termasuk implementasi kelasSystem danPrintStream yang diperlukan untuk menampilkan keluaran program. Gambar 6 merangkum proses membuat dan menjalankan program Java. Di beberapa lingkungan pemrograman, kompilator dan mesin virtual pada dasarnya tidak terlihat oleh pemrogram—mereka dijalankan secara otomatis setiap kali Anda meminta untuk menjalankan program Java. Di lingkungan lain, Anda perlu meluncurkan kompiler dan mesin virtual secara eksplisit.

Langkah4 Rapikan pekerjaamu.

Sebagai seorang programmer, Anda menulis program, mencobanya, dan memperbaikinya. Anda menyimpan program Anda dalam file. File disimpan dalam folder atau direktori. Sebuah folder dapat berisi

file serta folder lain, yang dengan sendirinya dapat berisi lebih banyak file dan folder 
(lihat Gambar 7). Hirarki ini bisa sangat besar, dan Anda tidak perlu khawatir dengan semua cabangnya. Namun, Anda harus membuat folder untuk mengatur pekerjaan Anda. Sebaiknya buat folder terpisah untuk pro-tugas mata kuliah tata bahasa. Di dalam folder itu, buat folder terpisah untuk setiap program.

Beberapa lingkungan pemrograman menempatkan program Anda ke lokasi default jika Anda tidak menentukan folder sendiri. Dalam hal ini, Anda perlu mencari tahu di mana file-file itu berada.

Pastikan Anda memahami di mana file Anda berada dalam hierarki folder. Informasi ini penting ketika Anda mengirimkan file untuk penilaian, danuntukmembuat salinan cadangan (lihat Tip Pemrograman 1.1). 

