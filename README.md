# Khairunnisa Labibah

## Introducing Sudoku
Pembuat puzzle asal Indiana, Howard Garns, yang kini sudah setengah perjalanan pensiun, menciptakan Sudoku pada tahun 1979. Numbers, permainan yang pertama kali muncul di majalah Prancis pada tahun 1800-an, adalah cikal bakal Sudoku. Meskipun mirip dengan Sudoku, Numbers membutuhkan aritmatika daripada penalaran untuk memecahkan teka-teki, dan angka dua digit kadang-kadang muncul.

Sayangnya, Howard Garns meninggal dunia sebelum inovasinya digunakan secara luas. Teka-teki ini pertama kali diterbitkan secara teratur di sebuah surat kabar Jepang pada pertengahan tahun 1980-an, dan Maki Kaji memberinya nama Sudoku. Sudoku tidak kembali ke Amerika Serikat dan mulai populer di seluruh dunia hingga akhir 1990-an dan awal 2000-an.

## How To Play Sudoku
Sudoku dimainkan di atas petak-petak berukuran 9x9 yang juga dibagi menjadi 9 bagian berukuran 3x3. Tujuan permainan ini adalah untuk mencari cara menempatkan angka 1 sampai 9 pada kotak sehingga setiap angka muncul tepat satu kali di setiap baris, kolom, dan bagian 3x3. Permainan akan dimulai dengan sejumlah kotak yang sudah terisi; kotak-kotak ini terkunci. Secara umum, semakin sedikit bagian yang Anda selesaikan di awal, semakin sulit permainannya. Tentu saja, ada satu hal penting: ketika jumlah kotak yang terisi terlalu sedikit, banyak solusi yang benar akan muncul dan permainan menjadi lebih mudah lagi.

## Sudoku-AI
Language : Python-3

Bahasa Kotak Sudoku disajikan sebagai bahasa pemrograman yang berbasis python. Komponen kunci dari kamus yang disebutkan adalah variabel nama-nama, yang masing-masing terhubung langsung ke lokasi di peta. Dengan kata lain, kita menggunakan nama Al sampai A9 untuk bar bagian atas (kanan) dan I1 sampai I9 untuk bar bagian bawah. Sebagai contoh, pada contoh teka-teki di atas, kita akan memiliki sudoku["B1"] = 9 dan sudoku["E9"] = 8. Untuk menghidupkan kembali petak-petak yang tidak terisi, digunakan sudut 0.

## How To Play Sudoku-AI
Pertama, Kita harus menerjemahkan teka-teki Sudoku yang ingin kita pecahkan ke dalam sebuah string satu dimensi, di mana kotak kosong diwakili oleh tanda "." . Kita akan membaca teka-teki Sudoku dari kiri ke kanan dan ke bawah halaman seperti sebuah buku untuk memasukkannya ke dalam format kotak yang tepat. 

Selanjutnya, kita akan membuat teka-teki Sudoku menggunakan string kisi-kisi dengan menginstansiasi objek Sudoku. AI solver dapat diinstal dengan cara yang sama dan dapat digunakan untuk memecahkan beberapa teka-teki Sudoku.

Terakhir, masukkan teka-teki tersebut ke dalam Sudoku AI. Ini akan mencetak solusi ke sudokut.
