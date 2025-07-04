# Modul 5: Title/Abstract Screening dengan GenAI

---

## **LANGKAH 1: SETUP INCLUSION/EXCLUSION CRITERIA**

### **Prompt untuk GenAI:**
```
Berdasarkan PICO framework dan research question saya:

PICO:
P: [Population/Problem]
I: [Intervention/Exposure]
C: [Comparison]
O: [Outcome]

Research Question: [research question]

Tolong bantu saya develop specific inclusion/exclusion criteria untuk title/abstract screening:

INCLUSION CRITERIA:
1. Study design: [types yang diterima]
2. Population: [karakteristik spesifik]
3. Intervention: [jenis yang relevan]
4. Outcome: [measures yang diterima]
5. Language: [bahasa yang diterima]
6. Publication type: [article, review, etc.]

EXCLUSION CRITERIA:
1. [specific exclusions dengan rationale]
2. [specific exclusions dengan rationale]
3. [specific exclusions dengan rationale]

Buat criteria yang clear, measurable, dan can be applied consistently.
```

**Review dan finalize** criteria sebelum mulai screening.

---

## **LANGKAH 2: BATCH SCREENING DENGAN GenAI**

### **Setup Screening Process:**
1. **Bagi CSV file** menjadi batch 10-15 artikel per batch
2. **Buat tracking spreadsheet** dengan columns:
   - ID/Number
   - Title
   - Decision (INCLUDE/EXCLUDE/UNCERTAIN)
   - Reason
   - Date

### **Prompt untuk Batch Screening:**
```
Saya akan melakukan title/abstract screening untuk systematic review.

INCLUSION CRITERIA:
[Gunakan inclusion criteria diatas/paste criteria yang sudah dibuat]

EXCLUSION CRITERIA:
[Gunakan exclusion criteria diatas/paste criteria yang sudah dibuat]

DATA UNTUK SCREENING:
[Gunakan dataset csv hasil tambang dari scopus]
1. Title: [title] | Abstract: [abstract] | Keywords: [keywords]
2. Title: [title] | Abstract: [abstract] | Keywords: [keywords]
[dst...]

Untuk setiap artikel, berikan:
- Decision: INCLUDE / EXCLUDE / UNCERTAIN
- Reason: Primary reason untuk decision
- Key Evidence: Phrase dari title/abstract yang support decision

Format output:
1. INCLUDE - Reason: [reason] - Evidence: "[key phrase]"
2. EXCLUDE - Reason: [reason] - Evidence: "[key phrase]"
[dst...]
```

**Process batch by batch** dan document decisions apabila data terlalu besar.

---

## **LANGKAH 3: REVIEW HASIL DAN PREPARE FULL-TEXT LIST**

### **Analyze Screening Results dengan GenAI:**
```
Hasil title/abstract screening saya:

TOTAL ARTICLES SCREENED: [number]
INCLUDED: [number] ([percentage]%)
EXCLUDED: [number] ([percentage]%)
UNCERTAIN: [number] ([percentage]%)

EXCLUSION REASONS BREAKDOWN:
- Wrong population: [number]
- Wrong intervention: [number]
- Wrong outcome: [number]
- Wrong study design: [number]
- Language: [number]
- Other: [number]

UNCERTAIN CASES:
[list artikel yang uncertain dengan alasan]

Tolong bantu:
1. Evaluate apakah exclusion pattern reasonable
2. Recommendation untuk handle uncertain cases
3. Suggest approach untuk resolve ambiguous articles
4. Prepare final list untuk full-text screening
5. Estimate full-text screening workload

Berikan recommendations untuk next steps.
```

**Finalize** included articles list dan prepare untuk full-text acquisition.

---

## **HASIL AKHIR**

### **Title/Abstract Screening Summary:**
```
=== TITLE/ABSTRACT SCREENING RESULTS ===

SCREENING OVERVIEW:
- Total articles screened: [number]
- Screening period: [dates]
- Criteria applied: ✓ Consistently
- Quality control: ✓ Implemented

RESULTS BREAKDOWN:
- INCLUDED for full-text: [number] ([percentage]%)
- EXCLUDED: [number] ([percentage]%)
- UNCERTAIN (resolved): [number] ([percentage]%)

EXCLUSION ANALYSIS:
- Population mismatch: [number]
- Intervention irrelevant: [number]
- Outcome not measured: [number]
- Study design inappropriate: [number]
- Language barrier: [number]
- Publication type: [number]
- Other reasons: [number]

INCLUDED ARTICLES LIST:
[list artikel yang lolos screening dengan brief identifier]

SCREENING QUALITY:
- Consistency check: ✓ Passed
- Criteria adherence: ✓ Verified
- Documentation: ✓ Complete

NEXT STEPS:
1. Acquire full-text articles
2. Conduct full-text screening
3. Proceed to data extraction

ESTIMATED FULL-TEXT WORKLOAD: [number] articles
```

---
