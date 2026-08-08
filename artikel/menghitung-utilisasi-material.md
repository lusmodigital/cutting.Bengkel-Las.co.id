---
article_id: CUT-09-06
title: "Cara Menghitung Utilisasi Material dan Sisa Lembaran"
slug: "menghitung-utilisasi-material"
description: "Menata komponen agar pemakaian material, waktu potong, dan sisa bahan lebih efisien."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2026-02-09"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-09
primary_intent: "Mengukur efisiensi pemakaian lembaran"
reader_community: "Bengkel-las.co.id"
reader_address: "Kawan Bengkel-las.co.id"
final_route: "/artikel/menghitung-utilisasi-material.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/83335.html"
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021"
---

# Cara Menghitung Utilisasi Material dan Sisa Lembaran

Halo, Kawan Bengkel-las.co.id! Utilisasi material bukan sekadar membagi luas komponen dengan luas lembaran. Anda perlu menetapkan ukuran lembaran yang benar-benar tersedia, memasukkan jarak antarpotong dan batas aman, lalu membedakan sisa yang masih dapat dipakai dari potongan kecil yang tidak praktis. Ukuran yang paling mudah diaudit adalah:

`Utilisasi (%) = (luas komponen yang jadi ÷ luas lembaran yang dialokasikan) × 100`

`Sisa lembaran = luas lembaran yang dialokasikan − luas komponen yang jadi − luas jalur potong dan batas yang tidak dapat dipakai`

