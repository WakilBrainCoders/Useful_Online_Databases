# Useful_Online_Databases: a list of useful resources for interpreting brain microarray data:

## Gene expression omnibus: A public archive of transcriptomic data (microarray, RNA-Seq, epigenetics...)
### I added example code for downloading from GEO here, but also put it in the folder specific to GEO
### Good for comparing our results to previous results:
#### 1) Can provide validation or confirmation (if the archived experiments address a similar research question)
#### 2) Can provide extra data if we need to increase sample size to see anything (meta-analysis)
#### 3) Can help with interpretation (e.g., comparing the influence of GROV in the brain to the influence of cortisol on cultured neurons)
https://www.ncbi.nlm.nih.gov/geo/

## dbSNP & dbVar: A searchable database of genetic variants linked to various diseases or phenotypes
### Note: typically, to interpret this information you will need to look up the genes that are thought to have expression regulated by these genetic variants in an eQTL database (see below). 
https://www.ncbi.nlm.nih.gov/projects/SNP/

## Rat Genome Database: Amongst other things, you can search for genetic variants related to behavioral phenotypes in rats & mice.
http://rgd.mcw.edu
### e.g. anxiety:
http://rgd.mcw.edu/rgdweb/search/qtls.html?term=Anxiety&chr=ALL&start=&stop=&map=360&rs_term=&vt_term=&speciesType=3&obj=qtl
### You can also search for the phenotypes associated with genetic variants near particular genes, e.g. C1qa:
http://rgd.mcw.edu/rgdweb/report/gene/main.html?id=1306716
### I think there is a way to do this in bulk, but I don't remember how.

## Mouse Genome Informatics: Amongst other things, you can search for genetic variants related to behavioral phenotypes in mice.
http://www.informatics.jax.org
### This website definitely lets you batch query a list of genes for known phenotypes:
http://www.informatics.jax.org/batch_data.shtml