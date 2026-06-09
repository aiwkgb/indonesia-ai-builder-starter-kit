# Beginner Project Structure

Contoh ini menunjukkan struktur project sederhana untuk pemula yang ingin membangun website, landing page, atau project AI-assisted kecil dengan bantuan Claude, Codex, GitHub, dan Vercel.

Tujuannya bukan membuat struktur yang paling canggih, tetapi membuat struktur yang mudah dipahami, mudah dirawat, dan cukup rapi untuk mulai belajar.

## Untuk siapa contoh ini?

Gunakan contoh ini jika kamu:

- Baru belajar membuat project dengan bantuan AI
- Baru belajar GitHub
- Ingin membuat landing page produk digital
- Ingin membuat website personal brand atau creator brand
- Ingin membantu UMKM membuat website sederhana
- Sering bingung file harus disimpan di mana

## Kapan struktur ini cocok dipakai?

Struktur ini cocok untuk project kecil sampai menengah seperti:

- Landing page produk digital
- Website portofolio sederhana
- Website creator brand
- Website profil bisnis lokal
- Prototype SaaS kecil
- Demo project untuk belajar AI-assisted coding

Untuk project yang sudah besar, struktur ini bisa dikembangkan lagi sesuai kebutuhan.

## Struktur folder sederhana

```text
my-ai-assisted-project/
  README.md
  package.json
  .gitignore
  .env.example

  docs/
    prd.md
    brand-guideline.md
    changelog.md

  public/
    images/
    icons/

  src/
    app/
    components/
    content/
    lib/
    styles/

  prompts/
    claude-project-instruction.md
    codex-agent-instruction.md
```

Catatan: nama folder bisa disesuaikan dengan framework yang kamu pakai. Kalau kamu menggunakan Next.js, struktur `src/app` cocok untuk App Router. Kalau kamu memakai framework lain, sesuaikan seperlunya.

## Penjelasan setiap bagian

### `README.md`

File utama yang menjelaskan project.

Isi minimal:

- Project ini apa
- Untuk siapa
- Cara menjalankan project
- Cara deploy
- Link penting
- Status project

Contoh isi singkat:

```md
# Nama Project

Deskripsi singkat project.

## Cara menjalankan

npm install
npm run dev

## Status

Early version / prototype.
```

### `package.json`

File konfigurasi project JavaScript atau Node.js.

Biasanya berisi:

- Nama project
- Script untuk menjalankan project
- Dependencies
- Dev dependencies

Untuk pemula, kamu tidak perlu mengedit file ini terlalu sering kecuali saat menambah package.

### `.gitignore`

File untuk memberi tahu Git file mana yang tidak perlu ikut disimpan ke GitHub.

Contoh file yang biasanya diabaikan:

```text
node_modules/
.env
.next/
dist/
build/
```

### `.env.example`

Contoh file environment variable.

Jangan upload file `.env` asli yang berisi rahasia. Upload `.env.example` agar contributor tahu format yang dibutuhkan.

Contoh:

```text
NEXT_PUBLIC_SITE_URL=
DATABASE_URL=
API_KEY=
```

### `docs/`

Folder untuk menyimpan dokumentasi project.

Contoh isi:

```text
docs/
  prd.md
  brand-guideline.md
  changelog.md
```

Gunakan folder ini untuk menyimpan keputusan penting agar project tidak hanya bergantung pada chat AI.

### `docs/prd.md`

PRD atau Product Requirements Document.

Isi minimal:

- Target user
- Masalah
- Tujuan project
- Fitur utama
- Non-goals
- User flow
- Success criteria

Gunakan template dari:

```text
templates/prd-template.md
```

### `docs/brand-guideline.md`

Dokumen guideline brand.

Isi minimal:

- Nama brand
- Target audience
- Tone of voice
- Warna
- Typography
- Visual direction
- Do and don't

Gunakan template dari:

```text
templates/brand-guideline-template.md
```

### `docs/changelog.md`

Catatan perubahan project.

Contoh:

```md
# Changelog

## v0.1.0

- Added initial landing page
- Added mobile responsive layout
- Added CTA section
```

### `public/`

Folder untuk asset statis yang bisa diakses oleh website.

Contoh:

```text
public/
  images/
  icons/
```

Simpan file seperti logo, gambar produk, icon, atau mockup di sini.

### `src/`

Folder utama untuk source code project.

Contoh:

```text
src/
  app/
  components/
  content/
  lib/
  styles/
```

### `src/app/`

Folder halaman utama aplikasi atau website.

Jika menggunakan Next.js App Router, halaman utama biasanya ada di:

```text
src/app/page.tsx
```

### `src/components/`

Folder untuk komponen UI yang bisa digunakan ulang.

Contoh:

```text
src/components/
  Navbar.tsx
  Hero.tsx
  CTASection.tsx
  Footer.tsx
```

