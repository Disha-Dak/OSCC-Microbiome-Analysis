# Microbial Dysbiosis and Biomarker Discovery in Oral Squamous Cell Carcinoma
Overview
This project investigates microbial signatures in Oral Squamous Cell Carcinoma (OSCC) and tobacco users through 16S rRNA sequencing analysis of saliva samples.

# Key Results

### Microbial Composition
- **OSCC Samples**:
  - High abundance of Megasphaera (13.2%), Parvimonas (7.4%), Prevotella (7.1%)
  - Distinct bacterial profile compared to controls

- **Tobacco Users**:
  - Dominated by Streptococcus (65.0%)
  - Significant presence of Rothia (5.5%) and Leptotrichia (3.2%)

### Statistical Analysis
- Clear group separation in PCA (48.48% total variance explained)
- Machine learning classification achieved AUC=1.00
- Identified key biomarkers:
  - Leptotrichia and Rothia: Strong positive association with tobacco use
  - Parvimonas and Veillonella: Negative association with tobacco use

## Data Processing
16S rRNA sequences quality assessment with FastQC and QIIME
Microbiome diversity analysis among control, OSCC, and tobacco users
Multivariate statistical analysis for differential abundance testing
Logistic regression-based machine learning for biomarker discovery

## Tools Used

QIIME 2 for microbiome analysis
Python 3.10 with libraries:

Pandas
NumPy
Scikit-learn
SciPy
Matplotlib
Seaborn
Statsmodels

## Key Findings and Implications
Clear microbial signature differences between groups
Potential biomarkers identified for disease progression
Tobacco users show intermediate microbiome profiles
Machine learning models demonstrate potential for diagnostic applications
Results suggest gradual microbiome changes from healthy individual to disease condition

## Diversity Analysis

Alpha rarefaction plots showed:

Higher diversity in control groups
Steeper increase in feature detection in OSCC samples
Variable feature detection levels in tobacco users
Some OSCC samples reached saturation at lower sequencing depths

## Data
- Source: NCBI SRA (PRJNA548462)
- Quality control: Forward reads truncated at 222, reverse at 216

## Contact
- Disha Jain
- Email: dj.disha39@gmail.com

## License
MIT License
