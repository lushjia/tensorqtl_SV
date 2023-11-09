## tensorQTL_SV
accomodate tensorqtl (https://github.com/broadinstitute/tensorqtl.git) for SV architecture    
so long as an SV span touch the gene window, the SV is included to compute correlation with the gene

mainly change genotypeio.py InputGeneratorCis function

input variant_df should be 4 columns: snp(index of df), chrom, pos (is accutually start of variants), end

