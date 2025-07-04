# Modul 6: Full-text Acquisition dan Screening

---

## **LANGKAH 1: FULL-TEXT ACQUISITION STRATEGY**

### **Prompt untuk GenAI:**
```
Saya memiliki [number] artikel yang lolos title/abstract screening untuk full-text review:

ARTICLES LIST:
[paste list artikel dengan format: Author, Year, Title, Journal]

Tolong bantu saya develop acquisition strategy:

1. PRIORITY ASSESSMENT:
   - Identify artikel yang likely accessible via institutional access
   - Identify open access articles
   - Rank by importance untuk research question

2. ACQUISITION METHODS:
   - Institutional library access
   - Open access repositories
   - Author contact strategy
   - Alternative sources

3. TIMELINE PLANNING:
   - Realistic timeframe untuk acquisition
   - Backup plans untuk inaccessible articles
   - Decision criteria untuk proceed without certain articles

4. TRACKING SYSTEM:
   - Organize files dengan proper naming
   - Track acquisition status
   - Document access issues

Berikan systematic approach untuk efficient acquisition.
```

**Implement** acquisition strategy dan organize files.

---

## **LANGKAH 2: FULL-TEXT SCREENING DENGAN GenAI**

### **Setup Full-text Screening:**
1. **Organize acquired PDFs** dengan naming: "ID_FirstAuthor_Year.pdf"
2. **Create detailed screening form** berdasarkan inclusion/exclusion criteria
3. **Prepare for systematic review** artikel by artikel
4. **Tambahan** Jika File kurang dari 20, minta GenAI untuk menggunakan aksesnya (Tidak memerlukan Pdf)

### **Prompt untuk Full-text Screening:**
```
Saya akan melakukan full-text screening untuk artikel:

ARTIKEL DETAILS:
- Title: [title]
- Authors: [authors]
- Year: [year]
- Journal: [journal]

INCLUSION CRITERIA (detailed):
[Guanakan INCLUSION CRITERIA sebelumnya / paste detailed criteria dari Modul 5]

EXCLUSION CRITERIA (detailed):
[Gunakan EXCLUSION CRITERIA sebelumnya / paste detailed criteria dari Modul 5]

// Apabila kurang dari 20, gunakan aksesmu untuk memperoleh fulltext artikel 

FULL-TEXT CONTENT:
[paste key sections: Abstract, Methods, Results, atau key paragraphs]

Tolong evaluate artikel ini berdasarkan:

1. STUDY DESIGN CONFIRMATION:
   - Actual study design vs claimed design
   - Methodology appropriateness untuk research question

2. POPULATION VERIFICATION:
   - Exact population characteristics
   - Sample size dan demographics
   - Setting dan context

3. INTERVENTION/EXPOSURE DETAILS:
   - Clear description dan implementation
   - Duration, intensity, standardization
   - Comparison group details

4. OUTCOME MEASUREMENTS:
   - Primary vs secondary outcomes
   - Measurement tools dan validity
   - Statistical analysis appropriateness

5. FINAL DECISION:
   - INCLUDE / EXCLUDE dengan detailed justification
   - Quality concerns jika included
   - Missing information yang critical

Format comprehensive assessment.
```

**Screen** setiap artikel dan document decisions.

---

## **LANGKAH 3: FINALIZE INCLUDED STUDIES DAN PREPARE DATA EXTRACTION**

### **Analyze Full-text Results dengan GenAI:**
```
Hasil full-text screening saya:

SCREENING SUMMARY:
- Articles acquired: [number]
- Articles not accessible: [number]
- Full-text screened: [number]
- INCLUDED: [number]
- EXCLUDED: [number]

EXCLUSION REASONS (full-text stage):
- Methodology inappropriate: [number]
- Population not matching: [number]
- Intervention details unclear: [number]
- Outcomes not measured: [number]
- Poor study quality: [number]
- Other: [number]

INCLUDED STUDIES LIST:
[list final included studies dengan brief description]

INACCESSIBLE STUDIES:
[list artikel yang tidak bisa diakses]

Tolong bantu:
1. Assess impact dari inaccessible articles pada review completeness
2. Evaluate final study selection quality
3. Identify potential bias dari missing studies
4. Recommend data extraction approach
5. Suggest quality assessment tools untuk included studies
6. Prepare for synthesis planning

Berikan recommendations untuk proceed ke data extraction.
```

**Peserta finalize** study selection dan prepare untuk data extraction phase.

---

## **HASIL AKHIR**

### **Full-text Screening Summary:**
```
=== FULL-TEXT SCREENING RESULTS ===

ACQUISITION RESULTS:
- Target articles: [number]
- Successfully acquired: [number] ([percentage]%)
- Not accessible: [number] ([percentage]%)
- Acquisition methods used: [list methods]

SCREENING RESULTS:
- Full-text articles screened: [number]
- INCLUDED in final review: [number] ([percentage]%)
- EXCLUDED at full-text stage: [number] ([percentage]%)

EXCLUSION ANALYSIS (full-text):
- Study design issues: [number]
- Population mismatch: [number]
- Intervention inappropriate: [number]
- Outcomes not relevant: [number]
- Methodological concerns: [number]
- Data quality issues: [number]

FINAL INCLUDED STUDIES:
[detailed list dengan citation dan brief description]

STUDY CHARACTERISTICS:
- Publication years: [range]
- Study designs: [breakdown]
- Sample sizes: [range]
- Geographic distribution: [countries]
- Quality indicators: [preliminary assessment]

INACCESSIBLE STUDIES IMPACT:
- Potential bias: [assessment]
- Missing data: [estimate]
- Review completeness: [percentage]

NEXT STEPS:
1. Data extraction from included studies
2. Quality assessment implementation
3. Synthesis planning based on study characteristics

READY FOR DATA EXTRACTION: ✓
```
