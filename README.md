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



---

##  Konsep OOP yang Diterapkan

### 1. **Abstraction**
- **`Kendaraan`** → dibuat sebagai `abstract class` yang tidak bisa di-*instance* langsung, hanya bisa diturunkan ke `Mobil` dan `Motor`.

  <img width="732" height="158" alt="image" src="https://github.com/user-attachments/assets/22b71637-e44b-4dc6-9075-5dcef4f4c7da" />


 Abstraction digunakan untuk membuat *blueprint* umum yang harus diimplementasikan oleh subclass / class turunan.

---

### 2. **Polymorphism**

#### a. **Overriding**
- Method `getInfo()` pada class `Mobil` dan `Motor` **menimpa (override)** method abstract `getInfo()` dari `Kendaraan`.

<img width="664" height="128" alt="image" src="https://github.com/user-attachments/assets/08b30b9a-a054-449a-9482-8d217151f919" />


- Dengan ini, setiap objek `Mobil` dan `Motor` bisa menampilkan informasi sesuai jenisnya.

  <img width="1147" height="144" alt="image" src="https://github.com/user-attachments/assets/342712c5-6ac8-4495-8092-6e8e77c38c8e" />

  <img width="1031" height="131" alt="image" src="https://github.com/user-attachments/assets/3ca27062-6625-4c45-baa0-0baef95f0f4e" />



#### b. **Overloading**
- Pada `KendaraanService`, terdapat dua method dengan nama sama tapi parameter berbeda:
  
<img width="823" height="620" alt="image" src="https://github.com/user-attachments/assets/73d07507-17fe-420a-8583-fee2f8eac8a0" />

