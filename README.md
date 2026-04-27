<div align="center">

# Analisis Etika dan Dampak Sosial *Algorithmic Management* pada Mitra *Driver* Platform *Ride Hailing* di Indonesia

*"Untuk memenuhi tugas pada mata kuliah Etika Profesi (A)"*

<br>

<img src="logo up.png" alt="Logo Universitas Pancasila" width="250">

<br>
<br>

**Disusun Oleh Kelompok 10:**
| Nama Anggota | NIM |
| :--- | :--- |
| Naila Putri Fahel | 4524210053 |
| Muhamad Edvin Hidayat | 4524210054 |
| Muhammad Agis Irawan | 4524210056 |
| Vina Aisya Hafiz | 4524210131 |
| Muhamad Bachtiar | 4524210141 |

<br>

**Dosen Pengampu:**
Adi Wahyu Pribadi, S.Si., M.Kom

<br>
<br>

# PROGRAM STUDI TEKNIK INFORMATIKA
# FAKULTAS TEKNIK UNIVERSITAS PANCASILA
# 2026

---
</div>

## BAB I PENDAHULUAN

### 1.1 Latar Belakang

Transformasi digital di Indonesia telah melahirkan fenomena *gig economy* yang masif, dengan platform *ride-hailing* seperti Gojek dan Grab sebagai aktor utamanya. Di balik kemudahan mobilitas yang ditawarkan, terdapat mekanisme *Algorithmic Management*, sebuah sistem kontrol digital di mana kode program mengambil alih peran manajer tradisional untuk mengatur, mengawasi, dan memberi sanksi kepada jutaan mitra pengemudi secara otomatis dan *real-time* (Bahasoan dkk., 2024).

Bagi pengembang perangkat lunak (*software engineer*), desain algoritma ini bukan sekadar urusan teknis untuk mencapai efisiensi (Profit), melainkan sebuah manifestasi dari Etika Profesi. Sebagai sebuah profesi yang memiliki standar global seperti IEEE (*Institute of Electrical and Electronics Engineers*), perancangan sistem harus menjunjung prinsip *Safety, Health, and Welfare of the Public* (Keselamatan, Kesehatan, dan Kesejahteraan Publik). Namun nyatanya, sistem kotak hitam (*black box*) yang diterapkan seringkali mengabaikan aspek kemanusiaan (People). Praktik suspend otomatis tanpa ruang banding manusiawi (*human-in-the-loop*) dan tekanan rating yang konstan telah menciptakan asimetri kekuasaan yang tajam, di mana kesejahteraan mitra dikorbankan demi optimalisasi sistem (Khairullah dkk., 2025; Pradana, 2024).

Selain itu, kegagalan dalam merancang algoritma yang efisien tidak hanya berdampak pada relasi sosial-ekonomi, tetapi juga pada aspek lingkungan (Planet). Algoritma yang memaksa pengemudi untuk terus berkendara tanpa arah demi memancing orderan (*cruising for fares*) berkontribusi pada pemborosan bahan bakar dan peningkatan emisi karbon di wilayah perkotaan.

Oleh karena itu, laporan ini akan membedah relasi kuasa antara kode program dan kesejahteraan mitra melalui lensa *Triple Bottom Line* (People, Profit, Planet). Analisis ini bertujuan untuk mengevaluasi apakah inovasi teknologi dalam platform *ride-hailing* sudah selaras dengan integritas moral profesi TI berdasarkan Kode Etik IEEE serta hukum positif di Indonesia seperti UU ITE dan UU PDP. Sebagai calon profesional IT, analisis ini krusial untuk menegaskan bahwa algoritma bukanlah entitas netral, melainkan produk dari keputusan manusia yang harus dapat dipertanggungjawabkan (*accountable*).

### 1.2 Masalah Utama

Berdasarkan latar belakang yang telah diuraikan, penerapan *algorithmic management* pada platform *ride-hailing* (Gojek/Grab) di Indonesia telah memunculkan empat masalah utama yang menjadi fokus analisis dalam laporan ini, yaitu: suspend otomatis mitra *driver*, *dynamic pricing*, tekanan *rating*, dan minimnya ruang banding. Keempat masalah ini mencerminkan ketidakseimbangan dalam kerangka *Triple Bottom Line* (People, Profit, Planet) serta menyentuh isu kesejahteraan *gig worker*, transparansi algoritma, dan relasi kekuasaan antara platform dengan mitra.

