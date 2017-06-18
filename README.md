# Analysis of Parkinson Disease dataset using R

Environment: R (3.3.1) and R Studio (1.0.136)

This project was based on Integrative Genomics. Initially, I learned how Genome-Wide Association Studies (GWAS) work. Then I learned how to find differential genes between colorectal cancer tumor/normal samples in a functional genomics dataset.

The raw data consists of more than 408,000 single nucleotide polymorphisms (SNPs) which were measured (or genotyped) across 276 patients with Parkinson’s Disease, and 276 normal control individuals. Each SNP is a potentially differing nucleotide between individuals. Recall that there are estimated to be as many as 10 million SNPs in the human genome, so this collection does not encompass all of them.

I used Chi-Squared Test to determine whether the genotype distribution seen in Parkinson’s Disease patients is different than control individuals (i.e. a case-control study). A chi-squared test for these data with 2 degrees of freedom yields a p-value of 6.301 x 10-6, indicating that it is highly unlikely that the Parkinson’s Disease distribution matches the control distribution. A Fisher-exact test was also used, yielding similar results. Either way, this indicated that the genotype distributions are significantly associated with the presence of Parkinson’s Disease.
