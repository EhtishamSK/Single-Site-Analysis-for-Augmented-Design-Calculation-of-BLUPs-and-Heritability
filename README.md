This R script automates the calculation of heritability and Best Linear Unbiased Predictions (BLUPs) for multiple numeric traits in a dataset. It selects numeric traits, fits a mixed model using the asreml package, and computes heritability and BLUPs for each trait. Heritability is derived from genetic variance, and BLUPs for each genotype are predicted with standard errors. The results are saved in two separate CSV files: Heritability_Results.csv for heritability estimates and BLUP_Results.csv for genotype BLUPs and their standard errors. The script is designed to handle multiple traits efficiently, making it scalable for large datasets.






