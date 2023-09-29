# Nama  : Roswanda Nuraini
# NIM  : 312210328
# Kelas  : TI.22.A3

# <p align="center">Praktikum1 : HTML Dasar</p>

# Membuat Paragraf

- Buka VS Code dan buat file HTML baru. Setelah itu buat struktur dasar HTML

```<title>Tag HTML</title> ```

      <!-- paragraf pertama -->
      <p>
        Kami sedang belajar HTML dasar, pada matakuliah Pemograman Web di
        prodi Teknik Informatika Universitas Pelita Bangsa
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana
        dalam mengenal tag-tag dasar HTML.
      </p>
      
      <!-- paragraf kedua -->
      <p>
        Ini adalah paragraf yang terdiri dari beberapa kalimat yang saling
        mendukung sehingga terbentuk menjadi kesatuan. Paragraf dengan menggunakan
        tag dasar HTML.
      </p>                

- Paragraf memiliki tag yaitu (p) di dalam tag juga kita bisa menambahkan style seperti warna dan format teks

### hasil output

![Screenshot (312)](https://github.com/roswanda11/lab1web/assets/115516632/ec8cf2fe-97e4-41d4-a670-bb8585e4e06f)

- Mengatur Atribut Paragraf ```(align => justify, left, right, dan center)```

      <p align="center">
        Kami sedang belajar HTML dasar, pada matakuliah Pemograman Web di
        prodi Teknik Informatika Universitas Pelita Bangsa.
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana
        dalam mengenal tag-tag dasar HTML.
      </p>
  
### hasil output

![Screenshot (317)](https://github.com/roswanda11/lab1web/assets/115516632/6e1d9282-7013-4dff-bd29-a69733bf6201)

# Membuat Judul

- Heading adalah judul artikel Heading terbesar yaitu (h1) dan seterus nya akan kecil,namun yang biasa digunakan yaitu (h1) atau (h2)

      <!-- paragraf pertama -->
      <h1>Belajar Dasar HTML</h1>
      
       <!-- paragraf kedua -->
      <h2>Paragraf pada HTML</h2>

![Screenshot (314)](https://github.com/roswanda11/lab1web/assets/115516632/89ade512-032f-4aa5-aec7-b60a710d129a)

# Memformat Teks

- ```<span style="background-color: yellow;>``` Menyisipkan sesuatu yang khusus, lalu atribut style menambahkan style pada sesuatu tersebut.
- ```<b>``` Membuat teks bold.
- ```<i>``` Membuat teks italic.
- ```<u>``` Membuat teks underline.

  
      <!-- paragraf pertama -->
      <h1>Belajar Dasar HTML</h1>
      <p align="center">
        Kami sedang belajar HTML dasar, pada matakuliah <b>Pemograman Web</b> di
        prodi <i>Teknik Informatika</i> <mark>Universitas Pelita Bangsa</mark>.
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana
        dalam mengenal tag-tag dasar HTML.
      </p>
        
      <!-- paragraf kedua -->
      <h2>Paragraf pada HTML</h2>
      <p>
          Ini adalah paragraf yang terdiri dari beberapa kalimat yang saling
          mendukung sehingga terbentuk menjadi kesatuan. Paragraf dengan menggunakan
          tag dasar HTML.
      </p>

### hasil output

![Screenshot (316)](https://github.com/roswanda11/lab1web/assets/115516632/6206efe9-6b3a-4da4-9d3f-2c604ee6161a)

# Menyisipkan Gambar

- Untuk menambahkan foto menggunakan tag img dan ditaruh folder yang sesui untuk source tersebut

      <h3>Menambahkan gambar</h3>
      <img src="LOGO HIMATIF.png" width="200" title="Logo Himatif UPB">

### hasil output

![Screenshot (318)](https://github.com/roswanda11/lab1web/assets/115516632/468ed44c-dc9c-4355-8be3-6b6441f7cde3)

# Menambahkan Hyperlink

- Jadi ini adalah contoh bagaimana hasil menambahkan link pada tag HTML yaitu a herf dan hasil nya sebagai berikut

      <!-- menambahkan link navigasi -->
      <nav>
        <a href="lab1_dasar.html">Dasar HTML</a>
        <a href="lab1_halaman2.html">Halaman 2</a>
        <a href="http://www.google.com">Halaman Web Eksternal Google</a>
      </nav>
      <hr>

![Screenshot (320)](https://github.com/roswanda11/lab1web/assets/115516632/34dfe877-5dcb-42d4-929d-964de5c0d72d)

- Kemudian kita membuat lab1_halaman2.html

```<title>Halaman 2</title>```

# Jawab Pertanyaan Berikut

### 1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
Tidak ada. HTML berjalan seperti biasa.

### 2. Apa perbedaan dari tag ```<p>``` dengan tag ```<br>```, berikan penjelasannya!
```<br>``` digunakan untuk menggerakan teks ke barisan baru sedangkan ```<p>``` digunakan untuk membuat paragraf baru, ```<br>``` bisa digunakan untuk menambah barisan baru kedalam sebuah teks. 

### 3. Apa perbedaan atribut ```title``` dan ```alt``` pada tag <img>, berikan penjelasannya!
```alt``` adalah untuk menyediakan tag alt gambar untuk menggambarkan gambar ke crawler mesin pencari dan pembaca layar untuk aksesibilitas web yang lebih baik. ```title``` adalah untuk memberikan penjelasan tentang tag alt gambar dan URL gambar dalam atribut ```src```. 

### 4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
Hanya dengan menggunakan ```width``` foto akan menjadi lebih presisi tetapi ```height``` bisa mengatur foto semaunya 

### 5. Pada ```link``` tambahkan atribut ```target``` dengan nilai atribut bervariasi ```( _blank, _self, _top,_parent )```, apa yang terjadi pada masing-masing nilai antribut tersebut?
- ```_blank```: Membuka dokumen yang dituju di jendela atau tab baru.
- ```_self``` : Membuka dokumen yang dituju di jendela atau frame yang sama dengan elemen yang diklik. Ini adalah nilai default jika atribut target tidak ditentukan.
- ```_top``` : Membuka dokumen yang dituju di jendela penuh, menggantikan semua frame, termasuk frame luar. Jika elemen tersebut tidak ada dalam frame, perilakunya sama seperti _self.
- ```_parent``` : Membuka dokumen yang dituju di frame parent dari elemen yang diklik. Jika elemen tersebut tidak ada dalam frame, perilakunya sama seperti _self.
