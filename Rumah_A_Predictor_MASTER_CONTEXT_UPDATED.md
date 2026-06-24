# Rumah A Predictor - Master Context

## Maklumat Projek

**Nama Projek:** Rumah A Predictor

**Platform:**
- Streamlit Cloud
- GitHub
- Android APK WebView
- Offline Local Streamlit Backup

**Status Semasa:**
- Current Stable Version: V27.5
- Status: Stable / Production Ready
- Digunakan secara harian
- APK WebView berjaya dibina dan diuji
- Offline backup berjaya dijalankan melalui localhost

---

## Zon Masa Rujukan

Semua tarikh dan masa projek ini merujuk kepada:

**Malaysia / Kuala Lumpur / GMT+8**

Jika berbincang mengenai tarikh, draw, update keputusan, jadual atau masa semasa, gunakan zon masa Malaysia kecuali dinyatakan sebaliknya.

---

## Objektif Projek

Projek ini dibangunkan untuk membantu membuat pemilihan nombor berdasarkan analisis statistik keputusan lampau.

Matlamat projek bukan untuk meramal dengan tepat setiap draw.

Sasaran yang lebih realistik ialah:
- Menjana pilihan nombor yang lebih tersusun.
- Mengurangkan pemilihan secara rawak.
- Mengenal pasti nombor yang mempunyai potensi lebih tinggi berdasarkan data sejarah.
- Meningkatkan kebarangkalian kejayaan dalam jangka panjang.
- Jika berjaya mendapat keputusan tepat beberapa kali sebulan, itu sudah dianggap sangat baik.

---

## Falsafah Sistem

Pemilik projek memahami bahawa:
- Tiada sistem boleh menjamin kemenangan setiap draw.
- Ramalan statistik hanyalah alat bantuan keputusan.
- Kejayaan beberapa kali dalam sebulan sudah dianggap pencapaian yang baik.
- Fokus adalah kepada analisis dan kebarangkalian, bukan jaminan kemenangan.
- Sistem ini bukan bertujuan untuk main secara buta-buta, tetapi sebagai alat sokongan berdasarkan data.

---

## Susunan Home V27.5

1. Update Keputusan Terbaru
2. Keputusan Terbaru
3. Generate Ramalan
4. AI Pick Of The Day
5. Top 3 Utama
6. Strong Buy Tambahan
7. Backup Pool
8. Quick Share WhatsApp
9. History Manager
10. Analysis / Hot & Cold Digits

---

## Workflow Harian

1. Selepas keputusan draw keluar, buka app.
2. Update Keputusan Terbaru.
3. Semak Keputusan Terbaru.
4. Tekan Generate Ramalan.
5. Semak AI Pick, Top 3, Strong Buy dan Backup Pool.
6. Guna Quick Share jika mahu salin nombor.
7. History Manager hanya digunakan jika mahu semak, edit atau delete rekod lama.
8. Analysis / Hot & Cold digunakan untuk semakan teknikal tambahan.

---

## Peraturan UI

### Header

Kekalkan hanya satu header utama:

**Rumah A Predictor**  
**AI Number Selection Engine**

Jangan paparkan:
- Nombor versi pada UI.
- JSON debug.
- Tajuk berulang.
- Banner duplicate.

### Update Keputusan

- Diletakkan paling atas.
- Digunakan selepas keputusan draw keluar.
- Tidak auto-expand.
- Hanya untuk kemas kini keputusan terbaru.
- Jangan letak tab Edit dan Delete di bahagian ini.

### History Manager

- Digunakan untuk semakan sejarah.
- Menyimpan fungsi edit dan delete.
- Tidak digunakan untuk update keputusan harian.
- Boleh kekal di bawah Quick Share.

### Analysis

- Menyimpan Hot Digit Analysis.
- Menyimpan Cold Digit Analysis.
- Menyimpan analisis tambahan.
- Tidak perlu dipaparkan terlalu atas kerana ia bukan fungsi harian utama.

### Quick Share

- Digunakan untuk salin nombor ke WhatsApp atau kegunaan lain.
- Format perlu ringkas, bersih dan mudah paste.

---

## Komponen Ramalan

### AI Pick Of The Day

Pilihan utama sistem.

### Top 3 Utama

Tiga nombor terbaik berdasarkan ranking semasa.

### Strong Buy Tambahan

Nombor tambahan yang mempunyai skor tinggi.

### Backup Pool

Nombor sokongan sekiranya pilihan utama gagal.

### Quick Share

Digunakan untuk menyalin nombor ke WhatsApp atau kegunaan lain.

---

