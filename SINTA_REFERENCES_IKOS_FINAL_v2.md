# Bank Referensi Nasional Terindeks SINTA — IKOS (FINAL v2)

**Versi:** 2.0 — hasil verifikasi silang 8 PDF jurnal asli terhadap `SINTA_REFERENCES_IKOS_LAST_FINAL.md`
**Prinsip kerja:** Tidak ada asumsi tanpa dasar. Setiap sel yang berubah dari versi sebelumnya dicatat di kolom **Koreksi** beserta alasannya. Informasi yang tidak ada di PDF/file terlampir ditulis eksplisit **TIDAK DITEMUKAN DI SUMBER** — tidak dikarang.

---

## ⚠ KONTRADIKSI TERDETEKSI (hasil cross-check terhadap `07_IKOS_SPECIFICATION_FINAL.md` Bagian 1–14.4)

- **Lokasi:** Bagian 7.6 (draf snippet baru, mengikuti penempatan di `IKOS_INTEGRATION_AND_BLUEPRINT.md`) vs Bagian 5.1, 5.2, dan 7.4 spesifikasi (terkunci).
- **Isi kontradiksi:** Definisi IKOS yang terkunci menyatakan kerentanan yang diukur adalah **eksposur terhadap disrupsi otomasi mekanis + GenAI** (Bagian 5.1), dan Bagian 5.2 secara eksplisit membatasi apa yang IKOS bukan. Namun draf blueprint untuk 7.6 memakai Annazah dkk. (2023) — dan kini Farhan & Irwansyah (2023) — untuk "memperkuat argumen bahwa S9 (Transportasi dan Pergudangan) layak dipandang bereksposur tinggi terhadap disrupsi". Setelah PDF dibaca penuh, kedua studi tersebut terverifikasi mengukur **kerentanan relasi kerja/regulasi kemitraan (precarity)**, bukan risiko otomasi/eksposur GenAI. Menyamakan keduanya berisiko konflasi dua konstruk "kerentanan" yang berbeda — persis jenis kerentanan argumentatif yang Bagian 5.2 minta dihindari.
- **Rekomendasi (tanpa memutuskan sendiri):**
  - **Opsi A:** Reposisi kedua referensi di 7.6 sebagai *konteks kerentanan struktural pekerja platform* (sensitivitas sosial-ekonomi S9), bukan bukti eksposur otomasi. Snippet 7.6 di `IKOS_SNIPPETS_INTEGRATED.md` sudah ditulis dengan kalimat pembatas versi Opsi A, tetapi keputusan final tetap di tim.
  - **Opsi B:** Pertahankan framing asli blueprint ("bereksposur tinggi terhadap disrupsi") dan terima risiko juri mempertanyakan lompatan dari precarity regulasi ke risiko otomasi.

### Catatan Anomali Internal Sumber (bukan kontradiksi dengan spesifikasi, dilaporkan agar tidak dikutip mentah)

1. **Annazah dkk. (2023), abstrak & hal. 199:** "share tenaga kerja di sektor formal sebesar 49,69% lebih kecil jika dibandingkan dengan sektor informal (59,31%)" — kedua angka berjumlah >100%. Dikutip persis apa adanya; jangan dipakai di esai tanpa verifikasi ulang ke rilis BPS.
2. **Annazah dkk. (2025):** bagian hasil (hal. 291) menulis efek wilayah high–high "approximately **74.02%** higher wage levels", tetapi bagian kesimpulan (hal. 293) menulis "approximately **55.36%** higher". Angka yang dipakai di snippet adalah versi bagian hasil (0,554 → ≈74,02%; dengan fixed effect 0,422 → ≈52,53%), dengan anomali ini dicatat terbuka.

---

## Pemetaan File PDF → Baris Tabel

| File PDF | Referensi (No. di tabel) | Hasil Pencocokan |
|---|---|---|
| `Kartu Prakerja Program and Youth Employment Gender-Specific Outc.pdf` | No. 1 — Anggara (2024, EFI) | COCOK |
| `8212-18692-1-PB.pdf` | No. 3 — Farhan & Irwansyah (2023) | COCOK |
| `document.pdf` | No. 6 — Nuraeni dkk. (2022) | COCOK |
| `document (1).pdf` | No. 7 — Wahyuni & Asy-Syifa (2025) | COCOK, dengan koreksi urutan penulis |
| `document (2).pdf` | No. 8 — Annazah dkk. (2023) | COCOK |
| `document (3).pdf` | No. 10 — Annazah dkk. (2025) | COCOK |
| `02.+Saragih.pdf` | No. 9 — Saragih (2019) | COCOK |
| `8171-18688-1-PB.pdf` | No. 11 — Alfaritdzi (2023) | COCOK, dengan koreksi penulis kedua |

