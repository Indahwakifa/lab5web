# lab5web

**NAMA : INDAH WAFIKAH**

**NIM : 312410559**

**KELAS : TI.24.A.5**

**MATKUL: PROGRAM WEB 1**

![foto](https://github.com/Indahwakifa/lab5web/blob/e1b3f1e40dbf5880ab2dc69898e3a430d7f13d87/foto/jvs1.png)

**penjelasan**

```Penjelasan singkatnya

window.alert("...") → munculkan kotak pesan (alert box).

document.write("...") → tampilkan teks langsung di halaman web.

console.log("...") → kirim pesan ke console browser.
```

**gambar 2**

![foto](https://github.com/Indahwakifa/lab5web/blob/f8a622895af8094bb131ed2444d4bb679c69003f/foto/jvs2.jpg)

**penjelasan**

```Penjelasan:

document.write() menulis teks ke halaman web.

console.log() menampilkan teks ke “Console” di browser (F12 → tab Console).

eksternal.js dipanggil dari HTML pakai tag <script src="...">.

```

**gambar3**
![foto](https://github.com/Indahwakifa/lab5web/blob/1b114735fed3b18344fc68e17105bf3d2f306c4a/foto/jvs3.png)

**penjelasan**

```Penjelasan:

window.alert() → menampilkan pesan pop-up ke pengguna.

<!-- ... //--> adalah gaya lama untuk menyembunyikan script dari browser lama (nggak wajib di browser modern).

```

**gambar4**
![foto](https://github.com/Indahwakifa/lab5web/blob/0b53e008ae465005107683f824a925b6eae55046/foto/jvs4.png)

**penjelasan**

```Penjelasan:

document.write() digunakan untuk menulis langsung ke halaman web.

<br> untuk membuat baris baru.

```

**gambar 5**
![foto](https://github.com/Indahwakifa/lab5web/blob/e2c1e282fcd130a8a780592e24b3d5821762bfcd/foto/jvs5.png)

**penjelasan**

```
window.prompt("Siapa nama Anda?", ""); → munculin kotak input ke pengguna untuk ngetik nama.

Nilai yang kamu ketik disimpan ke variabel nama.

document.write("Hai, " + nama + "! ..."); → menampilkan hasil input di halaman web.


<!-- ... //--> → cuma gaya lama dari HTML supaya browser lama gak bingung (sekarang gak wajib, tapi tetap sama seperti di modul).
```

**gambar6**

![foto](https://github.com/Indahwakifa/lab5web/blob/80930ce026dbdfb0f3bf0ee655d0edc3a2f7d0c7/foto/jvs6.png)

**penjelasan**

```Penjelasan:

function pesan() → mendefinisikan fungsi bernama pesan.

alert("Memanggil fungsi JavaScript"); → menampilkan kotak pesan saat fungsi dijalankan.

Tombol <input type="button"> dipakai untuk memanggil fungsi saat diklik.
→ onclick="pesan()" artinya tombol itu akan menjalankan fungsi pesan().
```

**gambar7**

![foto](https://github.com/Indahwakifa/lab5web/blob/859fb262208f530ad035469b3acf70e73d20f234/foto/jvs7.png)

**penjelasan**

```Penjelasan:

var nilai1 = 10; var nilai2 = 5; → mendefinisikan dua variabel angka.

+ - * / → operator aritmatika (penjumlahan, pengurangan, perkalian, pembagian).

document.write() → menampilkan hasil di halaman web.
```
**gambar8**

![foto](https://github.com/Indahwakifa/lab5web/blob/2e397b5eccdef933381744703ef25186e025b00d/foto/jvs8.png)

**penjelasan**

```Penjelasan:

prompt("Masukkan nilai Anda:") → minta input dari pengguna.

if (nilai >= 60) → kalau nilainya 60 ke atas, berarti Lulus, kalau nggak, Tidak Lulus.

document.write() → menampilkan hasilnya di halaman web.
```

**gambar9**

![foto](https://github.com/Indahwakifa/lab5web/blob/fd690042898cc389e2833d03ea4a2a2e2e730481/foto/jvs9.png)

**penjelasan**

```Penjelasan:

switch (nilai) → memeriksa isi variabel nilai.

case "1": sampai case "5": → kondisi yang dicek.

break; → menghentikan pemeriksaan agar tidak lanjut ke case lain.

default: → digunakan kalau input tidak cocok dengan case manapun.
```
**gamabar10**

![foto](https://github.com/Indahwakifa/lab5web/blob/0f4f48176ad69e81cfa0b6c23440262750df6255/foto/jvs10.png)

**penjelasan**

```Penjelasan:

<input type="text" name="nama"> → tempat pengguna mengetik nama.

<input type="button" onclick="tampilkanData()"> → tombol untuk menjalankan fungsi JavaScript.

document.formData.nama.value → ambil nilai dari input nama.

document.write() → tampilkan hasil di halaman.
```

**gamabr11**
![foto](https://github.com/Indahwakifa/lab5web/blob/7f2e96c1807acf7b9b7b7aa4f3a74503ec6a892d/foto/jvs11.png)

**penjelasan**

```Penjelasan:

onsubmit="return validasi()" → saat tombol Kirim ditekan, fungsi validasi() dijalankan dulu.

if (nama == "" || email == "") → kalau salah satu kosong, tampilkan alert peringatan.

return false; → menghentikan pengiriman form kalau data belum lengkap.

return true; → lanjut kirim (atau tampil pesan sukses) kalau semua terisi.
```

**gambar12**
![foto](https://github.com/Indahwakifa/lab5web/blob/231f8075654f14be8ea2ad29f932c76e034f1a50/foto/jvs12.png)

**penjelasan**

```Penjelasan:

Setiap menu punya checkbox dan harga (value).

Saat checkbox diklik (onclick="hitungTotal()"), fungsi hitungTotal() dijalankan.

Fungsi itu menghitung semua checkbox yang dipilih, lalu menjumlahkan harganya.

Hasilnya ditampilkan otomatis di <span id="total">.
```


