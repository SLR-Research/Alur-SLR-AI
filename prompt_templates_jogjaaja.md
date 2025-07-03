# Enhanced Prompt Templates untuk Form PAPERCAMP SLNA Yogyakarta

## **BAGIAN 1: TAHAP IDENTIFICATION - SEARCH STRATEGY**

### **Enhanced Prompt untuk Paragraf Identification (Bagian 1)**

```
Saya sedang menulis artikel Systematic Literature Review dengan topik [TOPIK ANDA]. 
Berdasarkan data search strategy berikut:

TEMA RISET: [tema riset dari form]
KATA KUNCI: [kata kunci yang digunakan]
DATABASE: [database yang digunakan]
TOTAL ARTIKEL: [jumlah total artikel awal]
RENTANG TAHUN: [rentang tahun]
TANGGAL PENCARIAN: [tanggal pencarian]

Tolong tulis PARAGRAF PERTAMA untuk bagian Methods - Identification yang:
1. Menjelaskan pemilihan kata kunci dengan justifikasi ilmiah (100-150 kata)
2. Menggunakan style academic writing yang engaging
3. Menjelaskan kombinasi Boolean operators dan rationale
4. Menyebutkan mengapa kata kunci tersebut dipilih untuk memastikan pencarian komprehensif
5. Include statement tentang balance antara specificity dan inclusivity
6. Format untuk jurnal bereputasi internasional

Berikan output yang dapat langsung digunakan untuk artikel, dengan proper academic tone.
```

### **Enhanced Prompt untuk Paragraf Identification (Bagian 2)**

```
Lanjutkan dengan PARAGRAF KEDUA untuk bagian Methods - Identification berdasarkan data:

DATABASE YANG DIGUNAKAN: [list database dari form]
KRITERIA PEMBATASAN:
- Tahun publikasi: [rentang tahun]
- Jenis dokumen: [article/proceedings/review]
- Bahasa: [bahasa]
- Artikel yang diluar scope: [jumlah]
- Setelah duplikasi dihapus: [jumlah final]

Tulis paragraf yang:
1. Menjelaskan rationale pemilihan database (100-150 kata)
2. Justifikasi kriteria inklusi awal (tahun, bahasa, jenis dokumen)
3. Jelaskan proses deduplication dan screening awal
4. Sertakan alasan mengapa database tertentu dipilih untuk memastikan coverage yang komprehensif
5. Mention quality assurance measures
6. End dengan hasil numerik yang clear

Format harus sesuai standar PRISMA dan dapat dipublikasi di jurnal Q1.
```

---

## **BAGIAN 2: TAHAP SCREENING - ENHANCED CRITERIA DEVELOPMENT**

### **Enhanced Prompt untuk Inclusion Criteria Development**

```
Berdasarkan framework PICO dan research question saya, bantu develop INCLUSION CRITERIA yang comprehensive:

PICO FRAMEWORK:
P (Population): [dari form]
I (Intervention/Interest): [dari form] 
C (Comparison): [dari form]
O (Outcome): [dari form]

PRIMARY RESEARCH QUESTION: [dari form]
TOPIK PENELITIAN: [tema riset dari form]

Develop DETAILED INCLUSION CRITERIA dengan format:

1. STUDY DESIGN CRITERIA:
   - Specific study designs yang diterima
   - Minimum methodological quality requirements
   - Peer-review publication requirements

2. POPULATION/CONTEXT CRITERIA:
   - Target population characteristics
   - Geographic scope (jika relevant)
   - Organizational/institutional settings
   - Sample size considerations

3. INTERVENTION/PHENOMENON CRITERIA:
   - Operational definitions yang specific
   - Duration/timeframe requirements
   - Implementation contexts
   - Variation yang acceptable

4. OUTCOME CRITERIA:
   - Primary outcomes yang wajib reported
   - Measurement approaches yang diterima
   - Data availability requirements
   - Quantitative vs qualitative data

5. PUBLICATION CRITERIA:
   - Language restrictions dengan justifikasi
   - Publication timeframe dengan rationale
   - Publication types (exclude grey literature atau tidak)
   - Accessibility requirements

Untuk setiap kriteria:
- Berikan justifikasi mengapa penting untuk research question
- Jelaskan bagaimana criteria ini mendukung validity of findings
- Ensure criteria specific, measurable, dan unambiguous
- Check alignment dengan PICO framework

Output format harus ready untuk inclusion dalam Methods section artikel.
```

### **Enhanced Prompt untuk Exclusion Criteria Development**

