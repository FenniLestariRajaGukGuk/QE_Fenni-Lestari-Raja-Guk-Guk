resume materi

1. Rest Assured adalah teknologi open source yang sangat banyak digunakan untuk Pengujian Otomasi REST API, ini didasarkan pada perpustakaan berbasis java.

Rest Assured berinteraksi dengan Rest API dalam mode klien tanpa kepala, kita dapat meningkatkan permintaan yang sama dengan menambahkan lapisan yang berbeda untuk membentuk permintaan dan membuat permintaan HTTP melalui kata kerja HTTPS yang berbeda ke server.

2. Piramida pengujian asli Mike Cohn terdiri dari tiga lapisan yang harus terdiri dari rangkaian pengujian Anda (bawah ke atas):

Tes Unit
Tes Layanan
Tes Antarmuka Pengguna

Dasar dari rangkaian pengujian Anda akan terdiri dari pengujian unit. Tes unit Anda memastikan bahwa unit tertentu ( subjek Anda yang sedang diuji ) dari basis kode Anda berfungsi sebagaimana dimaksud. Pengujian unit memiliki cakupan paling sempit dari semua pengujian di rangkaian pengujian Anda. Jumlah pengujian unit dalam rangkaian pengujian Anda sebagian besar akan melebihi jumlah jenis pengujian lainnya.

3. Memisahkan sistem Anda menjadi banyak layanan kecil sering kali berarti bahwa layanan ini perlu berkomunikasi satu sama lain melalui antarmuka tertentu (semoga terdefinisi dengan baik, terkadang tumbuh secara tidak sengaja).

Antarmuka antara aplikasi yang berbeda dapat datang dalam berbagai bentuk dan teknologi. Yang umum adalah

- REST dan JSON melalui HTTPS
- RPC menggunakan sesuatu seperti gRPC membangun arsitektur yang digerakkan oleh peristiwa menggunakan antrian

Untuk setiap antarmuka ada dua pihak yang terlibat: penyedia dan konsumen. Penyedia menyajikan data kepada konsumen. Konsumen memproses data yang diperoleh dari penyedia. Di dunia REST, penyedia membangun REST API dengan semua titik akhir yang diperlukan; konsumen melakukan panggilan ke REST API ini untuk mengambil data atau memicu perubahan di layanan lain. Dalam dunia yang tidak sinkron dan digerakkan oleh peristiwa, penyedia (sering disebut publisher ) menerbitkan data ke antrian; konsumen (sering disebut pelanggan ) berlangganan antrian ini dan membaca dan memproses data.

