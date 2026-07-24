# Topical Authority — cutting.bengkel-las.co.id

## Role and boundary

`cutting.bengkel-las.co.id` is planned as a practical Indonesian knowledge hub for buyers, designers, and fabricators who need to choose, specify, order, and evaluate CNC-based cutting work. The map covers laser cutting, CNC router/cutter, and CNC milling as distinct processes plus the shared decisions around files, materials, tolerances, cost, quality, and production. It does not absorb the parent site's general welding, canopy, railing, gate, or structural-steel service intents, and it does not create city-swapped editorial pages.

## Context used

- The visible homepage identifies the parent business as “Bengkel Las Professional #1” and exposes product, welding, ordering, and contact sections.
- The primary navigation explicitly names four meaningful cutting routes: `/laser-cutting`, `/cnc-cutter`, `/cnc-milling`, and `/cnc-laser-cutting`.
- Representative route labels distinguish Laser Cutting, CNC Cutter/CNC Router, CNC Milling, and CNC Laser Cutting; they also surface acrylic, ACP, MDF, PVC, plywood, wood, wall-panel, and room-divider applications.
- Tracked-route evidence contains 1 root homepage, 4 semantic cutting/CNC routes, 102 top-level `laser-cutting-<location>.html` templates, and 41 redirect rules.
- Evidence gate: the root homepage and many redirects describe the broader parent welding business, while the semantic subdomain and meaningful route family identify cutting as the editorial role. This mismatch is recorded, but it does not materially change the cutting taxonomy or require a deep audit.

## Ignored template noise

- 102 location-swapped laser-cutting HTML pages were counted as one template family; their repeated bodies and metadata were not analyzed.
- Repeated “Layanan Daerah” headings and city article cards inside semantic pages were treated as geographic template noise.
- 1,905 tracked files under `wp-content/` and `wp-includes/` were treated as framework, plugin, theme, upload, and asset noise.
- Update utilities, generated assets, archives, pagination, feeds, and common build files were excluded from editorial evidence.
- General welding-product redirects belong to `bengkel-las.co.id` and are commercial-route boundaries, not evidence for cutting article duplication.

## Topical map