#### A. Suspend Otomatis dan Minimnya Ruang Banding (Lensa *People*)

- Orderan fiktif menyebabkan performa *driver* turun hingga berakibat putus mitra (suspend) tanpa pesangon [6].
- *Driver* tidak memiliki ruang banding yang manusiawi (*human-in-the-loop*) karena keputusan suspend dilakukan sepihak oleh algoritma tanpa proses klarifikasi yang adil [6].
- Secara yuridis, sistem pengambilan keputusan otomatis tanpa penjelasan memadai melanggar hak transparansi informasi bagi mitra [12].

#### B. *Dynamic Pricing* yang Tidak Transparan (Lensa *Profit*)

- Kurangnya transparansi algoritma yang mengatur pendapatan *driver*, sementara biaya operasional (bahan bakar, perawatan kendaraan, kuota) ditanggung *driver* sendiri [9].
- Mekanisme *dynamic pricing* yang tertutup menciptakan ketimpangan informasi yang hanya menguntungkan platform [12].

#### C. Tekanan *Rating* (Lensa *Profit* & *People*)

- Sistem *rating* memainkan peran penting dalam menentukan pendapatan *driver*; *rating* tinggi meningkatkan jumlah order, sementara *rating* rendah mengurangi pendapatan [15].
- Hal ini menciptakan tekanan psikologis yang konstan, di mana *driver* terjebak dalam target algoritma yang ketat demi menghindari penalti [11].

#### D. Dampak Turunan terhadap Lingkungan dan Celah Status Kemitraan (Lensa *Planet* & *Profit*)

- Algoritma yang tidak menjamin kepastian orderan memaksa *driver* terus berkendara tanpa arah (*cruising for fares*), menyebabkan pemborosan BBM dan peningkatan emisi karbon [6][7].
- Fitur donasi penghijauan hanya bersifat *greenwashing* dan tidak menyentuh akar masalah [8].
- Status "mitra" dijadikan celah untuk menghindari kewajiban upah minimum dan jaminan sosial [7][13].

### 1.3 Rumusan Masalah

1. Bagaimana transparansi dan akuntabilitas dalam *Algorithmic Management* mempengaruhi kesejahteraan sosial dan ekonomi (*People* & *Profit*) mitra pengemudi?
2. Apakah praktik kontrol algoritma sepihak dan suspend otomatis telah memenuhi standar Etika Profesi TI (prinsip keselamatan, kesehatan, dan kesejahteraan publik menurut IEEE) serta regulasi hukum seperti UU PDP dan UU ITE?
3. Bagaimana peran profesional TI sebagai *moral agent* dalam menyeimbangkan efisiensi sistem dengan perlindungan hak-hak mitra kerja?

### 1.4 Tujuan Penulisan

<h2 align="center">BAB II<br>LANDASAN TEORI</h2>

## 2.2 Teori Etika yang Relevan
### 2.1.1 Etika sebagai Kerangka Teoritis
Etika merupakan cabang filsafat yang mengkaji prinsip-prinsip umum mengenai baik dan buruk, benar dan salah, serta tanggung jawab manusia dalam bertindak. Sifat etika adalah teoritis, sistematis, dan cenderung universal. Etika tidak hanya menanyakan apa yang harus dilakukan, tetapi juga mengapa tindakan tersebut dianggap benar serta berdasarkan prinsip apa keputusan itu diambil. Dalam konteks teknologi, etika menjadi dasar untuk menilai apakah suatu sistem algoritmik, seperti yang digunakan oleh *platform* ojek *online*, dapat dibenarkan secara prinsipil, bukan hanya secara teknis. 

### 2.1.2 Moral sebagai Penerapan Praktis
Berbeda dengan etika yang bersifat teoritis, moral merujuk pada nilai, keyakinan, dan norma yang dianut oleh individu atau kelompok sebagai pedoman perilaku dalam kehidupan sehari-hari. Moral bersifat lebih personal, praktis, dan kontekstual, karena dipengaruhi oleh budaya, agama, serta pengalaman hidup. Dalam kasus ojek *online*, moral muncul ketika seseorang menilai bahwa pemutusan akun atau *suspend* terhadap pengemudi secara otomatis, terutama jika tanpa ruang klarifikasi yang memadai, terasa tidak adil. Dengan demikian, moral menjadi respons intuitif atas ketidakwajaran yang dirasakan dalam praktik nyata. 

