---
article_id: CUT-06-05
title: "Workholding CNC Milling: Vice, Fixture, dan Soft Jaw"
slug: "workholding-cnc-milling"
description: "Memilih operasi milling untuk komponen berdimensi, pocket, slot, kontur, dan permukaan presisi."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-11-27"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-06
primary_intent: "Memilih penahan benda milling"
reader_community: "Bengkel-las.co.id"
reader_address: "Sobat Bengkel-las.co.id"
final_route: "/artikel/workholding-cnc-milling.html"
technical_review: required
sources:
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026"
  - "https://www.iso.org/standard/83335.html"
---

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** `LOCAL-014`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi CNC Milling 8](/wp-content/uploads/2019/11/CNC-Milling-8.jpg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `CNC Milling 8` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-014]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

# Workholding CNC Milling: Vice, Fixture, dan Soft Jaw

Halo, Sobat Bengkel-las.co.id! Kesalahan memilih penahan benda kerja sering tampak sepele: benda terlihat sudah terjepit, tetapi datum bergeser, bagian tipis melenting, atau pahat tidak punya ruang aman. Akibatnya ukuran pocket, slot, kontur, dan permukaan akhir ikut berubah. Jadi, pertanyaannya bukan “vice mana yang paling kuat?”, melainkan “penahan mana yang menjaga datum, akses pahat, dan kestabilan benda untuk operasi ini?”

Jawaban singkatnya: gunakan **vice** untuk pekerjaan umum dan pergantian benda yang cepat; gunakan **fixture** ketika orientasi, datum, atau pengulangan harus dikendalikan; gunakan **soft jaw** (rahang lunak yang dibentuk mengikuti kontur benda) ketika rahang standar akan menutup fitur, merusak permukaan, atau tidak memberi dukungan yang cukup. Pilihan akhir tetap bergantung pada gambar kerja, material, toleransi, urutan operasi, dan bukti uji penjepitan. [NEEDS PROJECT REVIEW: gaya penjepitan, toleransi, dan batas deformasi belum tersedia.]

![Ilustrasi CNC Milling 8](/wp-content/uploads/2019/11/CNC-Milling-8.jpg)

*Aset lokal proyek untuk ilustrasi; gambar ini bukan dokumentasi proyek tertentu.*

## Definisi dan batas objek

Workholding adalah seluruh cara menempatkan dan menahan benda selama pemotongan milling: bidang dudukan, locator atau penentu posisi, clamp, jaw, baut, serta antarmuka ke meja mesin. **Vice** biasanya menyediakan rahang tetap dan bergerak dalam satu unit. **Fixture** adalah rakitan penahan yang dirancang untuk datum dan orientasi benda tertentu. **Soft jaw** adalah rahang yang masih dapat dimachining agar bidang kontak mengikuti bentuk benda.

Ketiganya bukan pengganti satu sama lain secara mutlak. Vice dapat dipasang pada fixture plate; soft jaw dapat menjadi isi sebuah vice; fixture dapat memakai clamp, locator, dan stop sekaligus. Batas artikel ini khusus workholding untuk CNC milling, bukan clamp panel router atau rancangan struktur las. Jika komponen memiliki persyaratan sambungan, material, atau inspeksi khusus, dokumen proyek dan peninjauan teknis tetap menjadi acuan. [NEEDS TECHNICAL REVIEW: datum, toleransi, dan gaya pemotongan harus ditetapkan dari gambar kerja.]

## Cara kerjanya

Mulai dari datum pada gambar, bukan dari bentuk alat yang tersedia. Tentukan bidang atau lubang mana yang menjadi referensi, lalu rencanakan urutan: benda duduk pada permukaan yang stabil, locator menahan gerak yang tidak diinginkan, dan clamp memberi gaya ke arah dudukan. Gaya harus menekan benda ke penopang; bila arahnya mengangkat atau memutar benda, pahat dapat menariknya keluar dari posisi.

Setelah itu periksa jalur pahat. Rahang, baut, stop, dan chip pocket tidak boleh berada di lintasan pahat atau menghalangi pengukuran. Untuk benda tinggi atau tipis, tambahkan dukungan di dekat area pemotongan. Untuk fitur yang harus dikerjakan dari beberapa sisi, catat bagaimana datum dipulihkan pada setiap setup; jangan mengandalkan “nanti disetel lagi”.

