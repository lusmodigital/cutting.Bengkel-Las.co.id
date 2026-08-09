---
article_id: CUT-08-06
writing_contract_version: "native-id-v2"
title: "Lebar Slot, Diameter Lubang, dan Jarak Minimum Antarfitur"
slug: "batas-fitur-minimum-cnc-cutting"
description: "Menulis target dimensi dan toleransi yang realistis serta mengantisipasi kerf dan kompensasi."
status: draft
publication_date: "2026-01-19"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-08
primary_intent: "Memeriksa fitur kecil sebelum produksi"
reader_community: "Bengkel-las.co.id"
reader_address: "Sobat Bengkel-las.co.id"
final_route: "/artikel/batas-fitur-minimum-cnc-cutting.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
  - "https://www.iso.org/standard/83335.html"
  - "https://www.iso.org/standard/77795.html"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200"
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252"
  - "https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026"
  - "https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015"
  - "https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021"
  - "https://www.iso.org/standard/80209.html"
---

# Lebar Slot, Diameter Lubang, dan Jarak Minimum Antarfitur

Halo, Sobat Bengkel-las.co.id! Slot sempit, lubang kecil, dan fitur yang berdempetan tidak boleh diberi angka “aman” yang berlaku untuk semua mesin. Batas yang realistis berasal dari proses, alat, material, toleransi, dan dasar penerimaan proyek. Mulailah dengan geometri yang benar-benar diperlukan, tandai fitur kritis, lalu minta bengkel mengonfirmasi kemampuan proses sebelum gambar dikunci. Jika data mesin atau material belum tersedia, saya menulis [NEEDS REVIEW: kemampuan proses dan material belum dikonfirmasi] dan tidak menjanjikan ukuran minimum.

Kerf (lebar jalur material yang hilang akibat potong), diameter alat, getaran, penjepitan, dan kompensasi lintasan dapat mengubah bentuk akhir. Karena itu, angka pada gambar adalah target, bukan bukti bahwa fitur akan otomatis lolos inspeksi. Halaman ini membahas batas geometri kecil; pemilihan material dan nesting antarkomponen berada di luar cakupan.

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** `LOCAL-005`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi bengkel las](/wp-content/uploads/2019/10/bengkel-las.png)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `bengkel las` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-005]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

Gambar ini adalah aset lokal, bukan dokumentasi proyek tertentu, sehingga tidak menjadi bukti kemampuan mesin atau hasil potong.

![Ilustrasi bengkel las](/wp-content/uploads/2019/10/bengkel-las.png)

*Caption: Gambar ini adalah aset lokal, bukan dokumentasi proyek tertentu.*

## Definisikan fitur dan fungsi terlebih dahulu

Sebutkan apakah sebuah lubang untuk baut, jalur kabel, drainase, atau hanya pelepas tegangan. Slot (celah memanjang) perlu memiliki lebar, panjang, radius ujung, dan arah. Jarak minimum antarfitur diukur dari tepi ke tepi atau dari pusat ke pusat—pilih satu cara dan tuliskan. Datum (acuan geometri) harus menjelaskan dari mana ukuran diambil, agar operator dan pemeriksa tidak memakai titik berbeda.

Pisahkan dimensi kritis dari dimensi yang hanya membantu fabrikasi. Lubang yang menentukan posisi sambungan memerlukan dasar penerimaan dan toleransi yang jelas. Lubang akses yang tidak berhubungan dengan sambungan mungkin dapat memakai toleransi lebih longgar, tetapi keputusan itu tetap milik desain. Kawan Bengkel-las.co.id, jangan mengecilkan lubang hanya demi tampilan tanpa memeriksa alat masuk, radius sudut, dan kebutuhan inspeksi.

## Menghubungkan ukuran dengan proses cutting

Tanyakan proses yang benar-benar akan digunakan: laser, plasma, router, milling, atau kombinasi. Setiap proses memiliki karakter tepi, lebar potong, dan keterbatasan akses yang berbeda. Kompensasi alat menggeser lintasan untuk menempatkan tepi pada ukuran target, tetapi nilainya harus berasal dari prosedur serta verifikasi mesin, bukan angka internet.