Angka itu baru bermakna jika daftar komponen, orientasi, kerf (lebar material yang hilang oleh proses potong), dan toleransinya sudah disetujui. Contoh angka di bawah hanya ilustrasi perhitungan, bukan hasil suatu proyek. Dokumen fabrikasi yang terkendali semestinya mengaitkan identitas material, dimensi, revisi, toleransi, urutan, dan titik pemeriksaan; abstrak ISO 3834-6:2024 dapat menjadi rujukan tentang kerangka mutu, sementara detail penerapannya tetap harus berasal dari dokumen proyek yang berlaku ([ISO 3834-6:2024](https://www.iso.org/standard/83335.html)).

<!-- BEGIN MANAGED IMAGE PLAN
Image ID: LOCAL-005; placement: after opening; **Exact Markdown to insert:** `![Ilustrasi bengkel las](/wp-content/uploads/2019/10/bengkel-las.png)`; caption: Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
END MANAGED IMAGE PLAN -->

![Ilustrasi bengkel las](/wp-content/uploads/2019/10/bengkel-las.png)

Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.

## Hasil akhir dan prasyarat

Hasil yang dicari adalah tiga angka yang dapat ditelusuri: luas komponen bersih, luas material yang dialokasikan, dan luas sisa yang masih bisa digunakan. Tambahkan jumlah komponen jadi dan jumlah lembar yang dibuka agar angka luas tidak menutupi kesalahan hitung jumlah.

Sebelum menghitung, siapkan daftar potong (part number, panjang, lebar, jumlah, orientasi, dan revisi), ukuran lembar aktual, alat ukur atau data CAD, serta aturan penerimaan. Orang yang berwenang menyetujui gambar dan material harus mengunci data tersebut. Katalog BSN hanya mengidentifikasi SNI 1729:2020 dan ruang lingkup publiknya; katalog itu tidak menggantikan teks standar atau dokumen kerja berstempel yang memuat toleransi dan penerimaan ([SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020)).

Pisahkan metrik berikut sejak awal:

- **Utilisasi geometris:** perbandingan luas bentuk komponen dengan luas lembaran.
- **Utilisasi produksi:** memperhitungkan kerf, jarak aman, tepi yang harus dibuang, dan bentuk yang tidak boleh diputar.
- **Hasil jumlah:** berapa komponen yang benar-benar jadi dibanding kebutuhan.

Satu angka tidak dapat menggantikan yang lain. Lembaran dengan utilisasi area tinggi bisa tetap buruk jika satu komponen penting kurang, salah orientasi, atau tidak lolos pemeriksaan.

## Langkah 1 — tetapkan ruang lingkup

Tentukan apakah perhitungan berlaku untuk satu lembar, satu batch, atau seluruh pesanan. Tetapkan pula apakah area yang dihitung adalah ukuran nominal atau ukuran bersih setelah trim. Jangan mencampur lembar dengan ketebalan, grade, coating, atau heat/batch yang berbeda hanya karena dimensinya sama. Identitas dan jejak material perlu dicatat agar hasil potong dapat ditelusuri kembali; ISO 3834-6:2024 membahas kebutuhan mutu dan informasi yang perlu dikendalikan, tetapi tidak menetapkan material spesifik untuk pekerjaan Anda ([ISO 3834-6:2024](https://www.iso.org/standard/83335.html)).

Scope ini juga menandai hal yang tidak dikerjakan. Perhitungan utilisasi tidak menentukan kapasitas struktur, kesesuaian sambungan, harga penawaran, atau kelayakan operasi. Untuk klaim dimensi, beban, dan penerimaan, tandai `[NEEDS REVIEW: governing design and acceptance basis]` sampai gambar terbit dan persetujuan penanggung jawab tersedia. Untuk konteks umum pekerjaan bengkel, Anda dapat kembali ke [beranda Bengkel-las.co.id](/).

## Langkah 2 — kumpulkan dan cocokkan bukti

Mulai dengan tabel sederhana. Setiap baris memuat nomor komponen, ukuran, jumlah, luas satuan, orientasi, dan sumber revisi. Cocokkan angka dengan gambar atau model yang sama versinya. Jika gambar menyebut lubang, takikan, atau bentuk tidak persegi, gunakan luas geometri aktual dari CAD; jangan mengganti bentuk itu dengan persegi panjang tanpa menandai asumsi.

Lalu catat lembar yang tersedia: panjang, lebar, jumlah, kondisi tepi, dan bagian yang memang harus dipotong untuk meratakan. Ukur dimensi aktual bila pembelian memberi ukuran potong, bukan ukuran nominal. Tambahkan parameter proses dari mesin atau program yang disetujui: kerf, jarak antarkomponen, margin tepi, arah serat atau arah finishing bila diwajibkan, dan larangan memutar komponen. Nilai tersebut harus berasal dari program dan prosedur yang berlaku, bukan tebakan umum.

Buat kolom bukti dan status. “Ada di gambar”, “diukur”, “dikonfirmasi operator”, dan “menunggu persetujuan” adalah status berbeda. Kawan Bengkel-las.co.id, perbedaan ini mencegah angka optimasi diperlakukan sebagai fakta produksi sebelum material dan revisi benar-benar cocok.

## Langkah 3 — jalankan urutan kerja

1. **Hitung luas bersih komponen.** Untuk persegi panjang, kalikan panjang bersih dengan lebar bersih. Untuk bentuk gabungan, jumlahkan atau kurangi luas subbentuk sesuai geometri. Kalikan luas satuan dengan jumlah kebutuhan.
2. **Tentukan luas lembar yang dialokasikan.** Gunakan panjang efektif × lebar efektif setelah batas trim yang disepakati. Jika dua lembar dibuka, hitung keduanya; jangan memakai luas satu lembar lalu mengklaim sisa batch.
3. **Susun layout.** Tempatkan komponen dengan orientasi yang diizinkan. Sisakan kerf dan jarak antarpotong, serta margin tepi. Layout harus menghasilkan jumlah lengkap, bukan hanya tampak rapat di layar.
4. **Pisahkan sisa yang bernilai.** Tandai potongan utuh atau persegi yang dimensinya masih memenuhi kebutuhan komponen berikutnya. Sisanya dicatat sebagai offcut tanpa mengasumsikan dapat dipakai kembali.
5. **Hitung dua rasio.** Rasio bersih memakai luas komponen saja. Rasio produksi memakai luas komponen ditambah kerf, jarak, dan margin yang tidak dapat diselamatkan sebagai bagian dari layout. Pilih rasio produksi untuk membandingkan program potong.

Contoh ilustratif: satu lembar 1.000 × 2.000 mm memiliki luas 2.000.000 mm². Empat komponen 300 × 400 mm memiliki luas total 480.000 mm². Utilisasi geometrisnya 24%, dan sisa matematisnya 1.520.000 mm². Setelah kerf, margin, dan bentuk potongan diperhitungkan, utilisasi produksi akan berbeda. Catat selisih itu sebagai hasil layout, bukan sebagai kesalahan rumus.

Bandingkan alternatif layout dengan aturan yang sama. Layout A mungkin menyisakan satu persegi panjang besar; Layout B mungkin sedikit lebih tinggi utilisasinya tetapi hanya menghasilkan serpihan sempit. Pilih berdasarkan kebutuhan komponen berikutnya, waktu handling, dan kemampuan inspeksi—bukan persentase tertinggi saja.

## Titik tahan dan kondisi berhenti

Hentikan perhitungan dan minta review bila revisi gambar, grade, ketebalan, atau ukuran lembar tidak cocok; orientasi wajib belum jelas; kerf belum dikonfirmasi; atau layout mengurangi jumlah komponen di bawah kebutuhan. Jangan “mengakali” dengan memutar bagian yang punya arah kerja atau finishing tanpa persetujuan desain.

Tandai juga `[NEEDS REVIEW: material identity and approved substitution]` bila label, sertifikat, atau batch tidak dapat ditautkan ke lembar yang dipotong. Jika komponen akan dipakai untuk struktur atau fungsi kritis, utilisasi bukan bukti kapasitas atau keamanan. Review desain, metode fabrikasi, dan pemeriksaan yang diwajibkan harus selesai sebelum program dilepas.

Sisa yang terkontaminasi cat, oli, bahan kimia, atau material lain jangan langsung disebut scrap biasa atau pasti dapat didaur ulang. Rute penyimpanan, pelabelan, pengangkutan, dan penerima bergantung pada identitas serta konteks limbah; PP No. 22 Tahun 2021 adalah salah satu rujukan regulasi yang perlu diperiksa bersama penanggung jawab lingkungan setempat ([PP No. 22 Tahun 2021](https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021)).

## Verifikasi hasil dan serah terima

Sebelum material dipindahkan ke proses berikutnya, cocokkan:

- nomor program dan revisi dengan daftar potong;
- ukuran lembar aktual dan identitas material dengan catatan penerimaan;
- jumlah komponen, dimensi kritis, orientasi, dan tanda bagian;
- kerf, jarak, margin, serta alasan setiap area yang tidak dipakai;
- foto atau sketsa layout dan ukuran offcut yang disimpan;
- status pemeriksaan dan penyimpangan yang masih terbuka.

Hitung ulang dari catatan aktual setelah potong: luas komponen yang lolos, luas offcut yang diberi label, dan sisa yang menjadi scrap. Jika hasil berbeda dari prediksi, jangan menghapus angka awal; simpan keduanya dan cari penyebabnya—perubahan nesting, trim, kerf, atau komponen gagal. Handover yang baik mengaitkan item, revisi, tanggal, pemeriksa, dasar penerimaan, dan persetujuan; sebuah checklist tanpa identitas tidak membuktikan kesesuaian.

## Jalan pintas yang sering menyesatkan

Shortcut yang umum adalah memakai luas total komponen dibagi luas katalog lembar, lalu menyebut sisanya “waste”. Cara itu mengabaikan kerf, margin, bentuk aktual, jumlah yang kurang, dan offcut yang tidak punya ukuran berguna. Akibatnya, program terlihat hemat di spreadsheet tetapi memerlukan lembar tambahan atau pemotongan ulang.

Alternatif yang lebih andal adalah mengunci data, membuat layout versi, menghitung rasio produksi, lalu memverifikasi jumlah dan offcut secara fisik. Sobat Bengkel-las.co.id dapat menyimpan satu lembar kerja per revisi agar perubahan ukuran terlihat dan dapat disetujui sebelum mesin berjalan. Jika kemudian Anda menata beberapa desain dalam satu lembar, gunakan panduan [menggabungkan desain dalam satu lembar produksi](/artikel/gabung-desain-dalam-satu-lembar.html) setelah rute tersebut dinyatakan aktif.

## Kesimpulan

Cara menghitung utilisasi material adalah membagi luas komponen yang benar-benar dibutuhkan dengan luas lembar yang dialokasikan, lalu melaporkan sisa setelah kerf, margin, dan bagian yang tidak terselamatkan diperhitungkan. Lengkapi angka itu dengan jumlah komponen jadi dan daftar offcut berukuran nyata.

Langkah berikutnya: minta gambar terbit, identitas material, ukuran lembar aktual, dan parameter potong; buat layout ber-revisi; kemudian minta pemeriksaan sebelum program dilepas. Jika salah satu data itu belum ada, tampilkan `[NEEDS REVIEW]` dan jangan mengubah persentase menjadi janji penghematan. Utilisasi adalah alat kendali pemakaian material, bukan pengganti persetujuan desain, mutu, keselamatan, atau aturan limbah.
