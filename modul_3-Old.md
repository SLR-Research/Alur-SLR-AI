# Modul 3: Perumusan Research Question dengan Framework PICO Menggunakan Claude

## **SESI 3A: BRAINSTORMING TOPIK PENELITIAN**

### **Langkah 1: Eksplorasi Topik dengan Claude**

**Aktivitas Individual:**
Buka Claude dan gunakan prompt berikut (sesuaikan dengan bidang Anda):

```
Saya seorang peneliti di bidang [sebutkan bidang: kesehatan/pendidikan/teknologi/bisnis/dll]. 
Saya ingin melakukan systematic literature review untuk publikasi di jurnal bereputasi.

Tolong bantu saya:
1. Identifikasi 5 topik penelitian yang sedang trending dan memiliki research gap
2. Untuk setiap topik, jelaskan mengapa penting untuk diteliti
3. Berikan gambaran potensi kontribusi terhadap ilmu pengetahuan
4. Sebutkan jenis penelitian yang biasanya dilakukan untuk topik tersebut

Bidang spesifik saya: [sebutkan lebih detail, misal: manajemen sumber daya manusia, pendidikan anak usia dini, teknologi blockchain, dll]
```

**Output yang Diharapkan:**
- Daftar 5 topik potensial dengan justifikasi
- Pemahaman tren penelitian terkini
- Insight tentang research gaps

### **Langkah 2: Evaluasi dan Seleksi Topik**

**Prompt Lanjutan untuk Claude:**
```
Berdasarkan 5 topik yang Anda berikan, tolong bantu saya evaluasi dengan kriteria:

KRITERIA EVALUASI:
1. FEASIBILITY: Apakah topik dapat diteliti dengan resources yang tersedia?
2. INTEREST: Seberapa menarik topik ini untuk komunitas akademik?
3. NOVELTY: Apa aspek baru yang belum banyak diteliti?
4. ETHICAL: Adakah isu etis yang perlu dipertimbangkan?
5. RELEVANCE: Seberapa relevan dengan praktik dan kebijakan saat ini?

Untuk setiap topik, berikan:
- Skor 1-5 untuk setiap kriteria
- Justifikasi singkat
- Rekomendasi ranking topik
- Saran fokus penelitian yang spesifik
```

---

## **SESI 3B: PENGEMBANGAN FRAMEWORK PICO**

### **Langkah 1: Pemahaman Komponen PICO**

**Teori Singkat:**
- **P (Population/Problem)**: Siapa target populasi atau masalah apa yang diteliti?
- **I (Intervention/Interest)**: Intervensi, paparan, atau fenomena yang diteliti
- **C (Comparison)**: Pembanding atau kontrol (jika ada)
- **O (Outcome)**: Hasil atau dampak yang diukur

**Contoh PICO:**
- P: Mahasiswa tingkat akhir di perguruan tinggi
- I: Program mentoring sebaya (peer mentoring)
- C: Tidak ada program mentoring atau metode konvensional
- O: Tingkat stres akademik dan prestasi belajar

### **Langkah 2: Pengembangan PICO dengan Claude**

**Prompt untuk Pengembangan PICO:**
```
Saya ingin mengembangkan framework PICO untuk topik penelitian: [topik yang dipilih]

Konteks penelitian:
- Bidang: [bidang penelitian]
- Setting: [rumah sakit/sekolah/perusahaan/dll]
- Fokus utama: [apa yang ingin diteliti]

Tolong bantu saya mengembangkan:

P (Population/Problem): 
- Siapa target populasi yang spesifik?
- Karakteristik apa yang penting?
- Kriteria inklusi/eksklusi yang relevan?

I (Intervention/Interest):
- Apa intervensi/fenomena yang diteliti?
- Bagaimana mendefinisikannya secara operasional?
- Variasi atau jenis yang perlu dipertimbangkan?

C (Comparison):
- Apa pembanding yang tepat?
- Apakah perlu kelompok kontrol?
- Alternatif pembanding yang mungkin?

O (Outcome):
- Outcome primer apa yang paling penting?
- Outcome sekunder yang relevan?
- Cara mengukur outcome tersebut?

Berikan 2-3 alternatif untuk setiap komponen agar saya bisa memilih yang terbaik.
```

### **Langkah 3: Refinement PICO**

**Prompt untuk Penyempurnaan:**
```
Berdasarkan diskusi sebelumnya, saya memilih komponen PICO:

P: [pilihan final P]
I: [pilihan final I]
C: [pilihan final C]
O: [pilihan final O]

Tolong evaluasi dan sempurnakan:
1. Apakah setiap komponen sudah spesifik dan measurable?
2. Apakah kombinasi PICO ini feasible untuk SLR?
3. Adakah potential confounding factors yang perlu dipertimbangkan?
4. Saran untuk membuat komponen lebih fokus atau lebih luas?
5. Estimasi jumlah studi yang mungkin ditemukan dengan PICO ini?
```

---

