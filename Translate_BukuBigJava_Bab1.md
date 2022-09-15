![](https://user-images.githubusercontent.com/112606990/190147579-49ee998b-3305-4338-9889-ae661eb20967.png)

Nama : Fatimah Azzahra Maulida

NIM : 2110131220020

---

## `BAB` 1 
# PENGENALAN

`CHAPTER GOALS`

`TUJUAN BAB`

To learn about computers and programming

Untuk belajar tentang komputer dan pemrograman

To compile and run your first Java program

Untuk mengkompilasi dan menjalankan program Java pertama Anda

To recognize compile-time and run-time errors

Untuk mengenali kesalahan waktu kompilasi dan run-time

To describe an algorithm with pseudocode

Untuk menggambarkan suatu algoritma dengan pseudocode

`CHAPTER CONTENTS`

`ISI BAB`

**1.1 COMPUTER PROGRAMS** 2

**1.1 PROGRAM KOMPUTER** 2

**1.2 THE ANATOMY OF A COMPUTER** 3

**1.2 ANATOMI KOMPUTER** 3

##### C&S Computers Are Everywhere 5

##### C&S Komputer Ada Dimana-mana 5

**1.3 THE JAVA PROGRAMMING LANGUAGE** 6

**1.3 PEMROGRAMAN JAVA BAHASA** 6

**1.4 BECOMING FAMILIAR WITH YOUR PROGRAMMING ENVIRONMENT** 7

**1.4 MENJADI AKRAB DENGAN LINGKUNGAN PEMROGRAMAN ANDA** 7

#### PT1 Backup Copies 10

#### PT1 Salinan Cadangan 10

**1.5 ANALYZING YOUR FIRST PROGRAM** 11

**1.5 MENGANALISIS PROGRAM PERTAMA ANDA** 11

#### SYN Java Program 12

#### Program Java 12

#### CE1 Omitting Semicolons 13

#### Menghilangkan Titik Koma 13

**1.6 ERRORS** 14

**1.6 KESALAHAN** 14

#### CE2 Misspelling Words 15

#### CE2 Kata-kata yang salah eja 15

**1.7 PROBLEM SOLVING: ALGORITHM DESIGN** 15

**1.7 PENYELESAIAN MASALAH: DESAIN ALGORITMA** 15

#### HT1 Describing an Algorithm with Pseudocode 19

#### HT 1 Mendeskripsikan Algoritma dengan kode semu 19

#### WE 1 Writing an Algorithm for Tiling a Floor 21

#### WE 1 Kode semu 19 WE1 Menulis untuk Ubin Lantai 21

Just as you gather tools, study a project, and make a plan for 
tackling it, in this chapter you will gather up the basics you 
need to start learning to program. After a brief introduction 
to computer hardware, software, and programming in 
general, you will learn how to write and run your first 
Java program. You will also learn how to diagnose and 
fix programming errors, and how to use pseudocode to 
describe an algorithm—a step-by-step description of how 
to solve a problem—as you plan your computer programs.

Sama seperti Anda mengumpulkan alat, mempelajari proyek, dan membuat rencana untuk
mengatasinya, dalam bab ini Anda akan mengumpulkan dasar-dasar yang Anda
perlukan untuk mulai belajar memprogram. Setelah perkenalan singkat
perangkat keras komputer, perangkat lunak, dan pemrograman dalam
umum, Anda akan belajar cara menulis dan menjalankan yang pertama
program Java. Anda juga akan belajar cara mendiagnosis dan
memperbaiki kesalahan pemrograman, dan cara menggunakan kode semu untuk
menggambarkan suatu algoritme—deskripsi langkah demi langkah tentang bagaimana
untuk memecahkan masalah—saat Anda merencanakan program komputer Anda.

## **1.1 Computer Programs**

## **1.1 Program Komputer**
---

You have probably used a computer for work or fun. Many people use computers 
for everyday tasks such as electronic banking or writing a term paper. Computers are 
good for such tasks. They can handle repetitive chores, such as totaling up numbers 
or placing words on a page, without getting bored or exhausted. 

Anda mungkin pernah menggunakan komputer untuk bekerja atau bersenang-senang. Banyak orang menggunakan komputer untuk tugas sehari-hari seperti perbankan elektronik atau menulis makalah. Komputer adalah baik untuk tugas-tugas seperti itu. Mereka dapat menangani tugas berulang, seperti menjumlahkan angka atau menempatkan kata-kata di halaman, tanpa merasa bosan atau lelah.

The flexibility of a computer is quite an amazing phenomenon. The same machine 
can balance your checkbook, lay out your term paper, and play a game. In contrast, 
other machines carry out a much narrower range of tasks; a car drives and a toaster 
toasts. Computers can carry out a wide range of tasks because they execute different 
programs, each of which directs the computer to work on a specific task.

Fleksibilitas komputer adalah fenomena yang cukup menakjubkan. Mesin yang sama dapat menyeimbangkan buku cek Anda, meletakkan kertas istilah Anda, dan bermain game. Sebaliknya, mesin lain melakukan berbagai tugas yang jauh lebih sempit; mobil yang dikendarai dan pemanggang roti bersulang. Komputer dapat melakukan berbagai tugas karena mereka menjalankan tugas yang berbeda program, yang masing-masing mengarahkan komputer untuk bekerja pada tugas tertentu.

The computer itself is a machine that stores data (numbers, words, pictures), interacts with devices (the monitor, the sound system, the printer), and executes programs. 
A **computer program** tells a computer, in minute detail, the sequence of steps that are 
needed to fulfill a task. The physical computer and peripheral devices are collectively 
called the **hardware**. The programs the computer executes are called the **software**.

Komputer itu sendiri adalah mesin yang menyimpan data (angka, kata-kata, gambar), berinteraksi dengan perangkat (monitor, sistem suara, printer), dan menjalankan program. Sebuah **program komputer** memberi tahu komputer, secara rinci, urutan langkah-langkah yang diperlukan untuk memenuhi tugas. Komputer fisik dan perangkat periferal secara kolektif disebut **perangkat keras**. Program yang dijalankan komputer disebut **perangkat lunak**.

Today’s computer programs are so sophisticated that it is hard to believe that they 
are composed of extremely primitive instructions. A typical instruction may be one 
of the following:

Program komputer saat ini sangat canggih sehingga sulit dipercaya bahwa mereka terdiri dari instruksi yang sangat primitif. Instruksi tipikal mungkin satu dari berikut ini:

- Put a red dot at a given screen position.
- Add up two numbers.
- If this value is negative, continue the program at a certain instruction.

- Letakkan titik merah pada posisi layar tertentu.
- Tambahkan dua angka.
- Jika nilai ini negatif, lanjutkan program pada instruksi tertentu.

The computer user has the illusion of smooth interaction because a program contains 
a huge number of such instructions, and because the computer can execute them at 
great speed.

Pengguna komputer memiliki ilusi interaksi yang lancar karena sebuah program berisi sejumlah besar instruksi semacam itu, dan karena komputer dapat mengeksekusinya di kecepatan luar biasa.

The act of designing and implementing computer programs is called **programming**. In this book, you will learn how to program a computer—that is, how to direct 
the computer to execute tasks.

Tindakan merancang dan mengimplementasikan program komputer disebut **pemrograman**. Dalam buku ini, Anda akan belajar cara memprogram komputer yaitu cara mengarahkan komputer untuk menjalankan tugas.

To write a computer game with motion and sound effects or a word processor 
that supports fancy fonts and pictures is a complex task that requires a team of many 
highly-skilled programmers. Your first programming efforts will be more mundane. 
The concepts and skills you learn in this book form an important foundation, and 
you should not be disappointed if your first programs do not rival the sophisticated 
software that is familiar to you. Actually, you will find that there is an immense thrill 
even in simple programming tasks. It is an amazing experience to see the computer 
precisely and quickly carry out a task that would take you hours of drudgery, to make small changes in a program that lead to immediate improvements, and to see the 
computer become an extension of your mental powers.

Untuk menulis game komputer dengan efek gerakan dan suara atau pengolah kata yang mendukung font dan gambar mewah adalah tugas kompleks yang membutuhkan tim yang terdiri dari banyak orang programmer yang sangat terampil. Upaya pemrograman pertama Anda akan lebih biasa. Konsep dan keterampilan yang Anda pelajari dalam buku ini membentuk fondasi penting, dan Anda tidak boleh kecewa jika program pertama Anda tidak menyaingi sophis ticated perangkat lunak yang akrab bagi Anda. Sebenarnya, Anda akan menemukan bahwa ada sensasi yang luar biasa bahkan dalam tugas pemrograman sederhana. Ini adalah pengalaman yang luar biasa untuk melihat komputerdengan tepat dan cepat melaksanakan tugas yang akan memakan waktu berjam-jam kerja keras, untuk membuat perubahan kecil dalam program yang mengarah pada perbaikan segera, dan untuk melihat komputer menjadi perpanjangan dari kekuatan mental Anda.

1. What is required to play music on a computer? 
2. Why is a CD player less flexible than a computer? 
3. What does a computer user need to know about programming in order to play a video game?

1. Apa yang diperlukan untuk memutar musik di komputer?
2. Mengapa pemutar CD kurang fleksibel dibandingkan komputer?
3. Mengapa pemutar CD kurang fleksibel dibandingkan komputer?

## **1.2 The Anatomy of a Computer**

## **1.2 Anatomi Komputer**

To understand the programming process, you need to have a rudimentary understanding of the building blocks that make up a computer. We will look at a personal 
computer. Larger computers have faster, larger, or more powerful components, but 
they have fundamentally the same design.

Untuk memahami proses pemrograman, Anda harus memiliki pemahaman dasar dari blok bangunan yang membentuk komputer. Kami akan melihat secara pribadi komputer. Komputer yang lebih besar memiliki komponen yang lebih cepat, lebih besar, atau lebih kuat, tetapimereka pada dasarnya memiliki desain yang sama.

At the heart of the computer lies the **central 
processing unit (CPU)** (see Figure 1). The inside 
wiring of the CPU is enormously complicated. 
For example, the Intel Core processor (a popular 
CPU for personal computers at the time of this 
writing) is composed of several hundred million 
structural elements, called transistors.

Di jantung komputer terletak **pusatnya unit pemrosesan (CPU)** (lihat Gambar 1). Bagian dalam pengkabelan CPU sangat rumit.Misalnya, prosesor Intel Core (populer CPU untuk per komputer pribadi pada saat tulisan ini) terdiri dari beberapa ratus juta elemen struktural, yang disebut transistor.

![a](https://user-images.githubusercontent.com/112606990/190206386-2afad0cf-5ede-4908-bdb7-482407223d24.jpg)

The CPU performs program control and 
data processing. That is, the CPU locates and 
executes the program instructions; it carries out 
arithmetic operations such as addition, subtraction, multiplication, and division; it fetches data 
from external memory or devices and places 
processed data into storage.

CPU melakukan kontrol program dan data pengolahan. Artinya, CPU menempatkan dan mengeksekusi instruksi program; itu melaksanakan operasi aritmatika seperti penjumlahan, pengurangan,perkalian, dan pembagian; itu mengambil datadari memori eksternal atau perangkat dan tempatdata yang diproses ke dalam penyimpanan.

There are two kinds of storage. Primary storage, or memory, is made from electronic circuits that can store data, provided they are 
supplied with electric power. **Secondary storage**, usually a **hard disk** (see Figure 2)
or a solid-state drive, provides slower and less expensive storage that persists without electricity. A hard disk consists of rotating platters, which are coated with a magnetic material. A solid-state drive uses electronic components that can retain information 
without power, and without moving parts.

Ada dua macam penyimpanan. Penyimpanan utama,atau memori, dibuat dari sirkuit elektronik yang dapat menyimpan data, asalkan:disuplai dengan tenaga listrik. **Penyimpanan sekunder**, biasanya **hard disk** (lihat Gambar 2)atau solid-state drive, menyediakan penyimpanan yang lebih lambat dan lebih murah yang bertahan tanpa listrik. Sebuah hard disk terdiri dari piringan berputar, yang dilapisi dengan magnetnbahan. Solid-state drive menggunakan komponen elektronik yang dapat menyimpan informasitanpa daya, dan tanpa bagian yang bergerak.

![s](https://user-images.githubusercontent.com/112606990/190206463-cdd9f999-d69f-403b-8d3e-062fda35358d.jpg)

To interact with a human user, a computer requires peripheral devices. The computer transmits information (called output) to the user through a display screen, 
speakers, and printers. The user can enter information (called input) for the computer 
by using a keyboard or a pointing device such as a mouse.

Untuk berinteraksi dengan pengguna manusia, komputer membutuhkan perangkat periferal. Komputer mentransmisikan informasi (_disebut output_) kepada pengguna melalui layar tampilan, speaker, dan printer. Pengguna dapat memasukkan informasi (_disebut input_) untuk komputerdengan menggunakan keyboard atau alat penunjuk seperti mouse.

Some computers are self-contained units, whereas others are interconnected 
through **networks**. Through the network cabling, the computer can read data and 
programs from central storage locations or send data to other computers. To the user 
of a networked computer, it may not even be obvious which data reside on the computer itself and which are transmitted through the network. 

Beberapa komputer adalah unit mandiri, sedangkan yang lain saling berhubungan melalui **jaringan**. Melalui kabel jaringan, komputer dapat membaca data dan program dari lokasi penyimpanan pusat atau mengirim data ke komputer lain. Untuk penggunadari komputer jaringan, bahkan mungkin tidak jelas data mana yang berada di komputeritu sendiri dan yang ditransmisikan melalui jaringan.

Figure 3 gives a schematic overview of the architecture of a personal computer. 
Program instructions and data (such as text, numbers, audio, or video) reside in secondary storage or elsewhere on the network. When a program is started, its instructions are brought into memory, where the CPU can read them. The CPU reads and 
executes one instruction at a time. As directed by these instructions, the CPU reads 
data, modifies it, and writes it back to memory or secondary storage. Some program 
instructions will cause the CPU to place dots on the display screen or printer or to 
vibrate the speaker. As these actions happen many times over and at great speed, the 
human user will perceive images and sound. Some program instructions read user 
input from the keyboard, mouse, touch sensor, or microphone. The program analyzes the nature of these inputs and then executes the next appropriate instruction.

Gambar 3 memberikan gambaran skematis arsitektur komputer pribadi. Instruksi dan data program (seperti teks, angka, audio, atau video) berada di sekunder penyimpanan atau di tempat lain di jaringan. Ketika sebuah program dimulai, instruksinyadibawa ke memori, di mana CPU dapat membacanya. mbaca dan mengeksekusi satu instruksi pada suatu waktu. Seperti yang diarahkan oleh instruksi ini, CPU membacadata, memodifikasinya, dan menulisnya kembali ke memori atau penyimpanan sekunder. Beberapa programinstruksi akan menyebabkan CPU menempatkan titik-titik pada layar tampilan atau printer atau kegetaran speakernya. Karena tindakan ini terjadi berkali-kali dan dengan kecepatan tinggi,pengguna manusia akan melihat gambar dan suara. Beberapa instruksi program membaca penggunamasukan dari keyboard, mouse, sensor sentuh, atau mikrofon. Analisis programsifat input ini dan kemudian mengeksekusi instruksi yang sesuai berikutnya.

![d](https://user-images.githubusercontent.com/112606990/190206546-b7f07484-2952-4b66-ba3e-0e09072db48b.jpg)

4. Where is a program stored when it is not currently running?
5. Which part of the computer carries out arithmetic operations, such as addition and multiplication?
6. A modern smartphone is a computer, comparable to a desktop computer. Which components of a smartphone correspond to those shown in Figure 3?

4. Di mana program disimpan saat sedang tidak berjalan?
5. Bagian komputer mana yang melakukan operasi aritmatika, seperti penjumlahan dan perkalian?
6. Smartphone modern adalah komputer, sebanding dengan komputer desktop. Yang komponen smartphone sesuai dengan yang ditunjukkan pada Gambar 3?

### _Computing & Society 1.1_ **Computers Are Everywhere**

### _Komputasi & Masyaakat 1.1_ **Komputer Dimana-mana**
---

When computers 
were first invented 
in the 1940s, a computer filled an 
entire room. The photo below shows 
the ENIAC (electronic numerical integrator and computer), completed in 
1946 at the University of Pennsylvania. 
The ENIAC was used by the military to 
compute the trajectories of projectiles. 
Nowadays, computing facilities of 
search engines, Internet shops, and 
social networks fill huge buildings 
called data centers. At the other end of 
the spectrum, computers are all around 
us. Your cell phone has a computer 
inside, as do many credit cards and fare 
cards for public transit. A modern car 
has several computers––to control the 
engine, brakes, lights, and the radio.

Ketika komputer pertama kali ditemukan pada tahun 1940-an, komputer memenuhi seluruh ruangan.  Foto di bawah menunjukkan ENIAC (integrator numerik elektronik dan komputer), selesai pada tahun 1946 di University of Pennsylvania.  ENIAC digunakan oleh militer untuk menghitung lintasan proyektil.  Saat ini, fasilitas komputasi mesin pencari, toko internet, dan jejaring sosial memenuhi gedung-gedung besar yang disebut pusat data.  Di ujung lain spektrum, komputer ada di sekitar kita.  Ponsel Anda memiliki komputer di dalamnya, seperti halnya banyak kartu kredit dan kartu tarif untuk angkutan umum.  Sebuah mobil modern memiliki beberapa komputer––untuk mengontrol mesin, rem, lampu, dan radio.

The advent of ubiquitous computing changed 
many aspects of our 
lives. Factories used 
to employ people to 
do repetitive assembly 
tasks that are today 
carried out by computercontrolled robots, operated by a few people 
who know how to work 
with those computers. 
Books, music, and movies nowadays are often 
consumed on computers, and computers are 
almost always involved 
in their production. The book that you 
are reading right now could not have 
been written without computers.

Munculnya komputasi di mana-mana berubah banyak aspek dari kami hidup.  Pabrik digunakan mempekerjakan orang untuk lakukan perakitan berulang tugas-tugas yang hari ini dilakukan oleh komputer- robot yang dikendalikan, operasi dimakan oleh segelintir orang siapa yang tahu caranya bekerja dengan komputer.  Buku, musik, dan film saat ini sering dikonsumsi di komputer, dan komputer hampir selalu terlibat dalam produksi mereka.  Buku yang sedang Anda baca sekarang tidak mungkin ditulis tanpa komputer. 

Knowing about computers and 
how to program them has become 
an essential skill in many careers. 
Engineers design computer-controlled 
cars and medical equipment that 
preserve lives. Computer scientists 
develop programs that help people 
come together to support social 
causes. For example, activists used 
social networks to share videos 
showing abuse by repressive regimes, 
and this information was instrumental 
in changing public opinion.

Mengetahui tentang komputer dan cara memprogramnya telah menjadi keterampilan penting dalam banyak karier.  Insinyur merancang mobil yang dikendalikan komputer dan peralatan medis yang menyelamatkan nyawa.  Ilmuwan komputer mengembangkan program yang membantu orang berkumpul untuk mendukung tujuan sosial.  Misalnya, para aktivis menggunakan jejaring sosial untuk berbagi video yang menunjukkan pelecehan oleh rezim yang represif, dan informasi ini berperan penting dalam mengubah opini publik. 

As computers, large and small, 
become ever more embedded in our 
everyday lives, it is increasingly important for everyone to understand how 
they work, and how to work with them. 
As you use this book to learn how to 
program a computer, you will develop 
a good understanding of computing 
fundamentals that will make you a 
more informed citizen and, perhaps, 
a computing professional.

Ketika komputer, besar dan kecil, menjadi semakin tertanam dalam kehidupan kita sehari-hari, semakin penting bagi setiap orang untuk memahami cara kerjanya, dan cara bekerja dengannya.  Saat Anda menggunakan buku ini untuk mempelajari cara memprogram komputer, Anda akan mengembangkan pemahaman yang baik tentang dasar-dasar komputasi yang akan membuat Anda menjadi warga negara yang lebih berpengetahuan dan, mungkin, seorang profesional komputasi.

## **1.3 The Java Programming Language**

## **1.3 Bahasa Pemrogramman Java**
---

In order to write a computer program, you need to provide a sequence of instructions 
that the CPU can execute. A computer program consists of a large number of simple 
CPU instructions, and it is tedious and error-prone to specify them one by one. For 
that reason, **high-level programming languages** have been created. In a *high-level 
language*, you specify the actions that your program should carry out. A **compiler**
translates the high-level instructions into the more detailed instructions (called 
machine code)required by the CPU. Many different programming languages have 
been designed for different purposes.

Untuk menulis program komputer, Anda perlu memberikan urutan instruksi yang dapat dieksekusi oleh CPU. Sebuah program komputer terdiri dari sejumlah besar program instruksi CPU sederhana, dan membosankan juga rawan untuk kesalahan untuk menentukannya satu persatu. Karena alasan itu, **bahasa pemrograman tingkat tinggi** telah dibuat. Dalam bahasa tingkat tinggi, Anda menentukan tindakan yang harus dilakukan programnya. Penyusun menerjemahkan instruksi tingkat tinggi ke dalam instruksi yang lebih rinci (**disebut kode mesin**) yang dibutuhkan oleh CPU. Banyak bahasa pemrograman yang berbeda telah dirancang untuk tujuan yang berbeda.

In 1991, a group led by James Gosling and Patrick Naughton at Sun Microsystems 
designed a programming language, code-named “Green”, for use in consumer 
devices, such as intelligent television “set-top” boxes. The language was designed to 
be simple, secure, and usable for many different processor types. No customer was 
ever found for this technology.

Pada tahun 1991, sebuah kelompok yang dipimpin oleh James Gosling dan Patrick Naughton di Sun Microsystems merancang sebuah bahasa pemrograman, berkode nama “Green”, untuk kegunaan di perangkat konsumen, seperti “set-top” televisi cerdas. Bahasanya dirancang untuk sederhana, aman, dan dapat digunakan oleh berbagai tipe prosesor yang berbeda. Tidak ada pelanggan yang pernah ditemukan untuk teknologi ini.

Gosling recounts that in 1994 the team realized, 
“We could write a really cool browser. It was one 
of the few things in the client/server mainstream 
that needed some of the weird things we’d done: 
architecture neutral, real-time, reliable, secure.” 
Java was introduced to an enthusiastic crowd at 
the SunWorld exhibition in 1995, together with a 
browser that ran **applets**—Java code that can be 
located anywhere on the Internet. The figure at 
right shows a typical example of an applet.

Gosling menceritakan pada tahun 1994 tim menyadari “Kita bisa menulis browser yang sangat keren. Itu adalah salah satu dari sedikit hal dalam arus utama klien/server yang membutuhkan beberapa hal aneh yang telah kami lakukan: arsitektur netral, waktu nyata, andal, aman.” Java diperkenalkan kepada orang banyak yang antusias di pameran SunWorld pada tahun 1995, bersama dengan browser yang menjalankan **applets**—kode Java yang dapat ditemukan di mana saja di Internet. Gambar di sebelah kanan menunjukkan contoh khas applet.

Since then, Java has grown at a phenomenal rate. 
Programmers have embraced the language because 
it is easier to use than its closest rival, C++. In addition, Java has a rich **library** that 
makes it possible to write portable programs that can bypass proprietary operating 
systems—a feature that was eagerly sought by those who wanted to be independent 
of those proprietary systems and was bitterly fought by their vendors. A “micro edition” and an “enterprise edition” of the Java library allow Java programmers to target 
hardware ranging from smart cards to the largest Internet servers.

Sejak saat itu, Java telah berkembang dengan kecepatan yang fenomenal. Programmer telah menggunakan bahasa ini karena lebih mudah digunakan daripada saingan terdekatnya, C++. Selain itu, Java memiliki **perpustakaan** yang kaya yang memungkinkan untuk menulis program portabel yang dapat melewati sistem operasi berpemilik—fitur yang sangat dicari oleh mereka yang ingin menjadi independen dari sistem berpemilik tersebut dan diperjuangkan dengan sengit oleh vendor mereka.

Because Java was designed for the Internet, it has two attributes that make it very 
suitable for beginners: safety and portability.

Karena Java dirancang untuk internet, ia mempunyai dua atrbut yang membuatnya sangat cocok untuk pemula: keamanan dan portabilitas.

![ff](https://user-images.githubusercontent.com/112606990/190206656-bcdbf91e-03a0-447c-ab77-ed121498cbec.jpg)

Java was designed so that anyone can execute programs in their browser without 
fear. The safety features of the Java language ensure that a program is terminated if it 
tries to do something unsafe. Having a safe environment is also helpful for anyone 
learning Java. When you make an error that results in unsafe behavior, your program 
is terminated and you receive an accurate error report. 

Java dirancang sehingga siapapun dapat menjalankan program di browser mereka tanpa takut. Fitur keamanan bahasa Java memastikan program dihentikan apabila mencoba untuk melakukan sesuatu membahayakan. Memiliki lingkungan yang aman juga membantu bagi siapapun yang mempelajari Java. Disaat Anda melakukan error yang mengakibatkan perilaku membahayakan, program Anda dihentikan dan Anda menerima laporan eror yang akurat.

The other benefit of Java is portability. The same Java program will run, without 
change, on Windows, UNIX, Linux, or Macintosh. In order to achieve portability, 
the Java compiler does not translate Java programs directly into CPU instructions. 
Instead, compiled Java programs contain instructions for the Java **virtual machine**, 
a program that simulates a real CPU. Portability is another benefit for the beginning 
student. You do not have to learn how to write programs for different platforms.

Manfaat lain dari Java adalah portabilitas. Program Java yang sama akan jalan, tanpa perubahan, pada Windows, UNIX, Linux, atau Macintosh. Untuk mencapai portabilitas, penyusun Java tidak menerjemahkan program-program Java langsung ke dalam instruksi CPU. Melainkan, program Java yang tersusun memuat instruksi untuk **mesin virtual** Java, sebuah program yang menyimulasikan CPU nyata. Portabilitas adalah manfaat lain untuk murid pemula. Anda tidak harus belajar bagaimana cara menulis program untuk platform yang berbeda.

At this time, Java is firmly established as one of the most important languages for 
general-purpose programming as well as for computer science instruction. However, 
although Java is a good language for beginners, it is not perfect, for three reasons.

Saat ini, Java telah ditetapkan sebagai salah satu bahasa yang paling penting untuk pemrograman umum serta untuk instruksi ilmu komputer. Namun, meskipun Java adalah bahasa yang baik untuk pemula, tapi tidak sempurna, karena tiga alasan.

Because Java was not specifically designed for students, no thought was given to
making it really simple to write basic programs. A certain amount of technical machinery is necessary to write even the simplest programs. This is not a problem for professional programmers, but it can be a nuisance for beginning students. As you learn 
how to program in Java, there will be times when you will be asked to be satisfied with 
a preliminary explanation and wait for more complete detail in a later chapter.

Karena Java tidak dirancang khusus untuk siswa, tidak ada pemikiran yang diberikan untuk membuatnya sangat sederhana untuk menulis program dasar. Sejumlah mesin teknis diperlukan untuk menulis bahkan program yang paling sederhana. Hal ini bukan masalah bagi programmer profesional, tetapi bisa menjadi gangguan bagi pelajar pemula. Saat Anda mempelajari caranya untuk memprogram di Java, akan ada saatnya Anda akan diminta untuk puas dengan penjelasan awal dan menunggu detail yang lebih lengkap di bab selanjutnya.

Java has been extended many times during its life—see Table 1. In this book, we 
assume that you have Java version 7 or later.

Java telah diperpanjang berkali-kali selama masa pakainya—lihat Table 1. Dalam buku ini, kami menganggap bahwa Anda memiliki Java versi 8 atau yang lebih baru.

Finally, you cannot hope to learn all of Java in one course. The Java language itself 
is relatively simple, but Java contains a vast set of library packages that are required 
to write useful programs. There are packages for graphics, user-interface design, 
cryptography, networking, sound, database storage, and many other purposes. Even 
expert Java programmers cannot hope to know the contents of all of the packages—
they just use those that they need for particular projects. 

Pada akhirnya, Anda tidak dapat berharap untuk mempelajari keseluruhan dari Java dalam satu pembelajaran. Bahasa Java itu sendiri relatif sederhana, tapi Java berisi sekumpulan library packages yang diperlukan untuk menulis program yang berguna. Ada paket untuk grafik, desain antarmuka pengguna, kriptografi, jaringan, suara, penyimpanan basis data, dan banyak kegunaan lainnya. Bahkan programmer Java yang ahli sekalipun tidak dapat berharap untuk mengetahui isi semua paket—mereka hanya menggunakan yang mereka perlukan untuk proyek tertentu.

Using this book, you should expect to learn a good deal about the Java language 
and about the most important packages. Keep in mind that the central goal of this 
book is not to make you memorize Java minutiae, but to teach you how to think 
about programming. 

Dengan  menggunakan buku ini, Anda diharapkan untuk belajar banyak tentang bahasa Java dan tentang paket yang paling penting. Camkan selalu bahwa tujuan utama dari buku ini bukan untuk Anda mengingat detail kecil Java, tapi untuk mengajari Anda cara berpikir tentang pemrograman.

7. What are the two most important benefits of the Java language? 
8. How long does it take to learn the entire Java library?

7. Apa dua manfaat terpenting dari bahasa Java?
8. Berapa lama untuk mempelajari seluruh perpustakaan Java?

## 1.4 Becoming Familiar with Your Programming Environment

## 1.4 MENJADI AKRAB DENGAN LINGKUNGAN PEMROGRAMAN ANDA

Many students find that the tools they need as programmers are very different from 
the software with which they are familiar. You should spend some time making yourself familiar with your programming environment. Because computer systems vary 
widely, this book can only give an outline of the steps you need to follow. It is a good 
idea to participate in a hands-on lab, or to ask a knowledgeable friend to give you a tour.

Banyak siswa menemukan bahwa alat yang mereka butuhkan sebagai pemrogram sangat berbeda dari perangkat lunak yang mereka kenal. Anda harus meluangkan waktu untuk membiasakan diri dengan lingkungan pemrograman Anda. Karena sistem komputer sangat bervariasi, buku ini hanya dapat memberikan garis besar langkah-langkah yang perlu Anda ikuti. Merupakan ide bagus untuk Anda berpartisipasi dalam lab praktik, atau meminta teman yang berpengetahuan luas untuk memberi Anda penjelasan.

![g](https://user-images.githubusercontent.com/112606990/190206766-8c22ecd8-da9c-474f-8e61-0160be3454dd.jpg)

Step 1 Start the Java development environment.

Langkah1 Mulai lingkungan pengembangan Java.

Sistem komputer sangat berbeda dalam hal ini. Pada banyak komputer terdapat **lingkungan pengembangan terintegrasi** di mana Anda dapat menulis dan menguji program Anda.

Computer systems differ greatly in this regard. On many computers there is an **integrated development environment** in which you can write and test your programs. 
On other computers you first launch an **editor**, a program that functions like a word 
processor, in which you can enter your Java instructions; you then open a console 
window and type commands to execute your program. You need to find out how to 
get started with your environment.

Di komputerAnda pertama kali meluncurkan **editor**, sebuah program yang berfungsi seperti pengolah kata, di mana Anda dapat memasukkan instruksi Java Anda; Anda kemudian membuka _jendela konsol_ dan ketik perintah untuk menjalankan program Anda. Anda perlu mencari tahu bagaimana memulai dengan lingkungan Anda.

Step 2 Write a simple program.

Langkah2Tulis sebuah program yang sederhana.

The traditional choice for the very first program in a new programming language is 
a program that displays a simple greeting: “Hello, World!”. Let us follow that tradition. Here is the “Hello, World!” program in Java:

Pilihan tradisional untuk program pertama dalam bahasa pemrograman baru adalah program yang menampilkan sapaan sederhana: 

“Halo, Dunia!”. Mari kita ikuti tradisi itu. Inilah "Halo, Dunia!" program di java:

public class HelloPrinter

publicclassHelloPrinter

{

{

 public static void main(String[] args)

publicstaticvoidmain(String[]args)

 { 

{

 System.out.println("Hello, World!");

System.out.println("Hello,World!");

 }

}

}

}

We will examine this program in the next section. 

Kami akan memeriksa program ini di bagian selanjutnya.

No matter which programming environment you use, you begin your activity by 
typing the program statements into an editor window.

Apa pun lingkungan pemrograman yang Anda gunakan, Anda memulai aktivitas Anda dengan mengetikkan pernyataan program ke dalam jendela editor.

Create a new file and call it HelloPrinter.java, using the steps that are appropriate 
for your environment. (If your environment requires that you supply a project name 
in addition to the file name, use the name hello for the project.) Enter the program 
instructions exactly as they are given above. Alternatively, locate the electronic copy 
in this book’s companion code and paste it into your editor.

Buat file baru dan beri namaHelloPrinter.java, menggunakan langkah-langkah yang sesuai untuk lingkungan Anda. (Jika lingkungan Anda mengharuskan Anda memberikan nama proyek selain nama file, gunakan namahello untuk proyek tersebut.) Masukkan instruksi program persis seperti yang diberikan di atas. Atau, temukan salinan elektronik dalam kode pendamping buku ini dan tempelkan ke editor Anda.

![h](https://user-images.githubusercontent.com/112606990/190206935-723bca9c-3ee5-46ac-bbcf-72f7dffcfcb9.jpg)

As you write this program, pay careful attention to the various symbols, and keep 
in mind that Java is **case sensitive**. You must enter upper- and lowercase letters exactly 
as they appear in the program listing. You cannot type MAIN or PrintLn. If you are not 
careful, you will run into problems—see Common Error 1.2 on page 15. 

Saat Anda menulis program ini, perhatikan baik-baik berbagai simbol, dan ingatlah bahwa Java **sensitif terhadap huruf besar-kecil**. Anda harus memasukkan huruf besar dan kecil persis seperti yang muncul dalam daftar program. Anda tidak dapat mengetikMAIN atauPrintLn. Jika Anda tidak hati-hati, Anda akan mengalami masalah—lihat Kesalahan Umum 1.2.

Step 3 Run the program.

Langkah3 Jalankan programnya.

The process for running a program depends greatly on your programming environment. You may have to click a button or enter some commands. When you run the 
test program, the message

Proses untuk menjalankan program sangat bergantung pada lingkungan pemrograman Anda. Anda mungkin harus mengklik tombol atau memasukkan beberapa perintah. Saat Anda menjalankan program pengujian, pesannya.

Hello,World!

will appear somewhere on the screen (see Figures 4 and 5).

akan muncul di suatu tempat di layar (lihat Gambar 4 dan Gambar 5).

In order to run your program, the Java compiler translates your **source files** (that 
is, the statements that you wrote) into class files. (A class file contains instructions for 
the Java virtual machine.) After the compiler has translated your **source code** into 
virtual machine instructions, the virtual machine executes them. During execution, 
the virtual machine accesses a library of pre-written code, including the implementations of the System and PrintStream classes that are necessary for displaying the program’s output. Figure 6 summarizes the process of creating and running a Java program. In some programming environments, the compiler and virtual machine are 
essentially invisible to the programmer—they are automatically executed whenever 
you ask to run a Java program. In other environments, you need to launch the compiler and virtual machine explicitly. 

Untuk menjalankan program Anda, kompiler Java menerjemahkan file sumber Anda (yaitu, pernyataan yang Anda tulis) ke dalam file kelas. (Sebuah file kelas berisi instruksi untuk mesin virtual Java.) Setelah kompilator menerjemahkan kode sumber Anda ke dalam instruksi mesin virtual, mesin virtual akan mengeksekusinya. Selama eksekusi, mesin virtual mengakses pustaka kode yang telah ditulis sebelumnya, termasuk implementasi kelasSystem danPrintStream yang diperlukan untuk menampilkan keluaran program. Gambar 6 merangkum proses membuat dan menjalankan program Java. Di beberapa lingkungan pemrograman, kompilator dan mesin virtual pada dasarnya tidak terlihat oleh pemrogram—mereka dijalankan secara otomatis setiap kali Anda meminta untuk menjalankan program Java. Di lingkungan lain, Anda perlu meluncurkan kompiler dan mesin virtual secara eksplisit.

Step 4 Organize your work.


Langkah4 Rapikan pekerjaamu.

As a programmer, you write programs, try them out, and improve them. You store 
your programs in **files**. Files are stored in **folders** or **directories**. A folder can contain

Sebagai seorang programmer, Anda menulis program, mencobanya, dan memperbaikinya. Anda menyimpan program Anda dalam file. File disimpan dalam **folder** atau **direktori**. Sebuah folder dapat berisi

![q](https://user-images.githubusercontent.com/112606990/190207021-fabae3fc-3558-46a4-abad-e03f99d443c6.jpg)

files as well as other folders, which themselves can contain more files and folders (see 
Figure 7). This hierarchy can be quite large, and you need not be concerned with all of 
its branches. However, you should create folders for organizing your work. It is a 
good idea to make a separate folder for your programming coursework. Inside that 
folder, make a separate folder for each program.

file serta folder lain, yang dengan sendirinya dapat berisi lebih banyak file dan folder 
(lihat Gambar 7). Hirarki ini bisa sangat besar, dan Anda tidak perlu khawatir dengan semua cabangnya. Namun, Anda harus membuat folder untuk mengatur pekerjaan Anda. Sebaiknya buat folder terpisah untuk pro-tugas mata kuliah tata bahasa. Di dalam folder itu, buat folder terpisah untuk setiap program.

![w](https://user-images.githubusercontent.com/112606990/190207086-4dca0656-6177-41e2-81e1-5b7128f2d99c.jpg)

Some programming environments place your programs into a default location if 
you don’t specify a folder yourself. In that case, you need to find out where those files 
are located. 

Beberapa lingkungan pemrograman menempatkan program Anda ke lokasi default jika Anda tidak menentukan folder sendiri. Dalam hal ini, Anda perlu mencari tahu di mana file-file itu berada.

Be sure that you understand where your files are located in the folder hierarchy. 
This information is essential when you submit files for grading, and for making 
backup copies (see Programming Tip 1.1).

Pastikan Anda memahami di mana file Anda berada dalam hierarki folder. Informasi ini penting ketika Anda mengirimkan file untuk penilaian, danuntukmembuat salinan cadangan (lihat Tip Pemrograman 1.1). 

9. Where is the HelloPrinter.java file stored on your computer? 
10. What do you do to protect yourself from data loss when you work on programming projects?

9. Di mana file HelloPrinter.java disimpan di komputer Anda?
10. Apa yang Anda lakukan untuk melindungi diri Anda dari kehilangan data saat Anda mengerjakan proyek pemrograman?

`Programming Tip 1.1`
**Backup Copies**

`Tip Pemrograman 1.1`
**Salinan Cadangan**

You will spend many hours creating and improving Java programs. It is 
easy to delete a file by accident, and occasionally files are lost because 
of a computer malfunction. Retyping the contents of lost files is frustrating and time-consuming. It is therefore crucially important that 
you learn how to safeguard files and get in the habit of doing so before
disaster strikes. Backing up files on a memory stick is an easy and convenient storage method 
for many people. Another increasingly popular form of backup is Internet file storage. Here 
are a few pointers to keep in mind:

Anda akan menghabiskan banyak waktu untuk membuat dan meningkatkan program Java. Sangat mudah untuk menghapus file secara tidak sengaja, dan terkadang file hilang karena kerusakan komputer. Mengetik ulang konten file yang hilang membuat frustrasi dan memakan waktu. Oleh karena itu, sangat penting bagi Anda untuk mempelajari cara melindungi file dan membiasakannya jikamelakukannya sebelum bencana terjadi. Mencadangkan file di memoristick adalah metode penyimpanan yang mudah dan nyaman bagi banyak orang. Bentuk pencadangan lain yang semakin populer adalah penyimpanan file Internet. Berikut adalah beberapa petunjuk yang perlu diingat:

- Back up often. Backing up a file takes only a few seconds, and you will hate yourself if you have to spend many hours recreating work that you could have saved easily. I recommend that you back up your work once every thirty minutes.
- Rotate backups. Use more than one directory for backups, and rotate them. That is, first back up onto the first directory. Then back up onto the second directory. Then use the third, and then go back to the first. That way you always have three recent backups. If your recent changes made matters worse, you can then go back to the older version. 
- Pay attention to the backup direction. Backing up involves copying files from one place to another. It is important that you do this right—that is, copy from your work location to the backup location. If you do it the wrong way, you will overwrite a newer file with an older version.
- Check your backups once in a while. Double-check that your backups are where you think they are. There is nothing more frustrating than to find out that the backups are not there when you need them. 
- Relax, then restore. When you lose a file and need to restore it from a backup, you are likely to be in an unhappy, nervous state. Take a deep breath and think through the recovery process before you start. It is not uncommon for an agitated computer user to wipe out the last backup when trying to restore a damaged file.

- Sering-seringlah membuat cadangan. Mencadangkan file hanya membutuhkan beberapa detik, dan Anda akan membenci diri sendiri jika harus menghabiskan banyak waktu untuk membuat ulang pekerjaan yang sebenarnya bisa Anda simpan dengan mudah. Saya sarankan Anda mencadangkan pekerjaan Anda setiap tiga puluh menit sekali.
- Putar cadangan. Gunakan lebih dari satu direktori untuk cadangan, dan putar mereka. Artinya, back up dulu ke direktori pertama. Kemudian kembali ke direktori kedua. Kemudian gunakan yang ketiga, lalu kembali ke yang pertama. Dengan begitu Anda selalu memiliki tiga cadangan terbaru. Jika perubahan terbaru Anda memperburuk keadaan, Anda dapat kembali ke versi yang lebih lama.
- Perhatikan arah pencadangan. Pencadangan melibatkan penyalinan file dari satu tempat ke tempat lain. Anda harus melakukannya dengan benar—yaitu, menyalin dari lokasi kerja Anda ke lokasi pencadangan. Jika Anda melakukannya dengan cara yang salah, Anda akan menimpa file yang lebih baru dengan versi yang lebih lama.
- Periksa cadangan Anda sesekali. Periksa kembali apakah cadangan Anda berada di tempat yang Anda pikirkan. Tidak ada yang lebih membuat frustrasi daripada mengetahui bahwa cadangan tidak ada saat Anda membutuhkannya.
- Santai, lalu pulihkan. Saat Anda kehilangan file dan perlu memulihkannya dari cadangan, kemungkinan besar Anda berada dalam keadaan gelisah dan tidak bahagia. Ambil napas dalam-dalam dan pikirkan proses pemulihan sebelum Anda mulai. Bukan hal yang aneh bagi pengguna komputer yang gelisah untuk menghapus cadangan terakhir ketika mencoba memulihkan file yang rusak.

## **1.5 Analyzing Your First Program**

## **1.5 Menganalisis Program Pertama Anda**
---

In this section, we will analyze the first Java program in detail. Here again is the 
source code:

Pada bagian ini, kita akan menganalisis program Java pertama secara rinci. Di sini lagi adalah
Kode sumber:

![e](https://user-images.githubusercontent.com/112606990/190207151-addb48e6-ef5e-4d87-b9c0-ec3377effbd4.jpg)

**section_5/HelloPrinter.java**

The line

Garis

public class HelloPrinter

indicates the declaration of a class called HelloPrinter.

menunjukkan deklarasi kelas yang disebut HelloPrinter.

Every Java program consists of one or more classes. We will discuss classes in more 
detail in Chapters 2 and 3.

Setiap program Java terdiri dari satu atau lebih kelas. Kami akan membahas kelas lebih lanjut
rinci dalam Bab 2 dan 3.

The word public denotes that the class is usable by the “public”. You will later 
encounter private features.

Kata publik menunjukkan bahwa kelas dapat digunakan oleh "publik". Anda akan nanti
menemukan fitur pribadi.

In Java, every source file can contain at most one public class, and the name of the 
public class must match the name of the file containing the class. For example, the 
class HelloPrinter must be contained in a file named HelloPrinter.java.

Di Java, setiap file sumber dapat berisi paling banyak satu kelas publik, dan nama dari
kelas publik harus cocok dengan nama file yang berisi kelas tersebut. Misalnya,
kelas HelloPrinter harus terdapat dalam sebuah file bernama HelloPrinter.java.

The construction

Konstruksi

public static void main(String[] args)

{

 . . .

}

declares a **method** called main. A method contains a collection of programming 
instructions that describe how to carry out a particular task. Every Java application 
must have a **main method**. Most Java programs contain other methods besides main, 
and you will see in Chapter 3 how to write other methods.

mendeklarasikan **metode** yang disebut main. Sebuah metode berisi kumpulan pemrograman
instruksi yang menjelaskan bagaimana melaksanakan tugas tertentu. Setiap aplikasi Java
harus memiliki **metode utama**. Sebagian besar program Java berisi metode lain selain utama,
dan Anda akan melihat di Bab 3 cara menulis metode lain.

The term static is explained in more detail in Chapter 8, and the meaning of 
String[] args is covered in Chapter 11. At this time, simply consider

Istilah statis dijelaskan secara lebih rinci dalam Bab 8, dan arti dari
String[] args dibahas dalam Bab 11. Saat ini, cukup pertimbangkan

public class _ClassName_

{ 

 public static void main(String[] args)

 {

 . . .

 }

} 

as a part of the “plumbing” that is required to create a Java program. Our first program has all instructions inside the main method of the class

sebagai bagian dari "pipa" yang diperlukan untuk membuat program Java. Program pertama kami memiliki semua instruksi di dalam metode utama kelas.

The main method contains one or more **instructions** called statements. Each statement ends in a semicolon (;). When a program runs, the statements in the main method 
are executed one by one.

Metode utama berisi satu atau lebih **instruksi** yang disebut pernyataan. Setiap statemen diakhiri dengan titik koma (;). Ketika sebuah program berjalan, pernyataan dalam metode utama
dijalankan satu per satu.

![r](https://user-images.githubusercontent.com/112606990/190207275-3f5cff50-6d60-43b0-8aa1-c9c39c3f2e4f.jpg)

**Syntax 1.1** Java Program

**Sintaksis 1.1** Program Java

In our example program, the main method has a single statement:

Dalam program contoh kami, metode utama memiliki satu pernyataan:

System.out.println("Hello, World!");

This statement prints a line of text, namely “Hello, World!”. In this statement, we call
a method which, for reasons that we will not explain here, is specified by the rather 
long name System.out.println.

Pernyataan ini mencetak sebaris teks, yaitu “Halo, Dunia!”. Dalam pernyataan ini, kami menyebut
metode yang, untuk alasan yang tidak akan kami jelaskan di sini, ditentukan oleh
nama panjang System.out.println.

We do not have to implement this method—the programmers who wrote the Java 
library already did that for us. We simply want the method to perform its intended 
task, namely to print a value.

Kita tidak harus mengimplementasikan metode ini—programmer yang menulis Java
perpustakaan sudah melakukannya untuk kita. Kami hanya ingin metode untuk melakukan yang dimaksudkan
tugas, yaitu mencetak nilai.

Whenever you call a method in Java, you need to specify 
1. The method you want to use (in this case, System.out.println).
2. Any values the method needs to carry out its task (in this case, "Hello, World!"). 

The technical term for such a value is an argument. Arguments are enclosed in 
parentheses. Multiple arguments are separated by commas.

Setiap kali Anda memanggil metode di Java, Anda perlu menentukan
1. Metode yang ingin Anda gunakan (dalam hal ini, System.out.println).
2. Nilai apa pun yang dibutuhkan metode untuk menjalankan tugasnya (dalam hal ini, "Halo, Dunia!").

A sequence of characters enclosed in quotation marks

Istilah teknis untuk nilai seperti itu adalah argumen. Argumen terlampir dalam
tanda kurung. Beberapa argumen dipisahkan dengan koma.

A sequence of characters enclosed in quotation marks

Urutan karakter yang diapit tanda kutip

"Hello, World!"

is called a string. You must enclose the contents of the string inside quotation marks 
so that the compiler knows you literally mean "Hello, World!". There is a reason for 
this requirement. Suppose you need to print the word main. By enclosing it in quotation marks, "main", the compiler knows you mean the sequence of characters m a i n, 
not the method named main. The rule is simply that you must enclose all text strings 
in quotation marks, so that the compiler considers them plain text and does not try to 
interpret them as program instructions.

disebut string. Anda harus menyertakan isi string di dalam tanda kutip
sehingga kompiler mengetahui maksud Anda secara harfiah "Halo, Dunia!". Ada alasan untuk
persyaratan ini. Misalkan Anda perlu mencetak kata main. Dengan melampirkannya dalam tanda kutip, "utama", kompiler tahu maksud Anda urutan karakter m a i n,
bukan metode bernama main. Aturannya sederhana, Anda harus menyertakan semua string teks
dalam tanda kutip, sehingga kompiler menganggapnya sebagai teks biasa dan tidak mencoba
menafsirkannya sebagai instruksi program.

You can also print numerical values. For example, the statement

Anda juga dapat mencetak nilai numerik. Misalnya pernyataan

System.out.println(3 + 4);

evaluates the expression 3 + 4 and displays the number 7.

mengevaluasi ekspresi 3 + 4 dan menampilkan angka 7.

The System.out.println method prints a string or a number and then starts a new 
line. For example, the sequence of statements

Metode System.out.println mencetak string atau angka dan kemudian memulai yang baru
garis. Misalnya, urutan pernyataan

System.out.println("Hello");

System.out.println("World!");

prints two lines of text:

Cetak dua baris kata:

Hello

World!

There is a second method, System.out.print, that you can use to print an item without 
starting a new line. For example, the output of the two statements

Ada metode kedua, System.out.print, yang dapat Anda gunakan untuk mencetak item tanpa
memulai baris baru. Misalnya, output dari dua pernyataan

System.out.print("00");

System.out.println(3 + 4);

is the single line
007

adalah baris sendiri
007

11. How do you modify the HelloPrinter program to greet you instead?
12. How would you modify the HelloPrinter program to print the word “Hello” vertically?
13. Would the program continue to work if you replaced line 7 with this statement?

System.out.println(Hello); 

14. What does the following set of statements print?

System.out.print("My lucky number is");

System.out.println(3 + 4 + 5);

15. What do the following statements print?

System.out.println("Hello"); 

System.out.println(""); 

System.out.println("World");

11. Bagaimana Anda memodifikasi program HelloPrinter untuk menyambut Anda?
12. Bagaimana Anda memodifikasi program HelloPrinter untuk mencetak kata “Halo”Tegak lurus?
13. Apakah program akan terus bekerja jika Anda mengganti baris 7 dengan pernyataan ini?

System.out.printl (Halo);

14. Apa yang dicetak oleh kumpulan pernyataan berikut?

System.out.print("Angka keberuntungan saya adalah"); 

System.out.println(3 + 4 + 5);

15. Apa yang dicetak oleh pernyataan berikut?

System.out.println("Halo");

System.out.println("");

System.out.println("Dunia");

`Common Error 1.1`
**Omitting Semicolons**

`Kesalahan Umum 1.1`
**Menghilangkan Titik Koma**

In Java every statement must end in a semicolon. Forgetting to type a semicolon is a common 
error. It confuses the compiler, because the compiler uses the semicolon to find where one 
statement ends and the next one starts. The compiler does not use line breaks or closing braces 
to recognize the end of statements. For example, the compiler considers

Di Java setiap pernyataan harus diakhiri dengan titik koma. Lupa mengetik titik koma adalah hal biasa
kesalahan. Ini membingungkan kompiler, karena kompiler menggunakan titik koma untuk menemukan di mana satu
pernyataan berakhir dan yang berikutnya dimulai. Kompiler tidak menggunakan jeda baris atau kurung kurawal
untuk mengenali akhir pernyataan. Misalnya, kompiler menganggap

System.out.println("Halo")

System.out.println("Dunia!");

a single statement, as if you had written

satu pernyataan, seolah-olah Anda telah menulis

System.out.println("Halo") System.out.println("Dunia!");

Then it doesn’t understand that statement, because it does not expect the word System following the closing parenthesis after "Hello".

Kemudian tidak mengerti pernyataan itu, karena tidak mengharapkan kata Sistem mengikuti kurung penutup setelah "Halo".

The remedy is simple. Scan every statement for a terminating semicolon, just as you would 
check that every English sentence ends in a period. However, do not add a semicolon at the 
end of public class Hello or public static void main. These lines are not statements.

Obatnya sederhana. Pindai setiap pernyataan untuk tanda titik koma, seperti yang Anda lakukan
periksa apakah setiap kalimat bahasa Inggris diakhiri dengan tanda titik. Namun, jangan tambahkan titik koma di
akhir kelas publik Halo atau public static void main. Garis-garis ini bukan pernyataan.

## **1.6 Errors**

## **1.6 Kesalahan**
---

Experiment a little with the HelloPrinter program. 
What happens if you make a typing error such as

Bereksperimenlah sedikit dengan program HelloPrinter.
Apa yang terjadi jika Anda membuat kesalahan pengetikan seperti

System.ou.println("Halo, Dunia!");

System.out.println("Halo, Word!");

In the first case, the compiler will complain. It will 
say that it has no clue what you mean by ou. The 
exact wording of the error message is dependent 
on your development environment, but it might be 
something like “Cannot find symbol ou”. This is a 
**compile-time error**. Something is wrong according to the rules of the language and the compiler 
finds it. For this reason, compile-time errors are 
often called **syntax errors**. When the compiler 
finds one or more errors, it refuses to translate the program into Java virtual machine 
instructions, and as a consequence you have no program that you can run. You must 
fix the error and compile again. In fact, the compiler is quite picky, and it is common 
to go through several rounds of fixing compile-time errors before compilation succeeds for the first time.

Dalam kasus pertama, kompiler akan mengeluh. Itu akan
mengatakan bahwa itu tidak tahu apa yang Anda maksud dengan ou. Itu
kata-kata yang tepat dari pesan kesalahan tergantung
di lingkungan pengembangan Anda, tetapi mungkin saja
sesuatu seperti "Tidak dapat menemukan simbol ou". Ini adalah sebuah
**kesalahan waktu kompilasi**. Ada yang salah menurut aturan bahasa dan kompilernya
menemukannya. Untuk alasan ini, kesalahan waktu kompilasi adalah
sering disebut **kesalahan sintaks**. Ketika kompilator
menemukan satu atau lebih kesalahan, ia menolak untuk menerjemahkan program ke mesin virtual Java
instruksi, dan sebagai akibatnya Anda tidak memiliki program yang dapat dijalankan. Kamu harus
perbaiki kesalahan dan kompilasi lagi. Faktanya, kompilernya cukup pilih-pilih, dan itu umum
untuk melewati beberapa putaran memperbaiki kesalahan waktu kompilasi sebelum kompilasi berhasil untuk pertama kalinya.

If the compiler finds an error, it will not simply stop and give up. It will try to 
report as many errors as it can find, so you can fix them all at once.

Jika kompiler menemukan kesalahan, itu tidak akan berhenti dan menyerah begitu saja. Ini akan mencoba untuk
laporkan kesalahan sebanyak mungkin, sehingga Anda dapat memperbaiki semuanya sekaligus.

Sometimes, an error throws the compiler off track. Suppose, for example, you 
forget the quotation marks around a string: System.out.println(Hello, World!). The 
compiler will not complain about the missing quotation marks. Instead, it will report 
“Cannot find symbol Hello”. Unfortunately, the compiler is not very smart and it 
does not realize that you meant to use a string. It is up to you to realize that you need 
to enclose strings in quotation marks. 

Terkadang, kesalahan membuat kompiler keluar jalur. Misalkan, misalnya, Anda
lupakan tanda kutip di sekitar string: System.out.println(Halo, Dunia!). Itu
compiler tidak akan mengeluh tentang tanda kutip yang hilang. Sebaliknya, itu akan melaporkan
"Tidak dapat menemukan simbol Halo". Sayangnya, kompilernya tidak terlalu pintar dan
tidak menyadari bahwa Anda bermaksud menggunakan string. Terserah Anda untuk menyadari bahwa Anda membutuhkan
untuk melampirkan string dalam tanda kutip.

The error in the second line above is of a different kind. The program will compile 
and run, but its output will be wrong. It will print

Kesalahan pada baris kedua di atas adalah jenis yang berbeda. Program akan dikompilasi
dan jalankan, tetapi outputnya akan salah. Ini akan mencetak

Hello, Word!

Halo, Kata!

This is a **run-time error**. The program is syntactically correct and does something, 
but it doesn’t do what it is supposed to do. Because run-time errors are caused by 
logical flaws in the program, they are often called **logic errors**.

Ini adalah **kesalahan run-time**. Program ini secara sintaksis benar dan melakukan sesuatu,
tetapi tidak melakukan apa yang seharusnya dilakukan. Karena kesalahan run-time disebabkan oleh
kelemahan logis dalam program, mereka sering disebut **kesalahan logika**.

This particular run-time error did not include an error message. It simply produced the wrong output. Some kinds of run-time errors are so severe that they generate an **exception**: an error message from the Java virtual machine. For example, if 
your program includes the statement

Kesalahan run-time khusus ini tidak menyertakan pesan kesalahan. Itu hanya menghasilkan output yang salah. Beberapa jenis kesalahan run-time sangat parah sehingga menghasilkan **pengecualian**: pesan kesalahan dari mesin virtual Java. Misalnya, jika
program Anda menyertakan pernyataan

System.out.println(1 / 0);

you will get a run-time error message “Division by zero”.

Anda akan mendapatkan pesan kesalahan run-time "Pembagian dengan nol".

During program development, errors are unavoidable. Once a program is longer 
than a few lines, it would require superhuman concentration to enter it correctly 
without slipping up once. You will find yourself omitting semicolons or quotation 
marks more often than you would like, but the compiler will track down these problems for you.

Selama pengembangan program, kesalahan tidak dapat dihindari. Setelah program lebih lama
dari beberapa baris, itu akan membutuhkan konsentrasi manusia super untuk memasukkannya dengan benar
tanpa tergelincir sekali. Anda akan menemukan diri Anda menghilangkan titik koma atau kutipan
menandai lebih sering daripada yang Anda inginkan, tetapi kompilator akan melacak masalah ini untuk Anda.

Run-time errors are more troublesome. The compiler will not find them—in fact, 
the compiler will cheerfully translate any program as long as its syntax is correct—but the resulting program will do something wrong. It is the responsibility of the 
program author to test the program and find any run-time errors.

Kesalahan run-time lebih merepotkan. Kompiler tidak akan menemukannya—bahkan,
kompiler akan dengan senang hati menerjemahkan program apa pun selama sintaksnya benar tetapi program yang dihasilkan akan melakukan sesuatu yang salah. Ini adalah tanggung jawab
pembuat program untuk menguji program dan menemukan kesalahan run-time.

16. Suppose you omit the "" characters around Hello, World! from the HelloPrinter. java program. Is this a compile-time error or a run-time error?
17. Suppose you change println to printline in the HelloPrinter.java program. Is this a compile-time error or a run-time error?
18. Suppose you change main to hello in the HelloPrinter.java program. Is this a compile-time error or a run-time error?
19. When you used your computer, you may have experienced a program that “crashed” (quit spontaneously) or “hung” (failed to respond to your input). Is that behavior a compile-time error or a run-time error?
20. Why can’t you test a program for run-time errors when it has compiler errors? 

16. Misalkan Anda menghilangkan karakter "" di sekitar Hello, World! dari HelloPrinter. program java. Apakah ini kesalahan waktu kompilasi atau kesalahan waktu proses?
17. Misalkan Anda mengubah println menjadi printline pada program HelloPrinter.java. Apakah ini kesalahan waktu kompilasi atau kesalahan waktu proses?
18. Misalkan Anda mengubah main menjadi hello pada program HelloPrinter.java. Apakah ini kesalahan waktu kompilasi atau kesalahan waktu proses?
19. Saat Anda menggunakan komputer, Anda mungkin pernah mengalami program yang "crash" (berhenti secara spontan) atau "digantung" (gagal menanggapi masukan Anda). Adalah perilaku itu kesalahan waktu kompilasi atau kesalahan waktu proses?
20. Mengapa Anda tidak dapat menguji program untuk kesalahan run-time ketika memiliki kesalahan kompiler?

`Common Error 1.2`
**Misspelling Words**

`Kesalahan Umum 1.2` 
**Misspelling Words**

If you accidentally misspell a word, then strange things may happen, and it may not always be 
completely obvious from the error messages what went wrong. Here is a good example of how 
simple spelling errors can cause trouble:

Jika Anda secara tidak sengaja salah mengeja kata, maka hal-hal aneh mungkin terjadi, dan itu mungkin tidak selalu
benar-benar jelas dari pesan kesalahan apa yang salah. Berikut adalah contoh yang bagus tentang caranya
kesalahan ejaan sederhana dapat menyebabkan masalah:

HelloPrinter kelas publik

{

 public static void Main(String[] args)

 {

 System.out.println("Halo, Dunia!");

 }

}

This class declares a method called Main. The compiler will not consider this to be the same as 
the main method, because Main starts with an uppercase letter and the Java language is case sensitive. Upper- and lowercase letters are considered to be completely different from each other, 
and to the compiler Main is no better match for main than rain. The compiler will cheerfully 
compile your Main method, but when the Java virtual machine reads the compiled file, it will 
complain about the missing main method and refuse to run the program. Of course, the message “missing main method” should give you a clue where to look for the error.

Kelas ini mendeklarasikan sebuah metode yang disebut Main. Kompiler tidak akan menganggap ini sama dengan
metode main, karena Main dimulai dengan huruf besar dan bahasa Java peka huruf besar-kecil. Huruf besar dan huruf kecil dianggap benar-benar berbeda satu sama lain,
dan untuk kompiler Main tidak lebih cocok untuk main daripada rain. Kompiler akan dengan senang hati
kompilasi metode Utama Anda, tetapi ketika mesin virtual Java membaca file yang dikompilasi, itu akan
mengeluh tentang metode utama yang hilang dan menolak untuk menjalankan program. Tentu saja, pesan "metode utama yang hilang" akan memberi Anda petunjuk di mana mencari kesalahan.

If you get an error message that seems to indicate that the compiler or virtual machine is on 
the wrong track, check for spelling and capitalization. If you misspell the name of a symbol 
(for example, ou instead of out), the compiler will produce a message such as “cannot find symbol ou”. That error message is usually a good clue that you made a spelling error

Jika Anda mendapatkan pesan kesalahan yang tampaknya menunjukkan bahwa kompiler atau mesin virtual aktif
trek yang salah, periksa ejaan dan kapitalisasi. Jika Anda salah mengeja nama simbol
(misalnya, ou alih-alih keluar), kompiler akan menghasilkan pesan seperti "tidak dapat menemukan sym bol ou". Pesan kesalahan itu biasanya merupakan petunjuk bagus bahwa Anda membuat kesalahan ejaan.

## **1.7 Problem Solving: Algorithm Design**

## **1.7 PENYELESAIAN MASALAH: DESAIN ALGORITMA**
---

You will soon learn how to program calculations and decision making in Java. But 
before we look at the mechanics of implementing computations in the next chapter, 
let’s consider how you can describe the steps that are necessary for finding the solution to a problem. 

Anda akan segera belajar bagaimana memprogram perhitungan dan pengambilan keputusan di Java. Tetapi sebelum kita melihat mekanisme penerapan perhitungan di bab berikutnya, mari kita pertimbangkan bagaimana Anda dapat menjelaskan langkah-langkah yang diperlukan untuk menemukan solusi dari suatu masalah.

### **1.7.1 The Algorithm Concept**

### **1.7.1 Konsep Algoritma**

You may have run across advertisements that 
encourage you to pay for a computerized service 
that matches you up with a love partner. Think 
how this might work. You fill out a form and send 
it in. Others do the same. The data are processed 
by a computer program. Is it reasonable to assume 
that the computer can perform the task of finding 
the best match for you? Suppose your younger 
brother, not the computer, had all the forms on his 
desk. What instructions could you give him? You 
can’t say, “Find the best-looking person who likes 
inline skating and browsing the Internet”. There 
is no objective standard for good looks, and your 
brother’s opinion (or that of a computer program 
analyzing the photos of prospective partners) will likely be different from yours. If 
you can’t give written instructions for someone to solve the problem, there is no way 
the computer can magically find the right solution. The computer can only do what 
you tell it to do. It just does it faster, without getting bored or exhausted.

Anda mungkin telah menemukan iklan yang mendorong Anda untuk membayar layanan terkomputerisasi mencocokkan Anda dengan pasangan cinta. Memikirkan bagaimana ini bisa berhasil. Anda mengisi formulir dan kirimkan. Yang lain melakukan hal yang sama. Data diproses oleh program komputer. Apakah masuk akal untuk asumsikan bahwa komputer dapat melakukan tugasmenemukan pasangan terbaik untuk Anda? Misalkan Anda adik laki-laki, bukan komputer, memiliki semua formulir di mejanya. Instruksi apa yang bisa Anda berikan? memberinya? Anda tidak bisa mengatakan, “Temukan yang paling tampan orang yang suka inline skating dan browsing internet”. Tidak ada standar objektif untuk ketampanan, dan pendapat saudaramu (atau itu program komputer yang menganalisis foto calon mitra) kemungkinan akan berbeda dari milik Anda. Jika Anda tidak dapat memberikan instruksi tertulis kepada seseorang untuk menyelesaikannya masalah, tidak mungkin komputer secara ajaib dapat menemukan solusi yang tepat. Itu komputer hanya dapat melakukan apa yang Anda perintahkan. Itu hanya melakukannya lebih cepat, tanpa mendapatkan bosan atau lelah.

For that reason, a computerized match-making service cannot guarantee to find 
the optimal match for you. Instead, you may be presented with a set of potential partners who share common interests with you. That is a task that a computer program 
can solve. 

Oleh karena itu, layanan pembuatan jodoh yang terkomputerisasi tidak dapat menjamin untuk menemukanpasangan yang optimal untuk Anda. Sebagai gantinya, Anda mungkin disajikan dengan serangkaian calon mitra yang memiliki minat yang sama dengan Anda. Itu adalah tugas yang program computer dapat memecahkan.

In order for a computer program to provide an answer to a problem that computes 
an answer, it must follow a sequence of steps that is
- Unambiguous
- Executable
- Terminating 

Agar program komputer memberikan jawaban atas masalah yang menghitung
jawaban, itu harus mengikuti urutan langkah-langkah yang
- Jelas
- Dapat dijalankan
- Mengakhiri

The step sequence is unambiguous when there are precise instructions for what to do 
at each step and where to go next. There is no room for guesswork or personal opinion. A step is executable when it can be carried out in practice. For example, a computer can list all people that share your hobbies, but it can’t predict who will be your 
life-long partner. Finally, a sequence of steps is terminating if it will eventually come 
to an end. A program that keeps working without delivering an answer is clearly not 
useful.

Urutan langkah tidak ambigu ketika ada instruksi yang tepat tentang apa yang harus dilakukan pada setiap langkah dan kemana harus pergi selanjutnya. Tidak ada ruang untuk menebak atau pendapat pribadi. Sebuah langkah dapat dieksekusi ketika itu dapat dilaksanakan dalam praktek. Misalnya, komputer dapat mencantumkan semua orang yang memiliki hobi yang sama dengan Anda, tapi itu tidak bisa memprediksi siapa yang akan menjadi pasangan seumur hidup Anda. Akhirnya, urutan langkah berakhir jika pada akhirnya akan berakhir. Sebuah program yang terus bekerja tanpa memberikan jawaban adalah jelas tidak berguna.

A sequence of steps that is unambiguous, 
executable, and terminating is called an algorithm. 
Although there is no algorithm for finding a partner, many problems do have algorithms for solving 
them. The next section gives an example.

Urutan langkah yang tidak ambigu, dapat dieksekusi, dan diakhiri disebut algoritma. Meskipun tidak ada algoritme untuk menemukan pasangan, banyak masalah memiliki algoritme untuk diselesaikan mereka. Bagian berikutnya memberikan contoh. 

### **1.7.2 An Algorithm for Solving an Investment Problem**

### **1.7.2 Algoritma untuk Memecahkan Masalah Investasi**

Consider the following investment problem:

Pertimbangkan masalah investasi berikut:

You put $10,000 into a bank account that earns 5 percent interest per year. How many 
years does it take for the account balance to be double the original?

Anda memasukkan $10.000 ke dalam rekening bank yang menghasilkan bunga 5 persen per tahun. Berapa banyak tahun yang diperlukan agar saldo akun menjadi dua kali lipat dari aslinya?

Could you solve this problem by hand? Sure, you could. You figure out the balance 
as follows:

Bisakah Anda memecahkan masalah ini dengan tangan? Tentu, Anda bisa. Anda mengetahui keseimbangannya sebagai berikut:

![t](https://user-images.githubusercontent.com/112606990/190207626-1d262659-d254-4498-a15f-2d486730fd7f.jpg)

You keep going until the balance is at least $20,000. Then the last number in the year 
column is the answer.

Anda terus berjalan sampai saldo setidaknya $20.000. Kemudian angka terakhir di tahun inikolom adalah jawabannya.

Of course, carrying out this computation is intensely boring to you or your 
younger brother. But computers are very good at carrying out repetitive calculations quickly and flawlessly. What is important to the computer is a description of the 
steps for finding the solution. Each step must be clear and unambiguous, requiring no 
guesswork. Here is such a description:

Tentu saja, melakukan perhitungan ini sangat membosankan bagi Anda atau adik laki-laki Anda. Tetapi komputer sangat pandai melakukan perhitungan berulang dengan cepat dan tanpa cacat. Yang penting bagi komputer adalah deskripsi langkah-langkah untuk menemukan solusi. Setiap langkah harus jelas dan tidak ambigu, tidak memerlukan tebak-tebakan. Berikut adalah deskripsi seperti itu:

Start with a year value of 0, a column for the interest, and a balance of $10,000.

Repeat the following steps while the balance is less than $20,000

Add 1 to the year value. 

Compute the interest as balance x 0.05 (i.e., 5 percent interest).

Add the interest to the balance.

Report the final year value as the answer. 

**Setel tahun ke 0, saldo ke 10.000.**

![v](https://user-images.githubusercontent.com/112606990/190207692-cbae02a0-5467-45a8-b3a0-ccb97aabeb03.jpg)

**Ketika saldo kurang dari $20,000**

**Tambahkan 1 ke tabel tahun.**

**Tetapkan bunga ke saldo x 0,05 (yaitu, bunga 5 persen).**

**Tambahkan bunga ke saldo laporan tahun sebagai jawabannya.**

![b](https://user-images.githubusercontent.com/112606990/190207759-5a7b8b12-cc9a-423a-a38c-ea1b81e0a62e.jpg)

These steps are not yet in a language that a computer can understand, but you will 
soon learn how to formulate them in Java. This informal description is called pseudocode. We examine the rules for writing **pseudocode** in the next section.

Langkah-langkah ini termasuk dalam bahasa yang belum dapat dipahami oleh komputer, tapi kamu akan segera belajar bagaimana merumuskannya dalam Java. Deskripsi ini disebut dengan **pseudocode**. Kami membahas aturan untuk menulis pseudocode di bagian selanjutnya.

### **1.7.3 Pseudocode**

### **1.7.3 Pseudocode(Kode Semu)**

There are no strict requirements for pseudocode because it is read by human readers, 
not a computer program. Here are the kinds of pseudocode statements and how we 
will use them in this book:

Tidak ada persyaratan ketat untuk pseudocode karena dibaca oleh manusia,bukan program komputer. Berikut adalah jenis-jenis pernyataan pseudocode dan bagaimana kita akan menggunakan penerapannya dalam buku ini:

- Use statements such as the following to describe how a value is set or changed: 

total cost = purchase price + operating cost

Multiply the balance value by 1.05.

Remove the first and last character from the word.

- Describe decisions and repetitions as follows: 

If total cost 1 < total cost 2

While the balance is less than $20,000

For each picture in the sequence

Use indentation to indicate which statements should be selected or repeated:

For each car

operating cost = 10 x annual fuel cost

total cost = purchase price + operating cost

Here, the indentation indicates that both statements should be executed for 
each car.

- Indicate results with statements such as:

Choose car1.

Report the final year value as the answer.

- Gunakan pernyataan seperti berikut ini untuk menjelaskan bagaimana suatu nilai ditetapkan atau diubah:

    **biaya total = harga beli + biaya operasi**

    **Kalikan nilai saldo dengan 1,05.**

    **Hapus karakter pertama dan terakhir dari kata.**
- Jelaskan keputusan dan pengulangan sebagai berikut:

    **Jika total biaya 1 < total biaya 2**

    **Ketika saldo kurang dari $20,000**

    **Untuk setiap gambar dalam urutan**

    Gunakan lekukan untuk menunjukkan pernyataan mana yang harus dipilih atau diulang:

    **Untuk setiap mobil**

    **biaya operasi = 10 x biaya bahan bakar tahunan**

    **biaya total = harga**
    
    **beli + biaya operasi**

    Di sini, lekukan menunjukkan bahwa kedua pernyataan harus dieksekusi untuk setiap mobil.
- Tunjukkan hasil dengan pernyataan seperti:

    **Pilih mobil1.**

    **Laporkan tahun sebagai jawabannya.**

### **1.7.4 From Algorithms to Programs**

### **1.7.4 Dari Algoritma ke Program**

In Section 1.7.2, we developed pseudocode for finding how long it takes to double an 
investment. Let’s double-check that the pseudocode represents an algorithm; that is, 
that it is unambiguous, executable, and terminating. 
 
Di Bagian 1.7.2, kami mengembangkan pseudocode untuk menemukan berapa lama waktu yang dibutuhkan untuk menggandakan investasi. Mari kita periksa kembali bahwa pseudocode mewakili suatu algoritma itu . adalah bahwa pseudocode itu jelas, dapat dieksekusi, dan diakhiri.

Our pseudocode is unambiguous. It simply tells how to update values in each step. 
The pseudocode is executable because we use a fixed interest rate. Had we said to use 
the actual interest rate that will be charged in years to come, and not a fixed rate of 5 
percent per year, the instructions would not have been executable. There is no way 
for anyone to know what the interest rate will be in the future. It requires a bit of 
thought to see that the steps are terminating: With every step, the balance goes up by 
at least $500, so eventually it must reach $20,000.

Pseudocode kami jelas. Ini hanya memberi tahu cara memperbarui nilai di setiap langkah. Pseudocode dapat dieksekusi karena kami menggunakan tingkat bunga tetap. Apakah kami mengatakan untuk menggunakan tingkat bunga aktual yang akan dibebankan di tahun-tahun mendatang, dan bukan tingkat bunga tetap 5 persen per tahun, instruksi tidak akan dapat dieksekusi. Tidak ada jalan bagi siapa pun untuk mengetahui berapa tingkat bunga di masa depan. Ini membutuhkan sedikit berpikir untuk melihat bahwa langkah-langkahnya berakhir: Dengan setiap langkah, keseimbangan naik setidaknya $500, jadi akhirnya harus mencapai $ 20.000.

Therefore, we have found an algorithm to solve our investment problem, and 
we know we can find the solution by programming a computer. The existence of 
an algorithm is an essential prerequisite for programming a task. You need to first 
discover and describe an algorithm for the task before you start programming (see 
Figure 8). In the chapters that follow, you will learn how to express algorithms in the 
Java language.

Oleh karena itu, kami telah menemukan algoritme untuk menyelesaikan masalah investasi kami, dan kami tahu kami dapat menemukan solusinya dengan memprogram komputer. Keberadaan algoritma adalah prasyarat penting untuk memprogram tugas. Anda harus terlebih dahulu algoritma untuk tugas anda sebelum Anda memulai pemrograman (lihat Angka 8). Dalam bab-bab berikutnya, Anda akan mempelajari cara mengekspresikan algoritme dalam bahasa Java.

21. Suppose the interest rate was 20 percent. How long would it take for the investment to double?
22. Suppose your cell phone carrier charges you $29.95 for up to 300 minutes of calls, and $0.45 for each additional minute, plus 12.5 percent taxes and fees. Give an algorithm to compute the monthly charge from a given number of minutes.
23. Consider the following pseudocode for finding the most attractive photo from a sequence of photos:

Pick the first photo and call it "the best so far".

For each photo in the sequence

If it is more attractive than the "best so far"

 Discard "the best so far".

 Call this photo "the best so far".

The photo called "the best so far" is the most attractive photo in the sequence.

Is this an algorithm that will find the most attractive photo?

24. Suppose each photo in Self Check 23 had a price tag. Give an algorithm for finding the most expensive photo. 
25. Suppose you have a random sequence of black and white marbles and want to rearrange it so that the black and white marbles are grouped together. Consider this algorithm:

Repeat until sorted

Locate the first black marble that is preceded by a white marble, and switch them.What does the algorithm do with the sequence mlmll? Spell out the steps until the algorithm 
stops.
26. Suppose you have a random sequence of colored marbles. Consider this pseudocode: 

Repeat until sorted

Locate the first marble that is preceded by a marble of a different color, and switch them.

Why is this not an algorithm?

21. Misalkan tingkat bunga adalah 20 persen. Berapa lama waktu yang dibutuhkan agar investasi menjadi dua kali lipat?
22. Misalkan operator ponsel Anda menagih Anda $29,95 hingga 300 menit panggilan, dan $0,45 untuk setiap menit tambahan, ditambah pajak dan biaya 12,5 persen. Memberi algoritma untuk menghitung biaya bulanan dari sejumlah menit tertentu.
23. Perhatikan pseudocode berikut untuk menemukan foto paling menarik dari urutan foto:

    **Pilih foto pertama dan beri nama "yang terbaik sejauh ini".**

    **Untuk setiap foto dalam urutan**

    **Jika itu lebih menarik daripada "terbaik sejauh ini"**

    **Buang "yang terbaik 
    sejauh ini".**

    **Sebut foto ini "yang terbaik sejauh ini".**

    **Foto yang disebut "yang terbaik sejauh ini" adalah foto paling 
    menarik dalam urutan itu.**

    Apakah ini algoritma yang akan menemukan foto paling menarik?

24. Misalkan setiap foto di Self Check 23 memiliki label harga. Berikan algoritma untuk menemukan foto yang paling mahal.
25. Misalkan Anda memiliki urutan acak kelereng hitam dan putih dan ingin atur ulang sehingga kelereng hitam dan putih dikelompokkan bersama. Mempertimbangkan algoritma ini:

    **Ulangi sampai terurut**

    **Temukan kelereng hitam pertama yang didahului oleh kelereng putih, dan alihkan.**

    Apa yang dilakukan algoritma dengan urutan mlmll? Sebutkan langkah-langkahnya sampai algoritma berhenti.
26. Misalkan Anda memiliki urutan acak kelereng berwarna. Pertimbangkan kode semu ini:

    **Ulangi sampai terurut**

    **Temukan kelereng pertama yang didahului oleh kelereng dengan warna berbeda, dan ganti.**

    Mengapa ini bukan algoritma?

`How To 1.1`    

`BAGAIMANA 1.1`

**Describing an Algorithm with Pseudocode**

**Menjelaskan algoritma dengan Pseudocode**

This is the first of many “How To” sections in this book that give you step-by-step procedures for carrying out important tasks in developing computer programs.

Ini adalah yang pertama dari banyak cara bagian dalam buku ini yang memberikan Anda langkah-demi-langkah prosedur untuk melaksanakan tugas-tugas penting dalam mengembangkan program komputer.

Before you are ready to write a program in Java, you need to develop an algorithm—a 
method for arriving at a solution for a particular problem. Describe the algorithm in pseudocode––a sequence of precise steps formulated in English. To illustrate, we’ll devise an algorithm for this problem: 

Sebelum Anda siap untuk menulis sebuah program di Java, Anda perlu mengembangkan metode algorithma untuk tiba di solusi untuk masalah tertentu menggambarkan algoritma di pseudocode urutan langkah-langkah yang tepat dirumuskan dalam bahasa Inggris untuk menggambarkan, kami akan merancang sebuah algoritma untuk masalah ini:

**Problem Statement** You have the choice of buying one 
of two cars. One is more fuel efficient than the other, but also 
more expensive. You know the price and fuel efficiency (in miles 
per gallon, mpg) of both cars. You plan to keep the car for ten 
years. Assume a price of $4 per gallon of gas and usage of 15,000 
miles per year. You will pay cash for the car and not worry about 
financing costs. Which car is the better deal? 

**Pernyataan masalah**	 Anda memiliki pilihan untuk membeli salah satu dari dua mobil. Satu lebih hemat bahan bakar daripada yang lain, tetapi juga lebih mahal. 

Anda tahu harga dan efisiensi bahan bakar (dalam mil per galon, mpg) dari kedua mobil. Anda berencana untuk menyimpan mobil selama sepuluh tahun. Asumsikan harga $4 per galon gas dan penggunaan 15.000 mil per tahun. Anda akan membayar tunai untuk mobil dan tidak khawatir tentang biaya pembiayaan. Mobil mana yang lebih baik?

Step 1 Determine the inputs and outputs.

In our sample problem, we have these inputs:

• **purchase price1 and fuel efficiency1**, the price and fuel efficiency (in mpg) of the first car
• **purchase price2 and fuel efficiency2**, the price and fuel efficiency of the second car

We simply want to know which car is the better buy. That is the desired output.

Step 2 Break down the problem into smaller tasks.

For each car, we need to know the total cost of driving it. Let’s do this computation separately 
for each car. Once we have the total cost for each car, we can decide which car is the better deal. 

The total cost for each car is **purchase price + operating cost**.

We assume a constant usage and gas price for ten years, so the operating cost depends on the 
cost of driving the car for one year. 

The operating cost is **10 x annual fuel cost**.

The annual fuel cost is **price per gallon x annual fuel consumed**.

The annual fuel consumed is annual miles driven / fuel efficiency. For example, if you drive the car 
for 15,000 miles and the fuel efficiency is 15 miles/gallon, the car consumes 1,000 gallons. 

Step 3 Describe each subtask in pseudocode.

In your description, arrange the steps so that any intermediate values are computed before 
they are needed in other computations. For example, list the step

**total cost = purchase price + operating cost**

after you have computed **operating cost**.

Here is the algorithm for deciding which car to buy:

**For each car, compute the total cost as follows:** 

**annual fuel consumed = annual miles driven / fuel efficiency**

**annual fuel cost = price per gallon x annual fuel consumed**

**operating cost = 10 x annual fuel cost**

**total cost = purchase price + operating cost**

**If total cost1 < total cost2**

**Choose car1.**

**Else**

**Choose car2.**

Step 4 Test your pseudocode by working a problem.

We will use these sample values:

Car 1: $25,000, 50 miles/gallon

Car 2: $20,000, 30 miles/gallon

Here is the calculation for the cost of the first car:

**annual fuel consumed = annual miles driven / fuel  efficiency = 15000 / 50 = 300**

**annual fuel cost = price per gallon x annual fuel consumed = 4 x 300 = 1200**

**operating cost = 10 x annual fuel cost = 10 x 1200 = 12000**

**total cost = purchase price + operating cost = 25000 + 12000 = 37000**

Similarly, the total cost for the second car is $40,000. Therefore, the output of the algorithm is 
to choose car 1. 


Langkah 1 Tentukan input dan output. 

Dalam contoh soal kami, kami memiliki input ini:
- **Harga beli1 dan efisiensi bahan bakar1**, harga dan efisiensi bahan bakar (dalam mpg) mobil pertama.
- **Harga beli2 dan efisiensi bahan bakar2**, harga dan efisiensi bahan bakar mobil kedua.
Kami hanya ingin tahu mobil mana yang lebih baik dibeli. Itu adalah keluaran (output) yang diinginkan.

Langkah 2 Memecah masalah menjadi tugas-tugas yang lebih kecil. 

Untuk setiap mobil, kita perlu mengetahui total biaya mengemudinya. Mari kita lakukan perhitungan ini secara terpisah untuk setiap mobil. Setelah kita memiliki total biaya untuk setiap mobil, kita dapat memutuskan mobil mana yang lebih baik.

Total biaya untuk setiap mobil adalah **harga beli + biaya operasional**.

Kami mengasumsikan penggunaan konstan dan harga gas selama sepuluh tahun, sehingga biaya operasi tergantung pada biaya mengemudi mobil selama satu tahun.

Biaya operasi adalah **10 x biaya bahan bakar tahunan**.
Biaya bahan bakar tahunan adalah **harga per galon x bahan bakar tahunan yang dikonsumsi**.

Bahan bakar tahunan yang dikonsumsi adalah jarak tempuh tahunan / efisiensi bahan bakar. Misalnya, jika Anda mengendarai mobil sejauh 15.000 mil dan efisiensi bahan bakarnya 15 mil/galon, mobil tersebut mengkonsumsi 1.000 galon.

Langkah 3  Jelaskan setiap subtugas dalam pseudocode. 

Dalam uraian Anda, atur langkah-langkahnya sehingga setiap nilai antara dihitung sebelum diperlukan dalam perhitungan lain. Misalnya, daftar langkah:

**biaya total = harga pembelian + biaya operasi
Setelah Anda menghitung biaya operasi.**

Berikut adalah algoritma untuk memutuskan mobilmana yang akan dibeli:

**Untuk setiap mobil, hitung total biaya sebagai berikut:**

**konsumsi bahan bakar tahunan = jarak tempuh tahunan / efisiensi bahan bakar** 

**biaya bahan bakar tahunan = harga per galon x konsumsi bahan bakar tahunan** 

**biaya operasional = 10 x biaya bahan bakar tahunan** 

**total biaya = harga beli + biaya operasional** 

**Jika total biaya mobil1 < total biaya mobil2**

**Pilih mobil1.** 

**Lainnya**

**Pilih mobil2.**

Langkah 4 Uji pseudocode Anda dengan mengerjakan soal.

Kami akan menggunakan nilai sampel ini: 

Mobil 1: $25.000, 50 mil/galon 

Mobil 2: $20.000, 30 mil/galon 

Berikut adalah perhitungan biaya mobil pertama:

**konsumsi bahan bakar tahunan = jarak tempuh tahunan / efisiensi bahan bakar = 15000 / 50 = 300** 

**biaya bahan bakar tahunan = harga per galon x konsumsi bahan bakar tahunan = 4 x 300 = 1200** 

**biaya operasi = 10 x biaya bahan bakar tahunan = 10 x 1200 = 12000** 

**total biaya = harga pembelian + biaya operasi = 25000 + 12000 = 37000** 

Demikian pula, total biaya untuk mobil kedua adalah $ 40.000. Oleh karena itu, keluaran dari algoritma adalah memilih mobil 1.

Contoh Kerja berikut menunjukkan bagaimana menggunakan konsep-konsep dalam bab ini dan langkah-langkah dalam Cara untuk memecahkan masalah lain. Dalam hal ini, Anda akan melihat bagaimana mengembangkan algoritme untuk meletakkan ubin dalam pola warna yang bergantian. Anda harus membaca Contoh yang Dikerjakan untuk meninjau apa yang telah Anda pelajari, dan untuk bantuan dalam mengatasi masalah lain.

Di bab-bab selanjutnya, contoh yang dikerjakan ditunjukkan dengan deskripsi singkat tentang masalah yang ditangani dalam contoh, ditambah pengingat untuk melihatnya di eTeks Anda atau mengunduhnya dari situs web pendamping buku di www.wiley.com/go/bjeo7. Anda akan menemukan kode apa pun yang terkait dengan Contoh yang Dikerjakan yang disertakan dengan kode pendamping buku untuk bab ini. Saat Anda melihat deskripsi Contoh yang Dikerjakan, buka contoh dan lihat dan jalankan kode untuk mempelajari bagaimana masalah tersebut diselesaikan.
