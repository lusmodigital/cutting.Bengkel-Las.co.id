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

- **Image ID:** `LOCAL-002`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi CNC Router 4](/wp-content/uploads/2019/11/CNC-Router-4.jpg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `CNC Router 4` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-002]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

# Format File untuk Laser Cutting, CNC Router, dan CNC Milling

Halo, Teman Bengkel-las.co.id! File yang bisa dibuka belum tentu siap diproses. Format harus menyampaikan geometri, satuan, skala, orientasi, dan revisi secara konsisten. Tanyakan format yang benar-benar diterima vendor, kirim geometri sesuai proses, lalu sertakan PDF ukuran dan material. Kondisi mesin, perangkat lunak, dan acceptance basis dapat mengubah jawaban; tinggalkan [NEEDS PROJECT REVIEW] bila belum jelas.

![Ilustrasi CNC Router 4](/wp-content/uploads/2019/11/CNC-Router-4.jpg)

*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*


## Bedakan fungsi format

DXF biasanya menyimpan geometri datar; DWG dapat membawa informasi gambar lebih banyak; STEP menyimpan model 3D; PDF menjadi lembar rujukan. Tidak ada ekstensi yang otomatis memperbaiki kontur terbuka, garis ganda, skala salah, atau layer keliru. Datum (acuan geometri), unit, material, tebal, dan revisi harus ditulis terpisah.

## Sesuaikan dengan proses

Laser memerlukan kontur tertutup, tanpa duplikasi, dan penandaan fitur yang jelas. Router membutuhkan kontur, area pocket, kedalaman, serta titik masuk bila disepakati. Milling memerlukan model 3D, orientasi, datum, dan informasi penjepitan. Format file tidak menetapkan parameter alat atau urutan pemesinan.

Sertakan PDF dengan ukuran kritis, toleransi, material, dan revisi. Jelaskan fungsi setiap layer; warna layar bukan bukti. [SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020) hanya identitas katalog, bukan aturan format proyek.

## Periksa geometri dan ekspor

Validasi kurva terbuka, garis ganda, segmen bertumpuk, teks hidup, skala, dan satuan. Simpan file sumber serta ekspor dengan nomor revisi. Buka kembali file ekspor di perangkat lunak vendor untuk memastikan ukuran dan layer tetap. Jangan menimpa file lama; catat perubahan.

