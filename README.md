# counter_7

# Jelaskan apa yang dimaksud dengan stateless widget dan stateful widget dan jelaskan perbedaan dari keduanya.
  Stateless widget bersifat static atu tidak akan berubah. Contohnya adalah Icon, IconButton, Text. class dari stateless widget adalah StatelessWidget.
  Sedangkan stateful widget bersifat dynamic dan berubah sesuai dengan interaksi pengguna dengan tampilan yang telah kita buat. 
  Contohnya adalah Checkbox, Radio, Slider, InkWell, Form, dan TextField. class dari stateful widget adalah StatefulWidget.
  
 # Sebutkan widget apa saja yang kamu pakai di proyek kali ini dan jelaskan fungsinya.
 
  1. Text
      
Untuk memunculkan text berupa string pada display dengan berbagai style yang dapat kita customize
  
  2. Stack
  
Untuk membuat beberapa button dalam suatu frame. Selain itu, kita dapat menggunakan childclass nya yaitu Positioned untuk memposisikan 
masing-masing button.

# Apa fungsi dari setState()? Jelaskan variabel apa saja yang dapat terdampak dengan fungsi tersebut.
Pada dasarnya setState adalah untuk mengupdate value dari varible pada script yang kita jalankan. Dengan adanya setState, framework menerima sinyal
perubahan terhadap state, setelah itu framework akan me-rerun build nya sehingga value dari variable tersebut terupdate pada display. Jika setState
tidak dipanggil, maka framework tidak akan me-rerun build nya dan value dari variable tersebut tidak akan terupdate pada display.

Pada program flutter yang telah saya buat, saya melibatkan setState pada dua method, yang pertama adalah method _incrementCounter dan 
yang kedua adalah _decrementCounter. Kedua method tersebut digunakan untuk mengubah value dari variable _counter yang program miliki.

# Jelaskan perbedaan antara const dengan final
Const dapat hanya dapat dipakai ketika value dari variable tersebut sudah terdeklarasi dan konstan. Sedangkan final dapat dipakai ketika
value dari sebuah variable belum terdeklarasikan. Sebagai contoh, DateTime.now merupakan suatu object tanggal yang memberikan value yang
berbeda setiap variable dipanggil. Ketika kita menggunakan const, akan me return error karena value dari variable tersebut tidak konstan. Sedangkan
akan berjalan dengan baik jika kita menggunakan final.

# Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas.
  1. Jalankan flutter create counter_7 pada folder yang diiinginkan,
  2. Membuka folder yang telah terbuat pada andorid studio dan membuka file main.dart,
  3. Membuat method baru bernama _decrementCounter yang digunakan untuk decrement variable counter pada class _MyHomepageState,
  4. Membuat button baru dengan menambahkan widget stack sebagai tempat dari button-button tersebut,
  5. Menghubungkan button dengan method yang telah kita buat,
  6. Memposisikan button tersebut,
  7. Membuat conditionals untuk keluaran Ganjil atau Genap pada display beserta style warnanya.
  
