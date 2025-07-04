# Modul 5: Title/Abstract Screening dengan Claude

## **SESI 5A: PENGEMBANGAN INCLUSION/EXCLUSION CRITERIA**

### **Langkah 1: Penyusunan Kriteria Inklusi**

**Prompt untuk Claude:**
```
Berdasarkan framework PICO dan research question saya, bantu develop INCLUSION CRITERIA yang detail:

PICO FRAMEWORK:
P (Population): [deskripsi populasi]
I (Intervention/Interest): [deskripsi intervensi/fenomena]
C (Comparison): [deskripsi pembanding]
O (Outcome): [deskripsi outcome]

PRIMARY RESEARCH QUESTION: [research question]

Tolong bantu develop INCLUSION CRITERIA untuk:

1. STUDY DESIGN:
   - Jenis desain penelitian yang sesuai
   - Level of evidence yang diterima
   - Kriteria metodologi minimum

2. POPULATION CRITERIA:
   - Karakteristik demografis spesifik
   - Setting penelitian yang relevan
   - Sample size minimum (jika perlu)

3. INTERVENTION/EXPOSURE CRITERIA:
   - Definisi operasional yang jelas
   - Durasi minimal intervensi
   - Standardisasi yang diperlukan

4. OUTCOME CRITERIA:
   - Primary outcome yang wajib ada
   - Measurement tools yang diterima
   - Follow-up period minimum

5. PUBLICATION CRITERIA:
   - Bahasa publikasi
   - Tahun publikasi
   - Jenis publikasi (peer-reviewed, etc.)

Untuk setiap kriteria, berikan justifikasi mengapa penting untuk research question ini.
```

### **Langkah 2: Penyusunan Kriteria Eksklusi**

**Prompt untuk Claude:**
```
Berdasarkan inclusion criteria yang telah dibuat, tolong bantu develop EXCLUSION CRITERIA yang spesifik:

INCLUSION CRITERIA: [list kriteria inklusi]

Develop EXCLUSION CRITERIA untuk:

1. STUDY DESIGN EXCLUSIONS:
   - Desain penelitian yang tidak sesuai
   - Quality issues yang tidak dapat diterima
   - Publikasi yang tidak complete

2. POPULATION EXCLUSIONS:
   - Populasi yang tidak relevan
   - Komorbiditas yang mengkonfounding
   - Setting yang tidak applicable

3. INTERVENTION EXCLUSIONS:
   - Intervensi yang terlalu berbeda
   - Co-interventions yang mengkonfounding
   - Durasi yang tidak memadai

4. OUTCOME EXCLUSIONS:
   - Outcome yang tidak measurable
   - Tools yang tidak validated
   - Data yang incomplete

5. OTHER EXCLUSIONS:
   - Duplicate publications
   - Conference abstracts only
   - Non-original research

Pastikan setiap exclusion criteria:
- Tidak overlap dengan inclusion criteria
- Specific dan measurable
- Memiliki rationale yang jelas
```

### **Langkah 3: Validasi dan Refinement Criteria**

**Prompt untuk Claude:**
```
Tolong evaluasi kelengkapan dan konsistensi criteria saya:

INCLUSION CRITERIA:
[list semua inclusion criteria]

EXCLUSION CRITERIA:
[list semua exclusion criteria]

Evaluasi:
1. COMPLETENESS: Apakah semua aspek PICO sudah tercovered?
2. SPECIFICITY: Apakah criteria cukup spesifik untuk screening?
3. CONSISTENCY: Adakah overlap atau kontradiksi antar criteria?
4. FEASIBILITY: Apakah criteria dapat diaplikasikan secara praktis?
5. BIAS MINIMIZATION: Apakah criteria dapat meminimalkan selection bias?

Berikan rekomendasi untuk:
- Criteria yang perlu diperjelas
- Potential ambiguity yang harus diatasi
- Additional criteria yang mungkin diperlukan
- Simplifikasi jika terlalu kompleks
```

---

## **SESI 5B: SETUP DATABASE SCREENING**

### **Langkah 1: Persiapan Data dari Export Scopus**

**Prompt untuk Claude:**
```
Saya telah export data dari Scopus dengan [jumlah] artikel. Data yang tersedia meliputi:
- Title
- Abstract  
- Authors
- Journal
- Year
- Keywords
- DOI
- Document Type

Tolong bantu saya:
1. STRUKTUR DATABASE SCREENING:
   - Columns tambahan yang diperlukan untuk screening
   - Format numbering/ID yang systematic
   - Fields untuk tracking progress

2. DATA PREPARATION:
   - Cleaning steps yang perlu dilakukan
   - Standardisasi format yang diperlukan
   - Duplicate detection strategy

3. SCREENING WORKFLOW:
   - Sequence screening yang efisien
   - Batch size yang optimal
   - Quality control checkpoints

4. DOCUMENTATION REQUIREMENTS:
   - Fields untuk decision recording
   - Reason codes untuk exclusion
   - Reviewer identification system
```

### **Langkah 2: Template Database Screening**

