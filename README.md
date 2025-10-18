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
 <img width="765" height="539" alt="image" src="https://github.com/user-attachments/assets/add9cad8-6261-4ece-9091-eb50eea570e0" />
 
3.	Tambahkan Plugin iReport dan JDesktop yang tadi telah di ekstrak
 <img width="828" height="324" alt="image" src="https://github.com/user-attachments/assets/8bf386ba-9df5-46fd-bb19-bfd7b072f8d7" />

4.	Kemudian install dan neatbeans akan meminta restart ulang 
5.	Lihat apakah berhasil mendownload plugin dengan cara masuk ke instaled kemudian centang show details dan pastikan keempat plug-in JasperReports, Dan pastikan statusnya Activate.
 <img width="584" height="216" alt="image" src="https://github.com/user-attachments/assets/fda3b715-6d39-4a0a-b282-2865d0bcaceb" />


6.	Pada project klik kanan pada bagian package dan klik kanan lalu New – Report Wizard. (Jika belum ada, klik other lalu cari Report dan pilih Report Wizard)
 <img width="825" height="523" alt="image" src="https://github.com/user-attachments/assets/60e3dc48-c140-40cc-b321-b89a0c657714" />


7.	Pilih Layout atau template yang diinginkan kemudian next
 <img width="914" height="653" alt="image" src="https://github.com/user-attachments/assets/571e5e46-2ed8-44cf-8380-70f1e1b409ae" />


8.	Ubah nama file sesuai kebutuhan kalian kemudian next
 <img width="863" height="628" alt="image" src="https://github.com/user-attachments/assets/9a23c040-b141-45ce-9f0e-66813e1eb035" />


9.	Pilih koneksi yang terhubung ke postgre jika belum ada klik button new kemudian pilih Database JDBC connection dan next
 <img width="856" height="660" alt="image" src="https://github.com/user-attachments/assets/ee11846a-866c-47f9-9edc-044276c632f9" />


10.	Kemudian isi data koneksi sesuai arahan dan test apakah koneksi berhasil jika sudah klik save 
 <img width="680" height="686" alt="image" src="https://github.com/user-attachments/assets/80304ea9-a293-472e-a209-36a8aa7f875b" />


11.	Isi query sql yang telah terhubung ke database kemudian next
 <img width="843" height="608" alt="image" src="https://github.com/user-attachments/assets/2c9db7f8-2c91-4186-9410-cd2a71a556ff" />


12.	Pindahkan seluruh field data dari kiri ke kanan, dan klik next
 <img width="844" height="614" alt="image" src="https://github.com/user-attachments/assets/d669118e-1991-49a4-9ff3-a61059948a6a" />


13.	Langsung next 
 <img width="869" height="630" alt="image" src="https://github.com/user-attachments/assets/5d6315f2-5b92-46a3-aa22-9419bbc4234d" />


14.	Finish
 <img width="897" height="651" alt="image" src="https://github.com/user-attachments/assets/2db957db-4ad0-4cf1-be5c-d77406247c8e" />


15.	Design tampilan laporan semenarik mungkin dan jika ingin melihat hasilnya bisa klik preview 
 <img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/cf42b1a7-8541-48a7-b8af-a6b587f5b3ea" />


16.	Buat button cetak pada design Jframe
 <img width="809" height="567" alt="image" src="https://github.com/user-attachments/assets/955d13c0-e71d-4348-a49e-408cbb35a020" />


17.	Kemudian pada button cetak tambahkan program berikut 
 <img width="839" height="296" alt="image" src="https://github.com/user-attachments/assets/172905be-2a22-436e-a384-5c992d3fe851" />


18.	Tambahkan import net.sf.jasperreports.engine.JRException pada bagian atas program 
 <img width="620" height="38" alt="image" src="https://github.com/user-attachments/assets/cd90069b-63d4-42d2-b845-2cde639cdfcb" />  


kemudian download dan tambahkan library berikut     
 <img width="384" height="291" alt="image" src="https://github.com/user-attachments/assets/0f9d99d0-d946-44c4-88f8-8555bc066855" />

19.	Kemudian jalankan program Jframe dan klik button cetak, akan muncul Tampilan Jasper Reports yang tadi telah dibuat 
  <img width="940" height="681" alt="image" src="https://github.com/user-attachments/assets/c4ac8466-9b30-472c-994a-d6a51c440913" />

