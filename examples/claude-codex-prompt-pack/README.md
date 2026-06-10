# Claude and Codex Prompt Pack

Contoh ini berisi kumpulan prompt sederhana untuk pemula yang ingin memakai Claude, ChatGPT, dan Codex saat belajar membangun project AI-assisted.

Prompt pack ini dibuat untuk membantu kamu merencanakan project, memperbaiki dokumentasi, meminta review, dan menjaga klaim project tetap jujur. Gunakan contoh ini sebagai bahan belajar, bukan sebagai sistem otomatis yang menggantikan review manusia.

Positioning yang dipakai:

```text
early open-source educational infrastructure for Indonesian beginner AI builders.
```

## English summary

This prompt pack gives beginner-friendly examples for using Claude, ChatGPT, and Codex to plan, edit, review, and improve documentation for an early open-source educational infrastructure project for Indonesian beginner AI builders. Human review is still required before publishing or committing changes.

## When to use this prompt pack

Gunakan prompt pack ini ketika kamu:

- Baru mulai belajar membuat project dengan bantuan AI
- Ingin membuat rencana kerja sebelum coding
- Ingin memperbaiki README atau dokumentasi
- Ingin meminta Codex mengedit file di repository
- Ingin mengecek apakah dokumentasi sudah jelas untuk pemula
- Ingin menghindari klaim yang terlalu promosi atau berlebihan

Jangan langsung menerima hasil AI tanpa membaca ulang. AI bisa salah paham, membuat link keliru, atau menulis klaim yang terlalu besar. Selalu review hasilnya secara manual.

## Claude prompts

Gunakan prompt ini untuk pekerjaan berpikir, merencanakan, menjelaskan, dan mereview tulisan.

### Project planning

```text
Saya sedang membangun project open-source edukasi untuk pemula Indonesia yang belajar AI-assisted building.

Bantu saya membuat rencana project yang sederhana dan realistis.

Konteks project:
- Nama project: [isi nama project]
- Target user: pemula Indonesia yang ingin belajar membuat project dengan bantuan AI
- Tujuan utama: [isi tujuan utama]
- Batasan: jangan membuat klaim berlebihan, jangan membuat project terlihat sudah besar jika belum ada bukti

Tolong buatkan:
1. Ringkasan project
2. Target user
3. Masalah yang dibantu
4. Fitur atau dokumen awal yang perlu dibuat
5. Urutan kerja yang cocok untuk pemula
6. Risiko yang perlu direview manusia
```

### README improvement

```text
Tolong bantu perbaiki README berikut agar lebih jelas untuk pemula.

Aturan:
- Gunakan bahasa Indonesia yang praktis dan mudah dipahami
- Jangan membuat klaim tentang jumlah user, stars, downloads, atau adopsi
- Gunakan positioning: early open-source educational infrastructure for Indonesian beginner AI builders
- Fokus pada edukasi, dokumentasi, dan pembelajaran
- Tambahkan pengingat bahwa hasil AI harus direview manusia

README saat ini:
[tempel isi README di sini]

Tolong berikan versi README yang lebih rapi dan jelaskan perubahan pentingnya.
```

### Documentation review

```text
Tolong review dokumentasi berikut dari sudut pandang pemula.

Cek:
1. Apakah tujuannya jelas?
2. Apakah istilah teknis dijelaskan dengan cukup sederhana?
3. Apakah langkah-langkahnya mudah diikuti?
4. Apakah ada klaim yang terlalu besar?
5. Apakah ada bagian yang perlu direview manusia sebelum dipublish?

Dokumentasi:
[tempel dokumentasi di sini]

Berikan feedback yang praktis dan mudah ditindaklanjuti.
```

### Beginner-friendly explanation

```text
Jelaskan topik berikut untuk pemula Indonesia.

Topik:
[isi topik]

Aturan:
- Gunakan bahasa sederhana
- Beri contoh praktis
- Hindari jargon yang tidak perlu
- Jika harus memakai istilah teknis, jelaskan artinya
- Jangan membuat janji hasil instan
- Ingatkan bahwa output AI tetap perlu dicek manusia

Tolong buat penjelasan yang singkat, jelas, dan ramah untuk pemula.
```

### Claude for Open Source application review

