# mock-sequences

Mock community sequenced in three separate sequencing runs  (MiSeq fastq files)

Genomic DNA from the Microbial Mock Community B (Even, Low concentration), v5.1L (Catalog no. HM-782D, obtained through BEI Resources, NIAID, NIH as part of the Human Microbiome Project) was sequenced in three separate runs. Details of mock composition are included in Table 1. The mock contains DNA from 20 bacterial strains in equimolar (Even) ribosomal RNA operon counts (100000 copies per organism per µL). Two of the strains (Bacteroides vulgatus and Clostridium beijerinckii) have multiple sequence variants in the V4 region of the 16S rRNA gene. Bacteriodes vulgatus has three variants (in a 5:1:1 ratio), whereas Clostridium beijerinckii has two variants (in a 13:1 ratio). The 16S rRNA sequences of Staphylococcus aureus and Staphylococcus epidermidis are identical in the V4 region. Therefore, the mock contains a total of 22 variants (ASVs) of the 16S gene in the V4 region. These sequences correspond to 19 OTUs when clustered at 97% identity.

The ASV sequences of the strains contained in the mock (V4 region of the 16SrRNA gene) are also included in fasta format.

## File sizes and hashes

```bash
[mock-sequences]$ du -h *
 24M    Mock_3_R1.fastq.gz
 23M    Mock_3_R2.fastq.gz
6.1M    mock_1_R1.fastq.gz
7.2M    mock_1_R2.fastq.gz
 14M    mock_2_R1.fastq.gz
 18M    mock_2_R2.fastq.gz
8.0K    mock_sequences_V4.fasta

[mock-sequences]$ shasum *
c1d3c0b4d10faba265d88aac584264fb0653e834  Mock_3_R1.fastq.gz
f5a7639918350dbc684716682509ebf9f37ab22a  Mock_3_R2.fastq.gz
a708c49560e3d9d7ae213c3625fb79b85246a148  mock_1_R1.fastq.gz
4804ab584502d765c6aa2da94741d81bad3aa380  mock_1_R2.fastq.gz
4d6d2c18b7756baf4e99fff8d2f8820f9b18adba  mock_2_R1.fastq.gz
f4769a280e831b2cfdba6e523c5556e93ede3d3a  mock_2_R2.fastq.gz
986963cb32ac0bdfae976694ffd81aa94e5b9c0b  mock_sequences_V4.fasta
```
