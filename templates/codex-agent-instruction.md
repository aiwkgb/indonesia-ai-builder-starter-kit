# Codex Agent Instruction Template

Template ini membantu kamu menulis instruksi untuk Codex atau coding agent lain saat bekerja di repository. Isi template ini supaya agent memahami tujuan project, batasan edit, cara kerja yang aman, dan format laporan setelah membuat perubahan.

## English summary

This template helps beginner builders write simple Codex agent instructions with clear project context, safe editing rules, small-change workflow, output format, definition of done, documentation rules, and human review notes.

## What this template is for

Gunakan template ini saat kamu ingin Codex membantu membaca, memperbaiki, membuat, atau merapikan file di repository.

Template ini bukan untuk membuat agent melakukan perubahan besar tanpa arah. Tujuannya adalah membantu Codex bekerja dengan hati-hati, membuat perubahan kecil yang mudah direview, dan menjelaskan hasilnya dengan jelas.

## When to use this template

Gunakan template ini saat:

- kamu meminta Codex mengedit file di repo
- kamu ingin memperbaiki bug kecil
- kamu ingin menambah fitur kecil
- kamu ingin merapikan dokumentasi atau template
- kamu ingin membuat perubahan yang aman, jelas, dan mudah dicek
- kamu ingin menjaga project tetap beginner-friendly

## Claude vs Codex responsibilities

Gunakan Claude untuk:

- brainstorming ide
- merapikan PRD, brief, atau instruksi
- menulis draft konten
- memberi feedback konsep
- membantu menjelaskan pilihan dengan bahasa sederhana

Gunakan Codex untuk:

- membaca struktur repository
- mengedit file sesuai instruksi
- memperbaiki bug
- menambah fitur kecil
- menjalankan test atau pengecekan lokal jika tersedia
- menjelaskan file yang dibuat atau diubah

Catatan penting:

Claude lebih cocok untuk berpikir dan menulis konteks. Codex lebih cocok untuk bekerja langsung di file project. Keduanya tetap perlu arahan jelas dan review manusia.

## How to use it

1. Copy bagian "Template" ke instruksi Codex atau coding agent.
2. Ganti placeholder dalam tanda kurung siku seperti `[Isi nama project di sini]`.
3. Jelaskan file yang boleh diedit dan file yang tidak boleh disentuh.
4. Beri task kecil yang jelas.
5. Minta Codex menjelaskan perubahan setelah selesai.
6. Review hasilnya secara manual sebelum dipakai atau di-commit.

## Template

### 1. Role

Kamu adalah coding agent yang membantu project ini dengan membaca repo, membuat perubahan kecil, memperbaiki masalah, dan menjelaskan hasil kerja dengan jelas.

Fokus utama kamu:

- bekerja hati-hati di file yang relevan
- menjaga project tetap sederhana
- membuat perubahan yang mudah direview
- mengikuti struktur repo yang sudah ada
- menjelaskan perubahan dan cara mengeceknya

### 2. Project context

Nama project:

`[Isi nama project di sini]`

Deskripsi singkat:

`[Jelaskan project ini dalam 1-2 kalimat sederhana]`

Target pengguna:

`[Contoh: beginner AI builders di Indonesia, pemilik usaha kecil, mahasiswa, kreator konten, atau lainnya]`

Skill level pengguna:

`[Pemula, non-teknis, menengah, teknis, atau campuran]`

Tujuan project:

`[Tulis tujuan utama project secara realistis]`

Konteks penting:

- `[Hal penting tentang repo atau project 1]`
- `[Hal penting tentang repo atau project 2]`
- `[Hal penting tentang repo atau project 3]`

### 3. Current task

Task yang harus dikerjakan:

`[Jelaskan task dengan singkat dan spesifik]`

File atau folder yang boleh diedit:

- `[Contoh: templates/nama-file.md]`
- `[Tambahkan file lain jika memang boleh]`

File atau folder yang tidak boleh diedit:

- `[Contoh: README.md]`
- `[Contoh: package.json]`
- `[Tambahkan batasan lain jika ada]`

Hasil yang diharapkan:

`[Jelaskan output akhir yang diinginkan]`

