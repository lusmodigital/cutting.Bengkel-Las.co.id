---
article_id: CUT-09-02
title: "Common-Line Cutting: Manfaat dan Risiko Berbagi Garis Potong"
slug: "common-line-cutting"
description: "Menata komponen agar pemakaian material, waktu potong, dan sisa bahan lebih efisien."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2026-01-25"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-09
primary_intent: "Menilai penggunaan garis potong bersama"
reader_community: "Bengkel-las.co.id"
reader_address: "Kawan Bengkel-las.co.id"
final_route: "/artikel/common-line-cutting.html"
technical_review: required
sources:
  - "https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999.8Presiden"
  - "https://www.iso.org/standard/83335.html"
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
  - "https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021"
---

# Common-Line Cutting: Manfaat dan Risiko Berbagi Garis Potong

Halo, Kawan Bengkel-las.co.id! Common-line cutting berarti dua komponen berbagi satu segmen garis potong. Strategi ini dapat mengurangi lintasan alat, waktu proses, dan sisa tepi—tetapi hanya bila kedua sisi memang boleh dipisahkan oleh satu potongan yang sama. Ia bukan tombol otomatis untuk membuat semua layout lebih murah.

Jawaban praktisnya: gunakan berbagi garis pada komponen dengan material, ketebalan, orientasi, dan kebutuhan mutu yang kompatibel, setelah gambar produksi serta urutan pemotongan ditinjau. Jika identitas sisi, toleransi, akses pemeriksaan, atau risiko deformasi belum jelas, pakai garis terpisah. Keputusan final memerlukan dokumen proyek aktual; nilai kerf (lebar material yang hilang akibat potong), toleransi, dan penerimaan tidak tersedia dalam paket ini sehingga perlu **[NEEDS PROJECT REVIEW: material, mesin, kerf, toleransi, dan acceptance basis]**.

<!-- BEGIN MANAGED IMAGE PLAN
**Image ID:** `LOCAL-005`
**Placement:** after opening answer, before first detailed section.
**Exact Markdown to insert:** `![Ilustrasi bengkel las](/wp-content/uploads/2019/10/bengkel-las.png)`
**Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
**Selection basis:** filename/source metadata only; do not infer visual details, ownership, location, people, brands, condition, performance, or outcome.
END MANAGED IMAGE PLAN -->

![Ilustrasi bengkel las](/wp-content/uploads/2019/10/bengkel-las.png)

Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.

## Jawaban singkat dan salah paham utama

Manfaat utama common-line cutting adalah satu jalur dapat melayani tepi dua part. Secara logika geometri, lintasan dan lebar bidang yang terbuang bisa berkurang. Namun penghematan itu tidak sama dengan jaminan hasil: satu kesalahan pada garis bersama dapat memengaruhi dua komponen sekaligus, mempersulit pelacakan identitas, atau menyisakan tepi yang tidak sesuai fungsi.

