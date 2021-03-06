# mock-sequences
Mock community sequenced in three separate sequencing runs  (MiSeq fastq files)

Genomic DNA from the Microbial Mock Community B (Even, Low concentration), v5.1L (Catalog no. HM-782D, obtained through BEI Resources, NIAID, NIH as part of the Human Microbiome Project) was sequenced in three separate runs. Details of mock composition are included in Table 1. The mock contains DNA from 20 bacterial strains in equimolar (Even) ribosomal RNA operon counts (100000 copies per organism per µL). Two of the strains (Bacteroides vulgatus and Clostridium beijerinckii) have multiple sequence variants in the V4 region of the 16S rRNA gene. Bacteriodes vulgatus has three variants (in a 5:1:1 ratio), whereas Clostridium beijerinckii has two variants (in a 13:1 ratio). The 16S rRNA sequences of Staphylococcus aureus and Staphylococcus epidermidis are identical in the V4 region. Therefore, the mock contains a total of 22 variants (ASVs) of the 16S gene in the V4 region. These sequences correspond to 19 OTUs when clustered at 97% identity.

Reverse reads from the 3rd mock run ("mock_3") were split into 2 parts to accommodate the github file size upload limit. You simply need to ungzip and then concatenate the fastq files to reconstruct the original reverse reads fastq.

The ASV sequences of the strains contained in the mock (V4 region of the 16SrRNA gene) are also included in fasta format.
