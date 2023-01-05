Tujuan :
Tujuan dari tugas ini adalah untuk membangun sebuah sistem rekomendasi yang dapat memberikan rekomendasi film kepada pengguna berdasarkan rating film yang telah diberikan oleh pengguna lain, serta konten dari film tersebut.

Mekanisme :
Untuk mencapai tujuan tersebut, kami akan menggunakan mekanisme hybrid Colaborative Filtering dan Content Based Filtering yang dikemas dalam arsitektur pipelined.

Mekanisme Colaborative Filtering akan menggunakan rating film yang telah diberikan oleh pengguna lain untuk menentukan film-film yang disukai oleh pengguna tersebut, dan kemudian mencari film-film lain yang disukai oleh pengguna-pengguna lain yang memiliki preferensi yang sama.

Sedangkan mekanisme Content Based Filtering akan menggunakan konten dari film, seperti judul, genre, dan deskripsi, untuk mencari film-film yang memiliki konten yang sama dengan film yang disukai oleh pengguna.

Kedua mekanisme tersebut akan dikemas dalam arsitektur pipelined, yang akan memecah proses rekomendasi menjadi beberapa tahap yang dijalankan secara paralel.

Penggunaan :
Untuk menggunakan sistem rekomendasi ini, pengguna hanya perlu memasukkan ID film yang telah ditonton dan memberikan rating untuk film tersebut. Sistem akan menghasilkan daftar film yang direkomendasikan kepada pengguna berdasarkan mekanisme hybrid Colaborative Filtering dan Content Based Filtering yang telah diimplementasikan.

[Dataset](https://files.grouplens.org/datasets/movielens/ml-latest-small.zip) :
Dataset yang digunakan dalam tugas ini adalah ml-latest-small.zip, yang berisikan empat file CSV: ratings.csv, tags.csv, movies.csv, dan links.csv.

File ratings.csv berisi rating film yang telah diberikan oleh pengguna, termasuk ID pengguna, ID film, dan rating.

File tags.csv berisi tag yang diberikan oleh pengguna untuk setiap film, termasuk ID pengguna, ID film, dan tag.

File movies.csv berisi informasi mengenai film, termasuk judul, genre, dan deskripsi.

File links.csv berisi tautan ke situs-situs IMDB dan Wikipedia untuk setiap film.