## Teknologi

### Streamlit

Frontend utama aplikasi.

### GitHub Production

Digunakan untuk source code live dan deployment Streamlit.

### Streamlit Cloud

Digunakan untuk menjalankan web app online.

### Android APK

Dibina menggunakan Android Studio.

Jenis:
- WebView APK
- APK membuka URL Streamlit
- Bukan native APK penuh

APK berjaya:
- Dibina
- Dipasang
- Diuji pada telefon Android

### Offline Backup

Offline backup berjaya dijalankan melalui:

```text
run_app.bat
↓
Python
↓
Streamlit Local
↓
localhost:8501
```

Ini membolehkan app berjalan walaupun Streamlit Cloud atau GitHub bermasalah.

---

## Lokasi Backup

### Repo Production

Digunakan untuk app live yang dihubungkan kepada Streamlit Cloud.

### Repo Backup

Nama repo backup:

```text
Rumah-A-Predictor-Backup
```

Kandungan repo backup:
- Rumah_A_Predictor_MASTER_CONTEXT.md
- CHANGELOG.md
- Rumah_A_Predictor_OFFLINE_BACKUP.zip

Tujuan repo backup:
- Disaster recovery
- Simpan dokumentasi projek
- Simpan snapshot stable version
- Rujukan untuk chat baru

---

## Fail Penting

Fail utama projek:

```text
app.py
requirements.txt
TotoHistoryAll.xlsx
README.md
```

Fail backup / dokumentasi:

```text
Rumah_A_Predictor_MASTER_CONTEXT.md
CHANGELOG.md
BACKUP_NOTES.md
README_OFFLINE.md
Rumah_A_Predictor_OFFLINE_BACKUP.zip
```

---

## Perkara Yang Tidak Perlu Diubah Tanpa Sebab Kukuh

- Struktur AI Pick
- Struktur Top 3
- Struktur Strong Buy
- Struktur Backup Pool
- Workflow Update → Generate → Pilih Nombor
- Auto Save GitHub
- APK WebView
- Offline backup structure
- Susunan Home V27.5

---

## Perkara Yang Pernah Dibaiki

Antara isu yang pernah dibetulkan:
- Paparan JSON debug dibuang.
- Header/tajuk berulang dibuang.
- Update Keputusan dipindahkan ke bahagian atas.
- Update Keputusan tidak auto-expand.
- Edit/Delete dibuang daripada bahagian Update Keputusan.
- Edit/Delete kekal di History Manager.
- Quick Share dikemaskan.
- APK WebView berjaya dibina.
- Offline backup berjaya dijalankan.
- Repo backup khas berjaya dibuat.

---

## Sejarah Penting

Projek ini pernah cuba dibangunkan beberapa tahun lalu tetapi terbengkalai kerana kekurangan bantuan teknikal.

Pada Jun 2026, projek akhirnya berjaya disiapkan sehingga:
- Streamlit siap.
- GitHub siap.
- APK WebView berjaya dibina.
- UI stabil.
- Offline backup berjaya dijalankan.
- GitHub backup repo berjaya dibuat.
- App digunakan secara harian.

Ini dianggap sebagai pencapaian utama projek.

---

## Arahan Untuk ChatGPT Dalam Chat Baru

Jika fail ini dimuat naik dalam chat baru:

1. Anggap projek sedang berada pada versi stabil V27.5.
2. Baca fail ini dahulu sebelum mencadangkan perubahan.
3. Kekalkan falsafah dan objektif projek.
4. Elakkan perubahan besar kepada algoritma tanpa sebab yang jelas.
5. Utamakan kestabilan berbanding penambahan fungsi baru.
6. Sebarang perubahan UI mestilah mengekalkan workflow harian pengguna.
7. Jangan paparkan versi pada UI kecuali diminta.
8. Jangan tambah JSON debug.
9. Jangan ubah APK WebView kepada native app kecuali diminta.
10. Jika perlu edit kod, minta atau semak `app.py` paling terbaru dahulu.
11. Rujuk masa mengikut Malaysia / Kuala Lumpur / GMT+8.

---

## Nota Untuk Pembangunan Akan Datang

Cadangan masa depan hanya selepas penggunaan sebenar:
- Hit Rate Tracker
- Prestasi AI Pick
- Prestasi Top 3
- Prestasi Strong Buy
- Rekod keputusan bulanan
- Dashboard statistik keberkesanan
- Snapshot stable release untuk V28, V29 dan seterusnya

Jangan tambah fungsi baru terlalu cepat sebelum V27.5 digunakan beberapa minggu atau bulan.
