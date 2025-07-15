######################
#코드 실행 방법
Rscript rice.gwas.R

#코드 실행 시 필수 사항
rice.gwas.R 
setwd("~/lecture") # Change경로 변경 필수!
#

#######################
2. R
> R.version
               _
platform       x86_64-conda-linux-gnu
arch           x86_64
os             linux-gnu
system         x86_64, linux-gnu
status
major          4
minor          4.3
year           2025
month          02
day            28
svn rev        87843
language       R
version.string R version 4.4.3 (2025-02-28)
nickname       Trophy Case


> library 
library(rrBLUP)
library(BGLR)
library(DT)
library(SNPRelate)
library(dplyr)
library(qqman)
library(poolr)


######################
3. linux(conda 가능)
#plink
plink 1.9 version
vcftools 0.0.14 version
bcftools 1.2 version

