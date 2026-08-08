---
article_id: CUT-08-05
title: "Radius Sudut Dalam pada CNC Router dan CNC Milling"
slug: "radius-sudut-dalam-cnc"
description: "Menulis target dimensi dan toleransi yang realistis serta mengantisipasi kerf dan kompensasi."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2026-01-14"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-08
primary_intent: "Mendesain sudut yang dapat dikerjakan tool"
reader_community: "Bengkel-las.co.id"
reader_address: "Kawan Bengkel-las.co.id"
final_route: "/artikel/radius-sudut-dalam-cnc.html"
technical_review: required
sources: []
---

<!-- BEGIN MANAGED IMAGE PLAN
Image ID: LOCAL-003
Placement: setelah pembuka, sebelum H2 pertama
**Exact Markdown to insert:** `![Ilustrasi CNC Milling 4](/wp-content/uploads/2019/11/CNC-Milling-4.jpg)`
Caption/credit: Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
END MANAGED IMAGE PLAN -->

# Radius Sudut Dalam pada CNC Router dan CNC Milling

Halo, Kawan Bengkel-las.co.id! Sudut dalam yang tampak siku pada gambar CAD tidak otomatis dapat dibuat siku oleh CNC router atau CNC milling. Kedua mesin menggunakan tool dengan badan dan ujung yang berbentuk bulat. Saat tool mengikuti dua sisi yang bertemu, bagian paling dalam dari sudut menyisakan lengkung dengan radius tertentu. Akibatnya, target radius nol biasanya tidak realistis tanpa proses tambahan.

Jawaban singkatnya: rancang radius sudut dalam sekurang-kurangnya sebesar radius efektif tool yang benar-benar dipakai, lalu konfirmasikan dengan bengkel berdasarkan diameter, panjang potong, material, kedalaman, dan strategi pemesinan. Jika gambar meminta sudut lebih tajam daripada kemampuan tool, pilih radius yang lebih besar, ubah desain dengan relief, atau siapkan operasi akhir yang terpisah. Nilai toleransi dan kompensasi bukan angka universal; keduanya harus disepakati dari gambar, material, mesin, serta hasil pengukuran benda kerja.

![Ilustrasi CNC Milling 4](/wp-content/uploads/2019/11/CNC-Milling-4.jpg)

Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.

## Definisi dan batas objek

Radius sudut dalam adalah jarak dari titik pertemuan teoretis dua bidang ke lengkung aktual pada pojok bagian dalam. Pada gambar, sudut 90 derajat dengan radius dalam 3 mm berarti dua dinding bertemu melalui busur 3 mm, bukan melalui titik tajam. Istilah *corner radius* sering dipakai pada gambar berbahasa Inggris. Bedakan dengan radius luar: radius luar adalah lengkung pada sisi cembung, sedangkan pembahasan ini khusus sisi cekung yang dibatasi tool.

Artikel ini membahas desain fitur untuk CNC router dan CNC milling dengan tool berpenampang bulat. “Kerf” pada pemotongan adalah lebar material yang hilang akibat lebar tool; pada milling, persoalan yang sama muncul sebagai jejak tool dan kompensasi lintasan. Laser tidak menjadi intent utama di sini, karena mekanisme pembentukan sudutnya berbeda. Jangan memindahkan aturan radius CNC ke laser atau sebaliknya tanpa meninjau prosesnya. Bila Anda sedang menyusun paket pemotongan yang lebih luas, mulai dari [beranda Bengkel-las.co.id](/) untuk menempatkan kebutuhan ini dalam konteks pekerjaan Anda.

Gambar kerja sebaiknya memisahkan radius yang memang menjadi fungsi dari radius yang sekadar hasil proses. Radius fungsional perlu ditulis sebagai ukuran dan toleransi. Radius nonkritis dapat diberi catatan umum yang tetap disetujui pembuat dan pemeriksa. Jika dokumen hanya menulis “siku tajam” tanpa angka, bengkel tidak memiliki dasar yang sama untuk memilih tool, memprogram lintasan, atau menerima hasil.

## Cara kerjanya

Diameter tool menentukan batas geometris paling awal. Secara sederhana, radius ujung yang tersisa pada sudut dalam tidak dapat lebih kecil daripada setengah diameter tool pada bidang yang sedang dipotong. Tool diameter 10 mm, misalnya, memiliki radius 5 mm; tool itu tidak akan menghapus material sampai ke pojok dengan radius 2 mm dalam satu lintasan biasa. Contoh ini adalah hubungan geometri, bukan janji bahwa radius aktual pasti tepat 5 mm.

