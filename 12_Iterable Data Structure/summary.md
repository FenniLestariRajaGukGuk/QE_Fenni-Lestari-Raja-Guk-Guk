resume materi

Antarmuka Java Iterable mewakili kumpulan objek yang dapat diubah - artinya dapat diulang. Ini berarti, bahwa kelas yang mengimplementasikan Iterableantarmuka Java dapat memiliki elemen yang diulang. Anda dapat mengulangi objek Java Iterable dengan tiga cara: Melalui , dengan memperoleh Java Iterator dari Iterable, atau dengan memanggil metode Java Iterable forEach(). Anda akan melihat contoh ketiga metode iterasi nanti dalam tutorial Java Iterable ini.   

1. Cara pertama untuk mengulang elemen Java Iterable adalah melalui loop loop untuk setiap Java . 
Di bawah ini adalah contoh yang menunjukkan cara mengulangi elemen Daftar Java melalui Java untuk setiap loop. Karena antarmuka Java Listmemperluas Collectionantarmuka, dan Collectionantarmuka memperluas Iterableantarmuka, sebuah Listobjek dapat digunakan dengan loop for-each.

List<String> list = new ArrayList><();

list.add("satu");
list.add("dua");
list.add("tiga");

untuk( Elemen string : daftar ){
    System.out.println( elemen.toString() );
}                                                                                                             

2. Cara kedua Anda dapat mengulangi elemen Java Iterable adalah dengan mendapatkan Java Iterator darinya dengan memanggil iterator()metode Iterable. Anda kemudian dapat beralih melalui Iterator itu seperti yang Anda lakukan dengan Iterator lainnya. Anda dapat membaca lebih lanjut tentang Java Iterator di tutorial Java Iterator saya . Berikut adalah contoh iterasi elemen Java Iterable ( Daftar Java dalam contoh ini):

List<String> list = new ArrayList><();

list.add("satu");
list.add("dua");
list.add("tiga");

Iterator<String> iterator = list.iterator();

while(iterator.hasNext()) {
    Elemen string = iterator.next();
    System.out.println( elemen );
}                                                                                                                                                  
3. Cara ketiga untuk mengulangi elemen Java Iterable adalah melalui forEach()metodenya. Metode forEach()ini menggunakan Ekspresi Lambda Java sebagai parameter. Ekspresi lambda ini dipanggil sekali untuk setiap elemen di Iterable. Berikut adalah contoh iterasi elemen Iterable melalui forEach()metodenya:

List<String> list = new ArrayList><();

list.add("satu");
list.add("dua");
list.add("tiga");

list.forEach( (elemen) -> {
    System.out.println( elemen );
});
