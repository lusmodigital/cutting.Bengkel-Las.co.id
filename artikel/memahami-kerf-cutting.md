---
article_id: CUT-08-01
title: "Kerf Cutting: Arti, Cara Mengukur, dan Dampaknya pada Ukuran"
slug: "memahami-kerf-cutting"
description: "Menulis target dimensi dan toleransi yang realistis serta mengantisipasi kerf dan kompensasi."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-12-28"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-08
primary_intent: "Memahami kehilangan lebar potong"
reader_community: "Bengkel-las.co.id"
reader_address: "Kawan Bengkel-las.co.id"
final_route: "/artikel/memahami-kerf-cutting.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
  - "https://www.iso.org/standard/83335.html"
  - "https://www.iso.org/standard/77795.html"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910.1200"
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910.252"
  - "https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026"
  - "https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015"
  - "https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021"
  - "https://www.iso.org/standard/80209.html"
---

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** `LOCAL-004`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi memilih jasa bengkel las](/wp-content/uploads/2020/02/memilih-jasa-bengkel-las.jpg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `memilih jasa bengkel las` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-004]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

# Kerf Cutting: Arti, Cara Mengukur, dan Dampaknya pada Ukuran

Halo, Kawan Bengkel-las.co.id! Kerf adalah lebar material yang hilang atau terbakar di sepanjang jalur potong. Karena garis alat memiliki lebar, ukuran geometri pada file tidak selalu sama dengan ukuran part setelah dipisahkan. Dampaknya paling terasa pada lubang, slot, sambungan tekan, dan tepi yang menjadi datum.

Jawaban praktisnya: ukur kerf pada kombinasi mesin, material, ketebalan, pahat atau nozzle, dan parameter yang benar-benar dipakai. Jangan menyalin angka dari pekerjaan lain. Gunakan hasil kupon untuk menentukan kompensasi, lalu cocokkan part dengan toleransi gambar. Jika dasar penerimaan belum tersedia, tandai [NEEDS PROJECT REVIEW] dan jangan menjanjikan ukuran akhir.

![Ilustrasi memilih jasa bengkel las](/wp-content/uploads/2020/02/memilih-jasa-bengkel-las.jpg)

*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*


## Kerf bukan toleransi