Tidak ada PDF yang berstatus "REFERENSI BARU — BELUM ADA DI TABEL". Referensi No. 2, No. 4, dan No. 5 tetap **tanpa PDF**.

---

## Tabel Utama Referensi SINTA (v2)

| No | Sitasi APA Lengkap (terkoreksi) | Topik Singkat | SINTA Level | Data & Metode | Temuan Inti | Fungsi untuk IKOS | Koreksi | Status |
|---|---|---|---|---|---|---|---|---|
| 1 | Anggara, R. T. (2024). Kartu Prakerja Program and Youth Employment: Gender-Specific Outcomes in Indonesia. *Economics and Finance in Indonesia*, 70(1), 49–62. https://doi.org/10.47291/efi.2024.04 | Dampak Kartu Prakerja terhadap probabilitas kerja pemuda (18–24), dipilah gender | SINTA 2 (klaim file asli; tidak dapat diverifikasi dari PDF — dipertahankan) | PSM (weighted probit; NN, radius, kernel) atas **Sakernas Agustus 2021**; N=4.562 (952 peserta, 3.610 non-peserta); Rosenbaum bounds Γ=1–3 | ATT keseluruhan +5,1 s.d. +5,3 poin persentase; perempuan +5,7 s.d. +7,2 pp (signifikan 5%), laki-laki +4,1 s.d. +4,6 pp | Bagian 7 (7.6), 9.5, 12.2 | Sitasi tabel lama sudah persis sama dengan PDF (judul, volume, halaman, DOI cocok). "PERLU CEK gelombang Sakernas" di kolom metode kini terjawab dari PDF: **Agustus 2021** (hal. 52). Penulis lengkap: Rizki Tri Anggara, BPS-Statistics of Prabumulih Municipality | **TERVERIFIKASI — PDF TERSEDIA** |
| 2 | Suryono, I. L., Parmawati, R., Warsida, R. Y., Maryani, M., & Yani, R. A. A. (2022). Efektivitas Balai Latihan Kerja Komunitas dalam Meningkatkan Kualitas Tenaga Kerja. *Jurnal Ketenagakerjaan*, 17(1), 88–104. https://doi.org/10.47198/naker.v17i1.125 | Efektivitas kelembagaan BLK Komunitas | SINTA 2 (klaim file asli) | Kuantitatif deskriptif; kuesioner + dokumentasi; 4 aspek | BLK Komunitas dinilai efektif meningkatkan kualitas tenaga kerja, tapi jumlah lulusan tinggi tidak diimbangi ketersediaan lapangan kerja | Bagian 9.5, 12.2, 19 | Tidak ada koreksi — tidak ada PDF terlampir dan tidak ada dasar baru | **TANPA PDF — status asal dipertahankan** (sitasi lengkap sudah ada di file asli; peran: PENDUKUNG) |
| 3 | Farhan, M. I., & Irwansyah. (2023). Resistansi Pengemudi Ojek Online terhadap Celah Hukum Ketenagakerjaan. *Jurnal Kebijakan Publik*, 14(1), 119–130. https://doi.org/10.31258/jkp.v14i1.8212 | Kerentanan kerja pengemudi ojek online akibat celah regulasi kemitraan | SINTA 4 (klaim file asli; tidak tercetak di PDF — dipertahankan) | Kualitatif, studi kasus; studi pustaka + wawancara semi-terstruktur 3 pengemudi (purposive + snowball) di Kota Depok, November 2022; teori gamifikasi kerja | Status "mitra" dimanfaatkan perusahaan aplikasi menghindari kewajiban hak dasar & jaminan sosial; kemitraan ganda sebagai resistansi individualistis | Bagian 7 (7.6), 12.2 | Judul, jurnal, volume/nomor, tahun, halaman cocok persis dengan PDF. Catatan: DOI **tidak tercetak di PDF**, namun konsisten dengan ID artikel 8212 (nama file & pola URL jurnal); inisial "Irwansyah, I." pada tabel lama disederhanakan (PDF hanya menulis "Irwansyah") | **TERVERIFIKASI — PDF TERSEDIA** |
| 4 | Suryadi, & Nasution, F. A. P. (2023). Revolusi Industri, Tren Pekerjaan Masa Depan, dan Posisi Indonesia. *Jurnal Ketenagakerjaan*, 18(2), 125–141. https://doi.org/10.47198/naker.v18i2.237 | Positioning Indonesia pada tren pekerjaan masa depan | SINTA 2 (klaim file asli) | Kualitatif — tinjauan sistematis + analisis WEF Future of Jobs Report 2023 | Perusahaan RI menilai reskilling/upskilling & kerja fleksibel lebih rendah efektivitasnya vs rata-rata global | Bagian 9.5, 27 | Tidak ada koreksi — tidak ada PDF terlampir dan tidak ada dasar baru | **TANPA PDF — status asal dipertahankan** (peran: PENDUKUNG) |
| 5 | Anggara, R. T., & Auwalin, I. (2024). Optimizing the Kartu Prakerja Program for young workers. *Economics Development Analysis Journal*, 13(2), 168–178. https://doi.org/10.15294/edaj.v13i2.78970 *(sitasi diisi dari sumber tidak langsung — lihat Koreksi)* | Dampak partisipasi Kartu Prakerja terhadap retensi kerja & pendapatan pekerja muda | SINTA 2 (klaim file asli) | PSM; Sakernas Agustus 2021 (klaim blueprint — belum terverifikasi ke artikel asli) | Partisipasi Kartu Prakerja berasosiasi negatif signifikan dengan retensi kerja pekerja muda; efek pendapatan positif tidak signifikan (klaim blueprint — belum terverifikasi) | Bagian 7 (7.4 — kalimat penutup), 9.5, 12.2, 19 | Sitasi APA lengkap kini dapat diisi dari **daftar pustaka `document (1).pdf`** (Asy-Syifa & Wahyuni, 2025, hal. 493) — ini sumber tidak langsung; judul/volume/halaman/DOI tetap wajib dicek ke artikel asli. Item tindak lanjut afiliasi: inisial "R. T." pada sitasi tersebut mengindikasikan penulis yang sama dengan No. 1 (Rizki Tri Anggara), namun **belum terkonfirmasi definitif** | **BUTUH VERIFIKASI MANUAL — akses server terblokir (Cloudflare, journal.unnes.ac.id), coba jalur Garuda/SINTA sebagai alternatif** |
| 6 | Nuraeni, Y., Yuliastuti, A., Nasution, F. A. P., Muharam, A. S., & Iqbal, F. (2022). Peran Balai Latihan Kerja (BLK) Komunitas dalam Menyediakan Tenaga Kerja pada Dunia Usaha dan Industri. *Jurnal Ketenagakerjaan*, 17(1), 11–26. https://doi.org/10.47198/naker.v17i1.124 | Peran & ketersediaan data BLK Komunitas di level kelembagaan | SINTA 2 (klaim file asli) | Kualitatif deskriptif; wawancara informan kunci, FGD, observasi, studi dokumen; purposive sampling di **4 provinsi**: Jawa Barat, Lampung, Sulawesi Selatan, NTB | Data BLK Komunitas tersedia kelembagaan namun pendataan kebekerjaan alumni sangat bergantung inisiatif BLK-UPTP pembina; alumni sulit terserap DUDI, banyak diarahkan berwirausaha | Bagian 9.5, 12.2, 19 | Sitasi APA lengkap kini terisi dari halaman pertama PDF (sebelumnya "PERLU DIRAPIKAN"). Nama lengkap penulis: Yeni Nuraeni, Ari Yuliastuti, Faizal Amir Parlindungan Nasution, Asep Saepul Muharam, Faizul Iqbal. Nuansa temuan: frasa "granularitas terbatas untuk breakdown per sektor" di tabel lama tidak muncul verbatim di PDF; yang terverifikasi adalah keterbatasan pendataan kebekerjaan/alumni dan ketergantungan pada BLK-UPTP (hal. 21–22) — konsisten arah, redaksi disesuaikan | **TERVERIFIKASI — PDF TERSEDIA** |
| 7 | Asy-Syifa, A., & Wahyuni, R. N. T. (2025). The Impact of Kartu Prakerja Program Participation on the Decision to Become a Gig Worker and Gig Worker Earnings in Indonesia. *Jurnal Ketenagakerjaan*, 20(3), 477–496. https://doi.org/10.47198/jnaker.v20i3.539 | Dampak partisipasi Kartu Prakerja terhadap status kerja gig & pendapatan | SINTA 2 (klaim file asli) | Sakernas Agustus 2024; PSM (NN, caliper/radius, kernel) + model Tobit; N=16.394 (keputusan gig), N=11.331 (pendapatan); Rosenbaum bounds Γ=1–10 | Partisipasi Kartu Prakerja menaikkan probabilitas menjadi pekerja gig namun menurunkan pendapatan per jam mereka | Bagian 7 (7.4 — kalimat penutup), 9.5, 12.2 | **KOREKSI URUTAN PENULIS:** tabel lama menulis "Wahyuni, & Asy-Syifa (2025)"; halaman pertama PDF menulis "Adha Asy-Syifa, Ribut Nurul Tri Wahyuni*" — penulis pertama adalah Asy-Syifa (Wahyuni adalah penulis korespondensi). Sitasi in-text seharusnya (Asy-Syifa & Wahyuni, 2025). Halaman awal 477 diinferensikan dari header halaman kedua ("478"); nomor halaman tidak tercetak di lembar pertama PDF | **TERVERIFIKASI — PDF TERSEDIA** |
| 8 | Annazah, N. S., Tobing, H., Nasution, F. A. P., & Muhyiddin. (2023). Kondisi Kerja dalam Relasi Kemitraan: Studi Kasus pada Mitra Perusahaan Transportasi Online. *Jurnal Ketenagakerjaan*, 18(3), 198–212. https://doi.org/10.47198/naker.v18i3.305 | Kerentanan kerja mitra transportasi online akibat lemahnya perlindungan regulasi | SINTA 2 (klaim file asli) | Indepth interview komunitas ojek online di 3 provinsi zonasi 1 (DIY, Jawa Timur, Jawa Barat) + FGD stakeholder (Disnaker); analisis deskriptif; data sekunder lintas negara, analisis komparatif | Relasi kemitraan rentan (kekosongan hukum kemitraan & transportasi online; ketidakpastian pendapatan; jam kerja panjang); pengemudi menginginkan jaminan penghasilan | Bagian 7 (7.6), 12.2 | Sitasi APA lengkap kini terisi dari halaman pertama PDF (sebelumnya "PERLU DIRAPIKAN"). Metode "Wawancara / FGD" pada tabel lama terkonfirmasi dan diperinci. Halaman awal 198 diinferensikan dari header halaman kedua ("199") | **TERVERIFIKASI — PDF TERSEDIA** |
| 9 | Saragih, L. (2019). Identifikasi Dampak Perkembangan Teknologi terhadap Tenaga Kerja Toko Ritel Indonesia: Studi Kasus Toko X. *Jurnal Kependudukan Indonesia*, 14(1), 13–28. DOI: **TIDAK DITEMUKAN DI SUMBER** (tidak tercetak di PDF; p-ISSN 1907-2902, e-ISSN 2502-8537) | Dampak adopsi teknologi terhadap pekerja ritel berketerampilan rendah | SINTA 3 (klaim file asli) | Kualitatif (September–November 2018): observasi, wawancara mendalam, analisis SWOT; studi kasus Toko X (toko tanpa kasir pertama di Indonesia/Asia Tenggara) | Dampak adopsi teknologi (AI, big data, computer vision, toko tanpa kasir) ambigu — kasir & petugas keamanan tergantikan, namun tenaga kerja tetap dipekerjakan dan muncul kebutuhan keterampilan baru (STEM) | Bagian 7 (7.6), 12.2, 27 | Sitasi APA lengkap kini terisi dari halaman pertama PDF (sebelumnya "PERLU DIRAPIKAN"). Penulis: Luciana Saragih, Program Studi Ketahanan Nasional UI. DOI wajib dilengkapi manual (tidak ada di PDF) | **TERVERIFIKASI — PDF TERSEDIA** (DOI masih perlu dilengkapi manual) |
| 10 | Annazah, N. S., Martak, Y. F., Ilma, M. A. A., & Munandar, R. A. (2025). Analysis of Human Potential Resources Quality in High Growth Industrial Sectors in Indonesia. *Jurnal Ketenagakerjaan*, 20(2), 283–296. https://doi.org/10.47198/jnaker.v20i2.502 | Kesenjangan kualitas SDM pada sektor pertumbuhan tinggi (level distrik–sektor) | SINTA 2 (klaim file asli) | Data longitudinal Sakernas **2012 dan 2022** (dua gelombang) level distrik–sektor + data pelatihan 2024; regresi panel dengan province fixed effects; 517.713 individu (2012), 752.688 (2022) | Hanya 12,73% kabupaten/kota "high–high" (pertumbuhan sektoral + peningkatan SDM berpendidikan tinggi); wilayah high–high berupah ±74% lebih tinggi (±52,5% setelah fixed effects); efek pendidikan (4–8%) dan pelatihan (5–7%) sendiri-sendiri jauh lebih kecil | Bagian 9.3, 12.2, 27 | Sitasi APA lengkap kini terisi dari halaman pertama PDF (sebelumnya "PERLU DIRAPIKAN"). Nuansa metode: tabel lama menulis "panel Sakernas 2012–2022"; PDF memakai dua gelombang (2012 & 2022), bukan seri tahunan penuh. Halaman awal 283 diinferensikan dari header halaman kedua ("284"). Perhatikan anomali 74,02% vs 55,36% (lihat Catatan Anomali di atas) | **TERVERIFIKASI — PDF TERSEDIA** |
| 11 | Alfaritdzi, R. M., & Prathama, A. (2023). Peran Balai Pelatihan Vokasi dan Produktivitas (BPVP) dalam Mengurangi Angka Pengangguran. *Jurnal Kebijakan Publik*, 14(1), 111–118. DOI: **TIDAK DITEMUKAN DI SUMBER** (tidak tercetak di PDF; jurnal yang sama memakai pola DOI 10.31258/jkp — kemungkinan 10.31258/jkp.v14i1.8171 dari ID artikel, PERLU CEK sebelum dipakai) | Studi kasus BPVP/BLK lokal (BPVP Sidoarjo) dalam mengurangi pengangguran | SINTA 4 (klaim file asli) | Deskriptif kualitatif; observasi, wawancara, dokumentasi; purposive + snowball sampling; kerangka Pasal 17 Permenaker No. 1/2022 | Tiga peran BPVP Sidoarjo: (1) pelatihan vokasi online/offline (dana APBN, instruktur terverifikasi); (2) uji sertifikasi kompetensi bersama BNSP (20% materi, 80% praktik, acuan SKKNI); (3) peningkatan jejaring (pendampingan pasca-pelatihan, Job Market Fair dengan SMK & perusahaan swasta) | Bagian 12.2 | **KOREKSI PENULIS:** tabel lama hanya menulis "Alfaritdzi (2023)"; PDF mencantumkan dua penulis: Rivaldhi Muhammad Alfaritdzi & Ananta Prathama (UPN "Veteran" Jawa Timur). Topik "BPVP/BLK lokal" (hasil klarifikasi blueprint) **terkonfirmasi benar** dari PDF. "Temuan spesifik belum dirinci... PERLU CEK ke artikel penuh" pada tabel lama kini terjawab (lihat kolom Temuan Inti) | **TERVERIFIKASI — PDF TERSEDIA** (DOI masih perlu dilengkapi manual) |

