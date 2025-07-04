# Modul 4: Data Mining dan Export Scopus

---

## **LANGKAH 1: EKSEKUSI FINAL SEARCH DI SCOPUS**

### **Praktik di Scopus:**
1. **Login ke Scopus** dan masuk ke Advanced Search
2. **Input final search string** dari Modul 3
3. **Apply filters** yang sudah ditentukan:
   - Document type: Article, Review
   - Language: [sesuai kebutuhan]
   - Publication year: [range yang ditentukan]
4. **Catat total results** dan screenshot untuk dokumentasi

### **Evaluasi Final dengan Claude:**
```
Final search results di Scopus:
- Search string: [search string final]
- Total results: [jumlah hasil]
- Filters applied: [list filters]

Tolong confirm:
1. Apakah jumlah results ini optimal untuk SLR?
2. Apakah perlu supplementary search dari database lain?
3. Recommendation untuk export process
4. Expected screening workload berdasarkan jumlah ini

Berikan go/no-go decision untuk proceed ke export.
```

**Peserta mendapat confirmation** sebelum lanjut ke export process.

---

## **LANGKAH 2: EXPORT DATA DARI SCOPUS**

### **Export Process:**
1. **Select All** hasil pencarian
2. **Export** dengan format **CSV** 
3. **Pilih fields** yang diperlukan (minimal untuk Claude processing):
   - Authors
   - Title
   - Year
   - Abstract
   - Author Keywords
   - Index Keywords

### **Verifikasi Export dengan Claude:**
```
Saya telah export data Scopus dengan hasil:
- Total exported records: [jumlah]
- File format: CSV
- File size: [ukuran file]
- Fields included: Authors, Title, Year, Abstract, Author Keywords, Index Keywords

Tolong bantu:
1. Verify apakah essential fields untuk screening sudah complete
2. Identify potential data quality issues (missing abstracts, keywords)
3. Recommend data cleaning steps untuk Claude processing
4. Suggest database structure untuk screening
5. Prepare untuk tahap screening selanjutnya

Focus pada data yang dapat diproses Claude untuk screening assistance.
```

**Peserta mendapat guidance** untuk organize data sebelum screening.

---

## **LANGKAH 3: ORGANIZE DATA DAN SETUP SCREENING DATABASE**

### **Data Organization dengan Claude:**
```
Saya sudah memiliki CSV file dari Scopus export. 
Tolong bantu saya:

1. DATA CLEANING RECOMMENDATIONS:
   - Duplicate detection strategy
   - Missing data handling
   - Format standardization

2. SCREENING DATABASE SETUP:
   - Additional columns needed untuk screening
   - Tracking system untuk progress
   - Quality control measures

3. WORKFLOW PREPARATION:
   - Screening process organization
   - File backup strategy
   - Progress monitoring system

4. PRELIMINARY ANALYSIS:
   - Publication year distribution
   - Top journals represented
   - Document type breakdown

Berikan step-by-step instructions untuk setup.
```

**Peserta setup screening database** berdasarkan guidance Claude.

---

## **HASIL AKHIR**

### **Complete Data Mining Package:**
```
=== SCOPUS DATA MINING RESULTS ===

SEARCH EXECUTED:
- Search string: [final search string]
- Database: Scopus
- Date executed: [date]
- Total results: [number]
- Filters applied: [list filters]

EXPORT DETAILS:
- Format: CSV
- Records exported: [number]
- Essential fields: Authors, Title, Year, Abstract, Author Keywords, Index Keywords
- File size: [size]
- File location: [path]

DATA QUALITY:
- Duplicates detected: [number]
- Missing abstracts: [number]
- Missing keywords: [number]
- Data optimized for Claude processing: ✓ Ready

SCREENING SETUP:
- Database structure: ✓ Ready
- Tracking system: ✓ Implemented
- Backup strategy: ✓ Configured
- Progress monitoring: ✓ Active

PRELIMINARY STATISTICS:
- Publication years: [range]
- Top 5 journals: [list]
- Document types: [breakdown]
- Most cited article: [citation]

NEXT STEP: Begin title/abstract screening
ESTIMATED SCREENING TIME: [estimate]
```

---

## **TROUBLESHOOTING**

**Problem 1: Export limit exceeded (>2000 records)**
- Export in batches
- Use multiple CSV files
- Combine files systematically

**Problem 2: Missing essential fields**
- Re-export with correct field selection
- Check field availability in Scopus
- Use alternative field names

**Problem 3: CSV file corrupted**
- Try different export format (RIS, BibTeX)
- Check file encoding (UTF-8)
- Re-export with smaller batches

**Problem 4: Duplicate records**
- Use DOI untuk deduplication
- Check title similarity
- Manual verification untuk uncertain cases

**Problem 5: Access issues**
- Verify institutional access
- Check VPN connection
- Contact library untuk support

---

## **DELIVERABLES**

Setiap peserta menghasilkan:
1. **Clean CSV dataset** dari Scopus export
2. **Organized screening database** dengan proper structure
3. **Backup files** dan documentation
4. **Preliminary data analysis** summary
5. **Ready-to-screen dataset** untuk Modul 5