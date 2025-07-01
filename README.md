# Alur Pelatihan SLR dengan Gen AI untuk Artikel Jurnal Bereputasi - Panduan Spesifik

![Uploading slr_workflow.png…]()


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

### **Langkah 1: Brainstorming Topik dengan Gen AI**
**Prompt untuk Gen AI:**
```
Saya ingin melakukan systematic literature review di bidang [bidang penelitian]. 
Tolong bantu saya:
1. Identifikasi 5 topik penelitian yang trending dan relevan
2. Untuk setiap topik, berikan potential research gaps
3. Sertakan alasan mengapa topik ini penting untuk diteliti
4. Berikan referensi kunci untuk setiap topik (jika ada dalam knowledge base)
```

**Output yang diharapkan:**
- Daftar topik potensial dengan justifikasi
- Research gaps yang teridentifikasi
- Preliminary reading list

### **Langkah 2: Pengembangan PICO Framework dengan Gen AI**
**Prompt untuk Gen AI:**
```
Berdasarkan topik penelitian [topik terpilih], bantu saya mengembangkan PICO framework:

P (Population/Problem): [jelaskan konteks]
I (Intervention/Exposure): [jelaskan fokus]
C (Comparison): [jelaskan pembanding]
O (Outcome): [jelaskan hasil yang diukur]

Tolong:
1. Refine setiap komponen PICO agar lebih spesifik
2. Berikan alternatif formulasi untuk setiap komponen
3. Identifikasi potential confounding factors
4. Saran untuk membuat research question yang SMART
```

**Iterasi dengan Gen AI:**
- Diskusi setiap komponen PICO
- Refinement berdasarkan feedback
- Validasi dengan existing literature

### **Langkah 3: Finalisasi Research Question**
**Prompt untuk Gen AI:**
```
Berdasarkan PICO framework:
P: [final P]
I: [final I] 
C: [final C]
O: [final O]

Tolong formulasikan:
1. Primary research question
2. 2-3 secondary research questions
3. Null dan alternative hypothesis (jika applicable)
4. Evaluasi apakah research question sudah FINER (Feasible, Interesting, Novel, Ethical, Relevant)
```

---

## **MODUL 3: STRATEGI PENCARIAN SCOPUS DENGAN Gen AI**

### **Langkah 1: Pengembangan Keywords dengan Gen AI**
**Prompt untuk Gen AI:**
```
Berdasarkan research question: [research question]
Tolong bantu develop comprehensive keyword strategy:

1. Identifikasi main concepts dari research question
2. Untuk setiap concept, berikan:
   - Synonyms (sinonim)
   - Alternative spellings
   - Abbreviations
   - Related terms
   - Medical Subject Headings (MeSH) jika applicable
3. Kelompokkan keywords berdasarkan concept clusters
4. Berikan saran kombinasi Boolean operators (AND, OR, NOT)
```

**Gen AI akan membantu:**
- Identifikasi keywords utama dan alternatif
- Pengelompokan keywords by concepts
- Saran struktur Boolean search

### **Langkah 2: Konstruksi Search String untuk Scopus**
**Prompt untuk Gen AI:**
```
Berdasarkan keyword clusters:
Cluster 1: [keywords group 1]
Cluster 2: [keywords group 2]
Cluster 3: [keywords group 3]

Tolong konstruksi search string untuk Scopus dengan:
1. Proper Boolean operators (AND, OR, NOT)
2. Wildcard (*) untuk variations
3. Phrase searching dengan quotation marks
4. Field-specific searching (TITLE-ABS-KEY)
5. Date limitations jika diperlukan
6. Document type limitations
7. Language limitations

Format: TITLE-ABS-KEY((keyword1 OR keyword2) AND (keyword3 OR keyword4))
```

**Output yang diharapkan:**
- Search string yang ready untuk Scopus
- Alternative search strategies
- Explanation untuk setiap component

### **Langkah 3: Optimasi Search Strategy**
**Prompt untuk Gen AI:**
```
Evaluasi search string berikut: [search string]

Tolong analisis:
1. Apakah terlalu broad atau terlalu narrow?
2. Kemungkinan hasil yang akan didapat
3. Potential missing keywords
4. Saran untuk sensitivity vs precision balance
5. Alternative search approaches
6. Recommendation untuk pilot testing
```

---

## **MODUL 4: EKSEKUSI PENCARIAN DAN DATA MINING SCOPUS**

### **Langkah 1: Eksekusi Search di Scopus**
**Aktivitas Praktik:**
1. **Login ke Scopus** dan navigasi ke Advanced Search
2. **Input search string** yang telah dikembangkan dengan Gen AI
3. **Set filters:**
   - Document type (Article, Review, Conference Paper)
   - Publication year range
   - Language (English, Indonesian, dll)
   - Subject area (jika relevan)

**Prompt untuk Gen AI setelah mendapat hasil:**
```
Saya mendapat [jumlah] hasil dari Scopus dengan search string:
[search string yang digunakan]

Filters yang diaplikasikan:
- Document type: [types]
- Years: [range]
- Language: [languages]

Tolong analisis:
1. Apakah jumlah hasil ini reasonable untuk SLR?
2. Jika terlalu banyak (>5000), saran untuk narrow down
3. Jika terlalu sedikit (<50), saran untuk broaden search
4. Recommendation untuk additional filters
5. Perlu tidaknya supplementary searches
```

### **Langkah 2: Export Data dari Scopus**
**Prosedur Export:**
1. **Select All** hasil pencarian (atau pilih batch jika >2000)
2. **Export** dengan format:
   - **CSV format** untuk analisis dengan Gen AI
   - **RIS format** untuk reference manager
   - **BibTeX** jika diperlukan

