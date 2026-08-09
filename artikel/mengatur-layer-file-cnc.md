---
article_id: CUT-02-04
title: "Mengatur Layer untuk Potong, Ukir, Pocket, dan Marking"
slug: "mengatur-layer-file-cnc"
description: "Menyiapkan gambar yang dapat diperiksa dan diproses tanpa revisi berulang."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-08-26"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-02
primary_intent: "Memisahkan operasi melalui layer"
reader_community: "Bengkel-las.co.id"
reader_address: "Sobat Bengkel-las.co.id"
final_route: "/artikel/mengatur-layer-file-cnc.html"
technical_review: required
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
  - "https://peraturan.bpk.go.id/Details/146207/permenaker-no-38-tahun-2016"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.147"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.212"
  - "https://www.iso.org/standard/80209.html"
---

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

# Mengatur Layer untuk Potong, Ukir, Pocket, dan Marking

Halo, Sobat Bengkel-las.co.id! Kesalahan memisahkan layer sering membuat operator menebak mana garis potong, ukir, pocket, atau marking. Akibatnya operasi bisa tertukar, garis bantu ikut diproses, atau revisi bolak-balik. Solusi ringkasnya adalah menetapkan satu arti untuk setiap layer, menyimpan geometri dalam bentuk yang dapat diperiksa, lalu mengunci aturan itu sebelum ekspor.

Layer adalah kelompok objek pada berkas gambar, bukan parameter mesin. Warna layar boleh membantu, tetapi nama layer, jenis geometri, dan catatan operasi harus menjadi sumber keputusan. Kondisi yang dapat mengubah jawaban ialah jenis mesin, perangkat lunak CAM, material, dan standar proyek. Bila aturan vendor belum tertulis, tinggalkan [NEEDS PROJECT REVIEW] sebelum mengirim file produksi.

![Ilustrasi bengkel las](/wp-content/uploads/2019/10/bengkel-las.png)

*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*


## Tetapkan kamus layer sebelum menggambar

Buat kamus singkat yang menyebut nama, fungsi, dan perlakuan tiap layer. Contoh: `CUT-THRU` untuk kontur yang menembus material, `ENGRAVE` untuk ukiran dangkal, `POCKET` untuk area yang dikosongkan, `MARK` untuk penandaan, dan `REF` untuk garis acuan yang tidak boleh masuk toolpath. Nama itu hanya contoh; ikuti konvensi yang disepakati pemesan dan vendor. Jangan memakai satu layer untuk dua operasi karena operator akan kehilangan jejak niat desain.

Tuliskan satuan, skala, dan sistem koordinat di catatan pengiriman. Datum (acuan geometri) harus jelas bila part memiliki lubang, tepi pasang, atau orientasi tertentu. [SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020) hanya mengonfirmasi identitas standar pada katalog BSN; halaman tersebut bukan tabel aturan layer atau toleransi gambar Anda. Persyaratan proyek yang berlaku tetap harus disediakan oleh pihak berwenang.

## Pisahkan geometri berdasarkan operasi

Kontur potong sebaiknya berupa kurva tertutup tanpa garis ganda. Ukiran dapat memakai garis tengah atau batas area sesuai kemampuan alat, sedangkan pocket perlu batas tertutup yang menjelaskan area yang diambil. Marking harus diberi label apakah hanya referensi posisi atau benar-benar menjadi instruksi mesin. Garis konstruksi, ukuran, dan teks penjelas disimpan di `REF` atau layer dokumentasi.

Kawan Bengkel-las.co.id, jangan menganggap warna merah otomatis berarti potong. Warna bisa berubah ketika berkas dibuka pada aplikasi lain. Periksa nama layer, properti objek, dan hasil pratinjau toolpath. Jika vendor meminta warna tertentu, catat aturan itu sebagai konvensi tambahan, bukan satu-satunya bukti.

## Cegah masalah geometri sebelum ekspor

Jalankan pemeriksaan untuk kurva terbuka, objek duplikat, segmen bertumpuk, teks yang belum diubah menjadi kurva, dan blok yang menyimpan layer tersembunyi. Pastikan unit milimeter atau inci tidak berubah saat ekspor. Ukur kotak pembatas terhadap ukuran nominal dan periksa posisi datum. Jangan menghapus garis bantu secara massal sebelum memastikan tidak ada informasi inspeksi yang hilang.

