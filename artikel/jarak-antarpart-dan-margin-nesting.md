---
article_id: CUT-09-03
title: "Menentukan Jarak Antarpart dan Margin Tepi saat Nesting"
slug: "jarak-antarpart-dan-margin-nesting"
description: "Menata komponen agar pemakaian material, waktu potong, dan sisa bahan lebih efisien."
status: draft
publication_date: "2026-01-29"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-09
primary_intent: "Menata jarak aman pada lembaran"
reader_community: "Bengkel-las.co.id"
reader_address: "Sobat Bengkel-las.co.id"
final_route: "/artikel/jarak-antarpart-dan-margin-nesting.html"
technical_review: required
writing_contract_version: "native-id-v2"
sources:
  - "https://www.iso.org/standard/83335.html"
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
  - "https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021"
---

# Menentukan Jarak Antarpart dan Margin Tepi saat Nesting

Halo, Sobat Bengkel-las.co.id! Jarak antarpart dan margin tepi saat nesting tidak punya satu angka yang berlaku untuk semua lembaran. Nilainya ditetapkan setelah Anda tahu proses potong, material, ketebalan, bentuk part, cara mengambil hasil potong, dan batas area kerja mesin. Jadi, jangan mulai dari “biasanya sekian milimeter”. Mulailah dari batas teknis pada lembaran dan kebutuhan part yang akan dipakai.

Jawaban singkatnya: buat dua parameter terpisah. **Jarak antarpart** adalah ruang di antara kontur dua komponen, sedangkan **margin tepi** adalah ruang dari kontur terluar ke tepi lembaran. Pilih nilai awal yang konservatif dari pemasok mesin atau prosedur kerja, lalu sahkan lewat uji potong dan pemeriksaan gambar kerja. Jika belum ada data mesin, material, dan dokumen proyek yang cocok, tandai keputusan itu sebagai `[NEEDS SPACING VALIDATION: mesin, proses, material, dan ketebalan belum dikonfirmasi]`, bukan menyalin angka dari pekerjaan lain.

