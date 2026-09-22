<img width="1366" height="1068" alt="image" src="https://github.com/user-attachments/assets/056e8606-05e9-46ac-9d1e-fe6dae08b86f" />

# AcakAlamat

Aplikasi web statis untuk mengacak susunan komponen alamat langsung di browser. Tidak ada data yang dikirim ke server.

## Fitur

- Mengacak input yang dipisahkan koma, titik koma, atau baris baru
- Menghasilkan 1–10 variasi unik
- Pilihan format pemisah hasil
- Menghapus komponen duplikat secara opsional
- Salin satu hasil atau semua hasil
- Unduh hasil sebagai `.txt`
- Responsif, aksesibel, mode gelap otomatis
- Randomisasi menggunakan Web Crypto API jika tersedia
- Siap deploy ke Vercel tanpa build step

## Jalankan lokal

```bash
python3 -m http.server 3000
```

Lalu buka `http://localhost:3000`.

## Deploy ke Vercel

1. Import repository ini di Vercel.
2. Pilih preset **Other**.
3. Biarkan Build Command kosong.
4. Klik **Deploy**.

Konfigurasi redirect dan security headers tersedia di `vercel.json`.
