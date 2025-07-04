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

---

## **MODUL 7: DATA EXTRACTION DAN DATABASE BUILDING**

### **Langkah 1: Setup Data Extraction Database**
**Create Comprehensive Database Structure:**
```
Database columns yang diperlukan:
- Study_ID (unique identifier)
- Citation (full citation)
- DOI
- Study_Design
- Sample_Size
- Population_Characteristics
- Intervention/Exposure
- Comparison_Group
- Outcomes_Measured
- Key_Findings
- Quality_Score
- Extraction_Date
- Extractor_Name
- Notes/Comments
```

**Prompt untuk Gen AI untuk database setup:**
```
Berdasarkan research questions dan included studies, bantu design optimal data extraction database:

RESEARCH QUESTIONS: [questions]
STUDY TYPES: [types of studies included]
KEY VARIABLES: [variables of interest]

Tolong suggest:
1. Complete column structure dengan data types
2. Coding schemes untuk categorical variables
3. Standardized formats untuk continuous variables
4. Quality control measures
5. Backup dan version control strategies
```

### **Langkah 2: Systematic Data Extraction Process**
**Per study extraction dengan Gen AI:**
```
STUDY FOR EXTRACTION:
Citation: [full citation]
DOI: [DOI]
PDF attached: [yes/no]

EXTRACTION FRAMEWORK:
[paste extraction form fields]

Tolong extract semua relevant data dan organize dalam format:
Field_Name: Extracted_Data [Page_Number] "Direct_Quote_If_Needed"

Special attention to:
1. Sample demographics
2. Methodology details
3. Statistical results
4. Effect sizes
5. Confidence intervals
6. P-values
7. Author conclusions
8. Study limitations mentioned
```

### **Langkah 3: Data Quality Control**
**Gen AI-assisted quality checks:**
```
Saya telah extract data dari [number] studies. 
Tolong help dengan quality control:

EXTRACTED DATABASE: [summary of extracted data]

Quality checks needed:
1. Completeness check - identify missing data patterns
2. Consistency check - flag inconsistent formats
3. Logic check - identify contradictory entries
4. Outlier detection - unusual values yang perlu verification
5. Duplicate check - potential duplicate data entries

Provide specific recommendations untuk data cleaning.
```

### **Langkah 4: Data Validation dan Verification**
**Double extraction validation:**
```
Untuk high-priority studies, tolong bantu validate extraction:

ORIGINAL EXTRACTION: [data]
VERIFICATION EXTRACTION: [second extraction]

Compare dan identify:
1. Exact matches
2. Minor discrepancies (dapat diselesaikan)
3. Major discrepancies (require discussion)
4. Missing data dalam salah satu extraction
5. Recommendation untuk final data entry
```

---

## **MODUL 8: DATA ANALYSIS DAN SYNTHESIS DENGAN Gen AI**

### **Langkah 1: Pengembangan Data Extraction Form**
**Prompt untuk Gen AI:**
```
Berdasarkan research question dan included studies, bantu design data extraction form:

KATEGORI DATA:
1. Study characteristics (author, year, country, etc.)
2. Methodology (design, sample size, etc.) 
3. Population characteristics
4. Intervention/exposure details
5. Outcome measurements
6. Results (quantitative dan qualitative)
7. Quality indicators
8. Conflicts of interest

Untuk setiap kategori, berikan:
- Specific fields yang perlu extracted
- Format untuk data entry
- Coding schemes jika applicable
```

### **Langkah 2: Ekstraksi Data Individual Studies**
**Prompt untuk Gen AI:**
```
Bantu extract data dari study berikut menggunakan form yang sudah developed:

STUDY: [full citation dan abstract/full text]
EXTRACTION FORM: [form fields]

Tolong extract:
1. Semua relevant information sesuai form
2. Direct quotes untuk key findings
3. Numerical data dalam format yang consistent
4. Note any missing information
5. Highlight any concerns tentang study quality
```

