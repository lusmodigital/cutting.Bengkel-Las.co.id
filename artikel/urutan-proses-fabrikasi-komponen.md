---
article_id: CUT-13-06
title: "Menentukan Urutan Cutting, Machining, Marking, dan Assembly"
slug: "urutan-proses-fabrikasi-komponen"
description: "Merencanakan deburring, bending, welding, coating, perakitan, dan urutan kerja setelah cutting."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2026-05-15"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-13
primary_intent: "Menyusun routing proses komponen"
reader_community: "Bengkel-las.co.id"
reader_address: "Teman Bengkel-las.co.id"
final_route: "/artikel/urutan-proses-fabrikasi-komponen.html"
technical_review: required
sources:
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://www.iso.org/standard/83335.html"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200"
  - "https://www.iso.org/standard/51792.html"
  - "https://www.iso.org/standard/54936.html"
  - "https://www.iso.org/standard/80209.html"
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
---

Halo, Teman Bengkel-las.co.id! Urutan proses komponen tidak sebaiknya mengikuti kebiasaan “potong dulu, nanti dipikirkan”. Routing (rute proses) yang aman dimulai dari datum (acuan geometri) dan fungsi, lalu menetapkan proses yang mengubah bentuk paling besar sebelum proses yang membutuhkan referensi presisi. Pola umumnya adalah: review dokumen dan material, cutting, deburring, bending atau forming, machining, marking yang tidak mengganggu area kerja, fit-up dan welding, pemeriksaan, coating, lalu assembly dan pemeriksaan akhir.

