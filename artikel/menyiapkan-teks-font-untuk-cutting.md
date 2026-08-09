---
article_id: CUT-02-06
title: "Teks, Font, dan Kurva: Menyiapkan Tulisan agar Aman Dipotong"
slug: "menyiapkan-teks-font-untuk-cutting"
description: "Menyiapkan gambar yang dapat diperiksa dan diproses tanpa revisi berulang."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-09-03"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-02
primary_intent: "Menyiapkan elemen tulisan untuk produksi"
reader_community: "Bengkel-las.co.id"
reader_address: "Kawan Bengkel-las.co.id"
final_route: "/artikel/menyiapkan-teks-font-untuk-cutting.html"
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

- **Image ID:** `LOCAL-004`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi memilih jasa bengkel las](/wp-content/uploads/2020/02/memilih-jasa-bengkel-las.jpg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `memilih jasa bengkel las` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-004]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

# Teks, Font, dan Kurva: Menyiapkan Tulisan agar Aman Dipotong

Halo, Kawan Bengkel-las.co.id! Tulisan yang tampak benar di layar belum tentu aman dipotong. Font dapat berubah ketika file dibuka di komputer lain, huruf bisa memiliki celah yang jatuh, dan objek teks masih menyimpan ketergantungan pada perangkat lunak. Cara ringkasnya: sepakati teks dan font, ubah salinan produksi menjadi kurva, periksa bridge (jembatan penahan bagian dalam huruf), lalu uji pratinjau toolpath sebelum mengirim.

Jawaban ini berlaku untuk persiapan file, bukan keputusan desain signage atau toleransi struktur. Jenis mesin, ketebalan material, ukuran huruf, dan metode finishing dapat mengubah kebutuhan bridge. Bila data tersebut belum disetujui, tandai [NEEDS PROJECT REVIEW].

![Ilustrasi memilih jasa bengkel las](/wp-content/uploads/2020/02/memilih-jasa-bengkel-las.jpg)

*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*


## Kunci naskah dan revisi

Salin teks final dari dokumen yang disetujui dan cocokkan ejaan, kapitalisasi, angka, serta tanda baca. Beri nomor revisi pada nama file. Jangan memperbaiki kata langsung di gambar tanpa catatan karena perubahan kecil dapat mengubah jumlah huruf dan kebutuhan material. Kawan Bengkel-las.co.id, minta pihak lain membaca hasil ekspor sebagai teks, bukan hanya melihat bentuknya.

Pisahkan file kerja dengan file produksi. File kerja boleh menyimpan teks yang dapat diedit; file produksi menyimpan salinan kurva yang sudah diperiksa. Dengan cara ini, Anda masih dapat mengubah naskah tanpa merusak bukti versi yang dikirim.

## Pahami teks, outline, dan kurva

Objek teks bergantung pada font yang terpasang. Outline atau convert to curves mengubah karakter menjadi jalur geometri. Setelah dikonversi, ejaan tidak dapat diperbaiki dengan mudah sehingga simpan salinan teks asli. Pastikan setiap huruf menjadi kontur tertutup yang dapat dibaca perangkat lunak CAM.

Periksa skala setelah konversi. Ukur tinggi huruf, panjang keseluruhan, dan jarak antarhuruf dengan satuan yang disepakati. SNI 1729:2020 pada katalog BSN hanya identitas standar dan tidak memberi aturan font atau ukuran bridge ([SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020)).

## Periksa bridge dan bagian dalam huruf

Huruf seperti A, B, D, O, P, R, dan angka tertentu memiliki bagian dalam yang dapat terlepas ketika dipotong. Bridge adalah penghubung kecil yang mempertahankan pulau bagian dalam. Jumlah dan bentuk bridge bergantung pada ukuran huruf, material, proses, dan kebutuhan tampilan; jangan menyalin ukuran universal.

Gunakan pratinjau satu warna untuk melihat apakah pulau, counter (ruang dalam huruf), dan jembatan terbaca. Periksa juga ujung tajam, sudut sempit, dan jalur yang bertumpuk. Bila bridge mengubah makna visual, minta persetujuan pemesan sebelum mengedit geometri.

## Validasi jalur dan ekspor

Jalankan pemeriksaan kontur terbuka, garis ganda, objek duplikat, dan jalur yang saling berpotongan. Pastikan arah kurva dan layer sesuai konvensi vendor. Ekspor ke format yang diminta, lalu buka kembali berkas ekspor untuk memastikan font tidak kembali menjadi teks atau skala berubah.

