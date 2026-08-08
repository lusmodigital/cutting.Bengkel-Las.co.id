---
article_id: CUT-06-02
title: "Face Milling, Pocketing, Slotting, dan Contouring: Apa Bedanya?"
slug: "jenis-operasi-cnc-milling"
description: "Memilih operasi milling untuk komponen berdimensi, pocket, slot, kontur, dan permukaan presisi."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-11-18"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-06
primary_intent: "Memilih operasi milling"
reader_community: "Bengkel-las.co.id"
reader_address: "Teman Bengkel-las.co.id"
final_route: "/artikel/jenis-operasi-cnc-milling.html"
technical_review: required
sources:
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200"
---

# Face Milling, Pocketing, Slotting, dan Contouring: Apa Bedanya?

Halo, Teman Bengkel-las.co.id! Perbedaan keempat operasi ini terutama terletak pada **permukaan atau fitur yang hendak dibuat**, bukan pada nama program CNC-nya. Face milling meratakan bidang terbuka, pocketing mengosongkan area di dalam batas tertutup, slotting membuat alur, sedangkan contouring mengikuti garis luar atau profil.

Urutan memilihnya sederhana: tandai fitur pada gambar kerja, tentukan apakah area yang dipotong terbuka atau tertutup, lalu cek akses pahat dan toleransinya. Satu komponen dapat memakai beberapa operasi sekaligus. Kecepatan, pemakanan, kedalaman potong, jenis pahat, dan strategi lintasan tetap harus ditetapkan dari material, mesin, pahat, serta instruksi kerja yang disetujui—bukan ditebak dari istilah operasi. Jika Anda baru memetakan proses, gunakan [beranda Bengkel-las.co.id](/) untuk kembali ke konteks layanan dan istilah dasar sebelum menyusun work order.

![Ilustrasi CNC Milling 1](/wp-content/uploads/2019/11/CNC-Milling-1.jpg)

Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu. Anda dapat membuka [aset lokal ilustrasi](/wp-content/uploads/2019/11/CNC-Milling-1.jpg) bila perlu memeriksa berkas medianya.

## Definisi dan batas objek

Dalam artikel ini, “operasi” berarti cara menggerakkan pahat relatif terhadap benda kerja untuk menghasilkan fitur tertentu. Face milling biasanya memakai sisi dan bagian bawah pahat untuk menyapu bidang atas atau bidang referensi. Hasil yang dicari adalah kerataan, ukuran keseluruhan, atau datum yang dapat dipakai pada operasi berikutnya.

Pocketing berarti material di dalam kontur tertutup dihilangkan bertahap. Area itu bisa berupa cekungan, rumah komponen, atau rongga yang memiliki dasar. Slotting adalah kasus yang lebih spesifik: alur memanjang dengan lebar tertentu, sering kali menembus atau berhenti pada kedalaman tertentu. Contouring mengikuti kurva atau garis luar sehingga profil samping benda kerja terbentuk.

Batasnya penting. Artikel ini tidak memilih merek, diameter, geometri, atau grade end mill; tidak menghitung parameter potong; dan tidak memutuskan apakah mesin 3-axis, 4-axis, atau 5-axis yang wajib dipakai. Semua keputusan itu bergantung pada gambar kerja, material aktual, kapasitas mesin, dan evaluasi teknis. Jika dokumen belum menetapkan datum, toleransi, atau kondisi permukaan, hentikan pemrograman dan minta klarifikasi—[NEEDS TECHNICAL REVIEW: datum, toleransi, dan material benda kerja].

## Cara kerjanya

Mulailah dari gambar kerja, bukan dari menu CAM. Lingkari bidang yang harus rata, area yang harus kosong, alur, dan profil luar. Setelah itu tetapkan sistem koordinat serta permukaan referensi. Face milling sering ditempatkan lebih awal untuk membuat bidang acuan; pocketing dan slotting kemudian mengerjakan fitur internal; contouring dapat menjadi pemotongan profil akhir atau semi-finishing, bergantung pada allowance yang disepakati.

