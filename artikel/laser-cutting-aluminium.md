---
article_id: CUT-03-05
title: "Laser Cutting Aluminium: Reflektivitas, Burr, dan Distorsi"
slug: "laser-cutting-aluminium"
description: "Menentukan kecocokan laser untuk plat logam serta memahami hasil dan batas prosesnya."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-09-23"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-03
primary_intent: "Menilai risiko laser pada aluminium"
reader_community: "Bengkel-las.co.id"
reader_address: "Kawan Bengkel-las.co.id"
final_route: "/artikel/laser-cutting-aluminium.html"
technical_review: required
sources:
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
  - "https://www.iso.org/standard/83335.html"
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://www.iso.org/standard/80209.html"
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
  - "https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026"
  - "https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021"
---

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** `LOCAL-008`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi teralis jendela material aluminium](/wp-content/uploads/2020/02/teralis-jendela-material-aluminium.jpg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `teralis jendela material aluminium` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-008]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

# Laser Cutting Aluminium: Reflektivitas, Burr, dan Distorsi

Operator menjalankan uji, pemeriksa mencatat hasil, dan penanggung jawab teknis menyetujui batas rilis; pembagian aktor ini mencegah pengalaman sekali pakai dianggap sebagai jaminan universal.

Halo, Kawan Bengkel-las.co.id!

Laser bisa memotong aluminium, tetapi kata “bisa” bukan berarti setiap plat, mesin, dan gambar kerja akan langsung menghasilkan tepi yang siap dipasang. Aluminium memantulkan sebagian energi laser; panas yang tidak terkelola dapat meninggalkan burr (geram yang menempel), mengubah tepi, atau melengkungkan bagian tipis. Jadi keputusan yang aman adalah bersyarat: cocok bila mesin, material, program, gas bantu, dan pemeriksaan sudah dibuktikan pada kombinasi yang sama. Tanpa bukti itu, anggap hasil sebagai perlu uji, bukan janji.

Bukti yang mengubah keputusan bukan sekadar merek mesin. Minta catatan uji pada jenis dan ketebalan aluminium yang akan dipakai, gambar dengan toleransi, serta kriteria penerimaan tepi. [NEEDS TECHNICAL REVIEW: data uji mesin, paduan, ketebalan, dan kriteria burr/distorsi belum tersedia.] Untuk pekerjaan yang terhubung ke struktur atau keselamatan, paket fabrikasi dan pemeriksaan kompeten tetap menjadi penentu.

![Ilustrasi teralis jendela material aluminium](/wp-content/uploads/2020/02/teralis-jendela-material-aluminium.jpg)

Aset lokal; ini bukan dokumentasi proyek tertentu.

## Definisi dan batas objek

Artikel ini membahas pemotongan plat aluminium dengan laser: apa yang menyebabkan reflektivitas, burr, dan distorsi, serta cara menyaring pekerjaan sebelum produksi. Fokusnya aluminium, bukan perbandingan semua material. Ia juga bukan pengganti desain sambungan, perhitungan struktur, atau persetujuan K3.

Bedakan tiga hal saat membaca hasil. Reflektivitas adalah persoalan interaksi energi dengan permukaan dan dapat memengaruhi kestabilan proses. Burr adalah sisa logam di tepi yang harus dinilai terhadap fungsi dan proses setelah potong. Distorsi adalah perubahan bentuk atau posisi akibat siklus panas dan pelepasan tegangan; pada komponen tipis, sedikit perubahan dapat mengganggu perakitan. Besar-kecilnya ketiganya bergantung pada paduan, kondisi permukaan, ketebalan, geometri, penjepitan, dan setelan yang harus diverifikasi, bukan ditebak dari nama material saja.

Untuk komponen yang akan menjadi bagian struktur, dokumen yang mengatur fungsi, dimensi, material, toleransi, urutan fabrikasi, pemeriksaan, dan penyimpangan harus jelas. Katalog BSN untuk SNI 1729:2020 hanya mengonfirmasi identitas dokumen, bukan memberikan klausul desain atau nilai penerimaan; gunakan standar berlisensi dan dokumen proyek yang diterbitkan untuk kerja. [NEEDS DOCUMENT REVIEW: basis desain dan toleransi komponen belum diberikan.] ([BSN—SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020))