```text
Saya ingin mereview draft aplikasi open-source berikut sebelum dikirim.

Konteks project:
- Project ini adalah early open-source educational infrastructure for Indonesian beginner AI builders
- Fokus project adalah dokumentasi, contoh, template, dan pembelajaran
- Jangan klaim project memiliki banyak user, stars, downloads, atau adopsi jika tidak ada bukti

Draft aplikasi:
[tempel draft di sini]

Tolong cek:
1. Apakah positioning project sudah jelas?
2. Apakah klaimnya jujur dan tidak berlebihan?
3. Apakah manfaat edukasinya mudah dipahami?
4. Apakah ada bagian yang terdengar terlalu promosi?
5. Apa revisi yang paling penting sebelum dikirim?
```

## Codex prompts

Gunakan prompt ini ketika kamu ingin Codex membantu mengedit file di repository. Beri instruksi yang spesifik dan minta Codex tidak mengedit file yang tidak terkait.

### Create a new markdown file

```text
Create a new markdown file at:
[path file]

Requirements:
- Write in beginner-friendly Indonesian
- Include a short English summary near the top
- Keep the tone practical and clear
- Do not claim many users, stars, downloads, or adoption
- Use the positioning: early open-source educational infrastructure for Indonesian beginner AI builders
- Add a reminder that AI output should be reviewed by a human
- Do not edit unrelated files

After creating the file, show:
1. Changed file path
2. Short summary of what was added
3. Suggested commit message
```

### Update documentation links

```text
Please update the documentation links related to:
[isi topik atau file]

Rules:
- Only edit files directly related to this documentation update
- Keep link text clear for beginners
- Do not add promotional claims
- Do not edit unrelated files
- After editing, show the changed files and summarize the changes

Before editing, inspect the existing docs structure and follow the current style.
```

### Check broken links

```text
Please check the markdown documentation for broken or suspicious links.

Scope:
[isi folder atau file, contoh: docs/ dan examples/]

Rules:
- Report broken links clearly
- Fix only obvious internal link issues if safe
- Do not rewrite unrelated content
- Do not add new claims about adoption, users, stars, or downloads
- Show which files were checked and which files were changed

If a link cannot be verified locally, mark it as "needs human review".
```

### Improve folder structure

```text
Please review the folder structure for this beginner-friendly open-source education project.

Goal:
Make the structure easier for Indonesian beginner AI builders to understand.

Rules:
- Prefer small, clear changes
- Do not move files unless there is a strong reason
- Do not edit unrelated files
- Explain any proposed folder changes before making them
- Keep the focus on documentation and learning, not automation hype

After changes, summarize:
1. What changed
2. Why it helps beginners
3. What still needs human review
```

### Review changed files before commit

```text
Please review the changed files before I commit.

Check:
1. Are the changes limited to the requested task?
2. Is the Indonesian clear and beginner-friendly?
3. Are there broken links or missing references?
4. Are there overclaims about users, stars, downloads, adoption, revenue, or guaranteed results?
5. Is there anything a human should manually review?

Do not edit files unless you find a small, obvious fix. If you edit anything, explain exactly what changed.
```

## Review prompts

Gunakan prompt ini untuk mengecek hasil sebelum commit, publish, atau share ke orang lain.

### Check clarity

```text
Tolong cek apakah tulisan berikut sudah jelas untuk pemula.

Fokus review:
- Apakah tujuan dokumen mudah dipahami?
- Apakah urutannya masuk akal?
- Apakah ada kalimat yang terlalu panjang?
- Apakah ada istilah yang perlu dijelaskan?
- Apakah ada bagian yang perlu dicek manusia?

Tulisan:
[tempel tulisan di sini]

Berikan saran perbaikan yang praktis.
```

### Check broken links

```text
Tolong cek daftar link atau referensi berikut.

Daftar link:
[tempel daftar link atau isi markdown]

Tandai:
1. Link yang terlihat benar
2. Link yang kemungkinan rusak
3. Link yang perlu dicek manual oleh manusia
4. Teks link yang perlu dibuat lebih jelas
```

### Check consistency

```text
Tolong cek konsistensi dokumentasi berikut.

Cek:
- Apakah istilah yang dipakai konsisten?
- Apakah nama file dan folder ditulis sama?
- Apakah tone tulisannya seragam?
- Apakah ada bagian yang bertentangan?
- Apakah positioning project tetap konsisten sebagai early open-source educational infrastructure for Indonesian beginner AI builders?

Dokumentasi:
[tempel dokumentasi di sini]
```

### Check beginner-friendliness