**Template yang akan digunakan:**
```
DATABASE SCREENING TEMPLATE:

Required Columns:
- Study_ID: [sequential number]
- Title: [dari Scopus]
- Abstract: [dari Scopus]
- Authors: [dari Scopus]
- Journal: [dari Scopus]
- Year: [dari Scopus]
- Keywords: [dari Scopus]
- DOI: [dari Scopus]
- Decision: [INCLUDE/EXCLUDE/UNCERTAIN]
- Primary_Reason: [reason code]
- Detailed_Reason: [specific justification]
- Reviewer: [reviewer name/ID]
- Review_Date: [date of screening]
- Confidence_Level: [HIGH/MEDIUM/LOW]
- Notes: [additional comments]
```

### **Langkah 3: Systematic Screening Strategy**

**Prompt untuk Claude:**
```
Untuk screening [jumlah] artikel secara sistematis, bantu develop strategy:

TOTAL ARTICLES: [number]
ESTIMATED INCLUSION RATE: [percentage based on pilot]

Strategy needed untuk:
1. BATCH PROCESSING:
   - Optimal batch size untuk Claude processing
   - Sequencing strategy (random vs systematic)
   - Break intervals untuk quality maintenance

2. PROGRESS TRACKING:
   - Daily/weekly targets
   - Progress monitoring system
   - Quality checkpoints

3. CONSISTENCY MAINTENANCE:
   - Reference standards untuk borderline cases
   - Decision documentation procedures
   - Regular criteria review

4. EFFICIENCY OPTIMIZATION:
   - Time estimation per article
   - Workflow bottleneck identification
   - Resource allocation planning

Berikan detailed workflow step-by-step.
```

---

## **SESI 5C: PROSES SCREENING DENGAN CLAUDE**

### **Langkah 1: Single Article Screening Template**

**Prompt untuk Screening Individual:**
```
Bantu saya screen artikel berikut berdasarkan criteria yang telah ditetapkan:

INCLUSION CRITERIA:
[paste semua inclusion criteria]

EXCLUSION CRITERIA:  
[paste semua exclusion criteria]

ARTIKEL UNTUK SCREENING:
Study_ID: [ID]
Title: [title]
Abstract: [abstract]
Authors: [authors]
Journal: [journal]
Year: [year]
Keywords: [keywords]

Tolong evaluasi:
1. INCLUSION ASSESSMENT:
   - Apakah artikel memenuhi setiap inclusion criteria?
   - Evidence yang mendukung dari title/abstract
   - Level of confidence untuk setiap criteria

2. EXCLUSION ASSESSMENT:
   - Apakah ada exclusion criteria yang berlaku?
   - Specific exclusion yang triggered (jika ada)
   - Evidence yang mendukung exclusion

3. OVERALL DECISION:
   - Final decision: INCLUDE/EXCLUDE/UNCERTAIN
   - Primary reason untuk decision
   - Confidence level: HIGH/MEDIUM/LOW
   - Specific quotes dari abstract yang mendukung decision

Format output:
Decision: [INCLUDE/EXCLUDE/UNCERTAIN]
Primary_Reason: [main justification]
Triggered_Criteria: [specific criteria]
Confidence: [HIGH/MEDIUM/LOW]
Supporting_Evidence: [quotes dari abstract]
```

### **Langkah 2: Batch Screening Process**

**Prompt untuk Batch Processing:**
```
Saya akan provide batch articles untuk screening. Format yang sama untuk setiap artikel:

INCLUSION CRITERIA: [criteria list]
EXCLUSION CRITERIA: [criteria list]

BATCH ARTICLES (maksimal 5 articles per batch):

Article 1:
ID: [ID] | Title: [title] | Abstract: [abstract] | Keywords: [keywords]

Article 2:
ID: [ID] | Title: [title] | Abstract: [abstract] | Keywords: [keywords]

[continue untuk artikel lainnya]

Untuk setiap artikel, berikan assessment dalam format table:

| ID | Decision | Primary_Reason | Confidence | Key_Evidence |
|----|----------|----------------|------------|--------------|
| 1  |          |                |            |              |
| 2  |          |                |            |              |

Setelah table, berikan SUMMARY:
- Total screened: [number]
- Included: [number] 
- Excluded: [number]
- Uncertain: [number]
- Main exclusion reasons: [list top reasons]
```

### **Langkah 3: Uncertain Cases Management**

**Prompt untuk Uncertain Cases:**
```
Untuk articles yang di-flag sebagai UNCERTAIN, bantu detailed analysis:

UNCERTAIN ARTICLE:
[article details]

UNCERTAINTY REASONS:
[alasan mengapa uncertain]

Tolong bantu:
1. DETAILED CRITERIA ANALYSIS:
   - Check setiap inclusion/exclusion criteria secara detail
   - Identify specific areas of ambiguity
   - Search for additional clues dalam abstract/keywords

2. DECISION FRAMEWORK:
   - Conservative approach (exclude jika doubt)
   - Liberal approach (include untuk full-text assessment)
   - Recommendation berdasarkan research objectives

3. ADDITIONAL INFORMATION NEEDED:
   - Apakah perlu informasi dari full-text?
   - Author contact untuk clarification?
   - Additional databases search untuk similar studies?

4. FINAL RECOMMENDATION:
   - Final decision dengan strong justification
   - Risk assessment untuk false inclusion/exclusion
   - Documentation untuk audit trail
```

