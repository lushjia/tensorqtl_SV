## tensorQTL_SV
accomodate tensorqtl (https://github.com/broadinstitute/tensorqtl.git) for structural variant(SV) architecture    

Any structural variant (SV) that overlaps or touches the gene window is now included for correlation analysis with that gene.

The main modification is in the genotypeio.py file, within the InputGeneratorCis function.

The input variant_df should contain four columns: snp(index of input df), chrom, pos (start position of the variant), end

one chromosome at a time

