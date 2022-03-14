| Nama      | Shobahus Solichin  |
| ----------- | ----------- |
| NIM     | 312010076       |
| Kelas   | TI.20.A.1        |

## **Langkah-Langkah Praktikum**

Persiapan membuka VSCode dan Browser

![foto](foto/foto1.png)

Kemudian buat file baru dengan nama Lab1_tag_dasar.html dan tambahkan dasar dokumen HTML. 

# Modul Praktikum Pemrograman Web

![foto](foto/foto2.png)

kemudian selanjutnya,buka file tersebut pada web browser misalnya **google chrome.** 

![foto](foto/foto3.png)

# **1. Membuat Paragraf**

![foto](foto/foto4.png)

selanjutnya simpan kembali perubahannya, dan lakukan refresh pada web browser,lihat hasilnya.

# Modul Praktikum Pemrograman Web

![foto](foto/foto5.png)

Kemudian atur atribut paragraf seperti berikut, dan amati perubahanya.

![foto](foto/foto6.png)

Simpan kembali dan amati perubahannya dengan melakukan refresh pada web browser. 
Selanjutnya silakan ubah-ubah nilai atributnya (*align => justify, left, right, dan center*) untuk melihat perbedaan lainnya. 

## **2. Menambahkan Judul**
Seperti sudah dijelaskan pada materi bahwa judul memiliki 6 level yaitu mulai h1 sampai h6.Kemudian tambahkan judul h1 sebelum paragraf pertama dan tambahkan sub judul h2 sebelum paragraf kedua

![foto](foto/foto9.png)

Simpan perubahannya dan lihat hasilnya dengan melakukan refresh pada browser.

# **Modul Praktikum Pemrograman Web**

![foto](foto/foto8.png)

## **3. Memformat teks**
Lakukan pemformatan teks yang ada pada paragraf yang sudah ada sebelumnya, mengacu kepada penjelasan materi pemformatan teks, sehingga tampilannya seperti berikut.

![foto](foto/foto121.png)

Lakukan eksperimen lainnya dengan tag-tag pemformatan teks yang ada

## **4.Menyisipkan Gambar**
Untuk menyisipkan gmbar, siapkan gambar yang akan disisipkan pada halaman web, kemudian simpan file gambar tersebut satu folder dengan file dokumen html. Atau bisa juga menyisipkan gambar dari website external.

**Modul Praktikum Pemrograman Web**

![foto](foto/foto11.png)

Kemudian tambahkan tag img setelah paragraf yang kedua, dengan menambahkan heading 3 sebelumnya.

![foto](foto/foto13.png)

Simpan perubahannya, kemudian refresh browser.
![foto](foto/foto120.png)

**Modul Praktikum Pemrograman Web**

Gambar akan ditampilkan apa adanya sesuai dengan ukuran aslinya. Untuk mengatur ukuran gambar, dapat digunakan atribut witdh dan height dengan nilai integer yang disesuaikan.

![foto](foto/foto14.png)

## **5. Menambahkan Hyperlink**

Tambahkan hyperlink pada dokumen sebelum heading 1 seperti berikut.

![foto](foto/foto15.png)

Buat satu file lagi dengan nama lab1_halaman2.html kemudian isi dokumen tersebut dengan tag html dasar dan dengan isi bebas, boleh mengcopy dari halaman sebelumnya.

![foto](foto/foto171.png)

# **Jawab Pertanyaan Berikut**

1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah 
error ketika terjadi kesalahan penulisan tag?
2. Apa perbedaan dari tag `<p>` dengan tag `<br>`, berikan penjelasannya!
3. Apa perbedaan atribut title dan alt pada tag `<img>`, berikan penjelasannya!
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar 
proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, 
_parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?

## Jawab
1. Saya akan melakukan perubahan pada tag html, gambar yang ada dibawah ini yaitu merupakan syntax HTML sebelum saya merubahnya
![foto](foto/foto18.png "before")
Lalu ketika saya hilangkan akhiran pada Tag `</h1>`menjadi `<h1>`, maka yang akan terjadi seluruh elemen dibawah tag tersebut akan berubah mengikuti Tag `<h1>` dikarenakan tidak ada akhiran/penutup Tag tersebut. 
Seperti gambar dibawah ini.
![foto](foto/foto19.png "after")

2. Tag `<p>` berfungsi untuk memberi perintah paragraf pada halaman html

	Tag `<br>` berfungsi untuk memberikan perintah breakline atau baris baru
![foto](foto/foto20.png "paragraf & br")

3. `title` berfungsi untuk memberikan judul pada gambar

	`alt` berfungsi untuk menunjukkan sebuah alternate text (teks pengganti) yang akan muncul apabila gambar tidak dapat ditampilkan.

	gambar dibawah ini menunjukan perbedaan title dan alt
![foto](foto/foto21.png "alt title")

4.Menurut saya Kedua property ini sangat penting dan merupakan bagian yang tidak terpisahkan dari sebuah website karena masing-masing Tag atau Element pada sebuah HTML perlu memiliki ukuran yang ideal, sebab itu berpengaruh dalam pengaturan tataletak dan tampilan sebuah website,

	Kecuali pada kondisi tertentu seperti gambar sudah memiliki ukuran yang pas/proporsional cukup mengatur width nya saja
![foto](foto/foto22.png)  

5. `_blank` untuk membuka link di tab baru

	`_self` untuk membuka link di frame link itu berada

	`_top` untuk membuka link di frame paling atas (paling luar).  contohnya jika di website(1) di dalamnya ada website(2) lalu di website(2) di dalamnya ada website (3) lalu di website (3) ini ada link dan kita klik, maka link akan terbuka di website(1)

	`_parent` untuk membuka link di frame yang satu tingkat di atas frame link tersebut berada. contohnya jika di website(1) di dalamnya ada website(2) lalu di website(2) ini ada link dan kita klik, maka link akan terbuka di website(1)