resume materi

1. Map sangat cocok digunakan untuk pemetaan asosiasi nilai kunci seperti kamus. Peta digunakan untuk melakukan pencarian dengan kunci atau ketika seseorang ingin mengambil dan memperbarui elemen dengan kunci. Beberapa skenario umum adalah sebagai berikut: 

Map kode kesalahan dan deskripsinya.
Map kode pos dan kota.
Map manajer dan karyawan. Setiap manajer (kunci) dikaitkan dengan daftar karyawan (nilai) yang dia kelola.
Map kelas dan siswa. Setiap kelas (kunci) dikaitkan dengan daftar siswa (nilai).

2. Karakteristik Map Interface
    - Peta tidak dapat berisi kunci duplikat dan setiap kunci dapat dipetakan ke paling banyak satu nilai. Beberapa implementasi mengizinkan nilai null key dan null seperti HashMap dan LinkedHashMap , tetapi beberapa tidak menyukai TreeMap .
    - Urutan peta tergantung pada implementasi spesifik. Misalnya, TreeMap dan LinkedHashMap memiliki pesanan yang dapat diprediksi, sedangkan HashMap tidak.
    - Ada dua antarmuka untuk mengimplementasikan Peta di java. Mereka adalah Map dan SortedMap , dan tiga kelas: HashMap, TreeMap, dan LinkedHashMap.

3.  Kelas 1: HashMap 
HashMap adalah bagian dari koleksi Java sejak Java 1.2. Ini menyediakan implementasi dasar dari antarmuka Peta Java. Ini menyimpan data dalam pasangan (Kunci, Nilai). Untuk mengakses suatu nilai, seseorang harus mengetahui kuncinya. Kelas ini menggunakan teknik yang disebut Hashing . Hashing adalah teknik mengubah String besar menjadi String kecil yang mewakili String yang sama. Nilai yang lebih pendek membantu dalam pengindeksan dan pencarian lebih cepat.
    Kelas 2: LinkedHashMap
LinkedHashMap sama seperti HashMap dengan fitur tambahan untuk mempertahankan urutan elemen yang dimasukkan ke dalamnya. HashMap memberikan keuntungan penyisipan, pencarian, dan penghapusan yang cepat tetapi tidak pernah mempertahankan trek dan urutan penyisipan yang disediakan LinkedHashMap di mana elemen dapat diakses dalam urutan penyisipan.
    Kelas 3: Treemap
TreeMap di Java digunakan untuk mengimplementasikan antarmuka Peta dan NavigableMap bersama dengan Kelas Abstrak. Peta diurutkan menurut urutan alami kuncinya, atau oleh Pembanding yang disediakan pada waktu pembuatan peta, tergantung pada konstruktor yang digunakan. Ini terbukti menjadi cara yang efisien untuk menyortir dan menyimpan pasangan nilai kunci. Urutan penyimpanan yang dipertahankan oleh peta pohon harus konsisten dengan yang sama seperti peta yang diurutkan lainnya, terlepas dari pembanding eksplisit.