### **Langkah 3: Synthesis dan Coding dengan Gen AI**
**Prompt untuk Gen AI:**
```
Berdasarkan extracted data dari [jumlah] studies, bantu:

1. THEMATIC CODING:
   - Identify recurring themes
   - Group similar findings
   - Develop coding framework

2. PATTERN ANALYSIS:
   - Similarities across studies
   - Differences dan contradictions
   - Gaps dalam evidence

3. PRELIMINARY SYNTHESIS:
   - Key findings summary
   - Evidence strength assessment
   - Areas needing further investigation
```

### **Langkah 1: Descriptive Analysis dengan Gen AI**
**Analyze extracted database:**
```
Berdasarkan complete extracted database dengan [number] studies:

DATABASE OVERVIEW:
- Study designs: [distribution]
- Publication years: [range]
- Sample sizes: [range]
- Geographic distribution: [countries]
- Key outcomes: [list]

Tolong provide comprehensive descriptive analysis:
1. Study characteristics summary table
2. Population demographics aggregate
3. Methodological quality distribution
4. Outcome measurement approaches
5. Publication trends over time
6. Geographic and institutional patterns
7. Funding source analysis
8. Potential publication bias indicators
```

### **Langkah 2: Thematic Analysis dengan Gen AI**
**Develop comprehensive themes:**
```
Based on extracted findings dari [number] studies:

RAW FINDINGS: [summary of all key findings]

Tolong conduct systematic thematic analysis:
1. INITIAL CODING:
   - Identify recurring concepts
   - Group similar findings
   - Note contradictory results

2. THEME DEVELOPMENT:
   - Major themes (3-5 primary themes)
   - Sub-themes untuk each major theme
   - Supporting evidence untuk each theme
   - Frequency of theme occurrence

3. THEME RELATIONSHIPS:
   - How themes interconnect
   - Hierarchical theme structure
   - Contradictions atau tensions between themes

4. EVIDENCE SYNTHESIS:
   - Strength of evidence untuk each theme
   - Quality of supporting studies
   - Gaps atau weak evidence areas
```

### **Langkah 3: Quantitative Synthesis (jika applicable)**
**Statistical analysis dengan Gen AI:**
```
Untuk quantitative data yang dapat di-pool:

QUANTITATIVE RESULTS:
Study 1: [outcome measure, effect size, CI, sample size]
Study 2: [outcome measure, effect size, CI, sample size]
[continue for all studies dengan comparable outcomes]

Tolong assess:
1. HOMOGENEITY:
   - Clinical homogeneity assessment
   - Methodological similarity
   - Statistical heterogeneity indicators

2. META-ANALYSIS FEASIBILITY:
   - Sufficient number of studies
   - Comparable outcome measures
   - Available effect size data
   - Quality of included studies

3. SUBGROUP ANALYSIS POTENTIAL:
   - Meaningful subgroups
   - Sufficient studies per subgroup
   - Clinical relevance of subgroups

4. SENSITIVITY ANALYSIS PLANNING:
   - High vs low quality studies
   - Different study designs
   - Publication bias assessment
```

### **Langkah 4: Evidence Grading dengan Gen AI**
**GRADE atau similar approach:**
```
Untuk each main outcome:

OUTCOME: [specific outcome]
STUDIES: [studies yang measure this outcome]
FINDINGS: [summary of findings]

Tolong apply evidence grading:
1. RISK OF BIAS:
   - Individual study limitations
   - Overall risk across studies

2. CONSISTENCY:
   - Similarity of results
   - Explanation untuk heterogeneity

3. DIRECTNESS:
   - Population applicability
   - Intervention relevance
   - Outcome directness

4. PRECISION:
   - Confidence interval width
   - Sample size adequacy

5. PUBLICATION BIAS:
   - Funnel plot assessment (if applicable)
   - Small study effects

FINAL GRADE: High/Moderate/Low/Very Low
RATIONALE: [detailed explanation]
```

---

## **MODUL 9: CRITICAL APPRAISAL DENGAN Gen AI**

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

