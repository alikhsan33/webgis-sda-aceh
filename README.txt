WEBGIS SDA ACEH — FILE WEBSITE

Isi:
- index.html
- data/ws.geojson
- data/das.geojson
- data/sungai_besar.geojson
- data/anak_sungai.geojson
- data/kabupaten.geojson

Cara mencoba:
1. Ekstrak ZIP ini ke sebuah folder.
2. Untuk uji lokal, jalankan server web lokal dari folder tersebut (jangan buka index.html langsung karena browser bisa memblokir pembacaan GeoJSON).
3. Untuk akses HP, unggah isi folder ini ke repository GitHub dan aktifkan GitHub Pages dari Settings > Pages.
4. Buka URL Pages di Safari/Chrome. Izinkan akses lokasi untuk tombol GPS.

Catatan:
- Website memakai Leaflet, Turf.js, dan peta dasar online, jadi koneksi internet diperlukan.
- Semua layer sudah dikonversi ke EPSG:4326 (WGS 84).
- Nama hasil berasal dari atribut data sumber; fitur tanpa nama diberi label generik.
- Pencarian sungai terdekat memakai radius 3 km sebagai bantuan orientasi dan bukan penetapan resmi sungai.
- Periksa hasil di lapangan sebelum dipakai untuk keputusan teknis/resmi.
- Data batas dan atribut merupakan data yang diberikan pengguna. Pastikan memiliki izin sebelum memublikasikan ke layanan hosting publik.
