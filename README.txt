Project ini dikerjakan oleh :
20210801427 - Desnico Ferdiansyah
20210801429 - Dhimas Arya Priambodo

Project yang kami kerjakan berjudul Analisis Trend Pengiriman Jalur Udara bagi Manajemen Operasional. Diceritakan bahwa kami ditugaskan untuk mem-provide analisis data dari data yang diberikan oleh manajer operasional Air Cargo. 

Data mentah dapat dilihat pada file Excel "Dataset Project Analisis SMU SS". Data ini kami dapatkan dari salah seorang teman yang bekerja sebagai admin. Data ini mulanya hanya berisi 3 tahun. Kami menduplicate dan melakukan beberapa penyesuaian sehingga data ini menjadi berisi data 5 tahun.

File PDF "Perancangan Data Warehouse untuk Analisis Trend Pengiriman Jalur Udara bagi Manajemen Operasional" berisikan seluruh proses perancangan mulai dari Analisis Kebutuhan hingga Pembuatan Dashboard dengan penjelasan nya.

Kami menggunakan software Pentaho versi 9.4. File transformation dapat dilihat pada folder "File ktr".

Hasil Visualisasi data dapat dilihat pada file Excel "Dashboard Analisis Trend Air Cargo". File tersebut berisi beberapa fact table yang telah kita buat di database MySQL serta Pivot Table dan Pivot Chart dalam sheet terpisah.

Folder "File CSV" berisi beberapa file CSV untuk mendukung proses ETL.
Beberapa proses ETL mengalami beberapa error sehingga kami ketika membaca file data mentah untuk dimasukkan ke staging, sehingga kami menyeleksi secara manual untuk data apa saja yang dibutuhkan. Namun seluruh file ktr yang kami lampirkan, bisa dipastikan bekerja dengan normal ketika dijalankan.

Folder "Dokumentasi" berisi beberapa screenshot ketika kami menjalankan ETL. Kami tidak dapat melampirkan video proses ETL karena beberapa proses ETL memakan waktu yang sangat lama bahkan hingga 2 hari. Sehingga kami sudah melakukan ETL pada hari - hari sebelumnya. Kami juga melampirkan sample data pada setiap table.