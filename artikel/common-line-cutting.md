---
article_id: CUT-09-02
title: "Common-Line Cutting: Manfaat dan Risiko Berbagi Garis Potong"
slug: "common-line-cutting"
description: "Menata komponen agar pemakaian material, waktu potong, dan sisa bahan lebih efisien."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2026-01-25"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-09
primary_intent: "Menilai penggunaan garis potong bersama"
reader_community: "Bengkel-las.co.id"
reader_address: "Kawan Bengkel-las.co.id"
final_route: "/artikel/common-line-cutting.html"
technical_review: required
sources:
  - "https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999.8Presiden"
  - "https://www.iso.org/standard/83335.html"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200"
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
  - "https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021"
---

<!-- BEGIN MANAGED IMAGE PLAN
Image ID: LOCAL-005
Placement: after opening answer, before first detailed H2
**Exact Markdown to insert:** `![Ilustrasi bengkel las](/wp-content/uploads/2019/10/bengkel-las.png)`
Caption/credit: Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
Selection basis: filename/source metadata identifies bengkel las as relevant content media; no pixels were inspected.
Hard boundary: do not infer visual details, ownership, location, people, brands, condition, performance, or outcome.
END MANAGED IMAGE PLAN -->

# Common-Line Cutting: Manfaat dan Risiko Berbagi Garis Potong

Halo, Kawan Bengkel-las.co.id! Common-line cutting adalah strategi membuat dua komponen berbagi satu sisi garis potong. Manfaatnya bisa berupa lintasan alat yang lebih pendek, pemakaian material yang lebih hemat, dan lebih sedikit sisa di antara komponen. Namun garis bersama bukan “potongan gratis”. Jika celah, kerf (lebar material yang hilang akibat proses potong), urutan potong, atau penahan lembaran tidak cocok, satu kesalahan dapat merusak dua komponen sekaligus.

Jadi, gunakan garis bersama hanya setelah gambar kerja, jenis material, proses, dan kriteria penerimaan diperiksa. Efisiensi adalah hipotesis yang harus dibuktikan pada nesting dan hasil inspeksi, bukan jaminan dari fitur perangkat lunak. Untuk komponen yang memikul beban, menjadi bagian keselamatan, atau membutuhkan toleransi ketat, keputusan akhir memerlukan [NEEDS REVIEW: desain, material, proses, dan acceptance basis proyek].

![Ilustrasi bengkel las](/wp-content/uploads/2019/10/bengkel-las.png)

*Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.*

## Jawaban singkat dan salah paham utama

Garis potong bersama layak dicoba ketika dua tepi yang bersebelahan memang boleh menjadi satu hasil potong, geometri dan orientasinya sama-sama terkunci, serta proses mampu menjaga mutu tepi. Ia tidak layak dipaksakan hanya demi mengurangi panjang lintasan. Pada pemotongan yang menimbulkan panas, getaran, atau gaya tarik, perubahan bentuk dan perpindahan lembaran dapat menggeser garis berikutnya.

Salah paham yang sering muncul adalah menganggap penghematan waktu selalu sama dengan penghematan biaya. Waktu setting, pemeriksaan, pembersihan, pemisahan part, dan rework tetap ada. Penawaran juga harus menjelaskan apa yang termasuk—misalnya desain, bahan, inspeksi, transportasi, dan dokumentasi—karena angka total saja tidak membuat lingkup pekerjaan dapat dibandingkan secara adil ([UU No. 8 Tahun 1999 tentang Perlindungan Konsumen](https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999.8Presiden)).

## Definisi dan batas objek

Common-line cutting membahas satu garis yang dipakai bersama oleh dua atau lebih kontur part dalam satu lembaran. Fokusnya adalah keputusan berbagi garis, bukan seluruh teknik nesting. Jarak antarpart, margin tepi, dan arah serat memiliki pertimbangan tersendiri; jangan mengubah nilai tersebut hanya karena ada peluang berbagi garis. Untuk konteks alur kerja pemotongan, Anda dapat melihat [beranda Bengkel-las.co.id](/) sebelum menyusun permintaan teknis.

