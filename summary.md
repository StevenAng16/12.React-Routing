React Routing

1. Router merupakan modul dalam react yang berfungsi untuk melakukan proses navigasi pada SPA (Single Page Application).

2. Jenis React Router dan fungsi
    BrowserRouter digunakan sebagai router yang menggunakan API history dari HTML5, sehingga dapat menggunakan location untuk sinkronkan UI dengan url.
    Route digunakan sebagai pengarah jalan nya lalu lintas suatu aplikasi web.
    Switch atau Routes digunakan untuk membungkus kumpulan beberapa component Route.
    Link digunakan untuk berpindah antar halaman, property to tersebut merujuk pada path di route yang akan dituju.

3. Jenis Hook Routing React dan jelaskan
    useHistory memberi kita akses ke instance riwayat dapat digunakan untuk bernavigasi.
    useParams mengembalikan objek pasangan kunci/nilai parameter URL dapat digunakan untuk mengakses match.params dari Route saat ini.
    useRouteMatch mencoba mencocokan URL saat ini dengan cara yang sama seperti Route dapat berguna untuk mendapatkan akses ke data kecocokan tanpa benar-benar merender Route.
