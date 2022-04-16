resume materi

1. Pembuatan Code Testing
Sebelum memulai membut code untuk automatic testingnya, saya disclaimer dulu. Bahwa code java yang dibuat bukan best praktis code java untuk software development. Ini sekadara demo untuk dapat menjalankan automatic test sederhana dengan java, cucumber , dan appium.

- Create Project Maven dengan IDE yang telah terinsall.
- Pilih maven project dan tentukan nama project dan lokasi penyimpanan dari source code.
- Setelah project di buat, Edit POM project teserbut dan tambahkan beberapa library yang akan di gunakan.
- Lakukan clean install untuk mendowload beberapa library yang di perlukan.
- Buat folder untuk menyimpan scenario di bawah resources dan dua package dibawah test, setups dan steps.
- Buat scenario test seperti berikut dan pastikan lambang cucmber nyala.
- Buat java class dengan nama Capabilities pada package setups.
- Lakukan pengecekan nama device bisa dengan command berikut. Catatan setting environment Anda sudah benar.
- Buat dua file test dengan nama DoPositiveTest dan DoNegativeTest.
- Build Project
- Install Demo.apk yang akan kita test pada mobile device kita dan jangan lupa debuging mode di aktivekan.
- Les’t Test

2. kegunaan dari tool-tool 
- Java adalah bahasa pemograman yang digunakan
- IntteliJ adalah Java IDE yang akan membantu dan mempermudah pembuatan code atumatic test.
- Cucumber adalah BDD (Behaviour Driven Development) framework dan reporting
- Gherkin adakah format spesifikasi untuk cucumber. Ini adalah bahasa khusus domain yang membantu Anda mendeskripsikan perilaku bisnis tanpa perlu menjelaskan implementasi secara detail.
- Appium sendiri adalah library untuk kita dapat membuat automatic test pada mobile applikasi baik android atau ios.
- Maven 3 adalah tool untuk melakukan build source code java.
- Log4J2 sebagai logging framework, JUnit sebagai unit test tool, dan TestNG sebagai funsional test tool.

Dengan demikian akan menapatkan fitur dan keuntungan dari tool-tool di atas sebagai berikut.
- Design test menggunakan Page Object Model yang merupakan pattern yang umuam di gunakan pada proses automatis test.
- Behavior driven karena menggunakan cucumber.
- Support CI/CD.
- Support pararel ekeskusi dengan menggunakan JUnit dan TestNG.
- Suport untuk android dan ios.
- Start dan stop Appoium service programmatically.
- Support cucumber HTML report.
- Support CLI.

3. Karakteristik BDD
- Kolaborasi yang kuat
    BDD menyediakan kolaborasi yang kuat antara pihak-pihak yang terlibat. Itu hanya karena kasus uji mudah yang ditulis dalam bahasa Inggris. Dalam pengujian mentimun, pemegang saham memainkan peran penting dalam diskusi konstruktif karena hanya mereka yang tahu harapan dari perangkat lunak.

- Visibilitas tinggi
    Setiap orang mendapat visibilitas yang kuat dalam kemajuan proyek karena bahasa Inggris yang mudah.Desain perangkat lunak mengikuti nilai bisnis. BDD sangat mementingkan nilai dan kebutuhan bisnis. Dengan menetapkan prioritas dengan klien, tergantung pada nilai yang diberikan oleh mereka, pengembang dapat memberikan hasil yang lebih baik karena mereka memiliki pemahaman yang kuat tentang cara berpikir pelanggan.

- Bahasa di mana-mana
    Seperti disebutkan sebelumnya, kasus uji ditulis dalam bahasa yang ada di mana-mana, yang dapat dimengerti oleh semua anggota tim, baik mereka dari bidang teknis atau tidak. Ini membantu untuk mengurangi kesalahpahaman dan kesalahpahaman antara anggota terkait dengan konsep. Bahasa di mana-mana memudahkan bergabungnya anggota baru ke dalam pekerjaan.

- Pengembangan perangkat lunak memenuhi kebutuhan pengguna.
    BDD berfokus pada kebutuhan bisnis agar pengguna dapat terpuaskan, dan tentu saja pengguna yang puas menyiratkan bisnis yang berkembang. Dengan BDD, tester berfokus pada perilaku yang memiliki dampak lebih dari implementasi.

- Lebih percaya diri dari pihak pengembang
    Tim yang menggunakan BDD umumnya lebih percaya diri karena mereka tidak melanggar kode, dan dalam hal pekerjaan mereka, perkiraan yang lebih baik dilakukan.

- Biaya Lebih Rendah
    Dengan meningkatkan kualitas kode, BDD pada dasarnya mengurangi biaya pemeliharaan dan meminimalkan risiko proyek.