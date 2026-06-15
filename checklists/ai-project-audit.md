# AI Project Audit Checklist

Checklist ini membantu pemula mengecek apakah project AI-assisted mereka sudah cukup rapi, jelas, dan siap dibagikan di GitHub.

Gunakan checklist ini sebelum:

* Membagikan repo ke publik
* Membuat release pertama
* Mengirim project untuk review
* Menggunakan repo sebagai portofolio
* Mengajak contributor lain membantu project

## English summary

This checklist helps beginner AI builders review whether their AI-assisted project is clear, organized, beginner-friendly, and ready to share publicly.

## Cara menggunakan checklist ini

Baca setiap bagian, lalu centang item yang sudah selesai.

Tidak semua project harus sempurna dari awal. Checklist ini dipakai untuk membantu kamu melihat bagian mana yang sudah rapi dan bagian mana yang perlu diperbaiki.

Kalau checklist ini terasa terlalu panjang, mulai dari checklist yang lebih kecil:

* [`ai-workflow.md`](ai-workflow.md) untuk proses memakai AI dengan aman
* [`project-review.md`](project-review.md) untuk review project sebelum dibagikan
* [`github-setup.md`](github-setup.md) untuk kesiapan repository GitHub

---

## 1. Project clarity

Mulai dari kejelasan tujuan. Bagian ini membantu memastikan project bisa dijelaskan dengan sederhana.

* [ ] Nama project jelas
* [ ] Tujuan project dijelaskan dengan sederhana
* [ ] Target user atau target pembaca disebutkan
* [ ] Masalah yang ingin dibantu project ini jelas
* [ ] Project tidak memakai klaim yang berlebihan
* [ ] Project bisa dijelaskan dalam 1-2 kalimat

Pertanyaan bantu:

* Project ini dibuat untuk siapa?
* Project ini membantu menyelesaikan masalah apa?
* Apa hasil realistis yang bisa didapat user?

---

## 2. README

README adalah pintu masuk utama untuk orang yang baru melihat repo.

* [ ] README tersedia di root repo
* [ ] README memiliki ringkasan project
* [ ] README punya bagian "Start here" atau panduan awal
* [ ] README berisi link ke docs penting
* [ ] README berisi link ke templates, checklists, atau examples jika tersedia
* [ ] Link di README tidak broken
* [ ] Bahasa README mudah dipahami pemula
* [ ] README tidak terlalu panjang tanpa struktur

README yang baik sebaiknya menjawab:

* Ini project apa?
* Untuk siapa?
* Cara mulai dari mana?
* File penting ada di mana?
* Bagaimana cara berkontribusi?

---

## 3. Repository structure

Struktur folder yang rapi membantu pemula menemukan file penting.

* [ ] Struktur folder mudah dipahami
* [ ] Folder `docs/` digunakan untuk dokumentasi
* [ ] Folder `templates/` digunakan untuk template
* [ ] Folder `checklists/` digunakan untuk checklist
* [ ] Folder `examples/` digunakan untuk contoh project
* [ ] Tidak ada file acak yang membingungkan di root repo
* [ ] Nama file memakai format yang konsisten
* [ ] File dan folder memakai nama yang deskriptif

Contoh struktur sederhana:

* `docs/`
* `templates/`
* `checklists/`
* `examples/`
* `.github/ISSUE_TEMPLATE/`

---

## 4. Documentation quality

Dokumentasi tidak harus panjang. Yang penting pembaca tahu harus mulai dari mana.

* [ ] Ada dokumentasi getting started
* [ ] Ada dokumentasi workflow
* [ ] Ada roadmap
* [ ] Ada glossary jika project memakai banyak istilah teknis
* [ ] Dokumentasi ditulis dengan bahasa sederhana
* [ ] Dokumentasi punya heading yang jelas
* [ ] Dokumentasi tidak terlalu teknis untuk pemula
* [ ] Dokumentasi menjelaskan langkah demi langkah

Untuk project pemula, dokumentasi tidak harus sempurna. Yang penting pembaca tidak merasa tersesat.

---

## 5. Templates and prompts

Template dan prompt sebaiknya langsung bisa dipakai atau diisi oleh pemula.

* [ ] Template punya judul yang jelas
* [ ] Template menjelaskan kapan harus digunakan
* [ ] Template memakai placeholder yang mudah diganti
* [ ] Template tidak terlalu panjang tanpa arahan
* [ ] Prompt untuk AI jelas dan spesifik
* [ ] Instruksi untuk Claude/Codex/Gemini dipisahkan jika perlu
* [ ] Template tidak menjanjikan hasil instan
* [ ] Template bisa digunakan oleh pemula tanpa banyak istilah teknis

Pertanyaan bantu:

* Apakah template ini bisa langsung dipakai?
* Apakah pemula tahu bagian mana yang harus diisi?
* Apakah instruksinya terlalu abstrak?

---

## 6. AI workflow readiness

Gunakan bagian ini untuk mengecek apakah peran AI dan manusia sudah jelas.

