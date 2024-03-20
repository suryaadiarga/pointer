# laporantugas

SS code :
![Screenshot 2024-03-20 081644](https://github.com/suryaadiarga/pointer/assets/164111261/78696dee-411a-4e97-a870-f9302512421c)
![Screenshot 2024-03-20 081659](https://github.com/suryaadiarga/pointer/assets/164111261/a83bcd16-c682-4dea-bb22-ca6929cc6482)

SS output :
![Screenshot 2024-03-20 075506](https://github.com/suryaadiarga/pointer/assets/164111261/c1ae4aab-9c08-4052-8e54-73b67689b6ea)
![Screenshot 2024-03-20 075655](https://github.com/suryaadiarga/pointer/assets/164111261/e8a1d861-1aec-48ed-a6d3-838bcabc29ca)
![Screenshot 2024-03-20 075536](https://github.com/suryaadiarga/pointer/assets/164111261/43c67fb7-fe44-461d-95ed-57f79c7aa6cf)

Penjelasan Kode :
Pada program diatas  terdapat beberapa fungsi dan kode yang memiliki tugas masing – masing, yaitu :
1. Fungsi `lessThanRequired()`, `equalThanRequired()`, dan `moreThanRequired()`:
   - Fungsi `lessThanRequired()` digunakan untuk mencetak pesan bahwa panjang teks kurang dari yang ditentukan.
   - Fungsi `equalThanRequired()` digunakan untuk mencetak pesan bahwa panjang teks sesuai dengan yang ditentukan.
   - Fungsi `moreThanRequired()` digunakan untuk mencetak pesan bahwa panjang teks melebihi yang ditentukan.

2. Fungsi `checkLenghtRequirement(char* text)`:
   - Fungsi ini digunakan untuk memeriksa panjang teks yang diberikan sebagai argumen.
   - Jika panjang teks kurang dari `MIN_LENGTH`, fungsi akan mengembalikan nilai 0.
   - Jika panjang teks sama dengan `MIN_LENGTH`, fungsi akan mengembalikan nilai 1.
   - Jika panjang teks lebih dari `MIN_LENGTH`, fungsi akan mengembalikan nilai 2.

3. Bagian `main()`:
   - Program membuka file "file.txt" dan membaca teks dari file tersebut.
   - Kemudian, program memanggil fungsi `checkLenghtRequirement()` untuk memeriksa panjang teks.
   - Berdasarkan nilai yang dikembalikan oleh `checkLenghtRequirement()`, program memilih untuk menjalankan salah satu dari tiga fungsi cetak pesan yang telah disebutkan di atas menggunakan array pointer ke fungsi `function[selectOption]()`.
   - Program juga menghitung dan memperbarui nilai `lengthOfText` sesuai dengan persyaratan yang diberikan, menggunakan operasi aritmatika.

Pada bagian yang ditandai sebagai `TODO`, terdapat instruksi untuk menampilkan pesan sesuai dengan nilai yang dikembalikan oleh `checkLenghtRequirement()` tanpa menggunakan pernyataan `if` atau `switch`. Selain itu, nilai `lengthOfText` juga harus diperbarui sesuai dengan instruksi yang diberikan.
