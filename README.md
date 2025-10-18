# PBOPertemuan9
# JasperReport
JasperReport adalah library Java yang digunakan untuk membuat, menampilkan, dan mencetak laporan (report) dari berbagai sumber data, seperti database, file XML, atau collection data Java.
Laporan ini bisa dihasilkan dalam berbagai format seperti PDF, HTML, Excel, CSV, atau Word.  

🔹 Fungsi utama:  

- Mengolah data dari database dan menampilkannya dalam bentuk laporan.  

- Menyediakan format laporan yang profesional (tabel, grafik, logo, dll).  

- Dapat diintegrasikan langsung dengan aplikasi Java (NetBeans, Eclipse, dll).
# iReport  
iReport Designer adalah aplikasi visual (GUI) untuk membuat desain laporan JasperReport.
Dengan iReport, pengguna tidak perlu menulis kode manual untuk membuat laporan, cukup dengan drag and drop elemen seperti teks, tabel, gambar, dan field database.  

🔹 Fungsi utama:  

- Mendesain tampilan laporan (layout, header, footer, tabel, grafik).  

- Menghubungkan laporan dengan database menggunakan koneksi JDBC.  

- Meng-compile file .jrxml menjadi .jasper.  
# JDesktopLayout

JDesktopLayout atau lebih tepatnya JDesktopPane adalah komponen dalam Java Swing yang digunakan untuk membuat tampilan desktop multi-jendela (Multiple Document Interface / MDI) di dalam satu JFrame utama.  

🔹 Fungsi utama:  

- Menampung beberapa JInternalFrame (jendela kecil di dalam satu jendela utama).  

- Cocok untuk aplikasi besar seperti sistem kasir, manajemen data, atau sistem laporan, di mana banyak form atau laporan bisa dibuka bersamaan.  
# Langkah - Langkah Project
1.	Unduh terlebih dahulu iReport dan Jdesktop layout, kemudian ekstrak file tersebut 
2.	Buka aplikasi neatbeans kemudian masuk ke bagian tools – plugin – downloaded
 

3.	Tambahkan Plugin iReport dan JDesktop yang tadi telah di ekstrak
 

4.	Kemudian install dan neatbeans akan meminta restart ulang 
5.	Lihat apakah berhasil mendownload plugin dengan cara masuk ke instaled kemudian centang show details dan pastikan keempat plug-in JasperReports, pastikan statusnya Activate.
 
Dan 

6.	Pada project klik kanan pada bagian package dan klik kanan lalu New – Report Wizard. (Jika belum ada, klik other lalu cari Report dan pilih Report Wizard)
 

7.	Pilih Layout atau template yang diinginkan kemudian next
 



8.	Ubah nama file sesuai kebutuhan kalian kemudian next
 

9.	Pilih koneksi yang terhubung ke postgre jika belum ada klik button new kemudian pilih Database JDBC connection dan next
 

10.	Kemudian isi data koneksi sesuai arahan dan test apakah koneksi berhasil jika sudah klik save 
 

11.	Isi query sql yang telah terhubung ke database kemudian next
 

12.	Pindahkan seluruh field data dari kiri ke kanan, dan klik next
 

13.	Langsung next 
 



14.	Finish
 

15.	Design tampilan laporan semenarik mungkin dan jika ingin melihat hasilnya bisa klik preview 
 

16.	Buat button cetak pada design Jframe
 

17.	Kemudian pada button cetak tambahkan program berikut dan sesuaikan dengan 
 

18.	Tambahkan import net.sf.jasperreports.engine.JRException pada bagian atas program 
 

kemudian download dan tambahkan library berikut 
 
19.	Kemudian jalankan program Jframe dan klik button cetak, akan muncul Tampilan Jasper Reports yang tadi telah dibuat 
 

