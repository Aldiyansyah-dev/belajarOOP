# Aldiyansyah-dev

# Pendahuluan

- OOP adalah gaya pemrogramman atau paradigma pemrograman

- procedural programming

1. intruksi dilakukan langkah demi langkah
2. memecah program menjadi bagian - bagian kecil
3. disebut prosedurm subroutine atau function
4. linear / top-bottom
   fortran, ALgol, cobol, pascal, c, php, javascript

- kelebihan procedural programming

1. to the point
2. simplicity & kemudahan implementasi (untuk compiler & interpreter)
3. mudah ditelusuri
4. membutuhkan lebih sedikit memory (dibandingkan dengan OOP)

- Object Oriented Programming

1. menyusun semua kode program struktur data sebagai objek
2. objek adalah unit dasar dari program
3. objek menyimpan data dan perilaku
4. objek bisa saling berinteraksi
5. java, ruby, python, c++, javascript, php5

- kelebihan OOP

1. Representasi dunia nyata
2. enkapsulasi & abstraksi data
3. reusability
4. skalabilitas & ektensibilitas
5. kemudahan pengelolaan
6. kolaborasi
7. digunakan oleh framework

# procedural VS object oriented

tergantung kebutuhan lebih cocok yang mana yang kita pilih

# konsep OOP pada PHP ?

1. Basic

   - class & object
     #class
     - blueprint / template untuk membuat instance dari object
     - class mendefinisikan object
     - menyimpan data dan perilaku yang disebut dengan property dan method
       contoh membuat class:
       a. diawali dengan menuluskan keyword class, diikuti nama dan dibatasi dengan {} untuk menyimpan property dan method
       b. aturan penamaan class sama seperti variabel

   #object

   - instance yang didefinisikan oleh class
   - banyak object dapa dibuat menggunakan satu class
   - object dibuat dengan menggunakan keyword new

   * property & method
     #property

   - merepresentasikan data / keadaan dari sebuah object
   - variabel yang ada di dalam object (member variable)
   - sama seperti variabel di dalam PHP, ditambah dengan visibility di depannya

   #method

   - merepresentasikan perilaku dari sebuah object
   - function yang ada di dalam object
   - sama seperti function di dalam PHP, ditambah dengan visibility di depannya.

   contoh :
   property

   - nama
   - merk
   - warna
   - kecepatanMaksimal
   - jumlahPenumpang

   method

   - tambahKecepatan
   - KurangiKecepatan
   - gantiTransmisi
   - belokKiri
   - belokKanan

   * constructor
     method yang otomatis dijalankan ketika sebuah class instansiasi

   * object type
     tipe data primitif dan tipe data array

   * inheritance

   - Menciptakan hirarki antar kelas ( parent & child)
   - child class, mewarisi semua properti dan method dari parentnya ( yang visible)
   - child class, memperluas (extends) fungsionalitas dari parentnya

   * visibility / access

   - konsep yang digunakan untuk mengatur akses dari property dan method pada sebuah objek
   - ada 3 keyword visibility : public, protected, dan private

   # public

   a. public, dapat digunakan dimana saja, bahkan diluar kelas untuk semuanya
   b. protected, hanya dapat digunakan didalam sebuah kelas beserta turunannya
   c. private, hanya dapat digunakan di dalam sebuah kelas tertentu saja ( satu kelas )

   # kenapa ?

   - hanya memperlihatkan aspek dari class yang dibutuhkan oleh "client"
   - menentukan kebutuhan yang jelas untuk object
     -memberikan kendali pada kode untuk menghindari bug

   - setter & getter
   - static method

2. Advanced

   - abstract & interface
   - interceptor
   - object cloning
   - callbacks & closures
   - namespaces & autoloading

# belajarOOP

# belajarOOP
