---
article_id: CUT-06-02
title: "Face Milling, Pocketing, Slotting, dan Contouring: Apa Bedanya?"
slug: "jenis-operasi-cnc-milling"
description: "Memilih operasi milling untuk komponen berdimensi, pocket, slot, kontur, dan permukaan presisi."
status: draft
publication_date: "2025-11-18"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-06
primary_intent: "Memilih operasi milling"
reader_community: "Bengkel-las.co.id"
reader_address: "Teman Bengkel-las.co.id"
final_route: "/artikel/jenis-operasi-cnc-milling.html"
technical_review: required
writing_contract_version: "native-id-v2"
sources:
  - "https://www.iso.org/standard/83335.html"
  - "https://www.iso.org/standard/77795.html"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026"
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910.252"
  - "https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015"
  - "https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021"
---

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** `LOCAL-015`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi CNC Milling 1](/wp-content/uploads/2019/11/CNC-Milling-1.jpg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `CNC Milling 1` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-015]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

# Face Milling, Pocketing, Slotting, dan Contouring: Apa Bedanya?

Halo, Teman Bengkel-las.co.id! Face milling, pocketing, slotting, dan contouring adalah kelompok operasi CNC milling (pemesinan kendali numerik) yang menjawab bentuk berbeda. Face milling meratakan permukaan; pocketing mengosongkan area; slotting membuat alur; contouring mengikuti kontur luar atau dalam. Pilihan operasi harus mengikuti fungsi, datum, material, toleransi, dan cara benda dijepit—bukan nama operasi semata.

Jawaban singkatnya: tentukan permukaan atau fitur yang ingin dibuat, tetapkan titik acuan dan kriteria ukur, lalu minta programmer atau operator berwenang memeriksa urutan serta bukti uji. Artikel ini mengelompokkan operasi, bukan memilih end mill atau menetapkan parameter universal. [NEEDS PROJECT REVIEW: material, alat, toleransi, dan acceptance basis belum tersedia.]

![Ilustrasi CNC Milling 1](/wp-content/uploads/2019/11/CNC-Milling-1.jpg)

*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*


## Bedakan tujuan tiap operasi

**Face milling** mengurangi ketidakrataan pada bidang yang relatif terbuka. Hasil yang dicari dapat berupa datum (acuan geometri), ketebalan, atau permukaan pasangan yang dapat diukur. Lebar lintasan, penyangga, kekakuan, dan urutan pemakanan memengaruhi hasil; jangan menjanjikan kerataan dari nama operasi.

**Pocketing** menghilangkan material di dalam batas tertutup untuk membentuk area lebih rendah. Gambar perlu menyatakan kedalaman, radius sudut, lantai, dinding, dan toleransi. **Slotting** membuat alur memanjang atau fitur sempit; lebar, kedalaman, radius ujung, dan cara membersihkan chip harus jelas. **Contouring** mengikuti batas luar atau dalam untuk ukuran, profil, atau pemisahan material; titik masuk dan urutan dapat memengaruhi bekas pada tepi.

Teman Bengkel-las.co.id, satu fitur dapat membutuhkan beberapa operasi. Face milling mungkin mendahului pocketing agar permukaan acuan stabil; roughing (pengasaran awal) dapat mendahului finishing (pemesinan akhir). Urutan akhir harus berasal dari gambar dan rencana proses, bukan tebakan.

## Cara kerja dan antarmuka

Programmer menerjemahkan model atau gambar menjadi jalur alat, memilih datum, menetapkan penjepitan, lalu memeriksa simulasi atau lintasan uji. Operator memeriksa benda, alat, coolant bila dipakai, dan kondisi mesin. Pemeriksa mengukur fitur terhadap gambar serta acceptance basis (dasar penerimaan). WPS (spesifikasi prosedur pengelasan), sertifikat personel, laporan NDT (pengujian tak merusak), dan hasil pemesinan adalah bukti berbeda.