Untuk pemula, jangan terlalu banyak memecah komponen di awal. Pecah komponen ketika file sudah mulai terlalu panjang atau sulit dibaca.

### `src/content/`

Folder untuk menyimpan konten teks yang dipakai di halaman.

Contoh:

```text
src/content/
  landing-page.ts
  faq.ts
  testimonials.ts
```

Ini membantu memisahkan copywriting dari layout.

### `src/lib/`

Folder untuk fungsi helper atau konfigurasi kecil.

Contoh:

```text
src/lib/
  utils.ts
  constants.ts
```

Kalau belum butuh, folder ini boleh kosong atau tidak dibuat dulu.

### `src/styles/`

Folder untuk styling tambahan.

Contoh:

```text
src/styles/
  globals.css
```

Kalau menggunakan Tailwind CSS, styling utama biasanya ada di `globals.css` dan class Tailwind langsung di component.

### `prompts/`

Folder untuk menyimpan instruksi AI yang dipakai dalam project.

Contoh:

```text
prompts/
  claude-project-instruction.md
  codex-agent-instruction.md
```

Folder ini penting agar instruksi project tidak hilang di chat.

Gunakan template dari:

```text
templates/claude-project-instruction.md
templates/codex-agent-instruction.md
```

## Alur kerja yang disarankan

### 1. Mulai dari brief

Jangan langsung coding.

Tulis dulu:

- Project ini apa
- Untuk siapa
- Masalah apa yang diselesaikan
- Hasil akhir yang diinginkan
- Batasannya apa

### 2. Isi PRD

Gunakan:

```text
templates/prd-template.md
```

Simpan hasilnya sebagai:

```text
docs/prd.md
```

### 3. Isi brand guideline atau landing page brief

Untuk brand atau website creator, gunakan:

```text
templates/brand-guideline-template.md
```

Untuk landing page produk digital, gunakan:

```text
templates/landing-page-brief.md
```

### 4. Buat instruksi AI

Gunakan:

```text
templates/claude-project-instruction.md
templates/codex-agent-instruction.md
```

Simpan di folder:

```text
prompts/
```

### 5. Bangun project bertahap

Minta AI mengerjakan satu task kecil dulu.

Contoh task yang baik:

> Buat struktur folder awal dan halaman landing page sederhana berdasarkan PRD.

Contoh task yang kurang baik:

> Buatkan semua project sampai sempurna.

### 6. Review hasil

Cek:

- Apakah halaman bisa dibuka?
- Apakah layout mobile readable?
- Apakah CTA jelas?
- Apakah link tidak rusak?
- Apakah file tersusun rapi?

### 7. Commit ke GitHub

Gunakan commit message yang jelas.

Contoh:

```text
feat: add initial landing page
```

```text
docs: add project PRD
```

```text
fix: improve mobile hero spacing
```

### 8. Deploy ke Vercel

Gunakan checklist:

```text
templates/vercel-deploy-checklist.md
```

## Contoh urutan commit untuk project pemula

```text
docs: add initial PRD

docs: add brand guideline

chore: add project structure

feat: add homepage layout

feat: add CTA section

fix: improve mobile responsiveness

docs: update README with setup guide
```

## Kesalahan umum pemula

### 1. Langsung coding tanpa brief

Akibatnya AI menebak terlalu banyak dan hasilnya sering tidak sesuai.

Solusi: isi PRD atau brief dulu.

### 2. Satu prompt terlalu besar

Prompt terlalu besar membuat hasil sulit dikontrol.

Solusi: pecah task menjadi bagian kecil.

### 3. Tidak menyimpan keputusan penting

Kalau semua keputusan hanya ada di chat AI, project sulit dilanjutkan.

Solusi: simpan PRD, brand guideline, dan changelog di folder `docs/`.

### 4. Tidak mengecek mobile layout

Banyak user Indonesia membuka website dari HP.

Solusi: selalu cek tampilan mobile sebelum deploy.

### 5. Tidak membuat README

Tanpa README, orang lain sulit memahami project.

Solusi: tulis README sederhana sejak awal.

## Struktur minimal jika ingin lebih sederhana

Kalau struktur di atas masih terasa terlalu banyak, mulai dari versi ini dulu:

```text
my-project/
  README.md
  .gitignore

  docs/
    prd.md

  public/
    images/

  src/
    app/
    components/
```

Nanti folder lain bisa ditambahkan saat project mulai berkembang.

## Prinsip utama

Project yang baik tidak harus langsung kompleks.

Untuk pemula, yang paling penting adalah:

1. Tujuan jelas
2. Struktur mudah dipahami
3. Dokumentasi cukup
4. Bisa dijalankan
5. Bisa dideploy
6. Bisa diperbaiki bertahap

Mulai sederhana, lalu iterasi.
