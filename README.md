# Project_Scripting_for_Biologists
# Title: Identification of novel SNPs associated with breast cancer using WGS data
## Introduction: 
Breast cancer is a complex and heterogeneous disease with diverse genetic alterations contributing to its development and progression. With advancements in high-throughput DNA sequencing technologies, whole genome sequencing (WGS) has emerged as a powerful tool for identifying genetic variants associated with breast cancer. WGS allows for a comprehensive and unbiased assessment of the entire genome, providing detailed insights into the genomic landscape of breast cancer.

In this project, I utilized WGS data to identify genetic variants in breast cancer samples using Genomic Analysis Tool Kit (GATK) best practices. Variant calling is a critical step in the analysis of WGS data, where the goal is to identify DNA sequence changes, such as single nucleotide polymorphisms (SNPs) and small insertions/deletions (indels), that may underlie breast cancer pathogenesis. By applying haplotype caller to breast cancer WGS data, I aimed to comprehensively characterize the spectrum of genetic variants in the genome, which may contribute to our understanding of the molecular mechanisms underlying breast cancer development and progression.

## Bioinformatics Processing of the Data:
Quality Control of the WGS raw data





## Results:



## Conclusion:
In conclusion, this study utilized whole genome sequencing data and GATK best practices to identify genetic variants in breast cancer samples, providing valuable insights into the genomic landscape of breast cancer. The findings contribute to the growing understanding of the genetic alterations that drive breast cancer development and progression.

## Limitations and Future Directions:
The identification of genetic variants in breast cancer has important implications for clinical practice and research. It may enable the development of targeted therapies, as well as help in identifying potential biomarkers for diagnosis, prognosis, and treatment response prediction. Due to the gigantic size of the human WGS data, it has taken a huge amount of time to complete each step of the bioinformatics processing of the data. Most of the time I got an “out of memory” error while processing the data. Due to these limitations, I could not go further than variant calling. In future, the identified SNPs could be annotated using ANNOVAR and filtered based on allele frequency, functional impact, and predicted pathogenicity. The filtered SNPs could be tested for association with breast cancer using a logistic regression model implemented in PLINK. SNPs could be validated by comparing them to publicly available databases such as dbSNP, which contains information on known SNPs. This method can help determine whether the SNP has been previously identified in other studies. Nevertheless, the findings provide a foundation for future research and contribute to the growing body of knowledge on breast cancer genomics. These findings have the potential to impact breast cancer diagnosis, treatment, and personalized medicine approaches. Further research in this area may lead to improved therapeutic strategies and better patient outcomes in breast cancer management.
