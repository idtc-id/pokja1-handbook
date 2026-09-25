# 05 — Panduan GitHub untuk Pemula

Tidak perlu jadi programmer untuk berkontribusi. Sebagian besar kontribusi di Pokja 1 berupa **naskah, masukan, dan diskusi** yang bisa dilakukan lewat browser.

## 1. Buat akun & bergabung

1. Daftar di <https://github.com/signup>.
2. Aktifkan **two-factor authentication** (Settings → Password and authentication).
3. Kirim **username** GitHub ke pengurus Pokja 1.
4. Terima undangan organisasi `idtc-id` melalui email atau <https://github.com/idtc-id>.

## 2. Istilah penting

| Istilah | Arti sederhana |
|---|---|
| **Repository (repo)** | Folder proyek beserta riwayat perubahannya |
| **Issue** | Catatan tugas, usulan topik, atau masukan atas draf |
| **Discussion** | Forum tanya jawab dan ide |
| **Branch** | Salinan kerja agar perubahan tidak langsung mengubah versi utama |
| **Pull Request (PR)** | Usulan perubahan naskah yang direview sebelum digabung |
| **Markdown (.md)** | Format teks sederhana untuk dokumen di GitHub |

## 3. Ikut diskusi

Buka repo `pokja1-handbook` → tab **Discussions** → pilih kategori → **New discussion**.

## 4. Memberi masukan atas draf standar

Ada dua cara, pilih yang paling nyaman:

- **Masukan umum** → buat Discussion di repo `standar-dan-panduan`, atau balas thread tinjauan publik yang sudah ada.
- **Usulan perubahan kalimat tertentu** → buka file draf → klik ✏️ → ubah → ajukan sebagai Pull Request (lihat butir 5).

Sebutkan **bagian/nomor pasal** yang Anda komentari supaya penyusun mudah menindaklanjuti.

## 5. Mengedit dokumen lewat web (tanpa instal apa pun)

1. Buka file `.md` yang ingin diubah → klik ikon ✏️ (**Edit this file**).
2. Ubah teks. Klik **Preview** untuk melihat hasilnya.
3. Klik **Commit changes…** → pilih *Create a new branch… and start a pull request* → **Propose changes**.
4. Isi template PR → **Create pull request**. Peninjau akan memeriksa dan menggabungkan.

## 6. Mengunggah file kecil

Buka folder tujuan → **Add file → Upload files** → seret file → pilih *create a new branch* → **Propose changes**.
Ingat: file ≤ 50 MB, dan jangan mengunggah dokumen berlisensi tertutup (lihat [kebijakan dokumen](04-kebijakan-dokumen.md)).

## 7. Dasar Markdown

```markdown
# Judul
## Subjudul
**tebal**, *miring*
- butir daftar
1. daftar bernomor
[teks tautan](https://contoh.id)
| Kolom 1 | Kolom 2 |
|---|---|
| isi | isi |
```

## 8. Untuk yang ingin memakai git di komputer

Gunakan **GitHub Desktop** (<https://desktop.github.com>) atau git CLI:

```bash
git clone https://github.com/idtc-id/<repo>.git
git checkout -b docs/perubahan-saya
# ... ubah file ...
git add .
git commit -m "Jelaskan perubahan"
git push -u origin docs/perubahan-saya
```

Lalu buka Pull Request di GitHub.
