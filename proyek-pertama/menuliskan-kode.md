#### Menuliskan Kode

1. Membuka file `kt` dan melihan kontennya, menelusuri maknanya
2. Mengubah teks pada `textView` dengan `id.text = "Sesuatu"` 
3. Mencoba menjalankan aplikasi
4. Membuat `array` di Kotlin menggunakan `arrayListOf()` dengan nama value/variabel bebas, `val langList = ...` 
5. Membuat metoda ketika `button` di klik dengan `id.setOnClickListener { }` 
6. Menambahkan fitur random untuk memunculkan angka yang acak ketika `button` tersebut di klik dengan cara `val random = Random()` lalu mengambil angka acak dari `langList` dengan cara `val randomLang = random.nextInt(langList.count())`
7. Setelah itu, pasang `langList[randomLang]` ke `textView` yang telah disiapkan
8. Mencoba menjalankan aplikasi
9. Menambahkan kata dari `editText` ke `langList` dengan cara menambahkan metoda pada `button` menambah bahasa dengan `setOnClickListener()`
10. Penambahan ke `array` sederhana dilakukan dengan `langList.add()` dengan elemen yang ditambahkan diambil dari `editText` yang telah diubah menjadi `String` dengan menggunakan `id.text.toString()`
11. Setelah ditambahkan ke `array` maka, kosongkan tulisan di dalam `editText` dengan `id.text.clear()`



