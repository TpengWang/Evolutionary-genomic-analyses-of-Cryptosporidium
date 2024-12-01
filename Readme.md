# **Evolutionary genomic analyses of *Cryptosporidium***

This project was designed to describe procedures for evolutionary genomic analyses of *Cryptosporidium* spp. The approaches and their utility are described in recent publications:

> Wang, T., Y. Guo, D. M. Roellig, N. Li, M.
> Santin, J. Lombard, M. Kvac, D. Naguib, Z. Zhang, Y. Feng and L. Xiao (2022).
> "Sympatric Recombination in Zoonotic Cryptosporidium Leads to Emergence of
> Populations with Modified Host Preference." Mol Biol Evol **39**(7) [10.1093/molbev/msac150](https://doi.org/10.1093/molbev/msac150)
>
> Huang, W., Y. Guo, C. Lysen, Y. Wang, K. Tang,
> M. H. Seabolt, F. Yang, E. Cebelinski, O. Gonzalez-Moreno, T. Hou, C. Chen, M.
> Chen, M. Wan, N. Li, M. C. Hlavsa, D. M. Roellig, Y. Feng and L. Xiao (2023).
> "Multiple introductions and recombination events underlie the emergence of
> a hyper-transmissible Cryptosporidium hominis subtype in the USA." Cell
> Host Microbe **31**(1): 112-123 e114 [10.1016/j.chom.2022.11.013](https://doi.org/10.1016/j.chom.2022.11.013)

----

## Software and scripts used

**1**  **Quality control and variant calling**

1. Computer or server with Linux system
2. R v4.3.3 (https://www.r-project.org/)
3. Python v2.7 and v3.10 (https://www.python.org/)
4. fastp v0.24.0 (https://github.com/OpenGene/fastp)
5. bwa-mem2 v2.2.1 (https://github.com/bwa-mem2/bwa-mem2)
6. samtools v1.21 (https://github.com/samtools/samtools)
7. sambamba v1.0.1 (https://github.com/biod/sambamba)
8. bcftools v1.21 (https://github.com/samtools/bcftools)
9. GATK v4.3 (https://github.com/broadinstitute/gatk)
10. VCFtools v0.1.16 (https://vcftools.github.io/index.html)
11. moimix (https://github.com/bahlolab/moimix)
12. SeqArray (https://github.com/zhengxwen/SeqArray)

**2  Population structure analysis**

1. vcf2phylip (https://github.com/edgardomortiz/vcf2phylip)
2. IQ-TREE v2.3.6 (http://www.iqtree.org/)
3. iTOL v7 (http://itol.embl.de/)
4. SNPRelate (https://github.com/zhengxwen/SNPRelate)
5. gdsfmt (https://github.com/cran/gdsfmt)
6. Plink v1.9 (https://www.cog-genomics.org/plink/1.9/)
7. fastStructure (https://rajanil.github.io/fastStructure/)
8. CLUMPAK (https://tau.evolseq.net/clumpak/)

**3  Population genomic calculation**

1. genomics_general (https://github.com/simonhmartin/genomics_general)

**4  Recombination analysis**

1. PopLDdecay v3.43 (https://github.com/hewm2008/PopLDdecay)
2. SplitsTree v6 (https://github.com/husonlab/splitstree6)
3. Dsuite (https://github.com/millanek/Dsuite)