Pada setiap operasi, programmer menentukan titik masuk, arah lintasan, jumlah tingkat kedalaman, dan cara keluar dari material. Simulasi memeriksa tabrakan pahat, ragum, fixture, serta sisa material. Operator lalu melakukan setup, mengukur offset sesuai prosedur bengkel, dan menjalankan percobaan yang disetujui. Pemeriksaan hasil membandingkan ukuran dan kondisi permukaan dengan gambar kerja; jangan menganggap simulasi sebagai bukti bahwa komponen sudah memenuhi spesifikasi.

Untuk bahan kimia seperti coolant atau cairan pembersih, identitas produk dan lembar data keselamatan (SDS) harus tersedia dari pemasok. OSHA 29 CFR 1910.1200 dapat menjadi contoh konsep komunikasi bahaya melalui label dan SDS, tetapi aturan AS itu bukan hukum Indonesia; gunakan ketentuan K3 Indonesia dan instruksi produk yang berlaku di lokasi kerja ([rujukan OSHA](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200)).

## Faktor yang mengubah hasil

**Bentuk fitur.** Bidang terbuka mengarah ke face milling. Batas tertutup dengan dasar mengarah ke pocketing. Alur sempit atau memanjang mengarah ke slotting. Garis luar kompleks, radius, atau permukaan samping mengarah ke contouring. Bila satu fitur memiliki sudut dalam kecil, operasi dasarnya mungkin tetap pocketing, tetapi radius sudut yang dapat dicapai harus diperiksa.

**Toleransi dan permukaan.** Toleransi ukuran, kerataan, paralelisme, dan kekasaran dapat mengubah urutan roughing, semi-finishing, dan finishing. Jangan menjanjikan “presisi” hanya karena mesin CNC digunakan. Nilai toleransi dan metode inspeksi harus berasal dari gambar kerja atau spesifikasi proyek yang disahkan.

**Akses dan penjepitan.** Pahat harus mencapai area tanpa menyentuh fixture. Dinding tipis dapat bergetar; benda kerja yang menonjol jauh dari penjepit dapat berubah posisi. Jika profil memerlukan orientasi lain, kebutuhan setup tambahan atau sumbu berputar perlu ditinjau oleh programmer dan penanggung jawab proses.

**Material dan kondisi mesin.** Kekerasan, kondisi permukaan awal, kekakuan spindle, runout, coolant, serta kemampuan kontrol menentukan batas aman. Parameter potong tidak boleh disalin lintas material atau mesin. Catat revisi program dan hasil pengukuran agar perubahan dapat ditelusuri.

**Keselamatan dan lingkungan kerja.** Pelindung mesin, penguncian benda kerja, pengelolaan serpihan, kabut coolant, dan prosedur darurat harus dinilai terhadap mesin serta lokasi yang sebenarnya. Artikel ini tidak memberikan setelan ventilasi, PPE, atau batas paparan; minta tinjauan K3 kompeten bila risiko belum teridentifikasi.

## Contoh keputusan praktis

Gunakan tabel berikut sebagai pemetaan awal, bukan pengganti gambar kerja atau review program.

| Fitur pada gambar | Operasi utama | Pertanyaan pemeriksaan |
|---|---|---|
| Bidang atas luas yang menjadi datum | Face milling | Apakah bidang itu harus rata terhadap datum lain, dan apakah ada allowance? |
| Cekungan dengan batas tertutup dan dasar | Pocketing | Apakah pahat dapat mencapai seluruh sudut dan bagaimana sisa material di dasar diperiksa? |
| Alur lurus dengan lebar tertentu | Slotting | Apakah alur tembus, buntu, atau memiliki radius ujung yang ditentukan? |
| Profil luar mengikuti kurva atau garis | Contouring | Apakah ukuran profil diukur pada titik kontrol yang benar dan apakah diperlukan finishing pass? |

