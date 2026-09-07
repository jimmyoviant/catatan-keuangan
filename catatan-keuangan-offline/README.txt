# Catatan Keuangan Offline AI

Aplikasi web satu-file untuk pencatatan keuangan pribadi.

Fitur:
- Berjalan offline setelah file dibuka.
- Data disimpan di IndexedDB browser.
- Input bahasa sehari-hari dengan parser AI lokal (tanpa API/internet).
- Preview sebelum transaksi disimpan.
- Pemasukan, pengeluaran, tabungan, dana darurat.
- Rekap mingguan dan bulanan.
- Target dana darurat dan target tabungan.
- Backup/restore JSON.
- Sinkronisasi realtime antar TAB pada browser/perangkat yang sama melalui BroadcastChannel.

Catatan:
"Auto sinkron" pada versi offline berarti sinkron antar tab/jendela pada perangkat/browser yang sama. Sinkron antar HP/laptop yang berbeda tidak mungkin dilakukan tanpa jaringan/server. Jika nanti ingin sinkron antar perangkat, dapat ditambahkan mode LAN/peer-to-peer atau sinkronisasi cloud opsional.

Cara pakai:
1. Buka index.html.
2. Data tersimpan lokal di browser.
3. Jangan hapus site data/browser storage sebelum melakukan Backup.
