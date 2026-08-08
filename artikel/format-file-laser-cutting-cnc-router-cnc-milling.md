---
article_id: CUT-02-02
title: "Format File untuk Laser Cutting, CNC Router, dan CNC Milling"
slug: "format-file-laser-cutting-cnc-router-cnc-milling"
description: "Menyiapkan gambar yang dapat diperiksa dan diproses tanpa revisi berulang."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-08-18"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-02
primary_intent: "Memilih format file yang dapat diproses"
reader_community: "Bengkel-las.co.id"
reader_address: "Teman Bengkel-las.co.id"
final_route: "/artikel/format-file-laser-cutting-cnc-router-cnc-milling.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/83335.html"
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://www.iso.org/standard/85705.html"
---

# Format File untuk Laser Cutting, CNC Router, dan CNC Milling

Halo, Teman Bengkel-las.co.id! Format yang paling aman bukan sekadar ekstensi yang bisa dibuka, melainkan format yang menyimpan geometri, skala, satuan, dan informasi revisi secara jelas. Untuk laser cutting dan CNC router, kirim geometri 2D yang bersih—umumnya DXF atau DWG sesuai permintaan operator—serta PDF sebagai lembar acuan. Untuk CNC milling, tambahkan model 3D seperti STEP bila bentuk dan kedalaman tidak cukup dijelaskan oleh garis 2D.

Jawaban itu tetap bersyarat. Mesin, perangkat lunak CAM, post-processor, material, dan cara operator menetapkan titik nol menentukan format yang benar-benar dapat diproses. Tanyakan terlebih dahulu format yang diterima, satuan kerja, versi perangkat lunak, dan apakah file tersebut dipakai untuk potong, ukir, pocket, atau milling 3D. Jangan menganggap file yang dapat dibuka otomatis siap dipotong.

<!-- BEGIN MANAGED IMAGE PLAN
Image ID: LOCAL-002
Placement: after opening, before first detailed H2
**Exact Markdown to insert:** `![Ilustrasi CNC Router 4](/wp-content/uploads/2019/11/CNC-Router-4.jpg)`
Caption/credit: Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
Selection basis: filename/source metadata identifies CNC Router 4; no pixels inspected.
Hard boundary: do not infer visible details, ownership, location, people, brands, condition, performance, or outcome.
END MANAGED IMAGE PLAN -->

![Ilustrasi CNC Router 4](/wp-content/uploads/2019/11/CNC-Router-4.jpg)

Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu. [Buka aset lokal](/wp-content/uploads/2019/11/CNC-Router-4.jpg).

## Jawaban singkat dan salah paham utama

DXF sering menjadi pilihan praktis untuk kontur 2D karena operator CAM dapat membaca garis, busur, dan polyline. DWG dapat dipakai bila bengkel memintanya, tetapi versi dan objek di dalamnya perlu dikonfirmasi. SVG, AI, dan PDF berguna untuk pertukaran desain atau acuan visual; belum tentu cocok sebagai sumber toolpath. Untuk milling, STEP biasanya lebih berguna daripada PDF karena menyimpan permukaan dan volume 3D, namun tetap memerlukan pemeriksaan di CAM.

Salah paham yang sering menimbulkan revisi adalah menyamakan “format file” dengan “kesiapan produksi”. File bisa memiliki ekstensi yang benar tetapi berisi garis ganda, kontur terbuka, skala milimeter yang terbaca sebagai inci, atau teks yang masih berupa font. Bentuk-bentuk itu dapat membuat jalur alat salah, ukuran berubah, atau fitur terpotong dua kali. [NEEDS PROJECT REVIEW: konfirmasi aturan impor, satuan, dan toleransi pada mesin serta CAM yang akan dipakai.]

## Definisi dan batas objek

Artikel ini membahas pemilihan wadah data dan pemeriksaan sebelum file dikirim ke bengkel. Yang dimaksud “format” mencakup ekstensi, versi, satuan, dimensi bidang, dan cara data diterjemahkan oleh CAM. Artikel ini tidak mengajarkan menggambar CAD, menentukan diameter pahat, menghitung parameter laser, atau menyetujui desain struktur.

