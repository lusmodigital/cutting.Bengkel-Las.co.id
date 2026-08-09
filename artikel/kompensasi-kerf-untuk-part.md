---
article_id: CUT-08-02
title: "Kompensasi Kerf untuk Part yang Saling Pasang"
slug: "kompensasi-kerf-untuk-part"
description: "Menulis target dimensi dan toleransi yang realistis serta mengantisipasi kerf dan kompensasi."
status: draft
publication_date: "2026-01-01"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-08
primary_intent: "Menyetel ukuran pasangan komponen"
reader_community: "Bengkel-las.co.id"
reader_address: "Teman Bengkel-las.co.id"
final_route: "/artikel/kompensasi-kerf-untuk-part.html"
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
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910.252"
  - "https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026"
  - "https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015"
  - "https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021"
  - "https://www.iso.org/standard/80209.html"
---

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

# Kompensasi Kerf untuk Part yang Saling Pasang

Halo, Teman Bengkel-las.co.id! Kerf adalah lebar material yang hilang di sekitar jalur potong. Pada dua part yang saling pasang, kerf dapat membuat lubang terlalu besar, tab terlalu longgar, atau celah terlalu sempit bila geometri dikirim tanpa kompensasi. Namun kompensasi bukan angka tetap; ia bergantung pada mesin, material, tebal, gas, alat, dan arah lintasan.

Jawaban singkatnya: tetapkan fungsi pasangan dan toleransinya, ukur hasil kupon pada kondisi yang sama, lalu gunakan hasil itu untuk meninjau geometri. Jangan mengganti ukuran dari perkiraan atau menyalin nilai pekerjaan lain. [NEEDS PROJECT REVIEW: material, proses, toleransi, dan acceptance basis belum tersedia.]

![Ilustrasi memilih jasa bengkel las](/wp-content/uploads/2020/02/memilih-jasa-bengkel-las.jpg)

*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*


## Apa yang sebenarnya dikompensasi

Jalur alat memiliki lebar; sisi potongan yang dipertahankan menentukan apakah kontur digeser ke dalam atau ke luar. Pada fitur pasangan, yang penting bukan “nilai kerf” tunggal, melainkan ukuran akhir setelah material dan proses aktual diperiksa. Datum (acuan geometri), arah ukur, celah fungsi, dan toleransi harus tertulis pada gambar.