### 2.1.3 Etiket sebagai Norma Sopan Santun Sosial
Etiket berkaitan dengan tata cara perilaku yang berlaku dalam interaksi sosial dan bersifat sopan santun. Etiket lebih menekankan aspek kesusilaan dalam berhubungan dengan orang lain, bukan pada persoalan benar atau salah secara moral. Dalam konteks *platform* digital, etiket dapat terlihat misalnya pada tata cara komunikasi yang sopan antara pengemudi dan penumpang melalui aplikasi. Namun, etiket tidak cukup untuk menjawab persoalan yang lebih mendalam, seperti keadilan dalam sistem penilaian, transparansi algoritma, atau ketimpangan relasi antara *platform* dan mitra pengemudi.

| Dimensi | Etika | Moral | Etiket | Etika Profesi |
| :--- | :--- | :--- | :--- | :--- |
| **Sumber Otoritas** | Filsafat / teori | Budaya, agama, individu | Norma sosial | Kode profesi (*ACM*, *IEEE*) |
| **Sifat** | Sistematis, universal | Personal, praktis | Konvensional, situasional | Formal, mengikat anggota |
| **Fokus** | Prinsip universal | Keyakinan pribadi/kelompok | Kesopanan | Tanggung jawab pekerjaan |
| **Contoh Pelanggaran**| Mencuri melanggar prinsip keadilan | Menolak membantu orang karena egois | Tidak memberi salam saat bertamu | *Engineer* menyembunyikan cacat sistem fatal |
<div align="center">
  <small><b><i>Tabel 2.1</i></b> Perbandingan Etika, Moral, dan Etiket</small>
</div>

Pemahaman terhadap ketiga konsep tersebut penting karena membantu membedakan mana persoalan yang hanya menyangkut sopan santun interaksi, mana yang merupakan penilaian moral, dan mana yang termasuk persoalan etis fundamental yang memerlukan solusi sistemik. Dalam kasus *algorithmic management* pada ojek *online*, persoalan utama bukan terletak pada etiket, melainkan pada etika dan moral yang berkaitan dengan keadilan, tanggung jawab, serta perlindungan terhadap hak dan kesejahteraan mitra pengemudi.

---

## 2.2 Teori Etika yang Relevan

### 2.2.1 Utilitarianisme
*Utilitarianism* merupakan teori etika yang dikembangkan oleh Jeremy Bentham dan John Stuart Mill yang menilai moralitas suatu tindakan berdasarkan konsekuensinya. Prinsip utamanya adalah bahwa tindakan yang benar adalah tindakan yang menghasilkan kebaikan terbesar bagi jumlah orang terbesar (*the greatest good for the greatest number*). Dalam konteks *platform* ojek *online*, pendekatan ini sering digunakan untuk membenarkan praktik *algorithmic management*, di mana *platform* seperti Gojek dan Grab dianggap memberikan manfaat luas, seperti layanan transportasi yang murah dan efisien bagi konsumen, peningkatan mobilitas perkotaan, serta akses pendapatan bagi jutaan pengemudi.

Namun demikian, pendekatan *utilitarianism* memiliki kelemahan mendasar, yaitu kecenderungannya mengabaikan ketimpangan distribusi manfaat dan beban. Dalam praktiknya, keuntungan yang dinikmati oleh mayoritas sering kali diperoleh dengan mentransfer risiko kepada pengemudi, seperti ketidakpastian pendapatan, tekanan *rating*, dan ketiadaan jaminan sosial yang memadai [4]. Oleh karena itu, jika analisis hanya berfokus pada agregasi kepuasan tanpa mempertimbangkan penderitaan kelompok yang paling terdampak, maka klaim “kebaikan terbesar” menjadi tidak valid secara etis. Evaluasi yang lebih jujur harus memasukkan realitas ketidakadilan yang dialami pengemudi sebagai bagian dari perhitungan moral [5].

