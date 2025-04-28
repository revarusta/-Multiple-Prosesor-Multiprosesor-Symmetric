# -Multiple-Prosesor-Multiprosesor-Symmetric

![arsitektur Multiple Prosesor dan Multiprosesor Symmetric drawio](https://github.com/user-attachments/assets/488965cf-81af-44ae-94ba-ad652721dfe3)

# Multi  Prosesor (Kiri Gambar)

# Definisi: 
Multi Processor adalah sistem komputer yang memiliki lebih dari satu CPU yang bekerja sama. Setiap CPU bisa mengakses memori utama secara langsung.

# Komponen-Komponen:
1. CPU 1 dan CPU 2
Dua prosesor berbeda yang bisa bekerja pada kecepatan masing-masing.

2. Memori Utama (Memori Utama)
Tempat penyimpanan data dan proses yang dibutuhkan oleh kedua CPU.
Semua CPU dapat membaca/menulis ke memori ini.

3. Cache
Setiap CPU memiliki cache sendiri. Cache berfungsi untuk menyimpan data sementara agar akses lebih cepat tanpa perlu ke memori utama terus-menerus.

3. Perangkat I/O (Perangkat Input/Output)
Perangkat yang berhubungan dengan luar, seperti keyboard, printer, atau hard disk.
Setiap CPU memiliki jalur sendiri menuju perangkat I/O melalui cache masing-masing.

# Alur Kerja:

1. CPU mengakses cache terlebih dahulu.

2. Jika data tidak ada di cache, CPU mengambil dari memori utama.

3. I/O Devices juga bisa berinteraksi dengan CPU melalui jalur masing-masing.

# Ciri Khas Multi Prosesor:

1. CPU bisa bekerja paralel tapi juga bisa mengakses memori yang sama .

2. Cocok untuk sistem yang membutuhkan kecepatan lebih tinggi dan multitasking berat.







# 2. Multiprosesor Simetris (SMP) (kanan gambar)
# Definisi:
Symmetric Multiprocessing adalah model di mana Multiprosesor Simetris adalah model di mana semua CPU setara. Mereka berbagi satu memori utama dan satu jalur I/O yang sama.

# Komponen-Komponen:
Beberapa CPU (digambar ada tiga CPU)
Semua CPU memiliki status yang sama — tidak ada "CPU master" atau "slave."

Memori Utama
Semua CPU mengakses memori ini secara langsung.

I/O (Input/Output Controller)
Semua CPU berbagi jalur ke perangkat I/O melalui satu sistem I/O yang terhubung.


# Alur Kerja:

1. CPU mengakses memori utama secara serentak dan setara.

2. Semua CPU juga menggunakan jalur yang sama untuk komunikasi dengan perangkat I/O.



# Ciri Khas Multiprosesor Simetris:

1. Kesetaraan akses — tidak ada CPU yang lebih dominan.

2. Sederhana dalam pengelolaan beban kerja karena semua CPU identik.

3. Lebih mudah dikembangkan karena skalabilitasnya lebih baik dibandingkan multi processor biasa.

![Cuplikan layar 2025-04-28 140801](https://github.com/user-attachments/assets/ce6ca12a-9247-4a2a-9188-f665f4a844d0)
