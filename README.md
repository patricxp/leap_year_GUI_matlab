Tahun Kabisat GUI dengan MATLAB
📌 Deskripsi

Project ini membuat sebuah program GUI (Graphical User Interface) menggunakan MATLAB untuk mengecek dan menampilkan tahun kabisat (Leap Year).

👉 Tahun kabisat (Leap Year) adalah tahun dengan 366 hari, bukan 365. Tambahan 1 hari ada di bulan Februari (29 hari, bukan 28).
Hal ini terjadi karena bumi mengelilingi matahari bukan tepat 365 hari, melainkan sekitar 365 hari 5 jam 48 menit 46 detik.

Dengan program ini, user cukup memasukkan tahun awal dan jumlah tahun yang ingin dicek, lalu aplikasi akan menampilkan mana saja yang merupakan tahun kabisat.

🎯 Fitur

Input jumlah tahun yang akan dicek.

Input tahun pertama sebagai titik awal perhitungan.

Output berupa daftar tahun kabisat dan bukan kabisat.

Tampilan GUI sederhana dan interaktif.

🧮 Logika Perhitungan Leap Year

Aturan dasar:

Jika tahun habis dibagi 400 → tahun kabisat ✅

Jika tahun habis dibagi 100 tapi tidak 400 → bukan kabisat ❌

Jika tahun habis dibagi 4 tapi tidak 100 → tahun kabisat ✅

Selain itu → bukan kabisat ❌

Contoh:

2000 → kabisat (karena habis dibagi 400)

1900 → bukan kabisat (habis dibagi 100 tapi tidak 400)

2024 → kabisat (habis dibagi 4 tapi tidak 100)

2023 → bukan kabisat (tidak habis dibagi 4)

🖥️ Contoh Tampilan Output

Jika input:

Tahun mulai: 2000

Jumlah tahun: 10

Maka hasil:

2000 → Kabisat
2001 → Bukan Kabisat
2002 → Bukan Kabisat
2003 → Bukan Kabisat
2004 → Kabisat
2005 → Bukan Kabisat
2006 → Bukan Kabisat
2007 → Bukan Kabisat
2008 → Kabisat
2009 → Bukan Kabisat

🚀 Cara Menjalankan

Clone repository ini:

git clone https://github.com/patricxp/leap_year_GUI_matlab.git


Buka file .mlapp di MATLAB.

Jalankan aplikasi GUI.

Masukkan tahun awal dan jumlah tahun yang ingin dicek → Klik tombol mulai → Hasil akan muncul di text area.