Kerf menggambarkan kehilangan material akibat proses, sedangkan toleransi adalah rentang ukuran yang masih diterima pada fungsi tertentu. Keduanya berhubungan tetapi tidak sama. Kerf dapat berubah karena fokus, kecepatan, energi, gas, geometri, jenis material, atau keausan alat. Toleransi harus berasal dari gambar dan acceptance basis; katalog [SNI 1729:2020 di BSN](https://pesta.bsn.go.id/produk/detail/12882-sni17292020) hanya menunjukkan identitas standar, bukan nilai penerimaan part Anda.

## Cara mengukur pada kupon

Gunakan kupon dari material dan batch yang sama. Buat dua garis atau bentuk yang dapat diukur sebelum dan sesudah dipotong. Ukur lebar celah dengan alat yang sesuai, catat sisi masuk dan sisi keluar, lalu ulangi pada beberapa lokasi bila prosedur menyetujuinya. Jangan mengubah parameter di tengah kupon tanpa mencatat perubahan. Hasil kupon adalah bukti proses tertentu, bukan jaminan semua material.

Untuk router, periksa mata, arah pemakanan, penahanan, dan serpihan. Untuk laser, catat fokus, nozzle, gas, dan kondisi permukaan. Untuk milling, catat pahat, fixture (alat penahan), datum (acuan geometri), dan urutan pemakanan. Jika metode ukur atau alat belum diverifikasi, status hasil tetap perlu ditinjau kompeten.

## Dampak pada desain

Slot yang terlalu sempit dapat membuat tab patah atau tidak masuk; slot terlalu lebar dapat membuat sambungan longgar. Lubang kecil dapat kehilangan bentuk ketika kerf mengambil sebagian dinding. Pada tepi yang akan dilas atau dilapisi, allowance (sisa ukuran untuk proses berikutnya) harus ditulis dan tidak boleh diasumsikan dari kerf saja.

Kawan Bengkel-las.co.id, bedakan ukuran nominal file, ukuran hasil ukur, dan ukuran yang disyaratkan fungsi. Simpan datum, arah ukur, alat, status kalibrasi, dan revisi file. Jika part akan dibalik atau dipindahkan, tetapkan referensi ulang agar kompensasi tidak menggeser fitur lain.

## Faktor yang mengubah hasil

Material berlapis, minyak, film, atau perekat dapat mengubah panas dan residu. SDS membantu komunikasi bahaya, tetapi contoh OSHA bukan hukum Indonesia ([OSHA 29 CFR 1910.1200](https://www.osha.gov/laws-regs/regulations/standardnumber/1910.1200)). Untuk pelapisan, [ISO 12944-5:2019](https://www.iso.org/standard/77795.html) memberi kerangka pemilihan sistem, bukan bukti kecocokan coating tertentu. ISO 3834-6 membahas informasi mutu fabrikasi, tetapi abstraknya tidak menetapkan angka kerf atau parameter mesin ([ISO 3834-6:2024](https://www.iso.org/standard/83335.html)).

## Titik tahan dan keselamatan

Hentikan proses bila part bergeser, nozzle atau pahat berpotensi bertabrakan, asap berubah, tepi retak, atau hasil kupon keluar dari kriteria. UU No. 1 Tahun 1970 dan Permenaker No. 5 Tahun 2018 perlu diterapkan sesuai lokasi dan energi aktual; [OSHA 29 CFR 1910.252](https://www.osha.gov/laws-regs/regulations/standardnumber/1910.252) hanya contoh bahaya kerja panas. Perubahan aturan atau lokasi harus ditinjau melalui [Permenaker No. 11 Tahun 2026](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026) dan [Permenaker No. 12 Tahun 2015](https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015) oleh pihak berwenang.

Sisa dan limbah yang mengandung coating atau kontaminan perlu dipisahkan serta diberi identitas. [PP No. 22 Tahun 2021](https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021) menjadi rujukan kerangka, bukan klasifikasi otomatis setiap offcut. Untuk kriteria mutu dan pemeriksaan, ISO 17635 dan ISO 9712 membedakan metode, kompetensi, dan penerimaan; gunakan dokumen lengkap ([ISO 17635](https://www.iso.org/standard/85705.html); [ISO 9712](https://www.iso.org/standard/75614.html); [ISO 5817](https://www.iso.org/standard/80209.html)).

## Jalan pintas yang sering gagal

Mengisi kompensasi kerf dari tabel internet lalu menggunakannya untuk semua bahan dapat memindahkan kesalahan ke seluruh batch. Alternatif yang lebih aman adalah mengunci kombinasi proses, membuat kupon, mengukur dengan metode yang disetujui, lalu menguji satu part pertama sebelum produksi berulang. Simpan hasil, parameter, dan revisi agar perubahan dapat dilacak.

## Kesimpulan dan langkah berikutnya

Kerf adalah kehilangan lebar potong yang harus diukur pada kombinasi proses aktual. Ia memengaruhi slot, lubang, tepi, dan allowance, tetapi tidak menggantikan toleransi atau acceptance basis.

Langkah berikutnya: siapkan kupon dari material dan batch yang sama, catat parameter serta alat ukur, ukur hasil terhadap datum, dan minta persetujuan teknis sebelum mengunci kompensasi. Jika bukti belum cukup, tinggalkan [NEEDS PROJECT REVIEW] dan tahan batch. Sobat Bengkel-las.co.id, aturan operasinya sederhana: kompensasi yang baik lahir dari data proses yang terlacak, bukan dari angka tebakan.

Untuk konteks umum, Anda dapat kembali ke [beranda Bengkel-las.co.id](/) sambil membawa catatan kupon dan gambar revisi.

Sebelum menerima hasil, buat lembar pemeriksaan yang memisahkan observasi, pengukuran, dugaan sebab, dan keputusan. Tulis nomor part, revisi file, material, ketebalan, sisi referensi, alat ukur, tanggal, serta nama pemeriksa. Nilai kerf tidak boleh dipakai untuk “memperbaiki” dimensi setelah part selesai tanpa persetujuan desain karena perubahan itu dapat menggeser datum atau mengurangi allowance sambungan.

Untuk pekerjaan yang melibatkan energi listrik, panas, atau debu, [UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970) dan [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018) harus diterapkan oleh penanggung jawab K3 sesuai kondisi aktual. Rujukan tersebut tidak memberi angka kerf, toleransi mesin, atau pilihan APD yang bisa disalin langsung. Jika pekerjaan berpindah ke lapangan, tinjau ulang akses, ventilasi, listrik, cuaca, material mudah terbakar, dan pemeriksaan sebelum melanjutkan.

Kerf juga dapat memengaruhi keputusan komersial. Penawaran yang menyebut “potong sesuai file” belum tentu memasukkan kompensasi, kupon, deburring, pengukuran, atau sortasi. Minta vendor menuliskan apa yang termasuk, kapan parameter dikunci, dan bagaimana hasil yang menyimpang ditangani. Dengan begitu, biaya rework tidak disamarkan sebagai variasi biasa dan setiap perubahan memiliki pemilik persetujuan.

Kawan Bengkel-las.co.id, gunakan hasil kupon sebagai batas pengetahuan, bukan sebagai janji universal. Bila material, nozzle, pahat, suhu, atau program berubah, ulangi verifikasi yang relevan. Catatan sederhana tentang perubahan sering lebih berguna daripada angka presisi yang tidak dapat ditelusuri ke proses nyata.

Jangan lupa menyimpan sisa kupon dan foto hasil awal bila prosedur mengizinkan. Sampel tersebut membantu membedakan perubahan proses dari perubahan material ketika ada komplain. Jika sampel harus dibuang, catat alasan dan identitasnya sehingga keputusan tetap dapat diaudit.

Rilis produksi hanya setelah kupon, gambar, dan kriteria ukur disetujui pihak yang berwenang. Simpan bukti itu bersama nomor pesanan dan revisi.

Perubahan kecil pun harus dicatat agar kompensasi tetap dapat ditelusuri konsisten.
