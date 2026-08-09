---
article_id: CUT-01-04
title: "Panduan Memilih Proses Cutting Berdasarkan Jenis Material"
slug: "memilih-proses-cutting-berdasarkan-material"
description: "Memilih proses yang sesuai berdasarkan bentuk, bahan, toleransi, volume, dan hasil tepi."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-07-31"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-01
primary_intent: "Memetakan material ke proses yang cocok"
reader_community: "Bengkel-las.co.id"
reader_address: "Teman Bengkel-las.co.id"
final_route: "/artikel/memilih-proses-cutting-berdasarkan-material.html"
technical_review: required
sources:
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://www.iso.org/standard/83335.html"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
  - "https://www.iso.org/standard/85705.html"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252"
---

# Panduan Memilih Proses Cutting Berdasarkan Jenis Material

Istilah *shear* berarti pemotongan dengan gaya geser, sedangkan *waterjet* memakai semburan air bertekanan; keduanya tetap harus diuji pada material aktual.

Halo, Teman Bengkel-las.co.id! Jangan memilih proses cutting hanya karena mesin yang sedang kosong atau karena namanya terdengar paling cepat. Keputusan awal yang lebih dapat dipertanggungjawabkan dimulai dari material, bentuk, ketebalan, toleransi, jumlah komponen, dan mutu tepi yang dibutuhkan.

Secara praktis, lembaran tipis dengan kontur sederhana sering cukup diproses dengan shear atau gergaji; pelat baja yang lebih tebal dan perlu kontur fleksibel dapat mengarah ke plasma atau oxy-fuel; material nonkonduktif, komposit, atau permukaan yang sensitif panas dapat memerlukan waterjet; sedangkan detail dua dimensi yang presisi biasanya dipertimbangkan untuk laser. Itu baru penyaringan awal. Kondisi permukaan, zona terpengaruh panas, distorsi, akses penjepitan, kapasitas mesin, dan dokumen proyek dapat mengubah pilihan. [NEEDS PROJECT REVIEW: material, ketebalan, toleransi, dan kriteria tepi belum ditetapkan.]

![Ilustrasi memilih jasa bengkel las](/wp-content/uploads/2020/02/memilih-jasa-bengkel-las.jpg)

*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*
Gambar ini adalah aset lokal, bukan dokumentasi proyek tertentu. Buka aset media lokal bila perlu memeriksa berkas yang dirujuk.

## Hasil akhir dan prasyarat

Hasil yang ingin dicapai bukan sekadar potongan yang terpisah, melainkan komponen yang identitas materialnya jelas, dimensinya dapat diperiksa, tepinya sesuai fungsi, dan siap masuk ke tahap berikutnya tanpa kejutan. Orang yang berwenang menyetujui pilihan proses harus ditentukan sejak awal: bisa penanggung jawab desain, pengawas fabrikasi, atau pihak K3 untuk kondisi kerja tertentu. Operator menjalankan proses sesuai prosedur yang disetujui, bukan menetapkan sendiri persyaratan desain.

Sediakan gambar kerja dengan datum dan toleransi, daftar material atau sertifikat yang relevan, ukuran dan jumlah, bentuk kontur, kebutuhan permukaan, urutan proses setelah cutting, serta batasan lokasi kerja. Paket fabrikasi yang terkendali lazimnya juga menghubungkan fungsi, antarmuka, urutan fabrikasi, inspeksi, titik tahan (hold point), dasar penerimaan, dan penyimpangan yang disetujui. Rujukan katalog BSN untuk SNI 1729:2020 dan abstrak ISO 3834-6:2024 membantu mengingatkan bahwa persyaratan harus diturunkan dari dokumen pengendali yang berlaku, bukan dari kebiasaan lisan ([BSN](https://pesta.bsn.go.id/produk/detail/12882-sni17292020); [ISO 3834-6:2024](https://www.iso.org/standard/83335.html)).

## Langkah 1 — tetapkan cakupan

Tuliskan apa yang dipotong dan apa yang tidak. Apakah pekerjaan hanya membuat blank dari pelat, atau termasuk bevel, marking, pengeboran, deburring, dan pemeriksaan? Tetapkan antarmuka: sisi mana menjadi datum, bagian mana akan dilas, dan apakah tepi hasil cutting akan menerima beban, seal, atau lapisan pelindung.

Buat matriks singkat sebelum meminta penawaran:

| Pertanyaan | Dampak pada pilihan |
|---|---|
| Material konduktif atau tidak? | Menyaring proses berbasis busur/listrik dan membuka opsi mekanis atau waterjet. |
| Tebal dan ukuran pelat berapa? | Menentukan rentang kapasitas, risiko panas, dan kebutuhan penyangga. |
| Kontur lurus, lubang, atau bentuk bebas? | Membedakan shear/gergaji dari proses CNC atau jet. |
| Toleransi dan mutu tepi apa yang diminta? | Menentukan apakah perlu finishing, kompensasi kerf, atau inspeksi tambahan. |
| Satu komponen atau berulang? | Memengaruhi waktu setup, nesting, dan konsistensi antar-potongan. |

Jangan memasukkan material berlapis, cat lama, galvanis, atau benda yang pernah berisi bahan ke jalur panas tanpa penilaian bahaya dan ventilasi. Undang-Undang Keselamatan Kerja dan aturan K3 kerja panas menjadi dasar untuk menilai lingkungan aktual; keduanya tidak memberi izin otomatis untuk setiap situasi ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970); [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018)).

