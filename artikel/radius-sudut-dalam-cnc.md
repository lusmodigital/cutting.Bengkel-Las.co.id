---
article_id: CUT-08-05
title: "Radius Sudut Dalam pada CNC Router dan CNC Milling"
slug: "radius-sudut-dalam-cnc"
description: "Menulis target dimensi dan toleransi yang realistis serta mengantisipasi kerf dan kompensasi."
status: draft
publication_date: "2026-01-14"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-08
primary_intent: "Mendesain sudut yang dapat dikerjakan tool"
reader_community: "Bengkel-las.co.id"
reader_address: "Kawan Bengkel-las.co.id"
final_route: "/artikel/radius-sudut-dalam-cnc.html"
technical_review: required
writing_contract_version: "native-id-v2"
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

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** `LOCAL-003`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi CNC Milling 4](/wp-content/uploads/2019/11/CNC-Milling-4.jpg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `CNC Milling 4` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-003]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

# Radius Sudut Dalam pada CNC Router dan CNC Milling

Halo, Kawan Bengkel-las.co.id! Sudut dalam pada hasil CNC hampir selalu memiliki radius karena mata potong berbentuk bulat. Jika gambar meminta sudut siku-siku tanpa ruang alat, operator harus memilih kompromi, alat lebih kecil, lintasan tambahan, atau mengubah desain. Menulis radius sejak awal mencegah revisi dan biaya kejutan.

Jawaban singkatnya: tentukan radius minimum berdasarkan diameter alat yang benar-benar tersedia, sisakan ruang untuk penjepitan dan lintasan, lalu nyatakan radius sebagai dimensi fungsi atau detail yang harus diperiksa. Router dan milling memiliki batas berbeda; angka nominal pada katalog tidak membuktikan hasil part Anda. Kupon dan pemeriksaan tetap diperlukan.

![Ilustrasi CNC Milling 4](/wp-content/uploads/2019/11/CNC-Milling-4.jpg)

*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*


## Definisi dan batas objek

Radius sudut dalam adalah lengkungan pada pertemuan dua sisi di dalam kontur. Mata potong dengan diameter tertentu tidak dapat masuk ke sudut yang lebih tajam daripada kelengkungannya. Istilah radius alat, radius hasil, dan radius yang ditulis pada gambar harus dibedakan. Chamfer (serongan tepi) atau relief (cekungan pelepas) adalah solusi desain berbeda, bukan radius yang sama.

Halaman ini membahas keterbatasan alat bulat pada lembar atau blok yang dikerjakan router dan milling. Ia tidak menetapkan toleransi universal, kekuatan komponen, atau penerimaan proyek. Untuk fitur keselamatan, sambungan beban, atau geometri kritis, minta peninjauan desain dan data mesin.

## Cara kerjanya

Router atau milling menggerakkan mata potong mengikuti lintasan. Diameter alat, jumlah flute (alur pemotong), kedalaman lintasan, kekakuan mesin, material, penjepitan, dan strategi gerak memengaruhi sudut. Alat lebih kecil dapat membuat radius lebih kecil, tetapi mungkin membutuhkan lintasan lebih banyak dan lebih sensitif terhadap getaran atau patah.

Tulis radius pada gambar dan tunjukkan lokasi ukur. Jika sudut tidak kritis, gunakan catatan “radius mengikuti alat” hanya setelah pemilik desain menyetujui batasnya. Jika sudut harus menerima pasak atau sisipan, beri ukuran antarmuka, kedalaman, dan cara pemeriksaan, bukan sekadar “siku”.

## Faktor yang mengubah hasil

Material keras, lembar tipis, dan penjepitan lemah dapat membuat alat bergetar sehingga radius atau dinding berubah. Tool aus dapat memperbesar ukuran atau meninggalkan jejak. Pendinginan, pembuangan serpihan, dan urutan roughing (pengerjaan awal) serta finishing juga memengaruhi permukaan. Parameter tidak boleh disalin dari bahan lain.

