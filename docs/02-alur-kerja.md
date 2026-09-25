# 02 — Alur Kerja Penyusunan Dokumen

## 7 tahap

| # | Tahap | Keluaran | Lokasi |
|---|---|---|---|
| 1 | Usulan topik | Usulan disetujui jadi antrean kerja | Issue di repo ini |
| 2 | Kajian awal | Ringkasan standar yang sudah ada + celah yang mau diisi | Issue / `diskusi/` |
| 3 | Pembentukan kelompok | Kelompok penyusun & koordinator dokumen | Issue |
| 4 | Penyusunan draf | Draf 0.x | PR di `standar-dan-panduan` |
| 5 | Tinjauan internal | Draf direview 3 unsur (pemerintah, industri, akademisi) | Review PR |
| 6 | Tinjauan publik | Masukan terbuka ≥ 3 minggu | Discussions |
| 7 | Penetapan & terbit | Dokumen versi 1.0 berstatus *Berlaku* | Rilis di `standar-dan-panduan` |

Setiap tahap punya **gerbang (gate)**: lanjut ke tahap berikutnya setelah keluaran tahap sebelumnya ada di repo dan disetujui koordinator dokumen + Ketua Pokja.

## Uji lapangan

Sebelum tahap 7, draf sebaiknya **dipakai minimal satu pilot Pokja 2**. Temuan dari pilot dicatat sebagai issue di repo ini dan dijawab di draf. Ini yang membedakan standar yang dipakai dari standar yang hanya diterbitkan.

Jika belum ada pilot yang relevan, dokumen tetap bisa terbit dengan status **Berlaku (percobaan)** dan ditinjau ulang setelah ada penerapan nyata.

## Ritme kerja

| Kegiatan | Frekuensi | Peserta | Keluaran |
|---|---|---|---|
| Rapat kelompok penyusun | 2 mingguan (45–60 menit) | Kelompok penyusun | Notulen di `notulen/` |
| Rapat koordinasi Pokja | Bulanan | Pengurus + koordinator dokumen | Status semua dokumen |
| Diskusi rutin | 2 mingguan | Semua anggota | Rangkuman di `diskusi/` |
| Sinkronisasi lintas Pokja | Triwulan | Pengurus Pokja 1, 2, 3 | Daftar penyesuaian |
| Laporan ke pengurus IDTC | Bulanan | Ketua Pokja | Update status 1 halaman |

> Frekuensi di atas adalah **usulan awal** — dikonfirmasi pengurus Pokja pada rapat perdana.

## Board proyek

Pokja 1 memakai **GitHub Projects** (tampilan Board) dengan kolom:
`Usulan` → `Kajian` → `Penyusunan` → `Tinjauan internal` → `Tinjauan publik` → `Terbit`,
dan field **Jenis** (Standar / Guideline / Framework / Policy brief).

## Status bulanan

Gunakan format singkat:

- **Status**: 🟢 sesuai rencana / 🟡 ada hambatan / 🔴 terhambat
- **Dokumen aktif & tahapnya**
- **Capaian bulan ini**
- **Rencana bulan depan**
- **Hambatan & bantuan yang dibutuhkan**

## Mengambil keputusan

Keputusan diambil lewat **musyawarah** di rapat kelompok penyusun. Kalau tidak tercapai kesepakatan:

1. Perbedaan pendapat dicatat sebagai issue berlabel `keputusan`, lengkap dengan argumen tiap pihak.
2. Dibawa ke rapat koordinasi Pokja bulanan.
3. Bila masih buntu, Ketua Pokja memutuskan, dan **pendapat yang berbeda tetap dicatat** di lampiran dokumen.