### 2.2.2 Deontologi 
Berbeda dengan *utilitarianism*, *deontology* yang dipelopori oleh Immanuel Kant menilai moralitas suatu tindakan berdasarkan kesesuaian dengan kewajiban moral universal, bukan pada konsekuensinya. Prinsip utama dalam pendekatan ini adalah *categorical imperative*, yaitu bahwa seseorang harus bertindak hanya berdasarkan prinsip yang dapat dijadikan hukum universal. Dalam konteks ini, setiap tindakan harus menghormati martabat manusia sebagai tujuan, bukan sekadar alat untuk mencapai keuntungan.

Dari perspektif *deontology*, praktik *suspend* otomatis tanpa transparansi dan tanpa mekanisme banding yang adil merupakan pelanggaran terhadap kewajiban moral dasar. Jika prinsip tersebut diterapkan secara universal bahwa pihak berwenang boleh mencabut mata pencaharian seseorang tanpa proses yang adil maka hal ini akan merusak keadilan dalam sistem kerja secara keseluruhan. Selain itu, *dynamic pricing* yang tidak transparan juga melanggar prinsip kejujuran dan penghormatan terhadap otonomi individu, karena pengemudi tidak diberikan informasi yang cukup untuk mengambil keputusan rasional terkait pekerjaannya [3].

### 2.2.3 *Ethics of Care*
*Ethics of care* merupakan pendekatan etika yang dikembangkan oleh Carol Gilligan dan Nel Noddings yang menekankan pentingnya relasi interpersonal, empati, serta tanggung jawab kontekstual terhadap individu lain. Berbeda dengan pendekatan seperti *utilitarianism* yang berorientasi pada konsekuensi atau *deontology* yang berfokus pada prinsip universal, *ethics of care* menempatkan hubungan manusia dan perhatian terhadap pihak yang rentan sebagai pusat pertimbangan moral. Pendekatan ini memandang bahwa tindakan etis tidak hanya ditentukan oleh aturan atau hasil, tetapi juga oleh sejauh mana seseorang mampu merespons kebutuhan nyata orang lain dalam suatu relasi.

Dalam konteks *gig economy*, khususnya pada relasi antara *platform* dan pengemudi ojek *online*, *ethics of care* menjadi sangat relevan. *Platform* memiliki posisi dominan karena menguasai teknologi, data, dan mekanisme pengambilan keputusan berbasis algoritma. Sebaliknya, pengemudi berada dalam posisi yang lebih lemah karena bergantung pada sistem yang tidak transparan, sulit dipahami, serta tidak dapat dinegosiasikan secara langsung [2]. Ketimpangan ini menunjukkan bahwa hubungan yang diklaim sebagai “kemitraan” pada praktiknya mengandung relasi ketergantungan yang tinggi, sehingga menuntut adanya tanggung jawab moral yang lebih besar dari pihak *platform*. Dalam kerangka ini, perhatian terhadap kesejahteraan pengemudi tidak cukup diwujudkan melalui kontrak formal, tetapi harus tercermin dalam desain sistem yang adil dan manusiawi [1].

Implikasi dari pendekatan ini bagi profesional *IT* sangat signifikan. Seorang *engineer* tidak dapat hanya berfokus pada efisiensi sistem atau optimalisasi algoritma, tetapi juga harus mempertimbangkan dampak sosial dari teknologi yang dirancang. Dalam merancang sistem yang mengelola ratusan ribu pekerja, pertanyaan etis yang relevan bukan hanya apakah sistem tersebut efektif, tetapi juga apakah sistem tersebut sensitif terhadap kebutuhan, keterbatasan, dan kerentanan pengguna yang bergantung padanya. Dengan demikian, *ethics of care* mendorong pergeseran perspektif dari sekadar efisiensi teknis menuju tanggung jawab sosial yang lebih luas dalam pengembangan teknologi.

---

## 2.3 Kode Etik Profesi *IT*

### 2.3.1 Prinsip *ACM*: *Avoid Harm*
*Association for Computing Machinery* (*ACM*) menetapkan prinsip *avoid harm* sebagai salah satu landasan utama dalam kode etik profesi IT. Prinsip ini menegaskan bahwa profesional IT memiliki kewajiban untuk secara aktif mengidentifikasi, mencegah, dan memitigasi potensi dampak negatif dari sistem yang mereka kembangkan, baik yang bersifat teknis maupun sosial dan ekonomi. Selain itu, *ACM* juga menekankan pentingnya evaluasi risiko yang komprehensif sebelum suatu sistem diterapkan, serta kewajiban untuk menempatkan kepentingan publik di atas kepentingan bisnis atau pemberi kerja.