---

## Tahap 2 — Ekstraksi Temuan Kuantitatif per PDF

Halaman merujuk nomor halaman cetak artikel (bukan urutan lembar PDF), kecuali dinyatakan lain.

### No. 1 — Anggara (2024), EFI 70(1), 49–62

1. ATT program terhadap probabilitas bekerja pemuda keseluruhan: **+0,0527 (NN, t=2,82), +0,0511 (radius, t=2,81), +0,0534 (kernel, t=2,94)** — "increasing the probability of employment by 5.1 to 5.3 percentage points" (teks hal. 57; Tabel 6 hal. 60; catatan tabel: * signifikan 10%, ** signifikan 5%).
2. Efek pada perempuan: **+0,0721 (NN, t=2,07), +0,0571 (radius, t=2,21), +0,0612 (kernel, t=2,38)** — "5.7 to 7.2 percentage points, with statistically significant results at the 5 percent level across all matching methods" (hal. 57; Tabel 6 hal. 60). Laki-laki: +4,1 s.d. +4,6 pp (radius tidak signifikan, t=1,62).
3. Sampel: **4.562 individu usia 18–24** (952 peserta yang menyelesaikan pelatihan: 488 laki-laki, 464 perempuan; 3.610 non-peserta) dari 777.982 individu usia kerja Sakernas Agustus 2021 (hal. 52–53).
4. Rata-rata bias kovariat turun dari **12,7% sebelum matching menjadi 1,7% setelah matching** (hal. 57).
5. Rosenbaum bounds: efek tetap signifikan hingga **Γ = 3** (hal. 58).
6. Konteks: pengangguran muda 2021 **19,55%**; rasio pengangguran muda-dewasa **4,63** (hal. 50).

