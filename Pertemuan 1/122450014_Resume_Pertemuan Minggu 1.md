# Tugas VDI Pertemuan 1
**Nama     : Deva Anjani Khayyuninafsyah**\
**NIM      : 122450014**\
**Kelas    : RB**

## **Pendahuluan**
Dewasa ini, semua organisasi mempunyai data dengan jumlah yang begitu besar sehingga banyak organisasi menggunakan data serta analisis lanjutan guna membuat suatu keputusan yang strategis. Hal ini menjadikan visualisasi data berperan penting dalam memberikan gambaran umum tentang data yang besar sehingga mampu membantu menginterpretasikan hasil analisis data secara lebih efisien dan efektif. Tidak hanya itu, visualisasi data telah berkembang pesat di berbagai bidang melalui kontribusi beberapa komunitas, seperti komunitas grafis komputer, visualisasi, dan basis data.

Visualisasi data beberapa tahapan sebagai berikut.
1. **Impor data** : data berasal dari sumber yang diinginkan.
2. **Persiapan data** : melalui proses normalisasi, koreksi kesalahan, juga interpolasi nilai yang hilang.
3. **Manipulasi data** : menggunakan seleksi, penggabungan, dan pengelompokkan data.
4. **Pemetaan data** : data dipetakan dalam bentuk geometri, seperti titik dan garis, dengan atribut, seperti warna dan ukuran.
5. **Rendering** : guna mengubah data geometri menjadi representasi visual.

## **Spesifikasi Visualisasi**
Spesifikasi visualisasi menunjukkan bagaimana pengguna mampu menentukan kebutuhan mereka dalam menghasilkan suatu visualisasi. Terdapat tiga bagian utama dari spesifikasi visualisasi, yaitu :
1. **_Data_**, yaitu data yang akan divisualisasikan.
2. **_Marks_**, yaitu representasi visual dari data.
3. **_Mapping_**, yaitu proses menghubungkan antara data dengan _marks_ yang sesuai.

## **Kategori Bahasa Visual**
Bentuk dari spesifikasi visualisasi dapat berupa bahasa visual. Berdasarkan tingkat ekspresivitas dan kemudahan penggunaannya, bahasa visual dikelompokkan ke dalam kategori berikut.
1. **Level rendah** : pengguna menentukan seluruh elemen pemetaan secara detail.
2. **Level tinggi** : menyediakan abstraksi lebih tinggi dengan mengurangi detail yang harus diatasi oleh pengguna.
3. **Operasi visual berbasis GUI** : _GUI-Based Tools_ merupakan alat yang berbasis antarmuka grafis. Alat ini merupakan alternatif lain, selain bahasa grafis, yang memudahkan pengguna dalam menentukan visualisasi secara langsung melalui interaksi grafis sehingga bagi mereka yang tidak memiliki latar belakang teknis mudah untuk melakukan visualisasi. Salah satu contoh dari alat ini adalah _Tubleau_. Dengan _Tubleau_, pengguna mampu menarik atribut untuk membuat visualisasi.
4. **Spesifikasi yang kurang jelas** : ketika pengguna tidak memiliki gambaran tentang data yang ingin divisualisasikan, sistem visualisasi akan memberikan saran atau melengkapi visualisasi tersebut secara otomatis.

Bahasa visual dalam hal ini begitu penting diperhatikan pemilihannya sesuai dengan kebutuhan dan keterampilan pengguna. Pendekatan spesifikasi visualisasi ini penting untuk menambah efisiensi serta efektivitas dalam menghasilkan visualisasi suatu data.

## **Pendekatan Efisien untuk Visualisasi Data**
Pendekatan efisien untuk visualisasi data mencakup teknik-teknik berikut.
1. **Visualisasi data yang akurat**, meliputi _query translation_ (_query_ visualisasi bisa diterjemahkan menjadi SQL lalu diolah DBMS); integrasi dengan DBMS (mengintegrasi pengambilan data dan _rendering_ untuk mempercepat pembuatan visualisasi); _indexing_ (untuk mempercepat akses data dalam visualisasi); komputasi paralel (untuk memproses _query_ visualisasi secara bersama); _prediction and prefetching_ (memperkirakan data yang dibutuhkan selanjutnya).
2. **Visualisasi data yang hampir akurat**, meliputi pendekatan AQP dengan subset data yang representatif (untuk menghasilkan visualisasi yang mendekati akurat); _incremental sampling_ (visualisasi mendekati akurat dengan hasil bertahap); _human perception-based aproaches_ (menghentikan sampling saat perbedaan visualisasi tidak lagi terlihat oleh manusia).
3. **Visualisasi data progresif** : pada teknik ini visualisasi dibuat secara bertahap dengan membenahi hasil sementara seiring berjalannya waktu.

Teknik-teknik di atas dapat meningkatkan efisiensi dan skala dalam proses visualisasi data karena visualisasi data sering melibatkan siklus iteratif dengan pengguna yang terlibat. Dengan begitu, pengguna dapat mengeksplorasi data dengan cepat serta mengambil keputusan berdasarkan visualisasi secara cepat dan akurat.

