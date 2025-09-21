# Capstone Project: Dari Angka Menjadi Aksi dengan IBM Granite

**Sub-judul:** *Analisis Kesehatan Mental Remaja Menggunakan Pendekatan Metode Campuran*

---

## 📜 Ringkasan Proyek

### Latar Belakang
Di tengah era digital yang serba terhubung, kesehatan mental remaja telah menjadi salah satu isu paling krusial. Tekanan akademik yang semakin berat, dinamika sosial di dunia maya yang kompleks, serta perubahan gaya hidup yang cepat merupakan beberapa faktor yang secara signifikan memengaruhi kesejahteraan psikologis generasi muda. Seringkali, data mengenai isu penting ini hanya tersaji dalam bentuk angka dan statistik yang kaku, sehingga sulit bagi kita—baik sebagai pendidik, orang tua, maupun pembuat kebijakan—untuk memahami cerita dan konteks manusia di baliknya.

### Masalah yang Dipecahkan
Proyek ini berangkat dari sebuah masalah fundamental: **data kuantitatif (angka) tidak mampu menceritakan kisah seutuhnya**. Sebuah angka "tingkat stres 8/10" memang informatif, namun gagal menjawab pertanyaan-pertanyaan yang lebih dalam: *Seperti apa rasanya menjadi remaja dengan tingkat stres tersebut? Apa konflik internal yang dihadapinya? Dan yang terpenting, bagaimana cara saya membantunya secara efektif?* Terdapat kesenjangan besar antara data mentah dan pemahaman kualitatif yang dibutuhkan untuk menciptakan solusi yang benar-benar berdampak.

### Tujuan Proyek
Tujuan utama proyek ini adalah untuk menjembatani kesenjangan tersebut. Saya memanfaatkan model AI generatif canggih, **IBM Granite**, bukan sebagai kalkulator, melainkan sebagai **mitra berpikir analitis**. Proyek ini dirancang untuk mengubah data statistik global yang abstrak mengenai kesehatan mental remaja menjadi tiga output utama yang konkret dan humanis:

1.  **Persona (Studi Kasus):** Menciptakan narasi atau "wajah manusia" yang realistis dari profil data kunci.
2.  **Analisis Akar Masalah:** Menggali hipotesis "mengapa" di balik suatu masalah, dengan landasan teori psikologi yang relevan.
3.  **Rencana Aksi Strategis:** Menghasilkan rekomendasi solusi yang terstruktur dan dapat ditindaklanjuti.

---

## 📊 Dataset yang Digunakan

Analisis ini didasarkan pada dataset publik "Inside Teen Minds: Global Mental Health and Habits" yang tersedia di Kaggle. Dataset ini berisi data anonim dari remaja di berbagai negara mengenai berbagai aspek kehidupan mereka, mulai dari tingkat stres, kebiasaan tidur, hingga penggunaan media sosial.

