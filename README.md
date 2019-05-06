# data-visualisation-course
interactive data visualisation 



data-visualisation-course-book-dev
-------------------------------------


Course Title: Interactive bioinformatics-data visualisation
-----------------------------------------------------------


Course summary
---------------


Visualising and plotting big data can become tricky or even impossible in some situations to do all in one excel sheet. 
This course will introduce you to the basics of scientific data visualisation. 
It will help you to tease out the interesting parts of your data by going interactive. 
Interactive plotting and visualisation is becoming more popular as a part of scientific publication with an advent of tools like D3 (https://github.com/d3/d3/wiki/Gallery),
plotly( https://plot.ly/ ), etc. We will go through the most common scenario from next generation sequencing data, specifically RNAseq expression data visualisation.
We will start with an excel sheet or typical outputs files from RNAseq pipelines, and we select subset of genes and interactively visualise the variation in 2D and 3D along 
experimental conditions that include variations across time, temperature and replicates. 
We will use Degust which an interactive web-tool for RNA-seq analysis (https://github.com/drpowell/degust) and go through few examples.


Objectives          
-----------


After this course you should be able to:

- To be able to visualise big RNAseq expression data
- Be able to fetch an interesting subset of the data
- Understand what RNAseq interactive visualisation is about 


 Course Content
-------------------------


* Introduction - what we'll cover
* We will go through few exemplar cases: a quick demonstration
* Practical: A hands-on introduction
* Practical: RNAseq expression data through IGV viewer quick tour
* Practical: RNA-seq exploration using Degust
* Visualising and comparing Gene ontology (GO terms) from expression data set using GO View


Poll 
-----

Data Visualisation has become mainstream - no more big tables, spreadsheets, bar/pie charts -

For an inspiration lets visit the story : "The 25 Best Data Visualizations of 2018" (https://visme.co/blog/best-data-visualizations/)



Interactive plotting
--------------------


* Lot of researchers are making use of plotly and R (https://davetang.org/muse/2016/08/30/interactive-plots-r-using-plotly/) and visit to to checkout the RNAseq data (http://rpubs.com/davetang/205147)

* I have done a short demo  (https://plot.ly/~threadmapper/89) using mouse over we can explore(interactive) the gene names

* mRNA expression in tissues (https://plot.ly/~assafm/3/#/)

* I used to do make and edit templates (https://github.com/veusz/veusz) and save them into SVG and then add the interactivity by writing  tooltips. 

* Plotly serves a large bioinformatics research community. These users leverage the uniquely interactive features of plotly charts for dendrograms, heatmaps, volcano plots, and other visualizations common in this field. Using Python and R created through plotly  researchers have created some neat visualisation (https://moderndata.plot.ly/bioinformatics-plots-made-in-python-and-r/)

* For RNASeq specifically (http://gepia.cancer-pku.cn/) GEPIA built using plotly interctivity.
  Tang, Z. et al. (2017) GEPIA: a web server for cancer and normal gene expression profiling and interactive analyses. 
  (Nucleic Acids Res, 10.1093/nar/gkx247) .




MSA 
---

We go through Alignment Viewer (MSA) component is used to align multiple genomic or proteomic sequences from a FASTA or Clustal file.
Among its extensive set of features, the multiple sequence alignment viewer can display multiple subplots showing gap and conservation info, 
alongside industry standard colorscale support and consensus sequence. No matter what size your alignment is, Alignment 

(https://dash-bio.plotly.host/dash-alignment-viewer/)


Circos
------


* Useful links and useful advice to make your own ciros visualisation
  (https://medium.com/@Marianattestad/a-treatise-on-making-circos-plots-from-genomic-data-7ff496849e0)

* Visualize Circos: Human Chromosomes (https://dash-bio.plotly.host/dash-circos)

* Circos table viewer: It makes chord diagrams from an adjacency matrix webbased circos table viewer(http://mkweb.bcgsc.ca/tableviewer/)
 This is very generic and if you have understood this use can adjust it plot any genomic data as the underlying principles are same.
   
* If you prefer R (https://jokergoo.github.io/circlize_book/book/)

 



RNA seq mapping data visualisation(IGV)
---------------------------------------

* We will use IGV(Integrative Genomics Viewer)

* Integrated visualization tool for multiple data types and genome annotations.

* Data from NGS analysis can be easily visualized: Interactive and speedy visualization. Run locally on desktop

* Handles large datasets 

* View multiple datasets in separate panels on the same pane( hence intergrative)

* Supports several track management options (filtering, grouping, sorting) and in-built tools (index, sort, motif finder etc)

* Direct visualization from web-resource in the formats: bed, wig, gff, gff3, Bam, bigWig, bigBed, vcf etc


* IGV execises viewing BAMS  and spotting SNPs( data under the repo `igv-mutant-data`)


RNAseq Expression data visualisation (Degust)
---------------------------------------------

- We can upload the data  

- Already uploaded as a session (http://degust.erc.monash.edu/degust/config.html?code=d24c2a88f917954853272af3e80cde5a)








Using Expression atlas: Transcription profiling by high throughput sequencing of Arabidopsis roots, leaves, flowers and siliques 
(https://www.ebi.ac.uk/gxa/experiments/E-GEOD-38612/Results)




Further resources
-----------------


- We will use, GeNeCK (http://lce.biohpc.swmed.edu/geneck/) Zhang etal(2019) 1BMC Bioinformatics. 2019; 20: 12`  a web server for gene network construction and visualization we will spot the important gene in the networks gene expression data
- Cytoscape: a software environment for integrated models of biomolecular interaction networks, Genome Research 2003 Nov; 13(11):2498-504 