### No. 3 — Farhan & Irwansyah (2023), Jurnal Kebijakan Publik 14(1), 119–130

Studi kualitatif — koefisien/statistik inferensial **TIDAK DITEMUKAN DI SUMBER**. Temuan terukur yang tersedia:

1. Informan: **3 pengemudi ojek online di Kota Depok** (2 laki-laki: ABP, MY; 1 perempuan: SH), wawancara semi-terstruktur **November 2022** (hal. 121).
2. Praktik kemitraan ganda: **ABP bermitra dengan 4 aplikasi sekaligus** (Gojek, Grab, Maxim, InDrive); MY dengan 2 aplikasi (Grab, Hangry); SH dengan 2 aplikasi (Grab, ShopeeFood) (hal. 121).
3. Seluruh (3 dari 3) informan **tidak memiliki wawasan seputar kerja layak dan indikator penentunya** (hal. 123, komunikasi pribadi 11 November 2022).

### No. 6 — Nuraeni dkk. (2022), Jurnal Ketenagakerjaan 17(1), 11–26

1. Pembangunan BLK Komunitas: **1.113 unit (2017–2019)**; alokasi 2020 dipangkas dari 2.000 menjadi 1.000 karena pandemi (hal. 13); total terbangun s.d. 2020 **±2.117 unit**, di antaranya **1.048 unit (49%) kejuruan TIK**; kapasitas pelatihan **±204.192 pencari kerja** (hal. 16–17, 18).
2. Instruktur: **2.127 orang** — baru 1 instruktur per BLK-K yang dilatih Kemnaker (ideal minimal 3); biaya pelatihan instruktur **Rp32 juta untuk 47 hari (320 JP)**, tenaga pengelola **Rp9,5 juta untuk 7 hari** (hal. 18).
3. Pendataan kebekerjaan alumni (fragmentaris, bergantung BLK-UPTP pembina): BLK-UPTP Bandung mencatat **119 peserta** (39 bekerja di industri, 80 berwirausaha); BLK-UPTP Samarinda **2 bekerja di industri + 16 berwirausaha**; BLK-UPTP Lembang menghimpun **±240 peserta tercatat bekerja** (hal. 21–22).
4. Konteks kewirausahaan: rasio wirausaha Indonesia **3,47%** vs Singapura 8,76%, Thailand 4,26%, Malaysia 4,74% (hal. 11, mengutip Nurmayanti, 2020).
5. Ekosistem pelatihan vokasi s.d. 2019: **305 BLK Pemerintah, 5.020 LPKS, 109 lembaga pelatihan K/L lain, 1.799 Training Center industri, 1.113 BLK Komunitas** (hal. 14).