Dalam konteks sistem *algorithmic management* pada ojek *online*, prinsip ini memiliki implikasi yang nyata dan tidak dapat diabaikan. Penerapan *suspend* otomatis tanpa mekanisme banding yang transparan, serta penggunaan *dynamic pricing* yang tidak mempertimbangkan stabilitas pendapatan pengemudi, menunjukkan adanya potensi dampak merugikan yang signifikan. Kondisi ini menimbulkan pertanyaan kritis mengenai apakah *engineer* yang merancang sistem tersebut telah menjalankan prinsip *avoid harm* secara utuh, atau justru mengabaikan dimensi sosial demi efisiensi dan keuntungan *platform*.

### 2.3.2 Prinsip *IEEE*: Keselamatan, Kesehatan, dan Kesejahteraan Publik
*Institute of Electrical and Electronics Engineers* (*IEEE*) melalui kode etiknya menegaskan bahwa setiap profesional memiliki tanggung jawab untuk mengutamakan keselamatan, kesehatan, dan kesejahteraan publik dalam setiap keputusan yang diambil. Prinsip ini tidak hanya mencakup perlindungan terhadap bahaya fisik, tetapi juga mencakup kewajiban untuk mengungkapkan (*disclosure*) secara jujur setiap potensi risiko yang dapat merugikan masyarakat, serta menghindari konflik kepentingan dalam praktik profesional.

Menariknya, penekanan pada aspek “kesejahteraan” dalam kode etik *IEEE* memperluas cakupan tanggung jawab profesional *IT* ke ranah sosial-ekonomi. Dalam konteks ojek *online*, sistem yang secara struktural menurunkan kesejahteraan pengemudi misalnya melalui ketidakpastian pendapatan, mekanisme *suspend* yang tidak transparan, atau algoritma penentuan tarif yang sulit dipahami dapat dipandang sebagai bentuk pelanggaran etika, meskipun tidak menimbulkan kerugian fisik secara langsung. Minimnya transparansi dalam sistem algoritmik tersebut juga bertentangan dengan prinsip keterbukaan dan akuntabilitas yang menjadi bagian penting dari kode etik *IEEE* [3].

---

## 2.4 Kerangka 3P (*Triple Bottom Line*)

<div align="center">
  <img src="Gambar 2.4 Kerangka 3P Triple Bottom Line.png" alt="Kerangka 3P"><br>
  <small><b><i>Gambar 2.4</i></b> Kerangka 3P (<i>Triple Bottom Line</i>)</small>
</div>

Sesuai dengan konsep *Triple Bottom Line* (3P) yang dirumuskan oleh John Elkington, keberlanjutan sebuah entitas bisnis tidak lagi hanya diukur melalui indikator keuangan semata (*profit*), melainkan harus mengintegrasikan dampak sosial terhadap manusia (*people*) dan dampak terhadap lingkungan hidup (*planet*). Penerapan kerangka kerja ini sangat relevan sebagai sudut pandang holistik untuk mengevaluasi keberlanjutan model bisnis yang diterapkan oleh *platform* ojek *online* saat ini.

Ditinjau dari dimensi *profit*, *platform* besar seperti Gojek dan Grab secara tak terbantahkan telah mencapai skala operasional dan nilai valuasi yang sangat mengesankan. Akan tetapi, pencapaian tersebut berbanding terbalik dengan kondisi pada dimensi *people* yang menunjukkan indikasi permasalahan serius. Berbagai studi akademis mengidentifikasi adanya ketidakseimbangan struktural yang signifikan dalam ekosistem ini. Di satu sisi, mitra pengemudi harus menanggung seluruh risiko operasional mencakup biaya perawatan kendaraan, risiko kecelakaan lalu lintas, hingga fluktuasi pendapatan harian sedangkan di sisi lain, perusahaan *platform* menikmati pertumbuhan kapital yang pesat tanpa menanggung beban risiko yang setara [1][14]. Kerentanan posisi mitra pengemudi ini semakin diperparah oleh minimnya jaminan sosial ketenagakerjaan yang diterima oleh para pekerja *gig* (*gig workers*) di Indonesia [4].