**Fields yang harus di-export:**
- Authors
- Title
- Year
- Source title (Journal)
- Volume, Issue, Pages
- DOI
- Abstract
- Keywords
- Document Type
- Cited by count
- Affiliation

**Prompt untuk Gen AI setelah export:**
```
Saya telah export data Scopus dengan [jumlah] entries. 
File CSV berisi columns: [list column names]

Tolong bantu:
1. Verify apakah semua essential fields sudah ter-cover
2. Identify any data quality issues yang mungkin ada
3. Saran untuk data cleaning steps
4. Recommendation untuk organize data sebelum screening
```

### **Langkah 3: Data Import dan Organization**
**Menggunakan Gen AI untuk analisis CSV:**
```
Saya akan upload file CSV hasil export Scopus. 
Tolong bantu:

1. DATA OVERVIEW:
   - Total records
   - Date range publications
   - Top journals
   - Most cited articles
   - Document type distribution

2. PRELIMINARY ANALYSIS:
   - Duplicate detection based on title/DOI
   - Missing data identification (abstract, keywords, dll)
   - Publication trend by year
   - Geographic distribution (based on affiliation)

3. DATA PREPARATION:
   - Format standardization recommendations
   - Suggest additional columns needed for screening
   - Create unique identifier for each record
```

**Setup Screening Database:**
- **Create screening columns**: Include/Exclude, Reason, Reviewer, Date
- **Add tracking fields**: Stage (Title/Abstract, Full-text), Status
- **Backup original data** sebelum mulai screening

### **Langkah 4: Supplementary Search (jika diperlukan)**
**Prompt untuk Gen AI:**
```
Berdasarkan hasil Scopus search, apakah perlu supplementary searches?

CURRENT RESULTS:
- Total articles: [number]
- Date range: [range]
- Key journals covered: [list]
- Notable gaps: [gaps if any]

Tolong evaluate:
1. Perlu tidaknya search di database lain (PubMed, Web of Science)
2. Grey literature search requirements
3. Hand searching dari reference lists
4. Forward citation searching
5. Contact dengan experts untuk unpublished studies

Jika ya, berikan specific search strategies untuk each source.
```

---

## **MODUL 5: SCREENING DAN SELECTION DENGAN Gen AI**

### **Langkah 1: Pengembangan Inclusion/Exclusion Criteria**
**Prompt untuk Gen AI:**
```
Berdasarkan PICO framework dan research question, bantu develop:

INCLUSION CRITERIA:
1. Study design criteria
2. Population criteria  
3. Intervention/exposure criteria
4. Outcome criteria
5. Language criteria
6. Time period criteria
7. Publication type criteria

EXCLUSION CRITERIA:
1. Specific exclusions untuk setiap kategori
2. Rationale untuk setiap exclusion

Pastikan criteria:
- Specific dan measurable
- Tidak overlapping
- Aligned dengan research objective
```

### **Langkah 2: Batch Processing dengan Gen AI**
**Untuk screening banyak artikel sekaligus:**
```
Saya memiliki [jumlah] articles untuk title/abstract screening. 
Berikut data dalam format:

ID | Title | Abstract | Keywords
1 | [title 1] | [abstract 1] | [keywords 1]
2 | [title 2] | [abstract 2] | [keywords 2]
[dst, maksimal 10 articles per batch]

INCLUSION CRITERIA: [criteria list]
EXCLUSION CRITERIA: [criteria list]

Untuk setiap article, berikan:
- Decision (INCLUDE/EXCLUDE/UNCERTAIN)
- Primary reason
- Key factors yang influence decision
- Confidence level (High/Medium/Low)

Format output:
ID | Decision | Reason | Confidence
```

**Tracking Progress:**
- **Document decisions** dalam spreadsheet
- **Calculate inter-rater reliability** jika ada multiple reviewers
- **Flag uncertain cases** untuk diskusi tim

### **Langkah 3: Full-text Acquisition dan Management**
**Untuk artikel yang lolos screening:**
1. **Download full-text** dari institutional access
2. **Organize files** dengan naming convention: "ID_FirstAuthor_Year.pdf"
3. **Create full-text database** dengan linking ke original screening data

**Prompt untuk Gen AI setelah full-text review:**
```
Untuk artikel yang require full-text assessment:

ARTIKEL ID: [ID]
TITLE: [title]
AVAILABLE FULL-TEXT: Yes/No
REASON IF NOT AVAILABLE: [reason]

Jika full-text tidak available:
1. Alternative access strategies
2. Contact author procedures
3. Decision criteria untuk exclude due to unavailability
4. Impact assessment pada review comprehensiveness
```
**Prompt untuk Gen AI:**
```
Bantu saya screen artikel berdasarkan title dan abstract:

INCLUSION CRITERIA: [criteria list]
EXCLUSION CRITERIA: [criteria list]

ARTIKEL:
Title: [title]
Abstract: [abstract]

Tolong:
1. Evaluasi apakah artikel meet inclusion criteria
2. Identify any exclusion criteria yang applicable
3. Berikan reasoning untuk decision
4. Highlight key information yang support decision
5. Recommendation: INCLUDE / EXCLUDE / UNCERTAIN
```

**Catatan penting:**
- Lakukan untuk setiap artikel individually
- Dokumentasikan reasoning untuk audit trail
- Flag uncertain cases untuk diskusi

### **Langkah 3: Full-text Screening dengan Gen AI**
**Prompt untuk Gen AI:**
```
Untuk artikel yang lolos title/abstract screening, bantu full-text evaluation:

ARTIKEL: [artikel details]
INCLUSION/EXCLUSION CRITERIA: [detailed criteria]

Tolong analisis:
1. Study design assessment
2. Population characteristics match
3. Intervention/exposure details
4. Outcome measurements
5. Methodology quality indicators
6. Final recommendation dengan detailed justification
```

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