```
Berdasarkan inclusion criteria yang telah dibuat, develop COMPREHENSIVE EXCLUSION CRITERIA:

INCLUSION CRITERIA: [hasil dari prompt sebelumnya]
RESEARCH CONTEXT: [topik dan scope dari form]

Develop DETAILED EXCLUSION CRITERIA dengan structure:

1. METHODOLOGICAL EXCLUSIONS:
   - Study designs yang tidak sesuai dengan specific rationale
   - Quality issues yang tidak dapat diterima
   - Insufficient methodological detail
   - Data collection approaches yang tidak reliable

2. SCOPE EXCLUSIONS:
   - Population yang diluar target dengan clear boundaries
   - Interventions/phenomena yang terlalu different
   - Outcomes yang tidak directly relevant
   - Contexts yang tidak applicable

3. PUBLICATION EXCLUSIONS:
   - Editorial, commentary, opinion pieces
   - Conference abstracts without full papers
   - Duplicate publications atau overlapping datasets
   - Non-peer reviewed materials

4. DATA QUALITY EXCLUSIONS:
   - Incomplete data reporting
   - Insufficient sample sizes
   - Missing critical information
   - Conflicts of interest yang significant

5. LANGUAGE & ACCESSIBILITY EXCLUSIONS:
   - Non-English publications (dengan justifikasi)
   - Full-text tidak accessible
   - Behind paywalls tanpa institutional access
   - Retracted or corrected publications

Untuk setiap exclusion:
- Provide clear rationale
- Ensure no overlap dengan inclusion criteria
- Make criteria operationally specific
- Include examples jika membantu clarity

Format untuk Methods section yang PRISMA-compliant.
```

### **Enhanced Prompt untuk Screening Results Paragraph**

```
Berdasarkan hasil screening saya, tulis comprehensive paragraph untuk Methods section:

SCREENING STATISTICS:
- Total articles dari search: [dari form]
- Included for full-text: [jumlah]
- Excluded: [jumlah]

EXCLUSION BREAKDOWN:
- [Reason 1]: [jumlah] articles
- [Reason 2]: [jumlah] articles
- [dst sesuai hasil screening]

INCLUSION/EXCLUSION CRITERIA USED:
[paste criteria yang sudah developed]

Tulis 2 paragraf yang:

PARAGRAPH 1 (150-200 kata):
- Explain screening process systematically
- Reference ke Table yang menunjukkan inclusion/exclusion criteria
- Describe two-stage screening (title/abstract → full-text)
- Mention reviewer involvement dan quality assurance
- Include inter-rater reliability measures jika applicable

PARAGRAPH 2 (150-200 kata):
- Present numerical results dengan PRISMA flow reference
- Break down exclusion reasons dengan percentages
- Explain rationale untuk major exclusion categories
- Discuss any borderline cases dan resolution process
- End dengan final number untuk next stage

Style requirements:
- Academic tone suitable untuk top-tier journal
- PRISMA guideline compliance
- Clear and transparent reporting
- Use past tense consistently
- Include appropriate hedging language

Output harus ready untuk direct inclusion dalam manuscript.
```

---

## **BAGIAN 3: TAHAP ELIGIBILITY - ENHANCED QUALITY ASSESSMENT**

### **Enhanced Prompt untuk Eligibility Assessment Framework**

```
Saya perlu develop comprehensive framework untuk full-text eligibility assessment. Bantu create detailed approach:

RESEARCH CONTEXT:
- Topic: [topik dari form]
- Study types included: [dari screening results]
- Primary outcomes of interest: [dari PICO]

CREATE ELIGIBILITY ASSESSMENT FRAMEWORK:

1. METHODOLOGICAL QUALITY CRITERIA:
   - For [study design 1]: specific quality indicators
   - For [study design 2]: appropriate assessment tools
   - Minimum quality thresholds untuk each design
   - Red flags yang automatically exclude

2. RELEVANCE ASSESSMENT CRITERIA:
   - Alignment dengan research questions (1-5 scale)
   - Depth of relevant information
   - Quality of outcome reporting
   - Applicability to synthesis objectives

3. DATA ADEQUACY CRITERIA:
   - Sufficient detail untuk data extraction
   - Clear methodology description
   - Adequate sample/data reporting
   - Statistical/analytical rigor

4. MULTI-REVIEWER PROCESS:
   - Independent assessment procedures
   - Conflict resolution protocols
   - Consensus building approaches
   - Documentation requirements

Create assessment form/checklist dengan:
- Binary yes/no decisions untuk each criterion
- Scoring rubrics untuk quality assessment
- Clear decision rules untuk borderline cases
- Documentation template untuk rationales

Output harus operationally specific dan dapat digunakan langsung untuk assessment process.
```