* **[Tautan Menuju Dataset di Kaggle](https://www.kaggle.com/datasets/dakshbhatnagar08/inside-teen-minds-global-mental-health-and-habits/data)**

---

## 🔬 Metodologi Analisis: Pendekatan Metode Campuran

Untuk mendapatkan pemahaman yang holistik, saya menerapkan **Pendekatan Metode Campuran (Mixed-Methods)**, yang menggabungkan kekuatan analisis kuantitatif dan kualitatif. Bayangkan proses ini seperti pekerjaan seorang detektif:

#### **1. Tahap Kuantitatif: Mencari Petunjuk dalam Data**
Pada tahap awal, saya bertindak seperti detektif yang menganalisis statistik dari lokasi kejadian. Saya melakukan analisis data eksplorasi untuk mengidentifikasi "petunjuk" atau pola-pola signifikan dalam data. Ini saya lakukan dengan:
* **Membuat Visualisasi Data:** Grafik seperti *heatmap* korelasi, *bar chart*, dan *scatter plot* dibuat untuk memetakan hubungan antar variabel secara visual. Dari sini, saya bisa dengan cepat melihat tren seperti hubungan negatif antara durasi menatap layar dan kualitas tidur.
* **Mendefinisikan Arketipe:** Berdasarkan pola tersebut, saya tidak menganalisis data secara acak. Sebaliknya, saya mengelompokkan data ke dalam beberapa "arketipe" atau profil remaja kunci, seperti **"The Supported Striver"** (remaja dengan stres tinggi namun merasa didukung) dan **"The Socially Drained User"** (pengguna media sosial berat dengan interaksi sosial rendah).

#### **2. Tahap Kualitatif Berbantuan AI: Mewawancarai "Saksi Kunci" dengan Landasan Ilmiah**
Setelah menemukan petunjuk, detektif perlu mewawancarai saksi kunci untuk memahami motif dan cerita di baliknya. Di sinilah peran IBM Granite menjadi sangat penting. Saya memilih satu profil paling representatif dari setiap arketipe untuk dianalisis secara mendalam.

Untuk memastikan analisis AI tidak asal-asalan, saya menggunakan teknik canggih yang disebut **"suntik jurnal" (Journal Injection)**. Sebelum menganalisis, saya "memberi contekan" kepada AI berupa ringkasan dari teori-teori psikologi yang relevan dan sudah teruji.
* Untuk arketipe **"Supported Striver"**, saya menyuntikkan **[Teori "Stress-Buffering"](https://pubmed.ncbi.nlm.nih.gov/3901065/)** dari Cohen & Wills (1985).
* Untuk arketipe **"Socially Drained User"**, saya menyuntikkan **[Hipotesis Perpindahan (Displacement Hypothesis)](https://www.tandfonline.com/doi/full/10.1080/10410236.2017.1422101)** dan **[Teori Perbandingan Sosial](https://www2.psych.ubc.ca/~schaller/528Readings/Festinger1954.pdf)** dari Leon Festinger (1954).

Dengan cara ini, AI dipaksa untuk mendasarkan analisisnya pada landasan ilmiah, menghasilkan *insight* yang tidak hanya kreatif tetapi juga kredibel.

---

## 🧠 Temuan Utama dan Analisis

Analisis komparatif antara dua arketipe menghasilkan pemahaman yang kaya akan dinamika kesehatan mental remaja yang berbeda.

### Studi Kasus Arketipe 1: "The Supported Striver"
*(Remaja dengan tingkat stres tinggi, namun juga merasa sangat didukung oleh lingkungannya)*

* **Naratif Persona yang Dihasilkan AI:**
    > *Remaja dengan ID S0002, berumur 17 tahun, residen di Kanada, sedang dalam kelas 11 (sekolah seni atas), memiliki level kecemasan yang tinggi (8 dari skala 1-10) dan waktu tidur yang cukup sekitar 6,1 jam. Mereka memiliki gender non-binary atau 'lainnya'. Mereka tidak menggunakan AI hari ini dan tidak menulis jurnal. Tapi, mereka telah melakukan meditasi dan olahraga hari ini, dengan rating interaksi sosial sebesar 6 dan merasa diperhatikan dengan skala 9. Waktu penggunaan media digital atau layar sekitar 3,8 jam.*

* **Analisis Akar Masalah (berdasarkan Teori "Stress-Buffering"):**
    > *Remaja ini mengalami kecemasan tinggi (8/10) dengan durasi tidur kurang dari rekomendasi (6,1 jam), yang menunjukkan adanya kesulitan dalam mengelola stres sehingga berdampak pada kualitas tidur. Identitas gender non-binary atau “lainnya” juga berpotensi menimbulkan tantangan dalam membangun hubungan sosial karena belum sepenuhnya diakui oleh lingkungan. Meskipun mereka merasakan dukungan sosial yang tinggi (9), kecemasan tetap bertahan, kemungkinan karena sumber stres yang bersifat internal, seperti perfeksionisme, yang menurut teori stress-buffering tidak sepenuhnya dapat diredakan oleh dukungan sosial, terutama ketika stres tersebut dianggap pribadi dan berada di luar jangkauan bantuan orang lain.*

### Studi Kasus Arketipe 2: "The Socially Drained User"
*(Remaja dengan durasi media sosial sangat tinggi dan kualitas interaksi sosial di dunia nyata rendah)*

* **Naratif Persona yang Dihasilkan AI:**
    > *Remaja dengan ID S0914, bernama laki-laki, berusia 14 tahun, tinggal di Jepang, dalam kelas kecil 9, memiliki level kecemasan yang tinggi (7) dan level tidur yang kurang (4.8 jam). Pada hari terkait, level kegembiraan mencapai 4 dan level interaksi sosial juga cukup (4). Namun, waktu pemakaian layar lebih banyak (15.6 jam) dan tidak menggunakan AI atau melakukan pembalikan jurnal. Remaja ini mempunyai praktik meditasi harian (yay!), tetapi tidak melakukan olahraga atau aktivitas fisik lainnya.*

* **Analisis Akar Masalah (berdasarkan Hipotesis Perpindahan & Teori Perbandingan Sosial):**
    > *Remaja ini mengalami kecemasan tinggi dan kurang tidur, menciptakan konflik internal karena kebutuhan tubuh untuk istirahat tidak terpenuhi sehingga stres semakin meningkat. Selain itu, penggunaan layar berlebihan (15,6 jam) mengurangi kesempatan beraktivitas fisik, padahal aktivitas fisik penting untuk mengembalikan energi dan menurunkan stres, serta berpotensi memperburuk pola tidur dan memicu risiko bahaya digital. Keterbatasan interaksi sosial nyata juga membuat remaja lebih rentan membandingkan diri dengan orang lain di media sosial, yang sesuai dengan Teori Perbandingan Sosial dapat menurunkan self-esteem dan meningkatkan rasa terisolasi.*
---

## 🤖 Penjelasan Pemanfaatan IBM Granite

Pemanfaatan IBM Granite dalam proyek ini dilakukan melalui tiga lapisan analisis berantai yang canggih, mengubahnya dari sekadar model bahasa menjadi mitra analitis:

1.  **Generasi Persona (Data → Cerita):**
    Lapisan pertama adalah mengubah baris data yang dingin dan kuantitatif menjadi sebuah studi kasus naratif yang empatik. AI membantu saya memahami "wajah manusia" dan konteks kehidupan di balik angka-angka tersebut.

2.  **Analisis Akar Masalah Berbasis Teori (Cerita + Teori → Hipotesis "Mengapa"):**
    Ini adalah pemanfaatan yang paling krusial. Dengan "menyuntikkan" landasan teori dari jurnal, AI tidak lagi menebak-nebak, melainkan menganalisis narasi persona melalui "kacamata" ilmiah. Hasilnya adalah hipotesis akar masalah yang memiliki justifikasi teoretis yang kuat.

3.  **Generasi Rencana Aksi Strategis (Hipotesis → Solusi "Bagaimana"):**
    Pada lapisan terakhir, hipotesis akar masalah yang sudah divalidasi secara teoretis digunakan sebagai input. AI kemudian ditugaskan untuk merancang solusi yang konkret, terstruktur, dan ditargetkan untuk audiens yang berbeda (Siswa, Guru, dan Orang Tua), memastikan bahwa setiap rekomendasi benar-benar menjawab inti permasalahan.

---

## 🚀 Rekomendasi (Rencana Aksi Strategis)

Berikut adalah Rencana Aksi Strategis bagaimana kita bisa mengatasi kesehatan mental remaja dengan membuat eksosistem dari faktor internal dan eksternal secara spesifik yang dihasilkan oleh IBM Granite setelah melakukan analisis mendalam pada masing-masing dari dua arketipe kunci yang ditemukan dalam data dan juga dibantu oleh knowledge dari 2 jurnal psikologi yang relate.

### Rencana Aksi untuk Arketipe 1: "The Supported Striver"
*Rekomendasi ini dirancang khusus untuk remaja yang mengalami tingkat stres internal yang tinggi, meskipun mereka memiliki sistem pendukung eksternal yang kuat.*

#### Target: Siswa - Faktor Internal
* **Nama Program:** *Program Mengurangi Stres dan Memperkuat Tidur*
    * **Deskripsi:** *Program ini bertujuan untuk mengurangi level stres dan meningkatkan kualitas tidur muda. Program tersebut akan menerapkan teknik relaksasi seperti mindfulness dan yoga, serta memberikan pelatihan tentang pengaturan waktu tidur yang tepat. Program juga akan mengajak murid untuk berdiskusi tentang cara mengelola stres sehari-hari, dengan fokus pada identitas gender dan cara memperkuat hubungan sosial.*
* **Nama Program:** *Program Dukungan Sosial dan Perfeksionisme*
    * **Deskripsi:** *Program ini fokus pada meningkatkan dukungan sosial dan membantu murid dalam mengatasi perfeksionisme internal. Program akan mengadakan forum diskusi dan workshop untuk membahas topik identitas gender dan cara memperkuat hubungan sosial. Selain itu, program juga akan mengajak para sosok mentor atau counselor untuk memberikan dukungan sosial pribadi, serta mengajak murid untuk bersama-sama beraktivitas sosial yang dapat membantu mereka merasakan dirinya terhubung dan dihargai.*

#### Target: Guru - Faktor Eksternal
* **Nama Program:** *Program Mengurangi Stres dan Meningkatkan Kualitas Tidur*
    * **Deskripsi:** *Program ini bertujuan untuk membantu guru mengurangi stres dan meningkatkan kualitas tidur murid. Program tersebut akan menerapkan teknik relaksasi, mindfulness, dan manajemen waktu yang efektif. Selain itu, guru akan diberikan pelatihan tentang cara mengidentifikasi dan membantu murid yang mengalami stres, serta cara mendorong lingkungan sekolah yang lebih menyembuhkan untuk tidur yang cukup.*
* **Nama Program:** *Program Memperkuat Identitas dan Hubungan Sosial*
    * **Deskripsi:** *Program ini fokus pada menciptakan lingkungan sekolah yang akseleran untuk memperkuat identitas gender yang tidak sepenuhnya diakui (misalnya, gender non-binary atau 'lainnya') dan meningkatkan hubungan sosial positif. Program tersebut akan melibatkan diskusi, workshop, dan aktivitas bersama yang mendorong kepedulian, respek, dan aksesibilitas bagi seluruh murid, serta membuat guru lebih sensitif terhadap kebutuhan mereka.*

#### Target: Orang Tua - Faktor Eksternal
* **Nama Program:** *Program Mengurangi Stres dan Memperbaiki Waktu Tidur Remaja*
    * **Deskripsi:** *Program ini bertujuan untuk membantu orang tua memahami dan mengurangi stres yang dihadapi remaja mereka, serta memperbaiki pola tidur. Program tersebut akan menerapkan teknik relaksasi dan pengelolaan stres yang dapat dilakukan bersama-sama dengan remaja. Selain itu, program juga akan menyediakan informasi tentang pentingnya waktu tidur yang cukup dan cara membantu remaja mencapai waktu tidur yang dianjurkan.*
* **Nama Program:** *Program Memperkuat Identitas dan Hubungan Sosial Remaja*
    * **Deskripsi:** *Program ini dirancang untuk membantu remaja yang mengidentifikasi diri sebagai gender non-binary atau 'lainnya' dalam memperkuat identitas mereka dan memperbaiki hubungan sosial. Program ini akan menyediakan ruang diskusi, workshop, dan konseling bersama ahli masyarakat yang sudah paham dan mendukung variasi identitas gender. Orang tua dapat diberikan pelatihan untuk memahami dan mendukung proses identitas dan hubungan sosial remaja mereka.*

### Rencana Aksi untuk Arketipe 2: "The Socially Drained User"
*Rekomendasi ini berfokus pada tantangan yang dihadapi oleh remaja dengan durasi penggunaan media sosial yang sangat tinggi, yang berdampak pada kualitas tidur dan interaksi sosial di dunia nyata.*

#### Target: Siswa - Faktor Internal
* **Nama Program:** *Program Tidur Sehat dan Aktivitas Fisik*
    * **Deskripsi:** *Program ini bertujuan untuk meningkatkan kualitas tidur dan menambahkan waktu aktivitas fisik untuk siswa. Program tersebut akan menerapkan waktu batas untuk penggunaan layar sebelum tidur dan mendorong siswa untuk melakukan aktivitas fisik seperti olahraga atau seni selama 1 jam sehari. Program juga akan menyediakan informasi dan latihan tentang cara mengurangi stres dan meningkatkan kualitas tidur.*
* **Nama Program:** *Program Interaksi Sosial Real dan Mengurangi Perbandingan di Media Sosial*
    * **Deskripsi:** *Program ini bertujuan untuk meningkatkan interaksi sosial nyata dan mengurangi perbandingan terhadap kehidupan orang lain di media sosial. Program tersebut akan mengadakan acara sosial seperti kemahayanan, pertandingan olahraga, atau diskusi grup secara berkala. Selain itu, program juga akan menyediakan latihan dan informasi tentang efek negatif perbandingan di media sosial dan cara meningkatkan kesejahteraan pribadi tanpa harus mengandalkan perbandingan dengan orang lain.*

#### Target: Guru - Faktor Eksternal
* **Nama Program:** *Program Tidur dan Kesehatan Mental Guru*
    * **Deskripsi:** *Program ini bertujuan untuk meningkatkan kesedaran guru tentang pentingnya waktu tidur cukup dan kesehatan mental. Program ini akan menerapkan waktu tidur yang cukup sebagai bagian dari jadwal seharian guru, dan menyediakan latihan mindfulness dan relaxasi untuk mengurangi stres. Selain itu, program juga akan mengajarkan cara mengatasi pola tidur yang tidak baik yang disebabkan penggunaan layar yang berlebihan.*
* **Nama Program:** *Program Interaksi Sosial Real dan Digital Guru*
    * **Deskripsi:** *Program ini bertujuan untuk meningkatkan interaksi sosial nyata guru dan mengurangi terlalu banyak perbandingan dengan kehidupan orang lain di media sosial. Program ini akan menerapkan waktu aktivitas interaksi sosial nyata sebagian dari waktu belajar, seperti diskusi kelompok atau kegiatan bersama murid. Selain itu, program juga akan mengajarkan cara menggunakan media sosial secara positif dan mengurangi efek negatifnya, seperti perbandingan terburu-buru dan rasa terisolasi.*

#### Target: Orang Tua - Faktor Eksternal
* **Nama Program:** *Program Tidur Sehat untuk Anak*
    * **Deskripsi:** *Program ini bertujuan untuk meningkatkan kesedaran orang tua tentang pentingnya waktu tidur cukup bagi anak. Program ini akan menyajikan informasi tentang bagaimana kekurangan tidur dapat menyebabkan stres dan masalah kesehatan lainnya. Selain itu, program akan menyediakan tips praktis untuk menciptakan ritual tidur yang baik, seperti membuat rutinitas tidur yang sama, menghindari aktivitas yang menimbulkan kegembiraan sebelum tidur, dan memastikan ruangan tidur yang sehat dan nyaman.*
* **Nama Program:** *Program Aktivitas Fisik dan Teknologi Terintegrasi (AFTi)*
    * **Deskripsi:** *Program ini bertujuan untuk mengeksplorasi cara mengintegrasikan aktivitas fisik dengan penggunaan teknologi agar anak tidak terlalu banyak berinteraksi dengan layar. Program ini akan menyajikan ide-ide aktivitas fisik yang menarik dan menggunakan teknologi seperti aplikasi fitnes, video tutorial olahraga interaktif, dan permainan fisik yang melibatkan teknologi. Selain itu, program juga akan menyediakan tips untuk mengurangi waktu di depan layar dan mendorong interaksi sosial nyata secara langsung.*