### No. 7 — Asy-Syifa & Wahyuni (2025), Jurnal Ketenagakerjaan 20(3), 477–496

1. ATT terhadap keputusan menjadi pekerja gig: **+0,0598 (nearest neighbor), +0,0622 (caliper/radius), +0,0392 (kernel), seluruhnya signifikan 5%** (Tabel 7, hal. 486).
2. ATT terhadap pendapatan per jam pekerja gig (model Tobit): **−0,2222 (NN), −0,1889 (caliper), −0,1896 (kernel), seluruhnya signifikan 1%** — teks: penurunan pendapatan per jam **22,22% / 18,89% / 18,96%** (Tabel 14 dan teks, hal. 489–490).
3. Rata-rata pendapatan per jam: peserta **Rp19.998,86** vs non-peserta **Rp27.716,21** (Tabel 10, hal. 487).
4. Partisipasi: hanya **702 dari 16.394 individu eligible (4,28%)** peserta Prakerja; **83,48% peserta adalah pekerja gig** (hal. 482–483; Tabel 3 hal. 483).
5. Dampak sektoral pada pendapatan: transportasi & pergudangan **ATT −0,173 (p=0,002, signifikan 1%)**; jasa lainnya **ATT −0,212 (p=0,040, signifikan 5%)** (Tabel 17, hal. 492).
6. Determinan partisipasi (APE logit): tiap tahun sekolah **+0,51 pp**, usia **−0,19 pp** per tahun, menikah **+1,94 pp**, perkotaan **+0,87 pp**, berpengalaman kerja **+2,51 pp** (Tabel 4, hal. 484).

