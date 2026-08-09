---
article_id: CUT-10-06
title: "Membuat Kriteria Accept, Rework, dan Reject untuk Part Cutting"
slug: "kriteria-accept-rework-reject"
description: "Memeriksa ukuran, tepi, permukaan, kelengkapan, dan konsistensi sebelum hasil diterima."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2026-03-06"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-10
primary_intent: "Menetapkan keputusan penerimaan hasil"
reader_community: "Bengkel-las.co.id"
reader_address: "Kawan Bengkel-las.co.id"
final_route: "/artikel/kriteria-accept-rework-reject.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
  - "https://www.iso.org/standard/83335.html"
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
---

Halo, Kawan Bengkel-las.co.id! Part cutting tidak cukup dinyatakan *accept* hanya karena bentuknya terlihat rapi. Keputusan yang dapat dipertanggungjawabkan memerlukan kriteria tertulis: ukuran dan datum cocok dengan dokumen kerja, tepi aman untuk proses berikutnya, permukaan serta fitur tidak mengganggu fungsi, semua item dan identitasnya lengkap, lalu hasil pemeriksaan tercatat. Jika satu syarat kritis belum bisa dibuktikan, statusnya bukan accept.

Gunakan tiga status yang tegas. **Accept** berarti bukti pemeriksaan memenuhi persyaratan yang sudah disetujui. **Rework** berarti ada penyimpangan yang masih boleh dikoreksi dengan metode dan otoritas yang disetujui, kemudian diperiksa ulang. **Reject** berarti part tidak boleh dipakai atau dikoreksi dengan cara biasa karena tidak ada disposisi yang sah, batas koreksi terlampaui, atau identitas dan bukti pemeriksaannya hilang. Nilai toleransi, jenis material, dan batas cacat tetap harus diambil dari gambar, spesifikasi, atau rencana inspeksi proyek—bukan dari perkiraan bengkel. **[NEEDS PROJECT ACCEPTANCE BASIS: toleransi, fungsi kritis, dan kewenangan disposisi harus ditetapkan oleh dokumen proyek dan peninjau kompeten.]**

Gunakan juga status *hold* (ditahan sementara) ketika bukti belum lengkap tetapi keputusan belum boleh dipaksakan ke accept, rework, atau reject. Status ini harus memiliki pemilik tindakan dan tenggat tinjauan.

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

![Ilustrasi memilih jasa bengkel las](/wp-content/uploads/2020/02/memilih-jasa-bengkel-las.jpg)

*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*


# Membuat Kriteria Accept, Rework, dan Reject untuk Part Cutting

## Definisi dan batas objek

Objek artikel ini adalah keputusan mutu untuk part hasil pemotongan—misalnya potongan pelat, profil, atau komponen custom—sebelum masuk ke proses berikutnya. Yang dinilai adalah kesesuaian terhadap persyaratan yang telah diterbitkan, bukan selera visual operator. Pekerjaan pengelasan, penggerindaan, atau metode memperbaiki cacat merupakan lingkup lain; di sini kita hanya menentukan apakah part diterima, dikembalikan untuk koreksi, atau ditahan dan ditolak. Untuk konteks alur kerja umum bengkel, pembaca dapat melihat [halaman utama Bengkel-las.co.id](/) sebagai titik kembali; halaman itu tidak menggantikan gambar kerja atau persetujuan proyek.