Untuk fitur kecil, mulai dari potongan uji atau kupon bila proyek mengizinkan. Ukur diameter aktual, lebar slot, posisi terhadap datum, dan kondisi tepi. Catat alat ukur, identitas program, revisi, dan status kalibrasi atau verifikasi. [NEEDS REVIEW: tidak ada data uji, toleransi, atau status alat ukur pada paket ini.] ISO 17635:2025 mengingatkan bahwa metode, cakupan, kondisi permukaan, personel, peralatan, dan dasar penerimaan adalah bukti yang terpisah; lihat [abstrak ISO 17635](https://www.iso.org/standard/85705.html).

## Menetapkan jarak tepi dan antarfitur

Jarak antarfitur harus menjaga ligamen (jalur material tersisa di antara dua fitur) agar tidak mudah berubah bentuk atau robek selama cutting, pemindahan, dan finishing. Jangan mengubahnya menjadi satu angka tetap tanpa mengetahui ketebalan, arah gaya, cara penjepitan, dan urutan potong. Dekat tepi lembaran, tambahkan pertanyaan tentang deformasi serta kebutuhan margin.

Jika dua lubang dipakai untuk sambungan, periksa pola baut, akses pahat, dan ruang untuk alat ukur. Jika slot berada dekat tekukan, evaluasi apakah radius tekuk dan urutan pembentukan membuat ligamen menerima regangan berlebih. Desain yang disetujui, bukan artikel ini, menentukan apakah suatu jarak cukup secara struktural. Katalog [SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020) hanya menunjukkan identitas dokumen; teks standar dan paket kerja yang berlaku diperlukan untuk persyaratan desain.

## Toleransi, tepi, dan inspeksi

Tuliskan toleransi ukuran, posisi, dan bentuk secara terpisah. Toleransi lubang tidak otomatis sama dengan toleransi posisi pusat. Jelaskan apakah burr (geram tajam sisa pemotongan) boleh ada, harus dihilangkan, atau dinilai dengan kriteria lain. Jangan menyebut sebuah fitur “lulus” hanya karena diameter terukur; metode ukur, alat, permukaan, dan dasar penerimaan harus cocok.

ISO 5817:2023 dan ISO 9712:2021 dapat menjadi rujukan identitas untuk mutu pengelasan dan sertifikasi personel, tetapi abstraknya tidak memberi tabel batas cacat, teknik pemeriksaan, atau nilai penerimaan. Gunakan [abstrak ISO 5817](https://www.iso.org/standard/80209.html) dan [abstrak ISO 9712](https://www.iso.org/standard/75614.html) sebagai pintu ke dokumen resmi, lalu minta prosedur proyek. Sertifikat pemeriksa juga tidak membuktikan hasil part tertentu tanpa laporan yang dapat ditelusuri.

## Contoh keputusan bersyarat

Misalnya sebuah panel memerlukan slot untuk jalur kabel. Jika slot hanya untuk lewat dan tidak menjadi dudukan, tim dapat menguji apakah radius ujung dan lebar yang lebih longgar tetap memenuhi fungsi. Jika slot juga menerima pengikat, orientasi gaya, jarak tepi, dan toleransi posisi menjadi kritis; jangan memakai hasil uji fungsi sederhana sebagai bukti kekuatan. Catat asumsi, revisi gambar, hasil ukur, serta persetujuan pihak desain.

Untuk dua lubang yang sangat berdekatan, pilihan aman bukan selalu memperbesar jarak. Memindahkan pola dapat mengganggu datum, sambungan, atau ruang komponen lain. Buat dua alternatif layout, jelaskan dampak pada sisa material dan waktu, lalu minta keputusan tertulis. Sobat Bengkel-las.co.id, keputusan yang terdokumentasi lebih mudah diperiksa daripada instruksi lisan yang berubah di tengah produksi.

## Jalan pintas yang sering gagal

Shortcut pertama adalah menyalin angka minimum dari brosur mesin tanpa mencocokkan material dan ketebalan. Shortcut kedua adalah memperkecil slot untuk menghemat tempat tanpa pemeriksaan alat dan proses finishing. Shortcut ketiga adalah menilai semua fitur dengan penggaris yang sama, padahal kebutuhan posisi dan fungsi berbeda. Shortcut keempat adalah menganggap pemeriksaan visual menggantikan pengukuran atau NDT (pengujian tak merusak) yang ditetapkan proyek.

Catatan K3 juga harus spesifik. [UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018), [Permenaker No. 12 Tahun 2015](https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015), dan [Permenaker No. 11 Tahun 2026](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026) harus dibaca sesuai pekerjaan aktual. Panduan OSHA tentang komunikasi bahaya dan hot work—[1910.1200](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200) serta [1910.252](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252)—adalah rujukan Amerika Serikat, bukan otomatis hukum Indonesia.

## Checklist sebelum gambar dikeluarkan

Pastikan gambar menyebut fungsi fitur, datum, ukuran, toleransi, radius, jarak tepi, dan dasar penerimaan. Konfirmasi proses dan alat, lalu cocokkan program dengan revisi gambar. Siapkan kupon atau verifikasi awal bila risiko fitur kecil tinggi. Hubungkan nomor part, material, batch, program, operator, alat ukur, dan laporan agar traceability (keterlacakan) tidak putus. Jangan menebak kecocokan pelapis atau bahan habis pakai dari label generik; [ISO 3834-6:2024](https://www.iso.org/standard/83335.html), [ISO 12944-5:2019](https://www.iso.org/standard/77795.html), dan panduan OSHA tentang lembar data keselamatan memberi konteks, bukan bukti produk tertentu.

Bila pemotongan dipindahkan ke lapangan, evaluasi ulang akses, ventilasi, sumber api, energi, cuaca, pengangkatan, dan inspeksi. Rujuk [PP No. 22 Tahun 2021](https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021) untuk konteks lingkungan; klasifikasi limbah dan rute penanganan tetap memerlukan karakterisasi serta pihak berwenang.

## Penutup: kunci keputusan yang bisa ditindaklanjuti

Tidak ada satu angka minimum untuk semua slot, lubang, dan jarak antarfitur. Tetapkan fungsi, datum, proses, kerf, toleransi, tepi, dan bukti ukur; kemudian kunci ukuran hanya setelah kemampuan mesin serta dasar penerimaan dikonfirmasi. Teman Bengkel-las.co.id, minta bengkel mengembalikan hasil kupon atau verifikasi awal bersama revisi program, bukan sekadar janji “bisa”. Jika desain, material, atau kriteria inspeksi belum jelas, pertahankan [NEEDS REVIEW: persetujuan desain dan pemeriksaan belum lengkap] dan hentikan penerbitan gambar produksi. Anda dapat kembali ke [beranda Bengkel-las.co.id](/) untuk konteks umum, tetapi keputusan akhir harus berasal dari dokumen proyek dan peninjauan kompeten.
