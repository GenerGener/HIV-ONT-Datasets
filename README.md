# HIV-ONT-Datasets
Practice dataset for native RNA sequencing and assembly. These data provide a model for viral haplotyping for SNVs at least 6 kb apart. This information was made available for the [COVID-19 Biohackathon April 5-11 2020](https://github.com/virtual-biohackathons/covid-19-bh20).

## Background

The Tg26 mouse has gagpol-deleted HIV integrated artificially (inserted) into the mouse germline. These insertion sites have not been characterized at depth. A recent PCR-free gDNA sequencing run (unpublished) supported N HIV copies across multiple sites (Table 1). At the time, that study was limited by inherrent shortcomings of short read sequencing (paired-end 150, average insert sized 511). Variants in HIV copies further apart than 511 bases would not be able to be phased with this short-read data.

## Method

Genomic DNA from the bone marrow of one (n=1) Tg26 male mouse (Dickie, et al. 1991) was extracted with special consideration for maintaining longer gDNA. Longrange PCR was performed to create ~6 kb amplicons. DNA was sequence on one MinION (Oxford Nanopore Technologies, Oxford, UK), with SQK-LSK109 accroding to manufacturer's protocol. Live basecalling with MinKNOW verion 19.12.5 was done on High-accuracy mode. Read filtering was done in Galaxy, specifying reads between 6 and 6.25 kb. Read mapping done with minimap2 in Galaxy. Visualized in IGV.

## Results

*Table 1: Variants in a Tg26 mouse*

![](https://github.com/GenerGener/HIV-ONT-Datasets/blob/master/HIV-ONT-Datasets/Mapping_overview.tif)
*Figure 1: Subset of reads that were acquired by the end of the sequencing run*






## Sources:

[Tg26 HIV mouse](https://www.jax.org/strain/022354)

Dickie P; Felser J; Eckhaus M; Bryant J; Silver J; Marinos N; Notkins AL. 1991. HIV-associated nephropathy in transgenic mice expressing HIV-1 genes. Virology 185(1):109-19PubMed: 1926769MGI: J:90297