ISO 17635 memisahkan metode inspeksi, cakupan, kondisi permukaan, personel, alat, pelaporan, dan dasar penerimaan ([ISO 17635](https://www.iso.org/standard/85705.html)). Prinsip itu berguna untuk file: catat pemeriksa dan versi, tetapi jangan mengklaim standar tersebut menetapkan parameter cutting. ISO 3834-6:2024 juga menekankan informasi mutu terdokumentasi, bukan jaminan hasil proyek ([ISO 3834-6](https://www.iso.org/standard/83335.html)).

## Uji pratinjau dan part pertama

Tampilkan jalur potong, ukir, atau marking pada mode simulasi. Pastikan toolpath tidak memasuki area yang seharusnya menjadi bridge atau pulau. Untuk huruf kecil, buat kupon atau satu part pertama pada material aktual. Catat ukuran hasil, burr, distorsi, dan keterbacaan; foto hanya bukti pendukung.

ISO 9712 membahas kompetensi personel NDT, bukan batas keterbacaan huruf ([ISO 9712](https://www.iso.org/standard/75614.html)). ISO 5817 juga tidak otomatis menjadi acceptance basis untuk tulisan yang dipotong ([ISO 5817](https://www.iso.org/standard/80209.html)). Tahan produksi bila ukuran huruf, bridge, atau metode finishing belum disepakati.

## Keselamatan dan dokumentasi

Debu, asap, tepi tajam, dan energi mesin memerlukan pengendalian sesuai tempat kerja. UU No. 1 Tahun 1970 dan [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018) menjadi rujukan nasional. OSHA 29 CFR 1910.1200 (https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200) hanya contoh komunikasi bahaya. Untuk pekerjaan panas, [OSHA 29 CFR 1910.252](https://www.osha.gov/laws-regs/regulations/standardnumber/1910.252) bukan pengganti prosedur lokal.

Simpan naskah asli, file kurva, pratinjau, nomor revisi, dan persetujuan bridge dalam satu paket. Permenaker No. 11 Tahun 2026 (https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026), Permenaker No. 12 Tahun 2015 (https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015), dan Permenaker No. 38 Tahun 2016 (https://peraturan.bpk.go.id/Details/146207/permenaker-no-38-tahun-2016) harus diverifikasi sesuai tugas. Kendali energi dan pelindung mesin tidak boleh digantikan oleh catatan file; rujukan OSHA 1910.147 dan 1910.212 hanya pembanding teknis.

## Jalan pintas yang sering gagal

Mengirim file dengan teks hidup karena “font sudah umum” sering gagal saat komputer vendor tidak memiliki font itu. Mengubah semua teks menjadi kurva tanpa menyimpan salinan juga menyulitkan koreksi ejaan. Alternatifnya adalah paket dua versi, checklist geometri, pratinjau, dan persetujuan part pertama.

Tambahkan juga kondisi material, ketebalan, dan metode finishing pada lembar serah terima. Data ini membantu vendor menilai apakah ukuran bridge dan jarak antarhuruf masih masuk akal. Bila pemesan mengubah kata atau logo setelah pratinjau, buat revisi baru dan ulangi seluruh pemeriksaan geometri, bukan hanya mengganti satu huruf.

Rujukan pekerjaan panas dapat dibuka sebagai <a href="https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252">OSHA 1910.252</a>; alamat sumber mentahnya adalah `https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252`. Tautan tersebut hanya pembanding teknis dan tidak menggantikan persetujuan K3 setempat.

## Kesimpulan dan langkah berikutnya

## Paket serah terima dan pemeriksaan akhir

Buat daftar isi paket sebelum file dikirim: naskah yang disetujui, versi kurva, font referensi, ukuran kotak pembatas, satuan, layer operasi, dan hasil pratinjau. Sertakan catatan apakah bridge ditambahkan oleh desainer atau operator, karena perubahan itu dapat memengaruhi tampilan. [ISO 12944-5](https://www.iso.org/standard/77795.html) membahas sistem pelapisan secara umum, bukan aturan bridge atau parameter cutting. [UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970) tetap menjadi rujukan keselamatan kerja nasional. Untuk material dan sisa, [PP No. 22 Tahun 2021](https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021) perlu dibaca sesuai identitas serta jalur pengelolaan.

Jika berkas memicu pekerjaan panas atau mesin bergerak, tulis bahwa OSHA 1910.252 (https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252), OSHA 1910.147 (https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.147), dan OSHA 1910.212 (https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.212) hanyalah pembanding teknis. Persetujuan K3 Indonesia, identitas mesin, dan kondisi lokasi tetap menentukan izin mulai. Jangan menganggap checklist file sebagai bukti bahwa operator, pelindung, atau ventilasi sudah memadai.

Simpan checksum atau nama file final dan minta penerima mengonfirmasi bahwa file dapat dibuka tanpa font pengganti. Bila ada perbedaan tampilan, hentikan proses dan bandingkan kembali salinan naskah, kurva, dan revisi. Dengan rekaman ini, koreksi dapat dilakukan pada sumber yang benar, bukan dengan mengedit jalur secara acak di lantai produksi.

## Kesimpulan dan langkah berikutnya

Kunci naskah, simpan salinan teks, ubah salinan produksi menjadi kurva, periksa bridge dan kontur, lalu uji pratinjau pada material aktual. Kirim file dengan revisi, satuan, layer, dan catatan batas proses. Tahan produksi bila ejaan, ukuran, bridge, atau acceptance basis belum disetujui. Sobat Bengkel-las.co.id, kurva yang rapi membantu mesin membaca niat desain, tetapi tidak menggantikan review manusia dan bukti part pertama.

Untuk konteks umum, Anda dapat kembali ke [beranda Bengkel-las.co.id](/) sambil membawa paket file dan checklist.
