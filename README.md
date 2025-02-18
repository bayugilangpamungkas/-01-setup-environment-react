**LAPORAN PRAKTIKUM** <br>

**=========================** <br>
**NIM    : 244107027020**  <br>
**NAMA   : BAYU GILANG PAMUNGKAS**  <br>
**KELAS  : TI - 4K RPL**  <br>
**=========================**  <br>

**Tugas - Pengantar Pemrograman Berbasis Framework dan Reactjs** <br>
**1.	Praktikum 1 : Menyiapkan Lingkungan Pengembangan** <br>

a.	Jelaskan kegunaan masing-masing dari Git, VS Code dan NodeJS yang telah Anda install pada sesi praktikum ini! <br>
Jawaban : <br>

**Git:** Git adalah sistem pengendali versi terdistribusi yang digunakan untuk melacak perubahan dalam kode sumber selama pengembangan perangkat lunak. Kegunaan Git meliputi: <br>
      **•	Version Control:** Memungkinkan Anda untuk menyimpan riwayat perubahan kode, sehingga Anda dapat kembali ke versi sebelumnya jika terjadi kesalahan. <br>
      **•	Collaboration:** Memungkinkan banyak pengembang bekerja pada proyek yang sama secara bersamaan tanpa mengganggu pekerjaan satu sama lain. <br>
      **•	Branching and Merging:** Memungkinkan Anda membuat cabang (branches) yang terpisah untuk mengembangkan fitur baru atau memperbaiki bug, dan kemudian menggabungkannya kembali ke cabang utama setelah selesai. <br>
      
**VSCode (Visual Studio Code):** Visual Studio Code adalah editor kode sumber yang ringan, sangat kuat yang digunakan oleh banyak pengembang untuk menulis, mengedit, dan mengelola kode. Kegunaan VS Code meliputi: <br>
      **•	Code Editing:** Menyediakan fitur penyuntingan kode yang canggih seperti syntax highlighting, auto-completion, dan linting untuk membantu menulis kode dengan lebih efisien dan bebas kesalahan. <br>
      **•	Extensions:** Mendukung berbagai ekstensi yang dapat menambah fungsionalitas VS Code, seperti integrasi dengan sistem kontrol versi, alat debug, dan framework pemrograman. <br>
      **•	Integrated Terminal:** Memiliki terminal bawaan yang memungkinkan pengguna untuk menjalankan perintah dan skrip langsung dari editor tanpa harus beralih ke jendela terminal terpisah. <br>
      
**NodeJS:** NodeJS adalah runtime JavaScript yang dibangun di atas mesin V8 Chrome yang memungkinkan pengguna menjalankan kode JavaScript di luar peramban (browser). Kegunaan NodeJS meliputi: <br>
      **•	Server-Side Programming:** Memungkinkan pengguna menulis kode JavaScript untuk server dan mengembangkan aplikasi web yang dapat menangani permintaan HTTP, WebSocket, dan lainnya. <br>
      **•	Package Management:** Menyediakan ekosistem npm (Node Package Manager) yang memungkinkan pengguna menginstal dan mengelola pustaka dan dependensi yang diperlukan untuk proyek tersebut. <br>
      **•	Asynchronous Programming:** Mendukung pemrograman asinkron yang memungkinkan pengguna menangani banyak permintaan secara efisien tanpa memblokir thread eksekusi. <br>
b.	Buktikan dengan screenshoot yang menunjukkan bahwa masing-masing tools tersebut telah berhasil terinstall di perangkat Anda! <br>
Jawaban : <br>

