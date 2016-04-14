# hrbi
hrbi stands for Holly Ruess BioInformatics.

These programs were created to aid in the assembly of genomic regions from resequencing Illumina data.

# hrbi.simple_reseq_walker

Resequencing data can usually be mapped to a good reference sequence. But sometimes reads cannot map to introns or large insertions due to sequence differences. This program can take two scaffolds and try to connect them in a homozygous, unmappable region.

# hrbi.simple_reseq_finisher

This program is a complement to hrbi.simple_reseq_walker. It takes the final output file (*.final_walker.fa) and corrects the errors that were generated.

# hrbi.complex_reseq_walker

Resequencing data can usually be mapped to a good reference sequence. But sometimes reads cannot map to introns or large insertions due to sequence differences. This program can take two scaffolds and try to connect them in a heterozygous, unmappable region.

# hrbi.complex_reseq_finisher

This program is a complement to hrbi.complex_reseq_walker. It takes the final output file (*.final_walker.fa), corrects the errors that were generated and phases the data into 2 alleles.