Kondisi tersebut merepresentasikan inti dari diskrepansi dalam kerangka *triple bottom line* pada model bisnis ojek *online*: perusahaan *platform* cenderung mengoptimalkan pilar *profit* melalui strategi mengeksternalisasi biaya dan risiko operasional kepada pilar *people* (mitra pengemudi). Apabila ditinjau dari perspektif etika profesi TI, para insinyur (*engineers*) yang merancang sistem dan algoritma ini baik secara sadar maupun tidak turut berkontribusi dalam melanggengkan ketidakseimbangan tersebut. Hal ini menegaskan prinsip bahwa sebuah sistem yang dirancang tanpa mempertimbangkan keseimbangan aspek 3P tidak dapat dikategorikan sebagai sistem yang etis, meskipun secara teknis sistem tersebut mampu berfungsi dengan sempurna [5].

## BAB III ANALISIS KASUS (ALGORITHMIC MANAGEMENT)
### 3.1 Lensa People
### 3.2 Lensa Profit
### 3.3 Lensa Planet

## BAB IV PEMBAHASAN DAN SOLUSI
### 4.1 Dampak Etis 
### 4.2 Dampak Hukum
### 4.3 Rekomendasi

## BAB V PENUTUP
### 5.1 Kesimpulan
### 5.2 Saran


<h2 align="center">DAFTAR PUSTAKA</h2>
<table>
  <tr>
    <td valign="top">[1]</td>
    <td>M. Khairullah, R. O. Novasari, T. Kartika, and N. Y. Aryanti, “Digital Exploitation in the Gig Economy: A Marxian Study on Platform and Online Ojek Driver Relations,” <i>Electronic Journal of Education, Social Economics and Technology</i>, vol. 6, no. 1, 2025, doi: <a href="https://doi.org/10.33122/ejeset.v6i1.706">https://doi.org/10.33122/ejeset.v6i1.706</a>.</td>
  </tr>
  <tr>
    <td valign="top">[2]</td>
    <td>S. Asrori, M. Isma’il, and E. F. Gamalinda, “The flexibility illusion: Algorithmic control and precarity in Indonesia’s gig economy,” <i>Simulacra</i>, vol. 8, no. 2, pp. 187–205, Nov. 2025, doi: <a href="https://doi.org/10.21107/sml.v8i2.30214">https://doi.org/10.21107/sml.v8i2.30214</a>.</td>
  </tr>
  <tr>
    <td valign="top">[3]</td>
    <td>A. N. Marpaung, T. Farina, and N. Ali, “AI-Based Dynamic Pricing in Online Transportation Services: A Legal Review of Algorithmic Fairness and Transparency,” <i>Eduvest – Journal of Universal Studies</i>, vol. 6, no. 3, pp. 3621–3628, Mar. 2026.</td>
  </tr>
  <tr>
    <td valign="top">[4]</td>
    <td>M. Stevania and S. H. Hoesin, “Analisis kepastian hukum jaminan sosial ketenagakerjaan bagi gig worker pada era gig economy di Indonesia,” <i>Jurnal Ilmiah Penegakan Hukum</i>, vol. 11, no. 2, pp. 268–277, 2024, doi: <a href="https://doi.org/10.31289/jiph.v11i2.11968">https://doi.org/10.31289/jiph.v11i2.11968</a>.</td>
  </tr>
  <tr>
    <td valign="top">[5]</td>
    <td>J. Healy, D. Nicholson, and A. Pekarek, “Should We Take the Gig Economy Seriously?,” <i>Labour & Industry</i>, vol. 27, no. 3, pp. 232–248, 2017, doi: <a href="https://doi.org/10.1080/10301763.2017.1377048">https://doi.org/10.1080/10301763.2017.1377048</a>.</td>
  </tr>
  <tr>
    <td valign="top">[6]</td>
    <td>M. Adriaman, “Upaya Hukum Terhadap Suspend Dalam Perjanjian Kemitraan Antara PT. Gojek Indonesia dengan Driver,” <i>Jurnal Hukum Respublica Universitas Lancang Kuning</i>, vol. 20, No. 2, pp. 1–8, May 2021, doi: <a href="https://doi.org/10.31849/respublica.v20i2.7227">https://doi.org/10.31849/respublica.v20i2.7227</a>.</td>
  </tr>
</table>

### 📎 Lampiran Proyek
> **Link Presentasi:** [Akses Slide PPT di Canva](https://canva.link/9jlvh5ybk3alka1)
