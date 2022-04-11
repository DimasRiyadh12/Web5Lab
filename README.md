### Nama: Dimas Riyadh Alfajri
### Kelas: TI.20.A1
### Nim: 312010029
### Matkul: Pemrograman Web

# Praktikum 5: Javascript

### Pengantar Javascript
Javascript adalah bahasa pemrograman yang awalnya dirancang untuk berjalan di atas browser.
Namun, seiring perkembangan zaman, javascript tidak hanya berjalan di atas browser saja.
Javascript juga dapat digunakan pada sisi Server, Game, IoT, Desktop, dsb.

## Langkah-Langkah :

Persiapan membuat dokumen HTML dengan nama file lab5_javascript.html seperti berikut.

![img](ss/pict1.png)

![img](ss/pict2.png)

### Javascript Dasar

Pemakaian Alert sebagai property window.

![img](ss/pict3.png)

![img](ss/pict4.png)

Pemakaian method dalam objek

![img](ss/pict5.png)

![img](ss/pict6.png)

Pemakaian Prompt

![img](ss/pict7.png)

![img](ss/pict8.png)

![img](ss/pict9.png)

Pembuatan fungsi dan cara pemanggilannya

![img](ss/pict10.png)

![img](ss/pict11.png)

### Dasar Pemrograman di Javascript

Operasi dasar aritmatika

![img](ss/pict12.png)

![img](ss/pict13.png)

Seleksi kondisi (if..else)

![img](ss/pict14.png)

![img](ss/pict15.png)

Penggunaan operator switch untuk seleksi kondisi

![img](ss/pict16.png)

![img](ss/pict17.png)

![img](ss/pict18.png)

### Pembuatan Form

Form input

![img](ss/pict19.png)

![img](ss/pict20.png)

Form Button.

![img](ss/pict21.png)

![img](ss/pict22.png)

### Html DOM

Pilihan ini menggunakan checkbox dengan perhitungan otomatis

![img](ss/pict23.png)

![img](ss/pict24.png)


### Pertanyaan dan Tugas 

 1.Buat script untuk melakukan validasi pada isian form

### Jawaban!

Yaitu Membuat validasi nama, No.Telp, Email.

### Nama

Disini saya akan memberikan validasi berupa inputan hanya boleh menggunakan Huruf/Alphabet saja. Contoh : DimasRiyadh (benar), DimasRiyadhjr (salah)

![img](ss/pict25.png)

Penjelasan

 Membuat nama function Alphabet, dengan parameter dinamis yaitu (nilai,pesan)
 Data yang boleh dimasukkan adalah berupa "a-zA-Z"
 Jika selain data "a-zA-Z" ini dimasukkan, maka akan muncul pesan Alert "alert(pesan);"

![img](ss/pict26.png)

### No.Telp

Pada bagian ini akan saya berikan validasi berupa hanya angka saja yang boleh di inputkan, contoh: 12345 (benar), 123AB (salah).

![img](ss/pict27.png)

Penjelasan:

 var numberExp = /^[0-9]+$/; merupakan variabel numberExp yang diberi batasan validasi angka 0-9
 Arti Match pada "if(nilai.value.match(numberExp))" adalah string.match(), mencari string menggunakan Regular Expression (Regex)
 Jika salah atau inputan tidak benar maka akan ada pesan alert "alert(pesan);"

![img](ss/pict28.png)

### Email

Pada email akan diberikan validasi masih berupa Regular Expression. Contoh: dimasriyadh8291@gmail.com (benar), dimasriyadh8291@.com (salah).

![img](ss/pict29.png)

Penjelasan:

 membuat variabel email " var email = /^([a-zA-Z0-9_.+-])+@(([a-zA-Z0-9-])+.)+([a-zA-Z0-9]{2,4})+$/; " berupa huruf, angka dan simbol yang diperbolehkan dalam input sebuah email. Jika email salah maka akan ada pesan alert "alert(pesan);"

![img](ss/pict30.png)

### Berikut Penulisan Form yang benar

![img](ss/pict31.png)

![img](ss/pict32.png)

Cukup sekian dan Terimakasih.




