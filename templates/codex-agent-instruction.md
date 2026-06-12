# Codex Agent Instruction Template

Template ini membantu kamu memberi Codex scope task, batasan file, dan ekspektasi review yang jelas sebelum mengerjakan coding atau dokumentasi berbantuan AI.

## 1. Project context

- Nama project:
- Deskripsi singkat:
- Target pengguna:
- Status project saat ini:
- Tujuan task ini:

## 2. Role for Codex

- Codex berperan sebagai:
- Cara Codex harus membantu:
- Hal yang Codex tidak boleh lakukan:

Contoh role:

- focused documentation editor
- code cleanup assistant
- checklist improver
- beginner-friendly reviewer

## 3. Current task

- Issue/task:
- File utama yang dikerjakan:
- Perubahan yang diminta:
- Output yang diharapkan:

## 4. Allowed files

- File yang boleh diedit:
- Folder yang boleh disentuh:
- File/folder yang tidak boleh disentuh:

Jika sebuah file tidak tercantum sebagai file yang boleh diedit, jangan edit file itu tanpa bertanya dulu.

## 5. Working rules

- [ ] Kerjakan satu task kecil dalam satu waktu
- [ ] Jangan membuat file baru tanpa instruksi jelas
- [ ] Jangan mengubah banyak file sekaligus
- [ ] Jangan menghapus konten penting tanpa alasan jelas
- [ ] Jangan mengubah struktur repo besar tanpa izin
- [ ] Jelaskan perubahan dengan bahasa sederhana

## 6. Review checklist before commit

- [ ] Jalankan `git diff` untuk file yang diubah
- [ ] Pastikan hanya file yang diminta yang berubah
- [ ] Cek typo atau bagian yang membingungkan
- [ ] Pastikan tidak ada data pribadi, API key, token, atau password
- [ ] Pastikan klaim tetap realistis
- [ ] Berikan suggested commit message

## 7. Safety and privacy notes

- [ ] Jangan memasukkan secret, credential, atau private key
- [ ] Jangan mengklaim adopsi, user, star, download, atau impact tanpa bukti
- [ ] Jangan menghapus disclaimer penting
- [ ] Tandai asumsi yang belum pasti
- [ ] Minta klarifikasi jika instruksi ambigu

## 8. Expected output from Codex

- [ ] Summary of changes
- [ ] Files changed
- [ ] Notes or risks
- [ ] Suggested commit message
- [ ] Manual review reminder

## 9. Example instruction

```text
Kamu bekerja di repository dokumentasi untuk beginner AI builders di Indonesia.

Task: perbaiki satu file checklist Markdown agar lebih jelas untuk pemula.

File yang boleh diedit:
- checklists/example-checklist.md

File yang tidak boleh disentuh:
- README.md
- docs/
- templates/

Gunakan Bahasa Indonesia yang sederhana. Jangan membuat file baru. Jangan mengubah banyak file. Pastikan checklist tetap ringkas, praktis, dan tidak berisi klaim berlebihan.

Setelah selesai, jalankan git diff untuk file yang diubah, ringkas perubahan, sebutkan file yang berubah, tulis risiko atau hal yang perlu dicek, dan berikan suggested commit message.
```

## Short English summary

This template helps users define Codex's task scope, allowed files, working rules, safety notes, and review expectations before committing changes.
