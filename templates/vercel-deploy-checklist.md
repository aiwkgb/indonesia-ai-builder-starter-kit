# Vercel Deploy Checklist

Checklist ini membantu pemula menyiapkan, deploy, dan mengecek project kecil di Vercel dengan lebih aman dan jelas.

## 1. Before deploy

- [ ] Project sudah bisa berjalan di local
- [ ] README atau catatan project sudah cukup jelas
- [ ] File yang tidak perlu sudah dibersihkan
- [ ] Tidak ada API key, token, password, atau data pribadi di repo
- [ ] Environment variables sudah dicatat dengan aman
- [ ] Build command dan output folder sudah dipahami jika dibutuhkan

## 2. Repository check

- [ ] Repo sudah di-push ke GitHub
- [ ] Branch utama sudah jelas
- [ ] Commit terakhir sudah sesuai task
- [ ] Working tree bersih sebelum deploy
- [ ] Project status ditulis dengan jujur

## 3. Vercel setup

- [ ] Login ke Vercel
- [ ] Import project dari GitHub
- [ ] Pilih repository yang benar
- [ ] Cek framework preset
- [ ] Cek build command
- [ ] Cek output directory jika diperlukan
- [ ] Tambahkan environment variables jika project membutuhkannya

## 4. First deploy

- [ ] Klik deploy
- [ ] Tunggu proses build selesai
- [ ] Baca error message jika build gagal
- [ ] Jangan langsung panik jika deploy pertama gagal
- [ ] Catat error yang muncul untuk diperbaiki satu per satu

## 5. After deploy

- [ ] Buka URL hasil deploy
- [ ] Cek halaman utama
- [ ] Cek tombol/link penting
- [ ] Cek tampilan mobile
- [ ] Cek typo sederhana
- [ ] Pastikan tidak ada data sensitif yang muncul

## 6. Common beginner issues

| Masalah | Kemungkinan penyebab | Langkah cek awal |
| --- | --- | --- |
| Build failed | Build command salah, dependency belum lengkap, atau error kode | Baca log build dan cek error pertama yang muncul |
| Page blank | Routing, build output, atau error JavaScript | Buka browser console dan cek setting output directory |
| Image tidak muncul | Path gambar salah atau file belum ikut masuk repo | Cek nama file, lokasi file, dan huruf besar/kecil |
| Link rusak | URL salah atau halaman tujuan belum dibuat | Klik link satu per satu dan cek path tujuan |
| Environment variable tidak terbaca | Variable belum ditambahkan di Vercel atau namanya berbeda | Cek nama variable di Vercel dan di kode |

## 7. Safety notes

- [ ] Jangan share token atau secret di screenshot
- [ ] Jangan memasukkan file `.env` ke repo public
- [ ] Jangan klaim project production-ready jika masih prototype
- [ ] Jangan menghapus error tanpa memahami penyebabnya
- [ ] Minta review jika project akan dibagikan ke publik

## 8. Simple final review

- [ ] Apakah project bisa dibuka dari URL Vercel?
- [ ] Apakah fitur utama berjalan?
- [ ] Apakah tampilan mobile cukup aman?
- [ ] Apakah README atau catatan deploy sudah membantu?
- [ ] Apakah project siap disebut early version/prototype?

## Short English summary

This checklist helps beginners prepare, deploy, and review small AI-assisted projects on Vercel safely.
