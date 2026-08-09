---
article_id: CUT-05-02
title: "Memilih Mata Router untuk Kayu, MDF, Akrilik, dan ACP"
slug: "memilih-mata-cnc-router"
description: "Memahami penggunaan router untuk panel, kayu, plastik, komposit, ukiran, dan pemotongan lembaran."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-10-26"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-05
primary_intent: "Memilih jenis tool router menurut bahan"
reader_community: "Bengkel-las.co.id"
reader_address: "Kawan Bengkel-las.co.id"
final_route: "/artikel/memilih-mata-cnc-router.html"
technical_review: required
sources:
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200"
---

# Memilih Mata Router untuk Kayu, MDF, Akrilik, dan ACP

Halo, Kawan Bengkel-las.co.id! Memilih mata router tidak cukup dengan melihat diameter atau harga. Bahan yang akan dipotong menentukan geometri mata, jumlah flute (alur potong), dan cara membuang serpihan. Untuk kayu solid dan MDF, mulai dari mata carbide yang memang ditujukan untuk kayu; untuk akrilik, gunakan mata yang dirancang agar serpihan plastik tidak menempel; untuk ACP, pilih cutter yang dinyatakan kompatibel dengan panel komposit oleh produsennya. Satu mata serbaguna boleh saja untuk pekerjaan ringan, tetapi bukan asumsi aman untuk semua bahan.

Jawaban singkatnya: cocokkan mata dengan bahan, jenis operasi (potong tembus, pocket, atau ukir), serta kemampuan mesin. Lakukan uji pada potongan sisa dan ikuti rentang putaran, feed, kedalaman lintasan, serta penjepitan yang tercantum pada manual mesin dan mata. Tanpa data itu, saya tidak bisa menjanjikan tepi bersih, umur mata, atau keamanan tertentu. [NEEDS TECHNICAL REVIEW: parameter RPM, feed, dan kedalaman harus diverifikasi terhadap mesin, mata, dan material aktual.]

*Feed* (laju gerak relatif mata terhadap benda) berbeda dari putaran spindle. Keduanya perlu dibaca bersama manual agar uji tidak mengubah dua variabel sekaligus tanpa catatan.

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** `LOCAL-010`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi CNC router 3](/wp-content/uploads/2019/11/CNC-router-3.jpg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `CNC router 3` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-010]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->
![Ilustrasi CNC router 3](/wp-content/uploads/2019/11/CNC-router-3.jpg)

*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*


## Jawaban singkat dan salah paham utama

Kesalahpahaman yang sering muncul adalah menganggap mata berdiameter sama akan berperilaku sama pada kayu, plastik, dan ACP. Diameter hanya salah satu ukuran. Sudut potong, jumlah flute (alur potong), bentuk ujung (ujung datar, V, atau ball nose, yaitu ujung bulat untuk permukaan melengkung), dan arah pembuangan serpihan ikut menentukan apakah material terpotong atau malah meleleh, terangkat, dan tergores.

Sebelum membeli, tulis tiga hal di lembar kerja: bahan dan ketebalannya, hasil yang diinginkan, dan jenis collet (cekam penjepit mata) atau dudukan yang tersedia. Jika salah satunya belum pasti, keputusan terbaik adalah menunda pemotongan dan meminta verifikasi operator berpengalaman. Kawan, mata yang tidak pas bisa merusak panel sekaligus membebani spindle (poros pemutar mata).

## Definisi dan batas objek

“Mata router” di sini berarti cutter yang dipasang pada CNC router untuk memotong atau mengukir lembaran dan benda kerja nonlogam yang disebut dalam judul. Fokus artikel adalah pemilihan jenis tool, bukan tabel parameter universal, desain jig, perhitungan kapasitas mesin, atau penilaian kualitas hasil akhir.

Kayu solid memiliki serat dan arah yang berubah. MDF lebih homogen, tetapi menghasilkan debu halus. Akrilik bersifat termoplastik sehingga panas berlebih dapat membuat tepi melunak. ACP adalah panel berlapis dengan inti komposit; lapisan permukaan dan inti tidak boleh diasumsikan memiliki perilaku seperti kayu. Karena komposisi dan merek berbeda, selalu cek datasheet (lembar data teknis) panel dan rekomendasi cutter pabrikannya.