Pada vice, rahang standar cocok bila bidang luar benda cukup paralel dan akses pemotongan tidak tertutup. Fixture lebih tepat ketika stop, locator, dan orientasi perlu berulang pada banyak benda. Soft jaw berguna bila permukaan kontak perlu mengikuti radius atau profil tertentu. Machining pada soft jaw sendiri harus meninggalkan area kontak dan ruang chip yang memadai; detail ukuran, kedalaman, dan torsi tidak boleh ditebak tanpa data alat serta benda. [NEEDS SETUP REVIEW: verifikasi kontak aktual dan nilai pengencangan oleh penanggung jawab mesin.]

## Faktor yang mengubah hasil

**Geometri dan akses.** Pocket dalam, slot dekat tepi, atau kontur di empat sisi dapat membuat rahang standar menutup area yang seharusnya dipotong. Balik benda mungkin membuka akses, tetapi juga memperkenalkan sumber salah orientasi. Fixture dengan locator yang jelas dapat mengurangi kebingungan itu.

**Kekakuan benda.** Pelat tipis, dinding berongga, atau benda dengan area kontak kecil membutuhkan penopang yang menyebarkan gaya. Penjepitan terlalu dekat tepi dapat meninggalkan bekas; terlalu jauh dapat membiarkan bagian kerja bergetar. Jangan menyimpulkan bahwa gaya lebih besar selalu lebih aman.

**Material dan permukaan.** Benda lunak dan permukaan jadi memerlukan perlindungan dari bekas rahang. Soft jaw atau shim yang sesuai dapat membantu, tetapi kompatibilitas material dan kebersihannya perlu diperiksa pada kondisi nyata. Catat identitas material dan perubahan yang disetujui bila komponen masuk paket fabrikasi terkendali; praktik dokumentasi dan persetujuan substitusi dibahas dalam kerangka mutu fabrikasi ISO 3834-6:2024, bukan sebagai bukti bahwa satu setup tertentu sudah lulus ([ISO 3834-6:2024](https://www.iso.org/standard/83335.html)).

**Produksi dan pengulangan.** Satu benda prototipe mungkin efisien dengan vice dan stop sederhana. Batch berulang dapat membenarkan fixture khusus bila waktu loading, orientasi, dan pemeriksaan menjadi beban. Keputusan itu harus dibandingkan dengan waktu membuat, merawat, dan menyimpan fixture; jangan menganggap fixture selalu lebih murah.

**K3 dan lingkungan kerja.** Penahan harus diperiksa sebelum mesin dijalankan: tidak ada komponen longgar, kunci tertinggal, atau chip di bawah dudukan. Pengendalian bahaya di tempat kerja merupakan kewajiban sistemik, bukan sekadar memakai APD; dasar umumnya ada pada UU No. 1 Tahun 1970 dan aturan turunannya yang statusnya perlu dicek pada sumber resmi ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), [Permenaker No. 11 Tahun 2026](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026)). Catatan ini tidak menentukan torsi clamp, interlock, atau prosedur darurat; minta review K3 yang memahami mesin dan lokasi Anda.

Sobat Bengkel-las.co.id, berhenti sebelum trial cut jika Anda belum dapat menjawab: apa yang menahan gaya potong ke arah X, Y, dan Z; datum mana yang diukur; dan ke mana chip akan keluar? Tiga jawaban itu lebih berguna daripada meniru setup dari foto.

Untuk menyiapkan istilah dan alur kerja dasar, Anda dapat mulai dari [beranda Bengkel-las.co.id](/), lalu kembali ke panduan ini setelah gambar kerja siap.

## Contoh keputusan praktis

Gunakan tabel ini sebagai penyaring awal, bukan persetujuan proses:

| Kondisi komponen dan pekerjaan | Pilihan awal | Alasan yang perlu diverifikasi |
|---|---|---|
| Balok dengan dua bidang luar paralel, satu orientasi, jumlah kecil | Vice dengan stop | Akses pahat dan bidang datum tetap terbuka |
| Banyak benda dengan datum dan orientasi sama | Fixture dengan locator dan stop | Pengulangan loading lebih mudah diperiksa |
| Profil luar tidak beraturan atau permukaan jadi mudah tergores | Soft jaw | Kontak dapat mengikuti profil dan melindungi permukaan |
| Pocket dekat rahang atau pemotongan hampir mengelilingi benda | Soft jaw atau fixture | Rahang standar berpotensi menghalangi jalur pahat |
| Benda tipis yang melenting saat dikencangkan | Penopang tambahan plus penjepitan terkendali | Deformasi harus diukur, bukan diasumsikan hilang |

