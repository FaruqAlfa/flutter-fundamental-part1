# Pertemuan 6
A new Flutter Project

Nama: Mukhamad Faruq Al Fahmi
Kelas: 3D
Absen: 25
NIM: 2141720066
## Praktikum 1 - Membuat Project Flutter Baru

### Langkah 1

![Screenshot hasil praktikum 1](images/praktikum%201.png)


## Praktikum 2 - Membuat Repository GitHub dan Laporan Praktikum

### Langkah 1
![Screenshot hasil praktikum 2](images/Praktikum%202/Langkah%201.png)

### Langkah 2
![Screenshot hasil praktikum 2](images/Praktikum%202/Langkah%202.png)

### Langkah 3
![Screenshot hasil praktikum 2](images/Praktikum%202/Langkah%203.png)

### Langkah 4
![Screenshot hasil praktikum 2](images/Praktikum%202/Langkah%204.png)

### Langkah 5
![Screenshot hasil praktikum 2](images/Praktikum%202/Langkah%205.png)

### Langkah 6
![Screenshot hasil praktikum 2](images/Praktikum%202/Langkah%206.png)

### Langkah 7
![Screenshot hasil praktikum 2](images/Praktikum%202/Langkah%207.png)

### Langkah 8
![Screenshot hasil praktikum 2](images/Praktikum%202/Langkah%208.png)
![Screenshot hasil praktikum 2](images/Praktikum%202/Langkah%208-1.png)

### Langkah 10
![Screenshot hasil praktikum 2](images/Praktikum%202/Langkah%2010.png)

### Langkah 12
![Screenshot hasil praktikum 2](images/Praktikum%202/Langkah%2011.png)


## Praktikum 3 - Menerapkan Widget Dasar


### Langkah 1 - Text Widget
![Screenshot hasil praktikum 3](images/Praktikum%203/kode%20langkah%201.png)
![Screenshot hasil praktikum 3](images/Praktikum%203/Langkah%201.png)
Kode tersebut adalah implementasi sebuah widget Flutter yang disebut MyTextWidget. Widget ini merupakan turunan dari kelas StatelessWidget dan memiliki satu metode, yaitu build, yang mendefinisikan tampilan widget. Di dalamnya, terdapat widget Text yang menampilkan teks "Nama saya Fulan, sedang belajar Pemrograman Mobile". Teks ini memiliki gaya tertentu yang ditentukan oleh objek TextStyle, di mana warna teks diatur menjadi merah (Colors.red) dan ukuran font sebesar 14.

Selain itu, teks tersebut ditempatkan secara terpusat di layar melalui properti textAlign: TextAlign.center. Keseluruhan widget dirancang untuk digunakan dalam aplikasi Flutter untuk menampilkan teks dengan gaya dan tata letak tertentu.

Secara keseluruhan, MyTextWidget dapat digunakan sebagai komponen reusable yang memudahkan penataan dan penentuan gaya teks dalam aplikasi Flutter. Pemisahan antara logika tampilan dan logika bisnis dapat meningkatkan keterbacaan dan pemeliharaan kode.

### Langkah 2 - Image Widget
![Screenshot hasil praktikum 3](images/Praktikum%203/kode%20langkah%202.png)
![Screenshot hasil praktikum 3](images/Praktikum%203/Langkah%202.png)
kode di atas mempunyai makna yang sama dengan langkah 1 namun pada langkah 2 ini menampilkan gambar bukan text

## Praktikum 4 - Menerapkan Widget Material Design dan iOS Cupertino

