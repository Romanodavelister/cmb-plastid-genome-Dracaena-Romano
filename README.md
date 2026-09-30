# Characterization of a Plastid Genome

**Student Name:** Dave Lister F. Romano

**Course/Section:** BIO 300 - A

# Organism and Data Source

**Genus and Species:** *Dracaena draco* (Canary Islands dragon tree)

**Family:** Asparagaceae

**Accession/version:** NC_048492.1 (NCBI RefSeq, identical to GenBank MN990038)

**Source link:** https://www.ncbi.nlm.nih.gov/nuccore/NC_048492.1

**Date retrieved:** September 29, 2026

# Plastome Summary

**Genome size:** 155,422 bp

**Topology:** Circular
 
**GC content:** 37.60%

**Structure:** LSC 83,942 bp, SSC 18,472 bp, IR 26,504 bp each

**Genes:** 132 annotated genes ( 86 protein-coding, 38 tRNA, 8 rRNA)

# How the Genome Was Obtained

On the NCBI Nucleotide record page, I used Send to → Complete Record → File and downloaded the FASTA (Dracaena_draco_NC_048492.1.fasta). I uploaded the FASTA to usegalaxy.org and confirmed the datatype was fasta.

# Galaxy Analysis

**History name:** Plastid_Dracaena_Romano

**Tool used:** Fasta Statistics

# Gene Content and Important Observations

The Dracaena draco plastome (NC_048492.1) is a circular molecule of 155,422 bp with a GC content of 37.60%. It has the typical LSC-IR-SSC-IR structure (LSC 83,942 bp, SSC 18,472 bp, IR 26,504 bp each). The annotation lists 132 genes: 86 protein-coding, 38 tRNA, and 8 rRNA. It includes the photosynthesis genes (psa, psb, pet, atp, rbcL), RNA polymerase genes (rpo), ribosomal protein genes (rpl, rps), rrn and trn genes, and other conserved genes (matK, clpP, accD, cemA, ycf).

# Data Sources and References

NCBI Nucleotide, RefSeq NC_048492.1: https://www.ncbi.nlm.nih.gov/nuccore/NC_048492.1

Celinski K., Kijak H., Wiland-Szymanska J. (2020). Complete Chloroplast Genome Sequence and Phylogenetic Inference of the Canary Islands Dragon Tree (Dracaena draco L.). Forests 11(3): 309. https://doi.org/10.3390/f11030309

Galaxy: usegalaxy.org

# How to Repeat This Analysis

1. Search NCBI Nucleotide for NC_048492.1 and open the record.
2. Use Send to → Complete Record → File to download the FASTA and GenBank files.
3. Sign in to your own account at usegalaxy.org and create a history named Plastid_Dracaena_<Surname>.
4. Upload the FASTA, confirm the datatype is fasta, and rename it Dracaena draco NC_048492.1.
5. Run SeqKit stats / FASTA Statistics and record the number of sequences, length, and GC%.
6. Use the GenBank feature table to count genes and identify the gene groups.