[ISO 3834-6](https://www.iso.org/standard/83335.html) menekankan informasi mutu terdokumentasi. [ISO 17635](https://www.iso.org/standard/85705.html) memisahkan metode, cakupan, personel, alat, pelaporan, dan acceptance basis; abstrak standar tidak memberi angka universal.

## Minta pratinjau dan bukti

Minta vendor mengembalikan pratinjau toolpath atau daftar pertanyaan sebelum produksi. Cocokkan konversi dengan file sumber dan PDF. Untuk fitur penting, buat part pertama atau kupon; ukur hasil dan catat kondisi. [ISO 9712](https://www.iso.org/standard/75614.html) membahas kompetensi personel NDT, bukan jaminan file lulus.

## Faktor material dan keselamatan

Material, coating, kerf, penjepitan, dan proses lanjutan memengaruhi hasil. Simpan identitas material, batch, dan SDS. OSHA 1910.1200 (https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200) hanya pembanding komunikasi bahaya. UU No. 1 Tahun 1970 dan [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018) berlaku sesuai tempat kerja.

Untuk pekerjaan panas, OSHA 1910.252 (https://www.osha.gov/laws-regs/regulations/standardnumber/1910.252) bukan pengganti prosedur lokal. Kendali energi dan pelindung mesin mengikuti aturan fasilitas; OSHA 1910.147 dan 1910.212 hanya referensi teknis. Limbah mengikuti [PP No. 22 Tahun 2021](https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021).

## Jalan pintas dan checklist

Mengirim PDF saja, memakai file lama, atau mengandalkan warna layer dapat memindahkan datum dan toleransi tanpa jejak. Alternatifnya: paket sumber, PDF, material, revisi, unit, datum, dan daftar perubahan. Tanyakan ekstensi, versi perangkat lunak, unit default, kebutuhan model 3D, tafsir layer, dan bukti sebelum produksi.

Teman Bengkel-las.co.id, gunakan status siap, siap dengan pertanyaan, atau tahan. Status tahan berlaku bila kontur terbuka, skala meragukan, atau pihak penerima belum jelas. Kawan Bengkel-las.co.id, format yang baik adalah yang dapat diverifikasi terhadap gambar, bukan yang paling populer.

## Kesimpulan dan langkah berikutnya
Simpan rekaman ini bersama checksum file dan hasil part pertama.

Catat juga siapa penerima akhir, kapan konfirmasi diberikan, dan dokumen mana yang menjadi dasar penerimaan.

Jika vendor mengubah alur pascaproses, minta contoh hasil dan catatan versi. Keputusan format tetap berlaku hanya untuk mesin, material, dan proses yang ditinjau; perubahan konfigurasi memerlukan konfirmasi ulang.

Sebelum file dirilis, minta penerima mengulang ukuran kotak pembatas dan satu fitur kritis dari PDF. Bila angka berbeda, jangan memperbaiki dengan mengubah skala tanpa jejak; kembali ke sumber, periksa unit, dan buat revisi baru. Tandai file yang sudah disetujui sebagai hanya-baca agar operator tidak menimpa bukti. Untuk pekerjaan berulang, simpan hasil part pertama dan daftar perubahan sebagai acuan lot berikutnya.

Keselamatan kerja harus diperlakukan sebagai bagian dari paket, bukan catatan terpisah. [UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970) menjadi rujukan nasional. Referensi OSHA 1910.147 (https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.147) dan 1910.212 (https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.212) tidak menggantikan prosedur isolasi energi atau pelindung mesin setempat. Bila pekerjaan melibatkan panas, minta izin kerja, pengendalian api, dan peninjauan K3 sesuai lokasi. Catat keputusan itu bersama revisi file agar operator tidak menerima instruksi yang terpisah dari kondisi aktual.

## Pertanyaan sebelum menyetujui format

Tanyakan apakah vendor membaca file langsung atau melalui perangkat lunak pascaproses. Minta versi perangkat lunak, unit default, dukungan spline dan arc, batas ukuran file, serta cara mereka menangani layer tersembunyi. Untuk model 3D, tanyakan orientasi, datum, dan fitur yang akan dipakai. Untuk format datar, tanyakan apakah kontur harus tertutup dan bagaimana lubang kecil atau garis marking dibaca.

Pastikan penanggung jawab memeriksa hasil konversi. Pengirim memverifikasi teks, ukuran, material, dan revisi; vendor memverifikasi keterbacaan mesin dan pratinjau; penerima menyetujui fungsi serta acceptance basis. Pembagian ini mencegah asumsi bahwa satu pihak memeriksa semuanya. Dokumentasikan persetujuan dalam email atau lembar serah terima.

Part pertama menjadi bukti yang lebih kuat daripada janji format. Ukur fitur kritis, periksa tepi dan permukaan, lalu cocokkan dengan PDF. Bila penyimpangan terjadi, tahan batch dan telusuri apakah sumber, konversi, material, atau proses yang berubah. Jangan menghapus data awal setelah rework karena diperlukan untuk memahami penyebab.

## Paket pengiriman yang mudah diaudit

Buat folder dengan empat bagian: sumber gambar, ekspor mesin, lembar rujukan PDF, dan catatan perubahan. Nama file memuat identitas part, material, tebal, revisi, dan tanggal. Sertakan daftar layer, unit, datum, dan orientasi. Bila vendor mengembalikan konversi, simpan salinan itu terpisah dari sumber agar perbedaan dapat dibandingkan.

Untuk pekerjaan dengan coating, [ISO 12944-5](https://www.iso.org/standard/77795.html) menjadi konteks pemilihan sistem pelapisan, bukan parameter file. Untuk mutu las, [ISO 5817](https://www.iso.org/standard/80209.html) tidak otomatis menetapkan acceptance basis cutting. [Permenaker No. 11 Tahun 2026](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026), [Permenaker No. 12 Tahun 2015](https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015), dan [Permenaker No. 38 Tahun 2016](https://peraturan.bpk.go.id/Details/146207/permenaker-no-38-tahun-2016) dibaca sesuai tugas serta lokasi.

Jika vendor meminta format berbeda, minta alasan dan contoh pratinjau. Jangan mengubah file secara diam-diam karena perubahan unit atau spline dapat memengaruhi ukuran. Simpan pertanyaan terbuka sebagai [NEEDS PROJECT REVIEW] dan tetapkan siapa yang menjawab. Setelah jawaban diterima, naikkan nomor revisi dan ulangi pemeriksaan geometri.

## Kesimpulan dan langkah berikutnya

Bekukan revisi, pilih format berdasarkan proses, sertakan PDF rujukan, dan minta pratinjau serta konfirmasi teknis. Simpan jawaban vendor dan hasil part pertama. Bila geometri, unit, tujuan fitur, atau acceptance basis belum jelas, tahan file dan minta klarifikasi sebelum jalur alat dibuat.

Untuk konteks umum, Anda dapat kembali ke [beranda Bengkel-las.co.id](/) sambil membawa paket file.