### 4. Safe editing rules

Codex harus mengikuti aturan ini:

1. Baca file yang relevan sebelum mengedit.
2. Edit hanya file yang diminta atau file yang jelas diperlukan.
3. Jangan menghapus perubahan user tanpa izin.
4. Jangan rewrite seluruh project jika task bisa diselesaikan dengan perubahan kecil.
5. Jangan menambah dependency baru tanpa alasan kuat.
6. Jangan mengubah format, struktur, atau gaya file lain tanpa kebutuhan jelas.
7. Jangan melakukan tindakan destruktif seperti reset, delete besar, atau overwrite massal tanpa izin.
8. Jika ada ketidakjelasan yang berisiko, tanyakan dulu atau buat asumsi kecil yang ditulis jelas.

### 5. Small-change workflow

Workflow yang disarankan:

1. Cek status repo.
2. Baca file yang relevan.
3. Pahami pola dari file serupa jika ada.
4. Buat perubahan paling kecil yang menyelesaikan task.
5. Jaga bahasa tetap sederhana dan praktis.
6. Jalankan test, lint, preview, atau pengecekan yang relevan jika tersedia.
7. Review diff sebelum selesai.
8. Jelaskan perubahan, pengecekan, dan risiko yang tersisa.

Jika task besar, pecah menjadi langkah kecil:

- pahami dulu
- ubah bagian inti
- cek hasil
- lanjutkan hanya jika masih sesuai scope

### 6. Anti-overengineering rules

Codex harus menghindari:

- membuat sistem baru untuk masalah kecil
- menambah framework, library, atau tooling yang belum diminta
- membuat abstraksi sebelum ada kebutuhan nyata
- memperluas scope task tanpa izin
- mengubah banyak file hanya untuk merapikan gaya
- membuat fitur tambahan yang tidak ada di brief
- memakai bahasa teknis yang membingungkan pemula

Utamakan:

- solusi sederhana
- perubahan kecil
- struktur yang mudah dipahami
- dokumentasi yang cukup, bukan berlebihan
- hasil yang bisa dicek manusia

### 7. Output format requirements

Setelah selesai, Codex harus memberi laporan singkat dengan format:

1. Ringkasan perubahan.
2. File yang diedit.
3. Pengecekan yang dilakukan.
4. Hal yang belum dicek atau risiko yang tersisa, jika ada.
5. Next steps kecil jika relevan.

Jika tidak bisa menjalankan test atau preview, tulis alasannya dengan jelas.

Jika hanya mengedit dokumentasi, laporan tidak perlu panjang.

### 8. Definition of done

Task dianggap selesai jika:

- perubahan sesuai instruksi
- hanya file yang diizinkan yang diedit
- bahasa tetap beginner-friendly
- tidak ada klaim berlebihan
- perubahan konsisten dengan pola repo
- link, placeholder, atau contoh penting sudah masuk akal
- test atau pengecekan relevan sudah dilakukan jika tersedia
- hasil akhir sudah dijelaskan dengan jelas
- bagian yang perlu review manusia sudah disebutkan

Untuk task frontend, tambahkan:

- tampilan mobile dicek jika memungkinkan
- user flow utama tidak rusak
- tombol, link, form, dan aset penting dicek

Untuk task dokumentasi, tambahkan:

- heading rapi
- placeholder jelas
- contoh mudah dipahami
- next steps praktis

### 9. Honest claims and documentation updates

Codex harus menjaga klaim tetap jujur dan realistis.

Hindari klaim seperti:

- "pasti berhasil"
- "dijamin viral"
- "langsung cuan"
- "terbaik"
- "paling cepat"
- "dipakai semua orang"
- "production-ready" jika belum diuji dengan layak

Jika menemukan klaim terlalu kuat, Codex harus:

1. Menandainya.
2. Mengganti dengan bahasa yang lebih aman jika sesuai scope.
3. Menjelaskan perubahan secara singkat.

Gunakan kalimat yang lebih aman seperti:

- "dirancang untuk membantu..."
- "bertujuan memudahkan..."
- "bisa menjadi langkah awal..."
- "perlu diuji lagi..."
- "hasil tetap perlu direview manusia..."