![Ilustrasi memilih jasa bengkel las](/wp-content/uploads/2020/02/memilih-jasa-bengkel-las.jpg)

Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan
- Image ID: LOCAL-004
- Source type: local
- Placement: after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi memilih jasa bengkel las](/wp-content/uploads/2020/02/memilih-jasa-bengkel-las.jpg)`
![Ilustrasi memilih jasa bengkel las](/wp-content/uploads/2020/02/memilih-jasa-bengkel-las.jpg)
- Caption/credit: Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- Selection basis: filename/source metadata identifies `memilih jasa bengkel las` as relevant content media; no pixels were inspected.
- Hard boundary: do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- Substitution rule: do not replace this image. If unavailable or provenance is incomplete, insert [NEEDS IMAGE REVIEW: LOCAL-004] and continue drafting the prose.
END MANAGED IMAGE PLAN -->

## Jawaban singkat dan salah paham utama

Margin bukan “sisa supaya terlihat rapi”, dan jarak antarpart bukan sekadar celah untuk menghemat bahan. Keduanya memberi ruang bagi lintasan alat, panas, getaran, penjepitan, dan pengambilan part. Celah terlalu kecil dapat membuat kontur saling mengganggu atau menyisakan bagian yang sulit dipisahkan. Celah terlalu besar memang mengurangi kepadatan layout, tetapi belum tentu mengurangi biaya total jika waktu potong, handling, dan sisa rangka justru naik.

Pisahkan pula **ruang geometri** dari **batas fitur di dalam part**. Artikel ini hanya membahas penataan antarpart dan tepi lembaran. Lubang, slot, jembatan kecil, atau fitur yang berdekatan di dalam satu part mengikuti aturan desain dan proses yang berbeda; jangan menyelesaikannya dengan memperlebar margin luar.

## Definisi dan batas objek

Dalam gambar nesting, tandai sekurang-kurangnya empat garis: batas fisik lembaran, area yang boleh dipakai, kontur setiap part, dan jalur yang tidak boleh dilintasi alat atau penjepit. Margin tepi diukur dari kontur part terluar ke batas area pakai, bukan selalu ke tepi material mentah. Bila sebagian tepi harus dipotong, ditahan, atau dibuang karena kondisi lembaran, area pakai harus mengikuti keputusan itu.

Jarak antarpart diukur dari kontur ke kontur. Catat apakah perangkat lunak menghitung jarak dari garis nominal, garis kompensasi kerf, atau jalur pusat alat. Istilah *kerf* berarti lebar material yang hilang akibat proses potong. Perbedaan definisi ini dapat membuat angka yang tampak sama menghasilkan celah fisik yang berbeda.

Dokumen kerja sebaiknya memuat nama file dan revisi, ukuran serta identitas material, orientasi part, batas area pakai, nilai spacing, dan siapa yang menyetujuinya. ISO 3834-6:2024 menempatkan informasi dan pengendalian proses fabrikasi sebagai bagian dari praktik mutu; abstrak resminya dapat menjadi rujukan awal, tetapi bukan pengganti teks standar atau persyaratan proyek ([ISO 3834-6:2024](https://www.iso.org/standard/83335.html)).

## Cara kerjanya

Urutkan keputusan agar perubahan tidak merusak seluruh layout.

1. **Kunci data masukan.** Pastikan ukuran lembaran yang benar-benar tersedia, ketebalan, jenis proses potong, ukuran nozzle atau alat yang dipakai, serta kebutuhan orientasi dan arah finishing. Jika satu data belum pasti, beri status asumsi pada file nesting.
2. **Tentukan area terlarang.** Tandai sisi yang cacat, area untuk penjepit, lubang referensi, atau bagian yang harus disisakan untuk handling. Jangan menganggap seluruh persegi panjang lembaran dapat digunakan.
3. **Tetapkan nilai awal.** Gunakan rekomendasi terdokumentasi dari pengendali mesin atau prosedur internal sebagai titik awal. Nilai ini adalah parameter produksi, bukan hukum umum. Hindari mengklaim “aman untuk semua material”.
4. **Susun part dan cek jalur.** Letakkan part dengan jarak yang konsisten, kemudian periksa simulasi lintasan. Pastikan urutan potong tidak memotong part yang sudah kehilangan dukungan dan tidak membuat panas terkumpul pada satu zona.
5. **Uji dan ukur.** Potong sampel yang mewakili bentuk, ketebalan, dan kepadatan layout. Ukur hasilnya, periksa tepi, deformasi, dan kemudahan mengambil part. Catat revisi parameter; tanpa data uji, keputusan tetap sementara.
6. **Rilis dengan jejak persetujuan.** Simpan PDF/DXF atau format kerja, lembar parameter, hasil inspeksi, dan catatan penyimpangan. Paket fabrikasi yang terkendali biasanya perlu identitas material, dimensi, toleransi, urutan, dan titik inspeksi; katalog SNI 1729:2020 hanya menunjukkan identitas dokumen, bukan isi klausul atau nilai spacing ([katalog SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020)).

## Faktor yang mengubah hasil

**Proses dan mesin.** Laser, plasma, router, dan metode lain memiliki lebar potong, zona panas, dan kebutuhan dukungan yang berbeda. Kecepatan dan urutan juga memengaruhi panas lokal. Jangan memindahkan parameter antar mesin tanpa validasi.

**Material dan ketebalan.** Permukaan berlapis, lembaran melengkung, atau stok dengan toleransi ukuran dapat mengurangi area efektif. Identitas material dan batch perlu dicatat ketika spesifikasi proyek menuntut keterlacakan; label umum tidak cukup untuk menyimpulkan kompatibilitas atau hasil potong.

**Bentuk part.** Kontur dengan sudut tajam, leher sempit, atau banyak segmen kecil lebih peka terhadap panas dan getaran. Sisakan ruang yang memungkinkan part diangkat tanpa mencongkel part tetangga. Batas fitur di dalam part tetap harus ditinjau di gambar, bukan diselesaikan lewat spacing nesting.

**Handling dan keselamatan.** Jarak yang memudahkan alat memotong belum tentu memudahkan operator memisahkan lembaran. Penilaian keselamatan kerja harus melihat energi mesin, benda panas, tepi tajam, ventilasi, dan akses aktual. UU No. 1 Tahun 1970 dan Permenaker No. 5 Tahun 2018 adalah rujukan regulasi umum, tetapi detail pengendalian harus ditetapkan untuk tugas dan lokasi yang nyata ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018)).

**Tujuan pemakaian sisa.** Sisa lembaran yang masih dapat dipakai ulang membutuhkan penandaan ukuran, material, dan statusnya. Jangan menyebut semua scrap otomatis dapat didaur ulang atau mengklaim penghematan lingkungan tanpa mengetahui kontaminasi, jalur penyimpanan, dan penerima yang berwenang. PP No. 22 Tahun 2021 menegaskan pentingnya konteks dan pengelolaan limbah; rute aktual memerlukan verifikasi setempat ([PP No. 22 Tahun 2021](https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021)).

**Dokumen dan persetujuan.** Revisi ukuran part, perubahan material, atau perubahan target produksi dapat mengubah spacing yang layak. Simpan alasan perubahan, konsekuensi waktu dan bahan, serta persetujuan. Harga total atau janji “paling hemat” tidak membuktikan ruang lingkup, pengujian, atau hasil; bandingkan isi penawaran secara tertulis dan minta peninjauan teknis bila dampaknya signifikan.

## Contoh keputusan praktis

Anggap sebuah layout memuat part besar dan beberapa part kecil, tetapi belum ada data uji untuk material yang akan dipotong. Keputusan yang dapat dipertanggungjawabkan bukan memilih angka populer, melainkan membuat tiga lapis pemeriksaan:

| Pertanyaan | Jika jawabannya “ya” | Tindakan pada layout |
| --- | --- | --- |
| Apakah mesin dan proses sudah sama dengan data rujukan? | Parameter dapat dibandingkan | Gunakan nilai awal terdokumentasi, lalu jadwalkan uji konfirmasi. |
| Apakah part akan diambil dengan tangan atau alat bantu? | Kontur rapat bisa menyulitkan handling | Naikkan jarak di zona pengambilan atau ubah urutan potong. |
| Apakah tepi lembaran dipakai sebagai datum atau area penjepit? | Margin nominal tidak sama dengan area pakai | Tandai margin khusus dan jangan menempatkan kontur di sana. |
| Apakah ada syarat orientasi atau arah finishing? | Rotasi bebas tidak berlaku | Kunci orientasi sebelum mengoptimalkan kepadatan. |

Contoh ini sengaja tidak memberi angka universal. Setelah sampel dipotong, bandingkan ukuran aktual, kondisi tepi, sisa rangka, waktu pemisahan, dan catatan operator dengan target yang disetujui. Jika hasil berubah ketika ketebalan atau mesin berubah, buat parameter terpisah; jangan menggeneralisasi satu uji ke semua pekerjaan. Kawan Bengkel-las.co.id, gunakan tabel keputusan sebagai alat bertanya kepada penanggung jawab proses, bukan sebagai sertifikat kelayakan.

## Kesalahan umum dan cara memeriksanya

- **Menyalin spacing dari file lama.** Periksa apakah material, ketebalan, proses, mesin, dan definisi garisnya identik. Jika tidak, statusnya hanya referensi.
- **Mengukur ke tepi lembaran mentah.** Tumpangkan area penjepit, cacat, dan batas handling; ukur ulang ke area pakai.
- **Menganggap jarak sama di semua kontur.** Tinjau bagian tajam, leher sempit, dan zona panas; mintalah alasan bila nilai berbeda.
- **Mengoptimalkan persentase pemakaian saja.** Tambahkan waktu pemisahan, risiko merusak part, dan nilai sisa yang dapat dipakai ulang ke evaluasi.
- **Menghapus catatan revisi.** Pastikan file rilis memiliki nomor revisi, parameter, hasil pemeriksaan, dan persetujuan. Jika tidak ada, hentikan rilis dan minta kelengkapan dokumen.

## Jalan pintas yang tampak hemat tetapi berisiko

Shortcut yang sering dipilih adalah merapatkan semua kontur sampai perangkat lunak menyatakan lembaran “penuh”. Cara ini memang memperbesar kepadatan pada layar, tetapi dapat gagal ketika jalur alat berdekatan, panas menumpuk, rangka kehilangan kekakuan, atau operator sulit memisahkan hasil. Kepadatan juga tidak membuktikan waktu produksi lebih singkat.

Alternatif yang lebih aman adalah menetapkan batas minimum yang bisa dijelaskan, menjalankan simulasi, memotong sampel, lalu mengunci nilai melalui persetujuan teknis. Jika keputusan menyentuh struktur, lifting, tekanan, atau fungsi keselamatan, jangan rilis hanya berdasarkan nesting; minta peninjauan desain dan K3 yang kompeten. `[NEEDS TECHNICAL REVIEW: validasi spacing dan margin terhadap mesin, material, prosedur, serta dokumen proyek aktual]`.

## Kesimpulan

Menentukan jarak antarpart dan margin tepi berarti menetapkan area pakai yang realistis, bukan mengejar satu angka atau persentase kepadatan. Pisahkan kedua parameter, catat dasar pemilihannya, dan verifikasi dengan uji yang mewakili mesin, proses, material, dan cara handling Anda. Sobat Bengkel-las.co.id, langkah berikutnya adalah meminta file nesting ber-revisi, daftar parameter, hasil pengukuran sampel, serta persetujuan penanggung jawab sebelum produksi berulang. Untuk konteks pekerjaan lain, Anda dapat mulai dari [beranda Bengkel-las.co.id](/) dan membuka [aset gambar terkait](/wp-content/uploads/2020/02/memilih-jasa-bengkel-las.jpg) saat dokumen siap ditinjau.

Aturan operasinya sederhana: bila salah satu data kunci atau bukti uji belum tersedia, perlakukan spacing sebagai asumsi yang harus dikonfirmasi. Artikel ini membantu menata layout; ia tidak menggantikan gambar kerja terbit, persyaratan standar berlisensi, penilaian K3, atau persetujuan profesional untuk aplikasi khusus.