### No. 8 — Annazah dkk. (2023), Jurnal Ketenagakerjaan 18(3), 198–212

1. Waktu kerja pengemudi ojek online **rata-rata 10–12 jam per hari**, umumnya tanpa hari libur; sebagian bekerja **lebih dari 12 jam** (hal. 201, 208).
2. Penghasilan harian merosot: **±Rp150.000/hari** pasca-COVID-19 dan kenaikan BBM (belum dipotong BBM/perawatan/makan) vs **±Rp300.000/hari pada 2017/2018** dengan jam kerja lebih pendek (hal. 202).
3. Jaminan sosial: iuran **Rp16.800/bulan (JKK Rp10.000 + JKM Rp6.800)**, terpotong otomatis dari saldo dompet digital; beban berlipat bila bermitra multi-aplikasi (hal. 202).
4. Atribut wajib (helm + jaket) **±Rp400.000** (hal. 202); insentif Gojek mensyaratkan **22 trip per hari**; batas potongan tarif aplikator maksimal **20%** (hal. 202).
5. Konteks makro: kontribusi ekosistem Gojek ke perekonomian nasional **Rp349–428 triliun (1,8–2,2% PDB) pada 2022**; GoTo menambah kesempatan kerja **1,7 juta orang (1,2% penduduk bekerja)** (hal. 199, mengutip LPEM FEB UI 2022). Catatan anomali share formal 49,69% vs informal 59,31% — lihat blok anomali di atas.
6. Komparasi internasional: putusan Mahkamah Agung Inggris 2021 menaikkan status **±70 ribu pengemudi Uber menjadi worker** (hal. 209).

