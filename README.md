# conditional
Tugas Membuat source code untuk menampilkan hasil konversi nilai kuliah pada halaman web dengan menggunakan kondisional IF-ELSE

<?php 
$nilai = 60;

if($nilai <= 50){
    echo "Nilai E <br>";
}
elseif($nilai >= 50 && $nilai <= 59){
    echo "Nilai D <br>";
}
elseif($nilai >= 60 && $nilai <= 69){
    echo "Nilai C <br>";
}
elseif($nilai >= 70 && $nilai <= 79){
    echo "Nilai  <br>";
}
elseif($nilai >= 80){
    echo "Nilai A <br>";
}
else {
    echo "Error <br>";
}
?>