Urutan itu dapat berubah bila gambar mensyaratkan datum lain, sambungan perlu akses dari sisi tertentu, coating harus dilakukan sebelum perakitan, atau komponen terlalu besar untuk dikendalikan di bengkel. Jadi, sebelum melepas material, bekukan gambar revisi, material, toleransi, antarmuka, serta titik inspeksi. Paket fabrikasi yang terkendali memang perlu memuat dimensi, datum, material, sambungan, toleransi, urutan, inspeksi, dan dasar penerimaan; katalog BSN hanya mengonfirmasi identitas standar, bukan isi klausulnya ([SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020), [ISO 3834-6:2024](https://www.iso.org/standard/83335.html)).

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

![Ilustrasi bengkel las](/wp-content/uploads/2019/10/bengkel-las.png)

*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*


# Menentukan Urutan Cutting, Machining, Marking, dan Assembly

## Definisi dan batas objek

Artikel ini membahas routing satu komponen atau satu rakitan: perpindahan dari bahan mentah sampai siap dipasang. “Cutting” memisahkan blank; “machining” membentuk atau memperbaiki fitur dengan acuan; “marking” memberi identitas atau orientasi; “assembly” menggabungkan komponen. Deburring, bending, welding, coating, dan pemeriksaan adalah simpul yang menentukan kapan langkah berikutnya boleh dimulai.

Yang tidak dibahas adalah penjadwalan batch, kapasitas harian, atau optimasi antrean. Itu keputusan berbeda. Di sini pertanyaannya: proses mana yang harus mendahului proses lain agar datum, akses, keselamatan, dan bukti inspeksi tetap terjaga? Jika gambar, spesifikasi, atau kondisi lapangan belum jelas, tulis `[NEEDS PROJECT REVIEW: datum, toleransi, dan acceptance basis belum ditetapkan]` dan jangan mengunci routing sebagai instruksi produksi.

## Cara kerjanya

Mulai dengan lembar routing yang memiliki nomor komponen, revisi gambar, material, kuantitas, dan penanggung jawab. Pecah pekerjaan menjadi langkah berikut.

1. **Review dan identifikasi.** Cocokkan revisi, material, ketebalan, datum, lubang, sambungan, allowance, serta titik hold. Tandai fitur yang harus dilindungi dari panas atau coating. Jangan memulai jika material pengganti belum disetujui.
2. **Cutting.** Potong dengan allowance yang memang diberikan gambar. Sisakan tanda orientasi dan nomor komponen pada area yang tidak akan hilang oleh machining atau coating.
3. **Deburring dan pemeriksaan awal.** Hilangkan burr yang mengganggu penjepitan, ukur dimensi kritis, dan catat hasilnya. Burr bukan sekadar masalah tampilan; ia dapat menggeser datum dan melukai saat handling.
4. **Bending atau forming.** Lakukan sebelum fitur yang dapat berubah atau retak akibat pembentukan dibuat. Verifikasi sudut, radius, springback, dan arah serat bila relevan terhadap dokumen proyek.
5. **Machining.** Tetapkan datum kerja dari fitur yang sudah disetujui. Buat lubang presisi, slot, atau permukaan akhir setelah bentuk utama stabil. Bila machining dilakukan setelah welding, tetapkan allowance dan strategi untuk distorsi.
6. **Marking lanjutan.** Pastikan identitas tetap terbaca setelah proses berikutnya. Marking yang menjadi referensi assembly harus ditempatkan pada permukaan yang tidak dipotong, digerinda, atau tertutup coating.
7. **Fit-up dan welding.** Cek gap, alignment, tack, akses elektroda, urutan las, dan kebutuhan preheat/interpass sesuai WPS proyek. Kualifikasi prosedur, WPS produksi, kualifikasi welder, serta penerimaan sambungan adalah rekaman berbeda; jangan menukar satu dengan yang lain ([ISO 15614-1](https://www.iso.org/standard/51792.html), [ISO 9606-1](https://www.iso.org/standard/54936.html)).
8. **Pemeriksaan dan perbaikan.** Tetapkan siapa yang memeriksa, metode, extent, kondisi permukaan, identitas alat, laporan, dan otoritas disposition. Standar mutu las, metode NDT, dan sertifikasi personel tidak otomatis menetapkan acceptance proyek; gunakan standar dan prosedur yang disetujui ([ISO 5817](https://www.iso.org/standard/80209.html), [ISO 17635](https://www.iso.org/standard/85705.html), [ISO 9712](https://www.iso.org/standard/75614.html)).
9. **Coating.** Bersihkan dan siapkan permukaan sesuai produk serta spesifikasi. Jangan mengecat area yang masih memerlukan welding, grounding, atau fit-up. Catat produk dan batch; lembar keselamatan generik tidak membuktikan kompatibilitas, rasio campur, atau waktu curing ([OSHA hazard communication](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200)).
10. **Assembly dan closeout.** Rakit dengan fastener, shim, seal, atau komponen pengganti yang identitasnya terlacak. Lakukan pemeriksaan akhir terhadap orientasi, interface, marking, coating damage, dan dokumen serah-terima.

Kawan Bengkel-las.co.id, setiap perpindahan proses perlu kriteria “siap lanjut”. Tanpa itu, komponen yang sudah telanjur dicat sering kembali ke welding, lalu mengulang pembersihan dan inspeksi.

## Faktor yang mengubah hasil

Pertama, **fungsi dan datum**. Komponen yang menjadi acuan lubang atau bantalan harus memiliki datum stabil sebelum machining dan assembly. Kedua, **distorsi dan panas**. Welding dapat mengubah alignment, sehingga machining akhir mungkin lebih masuk akal daripada machining presisi sebelum las. Ketiga, **akses**. Lubang yang tertutup setelah assembly harus dibuat atau diperiksa sebelumnya; sebaliknya, sambungan yang baru dapat dijangkau setelah subassembly mungkin harus ditunda.

Keempat, **perlindungan permukaan**. Coating sebelum assembly bisa mengurangi pekerjaan di tempat, tetapi hanya jika permukaan sambungan, toleransi, dan area perbaikan sudah ditentukan. Kelima, **lokasi kerja**. Memindahkan welding ke lapangan karena transport sulit dapat mengubah fit-up, lifting, cuaca, fume, bahaya kebakaran, inspeksi, dan pemulihan area. OSHA 1910.252 berguna sebagai ilustrasi bahaya hot work, bukan sebagai pengganti persetujuan K3 Indonesia ([UU No. 1/1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), [Permenaker No. 5/2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018), [OSHA 1910.252](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252)).

Keenam, **bukti dan traceability**. Simpan hubungan antara heat atau batch material bila diwajibkan, filler, WPS, welder, alat ukur, laporan NDT, coating batch, dan nonconformance. Ketujuh, **K3 dan lingkungan**. Pengendalian dimulai dari eliminasi atau substitusi, rekayasa dan administrasi, baru PPE yang sesuai; detail ventilasi, APD, penyimpanan bahan, serta limbah harus ditetapkan dari produk dan lokasi aktual oleh pihak berwenang. `[NEEDS K3 REVIEW: kontrol tugas, bahan, energi, dan keadaan darurat belum disahkan]`.

## Contoh keputusan praktis

Gunakan tabel berikut sebagai alat diskusi, bukan instruksi universal.

| Kondisi yang terverifikasi | Routing yang masuk akal | Titik keputusan |
|---|---|---|
| Lubang presisi menjadi datum assembly dan tidak terpengaruh panas | Cutting → deburring → bending → machining lubang → marking → assembly | Lindungi lubang dari coating dan cek gauge sebelum rakit |
| Dua pelat dilas lalu permukaan harus rata | Cutting → deburring → fit-up/welding → pemeriksaan → machining akhir → coating → assembly | Sisakan allowance dan tetapkan batas distorsi |
| Sambungan hanya dapat dijangkau sebelum subassembly | Cutting → marking orientasi → fit-up/welding → pemeriksaan → coating lokal/akhir → assembly | Pastikan area las tetap bebas coating |
| Komponen harus dirakit di lokasi | Fabrikasi dan pemeriksaan di bengkel → perlindungan/packing → site fit-up | Tinjau ulang lifting, akses, cuaca, hot-work, dan inspeksi lapangan |

Misalnya, jika gambar belum menyatakan apakah permukaan referensi dibuat sebelum atau sesudah welding, jangan memilih berdasarkan mesin yang sedang kosong. Minta engineer atau inspector menetapkan datum, allowance, dan acceptance basis. Sobat Bengkel-las.co.id, keputusan kecil itu mencegah “koreksi” berupa menggerinda fitur yang seharusnya menjadi referensi.

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah menaruh marking di area yang pasti dimachining atau dicat. Tanyakan: apakah nomor, orientasi, dan jejak batch masih terbaca pada pemeriksaan akhir? Kedua, melakukan coating sebelum semua pekerjaan panas selesai. Tanyakan: area mana yang wajib bebas coating, dan siapa yang mengesahkan touch-up?

Ketiga, menganggap kartu welder sebagai bukti seluruh sambungan diterima. Periksa WPS, cakupan kualifikasi, kontinuitas, rekaman parameter yang diwajibkan, laporan pemeriksaan, dan disposition terpisah. Keempat, menganggap NDT otomatis menjawab kelayakan fungsi. Cocokkan metode dan extent dengan acceptance basis proyek; abstrak standar tidak menyediakan tabel batas yang boleh ditebak.

Kelima, merakit tanpa verifikasi interface. Ukur lubang, jarak, orientasi, shim, dan kerusakan coating sebelum mengencangkan. Keenam, memindahkan pekerjaan ke lapangan tanpa penilaian ulang. Tinjau energi, bahan mudah terbakar, penghuni sekitar, jalur evakuasi, listrik, cuaca, lifting, ventilasi, dan izin setempat. Jika salah satu belum jelas, hentikan dan tandai `[NEEDS SITE/K3 REVIEW]`.

## Jalan pintas yang perlu diuji

Shortcut yang sering terdengar adalah, “Marking dan coating belakangan saja; yang penting cepat dirakit.” Ini gagal ketika identitas hilang, lubang tertutup, atau subassembly menghalangi inspeksi dan perbaikan. Alternatif yang lebih andal adalah membuat marking minimum yang tahan terhadap proses, menetapkan area no-coat, dan menutup setiap langkah dengan catatan inspeksi. Kecepatan kemudian diukur dari sedikitnya rework, bukan dari langkah yang dilewati.

## Kesimpulan

Tentukan urutan dengan prinsip: stabilkan material dan datum, bentuk dan las sebelum finishing presisi yang rentan distorsi, lakukan machining saat referensi sudah dapat dipercaya, marking di permukaan yang tetap terlihat, coating setelah pekerjaan panas dan inspeksi yang diwajibkan, lalu assembly setelah interface lolos pemeriksaan. Urutan final harus mengikuti gambar revisi, WPS, acceptance basis, kondisi lokasi, dan keputusan kompeten—bukan kebiasaan bengkel.

Langkah berikutnya: buat satu lembar routing untuk komponen Anda, isi “siap lanjut” pada tiap handoff, lalu minta review engineer, inspector, dan penanggung jawab K3 sebelum produksi. Tanpa data proyek tersebut, artikel ini hanya kerangka pengambilan keputusan; `[NEEDS TECHNICAL REVIEW: routing final dan seluruh gate proyek belum disahkan]`.

Untuk menyiapkan pertanyaan teknis berikutnya, Anda dapat kembali ke [beranda Bengkel-las.co.id](/) sambil membawa gambar revisi dan daftar titik inspeksi.