Paket fabrikasi terkendali sebaiknya memuat revisi, material, dimensi, toleransi, urutan, titik hold, inspeksi, dan deviasi yang disetujui ([ISO 3834-6:2024](https://www.iso.org/standard/83335.html), [BSN](https://pesta.bsn.go.id/produk/detail/12882-sni17292020)). Jangan menganggap model 3D otomatis memuat toleransi atau fungsi semua permukaan.

## Faktor yang mengubah hasil

Material, kekerasan, batch, coating, ketebalan, kerataan, kekakuan benda, penjepitan, alat, pendingin, dan kondisi spindle memengaruhi getaran, panas, burr (tonjolan tajam), dan ukuran. Pilih alat serta parameter dari manual mesin, rekomendasi pembuat alat, uji, dan dokumen proyek; artikel ini tidak memberi angka putaran atau pemakanan.

Jika coating atau bahan pembersih terlibat, simpan identitas produk dan SDS (lembar data keselamatan). Lembar keselamatan membantu mengenali bahaya, tetapi tidak membuktikan kompatibilitas atau masa simpan tanpa produk dan lingkungan aktual ([ISO 12944-5:2019](https://www.iso.org/standard/77795.html), [OSHA 1910.1200](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200)).

## Contoh keputusan praktis

Gunakan face milling ketika bidang acuan perlu dibuat stabil; gunakan pocketing untuk rongga dengan lantai dan dinding terdefinisi; gunakan slotting untuk alur yang lebarnya kritis; gunakan contouring untuk profil luar atau dalam. Bila fitur saling bertemu, tentukan operasi mana yang menjaga datum dan akses ukur.

Sobat Bengkel-las.co.id, beri status **siap ditinjau**, **karantina**, atau **disetujui bersyarat**. Status harus menyebut revisi, material, alat, dan batas penggunaan. Jangan menyebut hasil “presisi” tanpa pengukuran dan alat yang statusnya dapat dibuktikan.

## Kesalahan umum dan pemeriksaan

Kesalahan umum meliputi memilih operasi dari nama fitur tanpa memeriksa penjepitan, mengabaikan radius sudut, mengukur dari permukaan yang belum stabil, dan mengubah program tanpa revisi. Shortcut “satu operasi untuk semua fitur” dapat meninggalkan lantai bergelombang, dinding miring, atau tepi yang tidak dapat dirakit. Alternatifnya adalah menulis urutan operasi, datum, fitur kritis, titik ukur, dan kondisi berhenti.

Hentikan pekerjaan bila material atau revisi tidak cocok, benda bergerak, alat rusak, ukuran keluar batas, atau guarding dan pengendalian energi tidak tersedia. K3 harus menetapkan kontrol aktual berdasarkan lokasi, energi, ventilasi, api, dan akses; rujukan umum tidak menggantikan prosedur fasilitas ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018), [Permenaker No. 11 Tahun 2026](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026)).

OSHA 1910.252 dapat dibaca sebagai contoh panduan asing tentang pengelasan, pemotongan, dan pekerjaan panas; jarak, izin, atau preskripsinya bukan hukum Indonesia. Untuk pekerjaan milling di fasilitas Anda, penanggung jawab harus memetakan energi listrik dan mekanik, gerakan meja, serpihan, coolant, kebisingan, ventilasi, api, serta keadaan darurat berdasarkan aturan dan prosedur lokal ([OSHA 1910.252](https://www.osha.gov/laws-regs/regulations/standardnumber/1910.252)). Permenaker No. 12 Tahun 2015 juga perlu dibaca dalam konteks pengendalian risiko kerja Indonesia, bukan sebagai daftar parameter mesin yang dapat disalin ([Permenaker No. 12 Tahun 2015](https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015)).

Tambahkan titik berhenti sebelum mengganti alat, membuka pelindung, membersihkan chip, atau memindahkan benda. Pastikan otorisasi restart, komunikasi operator, dan pemeriksaan ulang setelah gangguan tertulis. Tidak ada angka universal untuk jarak aman, durasi pendinginan, atau frekuensi pemeriksaan; tetapkan dari mesin, material, manual, dan penilaian K3 yang disetujui.

Saat membuat urutan operasi, tuliskan fitur yang akan menjadi acuan berikutnya. Misalnya, bidang hasil face milling dapat menjadi datum untuk pocket, tetapi hanya bila kerataan dan posisi telah diperiksa. Slot yang menjadi jalur kabel memerlukan ukuran dan radius yang terkait komponen pasangan. Contouring yang memisahkan part perlu meninggalkan penyangga atau tab bila benda kecil berisiko bergeser; cara melepasnya harus menjaga tepi.

Catat pula kondisi sebelum dan sesudah setiap operasi: nomor program, revisi, alat, material, orientasi, dan hasil ukur. Rekaman ini membantu membedakan masalah geometri dari masalah penjepitan atau keausan alat. Bila hasil menyimpang, karantina part, simpan bukti awal, dan minta keputusan perbaikan dari pihak yang berwenang sebelum mengubah program. Jangan menghapus rekaman atau mencampur part berstatus hold dengan part yang sudah diterima.

## Verifikasi dan serah-terima

Simpan file revisi, daftar fitur, alat dan status verifikasinya, hasil ukur, foto pendukung, serta keputusan penyimpangan. Handover (serah-terima) harus mengaitkan part dengan dokumen dan status diterima atau hold. Scrap (sisa potongan) tidak otomatis boleh dicampur; identitas, kontaminasi, penyimpanan, pengangkutan, dan penerima berwenang menentukan jalurnya ([PP No. 22 Tahun 2021](https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021)).

Menentukan operasi milling berarti menghubungkan bentuk fitur dengan datum, penjepitan, urutan, alat, dan bukti ukur. Langkah berikutnya: tandai fitur pada gambar, minta programmer menyusun urutan face, pocket, slot, atau contour, lalu sepakati titik ukur dan hold point. Gunakan [beranda Bengkel-las.co.id](/) hanya sebagai informasi umum. Aturan operasinya sederhana: bila fungsi, datum, alat, atau acceptance basis belum jelas, tahan program dan minta review kompeten. Catatan ini berlaku untuk setiap revisi dan setiap part yang diproses.
