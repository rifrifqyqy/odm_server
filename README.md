# Minecraft Server ODM

Selamat datang di repositori server Minecraft! Proyek ini berisi konfigurasi dan panduan untuk menjalankan server Minecraft menggunakan Java.

## Cara Menjalankan Server

Untuk menjalankan server Minecraft, gunakan perintah berikut di terminal:

```bash
java -Xmx3700M -Xms3624M -jar server.jar nogui

-Xmx3700M: Opsi ini menentukan jumlah maksimum memori heap yang dapat digunakan oleh Java Virtual Machine (JVM). Dalam hal ini, server Minecraft diizinkan menggunakan hingga 3700 MB (atau 3,7 GB) memori. Pengaturan ini berguna untuk memastikan server memiliki cukup memori untuk beroperasi dengan baik, terutama saat ada banyak pemain atau jika ada banyak mod yang diinstal.

-Xms3624M: Opsi ini menentukan jumlah memori heap awal yang dialokasikan untuk JVM saat server dimulai. Dalam hal ini, server dimulai dengan 3624 MB (atau 3,6 GB) memori. Menentukan ukuran awal ini membantu mengurangi kebutuhan untuk mengalokasikan memori secara dinamis saat server berjalan, yang dapat meningkatkan kinerja.
```

### Catatan

- Kamu dapat menyesuaikan bagian-bagian tertentu sesuai dengan kebutuhan spesifik server Minecraft kamu, seperti cara mengonfigurasi file `server.properties` atau informasi tentang mod yang digunakan, jika ada.
- Pastikan untuk mengganti `server.jar` dengan nama file JAR yang sebenarnya jika berbeda.

Jika ada yang ingin ditambahkan atau diubah, silakan beri tahu!
