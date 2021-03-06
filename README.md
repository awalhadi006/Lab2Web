# Lab2Web
<h1> Langkah-langkah Praktikum </h1>

<p>
<ol>
  <li><b>Membuat Dokumen HTML</b><br>
  Buatlah dokumen HTML dengan nama "lab2_css_dasar.html" seperti berikut.

![Screenshot_44](https://user-images.githubusercontent.com/24362384/114257379-e8607f80-99e9-11eb-8774-0a320a31490f.png)

Selanjutnya buka pada browser kalian (bisa berupa chrome, mozilla, dll) untuk melihat hasilnya.

![Screenshot_45](https://user-images.githubusercontent.com/24362384/114257432-3c6b6400-99ea-11eb-936b-61eacec527f8.png)

  <li><b>Mendeklarasikan CSS Internal</b><br>
  Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian head dokumen.
  
![Screenshot_46](https://user-images.githubusercontent.com/24362384/114257554-f8c52a00-99ea-11eb-9ccb-471259fdb12a.png)

Selanjutnya simpan perubahannya, dan lakukan refresh (reload) pada browser kalian untuk melihat hasil yang telah diubah sebelumnya.

![Screenshot_47](https://user-images.githubusercontent.com/24362384/114257590-2f02a980-99eb-11eb-9488-746da9bd8dbb.png)

  <li><b>Menambahkan Inline CSS</b><br>
  Kemudian tambahkan deklarasi inline CSS pada tag &lt;p&gt; seperti berikut.
 
    <p style="text-align: center; color: #ccd8e4;">
    
  Simpan kembali dan lakukan refresh pada browser kalian agar perubahannya terlihat.
  
![Screenshot_48](https://user-images.githubusercontent.com/24362384/114257752-468e6200-99ec-11eb-8b13-51fd120bb8b3.png)

  <li><b>Membuat CSS Eksternal</b><br>
  Buatlah file baru dengan nama <b>style_eksternal.css</b> kemudian buatlah deklarasi CSS seperti berikut.
  
![Screenshot_49](https://user-images.githubusercontent.com/24362384/114257884-0c719000-99ed-11eb-8fec-47ff079ee520.png)

Kemudian tambahkan tag &lt;link&gt; untuk merujuk file css yang sudah dibuat pada bagian &lt;head&gt;

![Screenshot_50](https://user-images.githubusercontent.com/24362384/114257927-62463800-99ed-11eb-8f39-e3c574b72243.png)

Selanjutnya refresh kembali browsernya agar terlihat perubahannya.

![Screenshot_51](https://user-images.githubusercontent.com/24362384/114257951-84d85100-99ed-11eb-9a45-93525b339924.png)

  <li><b>Menambahkan CSS Selector</b><br>
  Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Buka file <b>"style_eksternal.css"</b> yang telah kita buat sebelumnya, lalu tambahkan kode sebagai berikut.
  
![Screenshot_52](https://user-images.githubusercontent.com/24362384/114258085-69ba1100-99ee-11eb-8bed-1e31a9769de7.png)

Selanjutnya simpan file tersebut kemudian refresh kembali browsernya agar terlihat perubahannya.

![Screenshot_53](https://user-images.githubusercontent.com/24362384/114258113-92420b00-99ee-11eb-98cf-90b73a20c247.png)
</li></ol>
</p>

<h3> Pertanyaan dan Tugas </h3>
<p>
<ol>
  <li> Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada <i>CSS Cheat Sheet</i> yang diberikan pada file terpisah dari modul ini.
  <li> Apa perbedaan pendeklarasian CSS elemen <b>h1 {...}</b> dengan <b>#intro h1 {...}?</b> berikan penjelasannya!
  <li> Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
  <li> Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikut penjelasan dan contohnya! (&lt;p id="paragraf-1" class="text-paragraf"&gt;)
  </li></ol>

<h3> Jawaban </h3>
<ol>
  <li> Berikut Hasil eksperimen dalam mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada <i>CSS Cheat Sheet</i>.
    
![Screenshot_58](https://user-images.githubusercontent.com/24362384/114273478-5e91d000-9a44-11eb-88be-48d2f2713f39.png)

  <li> Perbedaan antara pendeklarasian CSS elemen <b>h1 {...}</b> dengan <b>#Intro h1 {...}?</b> adalah pada penggunaan tanda "#", dalam penggunaan "#" disebut juga ID Selector, ID Selector digunakan untuk menyeleksi elemen berdasarkan ID tertentu. Contoh di dalam css: #intro h1 {text-align: left}. Contoh tersebut menyeleksi element yang memiliki attribute ID dengan value "intro h1" agar tulisannya rata kiri didalam html. Dengan catatan sebuah halaman atau dokumen tidak boleh terdapat lebih dari satu <i>id</i> dengan value yang sama.
  <li> Deklarasi yang lebih dulu ditampilkan pada browser saat menggunakan deklarasi CSS secara internal, eksternal, dan inline adalah deklarasi CSS secara inline. karena inline merupakan deklarasi yang ditulis langsung pada atribut elemen HTML.<br>
  Contoh jika hanya menggunakan deklarasi eksternal:

![Screenshot_54](https://user-images.githubusercontent.com/24362384/114263408-769b2c80-9a0f-11eb-8bdc-a1920e8e26a6.png)

  Contoh jika menggunakan deklarasi internal dan eksternal:
  
![Screenshot_55](https://user-images.githubusercontent.com/24362384/114263419-8a469300-9a0f-11eb-85f3-9f6f173f4316.png)

  Contoh jika menggunakan deklarasi internal, eksternal, dan inline:
  
![Screenshot_56](https://user-images.githubusercontent.com/24362384/114263431-992d4580-9a0f-11eb-9fff-02f0ee6211c0.png)

  <li>Perbedaan dari selector class dan id adalah selector class di panggil pada css dengan menggunakan tanda titik ".", dan id di panggil pada css menggunakan tanda pagar "#". Lalu perbedaan lainnya adalah selector class dapat di berikan pada banyak element html dan dapat di panggil sekaligus, sedangkan id hanya dapat bekerja pada satu element saja.
  Jika nilai pada selector id dan class sama, maka yang akan muncul adalah nilai pada selector id.
  Contohnya :
  
  ![Screenshot_57](https://user-images.githubusercontent.com/24362384/114273401-12df2680-9a44-11eb-9593-92008c649f4f.png)


  
</li></ol></p>
