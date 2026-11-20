# Portfolio Bianca

Portofolio satu halaman berbasis HTML, CSS, dan JavaScript murni. Tidak membutuhkan framework, npm, atau proses build.

## Isi paket

- `index.html` — seluruh tampilan dan interaksi portofolio.
- `vercel.json` — clean URL dan header keamanan dasar.
- `README.md` — panduan pengeditan dan publikasi.

## Sebelum dipublikasikan

Buka `index.html`, lalu cari komentar `EDIT`. Ganti data contoh dengan data asli:
- Tahun masuk sekolah.
- Email.
- Username dan tautan GitHub.
- Detail proyek, pengalaman, pendidikan, dan sertifikasi.

Pastikan semua informasi benar dan dapat dibuktikan. Jangan menampilkan alamat rumah, nomor telepon pribadi, kata sandi, atau data sensitif. Hapus bagian yang belum relevan.

## Menjalankan di komputer

1. Ekstrak ZIP.
2. Buka folder `portfolio-bian`.
3. Klik dua kali `index.html`.
4. Uji navigasi, tombol tema, accordion pengalaman, filter proyek, dan tampilan di ukuran layar berbeda.

## Upload ke GitHub lewat browser

1. Masuk ke https://github.com dan buat repository baru bernama `portfolio`.
2. Pilih Public atau Private sesuai kebutuhan.
3. Upload **isi folder ini** (`index.html`, `vercel.json`, dan `README.md`) ke root repository, bukan folder induknya.
4. Klik **Commit changes**.
5. Pastikan `index.html` terlihat langsung di halaman utama repository.

## Deploy ke Vercel

1. Masuk ke https://vercel.com menggunakan akun GitHub.
2. Pilih **Add New → Project**.
3. Import repository `portfolio`.
4. Pada konfigurasi proyek, pilih **Framework Preset: Other**.
5. Biarkan Root Directory `./`; kosongkan Build Command, Output Directory, dan Install Command.
6. Klik **Deploy**.
7. Setelah selesai, buka alamat `.vercel.app` dan periksa seluruh halaman.

Setiap perubahan yang di-commit ke GitHub akan memicu deployment baru di Vercel.

## Domain sendiri (opsional)

Tambahkan domain melalui **Project → Settings → Domains** di Vercel. Ikuti record DNS yang ditampilkan Vercel dan masukkan record tersebut di panel DNS penyedia domain. Gunakan nilai persis yang diberikan Vercel; jangan menghapus record MX jika domain juga digunakan untuk email. DNS dapat memerlukan waktu untuk menyebar.

## Memperbarui

Edit `index.html`, simpan, lalu commit perubahan ke GitHub. Vercel akan menerbitkan versi terbaru secara otomatis.