| Topic ID | Parent topic | Reader outcome | Boundary | Article target |
|---|---|---|---|---:|
| CUT-01 | Pemilihan proses cutting CNC | Memilih proses yang sesuai berdasarkan bentuk, bahan, toleransi, volume, dan hasil tepi. | Memiliki keputusan lintas proses; panduan teknis tiap mesin dimiliki CUT-03 sampai CUT-06. | 6 |
| CUT-02 | Desain dan file siap produksi | Menyiapkan gambar yang dapat diperiksa dan diproses tanpa revisi berulang. | Memiliki geometri, format, layer, dan handoff file; parameter mesin dan toleransi hasil dimiliki CUT-08. | 6 |
| CUT-03 | Laser cutting logam | Menentukan kecocokan laser untuk plat logam serta memahami hasil dan batas prosesnya. | Khusus pemotongan logam dengan laser; bahan nonlogam dimiliki CUT-04 dan frais dimiliki CUT-06. | 6 |
| CUT-04 | Laser cutting nonlogam | Memilih teknik laser yang tepat untuk akrilik, kayu, tekstil, kertas, dan bahan nonlogam lain. | Khusus respons bahan nonlogam terhadap laser; pemotongan router dimiliki CUT-05. | 6 |
| CUT-05 | CNC router dan cutter | Memahami penggunaan router untuk panel, kayu, plastik, komposit, ukiran, dan pemotongan lembaran. | Memiliki proses berbasis spindle/router; laser dimiliki CUT-03 dan CUT-04, sedangkan milling presisi dimiliki CUT-06. | 6 |
| CUT-06 | CNC milling | Memilih operasi milling untuk komponen berdimensi, pocket, slot, kontur, dan permukaan presisi. | Memiliki pengurangan material dengan end mill pada benda berdimensi; routing panel dimiliki CUT-05. | 6 |
| CUT-07 | Perilaku dan pemilihan material | Memahami sifat bahan yang memengaruhi proses, kualitas tepi, deformasi, dan kebutuhan finishing. | Memiliki keputusan berbasis sifat material lintas mesin; panduan proses spesifik dimiliki CUT-03 sampai CUT-06. | 6 |
| CUT-08 | Kerf, toleransi, dan spesifikasi dimensi | Menulis target dimensi dan toleransi yang realistis serta mengantisipasi kerf dan kompensasi. | Memiliki spesifikasi geometrik dan akurasi; pemeriksaan hasil aktual dimiliki CUT-10. | 6 |
| CUT-09 | Nesting dan efisiensi lembaran | Menata komponen agar pemakaian material, waktu potong, dan sisa bahan lebih efisien. | Memiliki tata letak produksi dan utilisasi bahan; perhitungan harga penawaran dimiliki CUT-12. | 6 |
| CUT-10 | Pemeriksaan mutu hasil cutting | Memeriksa ukuran, tepi, permukaan, kelengkapan, dan konsistensi sebelum hasil diterima. | Memiliki metode inspeksi dan kriteria penerimaan; diagnosis penyebab cacat dimiliki CUT-11. | 6 |
| CUT-11 | Cacat potong dan pemecahan masalah | Mengenali gejala cacat, memperkirakan penyebab, dan menentukan apakah perlu rework atau potong ulang. | Memiliki diagnosis kegagalan hasil; kriteria inspeksi rutin dimiliki CUT-10. | 6 |
| CUT-12 | Harga, penawaran, dan kuantitas | Menyiapkan informasi permintaan harga dan memahami komponen biaya tanpa mengandalkan daftar harga semu. | Memiliki pembentuk biaya dan evaluasi penawaran; optimasi layout teknis dimiliki CUT-09. | 6 |
| CUT-13 | Finishing dan proses lanjutan | Merencanakan deburring, bending, welding, coating, perakitan, dan urutan kerja setelah cutting. | Memiliki integrasi pascapotong; layanan welding umum dan produk jadi tetap milik rute komersial parent site. | 6 |
| CUT-14 | Prototipe dan perencanaan produksi | Memilih alur sampel, batch, revisi, dan produksi berulang yang mengurangi risiko. | Memiliki strategi tahap produksi dan perubahan desain; negosiasi vendor dimiliki CUT-16. | 6 |
| CUT-15 | Aplikasi produk dan desain | Menerjemahkan kebutuhan signage, interior, panel, furnitur, enclosure, dan komponen menjadi brief cutting. | Memiliki kebutuhan menurut aplikasi; detail proses mesin tetap dimiliki CUT-03 sampai CUT-06. | 6 |
| CUT-16 | Pemilihan vendor dan pengelolaan pesanan | Menilai kapabilitas penyedia, menyusun brief, menyepakati bukti mutu, dan mengelola serah terima. | Memiliki keputusan pemasok dan koordinasi pesanan; kalkulasi biaya teknis dimiliki CUT-12. | 6 |

## Internal-link rule

Setiap artikel mengarah ke hub topiknya dan ke satu panduan proses atau keputusan yang benar-benar dibutuhkan pembaca. Hub CUT-01 menjadi jalur pemilihan menuju CUT-03 sampai CUT-06; CUT-02, CUT-07, dan CUT-08 menjadi prasyarat spesifikasi; CUT-09, CUT-10, dan CUT-11 membentuk jalur efisiensi–inspeksi–diagnosis; CUT-12, CUT-14, dan CUT-16 membentuk jalur penawaran–sampel–pemesanan; CUT-13 dan CUT-15 menghubungkan hasil potong dengan aplikasi akhir. Tautan ke rute komersial hanya diberikan saat pembaca sudah memiliki spesifikasi dan membutuhkan konsultasi atau penawaran.

## First publication wave

Gelombang pertama berisi 12 aset yang membentuk jalur lengkap dari pemilihan proses hingga brief penawaran: `CUT-01-01`, `CUT-01-02`, `CUT-01-03`, `CUT-01-04`, `CUT-02-01`, `CUT-02-02`, `CUT-02-05`, `CUT-07-01`, `CUT-08-01`, `CUT-09-01`, `CUT-10-01`, dan `CUT-12-01`. Hub pemilihan proses membagi pembaca ke perbandingan mesin; panduan file, material, toleransi, nesting, pemeriksaan sampel, dan permintaan harga kemudian menutup celah keputusan sebelum kontak komersial.