Program CAM mengubah geometri menjadi lintasan pusat tool. Pada *inside profile*, pusat tool harus berjarak dari dinding sebesar radius tool ditambah kompensasi yang diperlukan. Kompensasi dapat berasal dari geometri tool, keausan, defleksi, runout, penyelesaian permukaan, dan koreksi hasil ukur. Jika kompensasi dimasukkan dua kali—di gambar sekaligus di offset kontrol—ukuran dapat bergeser.

Urutan kerjanya biasanya seperti ini:

1. Anda menetapkan radius, kedalaman, datum, dan toleransi pada gambar.
2. Programmer memilih tool yang dapat masuk ke fitur tersebut dan menyusun lintasan CAM.
3. Operator mengatur tool offset, benda kerja, kecepatan pemakanan, serta strategi roughing dan finishing sesuai prosedur mesin.
4. Pemeriksa mengukur radius dan dimensi terkait dengan alat ukur yang sesuai terhadap datum yang benar.

Router sering dipilih untuk panel atau material nonlogam dan dapat memakai bit berujung datar, sedangkan milling menangani konfigurasi tool dan material yang lebih beragam. Namun nama mesin saja tidak cukup untuk menentukan radius minimum. Panjang potong, kekakuan penjepitan, akses ke sudut, dan kondisi tool dapat memaksa penggunaan diameter yang lebih besar. Minta bengkel menyatakan tool aktual dan operasi yang direncanakan, bukan hanya jenis mesinnya.

## Faktor yang mengubah hasil

Beberapa faktor berikut perlu masuk ke percakapan desain sebelum ukuran dikunci.

- **Diameter dan bentuk tool.** Ball nose, bull nose, dan flat end mill meninggalkan profil berbeda. Radius nominal tool juga bukan satu-satunya pengaruh; profil ujung dan bagian tool yang benar-benar menyentuh material ikut menentukan.
- **Kedalaman dan panjang menjulur.** Tool yang menjulur jauh lebih mudah mengalami defleksi. Pada sudut dalam yang dalam, bengkel mungkin memilih tool kecil bertahap atau operasi tambahan, dengan konsekuensi waktu dan risiko berbeda.
- **Material dan kondisi benda kerja.** Kekerasan, serat, panas, serta kecenderungan burr memengaruhi hasil tepi. Jangan menyamakan kemampuan pada aluminium, baja, plastik, dan kayu hanya karena ukuran toolnya sama.
- **Penjepitan dan datum.** Gerak benda kerja atau datum yang tidak konsisten dapat tampak seperti radius salah. Titik nol dan permukaan acuan harus tertulis dan dapat diakses untuk pemeriksaan.
- **Roughing, finishing, dan keausan.** Lintasan pengasaran dapat menyisakan stok untuk finishing. Tool aus dapat mengubah ukuran dan kualitas permukaan; penggantian tool harus mengikuti prosedur dan dicatat.
- **Toleransi yang diminta.** Toleransi radius, lebar fitur, kedalaman, dan posisi saling berhubungan. Toleransi sempit tanpa metode ukur dan bukti kapabilitas hanya memindahkan ketidakpastian ke tahap inspeksi.

Kawan Bengkel-las.co.id, tanyakan juga apakah radius itu benar-benar bekerja sebagai clearance untuk komponen pasangan. Bila jawabannya ya, tentukan celah minimum dan kondisi terburuk dari kedua komponen. Bila radius hanya mencegah pojok tajam, radius lebih besar dengan toleransi yang wajar sering memberi ruang proses lebih aman—tetapi keputusan itu tetap harus disetujui pemilik desain.

## Contoh keputusan praktis

Gunakan tabel berikut sebagai cara membingkai keputusan, bukan sebagai katalog batas mesin.

| Situasi pada gambar | Pilihan desain awal | Yang harus dikonfirmasi |
| --- | --- | --- |
| Sudut dalam tidak menerima komponen lain | Beri radius yang selaras dengan tool standar bengkel | Diameter tool, kualitas tepi, dan toleransi radius |
| Ada pin atau sudut pasangan yang harus masuk | Tentukan radius dan clearance dari geometri kedua komponen | Toleransi rakitan, datum, dan metode pemeriksaan |
| Radius yang diminta lebih kecil dari tool yang tersedia | Tambahkan relief, pecah operasi, atau ubah radius | Tool alternatif, akses, biaya/waktu proses, dan persetujuan desain |
| Dinding tipis berada dekat sudut | Perbesar radius atau beri jarak dari tepi | Kekakuan benda kerja dan risiko getaran/defleksi |
| Radius tidak kritis tetapi gambar meminta siku tajam | Tulis radius minimum atau catatan proses yang jelas | Definisi penerimaan dan siapa yang menyetujui penyimpangan |

