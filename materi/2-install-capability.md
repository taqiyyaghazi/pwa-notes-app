# Kriteria Install Capability

1. Diakses via https atau localhost
2. Memiliki Web App Manifest dengan nilai-nilai yang dibutuhkan

-   Berkas yg berisi informasi aplikasi
-   Jika tidak ada berkas ini, maka website tidak dianggap sebagai aplikasi
-   Contoh : <link rel="manifest" src="manifest.json"/>
-   Sumber berkas manifest (.json/.webmanifest)

3. Terdapat Icon sebagai identitas aplikasi

-   Buat icon menjadi maskable
-   Maskable Prewiewer Tool (https://maskable.app/)
-   Khusus icons di safari <link rel="apple-touch-icon" src="icon.png"/>
-   https://manifest-generator.netlify.app/

4. Bekerja secara offline dengan Service Worker (mobile device criteria)
