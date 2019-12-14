# Extensive Performance Analysis of AODV and Modified AODV for Link Stability and Network Life time in MANET

## TOPIK KHUSUS B

### KELOMPOK:
*  05111640000160 - MUHAMMAD ALGHIFARI YURIZIA
*  05111640000181 - AHMAD IMAM FADHILA
*  05111640000186 - ACHMAD JADID
*  05111640000192 - MUHAMMAD RENALDI ARYAPUTRA W

## Deskripsi Paper
*  Judul Paper : Extensive Performance Analysis of AODV and Modified AODV for Link Stability and Network Life time in MANET
*  Penulis Paper : Yatin Rana, Umang Soni
*  Tahun : 2015
*  Source : https://www.semanticscholar.org/paper/Extensive-Performance-Analysis-of-AODV-and-Modified-Rana-Soni/2039f879b96fe6565d34b2e66523e93b6f590bc1


## Latar Belakang
AODV adalah salah satu protokol routing Mobile Ad Hoc Network (MANET). Protokol routing  ini disebut juga sebagai Reactive routing, dimana  menentukan rute ketika diminta (on demand).

AODV ini akan melakukan Route Discovery untuk menentukan rute mana saja yang tersedia dengan cara Route Request yaitu source node akan menyebar secara broadcast ke node tetangga hingga sampai ke destination node. Setelah sampai ke destination node, node tersebut akan melakukan Route Reply dimana node akan menjawab dengan memberikan jarak terpendek kembali menuju node secara unicast.

AODV juga memiliki Route Maintenance dimana dia akan mengecek apabila sebuah node harus mengirim package/data ke destination tertentu dia akan mengecek routing table. Jika route ada, forward ke node selanjutnya, dan jika route tidak ada maka akan menginisiasi Route Discovery.


## Permasalahan
MANET terdiri dari independent wireless mobile node (node nirkabel yang dapat berpindah-pindah dan independen) yang akan membentuk jaringan sementara tanpa menggunakan fixed infrastructure atau centralized management.

Operasi routing pada MANET membutuhkan node yang mobile untuk bekerja sama satu sama lain agar berhasil. Maka dari itu ketersediaan node sangatlah penting. Namun terdapat dua faktor utama yang bisa menyebabkan kerusakan (link breakage) pada MANET seperti :
*  Energi sisa node (battery lifetime)
*  Mobilitas node


## Solusi
Pada paper ini solusi yang ditawarkan adalah dengan menggunakan AODV karena banyak digunakan di MANET. Kemudian melakukan modifikasi pada AODV yang akan mengambil keputusan forwarding berdasarkan dua parameter yaitu energi dari node dan Link Expire Time (LET) dan meneliti dampaknya terhadap stabilitas jaringan


## Modified AODV
Fokus utama pada paper ini adalah menunjukan bagaimana meningkatkan proses Route Discovery ketika ada source node yang mencoba untuk berkomunikasi  dengan node lain yang tidak memiliki info routing.

Dalam modifikasi AODV ini, ketika ada data untuk ditransmisikan, source node akan melakukan broadcast RREQ (Route Request), node yang berada disekitarnya akan memutuskan apakah meneruskan RREQ tersebut berdasarkan baterai yang tersisa dan link expiration time dari pengirim RREQ.


##