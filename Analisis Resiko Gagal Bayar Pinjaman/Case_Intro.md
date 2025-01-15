## Case Study: Faktor-Faktor yang Memengaruhi Harga Penjualan Mobil

Dalam kesempatan ini, suatu bank memberikan tantangan kepada analis data untuk mencari tahu apa saja hal-hal yang dapat memengaruhi nasabah dalam gagal membayar pinjamannya. Bank yang identitasnya dirahasiakan ini memberikan beberapa hipotesa yang harus dibuktikan kebenarannya. Sebelum melangkah jauh ke sana, analis data juga direkomendasikan untuk mengeksplor data yang diberikan dengan rinci dan memastikan tidak adanya kesalahan dalam mengambil kesimpulan terhadap beberapa hipotesa yang akan diuji. Proyek ini dalam narasinya akan digunakan sebagai laporan bahan pertimbangan untuk membuat **penilaian kredit** untuk calon nasabah agar tepat sasaran. Penilaian kredit tersebut digunakan untuk mengevaluasi kemampuan calon peminjam untuk melunasi pinjaman mereka.

Tujuan utama dari adanya proyek ini adalah seperti yang telah dijelaskan sebelumnya, yaitu untuk memastikan tiga hipotesa terdapat pengaruh terhadap gagal bayar pinjaman oleh nasabah dalam suatu bank yang tidak disebutkan namanya. Berikut ini merupakan hipotesa-hipotesa yang akan diuji dan dibuktikan dalam proyek ini.
1. Apakah terdapat hubungan antara **memiliki anak** dan probabilitas seseorang melakukan gagal bayar pinjaman?
2. Apakah terdapat hubungan antara **status perkawinan** dan probabilitas seseorang melakukan gagal bayar pinjaman?
3. Apakah terdapat hubungan antara **tingkat pendapatan** dan probabilitas seseorang melakukan gagal bayar pinjaman?
4. Bagaimana **perbedaan tujuan pinjaman** memengaruhi probabilitas seseorang melakukan gagal bayar pinjaman?

|Nama Proyek    |Tujuan    |Modul    |Bahasa    |
|---------------|----------|---------|----------|
|Analisis Resiko Gagal Bayar Pinjaman|Mengetahui dan menguji apakah **memiliki anak**, **status perkawinan**, **tingkat pendapatan**, dan **perbedaan tujuan pinjaman** memiliki pengaruh terhadap kemungkinan calon nasabah dalam gagal melunasi pinjamannya|Pandas|Python|

### Deskripsi Data yang akan Digunakan
Berikut ini merupakan nama-nama kolom beserta definisinya yang akan digunakan dalam mengerjakan proyek ini.
- `children`: jumlah anak dalam keluarga
- `days_employed`: berapa lama nasabah telah bekerja
- `dob_years`: usia nasabah
- `education`: tingkat pendidikan nasabah
- `education_id`: pengidentifikasi untuk tingkat pendidikan nasabah
- `family_status`: status perkawinan dari nasabah
- `family_status_id`: pengidentifikasi untuk status perkawinan nasabah
- `gender`: jenis kelamin nasabah
- `income_type`: jenis pendapatan nasabah
- `debt`: apakah nasabah pernah gagal dalam melunasi biaya pinjaman
- `total_income`: total pendapatan atau gaji nasabah setiap bulan
- `purpose`: alasan nasabah mengambil pinjaman kepada bank
