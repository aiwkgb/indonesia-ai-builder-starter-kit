# Digital Product Landing Page Example

Contoh ini membantu pemula membuat struktur awal landing page untuk produk digital seperti eBook, template, workbook, checklist, prompt pack, atau mini-course.

Tujuannya bukan membuat landing page yang langsung sempurna, tetapi memberi contoh alur berpikir, struktur file, dan checklist dasar agar project bisa dibangun dengan bantuan AI secara lebih rapi.

## Untuk siapa contoh ini?

Gunakan contoh ini jika kamu:

- Ingin menjual produk digital sederhana
- Butuh landing page yang mobile-first
- Baru belajar membuat website dengan bantuan Claude, Codex, GitHub, dan Vercel
- Bingung harus mulai dari brief, copywriting, atau struktur file
- Ingin membuat project kecil yang bisa dikembangkan bertahap

## Jenis produk yang cocok

Contoh ini cocok untuk:

- eBook
- Template Canva
- Prompt pack
- Workbook
- Checklist
- Mini-course
- Digital guide
- File edukasi PDF

## Tujuan landing page

Landing page sebaiknya punya satu tujuan utama.

Contoh tujuan:

- Mengarahkan user membeli produk
- Mengarahkan user ke checkout
- Mengarahkan user ke WhatsApp
- Mengumpulkan leads
- Menjelaskan isi produk dengan jelas

Untuk pemula, jangan terlalu banyak tujuan dalam satu halaman.

## Struktur halaman yang disarankan

```text
landing-page/
  hero-section
  problem-section
  product-explanation
  what-you-get
  who-this-is-for
  benefits
  bonus-section
  faq-section
  final-cta
```

## Penjelasan setiap section

### 1. Hero section

Bagian paling atas halaman.

Isi minimal:

- Headline jelas
- Penjelasan singkat produk
- Benefit utama
- CTA utama
- Visual produk jika ada

Contoh pertanyaan sebelum menulis hero:

- Produk ini membantu siapa?
- Masalah utama apa yang diselesaikan?
- Hasil apa yang paling diinginkan user?

### 2. Problem section

Bagian ini menjelaskan masalah yang dialami target user.

Gunakan bahasa yang dekat dengan kehidupan user.

Contoh:

> Banyak pemula ingin mulai menjual produk digital, tapi bingung harus membuat produk apa, menulis apa, dan menjualnya lewat mana.

### 3. Product explanation

Jelaskan produk dengan sederhana.

Isi minimal:

- Produk ini apa
- Formatnya apa
- Cara menggunakannya bagaimana
- Cocok untuk siapa

### 4. What you get

Tampilkan isi produk.

Contoh:

- Main eBook
- Worksheet
- Checklist
- Prompt bonus
- Template pendukung

### 5. Who this is for

Jelaskan siapa yang paling cocok membeli atau menggunakan produk ini.

Contoh:

- Pemula yang ingin mulai jualan digital product
- Creator yang ingin membuat produk pertama
- Mahasiswa yang ingin belajar membuat aset digital
- Freelancer pemula yang ingin punya produk sederhana

### 6. Benefits

Benefit menjelaskan hasil atau perubahan yang user dapatkan.

Bedakan fitur dan benefit:

- Fitur: 30 halaman panduan
- Benefit: user punya langkah jelas untuk membuat produk digital pertama

### 7. Bonus section

Gunakan jika produk memiliki bonus.

Jangan terlalu berlebihan. Jelaskan bonus dengan realistis.

### 8. FAQ section

FAQ membantu mengurangi keraguan user.

Contoh pertanyaan:

- Apakah ini cocok untuk pemula?
- Apakah butuh skill desain?
- Apakah bisa dikerjakan dari HP?
- Setelah beli dapat apa?
- Bagaimana cara akses produknya?

### 9. Final CTA

Tutup halaman dengan ajakan yang jelas.

Contoh:

