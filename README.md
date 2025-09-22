# WEb Sederhana

  Nama : ananda Friezy eka cahya 
   NIM : 31241011
 Kelas : TI24A4

   ## Tugas

   Jawab Pertanyaan Berikut
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah
error ketika terjadi kesalahan penulisan tag?
2. Apa perbedaan dari tag <p> dengan tag <br>, berikan penjelasannya!
3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar
proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top,
_parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?

### jawaaban

1. codingan biasa


```HTML

<!DOCTYPE html>
<html>
<head>
  <title>Identitas Ibnu</title>
</head>
<body>
  <h1>Belajar HTML</h1>
  <p>Nama: Ananda Friezy Eka Cahya</p>
  <p>Kelas : TI24A1</p>
  
  <!-- sub judul paragraf -->
  <h3>Menambahkan Gambar</h3>
  <!-- menambahkan gambar pada dokumen -->
  <img src="Logo_UPB.png" title="Logo Univeritas Pelita Bangsa">
</body>
</html>

```


penjelasan 

Jika tag ditulis benar, halaman akan tampil normal sesuai kode.
Jika ada kesalahan penulisan tag (misalnya <pp> bukan <p> atau <h3> ditutup dengan </h2>), browser biasanya tidak menampilkan pesan error.
Teks tetap muncul, tapi format tidak sesuai. Jadi, HTML “toleran” terhadap kesalahan, hanya saja hasil tampilannya bisa berantakan.

2. <p> = paragraph, digunakan untuk membuat paragraf baru. Secara default ada jarak atas & bawah.
<br> = line break, digunakan untuk pindah baris tanpa membuat paragraf baru. Tidak ada jarak tambahan.

Contoh:
``` HTML

<p>Ini paragraf pertama.</p>
<p>Ini paragraf kedua.</p>

Teks baris pertama<br>
Teks baris kedua
```

gambar 1.1

<img width="279" height="289" alt="image" src="https://github.com/user-attachments/assets/2e7b0605-54c5-47b4-85dc-60f9a280f886" />

3. alt → teks alternatif, muncul kalau gambar gagal dimuat. Juga dibaca oleh screen reader (untuk aksesibilitas).
title → teks tambahan (tooltip), muncul kalau mouse diarahkan ke gambar.

``` HTML
<img src="upb.jpg" alt="Foto pemandangan" title="Gunung indah">
```
gambar 1.2
<img width="747" height="411" alt="image" src="https://github.com/user-attachments/assets/97f2bfa8-68e5-4995-aa70-e18faa1e8a91" />



4.Sebaiknya tidak perlu isi dua-duanya.
Kalau kamu isi salah satu saja (misalnya width="300"), browser otomatis menyesuaikan tinggi gambar agar tetap proporsional.
Kalau isi dua-duanya tapi ukurannya tidak sesuai rasio asli gambar, hasilnya gambar bisa tampak gepeng atau melar.



5. Pada link tambahkan atribut target dengan nilai atribut bervariasi (_blank, _self, _top, _parent), apa yang terjadi pada masing-masing nilai atribut tersebut?

target="_blank" → link terbuka di tab/jendela baru.

target="_self" → link terbuka di halaman yang sama (default).

target="_top" → link terbuka di jendela penuh, menghapus semua frame (jika ada).

target="_parent" → link terbuka di halaman induk dari frame/iframe.

contoh

```HTML
<a href="https://www.google.com" target="_blank">Google (tab baru)</a><br>
<a href="https://www.google.com" target="_self">Google (halaman ini)</a><br>
<a href="https://www.google.com" target="_top">Google (jendela penuh)</a><br>
<a href="https://www.google.com" target="_parent">Google (halaman induk)</a>
```
gambar 1.3
<img width="647" height="136" alt="image" src="https://github.com/user-attachments/assets/5e757ec8-a5e0-4aab-91b0-ffc985ec2bce" />
