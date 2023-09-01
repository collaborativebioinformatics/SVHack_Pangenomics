# SVHack_Pangenomics

## Intro
- In large-scale population genomics research, the single standard reference genome model has inherent limitations, especially in the fields of human genomic analysis. Pan-Genome Research Tool Kit (PGR-TK) enabling analyses of complex pangenome structural and haplotype variation at multiple scales, which provides detailed structure and analysis on complex genomic regions which couldn’t be analyzed before.

- We are aimed to construct a database of high variation risk regions in human genomic sequences with corresponding indexes. 

## Flowchart
![image](https://github.com/collaborativebioinformatics/SVHack_Pangenomics/blob/main/graphic%20flowchart.jpg)

## Procedures
### Database establishment
1. Input a series of Human pan genome research consortium data set
2. Use tools to figure out high variation risk regions.
![image](https://github.com/collaborativebioinformatics/SVHack_Pangenomics/blob/main/Images/workflow1.PNG)
3.  Record the regions in the database.
4. Establish the index and classification of regions (e.g. The species, the gene, the relevant disease phenotype…)
5. Finish
![image](https://github.com/collaborativebioinformatics/SVHack_Pangenomics/blob/main/Images/workflow2.PNG)

### Query and Analysis
1. Input sequence data.
2. analyze via PGR-TK.
3. Compare the similarity of specific regions in input sequence with high variation risk regions in database.
4. Return analysis results and similar high variation risk regions.
![image](https://github.com/collaborativebioinformatics/SVHack_Pangenomics/blob/main/Images/workflow3.PNG)

### Why PGR-TK?
- Quick analysis. --<font color="Blue"> Quick results receipt</font>
- Detailed analysis and visualization of gene map-graph. –-<font color="Blue">Accurate and detailed results</font>
- Scripts can be integrated on the server, just need to input data. –-<font color="Blue">Convenient procedure for users</font>

