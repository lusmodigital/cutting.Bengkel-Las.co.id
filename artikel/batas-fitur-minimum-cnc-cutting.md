---
article_id: CUT-08-06
title: "Lebar Slot, Diameter Lubang, dan Jarak Minimum Antarfitur"
slug: "batas-fitur-minimum-cnc-cutting"
description: "Menulis target dimensi dan toleransi yang realistis serta mengantisipasi kerf dan kompensasi."
status: draft
writing_contract_version: "native-id-v2"
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
  - "https://www.iso.org/standard/83335.html"
  - "https://www.iso.org/standard/85705.html"
---

# Lebar Slot, Diameter Lubang, dan Jarak Minimum Antarfitur

Halo, Sobat Bengkel-las.co.id!

Slot yang terlalu sempit, lubang yang terlalu kecil, atau dua fitur yang terlalu berdekatan bisa gagal sebelum lembaran masuk mesin. Jawaban yang aman bukan satu angka “batas CNC” untuk semua pekerjaan. Lebar slot, diameter lubang, dan jarak antarfitur harus ditetapkan dari alat potong, tebal serta jenis material, metode pemotongan, kemampuan mesin, toleransi gambar, dan fungsi komponen. Tanpa data itu, angka minimum hanyalah tebakan dan perlu ditandai `[NEEDS PROJECT/MACHINE CAPABILITY REVIEW]`.

Mulailah dengan membedakan ukuran nominal pada gambar dari ukuran yang sanggup dibuat dan diukur secara konsisten. Tanyakan apakah slot akan dipakai untuk baut lewat, aliran udara, penguncian, atau sekadar mengurangi massa. Fungsi tersebut menentukan toleransi dan cara memeriksa hasil. Kerf—lebar material yang hilang oleh jalur potong—juga harus masuk ke kompensasi lintasan, tetapi kompensasi tidak dapat menghapus semua pengaruh panas, getaran, keausan alat, atau deformasi lembaran.

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

Aset lokal proyek; gambar ini bukan dokumentasi proyek tertentu.

## Definisi dan batas objek

“Fitur kecil” di sini berarti geometri yang ukurannya mendekati batas stabil proses: bukaan slot, lubang tembus atau buntu, sudut dalam, serta jarak dari fitur itu ke tepi atau fitur lain. Fokusnya adalah geometri pada satu komponen hasil CNC cutting. Nesting antarkomponen, yaitu pengaturan banyak komponen dalam satu lembaran, berada di luar bahasan ini.

Tiga ukuran perlu dibaca bersama. Lebar slot adalah ukuran bukaan setelah material terpotong, bukan sekadar diameter alat. Diameter lubang adalah ukuran akhir yang harus bisa menerima fungsi pasangan, bukan ukuran file CAD semata. Jarak antarfitur sebaiknya dibaca dari tepi-ke-tepi dan dari pusat-ke-pusat sesuai cara gambar mendefinisikannya. Jika datum atau arah pengukuran tidak jelas, operator dan pemeriksa dapat memakai acuan berbeda.

