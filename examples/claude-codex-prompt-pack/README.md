# Claude + Codex Prompt Pack for Beginners

## Purpose

Prompt pack ini membantu beginner builder merencanakan project dengan Claude, lalu mengeksekusi task kecil dengan Codex.

Fokusnya sederhana:

- Membuat ide project lebih jelas
- Mengubah ide besar menjadi task kecil
- Mengedit dokumentasi atau code dengan scope yang rapi
- Membantu pemula belajar workflow AI-assisted project secara bertahap

Gunakan prompt ini sebagai bahan belajar. Tetap baca ulang hasil AI sebelum dipakai, dicommit, atau dipublish.

## Who this is for

Use this prompt pack if you are:

- Baru belajar memakai Claude atau Codex untuk project kecil
- Ingin merapikan ide sebelum meminta AI membuat perubahan
- Ingin membuat dokumentasi, checklist, atau issue yang mudah dipahami
- Ingin menjaga task tetap kecil, jelas, dan bisa direview

## When to use this prompt pack

Gunakan prompt pack ini saat kamu:

- Memulai project AI-assisted dari ide awal
- Mereview README atau dokumentasi
- Membuat GitHub issue kecil
- Meminta Codex mengedit satu file dengan scope jelas
- Ingin memastikan output AI tetap praktis dan tidak berlebihan

## When to use Claude

Claude cocok dipakai untuk pekerjaan berpikir, merapikan ide, dan membuat rencana.

Gunakan Claude untuk:

- Planning project ideas
- Reviewing README atau dokumentasi
- Improving clarity
- Breaking big ideas into small tasks
- Membuat checklist issue yang mudah dikerjakan

## When to use Codex

Codex cocok dipakai ketika kamu sudah tahu file mana yang perlu diedit dan perubahan apa yang diminta.

Gunakan Codex untuk:

- Editing one file at a time
- Following a clear scope
- Making small documentation or code changes
- Producing diffs that can be reviewed before commit
- Checking that changes do not touch unrelated files

## Prompt examples

### 1. Ask Claude to turn an idea into a small project plan

```text
Saya punya ide project berikut:

[tulis ide project]

Tolong ubah ide ini menjadi rencana project kecil untuk pemula.

Buatkan:
1. Ringkasan project
2. Target user
3. Masalah yang ingin dibantu
4. Fitur awal yang paling sederhana
5. Urutan task kecil yang bisa dikerjakan satu per satu
6. Hal yang sebaiknya tidak dikerjakan dulu

Gunakan bahasa sederhana dan jangan membuat klaim berlebihan.
```

### 2. Ask Claude to review a README for beginner clarity

```text
Tolong review README berikut dari sudut pandang pemula Indonesia.

Cek:
1. Apakah tujuan project jelas?
2. Apakah pembaca tahu harus mulai dari mana?
3. Apakah ada istilah teknis yang perlu dijelaskan?
4. Apakah langkah berikutnya mudah diikuti?
5. Apakah ada klaim yang terlalu besar atau belum didukung bukti?

README:
[tempel isi README di sini]

Berikan saran perbaikan yang praktis dan singkat.
```

### 3. Ask Codex to edit only one specific file

```text
Please edit this file only:

[path/to/file.md]

Task:
[jelaskan perubahan yang diminta]

Rules:
- Do not edit any other files.
- Keep the change small and beginner-friendly.
- Avoid claims about users, stars, downloads, adoption, or large impact.
- After editing, summarize what changed.
```

### 4. Ask Codex to improve documentation without changing unrelated files

```text
Please improve the documentation in this file only:

[path/to/file.md]

Goal:
[jelaskan tujuan dokumentasi]

Requirements:
- Keep the main content simple and practical.
- Improve clarity for beginner AI builders.
- Do not rewrite unrelated sections.
- Do not change files outside the allowed path.
- Show the diff summary after editing.
```

### 5. Ask Claude to create a small GitHub issue checklist

```text
Saya ingin membuat GitHub issue kecil untuk project dokumentasi.

Konteks:
[jelaskan konteks singkat]

Tolong buatkan:
1. Judul issue
2. Tujuan issue
3. Checklist task kecil
4. Non-goals
5. Definition of done

Pastikan issue ini mudah dipahami oleh first-time contributor.
```

## Safety notes

- Keep tasks small.
- Review diffs before committing.
- Do not blindly accept generated code.
- Do not paste secrets, API keys, passwords, or private credentials into prompts.
- Ask the AI to explain changes in simple language.
- If the AI changes more files than requested, stop and review before continuing.

## Suggested workflow

1. Plan with Claude.
2. Create or choose one GitHub issue.
3. Ask Codex to edit only the allowed file.
4. Review the diff.
5. Commit and push.
6. Close the issue only after the working tree is clean.