### **Enhanced Prompt untuk Eligibility Results Paragraph**

```
Berdasarkan hasil full-text eligibility assessment, tulis Methods section paragraph:

ELIGIBILITY STATISTICS:
- Articles assessed for eligibility: [jumlah]
- Articles included in final synthesis: [jumlah]
- Articles excluded after full-text review: [jumlah]

EXCLUSION REASONS (FULL-TEXT):
- [Reason 1]: [jumlah] articles  
- [Reason 2]: [jumlah] articles
- [dst]

QUALITY ASSESSMENT DETAILS:
- Assessment tools used: [tools]
- Reviewer process: [single/double/triple reviewer]
- Inter-rater reliability: [hasil jika ada]

Tulis comprehensive paragraph (200-250 kata) yang:

1. PROCESS DESCRIPTION:
   - Explain systematic full-text review process
   - Detail quality assessment procedures
   - Describe reviewer training dan calibration
   - Mention conflict resolution process

2. RESULTS PRESENTATION:
   - Present exclusion numbers dengan clear rationale
   - Explain most common exclusion reasons
   - Discuss quality distribution of included studies
   - Reference ke quality assessment table

3. QUALITY ASSURANCE:
   - Detail inter-rater reliability results
   - Explain consensus building process
   - Mention any quality scoring outcomes
   - Discuss implications untuk synthesis

Requirements:
- PRISMA-compliant reporting
- Transparent dan reproducible description
- Appropriate academic language
- Past tense throughout
- Ready for Q1 journal submission

Include reference ke "Table X shows detailed quality assessment results" dan "Figure X presents PRISMA flow diagram."
```

---

## **BAGIAN 4: RESEARCH QUESTION DEVELOPMENT - ENHANCED AI WORKFLOW**

### **Enhanced Prompt untuk RQ Development dari Scopus Data**

```
Saya telah mengumpulkan dataset artikel dari Scopus untuk systematic literature review. Berperan sebagai senior researcher expert di bidang [BIDANG SPESIFIK], analisis dataset dan develop research questions.

DATASET CHARACTERISTICS:
- Total articles: [jumlah dari export]
- Time range: [rentang tahun]
- Database: Scopus
- Search terms used: [kata kunci yang digunakan]
- Document types: [article/review/conference paper]

CONTEXT & REQUIREMENTS:
- Target publication: Q1 international journal
- Methodology: Systematic Literature Review dengan possible bibliometric analysis
- Novelty requirement: Must fill existing research gap
- Practical relevance: Should inform [policy/practice/theory]

COMPREHENSIVE ANALYSIS REQUEST:

1. DATASET OVERVIEW:
   - Analyze publication trends by year
   - Identify dominant journals and authors
   - Map geographic distribution of research
   - Identify emerging vs established research areas

2. CONTENT ANALYSIS:
   - Extract recurring themes from abstracts
   - Identify methodological approaches used
   - Map theoretical frameworks applied
   - Spot under-researched aspects

3. GAP IDENTIFICATION:
   - Compare dengan existing systematic reviews
   - Identify methodological gaps
   - Spot geographical/contextual gaps
   - Find theoretical or practical gaps

4. RQ DEVELOPMENT:
   Generate 5-7 RESEARCH QUESTIONS yang:
   - Specific dan answerable dari available literature
   - Novel dan belum extensively reviewed
   - Practically relevant untuk stakeholders
   - Suitable untuk systematic synthesis
   - Can generate actionable insights

Untuk setiap RQ provide:
- Rationale mengapa important
- Expected contribution to knowledge
- Alignment dengan available data
- Potential impact pada field

Format output untuk direct integration ke research proposal.
```

### **Enhanced Prompt untuk Data Extraction Framework Development**

