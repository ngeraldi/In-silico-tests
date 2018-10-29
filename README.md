# In-silico-tests
Provides results of in silico tests of multiple primers

We are using muliptl eprimers for eDNA studies.  Below are some in silico test results using trim function from the insect package in R.

See training datasets for details about database creation and below for primer details

rbcl gene, reference library created from ncbi search, in silico test with mini-rbcl:
https://www.dropbox.com/s/v0oye0vqfvj7x48/ncbi_rbcl_dada_lineage_rbclmini_insilico.csv?dl=0

Multipl 18s primers, refernce library was Silva V132, in silico test using below 18s primers
All data:
https://www.dropbox.com/s/1xbwuxznjr94ya1/Silva132_dada_and_silva_lineage_wprimerinfo_all.csv?dl=0

Data with Bacteria removed:
https://www.dropbox.com/s/i7wnytvn2c9n4zs/Silva132_dada_and_silva_lineage_wprimerinfo_no_bacteria.csv?dl=0

Metazoan data with addition data on "marine species" as determined by Worms:
https://www.dropbox.com/s/rb05tl1b8hiohxc/Silva132_dada_and_silva_lineage_metaz_worms_18sprims.csv?dl=0


Primers used:
# vert
PRIMER1=ACTGGGATTAGATACCCC
PRIMER2=TAGAACAGGCTCCTCTAG

#  metazoan CO1    (Leray et al. 2013 )
#PRIMER1="GGWACWGGWTGAACWGTWTAYCCYCC"
#PRIMER2="TANACYTCNGGRTGNCCRAARAAYCA"
#  original with I -   don't use PRIMER1="GGWACWGGWTGAACWGTWTAYCCYCC"
#  original with I -   don't use PRIMER2="TAIACYTCIGGRTGICCRAARAAYCA"

#  euka02  (V7, Taberlet et al. 2018)
#PRIMER1='TTTGTCTGSTTAATTSCG'
#PRIMER2='CACAGACCTGTTATTGC' 
# 
##    18s mini (V9, Amaral-Zettler et al. 2009)
#PRIMER1="CCCTGCCHTTTGTACACAC"
#PRIMER2="CCTTCYGCAGGTTCACCTAC"
# 
##    18s Universal (V4, Stoeck et al 2010)
#PRIMER1="CCAGCASCYGCGGTAATTCC"
#PRIMER2="ACTTTCGTTCTTGATYRA"

####    minirbcl (Little et al. 2014)
#PRIMER1="GTTGGATTCAAAGCTGGTGTTA"
#PRIMER2="CVGTCCAMACAGTWGTCCATGT"
