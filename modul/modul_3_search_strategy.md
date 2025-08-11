# Modul 3: Strategi Pencarian Scopus dengan GenAI

---

## **LANGKAH 1: KEMBANGKAN KEYWORDS DARI PICO**

### **Prompt untuk GenAI:**
```
Berdasarkan PICO framework dari research question saya:

P: [Population/Problem]
I: [Intervention/Exposure]
C: [Comparison]
O: [Outcome]

Research Question: [research question]

Tolong bantu saya develop keywords untuk setiap komponen PICO:

P - POPULATION KEYWORDS:
- Main terms: [keyword utama]
- Synonyms: [sinonim]
- Alternative terms: [istilah alternatif]

I - INTERVENTION KEYWORDS:
- Main terms: [keyword utama]
- Synonyms: [sinonim]
- Alternative terms: [istilah alternatif]

C - COMPARISON KEYWORDS:
- Main terms: [keyword utama]
- Synonyms: [sinonim]
- Alternative terms: [istilah alternatif]

O - OUTCOME KEYWORDS:
- Main terms: [keyword utama]
- Synonyms: [sinonim]
- Alternative terms: [istilah alternatif]

Berikan 3-5 keywords untuk setiap komponen.
```

**Review keywords** dan tambahkan terms yang diperlukan dari domain expertise.

---

## **LANGKAH 2: KONSTRUKSI SEARCH STRING UNTUK SCOPUS**

### **Prompt untuk GenAI:**
```
Berdasarkan keywords yang sudah dikembangkan:

P keywords: [list keywords Population]
I keywords: [list keywords Intervention]
C keywords: [list keywords Comparison]
O keywords: [list keywords Outcome]

Tolong buat search string untuk Scopus dengan format:
TITLE-ABS-KEY((keyword1 OR keyword2 OR keyword3) AND (keyword4 OR keyword5) AND (keyword6 OR keyword7))

Gunakan:
- OR untuk synonyms dalam komponen yang sama
- AND untuk menghubungkan antar komponen PICO
- Wildcard (*) untuk variations (misal: educat* untuk education, educational, educating)
- Quotation marks untuk phrase searching ("machine learning")

Berikan 1 search string yang comprehensive tapi tidak terlalu broad.
```

**Copy search string** dan siap untuk testing di Scopus.

---

## **LANGKAH 3: TEST, OPTIMASI, DAN FINALISASI SEARCH STRATEGY**

### **Praktik di Scopus:**
1. **Login ke Scopus** dan masuk ke Advanced Search
2. **Gunakan search string** yang sudah dibuat
3. **Jalankan search** dan catat jumlah results
4. **Set basic filters**:
   - Document type: Article, Review
   - Language: English (atau sesuai kebutuhan)
   - Publication year: [sesuai research question]

### **Evaluasi dan Finalisasi dengan GenAI:**
```
Hasil search di Scopus:
- Search string: [search string yang digunakan]
- Total results: [jumlah hasil]
- Setelah filter: [jumlah setelah filter]

Tolong bantu saya:
1. Evaluasi apakah jumlah results reasonable untuk SLR? (ideal: 50-300 articles)
2. Jika perlu adjustment: berikan revised search string
3. Buat inclusion/exclusion criteria berdasarkan PICO
4. Dokumentasikan complete search strategy untuk research protocol

Format output yang ready untuk tahap screening.
```

**Adjust search string jika diperlukan**, lalu lanjut ke dokumentasi final.

---

## **HASIL AKHIR**

### **Complete Search Strategy Package:**
```
=== SCOPUS SEARCH STRATEGY ===

RESEARCH QUESTION: [research question]

KEYWORDS BY PICO:
P: [population keywords]
I: [intervention keywords]
C: [comparison keywords]
O: [outcome keywords]

FINAL SEARCH STRING:
[search string lengkap]

SEARCH PARAMETERS:
- Database: Scopus
- Search fields: Title-Abstract-Keywords
- Date range: [range]
- Language: [language]
- Document type: [types]

RESULTS:
- Total hits: [number]
- After filters: [number]
- Expected after screening: [estimate]

INCLUSION CRITERIA:
1. [criteria 1]
2. [criteria 2]
3. [criteria 3]

EXCLUSION CRITERIA:
1. [criteria 1]
2. [criteria 2]
3. [criteria 3]

NEXT STEP: Export data dan mulai screening
```

---

## **TROUBLESHOOTING**

**Problem 1: Results terlalu banyak (>300)**
- Tambahkan specific terms
- Narrow down time period
- Add more restrictive filters

**Problem 2: Results terlalu sedikit (<50)**
- Gunakan broader terms
- Reduce number of AND operators
- Extend time period

**Problem 3: Search string error di Scopus**
- Check bracket placement
- Verify quotation marks
- Ensure proper Boolean operators

**Problem 4: Irrelevant results**
- Review keywords relevance
- Add specific exclusion terms
- Refine PICO components

---