Garis harus tetap memiliki identitas yang jelas di file kerja: kontur part mana yang bertemu, sisi mana yang menjadi referensi, dan bagaimana part dipisahkan setelah pemotongan. Paket fabrikasi yang terkendali biasanya menghubungkan revisi gambar, dimensi, datum, material, toleransi, urutan kerja, titik inspeksi, dan dasar penerimaan. Katalog BSN hanya mengidentifikasi SNI 1729:2020; klausul dan nilai penerimaannya tetap harus diperoleh dari standar berlisensi serta dokumen proyek yang berlaku ([katalog SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020), [ISO 3834-6:2024](https://www.iso.org/standard/83335.html)).

## Cara kerjanya

Mulailah dari pasangan tepi yang kandidatnya berbagi garis. Tumpangkan kontur pada koordinat yang sama, lalu periksa apakah kedua part memiliki material, ketebalan, revisi, dan toleransi yang kompatibel. Setelah itu, tetapkan kompensasi kerf dan arah lintasan sesuai kemampuan proses yang benar-benar tersedia; jangan menyalin parameter dari mesin atau material lain.

Urutan kerja perlu mempertahankan kestabilan lembaran. Umumnya, operator mengatur fitur internal dan kontur luar dengan cara yang mencegah part kecil lepas terlalu dini, lalu melakukan pemisahan dan identifikasi setelah potong. Urutan terbaik tidak bisa dipastikan dari gambar saja: panas, penjepitan, vakum, tab, mikro-joint, dan sisa jembatan harus ditinjau pada mesin serta benda kerja nyata.

Sebelum produksi, simulasikan lintasan dan lakukan pemeriksaan pertama pada benda yang mudah diukur. Catat file dan revisinya, material atau nomor batch bila diwajibkan, operator, perubahan parameter, serta hasil pemeriksaan. Catatan semacam ini membantu menelusuri masalah; pedoman ISO 3834-6 menekankan pentingnya pengelolaan informasi mutu, tetapi abstrak standar tidak membuktikan bahwa suatu bengkel atau hasil tertentu telah memenuhi persyaratan proyek ([ISO 3834-6:2024](https://www.iso.org/standard/83335.html)).

## Faktor yang mengubah hasil

Pertama, geometri. Sisi lurus dan kontur yang benar-benar berimpit lebih mudah dievaluasi daripada sudut tajam, lubang dekat tepi, atau part dengan kompensasi berbeda. Kedua, material dan proses. Baja, aluminium, dan nonlogam dapat merespons panas serta gaya potong secara berbeda; identitas material dan instruksi proses harus berasal dari dokumen yang berlaku, bukan asumsi dari warna atau nama dagang.

Ketiga, fungsi part. Dua pelat dekoratif mungkin menoleransi sedikit pekerjaan akhir, sedangkan sambungan struktural atau komponen yang harus dipasang dengan datum tertentu tidak boleh dinilai hanya dari tampilan tepinya. Jika acceptance basis, toleransi, atau inspeksi belum jelas, hentikan keputusan berbagi garis dan minta persetujuan penanggung jawab desain.

Keempat, lingkungan dan K3. Pemotongan, pengelasan lanjutan, dan pembersihan dapat menghasilkan panas, asap, debu, kebisingan, atau serpihan. Pengendalian harus dimulai dari eliminasi atau rekayasa, dilanjutkan prosedur kerja dan PPE yang sesuai; label serta lembar data keselamatan membantu mengenali bahan, tetapi aturan OSHA adalah contoh yurisdiksi Amerika Serikat, bukan pengganti kewajiban Indonesia ([OSHA 29 CFR 1910.1200](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200), [UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018)).

Terakhir, sisa material bukan otomatis limbah yang bebas dicampur atau dijual. Identitas, kontaminasi, penyimpanan, pelabelan, pengangkutan, dan penerima berwenang menentukan rutenya. Pengurangan sisa hanya boleh disebut manfaat lingkungan setelah karakterisasi dan data aktual diperiksa ([PP No. 22 Tahun 2021](https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021)).

## Contoh keputusan praktis

Bayangkan dua panel dengan satu sisi lurus yang sama. Jika material, ketebalan, revisi, dan toleransinya cocok, serta kedua panel tetap tertahan sampai lintasan selesai, garis bersama dapat dipilih untuk uji pertama. Uji itu harus memeriksa dimensi luar, kelurusan sisi, burr atau slag, perubahan bentuk, dan kemudahan memisahkan panel. Hasil tersebut adalah bukti untuk konfigurasi itu saja, bukan jaminan bagi semua ukuran dan material.

Sebaliknya, bila salah satu panel akan menjadi bagian penahan beban, memiliki lubang referensi yang sensitif, atau memerlukan pemeriksaan khusus, perlakukan garis bersama sebagai opsi yang menunggu persetujuan. Jika satu gerakan lembaran bisa mengubah dua datum sekaligus, biaya inspeksi dan risiko rework mungkin lebih besar daripada lintasan yang dihemat.

Gunakan tabel keputusan singkat berikut.

| Pertanyaan | Jika “ya” | Jika “tidak” |
| --- | --- | --- |
| Kedua tepi memiliki material, revisi, dan toleransi yang serasi? | Lanjutkan simulasi | Pisahkan lintasan |
| Lembar tetap stabil sepanjang urutan potong? | Rencanakan uji pertama | Tinjau penahan dan urutan |
| Dasar penerimaan dan cara ukur sudah disetujui? | Tetapkan inspeksi | Minta klarifikasi proyek |
| Kegagalan satu garis tidak menggagalkan dua part kritis? | Pertimbangkan produksi | Jangan berbagi garis |

Kawan Bengkel-las.co.id, simpan keputusan, alasan, revisi file, dan konsekuensi waktu atau biaya. Rekaman itu lebih berguna daripada klaim umum “hemat material”.

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah menghapus garis ganda di CAD tanpa memeriksa kerf dan kompensasi. Tanyakan: apakah perangkat lunak menafsirkan garis tersebut sebagai satu lintasan, dan apakah hasil ukur aktual mendukungnya? Kedua, mengabaikan sisa tab atau mikro-joint. Tanyakan: bagaimana part dipisahkan tanpa mencongkel tepi kerja?

Ketiga, mengukur hanya satu dimensi yang mudah. Periksa datum, sudut, kelurusan, burr, dan distorsi sesuai acceptance basis. Keempat, memakai istilah “bersertifikat” sebagai pengganti bukti. Sertifikat seseorang memiliki metode, rentang, dan masa berlaku tertentu; itu tidak otomatis menyatakan seluruh perusahaan, mesin, desain, atau hasil proyek memenuhi persyaratan. Minta identitas dokumen dan cakupannya, lalu cocokkan dengan pekerjaan.

Kelima, memutuskan dari harga total. Minta rincian permintaan, bahan, consumable, pemrograman, inspeksi, rework, transportasi, dan dokumentasi. Jika ada perubahan, catat alasan, dampak waktu/biaya, pihak yang menyetujui, dan revisi. Jangan menganggap daftar cek generik sebagai nasihat hukum atau bukti kepatuhan.

## Jalan pintas yang tampak menarik

Jalan pintas paling menggoda adalah menerapkan common-line pada semua part yang tampak bersebelahan lalu berharap mesin “mengurus sisanya”. Cara itu gagal ketika satu part memerlukan orientasi, toleransi, atau urutan berbeda. Kegagalan juga dapat tersembunyi sampai proses bending, welding, coating, atau perakitan.

Alternatif yang lebih aman adalah mengklasifikasikan part menurut fungsi dan tingkat kritis, menguji satu pasangan pada konfigurasi nyata, kemudian membandingkan hasil ukur dengan dokumen yang disetujui. Bila bukti belum cukup, gunakan garis terpisah dan tandai keputusan tersebut untuk review teknis. [NEEDS TECHNICAL REVIEW: verifikasi geometri, kerf, material, stabilitas, dan acceptance basis sebelum rilis produksi.]

## Kesimpulan

Common-line cutting dapat mengurangi lintasan dan sisa hanya bila garis bersama benar-benar kompatibel dengan geometri, material, kestabilan lembaran, mutu tepi, serta cara inspeksi. Risikonya adalah kerusakan ganda, datum bergeser, pemisahan sulit, dan rework yang menghapus manfaat semula.

Langkah berikutnya: tandai kandidat garis pada file revisi, tulis asumsi material dan proses, minta persetujuan acceptance basis, lalu lakukan uji terukur sebelum produksi berulang. Teman Bengkel-las.co.id, perlakukan penghematan sebagai hasil yang harus dibuktikan pada konfigurasi tertentu—bukan janji universal—dan jangan rilis pekerjaan kritis sebelum review teknis menyelesaikan gate proyek yang masih terbuka. Untuk kembali ke halaman utama tanpa mengubah rute artikel, gunakan [beranda Bengkel-las.co.id versi ringkas](/.).