Artikel ini fokus pada fit antarkomponen, bukan toleransi umum, pemilihan end mill, atau parameter laser. Paket fabrikasi terkendali menghubungkan revisi, material, dimensi, sambungan, toleransi, urutan, inspeksi, dan dasar penerimaan ([BSN](https://pesta.bsn.go.id/produk/detail/12882-sni17292020), [ISO 3834-6:2024](https://www.iso.org/standard/83335.html)).

## Cara menguji sebelum produksi

Buat kupon dengan material, tebal, orientasi, gas, alat, dan program yang mewakili pekerjaan. Sertakan lubang, slot, tab, sudut, dan pasangan yang akan diukur. Catat sisi potong, burr (tonjolan tajam), dross (lelehan menempel), perubahan warna, kerataan, serta ukuran aktual. Foto membantu, tetapi tidak menggantikan pengukuran.

Gunakan alat ukur yang sesuai dan status kalibrasi atau verifikasinya dapat dibuktikan. Ukur fitur dan celah dengan metode yang disepakati, lalu hitung deviasi terhadap target. Jika kupon tidak konsisten, jangan menyembunyikan variasi dengan mengubah file; cari penyebab dari material, penjepitan, optik, alat, dan kondisi proses.

## Faktor yang mengubah pasangan

Material, batch, coating, ketebalan, kerataan lembar, panas, kecepatan, fokus, tekanan gas, keausan alat, dan urutan potong dapat mengubah ukuran. Untuk router atau milling, kekakuan, runout, dan penjepitan ikut menentukan. Toleransi celah juga dipengaruhi fungsi: pasangan dekoratif berbeda dari pasangan yang harus bergerak atau memindahkan beban.

Jika coating atau bahan pembersih terlibat, simpan identitas produk dan SDS (lembar data keselamatan). SDS tidak membuktikan kompatibilitas atau umur lapisan tanpa produk, batch, substrat, dan lingkungan aktual ([ISO 12944-5:2019](https://www.iso.org/standard/77795.html), [OSHA 1910.1200](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200)).

## Contoh keputusan praktis

Kompensasi dapat dipakai ketika kupon menunjukkan hasil stabil dan fungsi pasangan, datum, serta toleransi telah disetujui. Tinjau ulang bila material, tebal, mesin, alat, gas, program, atau proses finishing berubah. Tahan pekerjaan bila lubang dan tab tidak dapat dilacak ke revisi yang sama atau bila acceptance basis belum jelas.

Sobat Bengkel-las.co.id, gunakan status **kupon disetujui**, **perlu uji ulang**, atau **hold**. Catat nilai yang dipakai, kondisi uji, tanggal, operator, dan batas penggunaan. Jangan menyebut hasil “pas” hanya karena dua part dapat dipaksa masuk.

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah menggeser semua kontur dengan nilai yang sama tanpa membedakan lubang dan luar part. Kedua, mengukur dari permukaan yang belum dibersihkan. Ketiga, mencampur kupon dari material atau batch berbeda. Keempat, mengubah kompensasi tanpa menaikkan revisi. Kelima, mengabaikan burr atau dross yang mengubah celah setelah finishing.

Shortcut “uji satu lubang lalu produksi penuh” dapat gagal pada bentuk, arah, atau fitur berbeda. Alternatifnya adalah membuat kupon yang mewakili fitur kritis, meninjau hasil dengan pihak berwenang, dan melepas batch hanya setelah kriteria penerimaan terpenuhi. K3 harus menilai energi, ventilasi, api, akses, dan prosedur fasilitas; rujukan umum tidak menetapkan kontrol lokasi ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018)).

OSHA 1910.252 dapat dipakai sebagai contoh bacaan asing tentang pekerjaan panas dan pengendalian bahaya, bukan sebagai hukum atau jarak wajib di Indonesia. Permenaker No. 11 Tahun 2026 dan Permenaker No. 12 Tahun 2015 harus dibaca bersama penilaian risiko, prosedur fasilitas, serta otoritas K3 yang berwenang ([OSHA 1910.252](https://www.osha.gov/laws-regs/regulations/standardnumber/1910.252), [Permenaker No. 11 Tahun 2026](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026), [Permenaker No. 12 Tahun 2015](https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015)).

Jika part akan dilas, jangan menyimpulkan bahwa celah yang pas berarti sambungan otomatis memenuhi mutu. ISO 5817 membantu mengidentifikasi ruang lingkup mutu sambungan, tetapi abstraknya tidak memberikan tabel batas cacat atau penerimaan proyek yang boleh disalin. Gunakan standar dan prosedur lengkap yang berlaku, lalu kaitkan hasil ukur dengan fungsi pasangan ([ISO 5817:2023](https://www.iso.org/standard/80209.html)).

Catat juga kondisi pemindahan setelah potong. Part kecil dapat berubah posisi saat dilepas dari tab; tepi yang tajam dapat merusak sarung tangan atau permukaan pasangan. Tetapkan area penandaan, metode pembersihan, dan titik pemeriksaan sebelum komponen diteruskan. Bila lapisan atau perekat mengubah ukuran akhir, ukur setelah proses tersebut atau nyatakan batasnya di dokumen.

Teman Bengkel-las.co.id, minta pemeriksaan silang: satu orang membaca revisi dan target celah, orang lain memeriksa hasil kupon serta alat ukur. Simpan keputusan, tanggal, kondisi proses, dan siapa yang menyetujui. Jangan menghapus kupon gagal; ia membantu menjelaskan mengapa nilai kompensasi diubah dan mencegah kesalahan yang sama berulang.

Untuk pesanan berulang, tetapkan kapan kupon harus dibuat ulang: saat material atau batch berganti, mesin atau alat berubah, revisi gambar diterbitkan, atau hasil mulai menyimpang. Cantumkan batas penggunaan pada lembar proses dan jangan memperpanjangnya hanya karena jadwal mendesak. Jika perbedaan ukuran menyentuh fungsi keselamatan atau sambungan, tahan part dan minta penilaian desain yang kompeten sebelum rework atau produksi lanjut. Simpan alasan dan bukti setiap keputusan.

## Verifikasi dan serah-terima

Pastikan label part tetap terbaca setelah deburring atau coating, dan jangan menghapus tanda orientasi sebelum pemeriksaan akhir produksi.
Simpan catatan tersebut bersama laporan ukur dan revisi file.

Simpan file sumber dan revisi, hasil kupon, alat ukur, material, program, catatan deviasi, dan keputusan. NDT (pengujian tak merusak), laporan inspeksi, dan kualifikasi personel adalah bukti berbeda ([ISO 17635](https://www.iso.org/standard/85705.html), [ISO 9712](https://www.iso.org/standard/75614.html)). Handover (serah-terima) harus mengaitkan setiap part dengan dokumen dan status diterima atau hold. Scrap (sisa potongan) tidak otomatis boleh dicampur atau didaur ulang; identitas dan kontaminasi menentukan jalurnya ([PP No. 22 Tahun 2021](https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021)).

Menentukan kompensasi kerf untuk part yang saling pas berarti menguji proses dan mengaitkan celah dengan fungsi, bukan mengejar angka universal. Langkah berikutnya: tandai fitur pasangan, buat kupon, ukur hasil, dan minta persetujuan sebelum mengubah geometri. Gunakan [beranda Bengkel-las.co.id](/) hanya sebagai informasi umum. Aturan operasinya sederhana: bila kondisi uji atau acceptance basis berubah, ulangi tinjauan sebelum produksi berikutnya.