Bayangkan gambar kerja memiliki bidang referensi, satu rongga persegi, satu alur tembus, dan profil luar melengkung. Rencana awalnya dapat berupa face milling pada bidang referensi, pocketing pada rongga, slotting pada alur, lalu contouring untuk profil. Urutan aktual dapat berubah jika penjepitan, deformasi, atau akses pahat membuat langkah tersebut tidak aman atau tidak dapat diukur. Sobat Bengkel-las.co.id, tuliskan alasan perubahan itu pada lembar setup agar operator berikutnya tidak menebak.

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah menyebut semua pemakanan sebagai “contouring”. Periksa apakah pahat benar-benar mengikuti batas luar atau hanya menyapu area. Kesalahan kedua adalah menganggap pocketing sama dengan slotting karena keduanya menghilangkan material di dalam batas. Tanyakan: apakah lebar alur merupakan ukuran fitur yang dikendalikan, atau area luas dengan dasar yang harus diratakan?

Kesalahan ketiga adalah memilih operasi dari bentuk tampak atas tanpa memeriksa kedalaman dan akses. Buka simulasi, tampilkan fixture, dan pastikan tidak ada dinding yang terlewat. Kesalahan keempat adalah memakai parameter program lama tanpa mencocokkan material, pahat, coolant, dan kondisi mesin. Bandingkan kartu proses dengan work order dan lakukan pengukuran awal.

Kesalahan terakhir adalah menganggap hasil visual cukup. Tetapkan alat ukur, titik ukur, frekuensi pemeriksaan, serta kriteria penerimaan sebelum produksi. Jika toleransi atau material belum jelas, simpan marker [NEEDS INSPECTION BASIS] dan minta persetujuan teknis.

## Jalan pintas yang tampak menghemat waktu

Shortcut yang sering menggoda adalah memakai satu operasi “serba bisa” untuk seluruh fitur, misalnya memaksa pocketing mengerjakan alur dan profil sekaligus. Ini dapat menambah lintasan tidak perlu, menyulitkan kontrol ukuran, dan membuat pemeriksaan fitur menjadi kabur. Alternatif yang lebih dapat ditelusuri adalah memisahkan operasi berdasarkan fungsi fitur, memberi nama toolpath yang jelas, lalu memverifikasi simulasi dan ukuran pada setiap tahap. Penggabungan hanya layak dipilih bila programmer dapat menunjukkan bahwa akses, beban pahat, toleransi, dan inspeksinya tetap terkendali.

## Kesimpulan dan langkah berikutnya

Face milling meratakan bidang, pocketing mengosongkan area tertutup, slotting membuat alur, dan contouring membentuk profil luar. Satu komponen boleh memakai keempatnya; gambar kerja, akses, penjepitan, material, toleransi, serta kemampuan mesinlah yang menentukan urutan dan parameter.

Sebelum membuat program, minta gambar kerja berisi datum, toleransi, material, dan persyaratan permukaan. Tandai setiap fitur dengan operasi kandidat, lalu minta programmer serta penanggung jawab K3 meninjau setup, simulasi, dan rencana inspeksi. Kawan Bengkel-las.co.id, jadikan aturan kerja ini sebagai batas: bila bukti teknis atau kondisi lapangan belum lengkap, jangan mengisi celah dengan asumsi—tunda pemotongan sampai review kompeten selesai.

<!-- BEGIN MANAGED IMAGE PLAN
Image ID: LOCAL-015
Source type: local
Placement: after the opening, before the first detailed H2
**Exact Markdown to insert:** `![Ilustrasi CNC Milling 1](/wp-content/uploads/2019/11/CNC-Milling-1.jpg)`
Caption/credit: Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
Selection basis: filename/source metadata identifies CNC Milling 1 as relevant content media; no pixels were inspected.
Hard boundary: do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
END MANAGED IMAGE PLAN -->
