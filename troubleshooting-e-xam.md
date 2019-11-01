# Troubleshooting e-Xam

**Permasalahan**

**Alternatif Pemecahan Masalah**

Virtual Box tidak dapat dijalankan dan mengalami boor error

* * 1. Pastikan konfigurasi e-Xam Server.vbox sudah benar, download e-Xam Server langsung dari [http://e-xam.kemdikbud.go.id/main/?mod=download](http://e-xam.kemdikbud.go.id/main/?mod=download%20).
    2. Cek kembali persyaratan minimal PC Server yang digunakan dengan minimal Intel Corei, 4GB RAM disarankan 8GB RAM, dengan Sistem Operasi Windows 64 Bit
    3. Lakukanlah mematikan Server melalaui Prosedur yang benar melalui web pada menu **Matikan Server** atau melalui console **\#poweroff .** Hal ini untuk menghindari kerusakan pada file e-xam Server.vdi pada virtual box.

Pc Client tidak dapat menemukan IP Server sehingga tidak dapat melakukan auto boot e-Xam Pelaksana

1. Pastikan Setting Network Adapter 1 pada posisi NAT dan Adapter 2 di Enabled, Bridge Adapter di arahkan ke Ethernet yang digunakan untuk internet \(lihat panduan diatas pada No. 4\)
2. Pastikan E-Xam Delta sudah di jalankan dengan benar
3. Lakukan pengecekan Kabel Jaringan jika perlu pastikan pada sistem operasi windows, pc client sudah memperoleh IP secara otomatis dari PC Server e-Xam. Setting pada Lan, pastikan setting IP **Obtain an IP Address automatically**
4. Cabut dan colok kabel lanm jika masih belum memperoleh IP Address, Lakukan peng-**Crampingan ulang** jika kabel konektor bermasalah**.**
5. Konfigurasi IP secara otomatis pada **VirtualBox Host-Only Network**
6. Disable/matikan Antivirus dan Firewall pada PC Server.
7. Pastikan konfigurasi Network pada Virtual Box pada Adapter 2 Bridge Adapter, TIDAK TERBALIK posisinya dengan ethernet LAN **jika** anda menggunakan 2 Kartu Jaringan

Authentifikasi Soal Ujian lama muncul ketika peserta login ikut ujian

Pastikan koneksi internet pada PC Server tidak mengalami gangguan. Disarankan untuk tidak melakukan aktifitas Browsing di PC Server selama ujian on line berlansung.

Tidak ada jadwal ujian ketika peserta login untuk mengikuti ujian

1. Pastikan konfigurasi tanggal dan waktu pada PC Server sudah sesuai dengan Time Zone.
2. Aktivasi soal ujian belum dilakukan oleh Admin Pusat, segera laporkan ke Admin Pusat untuk mengaktifkan soal ujian.

e-Xam Pelakana tidak dapat diinstall

1. Pastikan untuk menghapus e-Xam Pelaksana versi sebelumnya
2. Sesuaikan instalasi e-Xam Pelaksana dengan Sistem Operasi. Pilih Instalasi **exm\_install-win32.exe** jika menggunakan Sistem Operasi **Windows 32** Bit dan atau **exm\_install-win64.exe** jika menggunakan Sistem Operasi Windows **64 Bit**.

Pembaharuan e-Xam Pengelola Gagal, Data yang diberikan tidak valid

1. Pastikan koneksi internet pada PC Server lancar
2. Disarankan untuk tidak menggunakan Proxy Internal di Router
3. Lakukan penggantian koneksi internet melalui jaringan internet yang lain \(Koneksi internet melalui HP\)
4. Lakukan pembaharuan

Mouse tidak muncul di PC Server sehingga tidak bisa digerakkan

Mouse tidak bisa digerakkan karena pada posisi klik di console Virtual Box, untuk memunculkan kembali, **tekan** tombol **ctrl pada kibor sebelah kanan**