### No. 9 — Saragih (2019), Jurnal Kependudukan Indonesia 14(1), 13–28

1. Akibat otomatisasi, estimasi risiko hilangnya pekerjaan ritel (Will Robots Take My Job, 2018, sebagaimana dikutip dalam Saragih, 2019): **kasir 97%, pramuniaga 92%, petugas keamanan 84%, petugas kebersihan 66%** (hal. 15).
2. ILO (2017, sebagaimana dikutip dalam Saragih, 2019): **91% tenaga kerja industri ritel dan reparasi kendaraan bermotor sangat berisiko** kehilangan pekerjaan akibat otomatisasi (hal. 15).
3. Observasi primer Toko X: toko tanpa kasir seluas **270 m²** tetap mempekerjakan **±18 karyawan** (shift siang & malam); profesi yang hilang: kasir dan petugas keamanan; pengemasan dialihkan ke resepsionis berperan ganda (hal. 17–19, 21).
4. Konteks tenaga kerja: pekerja perdagangan besar/eceran & reparasi kendaraan **±11,6 juta orang** (BPS Februari 2018, dalam Saragih, 2019, hal. 15).
5. Kualifikasi angkatan kerja (Dhakiri, 2018, dalam Saragih, 2019): dari angkatan kerja baru **±2,9 juta orang/tahun**, hanya **37% (3–4 dari 10 orang)** memenuhi persyaratan kerja (hal. 23).
6. Kesenjangan STEM (ILO 2017, dalam Saragih, 2019): hanya **24,4% perempuan** Indonesia mengambil jurusan STEM vs **50% laki-laki** (hal. 22–23).

### No. 10 — Annazah dkk. (2025), Jurnal Ketenagakerjaan 20(2), 283–296

