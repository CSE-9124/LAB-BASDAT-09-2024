# LAB-BASDAT-09-2024 Repository
Repositori ini adalah tempat pengumpulan tugas praktikum untuk mata kuliah Praktikum Basis Data 2024. Berikut adalah panduan singkat untuk mengumpulkan tugas di repositori ini.

## Tata Cara Pengumpulan (Commit)

Tata cara pengumpulan kode (commit) ke repositori ini mudah dipahami. Berikut langkah-langkahnya:

1. **Fork Repositori Ini**: Di kanan atas halaman repositori, klik tombol "Fork" untuk membuat salinan repositori ini ke akun GitHub pribadimu.

2. **Kloning Repositori**: Setelah kamu memiliki salinan repositori di akunmu, klik tombol "Code" dan pilih metode untuk mengunduh repositori. Salin URL yang diberikan.

3. **Buka Terminal**: Buka terminal atau command prompt di laptopmu.

4. **Kloning Repositori**: Ketik perintah berikut untuk mengkloning repositori ke laptopmu. Ganti `<repository-url>` dengan URL yang telah kamu salin.

```bash
  git clone <url-repositori-hasil-fork>
```

5. **Buat Cabang (Branch) Baru**: Masuk ke direktori repositori yang telah di-kloning. Lalu buat cabang sesuai nim masing-masing.

```bash
cd LAB-BASDAT-09-2024
git checkout -b H071231nn # Sesuaikan dengan NIM masing-masing
```

6. **Masuk ke Folder**: Masuk ke directory/folder sesuai NIM.

```bash
cd H071231nn # Sesuaikan dengan NIM masing-masing
```

7. **Lakukan Perubahan**: Mulai mengedit atau menambahkan berkas (folder maupun file tugas) sesuai dengan instruksi tugas yang diberikan.

8. **Tambahkan File Tugas**: Setelah selesai melakukan perubahan pada kode, tambahkan file tugas tersebut lalu.

```bash
git add .
```

9. **Commit Perubahan**: Setelah semua tugas sudah ditambah, commit dengan pesan yang deskriptif.

```bash
git commit -m "Tugas 1 : Query Dasar"  # Sesuaikan pesan dengan tugas yang kamu kumpulkan
```

Note: Untuk cek status file apakah sudah ditambahkan maupun dikomit, bisa dilakukan dengan `git status`

10. **Push ke GitHub**: Push cabang baru yang telah kamu buat ke repositori GitHub.

```bash
git push -u origin H071231nn # Sesuaikan dengan NIM masing-masing
```

11. **Buka Pull Request**: Di halaman repositori akunmu, akan ada pemberitahuan untuk melakukan `Pull Request`. Klik tautan tersebut lalu lakukan `Pull Request` ke repositori utama ini.

## Tips Tambahan

- Pastikan untuk memberi nama yang deskriptif pada pesan commit tugas.
- Gunakan pesan commit yang jelas agar mudah dimengerti suatu saat nanti.

### -- LAB-BASDAT-09-2024 --