Contoh bersyarat: bila CAD menunjukkan sudut 2 mm tetapi bengkel hanya dapat menjangkau dengan tool radius 4 mm, jangan meminta operator “mengakali” offset. Minta tiga opsi tertulis: mengubah radius menjadi 4 mm atau lebih, menambahkan *dog-bone relief* pada area yang tidak terlihat, atau memindahkan fitur ke proses finishing lain. Pilih berdasarkan fungsi, akses inspeksi, dan persetujuan revisi gambar.

Saat membuat permintaan penawaran, sertakan file dengan unit, material, ketebalan, datum, radius minimum, toleransi dimensi, dan fitur yang kritis. Lampirkan pertanyaan: “Tool diameter dan strategi finishing apa yang akan dipakai untuk sudut ini?” Jawaban tersebut lebih berguna daripada janji umum bahwa semua detail CAD dapat dipotong.

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah menganggap ukuran yang tampak di layar CAD sama dengan bentuk aktual. Periksa penampang sudut dan tampilkan radius sebagai dimensi, bukan hanya zoom visual. Kesalahan kedua adalah menyalin toleransi dari proyek lain. Toleransi perlu dikaitkan dengan fungsi, material, mesin, dan alat ukur pada pekerjaan sekarang.

Kesalahan ketiga adalah melupakan kompensasi. Tetapkan siapa yang mengendalikan *tool radius compensation*: geometri CAM, offset kontrol, atau kombinasi yang didokumentasikan. Lakukan satu pemeriksaan silang pada simulasi dan lembar setup agar koreksi tidak diterapkan ganda.

Kesalahan keempat adalah memeriksa radius dengan alat yang tidak cocok atau dari datum yang salah. Sebelum produksi, sepakati metode ukur—misalnya templat, pin ukur, CMM, atau alat lain yang memang mampu membaca fitur tersebut—serta lokasi titik ukur. Hasil ukur tanpa identitas datum dan kondisi benda kerja sulit dipakai untuk keputusan penerimaan.

Checklist singkat sebelum rilis gambar:

- Apakah setiap sudut dalam memiliki radius angka atau catatan minimum yang jelas?
- Apakah radius tersebut lebih besar atau sama dengan radius efektif tool yang disepakati?
- Apakah diameter tool, kedalaman potong, dan akses sudah dikonfirmasi bengkel?
- Apakah toleransi radius dan dimensi pasangannya memiliki fungsi yang jelas?
- Apakah datum, metode ukur, dan pihak yang menyetujui penyimpangan tertulis?
- Apakah revisi desain diperlukan bila relief atau operasi tambahan dipilih?

## Jalan pintas yang tampak praktis tetapi berisiko

Shortcut yang sering muncul adalah meminta bengkel memakai tool sekecil mungkin agar semua sudut terlihat “tajam”, tanpa memeriksa panjang menjulur dan kekakuannya. Tool kecil memang dapat mengurangi radius geometris, tetapi belum tentu aman atau stabil untuk kedalaman dan material yang diminta. Hasilnya dapat berupa waktu proses lebih panjang, permukaan tidak konsisten, atau dimensi yang perlu dikoreksi—tanpa ada dasar penerimaan yang jelas.

Alternatif yang lebih dapat dipertanggungjawabkan adalah mengunci fungsi dahulu, lalu meminta bengkel mengusulkan tool dan urutan operasi. Jika fungsi tidak memerlukan radius kecil, izinkan radius yang lebih besar. Jika fungsi sangat bergantung pada sudut, tandai fitur sebagai kritis, tetapkan toleransi dan metode ukur, dan minta persetujuan teknis atas kemampuan mesin aktual. Sobat Bengkel-las.co.id, berhenti sebelum pemotongan bila gambar, CAM, dan setup menyebut radius atau datum yang berbeda.

## Kesimpulan dan langkah berikutnya

Radius sudut dalam pada CNC router dan CNC milling pada dasarnya dibatasi oleh radius efektif tool bulat, kemudian dipengaruhi kedalaman, material, penjepitan, strategi CAM, keausan, dan kompensasi. Karena itu, jangan menulis sudut siku tanpa radius dan jangan menjanjikan toleransi sebelum tool serta metode ukur disepakati.

Langkah Anda berikutnya: tandai semua sudut dalam pada gambar, tulis radius dan toleransinya, lalu kirimkan pertanyaan tool-dan-proses kepada bengkel. Minta konfirmasi tertulis atas tool aktual, datum setup, strategi finishing, dan metode inspeksi. Jika ada konflik antara fungsi dan kemampuan tool, revisi geometri atau dapatkan tinjauan teknis yang berwenang sebelum pekerjaan dimulai. Untuk meninjau kembali ilustrasi yang ditugaskan, buka [aset CNC Milling 4](/wp-content/uploads/2019/11/CNC-Milling-4.jpg). Aturan operasinya sederhana: radius yang terlihat di CAD harus dapat diterjemahkan menjadi tool, lintasan, dan bukti ukur yang nyata.
