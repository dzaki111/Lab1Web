# Lab1Web
#### Nama   = DZAKI ARIF RAHMAN  
#### Kelas  = TI.24.A4  
#### NIM    = 312410312  
#### Matkul = Pemograman Web 1 
# Praktikum 1 – HTML Dasar


## Langkah Praktikum

### 1. Membuat Struktur Dasar HTML

Membuat file `lab 1.html` dengan struktur dasar dokumen HTML5:

```html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Lab 1 - Tag Dasar HTML</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  ...
</body>
</html>
```

---

### 2. Membuat Paragraf

Menambahkan paragraf menggunakan tag `<p>` dengan atribut align:

```html
<h2>Contoh Paragraf di HTML</h2>
<p style="text-align:center">
  <strong>Saat ini kita sedang berlatih dasar HTML</strong> pada mata kuliah Pemrograman Web.
</p>
<p style="text-align:right">
  Paragraf adalah kumpulan kalimat ... menggunakan elemen <code>&lt;p&gt;</code>.
</p>
```

---

### 3. Menambahkan Judul (Heading)

Menggunakan heading untuk judul dan subjudul:

```html
<header>
  <h1>Pengenalan Tag Dasar HTML</h1>
  <p class="lead small">Praktikum 1 — Dasar Pemrograman Web</p>
</header>
```

---

### 4. Memformat Teks

Menggunakan berbagai tag pemformatan:

```html
<h3>Format Tulisan</h3>
<p>
  Contoh penggunaan <b>teks tebal</b>, <i>teks miring</i>,
  <del>teks dicoret</del>, dan <ins>teks disisipkan</ins>.
</p>

<h3>Baris Baru vs Paragraf</h3>
<p>
  Tag &lt;br&gt; hanya membuat baris baru.<br>
  Contoh baris kedua menggunakan &lt;br&gt;.
</p>
```

---

### 5. Menyisipkan Gambar

Menambahkan gambar dengan tag `<img>`:

```html
<h3>Menyisipkan Gambar</h3>
      <img src="https://bloguna.com/wp-content/uploads/2025/08/Logo-Universitas-Pelita-Bangsa-UPB-Format-PNG-CDR-EPS-SVG-PDF-AI-300x228.png" alt="Logo Universitas Pelita Bangsa" width="250">
```

---

### 6. Menambahkan Hyperlink & Navigasi Antarhalaman

Menambahkan link ke halaman kedua:

```html
<h3>Tautan ke Halaman 2</h3>
<p><a href="halaman2.html">Klik di sini untuk ke Halaman 2</a></p>

<nav>
  <a href="lab 1.html" target="_self">Halaman Utama</a>
  <a href="halaman2.html" target="_self">Halaman 2</a>
</nav>
```

Halaman kedua `halaman2.html` dibuat dengan isi:

```html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Halaman 2 - Lab 1</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <main class="container">
    <header>
      <h1>Halaman Kedua</h1>
      <p class="lead small">Latihan navigasi antar halaman</p>
    </header>

    <nav>
      <a href="lab 1.html" target="_self">Kembali ke Halaman Utama</a>
      <a href="halaman2.html" target="_self">Halaman 2</a>
    </nav>

    <section class="article">
      <h2>Isi Halaman 2</h2>
      <p>Ini adalah halaman kedua sebagai latihan untuk menghubungkan beberapa halaman HTML.</p>

      <h3>Contoh Daftar</h3>
      <ul>
        <li>HTML untuk struktur</li>
      </ul>

      <h3>Link Balik ke Halaman 1</h3>
      <p><a href="lab 1.html">Klik di sini untuk kembali ke Halaman 1</a></p>
    </section>

    <footer class="small center">
      &copy; 2025 — Praktikum Web
    </footer>
  </main>
</body>
</html>
```

---

## Pertanyaan 

<img width="962" height="235" alt="image" src="https://github.com/user-attachments/assets/17bf6004-59a8-416c-94c3-c5b7875ae5fb" />

## Jawaban

1.  Browser biasanya masih nampilin halamannya, cuma tampilannya jadi berantakan atau ada yang nggak muncul sesuai harapan.  

2. `<p>` bikin paragraf baru (blok teks), sedangkan `<br>` cuma buat pindah baris di paragraf yang sama.  

3. `title` muncul kayak tooltip pas kursor diarahkan ke gambar, sedangkan `alt` jadi teks pengganti kalau gambar gagal dimuat.  

4. cukup isi salah satu (misalnya width). Kalau dua-duanya diisi nggak sesuai rasio asli bisa bikin gambarnya ketarik/gepeng.  

5.  - `_self` → buka link di tab/frame yang sama (default).  
    - `_blank` → buka link di tab baru.  
    - `_top` → buka link di frame paling atas (menghapus semua frame).  
    - `_parent` → buka link di frame induk (satu tingkat di atas).  

---