Mulailah dengan “paket identitas” setiap part: nomor gambar dan revisinya, nomor item atau nest, material dan tebal, kuantitas, serta penanda lot atau batch bila diwajibkan. Paket fabrikasi terkendali umumnya perlu memuat datum, toleransi, material, urutan kerja, titik tahan inspeksi, dan dasar penerimaan; katalog SNI 1729:2020 hanya mengonfirmasi keberadaan dan status standar, bukan memberi toleransi atau nilai penerimaan siap pakai ([BSN](https://pesta.bsn.go.id/produk/detail/12882-sni17292020)). Karena itu, jangan menyalin angka dari contoh internet ke lembar inspeksi Anda.

## Cara kerjanya

Susun pemeriksaan berurutan agar keputusan dapat diulang oleh pemeriksa lain.

1. **Kunci referensi.** Cocokkan gambar, revisi, arah potong, datum, dan fungsi antarmuka. Jika revisi tidak jelas, tahan part dan minta klarifikasi; jangan memilih gambar yang “paling mirip”.
2. **Periksa ukuran dan geometri.** Ukur dimensi yang mengendalikan perakitan lebih dulu, kemudian lubang, jarak tepi, sudut, kerataan, atau fitur lain yang disebut dokumen kerja. Catat alat, identitasnya, dan kondisi verifikasi/kalibrasinya. Satu angka yang cocok tidak membuktikan seluruh geometri.
3. **Periksa tepi dan permukaan.** Pastikan burr, slag, oksida, takik, distorsi, dan kerusakan permukaan dinilai terhadap fungsi dan persyaratan tertulis. Foto boleh menjadi petunjuk, tetapi bukan pengganti pengukuran atau pemeriksaan yang ditetapkan.
4. **Periksa kelengkapan dan ketertelusuran.** Hitung kuantitas, label, material, dokumen sertifikat atau laporan yang dipersyaratkan, serta status pemisahan part tidak sesuai. Rekaman material, consumable, dan produk membantu pemeriksaan serta penyelidikan kegagalan; ISO 3834-6 menempatkan informasi tersebut sebagai bagian dari sistem mutu, bukan jaminan bahwa part tertentu otomatis lulus ([ISO 3834-6:2024](https://www.iso.org/standard/83335.html)).
5. **Tentukan status dan otoritas.** Pemeriksa mengisi hasil, tetapi perubahan desain, penggunaan *as-is*, atau pengurangan persyaratan hanya boleh diputuskan oleh pihak yang diberi wewenang dalam prosedur proyek. Status sementara “hold” berguna ketika bukti belum lengkap; jangan menyamarkannya sebagai rework.
6. **Tutup siklus.** Part berstatus rework mendapat instruksi koreksi yang dapat dilacak, lalu mengulang pemeriksaan yang terdampak. Metode, cakupan, kondisi permukaan, personel, peralatan, laporan, dan dasar penerimaan adalah bukti terpisah; ISO 17635 memperingatkan bahwa tingkat penerimaan pemeriksaan tidak dapat diterjemahkan satu-banding-satu dari tingkat mutu pengelasan, sedangkan ISO 9712 membahas kompetensi personel pemeriksaan ([ISO 17635:2025](https://www.iso.org/standard/85705.html); [ISO 9712:2021](https://www.iso.org/standard/75614.html)).

## Faktor yang mengubah hasil

**Fungsi dan antarmuka.** Cacat kecil pada sisi yang tidak berpasangan dapat berbeda konsekuensinya dari cacat pada datum atau lubang baut. Tanyakan: apakah penyimpangan mengubah posisi, jarak, aliran, kekedapan, atau ruang untuk proses berikutnya? Tanpa jawaban fungsi dari dokumen proyek, gunakan status hold dan minta keputusan teknis.

**Jenis material dan kondisi tepi.** Material, tebal, arah serat, lapisan pelindung, dan proses potong dapat mengubah pemeriksaan yang diperlukan. Jangan menyimpulkan kompatibilitas atau performa terpasang dari label material saja. Catat identitas dan batch bila dokumen mensyaratkannya; detail penyimpanan, penggantian, atau perlakuan permukaan perlu diverifikasi terhadap produk dan prosedur aktual.

**Lingkungan pengukuran.** Suhu, kotoran, akses, pencahayaan, dan alat yang tidak sesuai dapat membuat hasil tidak dapat dibandingkan. Pada pemeriksaan non-destruktif, metode, teknik, cakupan, kondisi permukaan, status alat, dan personel harus ditentukan oleh prosedur yang berlaku, bukan oleh tampilan indikasi semata ([ISO 17635:2025](https://www.iso.org/standard/85705.html)).

**Kuantitas dan konsistensi.** Untuk pesanan banyak, kriteria harus menjelaskan apakah semua part diperiksa atau ada rencana sampling yang disetujui. Beberapa part yang baik tidak membuktikan seluruh lot konsisten. **[NEEDS SAMPLING PLAN: ukuran lot, tingkat pemeriksaan, dan aturan eskalasi harus berasal dari rencana inspeksi proyek.]**

**Perubahan lapangan.** Pemotongan ulang atau pengerjaan di lokasi dapat mengubah akses, fit-up, cuaca, keselamatan, dan kesempatan inspeksi. Jika kondisi berubah, hentikan keputusan otomatis dan minta tinjauan pihak yang berwenang. “Bisa diperbaiki nanti” bukan kriteria penerimaan.

## Contoh keputusan praktis

Gunakan tabel berikut sebagai kerangka, lalu isi kolom batas dengan dokumen proyek yang berlaku.

| Temuan saat inspeksi | Status awal | Tindakan keputusan |
|---|---|---|
| Dimensi pengendali, datum, material, tepi, dan dokumen semuanya sesuai | Accept | Rilis part dengan nomor laporan dan identitas lot. |
| Burr atau geometri menyimpang, tetapi prosedur proyek menyatakan koreksi aman dan masih dalam batas | Rework | Pisahkan, terbitkan instruksi koreksi, tetapkan pemeriksaan ulang, dan minta otorisasi. |
| Dimensi kritis di luar batas dan koreksi akan mengurangi fungsi atau ketertelusuran hilang | Reject atau hold sampai disposisi | Jangan kirim ke proses berikutnya; minta keputusan tertulis apakah scrap, penggantian, atau penggunaan khusus. |
| Hasil ukur tampak baik tetapi gambar/revisi atau alat ukur tidak dapat dibuktikan | Hold | Lengkapi referensi dan verifikasi alat sebelum menentukan accept. |

Contoh ini tidak menetapkan angka toleransi atau menjamin kelayakan pemakaian. **Kawan Bengkel-las.co.id**, mintalah pemeriksa menandai bukti yang benar-benar ada: hasil ukur, identitas alat, pemeriksaan visual, material, dan otorisasi. Jika salah satunya kosong, status yang jujur adalah hold, bukan accept.

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah memakai “kelihatan bagus” sebagai standar. Ganti dengan pertanyaan objektif: fitur mana yang diukur, terhadap datum apa, dengan alat apa, dan di mana hasilnya dicatat?

Kesalahan kedua adalah menganggap rework selalu aman. Tanyakan apakah prosedur mengizinkan koreksi, siapa yang menyetujui, apa yang terdampak, dan pemeriksaan apa yang diulang. Memperbaiki tepi dapat mengubah dimensi; memotong ulang dapat menghapus penanda material.

Kesalahan ketiga adalah mencampur lot. Beri label fisik untuk accept, rework, reject, dan hold; cocokkan dengan rekaman. Tanpa pemisahan, part yang ditolak dapat kembali ke aliran produksi tanpa sengaja.

Kesalahan keempat adalah memperluas klaim dari inspeksi. Hasil visual atau satu pengukuran tidak membuktikan kekuatan, umur, atau kesesuaian sistem. Bila fungsi kritis memerlukan pemeriksaan khusus, ikuti metode, personel, peralatan, dan laporan yang ditentukan dalam rencana inspeksi ([ISO 9712:2021](https://www.iso.org/standard/75614.html)).

Shortcut yang sering dipilih ialah memberi label accept agar pengiriman tidak tertunda, lalu menyusulkan dokumen. Shortcut ini gagal ketika revisi, lot, atau alat ukur ternyata salah; jejak keputusan sudah telanjur hilang. Alternatifnya adalah status hold dengan alasan singkat, pemilik tindakan, dan tenggat tinjauan. **[NEEDS DISPOSITION AUTHORITY: nama jabatan/pihak yang boleh mengubah hold, rework, atau reject harus ditetapkan dalam prosedur proyek.]**

## Kesimpulan dan langkah berikutnya

Kriteria accept, rework, dan reject untuk part cutting harus menghubungkan persyaratan tertulis dengan bukti pemeriksaan. Accept hanya setelah ukuran, tepi, permukaan, kelengkapan, konsistensi, identitas, dan rekaman memenuhi dasar penerimaan. Rework memerlukan koreksi yang diizinkan serta pemeriksaan ulang. Reject atau hold melindungi proses ketika batas atau bukti tidak terpenuhi.

Langkah berikutnya: ambil gambar dan revisi yang diterbitkan, buat lembar inspeksi berisi datum, fitur, metode, alat, hasil, status, dan otoritas disposisi, lalu minta peninjauan kompeten untuk mengisi toleransi, sampling, dan batas koreksi yang masih kosong. Simpan lembar yang telah disahkan bersama identitas lot agar pemeriksa berikutnya dapat menelusuri alasan keputusan; jangan mengandalkan ingatan operator atau pesan singkat yang mudah terlepas dari nomor part. Simpan juga salinan aset ilustrasi lokal hanya sebagai media pendukung, bukan bukti mutu. Teman Bengkel-las.co.id, jangan rilis part hanya karena jadwal mendesak—rilis berdasarkan bukti yang dapat dilacak, dan hentikan keputusan ketika bukti atau kewenangannya belum ada.
