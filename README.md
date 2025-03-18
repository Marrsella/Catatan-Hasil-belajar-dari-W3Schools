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
2. Tulis beberapa HTML
    <img width="487" alt="Screenshot 2025-03-18 093536" src="https://github.com/user-attachments/assets/4710ff2f-228d-4145-a7bd-7fe60708c0e7" />
3. Simpan halaman HTML
    <img width="487" alt="Screenshot 2025-03-18 093536" src="https://github.com/user-attachments/assets/94178c57-c336-4a30-8fa7-512d361edfe7" />
4. Lihat halaman HTML di browser
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
Meskipun sudah dikasih spasi tambahan atau baris tambahan (enter) hasilnya secara otomatis tidak akana ada spasinya.
- Aturan Horizontal HTML<br>
Menggunakan tag <hr> untuk memberikan pemisah antara paragraf satu dengan paragraf lainnya dengan garis horizontal.
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












  











   










