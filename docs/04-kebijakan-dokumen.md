# 04 — Kebijakan Dokumen

## Jenis dokumen

| Jenis | Isi | Sifat |
|---|---|---|
| **Standar** | Ketentuan teknis yang harus dipenuhi agar sistem bisa saling bekerja | Normatif |
| **Guideline** | Panduan praktis cara menerapkan | Anjuran |
| **Framework** | Kerangka berpikir, klasifikasi, tingkat kematangan | Acuan |
| **Policy brief** | Ringkasan isu + rekomendasi untuk pembuat kebijakan | Masukan |

## Status dokumen

Setiap dokumen mencantumkan status di halaman pertama.

| Status | Arti |
|---|---|
| **Draf** | Masih disusun; boleh berubah besar |
| **Tinjauan publik** | Terbuka untuk masukan siapa pun, minimal 3 minggu |
| **Berlaku (percobaan)** | Bisa dipakai, tapi belum teruji di penerapan nyata |
| **Berlaku** | Sudah diuji minimal satu penerapan dan ditetapkan pengurus Pokja |
| **Ditinjau ulang** | Sedang direvisi karena ada temuan baru |
| **Ditarik** | Tidak dipakai lagi; halaman tetap ada dengan alasan penarikan |

Dokumen **tidak pernah dihapus**. Yang sudah ditarik tetap bisa diakses supaya rujukan lama tidak putus.

## Penomoran versi

Format `MAJOR.MINOR`:

- **MINOR** naik (1.0 → 1.1) untuk perbaikan redaksi, contoh tambahan, klarifikasi.
- **MAJOR** naik (1.1 → 2.0) kalau ada perubahan ketentuan yang membuat penerapan lama tidak lagi sesuai.

Setiap versi punya **tanggal berlaku** dan **ringkasan perubahan** di bagian riwayat dokumen.

## Cara menyitir

```
Indonesia Digital Twin Community, Pokja 1. (TAHUN).
<Judul Dokumen>, versi <x.y>. Jakarta: IDTC.
Tersedia di: https://github.com/idtc-id/standar-dan-panduan
```

## Lisensi

| Jenis | Lisensi default |
|---|---|
| Dokumen standar, guideline, framework, policy brief | CC BY 4.0 |
| Contoh kode, skema, skrip validasi | MIT |
| Skema data (JSON Schema, XSD, dsb.) | CC BY 4.0 |

Dengan CC BY 4.0, instansi lain **boleh mengadopsi dan mengubah** dokumen ini untuk kebutuhannya, selama mencantumkan atribusi ke IDTC.

## Mengutip standar pihak lain

- Boleh **merujuk** nomor dan judul standar berbayar (mis. ISO), **tidak boleh menyalin** isinya ke dokumen IDTC.
- Standar terbuka (OGC, buildingSMART, W3C) boleh dikutip sesuai ketentuan lisensinya, dengan atribusi.
- Kalau ragu, tanyakan ke pengurus sebelum menyalin.

## Konflik kepentingan

Penyusun yang punya kepentingan komersial langsung pada suatu ketentuan (mis. vendor sebuah platform) **wajib menyatakannya** di awal keterlibatan. Pernyataan ini dicatat di halaman kontributor dokumen. Yang bersangkutan tetap boleh menyumbang keahlian, tetapi tidak memutuskan sendiri ketentuan yang menguntungkan produknya.

## Bahasa

- Bahasa utama: **Indonesia**.
- Istilah teknis yang belum punya padanan mapan ditulis dalam bahasa aslinya dan dijelaskan di glosarium.
- Policy brief sebaiknya tersedia juga dalam ringkasan bahasa Inggris untuk keperluan kerja sama internasional.
