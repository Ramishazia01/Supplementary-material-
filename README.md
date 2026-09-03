# Supplementary Evidence - Disaster Content Detection: A Systematic Review and Quantitative Synthesis of Datasets, Models, Evaluation Practices, Challenges, and Future Directions

This repository contains the complete supplementary evidence for our SLR on disaster content detection from social media (2015-2025). This file provides detailed steps of study selection for our systematic review.

**File:** `Disaster_survey_Final_supplementary_sheet.xlsx`

### Corpus Summary (Final Verified Counts)
- **Databases (5):** IEEE Xplore 47 + DBLP 120 + Google Scholar 195 + Scopus 145 + SpringerLink 75 = **582 retrieved**
- **Duplicates removed:** 262 (DOI + Title fuzzy matching)
- **Unique for screening:** 320
- **Excluded at Title/Abstract:** 79
- **Full-text assessed:** 241
- **Excluded at Full-text:** 28
- **Final included:** 213 = **172 Primary Studies + 22 Prior Review/Survey + 19 Background/Contextual**
- **Search execution:** 1-30 October 2025
- **Publication eligibility:** 1 January 2015 - 31 August 2025

### Sheet-wise Details (As per Final Excel)

**Sheet 01_Search_Log**
Exact name in Excel: `Search_Log_47_120_195_145_75`
Contains: Database/source, URL, Exact search string used/reproducible query (verbatim), Field restriction (TITLE-ABS-KEY, All Metadata, Title search), Total results found per database (716 total), Records retrieved (47,120,195,145,75=582), Search date, Duplicates removed, Publication/date restriction, Language, Filters/restrictions, Inclusion/Exclusion criteria, Negative terms (hazard prediction, susceptibility mapping, landslide prediction, flood forecasting, evacuation planning, etc.), Operator definition (+ = AND, * = wildcard, - = NOT). Also mirrored in Appendix A.

**Sheet 03_PRISMA**
Exact name in Excel: `PRISMA_582_320_241_213`
PRISMA 2020 flow: Initial retrieved 582, Duplicates removed 262, After deduplication 320, Excluded at Title/Abstract 79, Full-text assessed 241, Excluded at Full-text 28, Final included 213. Matches Figure 3.

**Sheet 03FullProcess_of paperselection**
Exact name in Excel: `Full process of paper selection`
Complete study-level list of 582 records. Key columns:
- `Duplicate(Yes/No)` - Deduplication proof: Yes=262 duplicates, No=320 unique
- `Screening Decision (Title/Abstract)` + `Screening Exclusion Reason` - 79 varied EC-coded reasons (not same text)
- `Full-Text Decision` + `Full-Text Exclusion Reason` - 28 varied EC-coded reasons
- `Final Status` - Included 213 / Excluded 369
- `Citation Category (Primary Study / Prior Review-Survey / Background-Contextual)` - Distinguishes 172 Primary (used for RQ analysis), 22 Survey, 19 Background
- `Reviewer/screener` - Rameesha Zia; Muhammad Shahid Iqbal Malik (independent double screening)
- `Disagreement resolution` - Consensus + senior adjudicator
- `Date of screening`, `Extraction status`
This sheet is the supplementary study-level list of all included papers requested by reviewer.

**Sheet 07_Extraction_Rules_Coding_Rule**
Exact name in Excel: `Extraction_Rules`
Defines: Study ID, Reference, Dataset, Disaster/event, Task, Model, Modality, Language, Size/class distribution, Train/test split, Metric, Numerical result, Evaluation setting, Comparability note, Annotation method, Labels, Reproducibility. Includes coding rule for Figure 6: Each distinct architecture evaluated within a study is counted as one model-use instance. Also defines Scope Boundary and EC4 objective test (disaster content detection as primary outcome vs adjacent tasks like satellite/UAV-only, hazard prediction, susceptibility mapping, logistics).

**Sheet 05_Quality_Risk_of_Bias**
Exact name in Excel: `Quality_Risk_of_Bias_172_DETAIL`
Quality assessment for 172 primary studies: Study ID, Authors, Year, Title, Dataset, Model, Q1: Data source/sample clearly described?, Q1 Justification, Q2: Labels/annotation/ground truth clearly described?, Q2 Justification, Q3: Train/val/test design clearly reported and leakage controlled?, Q3 Justification, Q4: Evaluation metrics/results adequately reported?, Q4 Justification, Total Score /8, Overall Risk-of-Bias, Reproducibility: Dataset public? Code available?, Notes.

**Sheet 08_Quality_Summary_Stats**
Exact name in Excel: `Quality_Summary_Stats` + `Quality_Scoring_Legend`
Scoring Legend: Q1-Q4 scored as Yes=2, Partial=1, Unclear=0.5, No=0. Overall Risk: Low risk ≥6.5 (High quality), Moderate 4.5-6 (Medium quality), High <4.5 (Low quality).
Summary: Total primary studies 172, Low risk 139 (80.8%), Moderate 33 (19.2%), High 0, Mean 6.85/8.



### Data Availability
All sheets have zero empty critical columns. All 79 Title/Abstract and 28 Full-Text exclusions have varied EC-coded reasons. Search log, screening log, extraction rules, quality assessment are provided to replace "Not Applicable".

### License
CC BY 4.0
