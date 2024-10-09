## Keterangan Project:

### 1. Alasan Mengambil Project Ini:
Saya mengambil ulasan aplikasi pemerintahan, dalam hal ini aplikasi BMKG (Badan Meteorologi, Klimatologi, dan Geofisika), karena ingin melihat bagaimana masyarakat merespons layanan informasi cuaca, gempa, dan iklim yang disediakan oleh pemerintah. Melalui analisis sentimen ini, saya berharap dapat memahami persepsi pengguna terhadap kualitas aplikasi serta menemukan pola ulasan yang bersifat positif dan negatif.

### 2. Dari Kapan Sampai Kapan Data yang Diambil:
Kami mengumpulkan data ulasan dari Google Play Store untuk aplikasi BMKG, mulai dari 13 September 2018 hingga 7 Oktober 2024. Periode ini mencakup berbagai pembaruan aplikasi dan perubahan fungsionalitas yang mungkin memengaruhi pengalaman pengguna.

### 3. Berapa Banyak Data yang Diambil:
Kami berhasil mengumpulkan total 5.000 ulasan aplikasi BMKG selama rentang waktu yang ditentukan. Data ini akan digunakan untuk analisis sentimen guna mengevaluasi pengalaman pengguna terhadap aplikasi tersebut.

### 4. Alur Preprocessing Data:
Proses preprocessing data bertujuan untuk membersihkan teks ulasan sebelum digunakan dalam analisis sentimen. Berikut adalah alur lengkap preprocessing yang dilakukan:

- Casefolding: Mengubah semua huruf dalam ulasan menjadi huruf kecil agar konsisten.
- Cleaning: Menghapus tanda baca, angka, dan karakter khusus yang tidak diperlukan.
- Emoji Removal: Menghapus emoji yang mungkin tidak relevan dalam analisis teks.
- Emoticon Removal: Menghapus emoticon seperti ":)" atau ":(" dari teks ulasan.
- Tokenisasi: Memecah teks menjadi token (kata-kata individu) agar bisa dianalisis lebih lanjut.
- Normalization: Menormalkan kata-kata tidak baku menjadi kata baku (misalnya, "gpp" menjadi "tidak apa-apa").
- Stopword Removal: Menghapus kata-kata umum yang tidak memiliki makna signifikan, seperti "dan", "di", atau "yang".
- Removal of Frequent Words: Menghapus kata-kata yang sangat sering muncul namun tidak memberikan kontribusi signifikan dalam membedakan sentimen.
- Stemming: Mengubah kata-kata menjadi bentuk dasar mereka (misalnya, "berjalan" menjadi "jalan").

Setelah langkah-langkah ini, teks ulasan sudah bersih dan siap untuk digunakan dalam analisis sentimen maupun visualisasi menggunakan teknik UMAP.
