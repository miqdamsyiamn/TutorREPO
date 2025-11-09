# 🚀 Pengaturan Cepat Repositori

Dokumen ini berisi langkah-langkah dasar untuk menghubungkan dan mengirim kode ke repositori GitHub ini dari baris perintah (command line).

---

### 1. 📦 Membuat Repositori Baru dari Command Line

Gunakan langkah-langkah ini jika Anda memulai proyek baru di komputer Anda.

```bash
# Membuat file README.md sederhana
echo "# SSH-Key" >> README.md

# Memulai repositori Git lokal
git init

# Menambahkan file README.md untuk di-commit
git add README.md

# Menyimpan perubahan secara lokal
git commit -m "first commit"

# Mengubah nama branch utama menjadi "main"
git branch -M main

# Menghubungkan repositori lokal Anda ke remote GitHub
git remote add origin git@github.com:Creacipe/SSH-Key.git

# Mengirim (push) commit Anda ke GitHub
git push -u origin main
```

### 2. ⬆️ Mendorong (Push) Repositori yang Sudah Ada
```bash
# Menghubungkan repositori lokal Anda ke remote GitHub
git remote add origin git@github.com:Creacipe/SSH-Key.git

# Mengubah nama branch utama menjadi "main" (jika perlu)
git branch -M main

# Mengirim (push) branch "main" Anda ke GitHub
git push -u origin main

```

## 🧠 Penjelasan Kode

* Saya telah mengubah judul seperti `...or create a new repository...` menjadi judul Markdown yang rapi menggunakan `###`.
* Semua perintah `git` dari gambar Anda telah ditempatkan di dalam blok kode ` ```bash ... ``` `.
* Saya juga menambahkan **komentar** (baris yang dimulai dengan `#`) di dalam blok kode untuk menjelaskan fungsi setiap perintah, sehingga README Anda juga berfungsi sebagai dokumentasi yang baik.

Apakah ini sudah sesuai dengan yang Anda inginkan?
