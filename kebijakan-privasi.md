# Kebijakan Privasi RaX

Berlaku sejak: [TANGGAL TERBIT]

RaX ("aplikasi") adalah aplikasi kamera Android yang bisa dikontrol dari browser di komputer dalam satu jaringan lokal (Wi-Fi). Aplikasi ini dibuat oleh [NAMA PENGEMBANG]. Kebijakan ini menjelaskan data apa yang dipakai aplikasi, untuk apa, dan ke mana data itu pergi.

## Ringkasan

- RaX **tidak mengirim foto, video, suara, atau data pribadi Anda ke server kami atau ke internet.**
- RaX **tidak memakai akun atau analitik.** RaX **menampilkan iklan** dari Google AdMob; layanan iklan ini mengumpulkan sebagian data perangkat (lihat "Iklan").
- Semua foto dan video tersimpan **di HP Anda sendiri**.
- Lokasi hanya ditulis ke dalam foto dan video bila Anda menyalakan **Geotag** sendiri. Lokasi tidak pernah dikirim ke kami. Bila Anda juga menyalakan **Cetak alamat di foto**, koordinat dikirim ke layanan alamat bawaan HP untuk mencari nama jalan dan wilayah (lihat "Layanan pihak ketiga").
- Data hanya berpindah di **jaringan lokal Anda**, ke komputer yang Anda izinkan sendiri.

## Izin yang diminta dan kegunaannya

| Izin | Kegunaan |
|------|----------|
| Kamera | Mengambil foto, merekam video, dan menampilkan pratinjau kamera |
| Mikrofon | Merekam suara untuk video dan mengirim suara pratinjau ke komputer yang terhubung |
| Perangkat Bluetooth sekitar | Memakai mikrofon Bluetooth (misalnya earphone nirkabel) sebagai sumber suara. RaX tidak memindai atau melacak perangkat Bluetooth lain |
| Internet, status jaringan, multicast Wi-Fi | Menjalankan server kecil di HP agar browser di komputer dalam jaringan yang sama bisa membuka panel kontrol, dan agar HP bisa ditemukan dengan nama `rax-xxxx.local` |
| Pengaturan audio | Memilih mikrofon yang dipakai (bawaan, kabel, USB, atau Bluetooth) |
| Lokasi (perkiraan dan akurat) | Menulis lokasi ke foto dan video (geotag), **hanya bila switch Geotag di Pengaturan menyala**. Izin ini diminta saat pertama kali membuka RaX dan boleh ditolak; RaX tetap berfungsi tanpa geotag. Lokasi dibaca hanya selama RaX terbuka di layar dan Geotag menyala |
| Akses lokasi media | Menjaga data lokasi di dalam foto tetap utuh saat Anda mengunduh salinannya ke komputer. Tanpa izin ini, Android menghapus lokasi dari salinan |

RaX tidak meminta izin kontak atau berkas di luar album RaX.

## Data yang disimpan di HP

- **Foto dan video** hasil RaX disimpan di galeri HP, album `DCIM/RaX`. Anda bisa melihat, membagikan, atau menghapusnya kapan saja lewat aplikasi galeri.
- **Metadata di dalam file**: waktu pengambilan dengan zona waktu, merek dan model HP, nama HP yang Anda tentukan, nama aplikasi, dan data kamera (misalnya exposure dan ISO). Bila **Geotag** menyala, file juga berisi **lokasi** tempat foto atau video diambil. Metadata ini ikut terbawa bila file Anda bagikan atau unggah ke tempat lain; matikan Geotag bila Anda tidak ingin lokasi ikut tersimpan.
- **Indeks kecil** berisi daftar file hasil RaX, agar komputer hanya melihat file buatan RaX dan tidak bisa melihat foto lain di HP.
- **Pengaturan aplikasi**, misalnya nama HP yang Anda tentukan dan pilihan kamera.
- **Data pemasangan (pairing)**: kode pengenal HP dan token akses untuk komputer yang pernah Anda izinkan. Data ini tidak ikut dicadangkan ke akun Google dan tidak dipindah ke HP lain.

Semua data di atas tetap di HP dan terhapus bila aplikasi dicopot, kecuali foto dan video di galeri yang tetap menjadi milik Anda.