## Langkah 2 — kumpulkan dan cocokkan bukti

Mulai dari identitas material, bukan warna atau nama dagang. Cocokkan grade atau designation, ukuran aktual, kondisi permukaan, dan sertifikat bila dipersyaratkan. Untuk aluminium, stainless, baja karbon, atau material nonlogam, pertanyaan utamanya tetap sama: apakah proses merusak sifat yang dibutuhkan, meninggalkan kontaminasi, atau membuat tepi tidak cocok dengan sambungan berikutnya?

Bandingkan proses dengan lima sumbu berikut.

1. **Metode mekanis (shear, gergaji, milling).** Tepat ketika geometri sederhana, kerf perlu terkendali, dan panas harus diminimalkan. Periksa burr, tegak lurus, radius minimum, serta kemampuan menjepit benda kerja.
2. **Laser.** Menarik untuk kontur detail dan pengulangan pada material yang sesuai dengan sumber laser dan rentang tebal mesin. Tetapkan toleransi, gas proses, kondisi permukaan, serta batas perubahan warna atau dross melalui prosedur; jangan menganggap semua grade dan ketebalan akan berperilaku sama.
3. **Plasma.** Berguna untuk pelat konduktif dan kontur yang lebih tebal, tetapi sisi potong, bevel, dross, dan zona panas perlu dibandingkan dengan kebutuhan sambungan. Hasil akhir harus dibuktikan melalui kupon atau pemeriksaan yang disepakati, bukan foto katalog.
4. **Oxy-fuel.** Dapat dipertimbangkan untuk baja karbon tebal dengan bentuk relatif sederhana. Panas dan perubahan bentuk menjadi faktor utama; material nonferrous atau kombinasi lapisan memerlukan verifikasi khusus.
5. **Waterjet.** Tidak menambahkan zona panas seperti proses termal dan dapat membantu material yang sensitif panas atau tidak konduktif. Namun, waktu proses, abrasif, penyangga, pengeringan, dan pengelolaan limbah harus masuk perhitungan.