Contoh terakhir sengaja tidak memberi angka gaya atau toleransi. Nilainya berasal dari material, ketebalan, luas kontak, alat potong, dan persyaratan gambar. [NEEDS PROCESS EVIDENCE: lakukan uji penjepitan dan pengukuran pada benda representatif sebelum produksi.]

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah mengencangkan vice sampai benda “tidak bergerak” tanpa memeriksa deformasi. Ukur bidang kritis sebelum dan sesudah penjepitan bila toleransinya ketat. Kedua, menjadikan ujung benda sebagai datum tanpa memastikan ujung itu sudah dikerjakan atau benar-benar lurus. Ketiga, menaruh clamp di atas area yang akan dipotong lalu berharap pahat dapat menghindarinya.

Kesalahan berikutnya adalah mengabaikan chip. Chip yang terjebak di bawah benda mengubah tinggi datum; chip di antara soft jaw dan benda dapat membuat kontak semu. Bersihkan, pasang, lalu lakukan pemeriksaan visual dan sentuh yang aman sebelum siklus. Jangan mengukur atau membersihkan ketika spindle masih berputar.

Terakhir, fixture sering dibuat tanpa identitas: tidak ada penanda orientasi, nomor revisi, atau catatan benda yang kompatibel. Untuk pekerjaan berulang, simpan sketsa datum, daftar komponen, dan hasil pemeriksaan awal. Jika ada perubahan locator atau jaw, perlakukan sebagai perubahan proses yang memerlukan persetujuan teknis, bukan improvisasi operator.

## Jalan pintas yang tampak praktis

Jalan pintas yang umum adalah memakai vice standar untuk semua bentuk karena setup-nya cepat. Ia dapat gagal ketika rahang menutup fitur, gaya menjepit melenturkan dinding, atau benda harus dibalik tanpa datum pemulihan. Alternatif yang lebih andal adalah menguji satu setup sederhana dengan benda representatif, menandai titik kontak dan jalur pahat, lalu beralih ke soft jaw atau fixture hanya bila bukti menunjukkan kebutuhan itu. Keputusan tersebut harus dicatat bersama batas toleransi dan hasil inspeksi; tanpa data itu, klaim “setup aman” belum dapat diterima.

Kawan Bengkel-las.co.id, bila lembar setup perlu dibagikan ke operator berikutnya, sertakan rujukan artikel ini agar revisi, datum, dan batas pemeriksaannya tidak terlepas dari konteks. Berkas ilustrasi yang ditetapkan dapat diperiksa sebagai [aset gambar lokal](/wp-content/uploads/2019/11/CNC-Milling-8.jpg), tanpa menjadikannya bukti kondisi mesin atau hasil pemotongan.

## Kesimpulan dan langkah berikutnya

Vice adalah titik awal serbaguna, fixture memberi pengulangan dan orientasi, sedangkan soft jaw memberi kontak yang disesuaikan. Pilih berdasarkan datum, akses pahat, kekakuan, perlindungan permukaan, dan jumlah pengulangan—bukan berdasarkan kekuatan nominal alat.

Langkah berikutnya: ambil gambar kerja, tandai datum dan fitur yang harus terbuka, buat sketsa arah gaya serta jalur pahat, kemudian minta operator berwenang melakukan dry run dan inspeksi benda pertama. Simpan hasilnya sebagai instruksi setup. Jika gaya penjepitan, deformasi, atau status aturan K3 belum terbukti, tinggalkan `[NEEDS PROJECT REVIEW]` dan jangan lanjut ke produksi sampai penanggung jawab teknis menyetujuinya.

Teman Bengkel-las.co.id, operating rule-nya sederhana: tidak ada siklus pemotongan sebelum datum, kontak penahan, jalur pahat, dan pemeriksaan keselamatan dapat ditunjukkan di meja mesin.