```
Berdasarkan finalized research questions, develop comprehensive data extraction framework:

FINALIZED RESEARCH QUESTIONS:
1. [RQ1 dari hasil sebelumnya]
2. [RQ2 dari hasil sebelumnya]
3. [RQ3 dari hasil sebelumnya]
[dst]

INCLUDED STUDIES CHARACTERISTICS:
- Total studies: [jumlah final included]
- Study designs: [mix of designs]
- Geographic distribution: [countries/regions]
- Timeframe: [publication years]

CREATE COMPREHENSIVE DATA EXTRACTION FRAMEWORK:

1. BIBLIOGRAPHIC DATA:
   - Citation details (standardized format)
   - Journal impact factor category
   - Author affiliations dan countries
   - Publication year dan citation count

2. STUDY CHARACTERISTICS:
   - Research design dan methodology
   - Sample/population details
   - Data collection methods
   - Analysis approaches used

3. RQ-SPECIFIC DATA EXTRACTION:
   For each research question, specify:
   - Exact variables to extract
   - Coding schemes (categorical variables)
   - Measurement approaches
   - Quality indicators

4. OUTCOME DATA:
   - Primary findings relevant to each RQ
   - Effect sizes (jika quantitative)
   - Qualitative themes atau patterns
   - Conclusions dan implications

5. QUALITY/BIAS ASSESSMENT:
   - Study quality indicators
   - Potential bias sources
   - Methodological limitations
   - Generalizability assessments

Create extraction template dengan:
- Clear field definitions
- Standardized response options
- Quality control measures
- Inter-rater reliability procedures

Output harus operational dan ready untuk systematic data extraction process.
```

---

## **BAGIAN 5: TECHNICAL WRITING - ENHANCED AI-ASSISTED WRITING**

### **Enhanced Prompt untuk Introduction Writing**

```
Tulis comprehensive Introduction section untuk systematic literature review artikel:

STUDY CONTEXT:
- Topic: [tema riset dari form]
- Research questions: [final RQ list]
- Number of studies reviewed: [included studies]
- Geographic scope: [dari analysis]
- Timeframe: [years covered]

TARGET JOURNAL: Q1 international journal in [field]
WORD LIMIT: 1200-1500 words (approximately 5 paragraphs)

WRITE COMPLETE INTRODUCTION dengan structure:

PARAGRAPH 1 - GLOBAL CONTEXT & URGENCY (250-300 words):
- Start with compelling global statistics atau trends
- Link to major global challenges (SDGs, climate change, digital transformation, etc.)
- Establish urgency dan importance of topic
- Use recent authoritative sources (last 3-5 years)
- Create reader engagement dari first sentence

PARAGRAPH 2 - CURRENT CHALLENGES & OPPORTUNITIES (250-300 words):
- Detail specific challenges dalam field
- Explain complexity of current approaches
- Highlight technological advances atau new opportunities
- Discuss implementation barriers
- Set stage untuk why review is needed

PARAGRAPH 3 - LITERATURE LANDSCAPE & GAPS (300-350 words):
- Acknowledge existing research achievements
- Identify what has been well-studied
- Clearly articulate gaps dalam current knowledge
- Reference key systematic reviews (jika ada) dan show differentiation
- Build case untuk novelty of current review

PARAGRAPH 4 - JUSTIFICATION & CONTRIBUTION (250-300 words):
- Explain why THIS review is needed NOW
- Articulate specific contributions to field
- Identify target beneficiaries (researchers, practitioners, policymakers)
- Link to practical applications
- Build excitement untuk findings

PARAGRAPH 5 - RESEARCH OBJECTIVES (150-200 words):
- Present clear research questions
- Explain review methodology briefly
- Outline structure of remaining artikel
- End dengan strong statement of expected impact

REQUIREMENTS:
- Academic tone suitable untuk top-tier journal
- Compelling narrative flow
- Strong literature integration (suggest 40-60 references)
- Clear novelty statement
- Engaging opening dan strong conclusion
- Perfect grammar dan academic style

Provide complete, publication-ready Introduction section.
```

### **Enhanced Prompt untuk Results Section Writing**

