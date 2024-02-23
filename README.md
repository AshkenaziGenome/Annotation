# Ashkenazi Genome Annotation
This repository contains the annotation for the Ash1 genome, beginning with version 1.7 of the
assembly. The annotation files include a GTF file describing all genes and transcripts, both
protein-coding and noncoding.

# Version 1.7

This is an initial version described in:

`Shumate A, Zimin AV, Sherman RM, Puiu D, Wagner JM, Olson ND, Pertea M, Salit ML, Zook JM, Salzberg SL. Assembly and annotation of an Ashkenazi human reference genome. Genome biology. 2020 Dec;21(1):1-8.`

The article is available online at https://genomebiology.biomedcentral.com/articles/10.1186/s13059-020-02047-7

The annotation for the version 1.7 is available at these locations:

* https://ashkenazi-genome.s3.us-east-2.amazonaws.com/Annotation/index.html
* ftp://ftp.ccb.jhu.edu/pub/data/Homo_sapiens/Ash1/v1.7/Annotation/

# Version 2.0

Version 2.0 sequence is a complete re-build of the chromosomes.  Thus we re-computed the annotation with version 1.5.0 of the Liftoff software following the procedure described in the original publication, lifting CHESS 2.2 annotation of GRCh38 onto v2.0 of Ash1.  Below is the comparison of the number of genes annotated on each chromosome (not counting genes annotated on unlocalized or alternative contigs) in the GRCh38, the original version 1.7 and the new version 2.0.  Note that Ash1 reference may have more genes on the chromosomes that GRCh38 because some genes that were on unplaced contigs in GRCh38 are on the chromosome sequences in Ash1.

|chromosome|GRCh38 # genes|v1.7 # genes|v1.7 # genes same chr as GRCh38|v2.0 # genes|v2.0 # genes same chr as GRCh38|
|----|----|----|----|----|----|
|chr1|4018|4009|4009|4010|4009|
|chr2|3019|3022|3022|3023|3022|
|chr3|2328|2324|2324|2328|2328|
|chr4|1930|1933|1933|1936|1935|
|chr5|2113|2117|2117|2117|2117|
|chr6|2280|2285|2284|2283|2283|
|chr7|2118|2119|2119|2125|2121|
|chr8|1697|1700|1700|1699|1699|
|chr9|1769|1765|1765|1771|1770|
|chr10|1792|1798|1798|1799|1798|
|chr11|2228|2232|2230|2229|2229|
|chr12|2107|2110|2110|2111|2110|
|chr13|1034|1031|1031|1028|1028|
|chr14|1308|1313|1313|1309|1309|
|chr15|1395|1396|1396|1399|1395|
|chr16|1723|1724|1723|1716|1716|
|chr17|2108|2109|2109|2108|2108|
|chr18|843|842|842|845|845|
|chr19|2111|2113|2113|2114|2112|
|chr20|1149|1162|1154|1155|1154|
|chr21|635|624|624|624|623|
|chr22|932|934|934|929|929|
|chrM|13|13|13|13|13|
|chrX|1334|1317|1317|1319|1319|
|chrY|184|210|210|218|216|
|Total|42168|42202|42190|42208|42188| 


The annotation for the 2.0 assembly is available here:

* ftp://ftp.ccb.jhu.edu/pub/data/Homo_sapiens/Ash1/v2.0/Annotation/

# Version 2.2

The annotation for the 2.2 assembly is available here:

* ftp://ftp.ccb.jhu.edu/pub/data/Homo_sapiens/Ash1/v2.2/Annotation/
