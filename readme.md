# Integrated Master Map — CAPTCHA KRS UGM

Analisis studi kasus **CAPTCHA visual yang menghambat mahasiswa tunanetra saat proses war KRS** menggunakan pendekatan **COBIT 2019** dan perspektif **IT Audit**.

## Tentang Proyek

Proyek ini menunjukkan bagaimana sebuah masalah pada kontrol keamanan dapat ditelusuri secara sistematis dari kebutuhan stakeholder sampai menjadi audit finding dan recommendation.

Fokus utama analisis:

- **COBIT 2019** sebagai kerangka Enterprise Governance of I&T
- **Stakeholder Needs & Goals Cascade**
- **Governance vs Management**
- **BAI02 — Managed Requirements Definition**
- **BAI02.01 — Define and maintain business functional and technical requirements**
- Governance system components dan design factors
- Performance/capability gap
- Audit criteria, evidence, testing, finding, dan recommendation
- Keseimbangan **security control** dan **digital accessibility**

## Alur Analisis

```text
Stakeholder Need
      ↓
Enterprise Goals (EG03, EG05)
      ↓
Alignment Goals (AG01, AG06)
      ↓
Risk & Design Factors
      ↓
COBIT Objective: BAI02
      ↓
Practice: BAI02.01
      ↓
Capability / Gap
      ↓
Audit Criteria & Evidence
      ↓
Audit Finding
      ↓
Recommendation
      ↓
Governance & Continuous Improvement
```

## Ringkasan Kasus

Kontrol anti-bot pada KRS dibutuhkan untuk mengurangi risiko penggunaan bot, tetapi CAPTCHA visual dapat menjadi hambatan bagi mahasiswa tunanetra apabila tidak tersedia alternatif yang benar-benar dapat digunakan dengan teknologi asistif.

Dari sudut pandang audit, perhatian tidak berhenti pada fitur CAPTCHA. Analisis diarahkan ke proses **requirement definition**, karena kebutuhan aksesibilitas seharusnya dipertimbangkan sebelum solusi dibangun.

## Temuan Utama

**Criteria** — Requirement sistem KRS perlu mencakup kebutuhan aksesibilitas, termasuk mekanisme verifikasi non-visual yang kompatibel dengan teknologi asistif.

**Condition** — Sistem hanya menyediakan CAPTCHA visual tanpa alternatif fungsional yang benar-benar dapat digunakan mahasiswa netra.

**Cause** — Requirement definition belum melibatkan kelompok pengguna disabilitas dan belum mengacu secara memadai pada standar accessibility.

**Effect / Risk** — Mahasiswa netra berpotensi mengalami keterlambatan atau kehilangan kesempatan memperoleh kelas berkuota terbatas, serta muncul risiko ketidaksetaraan layanan dan ketidakpatuhan regulasi.

## Rekomendasi

1. **Jangka pendek:** menyediakan mekanisme verifikasi alternatif non-visual yang kompatibel dengan screen reader.
2. **Jangka menengah:** memperkuat BAI02.01 agar accessibility menjadi requirement wajib dan diteruskan ke proses build/desain melalui BAI03.
3. **Jangka panjang:** memasukkan digital accessibility ke arah strategis governance I&T melalui EDM01.
4. **Berkelanjutan:** memasukkan accessibility testing ke quality assurance melalui APO11 sebelum fitur sistem akademik dirilis.

> Prinsip utama: **jangan menukar security dengan accessibility.** Targetnya adalah security control yang tetap efektif sekaligus accessible.

## Cara Menjalankan Lokal

Tidak membutuhkan framework atau instalasi dependency.

1. Clone repository.
2. Buka `index.html` di browser.
3. Untuk melihat versi master map lengkap, buka `Integrated_Master_Map_CAPTCHA_KRS_UGM_v2.html`.

## GitHub Pages

Repository ini disusun agar dapat dipublikasikan sebagai static website menggunakan **GitHub Pages**.

Konfigurasi yang disarankan:

- **Source:** Deploy from a branch
- **Branch:** `main`
- **Folder:** `/ (root)`

Setelah GitHub Pages aktif, `index.html` akan menjadi halaman utama website.

## Catatan Akademik

Materi analisis mengikuti studi kasus dan kerangka yang digunakan dalam bahan proyek. Pemetaan COBIT seperti BAI02/BAI02.01, EG/AG, serta rekomendasi digunakan sebagai alur penalaran untuk menghubungkan kebutuhan stakeholder dengan proses audit.

---

**Topik:** IT Governance · COBIT 2019 · IT Audit · KRS · Accessibility · Security Control  
**Format:** Static HTML · GitHub Pages
