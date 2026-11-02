# Pengingat Waktu TKA — SMAN 1 Katapang

Dashboard waktu ujian yang berjalan di browser, menyimpan pengaturan di perangkat, dan dapat digunakan offline setelah pertama kali dibuka.

## Publikasikan dengan GitHub Pages

1. Buat repositori GitHub baru, misalnya `pengingat-waktu-tka`.
2. Unggah semua file dan folder proyek ini ke repositori. Pastikan `index.html` berada di akar repositori.
3. Pilih branch `main` sebagai branch utama.
4. Buka **Settings → Pages** di repositori. Pada **Build and deployment**, pilih **GitHub Actions**.
5. Dorong perubahan ke branch `main`, atau jalankan workflow **Deploy site to GitHub Pages** dari tab **Actions**.

### Alamat situs

Untuk repositori bernama `pengingat-waktu-tka`, alamatnya biasanya:

`https://NAMA-AKUN.github.io/pengingat-waktu-tka/`

Situs akun dengan nama repositori `NAMA-AKUN.github.io` akan tersedia di `https://NAMA-AKUN.github.io/`.

Workflow di `.github/workflows/pages.yml` menerbitkan isi repositori saat ada push ke `main`. Aplikasi tidak memerlukan server atau database; jadwal ujian disimpan di penyimpanan browser masing-masing perangkat.