## Cara kerjanya

Flute (alur potong) pada cutter memotong material sedikit demi sedikit ketika spindle (poros pemutar) berputar dan mesin menggerakkan benda kerja relatif terhadap mata. Serpihan harus keluar dari alur potong. Bila serpihan tertahan, panas dan beban pada mata meningkat; bila gerakan terlalu agresif, tepi dapat robek atau panel bergeser.

Untuk potong tembus, ujung datar umumnya dipilih agar dasar potongan rata. Untuk alur atau ukiran bersudut, mata V lebih sesuai. Ball nose (ujung bulat) dipakai ketika bentuk permukaan memerlukan transisi melengkung, bukan sebagai pilihan otomatis untuk memotong lembaran. Mata kompresi menggabungkan arah potong ke atas dan ke bawah sehingga dapat membantu menjaga kedua permukaan panel berlapis, tetapi kecocokannya harus dikonfirmasi pada ketebalan dan jenis panel yang spesifik.

Pasang mata dengan panjang keluar secukupnya agar tidak bergetar. Bersihkan collet (cekam penjepit), masukkan shank (batang mata) secara benar, lalu kencangkan sesuai petunjuk pabrikan. Kunci benda kerja di beberapa titik yang tidak mengganggu lintasan. Jalankan simulasi lintasan tanpa menyentuh material bila tersedia, kemudian lakukan satu uji pada scrap (potongan sisa).

## Faktor yang mengubah hasil

Perhatikan faktor berikut sebelum memilih:

| Kondisi | Pertanyaan pemilihan | Konsekuensi bila diabaikan |
|---|---|---|
| Bahan | Kayu solid, MDF, akrilik cor/ekstrusi, atau ACP jenis apa? | Mata cepat tumpul, meleleh, atau menghasilkan tepi buruk. |
| Operasi | Potong tembus, pocket, chamfer, atau ukir? | Bentuk ujung salah dan dasar alur tidak sesuai. |
| Detail | Berapa lebar alur dan radius sudut yang diperlukan? | Mata terlalu besar untuk sudut atau terlalu lentur untuk detail. |
| Penjepitan | Apakah panel datar dan tidak bisa terangkat? | Getaran, ukuran meleset, dan risiko patahnya mata. |
| Pembuangan serpihan | Penyedot debu, chip evacuation (pembuangan serpihan), atau lintasan terbuka tersedia? | Debu menumpuk dan panas meningkat. |
| Mesin | Collet, panjang kerja, dan rentang putaran mendukung? | Shank tidak cocok atau spindle bekerja di luar batas. |

Untuk bahan plastik dan panel berlapis, tanyakan juga apakah lapisan pelindung harus tetap terpasang selama pemotongan. Jangan mengelupasnya hanya berdasarkan kebiasaan; ikuti petunjuk panel. Jika produk perekat, coating, atau pembersih dipakai, simpan identitas produk dan lembar data keselamatannya. Konsep komunikasi bahaya seperti label dan safety data sheet dijelaskan dalam [OSHA 29 CFR 1910.1200](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200), tetapi aturan tersebut bukan pengganti ketentuan K3 Indonesia.

## Contoh keputusan praktis

Gunakan tabel ini sebagai titik awal, bukan pengganti datasheet:

| Bahan dan pekerjaan | Pilihan awal | Verifikasi sebelum produksi |
|---|---|---|
| Kayu solid, potong profil | Mata carbide ujung datar atau profil sesuai bentuk | Arah serat, penjepitan, dan kondisi mata. |
| MDF, potong panel | Mata ujung datar dengan pembuangan serpihan baik | Debu, vacuum, dan apakah tepi akan dilapisi. |
| Akrilik, potong kontur | Mata khusus plastik dengan flute yang mencegah panas berlebih | Jenis akrilik, film pelindung, dan uji leleh/retak pada scrap. |
| ACP, potong alur atau panel | Cutter yang secara eksplisit direkomendasikan untuk panel komposit | Struktur lapisan, ketebalan, dan kualitas tepi yang diminta. |
| Ukiran dangkal pada kayu atau plastik | Mata V dengan sudut dan ukuran yang sesuai detail | Kedalaman ukir dan risiko ujung patah. |