```text
Tolong review apakah dokumentasi ini ramah untuk pemula.

Target pembaca:
Pemula Indonesia yang baru belajar memakai AI untuk membuat project.

Cek:
1. Apakah pembaca tahu harus mulai dari mana?
2. Apakah instruksi terlalu teknis?
3. Apakah ada contoh yang bisa langsung dicoba?
4. Apakah ada asumsi pengetahuan yang terlalu tinggi?
5. Apakah ada bagian yang perlu diperingatkan untuk direview manusia?

Dokumentasi:
[tempel dokumentasi di sini]
```

## Safety and positioning prompts

Gunakan prompt ini untuk menjaga dokumentasi tetap jujur, realistis, dan berguna untuk belajar.

### Avoid overclaiming

```text
Tolong cek apakah tulisan berikut memiliki klaim berlebihan.

Aturan:
- Jangan klaim banyak user, stars, downloads, atau adopsi jika tidak ada bukti
- Jangan klaim hasil pasti, instan, atau dijamin
- Jangan membuat project terlihat lebih matang dari kondisi sebenarnya
- Gunakan positioning: early open-source educational infrastructure for Indonesian beginner AI builders

Tulisan:
[tempel tulisan di sini]

Tolong tandai kalimat bermasalah dan berikan versi yang lebih jujur.
```

### Check if wording is too promotional

```text
Tolong cek apakah wording berikut terlalu promosi.

Target tone:
- Praktis
- Jelas
- Edukatif
- Beginner-friendly
- Tidak hype

Tulisan:
[tempel tulisan di sini]

Tolong ubah bagian yang terlalu promosi menjadi lebih tenang, jujur, dan berbasis pembelajaran.
```

### Keep project claims honest

```text
Tolong bantu menjaga klaim project ini tetap jujur.

Konteks:
Project ini adalah early open-source educational infrastructure for Indonesian beginner AI builders.

Cek tulisan berikut:
[tempel tulisan di sini]

Tolong pastikan:
1. Tidak ada klaim adopsi tanpa bukti
2. Tidak ada klaim hasil instan
3. Tidak ada klaim "terbaik", "terbesar", atau "paling lengkap" tanpa dasar
4. Manfaat project dijelaskan secara realistis
5. Ada pengingat bahwa output AI harus direview manusia
```

### Make sure documentation is useful for beginners

```text
Tolong cek apakah dokumentasi ini benar-benar berguna untuk pemula.

Pertanyaan review:
- Apakah ada contoh yang bisa langsung dipakai?
- Apakah langkah berikutnya jelas?
- Apakah bahasa terlalu abstrak?
- Apakah dokumen membantu belajar, bukan hanya terlihat canggih?
- Apakah ada bagian yang perlu disederhanakan?

Dokumentasi:
[tempel dokumentasi di sini]

Berikan rekomendasi perbaikan yang paling penting.
```

## Recommended workflow

Gunakan alur sederhana ini saat mengerjakan issue atau dokumentasi:

1. Ask Claude or ChatGPT to plan

   Minta Claude atau ChatGPT membantu memahami issue, membuat outline, dan mengusulkan struktur. Jangan langsung anggap rencana AI benar. Baca ulang dan sesuaikan dengan kebutuhan project.

2. Use Codex for repo edits

   Beri Codex task yang spesifik, misalnya membuat file markdown baru, memperbaiki link, atau mereview diff. Minta Codex tidak mengedit file yang tidak terkait.

3. Review diff manually

   Baca perubahan file satu per satu. Cek apakah ada link rusak, klaim berlebihan, typo, atau bagian yang membingungkan untuk pemula.

4. Commit with clear message

   Gunakan commit message yang menjelaskan perubahan dengan singkat.

   Contoh:

   ```text
   docs: add Claude and Codex prompt pack example
   ```

5. Close issue when done

   Setelah file sudah dibuat, direview, dan commit siap, tutup issue dengan ringkasan singkat. Jika ada bagian yang masih perlu dicek manusia, tulis dengan jelas.

## Human review reminder

AI bisa membantu mempercepat drafting, review, dan editing, tetapi keputusan akhir tetap perlu dibuat oleh manusia.

Sebelum publish atau commit, cek lagi:

- Apakah isi dokumen benar?
- Apakah bahasanya jelas untuk pemula?
- Apakah link bisa dibuka?
- Apakah klaimnya jujur?
- Apakah ada bagian yang terlalu promosi?
- Apakah perubahan hanya menyentuh file yang relevan?
