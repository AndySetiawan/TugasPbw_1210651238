TugasPbw
========

Analisa Program

1. Buat database latihan
2. Membuat table pengguna, artikel dan bukutamu
3. Merubah $dbpassword = "root"; menjadi $dbpassword = ""; pada koneksii.php
4. Menambah echo "<br>" menjadi echo "<br\>"; pada line 13 di prosesdaftar.php
5. Merubah while ($row=mysql_fetch_array($queryartikel)) { menjadi while ($row=mysql_query($queryartikel)) { pada line ke 58 di index.php
6. Menambah <label>Id Pengguna :</label>
<input type="text" name="id" class="form-control" placeholder="Id Pengguna"> (pada line 49 dan 50 di daftar.php).
7. Menambah $id = $_POST['id']; pada line ke 5 di prosesdaftar.php.
8. Query untuk prosesdaftar nya : mysql_query("insert into pengguna values ('$id','$name','$username','$password','member')");
9. }else{
echo "Maaf, pendaftaran anggota gagal" .mysql_error(); (menambah .mysql_error untuk mengetahui kesalahan jika terjadi kegagalan pada saat proses daftar).
10. Merubah while ($row=mysql_fetch_array($queryartikel)) di blog.php menjadi while ($row=mysql_query($queryartikel)) (karena index.php juga mysql_query).
11. Menambah echo "klik <a href='index.php'>disini</a> untuk kembali ke beranda"; di prosesbuktamu.php pada line ke 27 untuk bisa kembali lagi ke beranda setelah mengisi buku tamu.
12. Pada blog.php line 33 saya merubah <li ><a href="blog.php">Blog</a></li> menjadi <li class="active"><a href="blog.php">Blog</a></li> (agar pada saat saya klik menu blog agar menunjukkan bahwa menu blog sedang aktif).
13. Pada bukutamu.php line 31 saya merubah <li><a href="bukutamu.php">Bukutamu</a></li> menjadi 
<li class="active"><a href="bukutamu.php">Bukutamu</a></li>  (agar pada saat saya klik menu bukutamu agar menunjukkan bahwa menu bukutamu sedang aktif).
14. Saya menambahkan <li><a href="upload.php">Upload</a></li> di index.php pada line ke 35 agar member bisa mengupload file mereka.
