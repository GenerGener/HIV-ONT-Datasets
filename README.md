# HIV-ONT-Datasets
Practice dataset for native RNA sequencing and assembly. This information was made available for the [COVID-19 Biohackathon April 5-11 2020](https://github.com/virtual-biohackathons/covid-19-bh20).

## Background



## Method

Genomic DNA from the bone marrow of one (n=1) Tg26 male mouse (Dickie, et al. 1991) was extracted with special consideration for maintaining longer gDNA. Longrange PCR was performed to create ~6 kb amplicons. DNA was sequence on one MinION (Oxford Nanopore Technologies, Oxford, UK), with SQK-LSK109 accroding to manufacturer's protocol. Live basecalling with MinKNOW verion 19.12.5 was done on High-accuracy mode. Read filtering was done in Galaxy, specifying reads between 5.5 and 6 kb.

## Results

<img src="Mapping_overview.jpg"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />

![](https://github.com/GenerGener/HIV-ONT-Datasets/blob/master/HIV-ONT-Datasets/Mapping_overview.jpg) "test1"

![](https://github.com/NCBI-Codeathons/VirusGraphs3/blob/master/limit_of_linear.png)
Linear references are the gold standard for genomics applications, including capturing viral genome information and viral sequence recovery. Examples include HIV sequence detection and HIV genome assembly. HIV genome assembly can be loosely classified into whole (reference) genome assebly and HIV genotyping (partial assembly).

## Sources:

[Tg26 HIV mouse](https://www.jax.org/strain/022354)

Dickie P; Felser J; Eckhaus M; Bryant J; Silver J; Marinos N; Notkins AL. 1991. HIV-associated nephropathy in transgenic mice expressing HIV-1 genes. Virology 185(1):109-19PubMed: 1926769MGI: J:90297