* [ ] Project menjelaskan bagaimana AI digunakan
* [ ] Ada pembagian peran antara manusia dan AI
* [ ] Ada instruksi untuk review hasil AI
* [ ] Ada peringatan agar output AI tidak diterima mentah-mentah
* [ ] Ada workflow untuk membuat issue, mengubah file, dan review
* [ ] Ada panduan kapan memakai ChatGPT, Claude, Codex, atau tool lain
* [ ] Tidak ada instruksi yang mendorong overclaim atau manipulasi

AI sebaiknya diposisikan sebagai partner kerja, bukan pengganti seluruh proses berpikir manusia.

---

## 7. GitHub readiness

Bagian ini membantu mengecek apakah repo siap dibaca, direview, atau dikembangkan bertahap.

* [ ] Repo public jika memang ingin open-source
* [ ] Ada `LICENSE`
* [ ] Ada `CONTRIBUTING.md`
* [ ] Ada `CODE_OF_CONDUCT.md`
* [ ] Ada `CHANGELOG.md`
* [ ] Ada issue template
* [ ] Issue roadmap dibuat dengan scope kecil
* [ ] Issue yang selesai ditutup dengan alasan completed
* [ ] Release dibuat jika milestone sudah cukup jelas

Untuk project open-source awal, riwayat issue dan release membantu menunjukkan bahwa project aktif dirawat.

---

## 8. Beginner-friendliness

Review bagian ini dari sudut pandang orang yang baru belajar.

* [ ] Bahasa utama mudah dipahami
* [ ] Istilah teknis dijelaskan
* [ ] Contoh diberikan secara praktis
* [ ] Tidak mengasumsikan pembaca sudah jago coding
* [ ] Ada urutan belajar atau urutan penggunaan
* [ ] Ada checklist untuk membantu eksekusi
* [ ] Ada contoh project sederhana
* [ ] Dokumentasi tidak membuat pemula merasa tertinggal

Pertanyaan bantu:

* Apakah anak SMA atau mahasiswa non-coding bisa memahami arahnya?
* Apakah solo founder pemula bisa mulai dari README?
* Apakah creator non-teknis bisa memakai template?

---

## 9. Claims and positioning

Gunakan bagian ini untuk menjaga dokumentasi tetap jujur dan tidak berlebihan.

* [ ] Tidak mengklaim punya banyak user jika belum ada bukti
* [ ] Tidak mengklaim banyak stars jika belum benar
* [ ] Tidak mengklaim project sudah widely adopted jika belum ada bukti
* [ ] Tidak menjanjikan hasil finansial instan
* [ ] Positioning project jujur dan realistis
* [ ] Dampak project dijelaskan sebagai potensi atau tujuan, bukan klaim berlebihan
* [ ] Roadmap ditulis terbuka dan transparan

Untuk project baru, lebih aman memakai positioning seperti:

Early open-source educational infrastructure for Indonesian beginner AI builders.

---

## 10. Release readiness

Release sebaiknya dibuat saat milestone sudah jelas dan file penting sudah dicek.

* [ ] Changelog sudah diperbarui
* [ ] README sudah sinkron dengan isi repo
* [ ] File penting tidak broken
* [ ] Link penting sudah dicek
* [ ] Issue yang selesai sudah ditutup
* [ ] Release notes sudah disiapkan
* [ ] Tag release sesuai format, misalnya `v0.1.0`
* [ ] Release menjelaskan apa yang sudah ada dan apa yang belum ada

Release pertama tidak harus besar. Yang penting jelas, jujur, dan bisa dipakai sebagai milestone.

---

## 11. Contributor readiness

Kontribusi pertama sebaiknya mudah dipahami, kecil, dan bisa direview.

* [ ] Contributor tahu cara mulai membantu
* [ ] Ada issue dengan scope kecil
* [ ] Ada label seperti `good first issue` jika tersedia
* [ ] Ada kontribusi yang cocok untuk non-coder
* [ ] Panduan kontribusi tidak terlalu rumit
* [ ] Maintainer menjelaskan ekspektasi dengan ramah
* [ ] Project terbuka untuk perbaikan dokumentasi

Open-source bukan hanya soal code. Dokumentasi, contoh, checklist, dan template juga bisa menjadi kontribusi penting.

---

## 12. Final audit score

Gunakan skor sederhana ini:

* 0-5 item selesai: project masih sangat awal
* 6-15 item selesai: project sudah mulai terbentuk
* 16-30 item selesai: project cukup rapi untuk dibagikan
* 31-50 item selesai: project sudah kuat sebagai starter kit awal
* 50+ item selesai: project siap dikembangkan lebih serius

Catatan:

Skor ini bukan penilaian resmi. Gunakan hanya sebagai alat bantu review internal.

---

## Recommended next steps

Setelah audit selesai:

1. Catat bagian yang belum rapi
2. Buat issue kecil untuk setiap perbaikan
3. Prioritaskan README, docs, dan broken links
4. Hindari mengubah terlalu banyak file sekaligus
5. Review ulang setelah perubahan dilakukan
6. Buat release jika milestone sudah cukup jelas

## Prinsip utama

Project AI-assisted yang baik bukan project yang langsung sempurna.

Project yang baik adalah project yang:

* Jelas tujuannya
* Rapi strukturnya
* Mudah dipahami pemula
* Jujur positioning-nya
* Bisa diperbaiki bertahap
* Punya dokumentasi yang membantu orang lain mulai
