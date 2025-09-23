# Post-Test-3-PBO


#  Sistem Manajemen Penyewaan Kendaraan

## Nama : Muhammad Farros Anand
## NIM : 2409116085

---

##  Fitur
- Tambah Kendaraan (Mobil / Motor)
  
<img width="606" height="288" alt="Cuplikan layar 2025-09-23 200341" src="https://github.com/user-attachments/assets/9f6fbeab-d236-4a13-87ee-574c1726150b" />

<img width="512" height="293" alt="Cuplikan layar 2025-09-23 200348" src="https://github.com/user-attachments/assets/ec72d397-24dc-4b74-a2c5-895fbb9793aa" />


- Lihat Semua Kendaraan

<img width="718" height="284" alt="Cuplikan layar 2025-09-23 200424" src="https://github.com/user-attachments/assets/bdda4188-d644-4135-bfd9-51638783d411" />

  
- Update Kendaraan

  <img width="588" height="346" alt="image" src="https://github.com/user-attachments/assets/71f715c6-6d80-4cd3-9657-c88d37211555" />


- Hapus Kendaraan

  <img width="620" height="296" alt="image" src="https://github.com/user-attachments/assets/cd0bb5bc-3b94-4b0e-a67b-63894b4f4efd" />


- Cari Kendaraan berdasarkan nama/jenis

  <img width="741" height="290" alt="Cuplikan layar 2025-09-23 200411" src="https://github.com/user-attachments/assets/e76d6a7b-d797-4378-82a4-1a3254fe9990" />


- Keluar dari program
  
<img width="723" height="328" alt="image" src="https://github.com/user-attachments/assets/5952ab01-96dd-4670-b5ae-9531bd15b43f" />

---

##  Konsep OOP yang Diterapkan
1. **Encapsulation**  
   - Semua atribut dalam class `Kendaraan`, `Mobil`, dan `Motor` bersifat `private`
   - Menggunakan **getter & setter** untuk mengakses data
  
  <img width="1630" height="862" alt="image" src="https://github.com/user-attachments/assets/806590ef-798e-4798-914c-5eee644cde81" />


2. **Inheritance**  
   - `Kendaraan` sebagai **superclass**  
   - `Mobil` dan `Motor` sebagai **subclass**  

3. **Polymorphism & Overriding**  
   - Method `getInfo()` di `Kendaraan` dioverride di `Mobil` dan `Motor`  
   - Menampilkan informasi yang berbeda sesuai jenis kendaraan
     
     <img width="841" height="99" alt="image" src="https://github.com/user-attachments/assets/791bd4f3-81fd-4e4b-8db4-4f78748bf2d8" />


---

##  Struktur Project


<img width="224" height="224" alt="image" src="https://github.com/user-attachments/assets/b810a95f-6bef-4ff4-b364-f5023baaf205" />

