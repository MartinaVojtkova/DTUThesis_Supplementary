# Supplementary files for Genome-wide analysis for the quantification of gene flux in _E.coli_

`Gene_results_summary.csv`contains data for all 6434 selected for Gene Flux analysis.
The following columns are included:  
- **Gene:** Gene cluster name as provided by Roary
- **Occurrence**: Number of genomes where the gene was present
- **Kmer_distance_median:** Per-gene median value of the flanking region k-mer distance matrix. (K-mer Hamming distance used as measure)
- **ANI_median:** Per-gene median value of the flanking region average nucleotide identity matrix
- **Flank_index_median:** Per-gene median value of the flanking region flank identity index matrix. (Measure of flank annotation similiarity)
- **Proc_corelation:** The correlation between the flanking region k-mer distances and whole genome distances. (Symmetric Procrustes Analysis)
- **Proc_significance:** The significance value for Procrustes correlation.
- **Man_correlation**: The correlation between the flanking region ANI's and whole genome similarity. (Mantel Test)
- **Man_significance**: The significance value of Mantel statistic (correlation).
- **Man_significance_FDR_adjusted**: False discovery rate adjusted Mantel test p-values
- **Roary_annotation**: Gene annotation as provided by Roary
- **KEGG_Pathway**: Pathways from KEGG functional annotation
- **GO_BP_term**: Assigned Biological Process subontologies (separated by "/")
- **GO_MF_term**: Assigned Molecular Function subontologies (separated by "/")
- **GO_CC_term**: Assigned Cellular Component subontologies (separated by "/")