Simpan berkas sumber dan berkas kirim dengan nama yang memuat nomor revisi, material, ketebalan, dan tanggal. Kunci versi yang telah disetujui agar perubahan baru tidak menimpa bukti lama. ISO 3834-6:2024 menekankan pentingnya informasi mutu yang terdokumentasi, tetapi abstraknya tidak menetapkan format nama file atau aturan layer ([ISO 3834-6](https://www.iso.org/standard/83335.html)).

## Buat matriks operasi dan bukti

Sertakan tabel sederhana: nama layer, operasi, kedalaman atau status tembus, alat yang diperkirakan, dan cara verifikasi. Kolom terakhir menjawab bagaimana operator tahu bahwa objek benar. Untuk marking, tulis apakah hasil diperiksa secara visual atau dengan ukuran posisi. Untuk pocket, tulis permukaan akhir dan batas area hanya jika sudah disetujui; jangan mengarang parameter yang belum diberikan.

Bukti produksi dapat berupa tangkapan layar pratinjau, daftar objek, checksum berkas, atau hasil ukur part pertama. Bukti tersebut tidak membuktikan seluruh batch tanpa aturan sampling dan catatan yang sesuai. ISO 17635 menjelaskan bahwa metode, cakupan, kondisi permukaan, personel, alat, pelaporan, dan dasar penerimaan adalah item terpisah ([ISO 17635](https://www.iso.org/standard/85705.html)). ISO 9712 membahas kompetensi personel NDT, bukan izin untuk memakai angka penerimaan generik ([ISO 9712](https://www.iso.org/standard/75614.html)).

## Urutan pemeriksaan sebelum kirim

Pertama, cocokkan revisi gambar dengan purchase order dan material. Kedua, matikan semua layer referensi lalu pastikan tidak ada geometri produksi yang ikut hilang. Ketiga, tampilkan satu operasi pada satu waktu dan hitung jumlah kontur. Keempat, buka kembali berkas pada aplikasi yang akan dipakai vendor untuk memastikan nama layer dan unit tidak berubah. Kelima, minta pihak lain membaca matriks operasi tanpa penjelasan lisan; bila ia masih menebak, file belum siap.

Teman Bengkel-las.co.id, tahan pengiriman ketika kontur saling berpotongan, skala berubah, atau arah marking tidak disepakati. Minta klarifikasi tertulis daripada memperbaiki file berdasarkan asumsi. Jika ada perubahan desain, naikkan nomor revisi dan simpan catatan objek yang berubah.

## Keselamatan dan batas tanggung jawab

Layer yang rapi tidak membuat proses otomatis aman. Material, energi mesin, penjepitan, debu, asap, dan akses operator tetap perlu penilaian. UU No. 1 Tahun 1970 dapat dibaca pada [teks peraturan](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), sedangkan [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018) menjadi rujukan lingkungan kerja. OSHA 29 CFR 1910.1200 (https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200) hanya contoh komunikasi bahaya, bukan hukum Indonesia.

Untuk pekerjaan panas, rujukan [OSHA 29 CFR 1910.252](https://www.osha.gov/laws-regs/regulations/standardnumber/1910.252) tidak menggantikan izin dan pengendalian lokal. Kendali energi dan pelindung mesin perlu ditinjau terhadap kondisi aktual; jangan menyalin prosedur OSHA 1910.147 atau 1910.212 sebagai instruksi universal. Limbah dan sisa material mengikuti identitas serta jalur sah berdasarkan [PP No. 22 Tahun 2021](https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021).

## Jalan pintas yang sering gagal

Shortcut yang tampak cepat adalah menggabungkan semua objek ke satu layer lalu meminta operator memilih berdasarkan warna. Cara ini gagal ketika file dibuka dengan tampilan berbeda atau ada objek referensi yang lupa dimatikan. Alternatif yang lebih andal ialah kamus layer, matriks operasi, pemeriksaan berurutan, dan persetujuan revisi. Jangan menjanjikan hasil produksi hanya dari struktur file; kemampuan mesin dan material harus dibuktikan melalui review atau part pertama.

## Catatan revisi dan pemeriksaan mutu

Simpan daftar perubahan yang menjelaskan layer mana yang ditambah, dihapus, atau dipindahkan. Bila file dipakai untuk fabrikasi struktur, [ISO 12944-5](https://www.iso.org/standard/77795.html) dapat membantu membedakan kebutuhan informasi sistem pelapisan, tetapi abstraknya tidak menetapkan urutan coating atau kompatibilitas produk. [Permenaker No. 11 Tahun 2026](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026), [Permenaker No. 12 Tahun 2015](https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015), dan [Permenaker No. 38 Tahun 2016](https://peraturan.bpk.go.id/Details/146207/permenaker-no-38-tahun-2016) harus dibaca sesuai status pekerjaan dan lokasi. Referensi OSHA 1910.147 (https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.147) serta OSHA 1910.212 (https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.212) bukan pengganti prosedur K3 Indonesia. Untuk mutu las, [ISO 5817](https://www.iso.org/standard/80209.html) tidak memberi aturan layer atau izin menerima hasil tanpa dokumen proyek.

## Kesimpulan dan langkah berikutnya

Atur layer dengan satu fungsi per nama, geometri yang bersih, unit serta datum yang jelas, dan matriks operasi yang bisa dibaca pihak lain. Kirim berkas sumber, berkas ekspor, nomor revisi, material, dan daftar pemeriksaan kepada vendor. Minta konfirmasi tertulis bahwa setiap layer dipetakan ke operasi yang benar, lalu tahan produksi bila ada kontur terbuka, skala meragukan, atau aturan keselamatan yang belum disetujui. Sobat Bengkel-las.co.id, file siap proses ketika niat desain dapat dibuktikan tanpa menebak—bukan sekadar ketika tampilannya terlihat berwarna rapi.

Untuk konteks umum, Anda dapat kembali ke [beranda Bengkel-las.co.id](/) sambil membawa kamus layer dan matriks operasi.