### Langkah 1 - Cupertino Button dan Loading Bar
![Screenshot hasil praktikum 3](images/Praktikum%204/Langkah%201.png)
Kode tersebut adalah implementasi dasar dari sebuah aplikasi Flutter menggunakan widget MaterialApp. Aplikasi ini memiliki tampilan berupa layar tunggal (home) yang berisi sebuah kontainer (Container) dengan margin atas sejauh 30 piksel dan latar belakang berwarna putih. Di dalam kontainer tersebut, terdapat suatu kolom (Column) yang berisi dua widget anak. Pertama, ada CupertinoButton yang menampilkan teks "Contoh button" dan mendefinisikan suatu fungsi onPressed kosong, yang akan dijalankan ketika tombol tersebut ditekan. Kedua, ada CupertinoActivityIndicator, yang merupakan indikator aktivitas berputar dan menandakan bahwa ada proses yang sedang berlangsung. Keseluruhan struktur ini menciptakan antarmuka sederhana dengan tombol dan indikator aktivitas di tengah-tengah layar. Penting untuk dicatat bahwa widget CupertinoButton dan CupertinoActivityIndicator adalah bagian dari desain tata letak dan tampilan khas iOS, meskipun diintegrasikan ke dalam proyek Flutter yang menggunakan MaterialApp.


### Langkah 2 - Floating Action Button (FAB)
![Screenshot hasil praktikum 3](images/Praktikum%204/Langkah%202.png)
Kode tersebut merupakan implementasi dasar dari sebuah aplikasi Flutter menggunakan widget MaterialApp dengan satu layar yang menggunakan Scaffold. Di dalam Scaffold, terdapat sebuah tombol tindakan mengambang (FloatingActionButton) yang, ketika ditekan, akan menjalankan kode yang ditentukan dalam fungsi onPressed. Saat tombol ditekan, sebuah ikon jempol ke atas (Icon(Icons.thumb_up)) akan ditampilkan di dalam tombol, dan latar belakang tombol akan diatur menjadi warna merah muda (Colors.pink). Keseluruhan struktur ini menciptakan antarmuka yang sederhana dengan tombol tindakan mengambang di tengah layar, yang dapat disesuaikan lebih lanjut dengan menambahkan logika ke dalam fungsi onPressed.


### Langkah 3 - Scaffold Widget
![Screenshot hasil praktikum 3](images/Praktikum%204/Langkah%203.png)
kode di atas (Scaffold widget) digunakan untuk mengatur tata letak sesuai dengan material design.


### Langkah 4 - Dialog Widget
![Screenshot hasil praktikum 3](images/Praktikum%204/Langkah%204.png)
Kode tersebut mengimplementasikan sebuah aplikasi Flutter dengan dua widget utama, yaitu MyApp dan MyLayout. Kelas MyApp merupakan turunan dari StatelessWidget dan berfungsi sebagai entry point aplikasi. Di dalamnya, terdapat sebuah widget MaterialApp dengan satu layar yang menggunakan Scaffold dan memuat widget MyLayout.

Kelas MyLayout merupakan turunan dari StatelessWidget dan membangun antarmuka pengguna sederhana yang berisi satu tombol tindakan ditinggikan (ElevatedButton). Ketika tombol tersebut ditekan, fungsi showAlertDialog dipanggil, yang menampilkan jendela peringatan (AlertDialog) dengan judul "My title" dan pesan "This is my message". Jendela peringatan ini juga berisi tombol "OK" yang, jika ditekan, akan menutup peringatan. Keseluruhan aplikasi menciptakan pengalaman pengguna yang sederhana dengan kemampuan untuk menampilkan peringatan saat tombol tertentu ditekan.


### Langkah 5 - Input dan Selection Widget
![Screenshot hasil praktikum 3](images/Praktikum%204/Langkah%205.png)
kode diatas di gunakan untuk membuat Text Field dimana kita dapat mengetikkan sebuah kalimat di dalamnya
dan apapun yang di inputkan di sini akan berupa tipe data string


### Langkah 6 - Date and Time Pickers
![Screenshot hasil praktikum 3](images/Praktikum%204/Langkah%206.png)
kode diatas diggunakan untuk membuat tanggal dan waktu yang di inginkan dan mengeset tanggal dan waktu ke masa yang sekarang