1. Hanya **12,73% kabupaten/kota** mengalami pertumbuhan sektoral tinggi yang dibarengi peningkatan signifikan tenaga kerja berpendidikan tinggi ("high–high"); **87,27%** tumbuh tanpa perbaikan SDM memadai (Tabel 1, hal. 289).
2. Wilayah high–high: **koefisien log-wage 0,554, signifikan pada level 1% (robust SE 0,0898), setara ±74,02% tingkat upah lebih tinggi**; setelah province fixed effects **0,422 (SE 0,0995), setara ±52,53%** (Tabel 2 & teks, hal. 291). *(Kesimpulan artikel menulis ±55,36% — anomali internal, lihat blok anomali.)*
3. Efek parsial: delta pendidikan tinggi **0,0747***/0,0796*** (model tunggal) dan 0,0381***/0,0433*** (multivariabel)**; delta pelatihan **0,0666***/0,0693*** dan 0,0469***/0,0465***** — artikel merangkum kontribusi pendidikan 4–8% dan pelatihan 5–7% (Tabel 2, hal. 291–292; abstrak hal. 283).
4. Delta upah 2012–2022: wilayah high–high **Rp1.756.085** vs **Rp996.952** pada sektor tumbuh tanpa perbaikan SDM; rata-rata upah 2022 **Rp3.023.188** vs **Rp2.364.953** (hal. 290–291; uji-t signifikan).
5. Rata-rata delta perubahan sektoral **8,23%** vs delta proporsi pekerja berpendidikan tinggi hanya **4,31%** (hal. 289).
6. Sektor pertumbuhan tertinggi terbanyak: pos/telekomunikasi/penyiaran/sistem elektronik **26,88%** kabupaten/kota, transportasi **23,83%**, perdagangan **16,50%** (hal. 288).

### No. 11 — Alfaritdzi & Prathama (2023), Jurnal Kebijakan Publik 14(1), 111–118

1. Kelulusan pelatihan BPVP Sidoarjo 2020–2022: **1.486 dari 1.510 peserta (98,2%)**; per tahun: 2020 = 365/380 (96,1%), 2021 = 540/546 (99%), 2022 = 581/584 (99,5%) (Tabel 1, hal. 115).
2. Pengangguran Kabupaten Sidoarjo: **131.444 jiwa (10,97%)** — tertinggi kedua se-Jawa Timur setelah Kota Surabaya (hal. 112; satuan "juta jiwa" pada teks asli tampak salah ketik, dikutip apa adanya).
3. Penduduk usia kerja Sidoarjo Agustus 2020: **1,78 juta orang (naik 30,02 ribu vs Agustus 2019)**; angkatan kerja **1,19 juta orang (naik 2,00% / ±23,50 ribu)** (hal. 112, BPS Kab. Sidoarjo 2020).
4. Metode pelatihan & uji sertifikasi: **20% teori dan 80% praktik**, kurikulum SKKNI; pelatihan tersingkat **35 hari** (hal. 114–116).
5. Jejaring: **15 BLK/LPK Luar Negeri** terverifikasi menerima bantuan program pelatihan CPMI 2022 (hal. 117); konteks: Sidoarjo memiliki **±1.500 industri skala besar dan 6.000 industri skala menengah** (hal. 112).

---

## Item Tindak Lanjut (Diperbarui)

1. ~~Sitasi APA lengkap untuk No. 6–11~~ — **Selesai** untuk No. 6, 7, 8, 9, 10, 11 (dari PDF terlampir). Tersisa: **DOI No. 9 dan No. 11** (tidak tercetak di PDF, cari via portal jurnal/Garuda) dan **verifikasi No. 5** (sitasi sudah terisi dari sumber tidak langsung, artikel asli belum diakses).
2. **Konfirmasi afiliasi Anggara (No. 1) vs Anggara & Auwalin (No. 5):** ada bukti baru berupa inisial identik "Anggara, R. T." di daftar pustaka Asy-Syifa & Wahyuni (2025) — indikasi kuat orang yang sama, tetapi status tetap **PERLU CEK** sampai artikel EDAJ terbuka.
3. **Klarifikasi topik Alfaritdzi (2023)** — **Selesai dan terkonfirmasi dari PDF**: BPVP Sidoarjo (BLK lokal), bukan transportasi platform.
4. **Keputusan tim atas kontradiksi 7.6** (Opsi A vs Opsi B, lihat blok kontradiksi di atas) sebelum snippet 7.6 dianggap final.