```
Tulis comprehensive Results section berdasarkan systematic review findings:

REVIEW CHARACTERISTICS:
- Total included studies: [jumlah]
- Research questions addressed: [list RQ]
- Geographic distribution: [countries/regions]
- Publication timeframe: [years]
- Study designs: [mix of designs]

DATA SYNTHESIS RESULTS:
[Provide key findings untuk each RQ dari data extraction]

WRITE COMPLETE RESULTS SECTION dengan structure:

SECTION 1 - STUDY CHARACTERISTICS (400-500 words):
- Overview of included studies dengan descriptive statistics
- Geographic dan temporal distribution
- Study design breakdown dengan rationale for inclusion
- Quality assessment summary
- Reference ke comprehensive characteristics table

SECTION 2 - FINDINGS BY RESEARCH QUESTION:

For each RQ (300-400 words per RQ):
- Clear sub-heading aligned dengan RQ
- Synthesis of findings across studies
- Quantitative summaries (frequencies, percentages)
- Identification of patterns dan trends
- Notable outliers atau contradictions
- Supporting evidence dari multiple studies

SECTION 3 - CROSS-CUTTING THEMES (300-400 words):
- Themes yang emerge across multiple RQ
- Methodological patterns
- Geographic atau temporal trends
- Quality considerations affecting findings

SECTION 4 - SYNTHESIS SUMMARY (200-300 words):
- High-level synthesis across all findings
- Strength of evidence for each major finding
- Areas of consensus vs controversy
- Preparation untuk Discussion section

WRITING REQUIREMENTS:
- Objective tone (save interpretation untuk Discussion)
- Clear section/subsection structure
- Appropriate use of tables dan figures references
- Smooth transitions between sections
- Consistent past tense
- No interpretation - pure results presentation
- Reference numbering untuk individual studies (A1, A2, etc.)

Include suggestions untuk:
- Table captions dan structure
- Figure types yang would enhance presentation
- Appendix materials yang might be needed

Provide publication-ready Results section dengan professional academic style.
```

### **Enhanced Prompt untuk Discussion & Conclusion Writing**

```
Tulis comprehensive Discussion dan Conclusion sections:

STUDY RESULTS SUMMARY:
[Provide key findings dari Results section]

RESEARCH QUESTIONS:
[List original RQ dan main findings for each]

LITERATURE CONTEXT:
- Existing systematic reviews dalam field: [jika ada]
- Major empirical studies: [key references]
- Theoretical frameworks: [relevant theories]

WRITE COMPLETE DISCUSSION SECTION (1500-2000 words):

SUBSECTION 1 - PRINCIPAL FINDINGS (400-500 words):
- Synthesize major findings across RQ
- Highlight most important contributions
- Connect findings to original objectives
- Avoid repeating Results verbatim

SUBSECTION 2 - COMPARISON WITH EXISTING LITERATURE (500-600 words):
- Compare dengan previous systematic reviews
- Contrast dengan major empirical studies
- Identify confirmatory vs contradictory findings
- Explain discrepancies dengan evidence-based reasoning
- Position findings dalam broader literature landscape

SUBSECTION 3 - IMPLICATIONS (400-500 words):
- Theoretical implications untuk field advancement
- Practical implications untuk practitioners
- Policy implications untuk decision-makers
- Methodological implications untuk future research
- Educational implications jika relevant

SUBSECTION 4 - LIMITATIONS (300-400 words):
- Study selection limitations
- Data extraction limitations
- Synthesis limitations
- Publication bias possibilities
- Generalizability concerns
- Database dan language restrictions

SUBSECTION 5 - FUTURE RESEARCH DIRECTIONS (300-400 words):
- Specific research gaps identified
- Methodological improvements needed
- Geographic atau contextual studies needed
- Longitudinal research opportunities
- Interdisciplinary collaboration needs

CONCLUSION SECTION (300-400 words):
- Restate study purpose dan methods briefly
- Summarize key findings dan their significance
- Emphasize practical dan theoretical contributions
- Call untuk action atau implementation
- End dengan strong impact statement

WRITING REQUIREMENTS:
- Analytical dan reflective tone
- Strong argumentation dengan evidence support
- Balanced assessment of strengths dan limitations
- Clear implications for multiple stakeholder groups
- Future-oriented perspective
- Professional academic style
- Logical flow dengan smooth transitions

Provide complete, publication-ready Discussion dan Conclusion sections.
```

---

## **BAGIAN 6: BIBLIOMETRIC ANALYSIS - ENHANCED WORKFLOW**

### **Enhanced Prompt untuk Bibliometric Analysis Interpretation**

