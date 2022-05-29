## Marketplace - Local Pride Store

## Anggota Kelompok 
Rizki Januar Irmansyah		20051397046
Muhammad Yogi Firmansyah  20051397036
Fahmi Fahqur Rozi         20051397060

## Deskripsi Aplikasi Kami

Website Local Pride Store adalah marketplace yang sedarhana dimana disitu dapat menjual produk produk buatan lokal seperti contohnya baju, kaos, jam tangan, hodie, jaket dan lain sebagainya.
Untuk usernya kami membuat hanya admin dan user saja, mungkin untuk tahap selanjtnya bisa dikembangkan lagi untuk role user sebagai mitra.
Dan payment gatewaynya kami membuat Plugin Tripay, dimana Tripay disini adalah aplikasi pihak ketiga untuk melakukan pembayaran transaksi.
Pembuatan aplikasi ini menggunakan Tech PHP v.8, Laravel v.8, Composer v.2, dan beberapa tech lainnya.

## Cara Menjalankan Program
Aplikasi berbasis Website “Local Pride Store” yang bisa diakses menggunakan Browser. Adapun browser yang direkomendasikan yaitu Google Chrome pada link berikut : http://103.186.0.136/
Kenapa kami menggunakan IP? Kami sedikit ada kendala pada bag deployment yang dimana harusnya me-dump dari github langsung ke domain akan tetapi kami lupa pada saat itu dan akhirnya kami bikin manual di folder public nya.
Apakah Aman dengan ip tersebut? Kami rasa aman karena mungkin tidak terlalu perlu untuk security yang hold dan untuk ip tersebut adalah menggunakan ip public dari sub domain yang telah kami  rancang.

## Cara Menjalankan Program ini di Local
1. git clone (url_github)
2. composer install / untuk menginstall semua depedency
3. cp .env.example .env / untuk mengcopy file .env example ke .env
4. php artisan key:generate / untuk me-generate key yang ada di .env
5. buat database di mysql
6. edit name databasenya di env sesuai di mysqlnya
7. php artisan migrate --seed / untuk meinport semua table datbase dan kawan kawanya secara otomatis
8. php artisan serve / untuk menjalankan live servernya