![image](https://github.com/user-attachments/assets/6822b18c-9ba0-4a63-9988-984dcba1c714) <br>
Pada gambar diatas, terdapat informasi versi Git 2.43.0, versi vscode 1.70.0, versi nodejs v20.9.0 dan versi npm 8.19.4 yang semuanya sudah terinstall pada device saya. <br>

**2.	Praktikum 2 : Membuat Proyek Pertama React Menggunakan Next.js** <br>
a. Pada Langkah ke-2, setelah membuat proyek baru menggunakan Next.js, terdapat beberapa istilah yang muncul. Jelaskan istilah tersebut, TypeScript, ESLint, Tailwind CSS, App Router, Import alias dan Turbopack! <br>
Jawaban : <br>
1.	TypeScript: TypeScript adalah bahasa pemrograman open-source yang dikembangkan oleh Microsoft. Ini adalah superset dari JavaScript yang menambahkan pengetikan statis (static typing) dan fitur-fitur lainnya untuk meningkatkan pengembangan skala besar. TypeScript mengompilasi ke dalam JavaScript biasa, yang dapat dijalankan di peramban web atau server-side dengan Node.js. <br>
2.	ESLint: ESLint adalah alat analisis statis untuk JavaScript (dan TypeScript) yang digunakan untuk mengidentifikasi dan memperbaiki masalah dalam kode. ESLint memungkinkan pengembang untuk menentukan aturan linting yang konsisten dengan gaya kode yang diinginkan, sehingga membantu menjaga kualitas kode dan mencegah bug. ESLint juga dapat diintegrasikan dengan berbagai editor kode dan alat build untuk memberikan umpan balik langsung kepada pengembang. <br>
3.	Tailwind CSS: Tailwind CSS adalah framework CSS utilitas-first yang memungkinkan pengembang untuk membuat antarmuka pengguna (UI) yang responsif dan dapat disesuaikan dengan mudah. <br>
4.	App Router: App Router adalah konsep dalam pengembangan aplikasi web yang mengatur navigasi dan pengelolaan halaman atau tampilan dalam aplikasi. Router memungkinkan pengembang untuk mendefinisikan rute (routes) yang menghubungkan URL dengan komponen atau tampilan tertentu. <br>
5.	Import alias: Import alias adalah teknik dalam pemrograman yang memungkinkan pengembang untuk menetapkan nama alternatif (alias) untuk modul atau paket yang diimpor, berguna untuk menghindari konflik nama dan untuk membuat impor lebih mudah dibaca dan dikelola. Misalnya, mengimpor modul dengan jalur panjang dan kompleks. <br>
6.	Turbopack: Turbopack adalah alat bundling dan build yang dirancang untuk mempercepat proses pembuatan dan pengembangan aplikasi web. Turbopack juga dapat mengoptimalkan pemrosesan aset seperti JavaScript, CSS, dan gambar, sehingga mengurangi waktu build dan meningkatkan kinerja aplikasi. <br>
b.	Apa saja kegunaan folder dan file yang ada pada struktur proyek React yang tampil pada gambar pada tahap percobaan ke-3! <br>
Jawaban : <br>

## Struktur Folder dan File dalam Proyek

| Path/File               | Deskripsi |
|-------------------------|-----------|
| `/hello-world`          | Root folder proyek |
| `/next`                 | Folder yang berisi file-file build Next.js |
| `/node_modules`         | Berisi semua package/dependencies yang telah diinstal |
| `/public`               | Folder untuk menyimpan asset statis yang bisa diakses secara langsung |
| `/src/app`              | Folder utama aplikasi yang menggunakan App Router Next.js |
| `file.svg`              | Asset SVG untuk menampilkan icon file |
| `globe.svg`             | Asset SVG untuk icon globe/dunia |
| `next.svg`              | Logo Next.js |
| `vercel.svg`            | Logo Vercel |
| `window.svg`            | Asset SVG untuk icon window |
| `.gitignore`            | Mengatur file/folder yang tidak perlu di-track Git |
| `eslint.config.mjs`     | Konfigurasi ESLint untuk linting kode |
| `next-env.d.ts`         | Deklarasi tipe TypeScript untuk Next.js |
| `next.config.ts`        | Konfigurasi Next.js |
| `package-lock.json`     | Lock file untuk versi dependencies npm |
| `package.json`          | Manifest proyek & daftar dependencies |
| `postcss.config.mjs`    | Konfigurasi PostCSS (digunakan Tailwind) |
| `tailwind.config.ts`    | Konfigurasi Tailwind CSS |
| `tsconfig.json`         | Konfigurasi TypeScript |
| `favicon.ico`           | Icon website yang muncul di tab browser |
| `globals.css`           | CSS global aplikasi |
| `layout.tsx`           | Layout utama aplikasi Next.js |
| `page.tsx`             | Halaman utama/root aplikasi |

c.	Buktikan dengan screenshoot yang menunjukkan bahwa tahapan percobaan di atas telah berhasil Anda lakukan! <br>
Jawaban : <br>

Proses create project : <br>
![image](https://github.com/user-attachments/assets/d1856388-b7d7-4662-b146-bbf26d98a402) <br>

Proses Running: <br>
![image](https://github.com/user-attachments/assets/aa8afb59-8e37-4389-8dc0-5c3b84f8c808) <br>

Output Dari Hasil Running: <br>
![image](https://github.com/user-attachments/assets/f35495a5-fe7f-4bc3-a882-038a08239a2c) <br>

**3.	Praktikum 3 : Menambahkan Komponen React (Button)** <br>
a.	Buktikan dengan screenshoot yang menunjukkan bahwa tahapan percobaan di atas telah berhasil Anda lakukan! <br>
Jawaban : <br>
![image](https://github.com/user-attachments/assets/e9e94281-2150-411c-a49a-4cda149f35ec) <br>

![image](https://github.com/user-attachments/assets/9d92e8f4-2cf0-4224-85a6-398e794e66f2) <br>

![image](https://github.com/user-attachments/assets/436ec164-2b84-4ee8-af2d-1a9129d8ca8c) <br>

**4.	Praktikum 4 : Menulis Markup dengan JSX** <br>
a.	Untuk apakah kegunaan sintaks user.imageUrl? <br>
Jawaban : <br>
untuk mengakses atau menyimpan URL gambar dari properti atau objek user. <br>
b.	Buktikan dengan screenshoot yang menunjukkan bahwa tahapan percobaan di atas telah berhasil Anda lakukan! <br>
Jawaban : <br>
![image](https://github.com/user-attachments/assets/be454658-7761-4c8d-9654-b48406e00c82) <br>

![image](https://github.com/user-attachments/assets/c67d61bf-e403-4aac-836d-cf49882b42ab) <br>

![image](https://github.com/user-attachments/assets/1c0dde43-24f2-45d9-94f5-65cd1a459abd)