## **SESI 3C: FORMULASI RESEARCH QUESTION**

### **Langkah 1: Primary Research Question**

**Prompt untuk Formulasi:**
```
Berdasarkan framework PICO final:
P: [final P]
I: [final I]
C: [final C]
O: [final O]

Tolong formulasikan PRIMARY RESEARCH QUESTION yang:
1. Mengintegrasikan semua komponen PICO
2. Jelas dan spesifik
3. Dapat dijawab melalui systematic literature review
4. Menggunakan kata tanya yang tepat (bagaimana/seberapa/apakah)

Berikan 3 alternatif formulasi research question dengan style yang berbeda:
- Formulasi 1: Format pertanyaan langsung
- Formulasi 2: Format investigative
- Formulasi 3: Format comparative

Untuk setiap formulasi, jelaskan kelebihan dan kekurangannya.
```

### **Langkah 2: Secondary Research Questions**

**Prompt untuk Secondary Questions:**
```
Berdasarkan primary research question: [research question terpilih]

Tolong bantu kembangkan 2-3 SECONDARY RESEARCH QUESTIONS yang:
1. Mendukung dan memperkaya primary question
2. Mengeksplorasi aspek spesifik yang belum tercakup
3. Dapat dijawab dengan data yang sama
4. Memberikan insights tambahan yang valuable

Pertimbangkan aspek-aspek seperti:
- Subgroup analysis (berdasarkan demografis, severity, dll)
- Moderating factors
- Mediating variables  
- Implementation factors
- Cost-effectiveness (jika relevan)

Format: Berikan secondary questions dengan justifikasi mengapa penting.
```

### **Langkah 3: Validasi dengan Kriteria FINER**

**Prompt untuk Validasi:**
```
Tolong evaluasi research question saya dengan kriteria FINER:

PRIMARY RESEARCH QUESTION: [research question final]
SECONDARY RESEARCH QUESTIONS: [list secondary questions]

EVALUASI FINER:
F (FEASIBLE): 
- Apakah pertanyaan ini dapat dijawab dengan resources yang ada?
- Estimasi waktu dan effort yang dibutuhkan?

I (INTERESTING):
- Seberapa menarik untuk komunitas akademik dan praktisi?
- Potensi impact terhadap field ini?

N (NOVEL):
- Apa aspek baru yang belum pernah direview secara sistematis?
- Kontribusi unik terhadap existing knowledge?

E (ETHICAL):
- Adakah isu etis dalam penelitian ini?
- Apakah semua aspek sudah ethical?

R (RELEVANT):
- Relevansi dengan praktik current dan future?
- Aplikabilitas hasil untuk decision making?

Berikan skor 1-5 untuk setiap kriteria dan overall recommendation.
```

---

## **SESI 3D: FINALISASI DAN DOKUMENTASI**

### **Langkah 1: Hypothesis Development**

**Prompt untuk Hipotesis (jika applicable):**
```
Berdasarkan research questions yang telah diformulasikan, tolong bantu develop:

RESEARCH QUESTIONS: [list semua research questions]

1. NULL HYPOTHESIS (H0):
- Formulasi untuk primary research question
- Asumsi "tidak ada perbedaan/hubungan"

2. ALTERNATIVE HYPOTHESIS (H1):
- Formulasi yang mendukung expected findings
- Direction hypothesis (jika ada basis teori)

3. RATIONALE:
- Theoretical background yang mendukung hipotesis
- Previous evidence yang relevan
- Justifikasi untuk direction hypothesis

Note: Jika penelitian bersifat exploratory, jelaskan mengapa hypothesis tidak diperlukan.
```

### **Langkah 2: Documentation Template**

**Template Dokumentasi Research Question:**

```
DOKUMENTASI RESEARCH QUESTION - SYSTEMATIC LITERATURE REVIEW

Tanggal: [tanggal]
Peneliti: [nama]
Bidang Penelitian: [bidang]

FRAMEWORK PICO:
P (Population): [deskripsi detail]
I (Intervention/Interest): [deskripsi detail]  
C (Comparison): [deskripsi detail]
O (Outcome): [deskripsi detail]

PRIMARY RESEARCH QUESTION:
[research question lengkap]

SECONDARY RESEARCH QUESTIONS:
1. [secondary question 1]
2. [secondary question 2]
3. [secondary question 3]

HIPOTESIS (jika applicable):
H0: [null hypothesis]
H1: [alternative hypothesis]

VALIDASI FINER:
- Feasible: [skor dan justifikasi]
- Interesting: [skor dan justifikasi]
- Novel: [skor dan justifikasi]
- Ethical: [skor dan justifikasi]
- Relevant: [skor dan justifikasi]

ESTIMASI PENELITIAN:
- Estimasi jumlah studi: [range]
- Timeline yang dibutuhkan: [estimasi]
- Challenges yang diantisipasi: [list]

NEXT STEPS:
1. Protocol development
2. Search strategy development
3. Database selection
```