## **Rekomendasi Visualisasi**
Selain teknik pendekatan efisien untuk visualisasi data, juga terdapat teknik untuk merekomendasikan visualisasi kepada pengguna secara otomatis. Teknik-teknik tersebut meliputi :
1. **Pendekatan umum rekomendasi visualisasi** : sistem rekomendasi menghasilkan semua kemungkinan visualisasi lalu menyaringnya kemudian me-_ranking_ visualisasi yang paling relevan. Selain itu, terdapat _pruning_ visualisasi untuk menyaring visualisasi yang tidak relevan.
2. **Rekomendasi berdasarkan spesifikasi** : untuk spesifikasi yang tidak lengkap, sistem rekomendasi akan melengkapi petunjuk dari pengguna kemudian memberi saran visualisasi yang relevan. Dalam me-_ranking_ visualisasi, beberapa sistem awal ada yang menggunakan pendekatan berbasis aturan berdasarkan efektivitas perseptual. Selain itu, sistem modern sudah mulai menggunakan pembelajaran mesin untuk me-_ranking_ visualisasi berdasarkan contoh yang telah dipelajari sehingga rekomendasi lebih adaptif serta personal.
3. **Rekomendasi berdasarkan perilaku pengguna** : rekomendasi ini berasal dari riwayat perilaku pengguna sehingga rekomendasi yang diberikan akan lebih personal.
4. **Rekomendasi yang dipersonalisasi** : rekomendasi ini melibatkan preferensi dan kebutuhan pengguna untuk menyarankan visualisasi yang sesuai dengan mempertimbangkan konteks pengguna.

Melalui rekomendasi visualisasi di atas, proses visualisasi menjadi sederhana dalam memberi saran yang relevan secara otomatis kepada para pengguna. Proses pengambilan keputusan juga akan menjadi lebih cepat sehingga pengguna mampu menemukan solusi secara lebih efektif dan efisien.

## **Arah Penelitian Lain**
Dalam hal meningkatkan efisiensi dan efektivitas dari proses visualisasi data, terdapat beberapa penelitian lain yang mampu mengatasi hal tersebut di masa depan. Beberapa di antaranya, yakni sebagai berikut.
1. **_Visual Querying_** : pengguna bisa mengajukan pertanyaan dan mendapat jawaban dalam bentuk visualisasi data secara langsung. Penelitian lebih lanjut yang dibutuhkan, yakni pengembangan metode yang lebih intuitif dan _user-friendly_.
2. **_Data Cleaning and Integration_** : penelitian lebih lanjut yang dibutuhkan, yakni menggabungkan proses pembersihan data dan integrasi data dengan visualisasi data dengan lebih erat agar pengguna bisa langsung mengerjakan data yang siap untuk divisualisasikan.
3. **_Handling Uncertainty in Visualization_** : pada beberapa kasus terdapat ketidakpastian dalam data sehingg diperlukan penelitian lebih lanjut untuk mengembangkan teknik visualisasi yang lebih jelas dan efektif menggambarkan ketidakpastian tersebut kepada pengguna.
4. **_Scalability_** : dalam pesatnya perkembangan data, skalabilitas dapat menjadi suatu tantangan yang penting. Maka diperlukan penelitian lebih lanjut untuk mengembangkan teknik visualisasi yang dapat diskalakan dengan baik.
5. **_Real-Time Data Visualization_** : penelitian lebih lanjut yang dibutuhkan dalam kasus ini, yaitu pengembangan teknik visualisasi yang mampu mengatasi aliran data secara _real-time_ dan memberi hasil visualisasi yang responsif.
6. **_Visualization for Collaborative Analysis_** : kasus ini penting mengingat banyaknya keputusan yang diambil secara kolektif dalam tim. Oleh karena itu, penelitiannya harus fokus pada bagaimana alat-alat visualisasi mampu mendukung kolaborasi yang lebih baik antara anggota tim.

Melalui penelitian-penelitian lebih lanjut tersebut, diharapkan mampu membawa inovasi dalam memahami dan mempergunakan data visualisasi yang lebih efisien dan efektif.

## **Kesimpulan**
Visualisasi data begitu penting untuk membantu semua kalangan dalam memanfaatkan data besar sehingga pengambilan keputusan daoat dilakukan secara strategis dan terarah. Walaupun sudah banyak yang mengaplikasikannya, tantangan terkait efisiensi dan efektivitas visualisasi data masih perlu diperhatikan. Dalam hal ini telah diketahui bahwa terdapat berbagai pendekatan, seperti spesifikasi visualisasi, metode untuk mempercepat proses visualisasi, dan sistem rekomendasi otomatis yang dapat membuat visualisasi menjadi lebih efisien dan efektif. Di samping itu, dibutuhkan pula penelitian lebih lanjut di bidang tertentu, misalnya pada _visual querying_, penanganan ketidakpastian, skalabilitas, visualisasi _real-time_, dan analisis kolaboratif untuk meningkatkan pengalaman pengguna dalam bekerja dengan data. Dengan menggabungkan teknik-teknik yang ada dan mengeksplorasi arah penelitian baru, visualisasi data dapat menjadi lebih bermanfaat dan relevan dalam menghadapi tantangan bisnis dan industri yang terus berkembang.