Misalnya, Anda menerima gambar panel ACP dengan banyak sudut dalam. Jangan langsung memilih mata terbesar agar pekerjaan cepat. Periksa radius sudut pada gambar, sisakan lintasan untuk pembersihan sudut bila diperlukan, dan minta persetujuan bila tepi akan menjadi bagian tampak. Teman Bengkel-las.co.id, keputusan itu menyangkut geometri dan penerimaan hasil, bukan sekadar kecepatan mesin.

## Kesalahan umum dan cara memeriksanya

Pertama, memilih berdasarkan “mata kayu” untuk semua bahan. Periksa label penggunaan dan rekomendasi material dari produsen cutter. Kedua, memakai mata tumpul karena masih bisa berputar. Cari tanda panas, suara berubah, permukaan gosong, atau serpihan tidak lagi keluar; hentikan proses dan ganti atau asah melalui layanan yang sesuai.

Ketiga, menganggap pass pertama yang berhasil membuktikan parameter produksi. Uji satu potong hanya menunjukkan kondisi lokal. Catat mata, material, ketebalan, penjepitan, dan hasilnya; ulangi uji ketika batch atau sumber panel berubah. Keempat, mengabaikan debu dan bahan kimia. Sediakan pengendalian debu, ventilasi, pelindung mata dan pendengaran, serta prosedur K3 yang ditinjau penanggung jawab setempat. Detail APD dan ventilasi tidak boleh ditebak dari artikel umum.

Checklist sebelum menekan tombol start:

- Shank dan ukuran collet cocok, mata tidak retak, dan panjang keluar minimum.
- Bahan, ketebalan, sisi tampak, serta toleransi dari gambar kerja sudah jelas.
- Lintasan disimulasikan; area clamp dan titik nol tidak berada di jalur mata.
- Parameter awal berasal dari manual/datasheet, lalu dikonfirmasi lewat scrap.
- Debu, serpihan, dan keadaan darurat sudah ditangani sesuai penilaian K3 setempat.

## Ketika jalan pintas terlihat hemat

Shortcut “satu mata untuk kayu, MDF, akrilik, dan ACP” tampak hemat karena stok lebih sedikit. Masalahnya, mekanisme pembentukan serpihan dan respons panas tiap bahan berbeda. Mata yang baik di MDF belum tentu membuang serpihan akrilik tanpa panas, dan cutter plastik belum tentu cocok untuk lapisan ACP. Alternatif yang lebih dapat dipertanggungjawabkan adalah menyimpan beberapa jenis dasar, memberi label material yang dilayani, dan menyetujui mata baru melalui satu uji scrap terdokumentasi.

## Aturan penutup

Jadi, pilih mata berdasarkan bahan dan operasi: ujung datar untuk pemotongan umum, V untuk ukiran bersudut, ball nose untuk permukaan melengkung, dan cutter khusus plastik atau panel komposit bila datasheet menyatakannya. Jangan mengunci pilihan sebelum memeriksa mesin, penjepitan, pembuangan serpihan, dan parameter dari produsen.

Langkah berikutnya adalah membuat lembar setup untuk pekerjaan Anda, melampirkan datasheet mata dan panel, lalu meminta tinjauan operator atau penanggung jawab K3/teknis bila material, mesin, atau hasil tampak bersifat kritis. Untuk konteks umum pekerjaan bengkel, Anda dapat mulai dari [beranda Bengkel-las.co.id](/) dan melihat aset visual lokal yang menyertai pembahasan. Sobat Bengkel-las.co.id, aturan operasinya sederhana: jika kecocokan mata atau parameter belum terbukti pada bahan aktual, berhenti di tahap uji—jangan menjadikan tebakan sebagai produksi.