Data produk habis pakai juga perlu ditelusuri: identitas batch, klasifikasi consumable, kondisi penyimpanan, dan produk pelapis bila ada. Label generik tidak cukup untuk menyimpulkan kompatibilitas, masa simpan, atau parameter proses. Abstrak ISO 3834-6:2024 menekankan kerangka mutu, sedangkan detail produk tetap harus diverifikasi dari lembar data dan dokumen proyek ([ISO 3834-6:2024](https://www.iso.org/standard/83335.html)).

## Langkah 3 — jalankan urutan kerja

Urutan konseptual yang aman adalah: verifikasi dokumen, identifikasi dan ukur material, pilih proses kandidat, uji atau tinjau contoh, kunci program dan setup, lakukan cutting, lalu periksa hasil sebelum dipindahkan ke proses berikutnya.

Pada tahap kandidat, minta pemasok menjelaskan bukan hanya harga per meter, tetapi juga asumsi tebal, toleransi, allowance finishing, cara menahan pelat, dan siapa yang menerima hasil. Untuk batch, simpan revisi program dan identitas material agar potongan dapat ditelusuri. Jika proses panas dipakai di lapangan, lingkungan dapat mengubah akses, fume dispersion, listrik, cuaca, benda mudah terbakar, dan akses inspeksi; pemindahan kerja ke lokasi bukan alasan tunggal untuk mengabaikan kontrol ([OSHA 29 CFR 1910.252](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252)). Persyaratan Indonesia dan izin lokasi tetap menjadi acuan utama.

Setelah cutting, hilangkan burr atau dross hanya sejauh yang diizinkan gambar kerja. Jangan menggerinda sampai datum berubah. Tandai komponen, arah material bila relevan, dan status pemeriksaan. Jika tepi akan dilas, pastikan persiapan sambungan mengikuti prosedur pengelasan yang berlaku, bukan improvisasi operator.

## Titik tahan dan kondisi berhenti

Teman Bengkel-las.co.id, hentikan pekerjaan dan minta review ketika salah satu hal berikut terjadi: grade material tidak cocok dengan dokumen; ketebalan di luar asumsi program; toleransi tidak tercantum; tepi menunjukkan retak, delaminasi, dross berlebih, atau distorsi; material memiliki lapisan atau kontaminasi tak dikenal; atau mesin, alat ukur, dan prosedur tidak berstatus layak.

Hold point juga diperlukan sebelum memotong batch penuh jika contoh pertama belum diterima. Minta persetujuan tertulis untuk perubahan proses, substitusi material, perubahan allowance, atau penggunaan pekerjaan lapangan. [NEEDS PROJECT REVIEW: acceptance level, extent inspeksi, dan otorisasi deviasi harus berasal dari dokumen proyek yang berlaku.]

## Verifikasi hasil dan serah terima

Gunakan lembar pemeriksaan yang mengikat setiap potongan pada nomor gambar, revisi, material, tebal, program atau work order, operator, tanggal, dan hasil ukur. Periksa dimensi kritis dari datum yang benar, posisi lubang atau kontur, kondisi tepi, tanda identifikasi, serta kebutuhan pembersihan atau pelapisan.

Inspeksi visual atau satu pengukuran tidak otomatis membuktikan seluruh mutu. Metode, cakupan, teknik, kondisi permukaan, personel, status verifikasi alat, laporan, dan dasar penerimaan adalah item terpisah. ISO 17635:2025 menjelaskan bahwa tingkat penerimaan NDT tidak dapat diterjemahkan satu banding satu menjadi tingkat mutu pengelasan; karena itu, rujuk prosedur dan standar lengkap yang ditetapkan proyek ([ISO 17635:2025](https://www.iso.org/standard/85705.html)).

Handover minimal berisi daftar komponen diterima atau ditahan, laporan ketidaksesuaian, keputusan disposition, sisa pekerjaan, dan pihak yang memberi release. Jika hasil akan menjadi bagian struktur atau mesin, persetujuan teknis akhir tetap berada pada pihak yang berwenang.

## Jalan pintas yang sering gagal

Jalan pintas yang umum adalah menyamakan semua pelat dengan “potong plasma saja” karena proses itu tersedia dan tampak cepat. Cara ini bisa gagal ketika tepi harus menjadi datum presisi, material tidak cocok untuk panas, distorsi mengganggu fit-up, atau jumlah sedikit tidak sebanding dengan waktu setup.

Alternatif yang lebih andal adalah meminta dua atau tiga kandidat proses dibandingkan pada benda dan kriteria yang sama. Minta contoh kecil atau rencana uji, lalu nilai biaya total: setup, material terbuang, finishing, inspeksi, dan risiko rework. Kawan Bengkel-las.co.id, keputusan yang murah di meja pemesanan dapat menjadi mahal setelah tepi harus diperbaiki atau komponen tidak lagi pas.

## Kesimpulan dan langkah berikutnya

Pilih proses cutting dengan memetakan material dan ketebalan ke bentuk, toleransi, volume, hasil tepi, panas yang dapat diterima, serta kemampuan inspeksi. Shear atau gergaji cocok untuk bentuk sederhana ketika panas dan detail bukan kendala; laser, plasma, oxy-fuel, atau waterjet dipilih setelah kecocokan material dan kriteria penerimaan dibuktikan.

Langkah Anda sekarang: isi matriks material–geometri–toleransi–volume–tepi, lampirkan gambar kerja dan identitas material, lalu minta penanggung jawab teknis menyetujui proses kandidat serta contoh pertama. Bila perlu mengirim permintaan kerja, gunakan [jalur kontak di situs Bengkel-las.co.id](/). Jangan memulai batch atau kerja panas sebelum [NEEDS PROJECT REVIEW: prosedur K3, acceptance basis, dan otorisasi deviasi] tersedia. Aturan operasinya sederhana: proses yang tepat adalah proses yang memenuhi fungsi dan bukti penerimaan kasus Anda, bukan proses yang sekadar paling mudah diakses.

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