> Mulai bangun produk digital pertamamu hari ini.

## Struktur file sederhana

```text
digital-product-landing-page/
  README.md

  docs/
    landing-page-brief.md
    copywriting-draft.md
    changelog.md

  public/
    images/
      product-mockup.png
      hero-image.png

  src/
    app/
      page.tsx
    components/
      Hero.tsx
      ProblemSection.tsx
      ProductSection.tsx
      BenefitsSection.tsx
      FAQSection.tsx
      CTASection.tsx
    content/
      landing-page-copy.ts
```

Catatan: struktur ini hanya contoh. Sesuaikan dengan framework dan kebutuhan project.

## Template yang dipakai

Mulai dari template ini:

```text
templates/landing-page-brief.md
```

Jika project mulai lebih serius, tambahkan:

```text
templates/prd-template.md
templates/brand-guideline-template.md
templates/claude-project-instruction.md
templates/codex-agent-instruction.md
```

## Workflow sederhana

1. Isi landing page brief
2. Tulis target user dan masalah utama
3. Buat struktur section landing page
4. Minta Claude membantu merapikan copywriting
5. Minta Codex membuat struktur file atau halaman awal
6. Review tampilan mobile
7. Commit ke GitHub
8. Deploy ke Vercel
9. Audit halaman dengan checklist
10. Iterasi berdasarkan feedback

## Checklist sebelum deploy

- [ ] Headline jelas
- [ ] Target user jelas
- [ ] CTA terlihat di bagian atas
- [ ] Isi produk mudah dipahami
- [ ] FAQ tersedia
- [ ] Tampilan mobile terbaca
- [ ] Link CTA tidak rusak
- [ ] Gambar sudah dioptimalkan
- [ ] Tidak ada klaim berlebihan
- [ ] README project sudah menjelaskan cara menjalankan project

## Kesalahan umum pemula

### 1. Terlalu banyak CTA

Satu halaman sebaiknya punya satu CTA utama.

### 2. Headline terlalu umum

Headline seperti "Produk Digital Terbaik" kurang spesifik.

Lebih baik jelaskan untuk siapa dan hasilnya apa.

### 3. Terlalu cepat masuk desain

Sebelum desain, pastikan brief dan copywriting sudah cukup jelas.

### 4. Tidak cek mobile

Banyak user Indonesia membuka landing page dari HP. Selalu cek versi mobile.

### 5. Klaim terlalu besar

Hindari klaim seperti pasti cuan, auto kaya, atau hasil instan.

Gunakan bahasa jujur, praktis, dan realistis.

## Prompt awal untuk Claude

```text
Saya ingin membuat landing page untuk produk digital.

Bantu saya merapikan brief berikut menjadi struktur landing page yang jelas, mobile-first, dan beginner-friendly.

Target user:
[isi target user]

Produk:
[isi nama dan jenis produk]

Masalah utama:
[isi masalah]

Hasil yang dijanjikan:
[isi hasil realistis]

CTA utama:
[isi CTA]

Tolong buatkan:
1. Struktur section landing page
2. Draft headline
3. Draft copy tiap section
4. FAQ
5. Checklist sebelum build
```

## Prompt awal untuk Codex

```text
Build a simple mobile-first digital product landing page based on the provided landing page brief.

Rules:
- Keep the structure simple
- Use reusable components
- Prioritize mobile readability
- Make CTA buttons obvious
- Avoid unnecessary dependencies
- Do not add fake testimonials
- Keep copy easy to edit
- Explain what files were created or changed
```

## Prinsip utama

Landing page yang baik tidak harus kompleks.

Untuk pemula, yang paling penting adalah:

1. Target user jelas
2. Masalah jelas
3. Produk mudah dipahami
4. CTA jelas
5. Mobile readable
6. Bisa diperbaiki bertahap

Mulai dari versi sederhana, lalu iterasi setelah mendapat feedback.