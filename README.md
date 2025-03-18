# Catatan Hasil belajar dari W3Schools
# Pengantar HTML
HTML (Hyper Text Markup Language) adalah bahasa markup standar untuk membuat halaman web dan menggambarkan struktur halaman web. HTML terdiri dari serangkaian elemen untuk menampilkan konten dan memberi label pada konten. Adapun struktur dalam HTML:
1. &lt;head&gt; : informasi meta tentang halaman HTML
2. &lt;tittle&gt; : judul untuk halaman HTML (ditampilkan di judul browser)
4. &lt;body&gt; : wadah untuk semua konten terlihat
5. &lt;h1&gt; : judul pertama
6. &lt;p&gt; : paragraf pertama dan paragraf lainnya.
Semua struktur ini diakhiri dengan / atau tag penutup.

# Editor HTML
Mempelajari HTML dengan Notepad
1. Buka Notepad
2. Tulis beberapa HTML<br>
    <img width="487" alt="Screenshot 2025-03-18 093536" src="https://github.com/user-attachments/assets/4710ff2f-228d-4145-a7bd-7fe60708c0e7" />
    
3. Simpan halaman HTML<br>
    <img width="487" alt="Screenshot 2025-03-18 093536" src="https://github.com/user-attachments/assets/94178c57-c336-4a30-8fa7-512d361edfe7" />
    