---

## **SESI 5D: QUALITY CONTROL DAN FINALISASI**

### **Langkah 1: Screening Results Analysis**

**Prompt untuk Results Analysis:**
```
Analisis hasil title/abstract screening:

SCREENING STATISTICS:
- Total articles screened: [number]
- Included for full-text: [number] ([percentage]%)
- Excluded: [number] ([percentage]%)
- Uncertain cases: [number]

EXCLUSION BREAKDOWN:
- Wrong population: [number]
- Wrong intervention: [number]
- Wrong study design: [number]
- Wrong outcome: [number]
- Language: [number]
- Publication type: [number]
- Other reasons: [number]

Tolong analyze:
1. SCREENING PATTERNS:
   - Apakah exclusion pattern reasonable?
   - Indication criteria terlalu restrictive/liberal?
   - Most common exclusion reasons dan implications

2. QUALITY INDICATORS:
   - Consistency dalam decision making
   - Appropriate inclusion rate untuk research question
   - Potential missed relevant studies

3. NEXT STEPS PLANNING:
   - Full-text acquisition strategy
   - Expected final inclusion numbers
   - Resource requirements untuk next phase

4. POTENTIAL ISSUES:
   - Studies yang mungkin borderline
   - Areas yang perlu special attention
   - Criteria refinement untuk full-text phase
```

### **Langkah 2: Inter-rater Reliability Assessment**

**Prompt untuk Reliability Check (jika ada second reviewer):**
```
Untuk quality assurance, bandingkan screening results dari dua reviewers:

REVIEWER 1 RESULTS: [sample of decisions]
REVIEWER 2 RESULTS: [sample of decisions for same articles]

Calculate dan analyze:
1. AGREEMENT METRICS:
   - Overall agreement percentage
   - Cohen's Kappa calculation
   - Agreement by decision type (include/exclude)

2. DISAGREEMENT ANALYSIS:
   - Articles dengan disagreement
   - Pattern disagreement (systematic bias?)
   - Most common sources of disagreement

3. RESOLUTION STRATEGY:
   - Procedure untuk resolve conflicts
   - Third reviewer involvement
   - Criteria clarification needs

4. IMPROVEMENT RECOMMENDATIONS:
   - Reviewer training areas
   - Criteria refinement
   - Process optimization

Berikan calculation step-by-step dan interpretation.
```

### **Langkah 3: Preparation untuk Full-text Phase**

**Prompt untuk Full-text Preparation:**
```
Berdasarkan hasil title/abstract screening, bantu prepare untuk full-text phase:

INCLUDED ARTICLES: [number]
ARTICLE LIST: [list dengan basic details]

Preparation needed:
1. FULL-TEXT ACQUISITION STRATEGY:
   - Priority ranking articles berdasarkan accessibility
   - Institutional access assessment
   - Open access identification
   - Author contact strategy untuk unavailable articles

2. REFINED SCREENING CRITERIA:
   - Additional criteria untuk full-text assessment
   - Specific methodological requirements
   - Data extraction requirements yang impact inclusion

3. RESOURCE PLANNING:
   - Time estimation untuk full-text screening
   - Workload distribution
   - Quality control procedures

4. DOCUMENTATION UPDATES:
   - PRISMA flow diagram preparation
   - Screening results summary
   - Method section documentation

5. CONTINGENCY PLANNING:
   - Jika terlalu banyak articles included
   - Jika terlalu sedikit articles available
   - Alternative search strategies

Berikan detailed action plan dengan timelines.
```

### **Langkah 4: Documentation Template**

**Template Dokumentasi Screening Results:**

```
TITLE/ABSTRACT SCREENING RESULTS - SYSTEMATIC LITERATURE REVIEW

Tanggal Screening: [date range]
Reviewer(s): [names]
Research Question: [research question]

SCREENING CRITERIA:
Inclusion Criteria:
- [list semua inclusion criteria]

Exclusion Criteria:
- [list semua exclusion criteria]

SCREENING RESULTS:
Total articles from search: [number]
After duplicate removal: [number]
Title/Abstract screened: [number]
Included for full-text: [number] ([percentage]%)
Excluded: [number] ([percentage]%)

EXCLUSION REASONS:
- [reason 1]: [number] articles
- [reason 2]: [number] articles
- [continue untuk semua reasons]

QUALITY ASSURANCE:
- Inter-rater reliability: [kappa value if applicable]
- Uncertain cases resolved: [number]
- Criteria modifications: [any changes made]

NEXT STEPS:
- Full-text acquisition target: [number] articles
- Expected timeline: [dates]
- Resource requirements: [requirements]

ARTICLES FOR FULL-TEXT REVIEW:
[list dengan Study_ID, Authors, Title, Journal, Year, DOI]
```