Untuk pekerjaan yang terhubung ke konstruksi atau fabrikasi, file digital hanyalah satu bagian dari paket terkendali. Ringkasan [ISO 3834-6:2024](https://www.iso.org/standard/83335.html) menempatkan pengaturan mutu sebagai hal yang perlu ditentukan sesuai aplikasi; artinya identitas material, revisi, instruksi, dan catatan pemeriksaan tidak boleh diganti dengan nama file yang samar. Bila gambar menjadi bagian dari paket kerja, [katalog BSN untuk SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020) juga perlu diperlakukan sebagai rujukan status standar, bukan sebagai pengganti dokumen proyek berlisensi dan gambar terbitan.

## Cara kerjanya

Urutan yang sederhana membantu memisahkan masalah desain dari masalah pemrosesan.

1. **Tentukan operasi.** Tandai apakah geometri dipakai untuk potong tembus, marking, ukir, pocket, atau kontur 3D. Satu file yang mencampur semua operasi tanpa penanda membuat operator menebak.
2. **Pilih data utama.** Gunakan geometri 2D untuk laser dan router 2D. Gunakan model 3D untuk milling yang memerlukan permukaan atau volume. Sertakan PDF berdimensi sebagai pembanding manusia, bukan sebagai jaminan bahwa PDF dapat menjadi toolpath.
3. **Tetapkan satuan dan titik acuan.** Tulis “mm” atau “inch” di nama paket dan lembar acuan. Cantumkan ukuran keseluruhan dan posisi titik nol yang diharapkan. Jangan meminta operator mengukur ulang dari tampilan layar.
4. **Bersihkan geometri.** Pastikan kontur tertutup, tidak ada garis duplikat, dan elemen berada pada bidang yang benar. Untuk teks, ubah font menjadi outline bila teks memang akan dipotong atau diukir.
5. **Kirim paket dengan identitas revisi.** Nama seperti `bracket_A_rev03.dxf` lebih mudah dilacak daripada `final-final.dxf`. Sertakan daftar file, material, tebal atau ukuran stok, jumlah, dan catatan fitur yang tidak boleh diubah.
6. **Minta pratinjau CAM.** Sebelum produksi, cocokkan ukuran bounding box, arah, titik nol, urutan operasi, dan jumlah kontur. Simpan hasil persetujuan bersama nomor revisi.

Teman Bengkel-las.co.id, langkah keenam penting karena keberhasilan impor bukan bukti bahwa toolpath sudah benar. Hasil akhir dipengaruhi post-processor dan setup mesin yang hanya dapat disahkan oleh operator atau penanggung jawab teknis yang menguasai peralatan tersebut.

## Faktor yang mengubah hasil

Beberapa kondisi membuat format yang sama berperilaku berbeda:

| Faktor | Pertanyaan yang perlu dijawab sebelum kirim |
|---|---|
| Mesin dan CAM | Perangkat lunak apa yang mengimpor file, dan versi berapa? |
| Operasi | Apakah setiap layer/objek mewakili potong, marking, pocket, atau finishing? |
| Material | Apa jenis dan tebal bahan, serta ukuran stok yang tersedia? |
| Geometri | Apakah skala 1:1, kontur tertutup, dan semua kurva berada di bidang kerja? |
| Toleransi | Angka toleransi berasal dari gambar terbitan atau hanya asumsi pengirim? |
| Revisi | File mana yang berlaku, siapa yang menyetujui, dan apa yang berubah? |
| Bukti pemeriksaan | Apakah ada PDF berdimensi, pratinjau toolpath, atau catatan hasil ukur? |

Bila gambar dikaitkan dengan komponen struktural, jangan menerjemahkan label format menjadi keputusan kelayakan. [ISO 17635:2025](https://www.iso.org/standard/85705.html) membedakan metode, cakupan, teknik, personel, peralatan, pelaporan, dan dasar penerimaan dalam inspeksi. Prinsipnya relevan di sini: file yang rapi mendukung pemeriksaan, tetapi tidak menggantikan persetujuan teknik atau pemeriksaan benda jadi.

## Contoh keputusan praktis

Bayangkan Anda hendak memotong plat datar dengan laser. Bengkel meminta DXF dan PDF. Kirim satu DXF berisi kontur potong saja, dengan satuan dan ukuran keseluruhan tertulis; gunakan PDF untuk menunjukkan dimensi lubang, jumlah, dan orientasi. Jika ada marking, letakkan pada layer atau file terpisah yang diberi nama jelas. Jangan menaruh garis konstruksi di layer potong.

Untuk panel nonlogam pada router, pertanyaan tambahannya adalah apakah sudut dalam memerlukan radius akibat diameter pahat. File DXF dapat menyampaikan kontur, tetapi tidak memutuskan radius minimum, kedalaman, atau urutan pemakanan. Minta operator menandai fitur yang tidak dapat dicapai pahat dan setujui perubahan melalui revisi.

Untuk komponen dengan rongga atau permukaan miring pada CNC milling, kirim STEP dan PDF. STEP membantu pertukaran bentuk 3D; PDF menjelaskan ukuran kritis, datum, dan toleransi yang harus diperiksa. Jika operator hanya menerima format tertentu, tanyakan konversi yang mereka lakukan dan minta pemeriksaan ulang setelah konversi. [NEEDS PROJECT REVIEW: format 3D, versi STEP, dan toleransi harus disahkan berdasarkan CAM serta gambar terbitan proyek.]

## Kesalahan umum dan cara memeriksanya

- **Mengirim PDF saja.** PDF dapat menjadi acuan, tetapi belum tentu memuat geometri yang dapat dipakai CAM. Tanyakan format kerja yang diminta dan lampirkan PDF sebagai pembanding.
- **Mengandalkan ekstensi tanpa memeriksa satuan.** Buka properti atau ukur dimensi keseluruhan di perangkat lunak, lalu bandingkan dengan angka pada lembar acuan.
- **Mencampur layer.** Beri nama layer berdasarkan operasi dan pastikan layer bantu dimatikan dari ekspor produksi.
- **Membiarkan kontur terbuka atau ganda.** Jalankan pemeriksaan geometri, kemudian minta operator mengonfirmasi jumlah profil dan panjang potong pada pratinjau.
- **Menamai semua versi “final”.** Gunakan nomor revisi, tanggal sesuai sistem proyek, dan catatan perubahan. Hapus salinan lama dari paket pengiriman agar tidak tertukar.
- **Mengubah model tanpa jejak.** Setiap koreksi ukuran atau radius harus kembali ke sumber gambar dan disetujui; jangan hanya memperbaiki hasil ekspor.

Kawan Bengkel-las.co.id, checklist singkat sebelum menekan tombol kirim adalah: format sesuai permintaan bengkel, satuan tertulis, skala 1:1, kontur yang diperlukan tertutup, layer operasi terpisah, material dan tebal dicantumkan, PDF acuan tersedia, lalu nomor revisi cocok di semua berkas. Jika satu jawaban belum jelas, berhenti dan minta klarifikasi.

## Jalan pintas yang tampak praktis

Jalan pintas yang sering dipilih adalah mengubah gambar menjadi format apa pun yang “bisa dibuka” oleh operator, lalu berharap bengkel menyesuaikan. Cara itu menggeser keputusan penting—skala, layer, titik nol, dan interpretasi kurva—ke tahap yang sulit diaudit. Konversi juga dapat mengubah spline menjadi segmen atau menghilangkan informasi 3D.

Alternatif yang lebih aman adalah menyepakati format asli dan format pertukaran sebelum menggambar selesai, mengirim paket kecil untuk uji impor, dan meminta tangkapan pratinjau atau daftar hasil pemeriksaan. Persetujuan tersebut harus melekat pada nomor revisi, bukan pada percakapan yang tidak terdokumentasi.

## Kesimpulan dan langkah berikutnya

Format file yang tepat bergantung pada operasi dan rantai CAM: DXF/DWG untuk geometri 2D sesuai permintaan mesin, STEP untuk bentuk 3D yang benar-benar diperlukan, dan PDF sebagai acuan berdimensi. Tidak ada ekstensi yang sendirian menjamin hasil potong atau milling.

Sebelum mengirim, tanyakan kepada operator: format dan versi apa yang diterima, satuan serta titik nol apa yang dipakai, layer mana untuk tiap operasi, dan bukti pratinjau apa yang akan dikembalikan. Lampirkan material, ukuran stok, toleransi dari gambar terbitan, dan nomor revisi. Jika keputusan menyentuh fungsi struktur, keselamatan, atau penerimaan produk, minta peninjauan teknis yang berwenang.

Aturan kerjanya sederhana: file boleh diproses hanya setelah geometri, satuan, operasi, revisi, dan persetujuan impor dapat ditelusuri; kemampuan membuka file bukan pengganti verifikasi.

Untuk menyiapkan berkas dan mengirim pertanyaan teknis, Anda dapat mulai dari [beranda Bengkel-las.co.id](/) agar konteks pekerjaan dan kebutuhan bengkel tetap tercatat.