4. Lihat halaman HTML di browser<br>
   ![Screenshot 2025-03-18 093504](https://github.com/user-attachments/assets/357a0030-bfc1-49bf-a1b0-210707c5a668)

# HTML Dasar
1. Dokumen HTML<br>
Dokumen HTML harus dimulai dengan deklarasi tipe dokumen &lt;!DOCTYPE 
html&gt;. Dokumen HTML dimulai dengan &lt;html&gt dan diakhiri &lt;/html&gt;, sedangkan untuk bagian yang terlihat berada diantara &lt;body&gt; dan &lt;/body&gt;.

2. Deklarasi &lt;!DOCTYPE&gt;<br>
- mewakili jenis dokumen dan membantu browser menampilkan halaman web dengan benar
- hanya boleh muncul 1x sebelum tag HTML apapun
- tidak peka huruf besar/kecil
- untuk HTML5 adalah &lt;!DOCTYPE html&gt;

3. Judul HTML<br>
Didefinisikan dengan tag &lt;h1&gt; (untuk judul yang penting) sampai &lt;h6&gt; (untuk judul yang paling tidak penting)

4. Paragraf HTML<br>
Didefinisikan dengan &lt;p&gt;

5. Tautan HTML<br>
Didefinisikan dengan &lt;a&gt;

6. Gambar HTML<br>
Didefinisikan dengan &lt;img&gt;.
- src (sumber)
- alt (teks alternatif)
- width (lebar)
- height (tinggi)

7. Cara melihat sumber HTML<br>
Lihat kode sumber HTML dengan klik CTRL U, lalu klik kanan pada elemen dan pilih "Periksa".

# Elemen HTML
- Elemen HTML dapat bersarang, berarti suatu elemen dapat berisi elemen lain. 
- Elemen HTML kosong dengan tag &lt;br&gt; (tanpa tag penutup untuk mendefinisikan jeda baris)

# Atribut HTML
Semua elemen HTML memiliki atribut. Atribut disarankan menggunakan huruf kecil dan dikutip.

- Atribut href <br>
Mendefinisikan hyperlink dengan tag &lt;a&gt; untuk menentukan URL halaman yang dituju oleh tautan tersebut
- Atribut src <br>
Tag &lt;img&gt; untuk menyematkan gambar dan atribut src menentukan jalur ke gambar yang ditampilkan.
- Atribut lebar dan tinggi <br>
Tag &lt;img&gt; memerlukan atribut width (lebar) dan (tinggi)
- Atribut alt<br>
Tag &lt;img&gt; memerlukan alt untuk menentukan teks alternatif untuk gambar.
- Atribut gaya<br>
Untuk menambahkan gaya ke suatu elemen, seperti warna, font, ukuran, dan lainnya.
- Atribut lang<br>
Sertakan lang untuk atribut di dalam &lt;html&gt; tag untuk menyatakan bahasa halaman web untuk membantu mesin pencari. misalnya menentukan bahasa inggris &lt;html lang="en"&gt; dan untuk bahasa inggris sebagai bahasa dan negara &lt;html lang="en-US"mg&gt;.
- Judul Atribut <br>
Atribut tittle mendefiniskan beberapa informasi tambahan tentang suatu elemen.

# Judul HTML
- &lt;h1&gt; itu judul utama dengan ukuran besar sedangkan jika &lt;h2&gt; sampai &lt;6&gt; ukurannya akan mengecil jadi bisa digunakan sebagai sub judul.
- Untuk menentukan ukuran setiap judul bisa menggunakan atribut style dan properti CSS font-size:, contoh: <br>
&lt;h1 style="font-size:60px;"&gt;Heading 1&lt;/h1&gt;

# HTML Paragraf &lt;p&gt;
- Tampilan HTML <br>
Meskipun sudah dikasih spasi tambahan atau baris tambahan (enter) hasilnya secara otomatis tidak akan ada spasinya.
- Aturan Horizontal HTML<br>
Menggunakan tag &lt;hr&gt; untuk memberikan pemisah antara paragraf satu dengan paragraf lainnya dengan garis horizontal.
- Pemutusan Baris HTML<br>
Untuk memberikan spasi maka perlu menggunakan elemen &lt;br&gt;
- Menulis Puisi<br>
Perlu mengganti &lt;p&gt; dengan &lt;pre&gt; untuk mempertahankan spasi yang kita beri sebelumnya.

# Gaya HTML
Menggunakan atribut Style untuk menambahkan gaya ke suatu elemen, seperti warna, font, ukuran, dll. Atribut style memiliki sintaksis: <br>
&lt;tagname style="property:value;"&gt; <br>
contoh penggunaan atribut: <br>
&lt;p style="color:red;"&gt;I am red&lt;/p&gt;, maka hasil tulisannya merah.

Properti untuk Style
- warna Latar Belakang : background-color 
- warna Teks : color
- font teks : font-family
- ukuran teks : font-size
- align teks : text-align

# Pemformatan Teks HTML
Elemen pemformatan dirancang untuk menampilkan jenis teks khusus:
- &lt;b&gt; : teks tebal
- &lt;strong&gt; : teks penting
- &lt;i&gt; : teks miring
- &lt;em&gt; : teks yang ditekankan
- &lt;mark&gt; : teks yang ditandai
- &lt;small&gt; : teks lebih kecil
- &lt;del&gt; : teks dihapus
- &lt;ins&gt; : teks disisipkan
- &lt;sub&gt; : teks subskrip (pangkat bawah)
- &lt;sup&gt; : teks superskrip (pangkat atas)

# Kutipan HTML
- &lt;blockquote&gt; : untuk definisikan bagian yang dikutip dari sumber lain
- &lt;q&gt; : untuk definisikan kutipan pendek (ada tanda kutip)
- &lt;abbr&gt; : untuk definisikan singkatan.
- &lt;address&gt; : untuk definisikan informasi penulis (ditampilkan italic)
- &lt;cite&gt; : untuk definisikan judul suatu karya (ditampilkan italic)
- &lt;bdo&gt; : untuk mengganti arah teks saat ini

# Komentar HTML
- Tag Komentar HTML
Untuk menambahkan komentar ke sumber HTML perlu menggunakan sintaks berikut:<br>
&lt;!-- Write your comments here --&gt; <br>
ini tidak ditampilkan di browser

- Dengan komentar kita dapat:
1. menempatkan pemberitahuan dan pengingat dalam kode HTML
2. menyembunyikan konten sementara
3. menyembunyikan konten sebaris

# Warna HTML
1. Nama Warna
- Tomato : merah
- Orange : oren
- DodgerBlue : biru
- MediumSeaGreen : hijau
- Gray : abu-abu
- SlateBlue : Ungu
- Violet : pink
- LightGray : abu-abu muda
  
2. Warna Teks
Contoh penggunaan: <br>
&lt;h1 style="color:Tomato;">Hello World</h1&gt;

3. Warna Batas
Contoh penggunaan: <br>
&lt;h1 style="border:2px solid Tomato;">Hello World</h1&gt;

4. Nilai Warna (stabilo)
Contoh penggunaan: <br>
&lt;h1 style="background-color:rgb(255, 99, 71);"&gt;... &lt;/h1&gt;

# Bahasa Pemograman HTML dan CSS
CSS (Cascading Style Sheets) digunakan untuk memformat tata letak halamat web. 

Berikut adalah atribut CSS HTML: <rb>
 - style : untuk gaya sebaris

Berikut adalah elemen CSS HTML: <rb> 
 - &lt;style&gt; : untuk menentukan CSS internal
 - &lt;link&gt; : untuk merujuk ke file CSS eksternal
 - &lt;head&gt; : untuk menyimpan elemen &lt;style&gt; dan &lt;link&gt;

Berikut adalah properti CSS HTML: <rb>
 - color : untuk warna teks
 - font-family : untuk font teks
 - font size : untuk ukuran teks
 - border : untuk batas
 - padding : untuk spasi di dalam perbatasan
 - margin : untuk spasi di laur batas

# Tautan HTML (Hyperlink)
Ketika diklik tautannya dapat melompat ke dokumen lain. Tag yang digunakan &lt;a&gt; memiliki sintaks berikut: <br>
&lt;a href="url"&gt;Link text&lt;/a&gt;

1. Atribut Target (menentukan tempat untuk membuka dokumen yang ditautkan)
- _self: Default. Membuka dokumen di jendela/tab yang sama saat diklik
- _blank: Membuka dokumen di jendela atau tab baru
- _parent: Membuka dokumen di bingkai induk
- _top: Membuka dokumen di badan penuh jendela

2. URL Absolut vs. URL Relatif
Menggunakan atribut href. Bedanya kalau Absolut (web lengkap), sedangkan relative (tanpa bagian "https://wwww")

3. Menggunakan Gambar Sebagai Tautan
Dengan cara memasukkan tag &lt;img&gt; di dalam tag &lt;a&gt;

 4. Tautan ke alamat email
Dengan cara menggunakan mailto: di dalam atribut href.

5. Tombol sebagai tautan
Dengan cara menggunakan tombol HTML JavaScript.

6. Judul Tautan
Dengan cara menggunakan atribut tittle.

# Gambar HTML
Tag &lt;img&gt; memerlukan dua atribut:
- src : Menentukan jalur ke gambar
- alt : Menentukan teks alternatif untuk gambar

Berikut sintaksisnya, <br>
&lt;img src="url" alt="alternatetext"&gt;

- Gunakan HTML width adn height untuk ukuran lebar dan tinggi gambar
- Gunakan properti CSS float untuk membiarkan gambar melayang ke kanan dan ke kiri

# Ikon HTML
Cara menambahkan favicon di HTML:
1. simpan gambar favicon Anda ke direktori akar server web Anda, atau buat folder di direktori akar yang disebut gambar
2.  simpan gambar favicon Anda di folder ini. Nama umum untuk gambar favicon adalah "favicon.ico"
3. tambahkan &lt;link&gt;elemen ke file "index.html" Anda, setelah &lt;title&gt;elemen
4. simpan berkas "index.html" dan muat ulang di peramban

# Judul Halaman HTML
Elemen &lt;title&gt;:
- mendefinisikan judul di bilah alat browser
- memberikan judul untuk halaman saat ditambahkan ke favorit
- menampilkan judul halaman di hasil mesin pencari

# Tabel HTML &lt;table&gt;
Setiap sel tabel didefinisikan oleh tag &lt;td&gt; dan &lt;/td&gt; <br>
Berikut adalah tag yang dipakai dalam membuat tabel di HTML: <br>
1. &lt;table&gt; : mendefinisikan sebuah tabel
2. &lt;th&gt; : mendefinisikan judul tabel
3. &lt;tr&gt; : mendefinisikan baris dalam tabel
4. &lt;td&gt; : mendefinisikan sel dalam tabel
5. &lt;caption&gt; : mendefinisikan keterangan tabel
6. &lt;colgroup&gt; : menentukan grup dari satu kolom atau lebih di sebuah tabel untuk pemformatan.
7. &lt;col&gt; : menentukan properti kolom untuk setiap kolom dalam elemen &lt;colgroup&gt;
8. &lt;thead&gt; : mengelompokkan konten header dalam sebuah tabel
9. &lt;tbody&gt; : mengelompokkan konten body dalam sebuah tabel
10. &lt;tfoot&gt; : mengelompokkan konten footer dalam sebuah tabel

# Daftar HTML
1. Daftar HTML Tidak Berurut (pakai dot) <br>
Dimulai dengan tag &lt;ul&gt;, setiap item dalam daftar dimulai dengan &lt;li&gt;
2. Daftar HTML yang Diurutkan (pakai nomor)
Dimulai dengan tag &lt;ol&gt;, setiap item dalam daftar dimulai dengan &lt;li&gt;
3. Daftar Deskripsi HTML
- &lt;dl&gt; : untuk mendefinisikan daftar deskripsi
- &lt;dt&gt; : untuk mendefinisikan istilah (nama)
- &lt;dd&gt; : untuk mendeskripsikan setiap istilah

# Blok HTML dan ELemen Sebaris (border)
- Dua elemen blok yang umum digunakan adalah:
1. &lt;p&gt; : mendefinisikan paragraf dalam dokumen HTML
2. &lt;div&gt; : mendefinisikan divisi atau bagian dalam dokumen HTML

- &lt;span&gt; digunakan untuk memborder kata yang dipilih saja. Jika digabungkan dengan CSS maka dapat memberi gaya pada bagian teks namun memerlukan atribut style, class, dan id.

  # Elemen Div HTML
  1. Untuk Kalimat dengan menggunakan &lt;div&gt;
  2. Untuk blok semua kalimat maka letakkan &lt;div&gt; sebelum menaruhkan elemen lainnya
  3. Untuk blok rata tengah maka atur margin properti CSS ke auto
  4. Untuk blok paragraf yang berbeda maka tambahkan beberapa &lt;div&gt; pada halaman yang sama.
  5. Untuk blok berdampingan pakai properti CSS &lt;float&gt; ini hasilnya akan mepet, jika ingin ada celah maka pakai in-line block.
 
# Atribut Kelas HTML
1. Atribut kelas digunakan untuk menunjuk ke nama kelas dalam style sheet.
2. Nama kelas peka pada huruf kecil dan besar
3. getElementsByClassName() digunakan JavaScript untuk mengakses elemen dengan nama kelas tertentu.

 # Atribut id HTML
 Digunakan untuk menentukan id unik untuk elemen HTML. Nama id peka dengan huruf kecil dan besar. Setidaknya atribut id mengandung satu karakter, tidak dapat dimulai dengan angka, dan tidak boleh spasi.

 - Atribut id <br>
Nilai atribut id harus unik dalam dokumen HTML. Atribut ini iddigunakan untuk menunjuk ke deklarasi gaya tertentu dalam lembar gaya.
- Perbedaan antara kelas dan id <br>
Kelas bisa digunakan oleh beberapa elemen HTML sedangkan nama id hanya boleh digunakan oleh satu elemen HTML saja.
- Bookmark HTML dengan ID dan Tautan <br>
Untuk menggunakan bookmark, harus membuatnya terlebih dahulu, lalu menambahkan tautan ke dalamnya. Lalu, saat tautan diklik, halaman akan bergulir ke lokasi yang terdapat penanda halaman.
- Menggunakan atribut id di JavaScript <br>
JavaScript dapat mengakses elemen dengan id tertentu dengan getElementById().

# Iframe HTML
Digunakan untuk menampilkan halaman web di dalam halaman web. Sintaksisnya adalah sebagai berikut:
&lt;iframe src="url" title="description"&gt;&lt;/iframe&gt;

- Mengatur tinggi dan lebar Iframe <br>
Gunakan atribut height dan width.
- Hapus batasan <br>
Dengan cara tambahkan style dan gunakan properti CSS border.
- Target untuk tautan <br>
Atribut targettautan harus merujuk ke nameatribut iframe.

# Bahasa Pemogramana HTML dan JavaScript
Ada 2 tag HTML yang digunakan yaitu: <br>
1. &lt;script&gt; untuk mendefinisikan skrip sisi klien (JavaScript)
2. &lt;nonscript&gt; untuk mendefinisikan konten alternatif yang akan ditampilkan kepada pengguna yang telah menonaktifkan skrip di browser mereka.

# Jalur Berkas HTML
- Jalur Berkas HTML
Jalur berkas menggambarkan lokasi berkas dalam struktur folder situs web. Jalur berkas digunakan saat menautkan ke berkas eksternal, seperti: <br>
1. Halaman web
2. Gambar
3. Lembar gaya
4. JavaScript dalam bahasa Inggris

- Jalur File Absolut <br>
URL lengkap ke suatu berkas.

- Jalur File Relatif <br>
Menunjuk ke berkas yang relatif terhadap halaman saat ini.

# Kepala HTML
- &lt;head&gt; : untuk metadata (data tentang data) diletakkan antara &lt;html&gt; dan &lt;body&gt;.
- &lt;title&gt; : untuk menentukan judul dokumen.
- &lt;style&gt; : untuk menentukan informasi gaya untuk satu halaman HTML.
- &lt;link&gt; : untuk mendefinisikan hubungan antara dokumen saat ini dan sumber daya eksternal. 
- &lt;meta&gt; : untuk menentukan set karakter, deskripsi halaman, kata kunci, penulis dokumen, dan pengaturan viewport (area yang terlihat oleh pengguna di halaman web).
- &lt;script&gt; : untuk mendefinisikan JavaScript sisi klien.
- &lt;base&gt; : menentukan URL dasar dan/atau target untuk semua URL relatif di suatu halaman.

# Tata Letak HTML
- &lt;header&gt; : Menentukan header untuk dokumen atau bagian
- &lt;nav&gt; : Menentukan sekumpulan tautan navigasi
- &lt;section&gt; : Menentukan bagian dalam dokumen
- &lt;article&gt; : Mendefinisikan konten yang independen dan mandiri
- &lt;aside&gt; : Mendefinisikan konten selain konten (seperti sidebar)
- &lt;footer&gt; : Menentukan footer untuk dokumen atau bagian
- &lt;details&gt; : Menentukan detail tambahan yang dapat dibuka dan ditutup oleh pengguna sesuai permintaan
- &lt;summary&gt; : Menentukan judul untuk &lt;details&gt; elemen

Ada 4 teknik tata letak HTML
1. Kerangka kerja CSS <br>
menggunakan kerangka kerja CSS, seperti W3.CSS atau Bootstrap .
2. Properti float CSS
3. Kotak fleksibel CSS <br>
memastikan bahwa elemen berperilaku sesuai prediksi saat tata letak halaman harus mengakomodasi berbagai ukuran layar dan perangkat tampilan yang berbeda.
4. Jaringan CSS <br>
dengan baris dan kolom, sehingga memudahkan dalam mendesain halaman web tanpa harus menggunakan float dan pemosisian.

# Desain Web Responsif HTML
tentang penggunaan HTML dan CSS untuk secara otomatis mengubah ukuran, menyembunyikan, mengecilkan, atau memperbesar situs web, agar terlihat bagus di semua perangkat (desktop, tablet, dan ponsel).
1. Mengatur viewport <br>
Dengan menambahkan &lt;meta&gt; ke semua halaman web.
2. Gambar responsif <br>
gambar yang skalanya dapat disesuaikan dengan ukuran browser apa pun. Kalau pakai width maka bisa di zoom, sedangkan kalau pakai max-width maka tidak bisa dizoom besar dari ukuran aslinya.
3. Menampilkan Gambar Berbeda Tergantung pada Lebar Browser <br>
&lt;picture&gt; untuk menentukan gambar yang berbeda untuk ukuran jendela browser yang berbeda.
4. Ukuran Teks Responsif <br>
Ukuran teks dapat diatur dengan satuan "vw", yang berarti "lebar tampilan".

# Kode Komputer HTML
- &lt;kbd&gt; : mendefinisikan input keyboard
- &lt;samp&gt; : mendefinisikan contoh keluaran dari program komputer
- &lt;code&gt; : mendefinisikan sepotong kode komputer
- &lt;var&gt; : mendefinisikan variabel dalam pemrograman atau dalam ekspresi matematika
- &lt;pre&gt; : endefinisikan teks yang telah diformat sebelumnya

#



   



  

  



























  











   










