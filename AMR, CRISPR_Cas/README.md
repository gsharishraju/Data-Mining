Perfomed EDA on a medical dataset and visualized important variables and found correlation.

The given dataset comprises of 2223 rows and 3 columns. The 3 columns are Genome_ID,
CRISPR_Cas and AMR.
CRISPR_Cas has only two values. 0 indicating no presence and 1 indicating presence of
CRISPR_Cas.
AMR values have a min of 0 and a maximum of 31.
The histogram shows us that the CRISPR_Cas is absent in 2168 Genomes and is present in only
55 Genomes.
AMR gene numbers 3, 0, 16, 15 and 18 were found to be most present in the genomes
compared to other AMR genes.
Correlation between AMR and CRISPR_Cas is -0.156173 ≈ -0.16 which signals a negative
correlation.
The box plot of CRISPR_Cas shows that most genome_ids have a 0 value and only a few have a
value of 1. The AMR boxplot shows a minimum value of 0 and maximum value of 31. The
median lies at around 12. The 25th percentile lies at around 3 while the 75th percentile lies at
around 16.
