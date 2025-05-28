<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
 
</head>
<body>

  <h1>📘 Penjelasan Lengkap Perintah Git</h1>

  <h2>🔹 <code>git init</code></h2>
  <blockquote>
    <strong>Fungsi:</strong> Menginisialisasi repository Git lokal di folder proyek kamu.<br />
    <strong>Artinya:</strong> Folder proyek kamu sekarang menjadi repositori Git, dan Git mulai bisa melacak perubahan file di dalamnya. Akan terbentuk folder <code>.git</code> tersembunyi sebagai database versi.
  </blockquote>

  <pre><code>git init</code></pre>

  <h2>🔹 <code>git add .</code></h2>
  <blockquote>
    <strong>Fungsi:</strong> Menambahkan seluruh file dan folder yang ada di dalam direktori ke <em>staging area</em>.<br />
    <strong>Artinya:</strong> Semua file yang ada (bukan hanya satu file tertentu seperti <code>README.md</code>) disiapkan agar bisa dimasukkan ke commit berikutnya. Titik (<code>.</code>) berarti "semua file dan folder".
  </blockquote>

  <pre><code>git add .</code></pre>

  <h2>🔹 <code>git commit -m "first commit"</code></h2>
  <blockquote>
    <strong>Fungsi:</strong> Menyimpan snapshot dari file yang sudah ditambahkan ke staging area, dengan pesan <code>"first commit"</code>.<br />
    <strong>Artinya:</strong> Kamu menciptakan versi awal dari proyekmu dan menyimpan catatan perubahan tersebut ke dalam Git dengan keterangan tersebut.
  </blockquote>

  <pre><code>git commit -m "first commit"</code></pre>

  <h2>🔹 <code>git branch -M main</code></h2>
  <blockquote>
    <strong>Fungsi:</strong> Mengubah nama branch aktif menjadi <code>main</code>.<br />
    <strong>Artinya:</strong> Branch default awalnya bernama <code>master</code>, dan sekarang kamu ubah menjadi <code>main</code> sesuai standar baru di GitHub dan komunitas.
  </blockquote>

  <pre><code>git branch -M main</code></pre>

  <h2>🔹 <code>git remote add origin https://github.com/ariandika79754/Belajar-dasar.git</code></h2>
  <blockquote>
    <strong>Fungsi:</strong> Menambahkan remote repository GitHub dengan nama <code>origin</code>.<br />
    <strong>Artinya:</strong> Kamu menghubungkan proyek lokalmu ke repository GitHub bernama <code>Belajar-dasar</code> milikmu. Git sekarang tahu ke mana harus mengirim data (push) dan mengambil data (pull).
  </blockquote>

  <pre><code>git remote add origin https://github.com/ariandika79754/Belajar-dasar.git</code></pre>

  <h2>🔹 <code>git push -u origin main</code></h2>
  <blockquote>
    <strong>Fungsi:</strong> Mengupload (<em>push</em>) branch <code>main</code> lokal ke repository GitHub <code>origin</code>.<br />
    <strong>Artinya:</strong>
    <ul>
      <li>Semua commit yang sudah kamu buat di branch <code>main</code> dikirim ke GitHub.</li>
      <li>Opsi <code>-u</code> membuat branch lokal <code>main</code> terkait (tracking) otomatis dengan branch <code>main</code> di remote <code>origin</code>. Jadi ke depannya kamu cukup pakai <code>git push</code> saja tanpa harus menyebut <code>origin main</code>.</li>
    </ul>
  </blockquote>

  <pre><code>git push -u origin main</code></pre>

  <h2>🧠 Kesimpulan</h2>
  <ul>
    <li>✅ Semua file proyek kamu sudah <span class="highlight">terlacak oleh Git</span>.</li>
    <li>✅ Semua perubahan sudah <span class="highlight">tersimpan dalam commit awal</span>.</li>
    <li>✅ Proyek lokal sudah <span class="highlight">terhubung dengan repository GitHub</span>.</li>
    <li>✅ Commit kamu sudah <span class="highlight">di-upload ke GitHub di branch <code>main</code></span>.</li>
  </ul>

  <p>Kalau kamu ingin aku bantu buatkan file <code>.gitignore</code>, panduan deploy ke GitHub Pages, atau membuat file <code>index.html</code> dasar untuk mulai proyekmu, tinggal bilang ya!</p>

</body>
</html>
