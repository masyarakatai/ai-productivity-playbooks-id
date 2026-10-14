# Rapat menjadi rencana eksekusi

## Masalah yang diselesaikan

Catatan rapat sering panjang tetapi tidak menghasilkan pemilik tugas, tenggat, atau keputusan yang jelas. Playbook ini membantu mengubah catatan menjadi rencana aksi yang dapat ditinjau tim.

## Kapan digunakan

Gunakan setelah rapat internal atau sesi proyek. Jangan gunakan sebagai satu-satunya catatan resmi untuk keputusan hukum, keuangan, atau SDM.

## Input yang diperlukan

- Catatan rapat atau transkrip yang sudah dicek izinnya.
- Nama peran, bukan informasi pribadi, bila memungkinkan.
- Tujuan rapat dan tenggat proyek yang diketahui.

Hapus informasi pelanggan, kata sandi, angka rekening, atau data personal sebelum diproses.

## Alur kerja

1. Tandai keputusan yang benar-benar diucapkan, pertanyaan terbuka, dan tugas lanjutan.
2. Minta AI menyusun tabel aksi tanpa mengarang pemilik atau tenggat.
3. Tinjau tabel bersama peserta rapat.
4. Konfirmasi pemilik tugas dan tenggat sebelum membagikan hasil.

## Contoh instruksi

```
Ubah catatan rapat berikut menjadi tiga bagian: keputusan yang sudah disepakati,
tugas lanjutan, dan pertanyaan terbuka. Untuk tugas lanjutan, gunakan tabel
{tugas | pemilik yang disebutkan | tenggat yang disebutkan | bukti dari catatan}.
Jangan menebak pemilik atau tenggat. Tandai dengan "perlu konfirmasi" bila tidak ada.
```

## Checklist kualitas

- [ ] Semua keputusan dapat ditelusuri ke catatan rapat.
- [ ] Tidak ada pemilik atau tenggat yang diciptakan AI.
- [ ] Peserta rapat sudah mengonfirmasi tugas mereka.

## Batasan dan risiko

Transkrip dapat salah menangkap pembicara atau konteks. Rekaman dan transkrip rapat juga dapat berisi data sensitif; patuhi kebijakan organisasi sebelum mengunggahnya ke layanan AI.
