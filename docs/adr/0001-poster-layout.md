# Poster layout, bukan rail kiri

Status: accepted

Portfolio memakai poster layout: sembilan Section, masing-masing minimal satu
viewport, dengan grid 12 kolom, nomor besar, dan tipografi display. Alternatif
awal adalah rail identitas tetap di kiri dengan konten bergulir di kanan.
Rail lebih mudah dibuat dan selalu menampilkan nama, tetapi membuat halaman
terasa seperti dashboard dan menyisakan ruang vertikal yang sempit untuk
komposisi besar. Poster dipilih karena portofolio ini dinilai dari kesan visual
dalam beberapa detik pertama, dan karena pemiliknya ingin hasil yang berbeda
dari referensi `juleo.sclassbinus.com` yang juga memakai layout kolom gelap.
Konsekuensinya: konten harus dikurasi per layar, navigasi dipindah ke Index
vertikal, dan `100svh` dipakai agar browser mobile tidak memotong Section.

## Considered Options

- Rail kiri tetap: mudah, tetapi generik dan sempit.
- Poster penuh: kuat secara visual, menuntut kurasi konten.
- Grid dokumen tanpa elemen menempel: tenang, tetapi lemah sebagai hero.

## Consequences

- Section dengan banyak item memakai Panel atau daftar yang dipangkas.
- Snap hanya `proximity` di desktop; tidak ada scroll hijacking.
- Nomor Section menjadi elemen grafis, bukan sekadar label.