Salah paham yang sering muncul adalah menganggap garis yang berimpit di layar pasti aman dipotong sekali. Yang perlu dibuktikan bukan hanya posisi, melainkan juga apakah kedua part punya datum, arah, material, finishing, dan kelas mutu yang sama. Standar seperti ISO 3834-6 memberi kerangka mutu pengelasan dan fabrikasi, tetapi abstrak standar tidak membuktikan bahwa layout tertentu telah memenuhi persyaratan proyek ([ISO 3834-6:2024](https://www.iso.org/standard/83335.html)).

Kawan Bengkel-las.co.id, perlakukan garis bersama sebagai keputusan yang harus dapat diaudit: siapa yang menyetujui, revisi gambar mana yang dipakai, dan pemeriksaan apa yang dilakukan setelah part dipisahkan.

## Definisi dan batas objek

Dalam artikel ini, garis bersama adalah segmen batas dua komponen yang sengaja dilewati satu kali oleh alat potong. Fokusnya adalah strategi berbagi garis, bukan pengaturan jarak antarpart, margin tepi, atau nesting secara umum. Jarak aman, lead-in/lead-out, dan margin harus tetap ditentukan dalam aturan proses serta gambar yang berlaku.

Common-line juga berbeda dari sekadar menempelkan dua bentuk pada perangkat lunak. Pada garis bersama, sistem CAM harus memahami apakah segmen itu satu entitas pemotongan atau dua lintasan yang kebetulan berimpit. Simulasi jalur, urutan pemotongan, dan cara part ditahan menentukan apakah geometri tetap stabil.

Dokumen fabrikasi yang terkendali semestinya mengikat revisi gambar, fungsi, datum, identitas material dan sambungan, toleransi, urutan kerja, titik inspeksi, serta dasar penerimaan. Katalog BSN untuk SNI 1729:2020 hanya menunjukkan identitas dan ruang lingkup dokumen, bukan isi klausul atau toleransi; gunakan standar berlisensi dan dokumen proyek yang diterbitkan untuk bekerja ([katalog SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020)).

## Cara kerjanya

Urutan yang dapat dipakai sebagai kerangka kerja adalah sebagai berikut.

1. **Kelompokkan kandidat.** Tandai part yang berbagi material, ketebalan, fungsi tepi, dan arah finishing. Jangan menggabungkan part berbeda hanya karena bentuknya bersentuhan.
2. **Tetapkan geometri.** Pilih segmen yang benar-benar menjadi batas kedua part. Tandai datum dan sisi yang harus dipertahankan agar operator tidak menukar orientasi.
3. **Tentukan aturan proses.** Masukkan kompensasi kerf, lead-in, lead-out, urutan, penahanan lembaran, dan rencana pemisahan. Nilai numeriknya harus berasal dari mesin, material, dan prosedur yang disetujui—**[NEEDS MACHINE/PROCESS REVIEW]**.
4. **Simulasikan dan beri identitas.** Periksa lintasan tanpa tabrakan, sisa jembatan, kemungkinan part bergeser, serta penandaan atau nesting yang menjaga identitas setelah dipotong.
5. **Tinjau sebelum rilis.** Pembuat layout, pemeriksa, dan penanggung jawab teknis membandingkan file dengan gambar revisi yang berlaku. ISO 3834-6 dapat menjadi rujukan kerangka mutu, bukan bukti otomatis bahwa operator, mesin, atau hasil tertentu telah memenuhi proyek.
6. **Periksa hasil.** Ukur titik kendali yang ditetapkan, cek tepi, identifikasi part, dan catat penyimpangan sebelum finishing atau pengelasan. Jika hasil tidak sesuai, tahan dua part yang terhubung oleh garis yang sama sampai penyebabnya jelas.

## Faktor yang mengubah hasil

**Material dan proses.** Perbedaan grade, ketebalan, lapisan, atau respons panas dapat membuat satu parameter tidak cocok untuk dua part. Jangan menyimpulkan kompatibilitas dari label umum; catat material, batch bila diwajibkan, dan dokumen pemasok dalam paket pekerjaan.

**Fungsi tepi.** Tepi yang akan dilas, dibaut, disegel, atau terlihat memiliki tuntutan berbeda. Garis bersama yang menghemat lintasan bisa menghilangkan allowance yang dibutuhkan untuk persiapan sambungan. Dasar desain dan penerimaan harus disepakati sebelum rilis—**[NEEDS DESIGN/ACCEPTANCE REVIEW]**.

**Kekakuan dan penahanan.** Saat satu segmen dipotong, bagian yang tersisa dapat bergerak atau terpuntir. Risiko meningkat bila part panjang, tipis, atau memiliki banyak kontur. Rencana penahanan, urutan, dan titik angkat harus mengikuti kondisi mesin dan lembaran aktual.

**Inspeksi dan keterlacakan.** Dua part yang lahir dari satu garis harus tetap dapat ditelusuri ke gambar, revisi, material, operator, dan catatan pemeriksaan. Klaim “bersertifikat” tidak cukup untuk membuktikan kemampuan vendor atau hasil proyek tertentu; bukti harus cocok dengan metode dan ruang lingkupnya.

**Keselamatan dan lingkungan kerja.** Pemotongan adalah pekerjaan dengan energi, panas, asap, dan potensi serpihan. UU No. 1 Tahun 1970 dan Permenaker No. 5 Tahun 2018 menjadi rujukan umum keselamatan kerja, tetapi kontrol tugas spesifik tetap harus ditetapkan berdasarkan mesin, bahan, ventilasi, akses, dan penilaian K3 setempat ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018)). Jangan mengimpor jarak, durasi, atau pilihan APD dari aturan asing tanpa review Indonesia.

**Sisa dan limbah.** Potongan yang lebih kecil belum otomatis berarti manfaat lingkungan. Identitas, kontaminasi, penyimpanan, pengangkutan, dan penerima berwenang menentukan rute limbah menurut PP No. 22 Tahun 2021. Karena itu, pisahkan sisa berdasarkan karakter yang benar-benar diketahui dan jangan mengklaim dapat didaur ulang tanpa bukti karakterisasi serta jalur lokal ([PP No. 22 Tahun 2021](https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021)).

## Contoh keputusan praktis