```
Berdasarkan hasil analisis bibliometric menggunakan VOSviewer, bantu interpret findings untuk artikel:

BIBLIOMETRIC RESULTS DATA:
- Total publications analyzed: [jumlah]
- Time period: [tahun-tahun]
- Co-occurrence analysis results: [describe clusters/themes]
- Co-citation analysis results: [key cited works]
- Temporal trends: [publication trends by year]

RESEARCH QUESTIONS untuk BIBLIOMETRIC:
1. [RQ1 dari form - evolusi publikasi]
2. [RQ2 dari form - tren topik]  
3. [RQ3 dari form - dokumen berpengaruh]

WRITE COMPREHENSIVE INTERPRETATION:

SECTION 1 - PUBLICATION TRENDS ANALYSIS (300-400 words):
- Interpret temporal patterns dalam publication volume
- Identify growth phases atau decline periods
- Connect trends to external factors (policy changes, technological advances, etc.)
- Discuss implications of publication patterns
- Compare dengan global research trends in field

SECTION 2 - THEMATIC EVOLUTION ANALYSIS (400-500 words):
- Interpret co-occurrence clusters meaningfully
- Identify emerging vs declining themes
- Map thematic relationships dan interconnections
- Discuss evolution of research focus over time
- Connect themes to practical developments in field

SECTION 3 - INTELLECTUAL STRUCTURE ANALYSIS (400-500 words):
- Interpret co-citation networks dan citation patterns
- Identify foundational vs current influential works
- Map schools of thought atau methodological approaches
- Discuss knowledge diffusion patterns
- Identify research gaps from citation analysis

SECTION 4 - GEOGRAPHIC & INSTITUTIONAL PATTERNS (300-400 words):
- Analyze geographic distribution of research
- Identify leading countries dan institutions
- Discuss collaboration patterns
- Connect geographic patterns to local/regional needs
- Identify underrepresented regions

SECTION 5 - SYNTHESIS & IMPLICATIONS (300-400 words):
- Integrate bibliometric findings dengan content analysis
- Discuss what bibliometric patterns reveal about field maturity
- Identify future research directions dari pattern analysis
- Connect findings to practical field development
- Suggest strategies untuk field advancement

REQUIREMENTS:
- Connect quantitative patterns to qualitative insights
- Use academic language appropriate untuk Results/Discussion
- Include specific numbers dan percentages dari analysis
- Reference appropriate bibliometric methodology literature
- Prepare text untuk direct inclusion dalam manuscript
- Suggest appropriate figure captions untuk VOSviewer outputs

Provide analysis yang bridges quantitative bibliometric data dengan meaningful academic interpretation.
```

---

## **BAGIAN 7: QUALITY ASSURANCE - ENHANCED VALIDATION PROMPTS**

### **Enhanced Prompt untuk Overall Manuscript Review**

```
Conduct comprehensive quality review untuk systematic literature review manuscript:

MANUSCRIPT COMPONENTS:
- Introduction: [word count]
- Methods: [word count]  
- Results: [word count]
- Discussion: [word count]
- Abstract: [word count]
- References: [jumlah]

TARGET JOURNAL: [specific journal name dan requirements]
REVIEW TYPE: Systematic Literature Review

COMPREHENSIVE REVIEW CHECKLIST:

1. STRUCTURE & FLOW ANALYSIS:
   - Logical progression from Introduction to Conclusion
   - Smooth transitions between sections
   - Appropriate section lengths dan balance
   - Clear subsection organization

2. CONTENT QUALITY ASSESSMENT:
   - Research questions clearly stated dan addressed
   - Methods sufficiently detailed untuk replication
   - Results objectively presented without interpretation
   - Discussion appropriately interpretive dan balanced
   - Conclusion aligned dengan findings

3. PRISMA COMPLIANCE CHECK:
   - All required PRISMA elements included
   - Flow diagram accurately represents process
   - Search strategy sufficiently detailed
   - Selection criteria clearly defined
   - Data extraction process transparent

4. ACADEMIC WRITING QUALITY:
   - Appropriate academic tone throughout
   - Consistent tense usage
   - Precise dan clear language
   - Proper hedging dan tentative language
   - Professional presentation

5. METHODOLOGICAL RIGOR:
   - Systematic approach clearly documented
   - Bias minimization strategies employed
   - Quality assessment appropriately conducted
   - Synthesis methods suitable untuk data

6. NOVELTY & CONTRIBUTION:
   - Clear articulation of research gap
   - Novel insights atau approaches identified
   - Practical implications clearly stated
   - Theoretical contributions explained

7. TECHNICAL ACCURACY:
   - Reference formatting consistent
   - Statistical presentations accurate
   - Table dan figure integration appropriate
   - Citation accuracy dan completeness

PROVIDE DETAILED FEEDBACK:
- Strengths of manuscript
- Areas requiring improvement
- Specific suggestions untuk enhancement
- Compliance issues yang need attention
- Recommendations untuk journal submission readiness

Rate overall manuscript quality (1-10) dan provide specific action items untuk improvement.
```

Ini adalah enhanced prompt templates yang terintegrasi dengan form PAPERCAMP SLNA dan memberikan guidance yang lebih detail dan praktis untuk setiap tahap systematic literature review dengan AI assistance.