Kawan Bengkel-las.co.id, bedakan ukuran nominal dengan hasil aktual. Buat kupon yang memuat radius terkecil, lubang, dan dinding tipis; ukur setelah proses. Catat alat, kondisi, material, dan revisi agar hasil dapat ditelusuri. Kerangka dokumen fabrikasi seperti [SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020) dan [ISO 3834-6:2024](https://www.iso.org/standard/83335.html) mendukung keterlacakan pada lingkupnya, tetapi tidak menentukan radius mesin Anda.

## Contoh keputusan praktis

Jika komponen menerima sudut luar pasangan tetapi sudut dalam hanya memberi ruang, radius moderat biasanya cukup dan lebih mudah diproduksi. Jika sisipan harus duduk rapat di empat sudut, pertimbangkan relief kecil pada sudut atau desain sisipan yang menerima radius. Jangan menambahkan relief tanpa memeriksa kebersihan, kekuatan, dan fungsi pemasangan.

Pertimbangkan juga arah beban dan cara alat mencapai sudut. Radius yang lebih besar dapat mengurangi konsentrasi perubahan arah, tetapi bisa mengganggu dudukan atau jalur kabel. Tandai sudut yang benar-benar fungsional dan sudut yang sekadar kosmetik agar waktu pemrograman dan pemeriksaan dipakai pada tempat yang tepat.

Untuk pocket dangkal, gunakan alat yang dapat mencapai dasar tanpa menyentuh penjepit. Untuk pocket dalam, periksa rasio panjang alat terhadap diameter dan minta review operator. Angka kedalaman, kecepatan, atau toleransi harus berasal dari datasheet alat, prosedur, dan uji, bukan dari artikel umum.

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah menggambar sudut siku-siku lalu berharap mata potong menghapus material ekstra. Kedua, memilih alat kecil tanpa memperhitungkan kekakuan dan waktu. Ketiga, memeriksa panjang dan lebar tetapi tidak memeriksa radius dengan pengukur yang sesuai. Keempat, menganggap semua sudut hasil satu batch identik walau alat atau material berubah.

Perbaiki dengan daftar: diameter alat dan kondisi, radius target, fitur pasangan, material dan batch, metode ukur, serta status kupon. Jika hasil kupon gagal, tahan produksi dan naikkan revisi atau ubah geometri. Jangan menutup masalah dengan dempul atau coating sebelum dimensi dasar diterima.

## Bukti, keselamatan, dan batas standar

Dokumen inspeksi memisahkan metode, cakupan, alat, kondisi permukaan, personel, laporan, dan dasar penerimaan. [ISO 17635:2025](https://www.iso.org/standard/85705.html) dan [ISO 9712:2021](https://www.iso.org/standard/75614.html) membahas aspek pengujian serta kompetensi pada ruang lingkupnya; [ISO 5817:2023](https://www.iso.org/standard/80209.html) berkaitan dengan mutu sambungan, bukan penerimaan radius CNC.

SDS membantu memahami bahan dan cairan; [OSHA 1910.1200](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200) adalah contoh asing. Finishing pelindung memiliki ruang lingkup sendiri; [ISO 12944-5:2019](https://www.iso.org/standard/77795.html) tidak menjamin kecocokan coating pada semua material CNC. Untuk pekerjaan panas dan area mesin, terapkan [UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018), [Permenaker No. 11 Tahun 2026](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026), dan [Permenaker No. 12 Tahun 2015](https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015) bersama K3 setempat. [OSHA 1910.252](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252) hanya contoh pekerjaan panas dari Amerika.

Sisa serpihan dan cairan perlu diidentifikasi sebelum disimpan atau disalurkan. [PP No. 22 Tahun 2021](https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021) tidak membuktikan semua scrap aman dicampur. Simpan catatan material, kontaminasi, dan penerima yang berwenang.

## Titik tahan dan pemeriksaan

Tahan pekerjaan bila radius pada gambar bertentangan dengan model, alat tidak tersedia, penjepitan menghalangi lintasan, atau pemilik desain belum menentukan fungsi sudut. Hentikan mesin jika serpihan tidak terhisap, alat bergetar, atau pelindung terbuka. Jangan mengubah urutan servis atau membuka pelindung tanpa prosedur kompeten; standar asing seperti OSHA 1910.147 dan 1910.212 tidak boleh disalin sebagai instruksi lokal tanpa tinjauan.

Serah-terima memuat file revisi, daftar radius kritis, alat yang dipakai, hasil kupon, ukuran aktual, item terbuka, dan nama pemeriksa. Simpan sampel jika hasil perlu dibandingkan pada batch berikutnya. Teman Bengkel-las.co.id, minta penerima menandatangani status yang sama dengan yang dilihat operator. Tambahkan sketsa lokasi radius pada PDF agar pemeriksa tidak keliru memilih sudut. Bila part memiliki pasangan kiri dan kanan, catat orientasi serta nomor pasangan. Perubahan alat, batch, atau cara penjepitan harus dicatat sebagai kondisi baru, bukan disamakan dengan hasil lama.

## Penutup dan langkah berikutnya

Radius sudut dalam harus dirancang bersama alat, material, penjepitan, dan fungsi part. Langkah berikutnya: tandai semua sudut kritis, minta penyedia mengonfirmasi alat yang tersedia, buat kupon, ukur hasil, lalu bekukan revisi setelah persetujuan. Jika dasar penerimaan atau kemampuan alat belum jelas, tahan produksi dan minta review teknis.

Aturan operasinya: jangan menjanjikan sudut siku-siku dari alat bulat tanpa relief, alat khusus, atau bukti uji. Gunakan [beranda Bengkel-las.co.id](/) untuk informasi umum; rute artikel saudara yang masih direncanakan belum menjadi tautan publik.
