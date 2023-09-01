# SVHack_Pangenomics

## Intro
Genomics is the foundation for understanding the biological characteristics, evolution, and human genetic diseases of species. Since the launch of the Human Genome Project, millions of human genomes have been sequenced, and the cost of short read long DNA sequencing has significantly decreased. However, there is still some basic information in the genome that needs to be explored.

Pan-genomics is the sum of all genomic information within a species, covering more genetic diversity than a single reference genome, which is helpful for population research. Not only focusing on common core gene sets in all individuals, pan genomics also includes some accessory genes not shared. Due to the complexity and diversity of pangenomes, more advanced tools are currently needed for analysis.

In large-scale population genomics research, the single standard reference genome model has inherent limitations, especially in the fields of human genomic analysis, while a graph representing many genome assemblies at once have been employed as the powerful tool for pan genomic analysis, as it provides an approach for visualization and complicated structural variations. Also, graph genomics can be adopted to representation of linear or non-linear genomic structures, new presentation method for variations has been provided. Toolkits for graph genomes generation has been proposed for various applications, including PGR-TK, PGGB, PanGenie, Giraffe method and so on. 

-Pan-Genome Research Tool Kit (PGR-TK) enabling analyses of complex pangenome structural and haplotype variation at multiple scales, which provides detailed structure and analysis on complex genomic regions which couldn’t be analyzed before.

- We are aimed to construct a database of high variation risk regions in human genomic sequences with corresponding indexes. 



## Overview

### Procedures
![image](https://github.com/collaborativebioinformatics/SVHack_Pangenomics/blob/main/Images/1.PNG)

### Flowchart
![image](https://github.com/collaborativebioinformatics/SVHack_Pangenomics/blob/main/Images/2.PNG)

## Methodology
### Database establishment
1. Input a series of Human pan genome research consortium data set
2. Use tools to figure out high variation risk regions.
3. Record the regions in the database.
4. Establish the index and classification of regions (e.g. The variation type, the position…)
5. That's the Database!
![image](https://github.com/collaborativebioinformatics/SVHack_Pangenomics/blob/main/Images/4.PNG)
![image](https://github.com/collaborativebioinformatics/SVHack_Pangenomics/blob/main/Images/5.PNG)

### Query and Analysis
1. Input sequence data.
2. analyze via PGR-TK.
3. Compare the similarity of specific regions in input sequence with high variation risk regions in database.
4. Return analysis results and similar high variation risk regions.
![image](https://github.com/collaborativebioinformatics/SVHack_Pangenomics/blob/main/Images/6.PNG)

### Why PGR-TK?
- Quick analysis. --<font color="Blue"> Quick results receipt</font>
- Detailed analysis and visualization of gene map-graph. –-<font color="Blue">Accurate and detailed results</font>
- Scripts can be integrated on the server, just need to input data. –-<font color="Blue">Convenient procedure for users</font>
## Tools Adopted
PGR-TK- Chin, CS., Behera, S., Khalak, A. et al. Multiscale analysis of pangenomes enables improved representation of genomic diversity for repetitive and clinically relevant genes. Nat Methods 20, 1213–1221 (2023). https://doi.org/10.1038/s41592-023-01914-y
        
        
        
        
        
        
        
        
        
        

SnpEFF- Cingolani P, Platts A, Wang le L, Coon M, Nguyen T, Wang L, Land SJ, Lu X, Ruden DM. Fly (Austin).A program for annotating and predicting the effects of single nucleotide polymorphisms, SnpEff: SNPs in the genome of Drosophila melanogaster strain w1118; iso-2; iso-3.,  2012 Apr-Jun;6(2):80-92. PMID: 22728672
        
        
        
        
        
        
        
        

FastANI- Jain, C., Rodriguez-R, L.M., Phillippy, A.M. et al. High throughput ANI analysis of 90K prokaryotic genomes reveals clear species boundaries. Nat Commun 9, 5114 (2018). https://doi.org/10.1038/s41467-018-07641-9
        
        
        
        
        
        
        
        

## Contributor
Yidong Zhang- Conceptualization, Text Writing, Figure Drawing, Presentation and ....wow.