## Data yang dikirim ke komputer di jaringan lokal

Saat Anda menyalakan **Kontrol dari PC**, komputer yang **Anda izinkan** (lewat pemasangan di HP atau dengan memindai QR) bisa:

- melihat pratinjau kamera bersuara beresolusi rendah,
- mengontrol kamera (foto, rekam, pengaturan),
- melihat status HP seperti persentase baterai,
- melihat dan **mengunduh salinan** foto dan video hasil RaX.

Data ini dikirim langsung dari HP ke komputer di jaringan yang sama, tanpa melewati server kami. Mengunduh hanya membuat salinan; file di HP tidak dipindah atau dihapus. Server di HP hanya berjalan selama RaX terbuka di layar dan **Kontrol dari PC** menyala. Akses bisa Anda hentikan dengan mematikan fitur ini, atau dicabut dengan tombol **Putuskan semua PC** di aplikasi.

Koneksi di jaringan lokal memakai HTTP biasa (tanpa enkripsi). Gunakan RaX di jaringan Wi-Fi yang Anda percaya, bukan Wi-Fi umum.

## Layanan pihak ketiga

Bila **Cetak alamat di foto** menyala, RaX memakai **layanan alamat bawaan Android (Geocoder)** untuk mengubah koordinat menjadi nama jalan, kelurahan/desa, kecamatan, kota/kabupaten, dan provinsi. Di sebagian besar HP layanan ini disediakan Google, sehingga **koordinat tempat foto diambil dikirim ke Google** saat alamat dicari (butuh internet). RaX tidak mengirim foto, nama HP, atau data lain ke layanan ini. Kebijakan Google: https://policies.google.com/privacy. Bila fitur ini mati, tidak ada koordinat yang dikirim ke mana pun.

Untuk memindai QR sesi komputer, RaX memakai **pemindai kode dari Google Play Services (Google ML Kit)**. Pemindaian berlangsung di HP. Google dapat mengumpulkan data diagnostik dan penggunaan yang terbatas sesuai kebijakan Google: https://policies.google.com/privacy dan https://developers.google.com/ml-kit/terms. RaX tidak menerima gambar dari pemindai ini, hanya isi QR yang dipindai.

## Iklan

RaX gratis dan dibiayai iklan dari **Google AdMob**:

- banner kecil di bagian atas layar kamera,
- banner kecil di bagian bawah Pengaturan,
- iklan layar penuh yang kadang muncul **sebelum** Anda menghubungkan HP ke komputer (paling sering sekali dalam 10 menit, tidak pernah saat merekam).

Untuk menampilkan dan mengukur iklan, Google dapat mengumpulkan dan memakai data seperti **ID iklan perangkat**, alamat IP, jenis dan pengaturan perangkat, serta interaksi dengan iklan, sesuai kebijakan Google: https://policies.google.com/technologies/partner-sites dan https://policies.google.com/privacy. RaX tidak memberikan foto, video, suara, lokasi, atau nama HP Anda kepada layanan iklan.

Bila hukum di wilayah Anda mewajibkannya (misalnya di Eropa), RaX menampilkan formulir persetujuan dari Google sebelum iklan dimuat, dan pilihan itu bisa diubah lewat **Pengaturan > Info > Pengaturan privasi iklan**. Anda juga bisa menghapus atau mengganti ID iklan di Setelan HP > Google > Iklan (nama menu bisa berbeda tiap merek HP).

## Anak-anak

RaX tidak ditujukan khusus untuk anak-anak dan tidak dengan sengaja mengumpulkan data pribadi dari siapa pun.

## Keamanan

Komputer harus diizinkan dulu di HP sebelum bisa mengontrol kamera atau mengunduh file. Meski begitu, tidak ada sistem yang sepenuhnya aman, terutama di jaringan tanpa enkripsi. Karena itu, pakailah jaringan pribadi dan putuskan komputer yang tidak lagi dipakai.

## Perubahan kebijakan

Kebijakan ini bisa diperbarui bila fitur aplikasi berubah. Versi terbaru selalu tersedia di halaman ini, dengan tanggal berlaku di bagian atas.

## Kontak

Pertanyaan tentang privasi bisa dikirim ke: [ALAMAT EMAIL KONTAK]