## Cara kerjanya

Urutan yang masuk akal dimulai dari gambar kerja. Operator memeriksa paduan, tebal nominal, ukuran lembar, kontur kecil, lubang, sudut dalam, dan datum yang harus dipertahankan. Setelah itu program nesting dan jalur potong disiapkan dengan mempertimbangkan urutan fitur serta titik masuk-keluar. Jangan mengubah ukuran untuk “mengompensasi” burr sebelum ada hasil uji yang dapat diukur.

Saat sinar dan gas bantu bekerja, panas terlokalisasi mencairkan material di jalur potong dan aliran gas membantu mengeluarkan lelehan. Pada aluminium, pantulan dan konduktivitas panas membuat jendela proses lebih sensitif. [NEEDS TECHNICAL REVIEW: jenis sumber laser, panjang gelombang, daya, fokus, tekanan gas, dan kecepatan belum ditetapkan.] Karena itu, lembar parameter dari vendor hanya titik awal; kupon uji pada material aktual diperlukan sebelum bagian produksi.

Pemeriksaan dilakukan berlapis. Pertama, cek visual untuk burr, percikan, perubahan warna, dan tepi yang tidak seragam. Kedua, ukur dimensi kritis dan kerataan dengan alat serta metode yang disepakati. Ketiga, cocokkan hasil dengan gambar dan kriteria penerimaan. Jika komponen dilas atau diberi lapisan setelah dipotong, identitas material, consumable, coating, dan revisi dokumen perlu ditelusuri. ISO 3834-6 menekankan kebutuhan informasi dan pengelolaan mutu pengelasan; abstraknya tidak menggantikan prosedur proyek. ([ISO 3834-6:2024](https://www.iso.org/standard/83335.html))

## Faktor yang mengubah hasil

**Material dan permukaan.** Paduan, temper, ketebalan aktual, film pelindung, minyak, goresan, dan oksida dapat mengubah penyerapan energi serta aliran lelehan. Catat identitas lot atau sertifikat yang dipersyaratkan proyek. Jangan menyamakan dua lembar hanya karena sama-sama berlabel aluminium.

**Geometri.** Kontur panjang dan tipis lebih mudah kehilangan kerataan. Lubang kecil, sudut tajam, serta jarak fitur yang rapat meningkatkan kebutuhan kontrol urutan dan penjepitan. Toleransi harus menyebut datum dan cara ukurnya, bukan hanya “presisi”.

**Mesin dan program.** Kondisi lensa, fokus, nozzle, kebersihan meja, kalibrasi, dan kestabilan gas memengaruhi pengulangan. Catat versi program serta parameter yang dipakai pada kupon. Tanpa log itu, penyebab perubahan antar-batch sulit dipisahkan dari perubahan material.

**Lingkungan dan K3.** Pemotongan terkendali di bengkel memudahkan pembatasan area, ventilasi, pemadaman, dan akses pemeriksaan. Pemindahan pekerjaan ke lapangan mengubah akses, pasokan listrik, cuaca, paparan pekerjaan sekitar, dan rencana darurat. UU No. 1 Tahun 1970 dan Permenaker No. 5 Tahun 2018 menjadi rujukan umum keselamatan kerja; kontrol tugas spesifik tetap harus disetujui penanggung jawab K3. ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018))

## Contoh keputusan praktis

Gunakan matriks sederhana sebelum menerima pesanan:

| Kondisi yang sudah diketahui | Keputusan sementara | Bukti yang masih diminta |
|---|---|---|
| Gambar, paduan, tebal, dan toleransi jelas; ada kupon uji pada kombinasi sama | Lanjut ke peninjauan produksi | Rekaman inspeksi dan persetujuan revisi |
| Material jelas, tetapi belum ada data burr atau kerataan | Tahan produksi serial | Kupon uji, metode ukur, dan batas penerimaan |
| Gambar belum menetapkan fungsi tepi atau datum | Jangan mengunci harga/hasil | Klarifikasi desain dan kriteria penerimaan |
| Pekerjaan akan dipotong di area berpenghuni atau terbuka | Utamakan opsi bengkel terkendali | Rencana K3, isolasi area, energi, dan pemulihan |

