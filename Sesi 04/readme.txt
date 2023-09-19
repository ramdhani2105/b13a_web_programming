Mengapa Algoritma ?
-Algoritma adalah inti dari ilmu komputer
-Algoritma adalah urutan-urutan dari instruksi atau langkah-langkah untuk menyelesaikan suatu masalah
-Algoritma adalah blueprint dari program
-Sebaiknya disusun sebelum membuat program

Kriteria Algoritma
-Ada input dan output
-Efektifitas dan efisien
-Terstruktur

Contoh lagi : Algoritma TUKAR ISI EMBER



Diberikan 2 buah ember A dan B, ember A berisi larutan berwarna merah, 
ember B berisi larutan berwarna biru. Tukarkan isi kedua ember itu sedemikian  
sehingga ember A berisi larutan warna biru dan ember B berisi larutan berwarna merah.

Deskripsi:
Tuangkan larutan dari ember A ke dalam ember B
Tuangkan larutan dari ember B ke dalam ember A
Algoritma TUKAR ISI EMBER di atas tidak menghasilkan pertukaran yang benar.
Langkah di atas tidak logis, hasil pertukaran yang terjadi adalah pertukaran  
kedua larutan tersebut.

Supaya logis seperti apa ?

Deskripsi:
Tuangkan larutan dari bejana A ke dalam ember C.
Tuangkan larutan dari bejana B ke dalam ember A.
Tuangkan larutan dari bejana C ke dalam ember B.

<h1>Belajar Algoritma Nilai</h1>
<script>
    // var bs diubah (diluar scope)
    // let bs diubah (didalam scope)
    // const tidak bisa diubah (wajib assign data)

    var nama
    nama = "arif"
    let result
    if (nama == "arif") {
        result = "benar"
        // console.log(result)
    }
    console.log(result)
q
    let index = 1
    const a = index
    console.log(a)

    for (index = 0; index < 5; index++) {
        result = "looping";
        console.log(result)
    }
    result = "selesai"
    console.log(index)
    index = 20
    console.log(index)
    // a = 20
    console.log(a)

    // deklarasi awal
    var nama //data tidak ada (blm assign) > undefined
    //assign data
    nama = "arif"

    // batas
    var nama = "arif"
    var nilai = 50
    var result2 = "tidak lulus"
    if (nilai >= 60) result2 = "lulus"
    // else result = "tidak lulus"
    console.log("Data Keterangan : " + result2)
</script>
================================================================================================================

<h1>Belajar Membuat JS</h1>
<script>
    var hungry = true
    var result = "tidak makan"
    if (hungry) result = "makan"
    console.log("i`am happy");
</script>

=================================================================================
catatan :

algoritma kelulusan : cek nilai

variabel nama : wajib input > arif
variabel nilai mahasiswa : wajib input number > 80 ABC (diinput huruf)

logic :

langkah pertama > version 1.0
1. jika nilai >= 60 maka "keterangan : lulus"
2. jika nilai < 60 maka "keterangan : tidak lulus"

//pseudocode
//deklarasi dan assign
read and save nama, nilai, result 
//logic and condition
compute checking nilai
//assign result
save result
//output (console)
show result

//kode menggunakan javascript
var nama = "arif"
var nilai = 80
var result
if (nilai >= 60) result = "lulus"
else result = "tidak lulus"
console.log("Data Keterangan : "+result)

//unit testing

langkah kedua > version 2.0
1. jika nilai >= 60 && <= 100 maka "keterangan : lulus"
    > diluar inputan > 100 (101) > "keterangan : data tidak sesuai"
2. jika nilai >= 0 && < 60 maka "keterangan : tidak lulus"
    > disaat diinput -1 maka "keterangan : data tidak sesuai"

langkah ketiga > version 3.0
1. jika nilai >= 60 && <= 100 maka "keterangan : lulus"
    > diluar inputan > 100 (101) > "keterangan : data tidak sesuai"
2. jika nilai >= 0 && < 60 maka "keterangan : tidak lulus"
    > disaat diinput -1 maka "keterangan : data tidak sesuai"
3. jika inputan nilai bukan bertipe integer (number) maka "keterangan : data tidak sesuai"


===========================================================================

<h1>Belajar JS Score MySelf</h1>
<script>
    var score = 70
    var result = "reward myself"
    if (score < 70) result = "learn more"
    console.log(result)
</script>

======================================= TUGAS MANDIRI ====================================
durasi waktu 08:45
boleh browsing (present jika udah selesai)

1. judul algoritma (done)
    > heading / paragraf / yg lainnya
    > menghitung luas dan keliling lingkaran
2. inputan menghitung luas dan keliling lingkaran
    > deklarasi variabel dan assign data
3. kalkulasi
    > proses > assign result
4. output
    > alert / console / by html

1. flow / alur / narasi (wajib)
2. pseudocode (wajib)
3. koding (optional)
4. optimize / custom  (optional)