Toleransi bukan “bonus” yang otomatis tersedia. Toleransi adalah rentang yang disepakati, dengan metode ukur dan kondisi ukur yang juga harus jelas. Spesifikasi fabrikasi yang terkendali lazimnya menghubungkan dokumen dan revisi, material, dimensi, toleransi, urutan kerja, titik inspeksi, serta dasar penerimaan; identitas kebutuhan itu perlu datang dari paket kerja yang disetujui, bukan kebiasaan lisan. Rujukan [ISO 3834-6:2024](https://www.iso.org/standard/83335.html) dapat dipakai sebagai pengingat bahwa persyaratan mutu dan dokumentasi harus ditentukan untuk pekerjaan yang relevan, sementara rincian proyek tetap memerlukan dokumen yang berlaku. [NEEDS PROJECT FABRICATION SPECIFICATION]

## Cara kerjanya

Urutkan keputusan dari fungsi ke proses. Pertama, tandai fitur mana yang benar-benar kritis: lubang untuk pin, slot untuk penyetelan, atau jarak yang memengaruhi kekuatan tepi. Kedua, pilih proses yang diizinkan oleh material dan tebalnya. Laser, plasma, router, atau proses lain meninggalkan karakter tepi, lebar zona terpengaruh panas, dan kebutuhan finishing yang berbeda. Ketiga, minta kemampuan aktual mesin pada kombinasi material tersebut, bukan angka promosi umum.

Setelah itu, hitung lintasan berdasarkan ukuran akhir yang diinginkan. Pada pemotongan profil, pusat lintasan alat berada di satu sisi garis teoritis; nilai offset mempertimbangkan kerf. Kerf yang berubah sepanjang lembaran membuat kompensasi nominal perlu dibuktikan dengan kupon atau pemeriksaan awal yang disetujui. Jangan mengubah nilai offset hanya agar satu lubang terlihat pas lalu menerapkannya ke semua fitur tanpa verifikasi.

Untuk slot, periksa lebar efektif di beberapa titik dan pastikan alat dapat masuk, berbelok, serta membuang panas dan serpihan sesuai proses. Slot yang memanjang tetapi sempit bisa lebih sensitif terhadap kelurusan dan taper daripada lubang pendek. Untuk lubang, periksa kebulatan, taper, burr, dan kondisi permukaan sebelum menyimpulkan bahwa diameter sudah memenuhi fungsi. Untuk fitur berdekatan, lihat juga sisa web atau ligamen di antaranya: bagian ini dapat melengkung, terbakar, atau robek ketika panas dan gaya pemotongan terakumulasi.

Rencana inspeksi perlu menyebut siapa yang mengukur, alat ukur apa, resolusi dan status verifikasinya, lokasi titik ukur, serta cara menangani hasil di luar toleransi. [ISO 17635:2025](https://www.iso.org/standard/85705.html) mengingatkan bahwa metode, cakupan, teknik, personel, peralatan, kondisi permukaan, pelaporan, dan dasar penerimaan adalah bukti yang terpisah; satu pengukuran visual tidak otomatis menjadi keputusan penerimaan menyeluruh. [NEEDS INSPECTION PLAN AND ACCEPTANCE BASIS]

## Faktor yang mengubah hasil

Material dan tebal mengubah panas, kekakuan, dan respons tepi. Lembaran tipis dapat bergerak ketika area di sekitarnya dipotong; material yang lebih tebal dapat memerlukan strategi lintasan berbeda. Kondisi permukaan, lapisan, sisa tegangan, dan kualitas penyanggaan juga dapat mengubah hasil. Karena itu, contoh angka dari material lain tidak boleh dipindahkan begitu saja.

Alat potong dan kondisi mesin ikut menentukan. Diameter atau lebar alat, fokus atau tinggi pemotongan, kecepatan, daya, gas, strategi masuk-keluar, keausan, dan kebersihan meja merupakan parameter proses. Nilai tersebut adalah parameter pekerjaan, bukan fakta universal yang dapat ditetapkan dari judul artikel ini. Mintalah lembar kemampuan proses atau hasil trial yang menyebut kombinasi material, tebal, alat, dan tanggal verifikasi. `[NEEDS CURRENT MACHINE CAPABILITY RECORD]`

Geometri juga saling memengaruhi. Lubang dekat tepi meninggalkan web yang lebih kecil daripada lubang yang sama di area lapang. Dua slot paralel dapat menyisakan strip sempit yang mudah berubah bentuk. Radius sudut dalam, urutan potong, dan titik lead-in dapat mengurangi atau memindahkan masalah, tetapi tidak mengubah fungsi desain yang memang meminta bukaan sangat kecil.

Terakhir, bedakan ukuran sebelum dan sesudah finishing. Deburring, penggerindaan, pelapisan, atau pembesaran lubang untuk proses lanjutan dapat mengubah ukuran dan tepi. Gambar harus menyatakan tahap mana yang menjadi referensi penerimaan. Jika komponen akan dirakit, toleransi pasangan, arah pemasangan, dan kemungkinan penyesuaian harus ditinjau bersama oleh perancang dan pelaksana.

## Contoh keputusan praktis

Gunakan tabel keputusan berikut sebagai percakapan awal, bukan pengganti data proses.

| Pertanyaan pada gambar atau permintaan | Keputusan awal yang aman | Bukti yang masih diperlukan |
|---|---|---|
| Slot hanya untuk mengurangi massa | Longgarkan target bila fungsi mengizinkan dan hindari web yang sangat tipis | Fungsi, tebal material, dan target kekuatan |
| Slot menjadi jalur baut atau penyetelan | Tetapkan ukuran akhir dan toleransi berdasarkan pasangan baut/washer serta cara ukur | Detail pasangan, datum, dan kapabilitas mesin |
| Lubang menerima pin atau poros | Jangan memakai diameter alat sebagai diameter akhir; tetapkan kebutuhan pas dan proses lanjutan | Spesifikasi pasangan, finishing, dan verifikasi diameter |
| Dua lubang sangat dekat | Periksa web minimum, urutan potong, dan risiko deformasi sebelum menyetujui | Trial pada material-tebal yang sama dan persetujuan desain |
| Tepi fitur akan dilas atau dilapisi | Sisakan kondisi tepi dan akses yang memungkinkan proses berikutnya | Prosedur sambungan/lapisan dan titik inspeksi |

Misalnya, permintaan “buat lubang sekecil mungkin” belum cukup untuk diteruskan ke operator. Pertanyaan yang benar adalah: sekecil apa menurut fungsi, pada material dan tebal berapa, dengan proses apa, dan bagaimana diameter akan diterima? Jika jawabannya belum tertulis, tahan rilis gambar dan pasang `[NEEDS DESIGN FUNCTION AND ACCEPTANCE CRITERIA]`.

Sobat Bengkel-las.co.id, ketika hasil trial menunjukkan satu ukuran berhasil, catat kondisi yang membuatnya berhasil. Catatan itu bukan jaminan untuk semua batch; ia hanya bukti untuk kombinasi yang diuji. Perubahan material, nozzle, alat, program, atau urutan potong memerlukan penilaian ulang.

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah menyalin “minimum hole” dari tabel vendor tanpa mencocokkan material, tebal, proses, dan toleransi. Periksa sumber angka dan minta kapabilitas yang dapat ditelusuri.

Kesalahan kedua adalah mengukur satu titik lalu menyatakan semua fitur lulus. Ukur pola yang mewakili awal, tengah, dan akhir pemotongan; tetapkan metode serta alatnya di rencana inspeksi. Jika metode pemeriksaan atau dasar penerimaan belum disepakati, hasilnya belum menjadi keputusan final.

Kesalahan ketiga adalah mengira kompensasi kerf menyelesaikan taper, burr, panas, dan gerakan lembaran sekaligus. Verifikasi ukuran akhir dan kondisi tepi; jangan menyamakan koreksi program dengan jaminan performa.

Kesalahan keempat adalah mengabaikan revisi gambar dan datum. Cocokkan file yang diprogram, gambar yang disetujui, nomor revisi, orientasi material, serta tanda identifikasi komponen sebelum memotong.

Kesalahan kelima adalah memperbesar atau menggerinda fitur di lapangan tanpa otorisasi. Perubahan itu dapat memindahkan datum dan mengurangi web. Setiap penyimpangan harus dicatat dan disetujui pihak berwenang dalam paket kerja.

## Jalan pintas yang sering dipilih

Jalan pintas yang paling menggoda adalah menetapkan satu angka minimum untuk semua lubang dan slot agar pemesanan cepat. Cara ini gagal karena angka minimum bukan hanya sifat mesin; ia adalah hasil interaksi fungsi, material, proses, toleransi, dan pemeriksaan. Lebih aman membuat daftar fitur kritis, meminta rekaman kapabilitas untuk kombinasi yang akan dipakai, lalu melakukan trial atau review teknik bila bukti belum ada.

Kawan Bengkel-las.co.id, jangan menyamarkan ketidakpastian dengan menulis toleransi rapat yang tidak bisa diverifikasi. Toleransi yang terlalu ketat dapat memicu rework, sedangkan toleransi yang terlalu longgar dapat menggagalkan perakitan. Pilih toleransi yang dibutuhkan fungsi dan pastikan cara ukurnya realistis.

## Kesimpulan

Lebar slot, diameter lubang, dan jarak minimum antarfitur tidak memiliki satu angka universal. Tetapkan ukuran akhir dari fungsi, tebal dan jenis material, proses serta alat, kerf dan kompensasinya, kondisi finishing, lalu pastikan toleransi, datum, dan dasar penerimaan tertulis. Sebelum produksi, minta gambar revisi yang disetujui, catatan kemampuan mesin atau trial yang relevan, dan rencana inspeksi; tandai `[NEEDS TECHNICAL REVIEW]` bila salah satunya belum tersedia.

Teman Bengkel-las.co.id, aturan operasionalnya sederhana: fitur kecil boleh dirilis hanya setelah fungsi dan cara ukurnya jelas serta kapabilitas prosesnya dibuktikan untuk kombinasi pekerjaan tersebut. Jika bukti itu belum ada, berhenti di tahap review—jangan mengisi kekosongan dengan angka tebakan. Untuk konteks layanan dan topik terkait, mulai dari [beranda Bengkel-las.co.id](/), lalu simpan [rujukan ilustrasi kerja](/wp-content/uploads/2019/10/bengkel-las.png) bersama gambar dan kriteria penerimaan sebelum rilis.
