What is the difference between IaaS, SaaS, and Paas?

Dalam hal dibuat di rumah, itu berarti lingkungan di tempat
Anda mengelola segala sesuatu yaitu Anda membuat keju, topping, adonan pizza Anda sendiri, Anda memiliki oven sendiri, 
gas dll,dan Anda membuat semuanya sendiri dan makan di rumah. Anda mengontrol seberapa baik (atau buruk) pizza Anda 
Dalam hal IaaS, Anda membeli bahan baku (yaitu lingkungan komputasi, disk penyimpanan, OS Anda, dll.) 
Dari Penyedia Layanan Cloud Anda. Infrastruktur akan diberikan kepada Anda oleh Penyedia Cloud dan Anda tidak 
akan memiliki kontrol penuh padanya (Anda tidak akan tahu di mana tepatnya server Anda, di mana disk Anda dll). 
Tetapi Anda mengontrol bagaimana penambalan dilakukan pada OS Anda, beban kerja apa yang Anda miliki di lingkungan Anda, dll
Di PaaS, Anda membeli pizza di luar dan memakannya di rumah yaitu, Anda tidak perlu khawatir tentang bagaimana 
mengonfigurasi basis data, loadbalancers, dll. Mereka disediakan untuk Anda sebagai layanan yang dikelola oleh penyedia 
layanan cloud Anda. Tugas seperti membuat cadangan database dll dapat didorong ke ujung penyedia layanan dan Anda hanya dapat 
berkonsentrasi pada membangun dan menggunakan aplikasi Anda. Tingkat sumber daya yang dikontrol oleh Anda berkurang
Dalam model SaaS, sebagian besar layanan dikelola oleh penyedia layanan Anda dan jumlah 
konfigurasi atau pengaturan di ujung Anda minimal. Jumlah kontrol yang Anda miliki pada sumber daya cloud Anda terus menurun saat Anda menuju ke kanan dalam diagram 
(Kontrol tertinggi pada IaaS untuk kontrol setidaknya pada SaaS)

SAAS (Software as a Service) Platform Architecture
Perangkat lunak sebagai layanan adalah model lisensi dan pengiriman perangkat lunak di mana perangkat lunak dilisensikan 
berdasarkan berlangganan dan di-host secara terpusat. Pengguna dapat mengaksesnya dengan bantuan browser web.
aaS adalah model pengiriman umum untuk banyak aplikasi bisnis, termasuk perangkat lunak perkantoran dan pesan, 
perangkat lunak manajemen, virtualisasi dll. Ini adalah bagian dari nomenklatur komputasi awan, bersama dengan 
infrastruktur sebagai layanan (IaaS), platform sebagai layanan (PaaS) , desktop sebagai layanan (DaaS).

SAAS Architecture:
Dengan model ini, satu versi aplikasi, dengan satu konfigurasi digunakan untuk semua pelanggan. 
Aplikasi ini diinstal pada banyak mesin untuk mendukung skalabilitas (disebut penskalaan horizontal). 
Dalam beberapa kasus, versi kedua aplikasi diatur untuk menawarkan kelompok pelanggan tertentu dengan akses ke 
versi pra-rilis aplikasi untuk tujuan pengujian. Dalam model tradisional ini, setiap versi aplikasi didasarkan pada kode unik. 
Meskipun pengecualian, beberapa solusi SaaS tidak menggunakan multitenancy, untuk mengelola secara efektif sejumlah besar
pelanggan di tempat. Apakah multitenancy merupakan komponen yang diperlukan untuk perangkat lunak-sebagai-layanan adalah 
topik kontroversi.

There are two main varieties of SaaS:
a. SaaS Vertikal
b. Perangkat Lunak yang menjawab kebutuhan industri tertentu (mis., Perangkat lunak untuk kesehatan, 
   pertanian, real estat, industri keuangan).
c. SaaS Horisontal
d. Produk-produk yang berfokus pada kategori perangkat lunak (pemasaran, penjualan, alat pengembang, SDM)
   tetapi agnostik industri.


How SaaS Affects IT ?
Setelah Anda membuat keputusan untuk mengejar SaaS, selanjutnya adalah mempersiapkan transisi dengan menilai bagaimana
penyebaran akan mempengaruhi aset TI yang ada.Melakukan uji tuntas adalah bagian rutin dari setiap proyek penyebaran
infrastruktur TI yang sukses. Beberapa bidang yang harus ditangani dalam daftar periksa uji tuntas meliputi, 
Standar keamanan data: Memindahkan data bisnis penting "di luar tembok" menimbulkan risiko kehilangan data atau paparan 
informasi sensitif yang tidak disengaja. Nilai kebutuhan keamanan data Anda, dan pastikan bahwa penyedia memiliki langkah-langkah 
untuk memenuhi standar yang Anda tetapkan.

Impact on IT Roles and Responsibilities :
Menambahkan SaaS dapat menyebabkan perubahan mendasar dalam peran departemen TI sebagai penyedia layanan informasi. 
Di masa lalu, sifat penyebaran perangkat lunak telah menempatkan petugas informasi kepala dalam peran penjaga gerbang.

SAAS (Software as a Service) Platform Architecture :
pengantar :
Pengiriman perangkat lunak telah berubah selama bertahun-tahun. Secara historis, aplikasi ditulis untuk 
mainframe dalam bahasa seperti COBOL. Di tahun 70-an dan 80-an, kami melihat ledakan komputasi di rumah dan kebangkitan 
programmer kamar tidur. Komputasi daya ditingkatkan dan memungkinkan pengguna menjalankan aplikasi kompleks pada mesin desktop
mereka. Modem dan Sistem Papan Buletin (BBS) menjadi populer di tahun 80-an yang memungkinkan penggemarkomputer untuk menawarkan
layanan online dasar seperti email mentah (Fidonet), fasilitas pengiriman pesan / paging dan membuat perangkat lunak
tersedia untuk diunduh. Semua ini dilakukan di era pra-broadband melalui saluran telepon biasa. dan Pada tahun 90-an, kita melihat munculnya web di seluruh dunia seperti yang kita kenal sekarang dan kekuatan komputasi. 
Infrastruktur jaringan terus tumbuh di tahun 90-an dan ketika teknologi web meningkat, kompleksitas dan fungsionalitas
situs web terus meningkat. Akhirnya, kami melihat perkembangan layanan yang lebih maju untuk internet (atau cloud).

membangun untuk cloud :
Saat membangun aplikasi SaaS (global), ada kemungkinan besar bahwa Anda membangunnya di cloud. 
Cloud memiliki banyak keunggulan - pikirkan skalabilitas - berbeda dengan lingkungan server lokal

The perfect database :
Jadi, salah satu hal pertama dalam daftar Anda akan mencakup pemasangan basis data. Kami merekomendasikan penggunaan basis 
data berorientasi dokumen. Database dokumen sangat berbeda dengan konsep tradisional database relasional

MongoDB - database untuk aplikasi web Anda?
Kami - di Usersnap - berakhir menggunakan MongoDB sebagai basis data kami sebelumnya.

Mengapa kami memilih MongoDB? 
Karena MongoDB adalah database berorientasi dokumen yang memberikan kinerja tinggi, ketersediaan tinggi, dan skalabilitas mudah.
Ya. Selain kinerja (yang menginginkan database yang lambat?), Skalabilitas adalah faktor terpenting bagi 
kami sebagai bisnis SaaS global.