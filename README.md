# NYC Traffic Safety & Collision Analysis Dashboard

Dashboard Excel interaktif untuk menganalisis pola kecelakaan lalu lintas di New York City, mengidentifikasi faktor pemicu utama, serta memetakan titik rawan wilayah dan waktu berisiko tinggi guna mendukung rekomendasi keselamatan jalan. Dikerjakan menggunakan Microsoft Excel (PivotTable, PivotChart, dan Data Modeling).

<img width="479" height="354" alt="image" src="https://github.com/user-attachments/assets/eea287ca-5c1e-418f-9f5e-7d07a138e028" />



## Ringkasan Metrik Kunci
- **Total Kecelakaan**: 238.421 kasus
- **Korban Luka (Injuries)**: 116.227 orang
- **Korban Meninggal (Fatalities)**: 268 orang
- **Rasio Cedera**: 48,7%

---

## Problem
Tingginya angka kecelakaan lalu lintas di kawasan perkotaan padat seperti New York City menimbulkan beban keselamatan publik yang besar. Tanpa pemetaan yang jelas, alokasi patroli lalu lintas dan intervensi keselamatan berisiko tidak tepat sasaran. Analisis ini bertujuan menjawab: di mana kecelakaan paling sering terjadi, kapan waktu paling rawan, dan apa akar penyebab utamanya?

## Action
1. **Pembersihan Data**: Mengekstrak data mentah kecelakaan, menangani nilai kosong pada atribut lokasi dan faktor penyebab, serta menstandarkan penamaan wilayah (*borough*).
2. **Pemodelan & Kalkulasi**: Menambahkan ekstraksi waktu (jam dan bulan) serta rasio tingkat keparahan korban cedera/meninggal.
3. **Penyusunan Dashboard**: Membangun 4 sudut pandang analisis berbasis pertanyaan bisnis (*Di Mana, Kapan Musiman, Kapan Jam, Kenapa*) dengan ringkasan *Headline Insight* dan rekomendasi aksi di bagian bawah.

## Result & Temuan Utama
- **Wilayah (Di Mana)**: Brooklyn (76.416 kasus / 32%) dan Queens (63.751 kasus) menjadi kontributor terbesar, menyumbang hampir 59% dari total kecelakaan kota.
- **Pola Musiman (Kapan)**: Angka tabrakan mencapai puncaknya pada bulan Maret (25.099 kasus) dan relatif melandai menjelang akhir tahun.
- **Jam Rawan (Waktu)**: Tren kecelakaan meningkat signifikan mulai jam makan siang dan mencapai titik puncak pada jam sibuk pulang kerja sore hari (pukul 16.00–17.00).
- **Akar Masalah (Kenapa)**: Kelalaian pengemudi (*Driver Inattention/Distraction*) mendominasi secara mutlak dengan 58.308 kasus (±25%), disusul oleh kegagalan memberi prioritas jalan (*Failure to Yield Right-of-Way*) dan menjaga jarak aman (*Following Too Closely*).

---

## What, So What, Now What

### 1. Faktor Manusia (Distraksi)
- **What**: 1 dari 4 kecelakaan disebabkan oleh kelalaian atau distraksi pengemudi.
- **So What**: Faktor perilaku pengendara jauh lebih mematikan dibanding faktor teknis kendaraan atau kondisi jalan.
- **Now What**: Prioritaskan kampanye edukasi anti-distraksi (seperti larangan penggunaan ponsel saat menyetir) dan penegakan hukum otomatis berbasis tilang elektronik di titik padat.

### 2. Konsentrasi Wilayah (Brooklyn & Queens)
- **What**: 59% insiden terkonsentrasi di dua wilayah utama (Brooklyn & Queens).
- **So What**: Intervensi skala kota tidak perlu disebar merata; fokus pada dua area ini akan menyelesaikan lebih dari separuh masalah.
- **Now What**: Tingkatkan alokasi rambu keselamatan, pos pantau, dan patroli fisik secara masif di persimpangan rawan kedua borough tersebut.

### 3. Waktu Sibuk Sore Hari
- **What**: Lonjakan kasus terjadi stabil di rentang sore (pukul 14.00–18.00), memuncak pada jam 16–17.
- **So What**: Volume kendaraan komuter yang bercampur dengan kelelahan pengemudi di akhir jam kerja memperbesar peluang tabrakan.
- **Now What**: Perketat rekayasa lalu lintas dan siagakan personel patroli aktif menjelang jam 14.00 hingga 18.00 untuk mengurai kemacetan sebelum jam puncak.

---

## File Proyek
- File Excel Workbook: `NYC_Collisions_Analysis_Dashboard_v1.xlsx`