Contohnya, pesanan panel tipis dengan banyak lubang mungkin tampak sederhana. Jika lubang harus menjadi datum perakitan, uji harus mengukur posisi lubang dan kerataan setelah pelepasan dari meja, bukan hanya melihat kilap tepi. Sebaliknya, bagian dekoratif dengan tepi yang akan ditutup mungkin memiliki kriteria berbeda—tetap harus ditulis dan disetujui. Sobat Bengkel-las.co.id, “bisa dipotong” dan “memenuhi fungsi” adalah dua keputusan yang berbeda. Teman Bengkel-las.co.id, pastikan keputusan itu tercatat sebelum lembar masuk produksi.

## Kesalahan umum dan cara memeriksanya

1. **Menganggap semua aluminium sama.** Tanyakan paduan, temper, tebal aktual, dan identitas lot; cocokkan dengan kupon.
2. **Mengejar kecepatan sebelum mutu.** Minta hasil uji yang menunjukkan dimensi, burr, dan kerataan pada kecepatan yang diusulkan.
3. **Mengamplas semua burr tanpa mencari sebab.** Periksa fokus, nozzle, gas, urutan, dan kebersihan. Finishing tambahan dapat mengubah ukuran tepi.
4. **Mengukur hanya saat masih terjepit.** Ukur kembali setelah bagian dilepas dan stabil; metode serta alat harus tercantum di rencana inspeksi.
5. **Menyebut sertifikat welder sebagai bukti potongan laser.** Kualifikasi prosedur, operator, pemeriksaan, dan penerimaan akhir adalah rekaman yang berbeda. ISO 5817, ISO 17635, dan ISO 9712 memberi kerangka berbeda untuk mutu dan pemeriksaan; abstrak publik tidak menyediakan batas cacat atau teknik yang boleh ditebak. ([ISO 5817:2023](https://www.iso.org/standard/80209.html), [ISO 17635:2025](https://www.iso.org/standard/85705.html), [ISO 9712:2021](https://www.iso.org/standard/75614.html))
6. **Membuang offcut tanpa identifikasi.** Pisahkan material dan kontaminan sesuai aturan setempat; rute limbah ditentukan oleh karakterisasi dan pihak berwenang, bukan asumsi bahwa semua sisa aluminium otomatis aman didaur ulang. ([PP No. 22 Tahun 2021](https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021))

## Jalan pintas yang perlu dihindari

Shortcut yang sering dipilih adalah memakai setelan dari pekerjaan aluminium sebelumnya karena “tebalnya mirip”. Itu dapat gagal ketika paduan, permukaan, geometri, atau kondisi nozzle berbeda. Alternatif yang lebih dapat dipertanggungjawabkan: keluarkan kupon dari material aktual, tetapkan fitur kritis dan metode ukur, lalu minta persetujuan atas parameter dan kriteria sebelum serial. Jika pekerjaan menyentuh instalasi berisiko atau area kerja berubah, hentikan asumsi bengkel dan lakukan tinjauan K3 tugas spesifik. Permenaker No. 11 Tahun 2026 perlu diperiksa terhadap status dan penerapannya pada konteks kerja Anda; jangan mengutip kewajiban yang belum diverifikasi. ([Permenaker No. 11 Tahun 2026](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026))

## Kesimpulan

Laser cutting aluminium layak dipertimbangkan bila kombinasi material–mesin–program dibuktikan melalui uji dan hasilnya memenuhi fungsi, burr, dimensi, serta kerataan yang disepakati. Reflektivitas, burr, dan distorsi bukan alasan otomatis untuk menolak, tetapi juga bukan masalah yang boleh ditutup dengan klaim “mesin sudah biasa”.

Langkah berikutnya: kirim gambar revisi, identitas paduan dan tebal, fitur kritis, kriteria tepi, serta kondisi pemasangan kepada operator dan penanggung jawab teknis. Minta kupon uji, rekaman inspeksi setelah dilepas dari meja, dan keputusan tertulis sebelum produksi serial. Jika bukti itu belum ada, tandai pekerjaan sebagai [NEEDS TECHNICAL REVIEW] dan jangan menjanjikan hasil akhir. Untuk menyiapkan pertanyaan lanjutan, Anda dapat kembali ke [beranda Bengkel-las.co.id](/).
