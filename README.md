 Smart-Queue
Smart Queue Application adalah aplikasi web berbasis Laravel yang mensimulasikan sistem antrian loket digital dengan menekankan interaksi hardware secara virtual melalui event listener keyboard dan mouse. Aplikasi ini memungkinkan pengunjung mengambil nomor antrian layaknya menekan tombol mesin antrian fisik, sementara petugas memanggil antrian melalui panel khusus. Nomor antrian yang dipanggil ditampilkan secara realtime dan dibacakan otomatis menggunakan teknologi Text-to-Speech, sehingga aplikasi ini berfungsi sebagai media simulasi dan pembelajaran untuk memahami konsep interaksi hardware dalam pengembangan web interaktif tanpa memerlukan perangkat tambahan.


❗️FITUR UTAMA 
1. Pengambilan Nomor Antrian (Create)
Pengunjung dapat mengambil nomor antrian:
Dengan klik tombol (mouse event)
Dengan tombol keyboard (misalnya tombol Enter)
Nomor antrian otomatis tersimpan ke database

2. Daftar dan Status Antrian (Read)
Menampilkan daftar seluruh antrian
Menampilkan nomor antrian yang sedang dipanggil
Ditampilkan pada halaman panel petugas dan display TV
 
3. Pemanggilan dan Update Status Antrian (Update)
Petugas dapat:
Memanggil nomor antrian
Menandai antrian selesai
Melewati antrian
Status antrian berubah secara otomatis di sistem

4. Reset dan Penghapusan Antrian (Delete)
Reset antrian harian
Menghapus data antrian yang sudah tidak digunakan
5. Display Realtime (AJAX)
Nomor antrian tampil secara realtime di layar display
Tidak memerlukan refresh halaman
Cocok untuk mode TV atau layar besar

 6. Panggilan Suara Otomatis (Text-to-Speech)
Setiap nomor yang dipanggil akan:
Dibacakan otomatis oleh sistem
Menggunakan suara dari browser
Meniru sistem antrian profesional seperti di bank


🗯️ TEKNOLOGI YANG DIGUNAKAN 
Laravel
PHP
Visual Studio Code 
Bootstrap
Web Speech API
Laravel Storage (File System)

📎 PROSES PENGERJAAN 
✅ Setup project Laravel
✅ Implementasi TTS & STT
✅ Penyimpanan file audio & teks
✅ Records List & Detail
✅ UI/UX & Dark Mode
🔄 Penyempurnaan fitur dan UI

▶️ CARA MENJALANKAN PROJEK 
Clone repository
Jalankan: 
composer install
