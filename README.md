# CactoblastisOutliersTest
Analysis in *Cactoblastis cactorum* of the native region (Argentina) with ddRAD data to find candidate genes.

Process:
* We added the basic analysis command lines (structure and diversity)-> See Structure and diversity basic analysis script.txt file.
* We tested if there is an association between genetic structure and geography with a Mantel test. -> See Mantel test.txt file.
* We make a RDA to find candidate SNPs possibly associated to environmental variables -> See Redundancy Analysis (RDA) script.txt file.

NOTE: we already knew that five variables are important for Cactoblastis cactorum establishment,
and they are not correlationed with each other. The variables are: Annual Mean Temperature, 
Annual Precipitation, Mean Diurnal Range, Isothermality and 
Temperature Annual Range (N. Castillo, personal communication, March 7, 2022).

Data was previously filtered with vcftools and plink1.9:
* min_alleles and max alleles=2 
* missing data=0.8
* MAF=0.05
* HWE=0.05
* LD(linkage disequilibrium)=0.25

We obtained 7,552 SNPs with 224 individuals.

* Environmental variables values were obtained with WorldClim (worldclim.org/data/bioclim.html).
