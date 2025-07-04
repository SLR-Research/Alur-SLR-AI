# Alur Pelatihan SLR dengan Gen AI untuk Artikel Jurnal Bereputasi - Panduan Spesifik


![slr_workflow (1)](https://github.com/user-attachments/assets/2d6bb95a-1edc-4c42-bccc-0ff6d1fe3860)


## **MODUL 1: FONDASI TEORI DAN KONSEP**

### Sesi 1: Pengenalan SLR
- **Teori**: Definisi, tujuan, dan jenis-jenis literature review
- **Perbedaan**: Narrative review vs Systematic review vs Meta-analysis
- **Standar kualitas**: PRISMA guidelines, Cochrane standards
- **Praktik**: Analisis contoh SLR yang baik dan buruk

### Sesi 2: Metodologi SLR
- **Research question**: Formulasi PICO/SPIDER framework
- **Search strategy**: Database Scopus, keyword development
- **Inclusion/exclusion criteria**: Pengembangan kriteria yang jelas
- **Quality assessment**: Tools dan checklist evaluasi

### Sesi 3: Pengenalan Gen AI dalam Penelitian
- **Etika penggunaan AI**: Transparansi, bias, limitasi
- **Gen AI capabilities**: Natural language processing untuk research
- **Academic integrity**: Batasan dan pedoman penggunaan
- **Setup**: Akses Gen AI dan eksplorasi interface

---

## **MODUL 2: PERUMUSAN RESEARCH QUESTION DENGAN Gen AI**
- [Modul 2: Perumusan Research Question](./modul/modul_2.md)

## **MODUL 3: STRATEGI PENCARIAN SCOPUS DENGAN Gen AI**
- [Modul 3: Strategi Pencarian Scopus](./modul/modul_3_search_strategy.md)

## **MODUL 4: EKSEKUSI PENCARIAN DAN DATA MINING SCOPUS**
- [Modul 4: Data mining Scopus](./modul/modul_4_data_mining.md)

## **MODUL 5: SCREENING DAN SELECTION DENGAN Gen AI**
- [Modul 5: Title/Abstract Screening dengan GenAI](.modul/modul_5_screening.md)

## **MODUL 6: FULL TEXT Full-text Acquisition dan Screening**
- [Modul 6: FULL TEXT Full-text Acquisition](.modul/modul_6_fulltext.md)

## **MODUL 7: DATA EXTRACTION DAN DATABASE BUILDING**
- [Modul 7: Data Extraction dan Quality Assessment](.modul/modul_7_extraction.md)

## **MODUL 8: DATA ANALYSIS DAN SYNTHESIS DENGAN Gen AI**
- [Modul 8: Data Analysis dan Synthesis](.modul/modul_8_analysis.md)

## **MODUL 9: Manuscript Writing dengan GenAI**
- [Modul 9: Manuscript Writing](.modul/modul_9_writing.md)

### **Langkah 1: Quality Assessment Tool Selection**
**Prompt untuk Gen AI:**
```
Berdasarkan study designs dalam review saya:
[list study designs dan jumlah]

Tolong recommend:
1. Appropriate quality assessment tools (CASP, JBI, ROBINS-I, dll)
2. Specific criteria untuk setiap study design
3. Scoring system atau approach
4. How to handle mixed study designs
```

### **Langkah 2: Individual Study Quality Assessment**
**Prompt untuk Gen AI:**
```
Bantu assess quality study berikut menggunakan [tool name]:

STUDY: [citation dan key details]
QUALITY TOOL: [specific criteria]

Tolong evaluate:
1. Setiap criterion dalam tool
2. Supporting evidence dari study
3. Overall quality rating
4. Key strengths dan limitations
5. Impact pada overall review conclusions
```

### **Langkah 3: Overall Evidence Assessment**
**Prompt untuk Gen AI:**
```
Berdasarkan quality assessment semua studies:

STUDIES: [summary of all assessments]

Tolong synthesize:
1. Overall quality of evidence
2. Pattern of methodological strengths/weaknesses
3. Risk of bias assessment
4. Confidence dalam findings
5. Implications untuk conclusions
6. Recommendations untuk future research
```

---

## **MODUL 10: PENULISAN ARTIKEL DENGAN Gen AI**

### **Langkah 1: Abstract Writing**
**Prompt untuk Gen AI:**
```
Berdasarkan completed SLR, bantu tulis structured abstract:

REVIEW DETAILS:
- Research question: [question]
- Methods: [brief methodology]
- Results: [key findings]
- Conclusions: [main conclusions]

FORMAT ABSTRACT (150 words):
1. Background & Objective
2. Methods (search strategy, inclusion criteria, analysis)
3. Results (number of studies, key findings)
4. Conclusions (implications, recommendations)

Tulis draft abstract yang:
- Concise tapi comprehensive
- Follow journal requirements
- Highlight novelty dan significance
```

### **Langkah 2: Introduction Section**
**Prompt untuk Gen AI:**
```
Bantu tulis Introduction section dengan struktur:

1. BACKGROUND:
   - Context dan importance of topic
   - Current state of knowledge
   - Existing reviews dan gaps

2. RATIONALE:
   - Why this review needed
   - What new insights expected

3. OBJECTIVES:
   - Primary dan secondary objectives
   - Specific research questions

INPUT DATA:
- Research area: [area]
- Key background studies: [studies]
- Identified gaps: [gaps]
- Review objectives: [objectives]

Tulis introduction yang engaging dan well-referenced.
```

### **Langkah 3: Methods Section**
**Prompt untuk Gen AI:**
```
Bantu tulis Methods section yang PRISMA-compliant:

METHODOLOGY DETAILS:
- Search strategy: [strategy]
- Databases: Scopus
- Inclusion/exclusion criteria: [criteria]
- Screening process: [process]
- Data extraction: [extraction method]
- Quality assessment: [assessment tools]
- Analysis approach: [analysis]

Sections needed:
1. Protocol registration (jika ada)
2. Search strategy
3. Study selection
4. Data extraction
5. Quality assessment
6. Data synthesis

Pastikan transparency dan reproducibility.
```

### **Langkah 4: Results Section**
**Prompt untuk Gen AI:**
```
Bantu organize dan present results:

RESULTS DATA:
- Search results: [numbers]
- Included studies: [final number]
- Study characteristics: [summary]
- Key findings: [findings]
- Quality assessment: [quality summary]

Structure:
1. Search results (dengan PRISMA flow diagram description)
2. Study characteristics table description
3. Main findings by research question
4. Quality assessment summary
5. Subgroup analyses (jika ada)

Present results objectively tanpa interpretation.
```

### **Langkah 5: Discussion Section**
**Prompt untuk Gen AI:**
```
Bantu develop comprehensive Discussion:

REVIEW FINDINGS: [summary results]
RESEARCH QUESTIONS: [original questions]

Structure Discussion:
1. SUMMARY OF FINDINGS:
   - Key results interpretation
   - Answer to research questions

2. COMPARISON WITH EXISTING LITERATURE:
   - How findings relate to previous reviews
   - Confirmation atau contradiction

3. IMPLICATIONS:
   - Clinical/practical implications
   - Policy implications
   - Research implications

4. LIMITATIONS:
   - Study limitations
   - Review limitations
   - Potential biases

5. FUTURE RESEARCH:
   - Identified gaps
   - Research recommendations

Maintain balanced perspective dengan critical analysis.
```

### **Langkah 6: Tables dan Figures dengan Gen AI**
**Prompt untuk Gen AI:**
```
Bantu create comprehensive tables dan figures:

1. PRISMA FLOW DIAGRAM:
   - Database search results: [numbers]
   - Screening results: [numbers]
   - Full-text assessment: [numbers]
   - Final included studies: [number]
   - Exclusion reasons: [reasons dengan numbers]

2. STUDY CHARACTERISTICS TABLE:
   - Columns: Author/Year, Country, Design, Sample, Intervention, Outcomes
   - Data: [study data]

3. RESULTS SUMMARY TABLE:
   - Key findings organized by themes
   - Quality ratings
   - Effect sizes (jika applicable)

Format tables untuk journal submission requirements.
```

---

## **MODUL 11: FINALISASI DAN SUBMISSION**

### **Langkah 1: Manuscript Review dengan Gen AI**
**Prompt untuk Gen AI:**
```
Tolong review complete manuscript untuk:

1. CONTENT REVIEW:
   - Logical flow antar sections
   - Consistency dalam terminology
   - Completeness of information
   - Adherence to PRISMA guidelines

2. LANGUAGE REVIEW:
   - Grammar dan syntax
   - Academic writing style
   - Clarity dan conciseness
   - Consistency dalam tenses

3. TECHNICAL REVIEW:
   - Reference formatting
   - Table dan figure quality
   - Word count compliance
   - Journal requirement adherence

Berikan specific suggestions untuk improvement.
```

### **Langkah 2: Cover Letter Writing**
**Prompt untuk Gen AI:**
```
Bantu tulis cover letter untuk journal submission:

MANUSCRIPT DETAILS:
- Title: [title]
- Journal target: [journal name]
- Key findings: [findings]
- Novelty: [what's new]
- Significance: [importance]

COVER LETTER STRUCTURE:
1. Introduction dan manuscript submission
2. Brief study overview
3. Key contributions dan novelty
4. Relevance to journal scope
5. Confirmation of ethical requirements
6. Declaration of conflicts

Tone: Professional, confident, persuasive tapi tidak overselling.
```

### **Langkah 3: Response to Reviewers Preparation**
**Prompt untuk Gen AI:**
```
Bantu prepare untuk potential reviewer comments:

1. COMMON SLR REVIEW ISSUES:
   - Methodology concerns
   - Search strategy questions
   - Inclusion criteria clarity
   - Data extraction accuracy
   - Quality assessment rigor

2. RESPONSE STRATEGIES:
   - How to address methodology critiques
   - Providing additional evidence
   - Clarifying procedures
   - Acknowledging limitations gracefully

3. REVISION PLANNING:
   - Potential areas for improvement
   - Additional analyses yang mungkin needed
   - Supplementary materials preparation

Prepare responses yang constructive dan evidence-based.
```

---

