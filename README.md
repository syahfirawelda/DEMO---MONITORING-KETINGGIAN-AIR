#  Smart Water Level Monitoring System

Sistem pemantauan ketinggian air berbasis web secara *real-time* yang menampilkan data hasil pengukuran dari perangkat sensor/IoT (*microcontroller*). 

🔗 **Link Demo Web:** [http://weldasyahfira.42web.io/monitoring_air/]

---

##  Deskripsi Projek
Projek ini merupakan dashboard monitoring web yang dirancang untuk menampilkan data ketinggian air secara langsung (*read-only*) dari database. Data di dalam database diinput secara otomatis oleh perangkat sensor (seperti Arduino / ESP32) yang terpasang di lokasi pemantauan.

Projek ini dikembangkan dengan arsitektur terpisah antara **Front-End** (untuk antarmuka pengguna) dan **Back-End** (untuk pengelolaan data dan antarmuka alat).

---

##  Fitur Utama
- **Dashboard Real-Time:** Menampilkan data ketinggian air terbaru secara rinci dan mudah dibaca oleh publik.
- **Informasi Lokasi:** Menampilkan titik stasiun pemantauan air.
- **Otomatisasi Data:** Menerima *input* data otomatis dari perangkat IoT/sensor tanpa perlu *input* manual.
- **Multi-User Access:** 
  - **Publik:** Dapat melihat (*read-only*) kondisi dan status ketinggian air.
  - **Admin/Sistem:** Mengendalikan informasi lokasi dan konfigurasi sistem di sisi Back-End.

---

##  Arsitektur & Teknologi

### 1. Front-End (Web Viewer)
* **Teknologi:** HTML5, CSS3, JavaScript (Fetch API)
* **Fungsi:** Mengambil data dari server Back-End dan menginterpretasikannya ke dalam tampilan visual/dashboard untuk pengguna umum.
* **Hosting:** GitHub Pages

### 2. Back-End & Database (Server & API)
* **Teknologi:** PHP / Node.js & Database MySQL (atau sejenisnya)
* **Fungsi:** Menerima kiriman data dari alat sensor, menyimpannya ke database, dan menyediakan endpoint API untuk dibaca oleh Front-End.


![Tampilan Dashboard](MONITORING AIR/1.png)
---

##  Pengembang
Dikembangkan sebagai sistem pemantauan ketinggian air otomatis untuk kebutuhan monitoring dan peringatan dini.