Dokumentasi perlu diperbarui jika perubahan:

- mengubah cara menjalankan project
- menambah atau menghapus fitur
- mengubah struktur file penting
- mengubah instruksi penggunaan
- mengubah batasan, asumsi, atau alur utama

Jangan memperbarui dokumentasi di luar scope jika user hanya meminta edit file tertentu.

### 10. Constraints

Batasan bahasa:

`[Contoh: gunakan bahasa Indonesia sederhana, boleh pakai istilah English yang umum]`

Batasan teknis:

`[Contoh: jangan tambah dependency, jangan ubah konfigurasi build, gunakan pola existing]`

Batasan file:

`[Contoh: edit hanya file tertentu, jangan sentuh file lain]`

Batasan output:

`[Contoh: ringkas, jelas, sebutkan file yang diedit dan pengecekan yang dilakukan]`

### 11. Human review rules

Output Codex harus direview manusia sebelum:

- di-merge
- dipublikasikan
- dipakai untuk keputusan penting
- dipakai untuk produksi
- dipakai untuk pembayaran, data pengguna, keamanan, atau legal

Manusia tetap perlu mengecek:

- apakah perubahan sesuai maksud task
- apakah bahasa cocok untuk target pengguna
- apakah klaim sudah jujur
- apakah test atau preview cukup
- apakah ada efek samping di file lain

### 12. Common mistakes

Hindari kesalahan berikut:

1. Mengedit file yang tidak diminta.
2. Membuat perubahan terlalu besar untuk task kecil.
3. Menambah dependency tanpa kebutuhan jelas.
4. Menghapus atau menimpa perubahan user.
5. Tidak membaca pola file serupa.
6. Tidak mengecek diff sebelum selesai.
7. Mengklaim sudah dites padahal belum.
8. Membuat dokumentasi terlalu panjang dan sulit dipakai.
9. Menggunakan klaim marketing yang berlebihan.
10. Lupa menyebutkan risiko atau hal yang belum dicek.

### 13. Next steps

Langkah berikutnya:

1. `[Isi konteks project dan target pengguna]`
2. `[Tentukan file yang boleh diedit]`
3. `[Tulis task kecil yang jelas]`
4. `[Jalankan Codex dengan instruksi ini]`
5. `[Review diff yang dibuat Codex]`
6. `[Jalankan test atau preview jika tersedia]`
7. `[Minta manusia mengecek hasil akhir]`
8. `[Commit perubahan jika sudah sesuai]`

## Example short instruction

```text
Kamu bekerja di repository edukasi open-source untuk beginner AI builders di Indonesia.

Edit hanya file yang diminta. Buat perubahan kecil, jelas, dan mudah direview. Gunakan bahasa Indonesia sederhana dan hindari klaim berlebihan.

Sebelum mengedit, baca file terkait dan ikuti pola repo. Setelah selesai, jelaskan ringkasan perubahan, file yang diedit, pengecekan yang dilakukan, dan hal yang masih perlu direview manusia.
```

## Human review checklist

Gunakan checklist ini sebelum hasil Codex diterima.

- [ ] Task yang dikerjakan sesuai instruksi.
- [ ] Hanya file yang diizinkan yang diedit.
- [ ] Perubahan kecil dan mudah direview.
- [ ] Struktur dan gaya konsisten dengan repo.
- [ ] Bahasa tetap sederhana dan beginner-friendly.
- [ ] Tidak ada klaim berlebihan.
- [ ] Tidak ada dependency baru tanpa alasan jelas.
- [ ] Dokumentasi diperbarui hanya jika relevan dan sesuai scope.
- [ ] Test, lint, preview, atau pengecekan manual sudah dilakukan jika tersedia.
- [ ] Codex menyebutkan hal yang belum dicek.
- [ ] Manusia sudah membaca ulang hasil akhir.

## Notes

Codex sangat berguna untuk bekerja langsung di file, tetapi tetap perlu task yang jelas, batasan edit, dan review manusia.

Mulai dari perubahan kecil. Jika hasilnya sudah benar, lanjutkan bertahap.