Bayangkan dua bracket identik pada satu lembar yang memiliki segmen lurus berimpit. **Asumsi contoh:** material dan ketebalan sama, gambar menyetujui tepi bersama, mesin mendukung urutan tersebut, dan pemeriksa dapat mengukur kedua part. Dalam kondisi itu, ajukan satu garis bersama untuk ditinjau. Simpan simulasi, tunjukkan cara part ditahan, dan tetapkan titik ukur setelah pemisahan.

Sebaliknya, bila satu part menjadi komponen struktural dan yang lain hanya penutup, atau keduanya memerlukan finishing berbeda, perlakukan sebagai kandidat berisiko. Jika gambar tidak menjelaskan allowance, toleransi, atau cara menerima tepi, jangan mengoptimalkan lintasan terlebih dahulu. Minta dasar desain dan acceptance basis tertulis—**[NEEDS PROJECT DOCUMENT REVIEW]**.

Gunakan tabel keputusan singkat ini:

| Pertanyaan | Ya | Tidak |
|---|---|---|
| Material, ketebalan, dan arah proses kompatibel? | Lanjut ke tinjauan geometri | Garis terpisah |
| Segmen bersama diizinkan gambar dan fungsi tepi? | Lanjut simulasi | Hentikan optimasi |
| Kerf, penahanan, dan urutan telah dibuktikan pada proses ini? | Rilis untuk pemeriksaan | **[NEEDS PROCESS REVIEW]** |
| Identitas dan titik ukur kedua part jelas setelah dipisahkan? | Catat dalam inspeksi | Jangan gunakan common-line |

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah mengejar persentase penghematan tanpa membandingkan waktu inspeksi, pemisahan, deburring, dan potensi rework. Minta penawaran atau rencana kerja yang memisahkan ruang lingkup survei, desain, material, consumable, transport, pengujian, rework, pajak, dan dokumentasi. Total harga saja tidak membuat dua ruang lingkup menjadi sebanding; perubahan juga perlu alasan, dampak waktu/biaya, persetujuan, dan riwayat revisi ([UU No. 8 Tahun 1999](https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999.8Presiden)).

Kesalahan kedua adalah menghapus garis ganda secara manual di file tanpa simulasi. Periksa apakah CAM memotong segmen itu sekali, apakah lead-in masuk ke area yang benar, dan apakah sisa jembatan menahan part sampai urutan selesai. Catat versi file dan checksum atau mekanisme pengendalian revisi yang dipakai organisasi.

Kesalahan ketiga adalah menganggap hasil visual sudah cukup. Tepi perlu dibandingkan dengan toleransi dan fungsi, bukan hanya tampak rapi. Bila ada cacat atau ukuran meragukan, hentikan proses lanjutan dan minta pemeriksa yang kompeten; jangan menutupinya dengan penggerindaan yang mengubah bukti.

## Jalan pintas yang perlu dihindari

Shortcut yang menarik adalah “satukan semua garis yang berimpit agar waktu potong pasti turun.” Cara ini gagal ketika satu garis memiliki dua tuntutan tepi berbeda atau part kehilangan penahanan. Efeknya bisa berupa dua komponen salah sekaligus dan sulit dipisahkan dari sumber penyebabnya.

Alternatif yang lebih andal adalah optimasi bertahap: pilih satu kandidat berisiko rendah, dokumentasikan asumsi, simulasikan, potong dengan kontrol yang berlaku, lalu evaluasi hasil sebelum memperluas aturan. Sobat Bengkel-las.co.id, bila common-line menyentuh struktur, tekanan, pengangkatan, atau keselamatan, minta persetujuan desain dan K3 yang berwenang sebelum produksi.

## Langkah penutup

Common-line cutting bermanfaat bila geometri, material, proses, penahanan, dan acceptance basis memang kompatibel; risikonya meningkat ketika penghematan lintasan mengalahkan keterlacakan dan pemeriksaan. Jadi, jangan menilai dari jumlah garis yang hilang saja. Untuk konteks pekerjaan lain, mulai dari [beranda Bengkel-las.co.id](/) atau [indeks artikel](/index.html).

Langkah berikutnya: siapkan gambar revisi, daftar material, simulasi lintasan, rencana penahanan, titik ukur, serta catatan siapa yang menyetujui. Minta tinjauan proyek untuk **[NEEDS PROJECT REVIEW: kerf, toleransi, desain, K3, dan penerimaan]** sebelum file dilepas ke mesin. Aturan operasinya sederhana: satu garis boleh dipakai bersama hanya jika kedua part tetap dapat diproduksi, diperiksa, dan ditelusuri secara terpisah.
