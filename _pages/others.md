---
layout: archive
title: "Others"
permalink: /others/
author_profile: true
---


## download data from dbGaP and annotate 


<span style="font-size:0.7em;">
[dbGaP](https://www.ncbi.nlm.nih.gov/gap/) is short for database of Genotypes and Phenotypes, which is a public repository for individual level genotype, phenotype and sequence data. Before one downloads a data set from dbGaP, PI needs to submit an access request and it may take a couple of weeks to get approved.</span>  
  
 <span style="font-size:0.7em;">
 step 1: login to PI's [eRA Commons account](https://public.era.nih.gov/commons/public/login.do?TARGET=https%3A%2F%2Fpublic.era.nih.gov%2Fcommons%2FcommonsInit.do) to access the data <br>
 step 2: once you find the requested data, click download. There are several options, you may choose download to the local machine (make sure you have enough space) or HPC cluster which is preferred because the raw data even zipped is pretty big, (could be ~100G). It may take some time for download, especially when the data is very large, thus they would recommand installing [Aspera Connect](https://www.ibm.com/aspera/downloads/?p1=Search&p4=43700050328291508&p5=b&cm_mmc=Search_Google-_-1S_1S-_-WW_NA-_-%2Baspera_b&cm_mmca7=71700000060940834&cm_mmca8=kwd-297893703589&cm_mmca9=EAIaIQobChMIsJXmh5Ct6gIVTr7ACh0JHQ_-EAAYASABEgIQF_D_BwE&cm_mmca10=406108702306&cm_mmca11=b&gclid=EAIaIQobChMIsJXmh5Ct6gIVTr7ACh0JHQ_-EAAYASABEgIQF_D_BwE&gclsrc=aw.ds) for high speed download.<br>
 step 3: <b>all data are encrypted </b> for the sake of privacy. Data decryption is a bit tricky and complex. You will need a `repository key` which is a `.ngc` file associated with downloaded sample, then follow the instruction in **[Set dbGaP repository key for the project](http://statgen.us/lab-wiki/productivity_tips/dbGaP-download)** by Gao.<br>
step 4: Now all data should be decrypted and `vcf` file is ready for downstream analysis.<br>
step 5: For annotation, Yubin has [documentations](https://yubinxie.github.io/Genomics-Box/AnnotationDocument.html). 
 </span>
