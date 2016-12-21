This package constitutes an interactive R problem set based on the RTutor package (https://github.com/sebmerk/RTutorInnoComp). 

This RTutor problem set analysis the relationship between market structure and innovation in the global automotive industry. It is based on the paper **The Relationship Between Market Structure and Innovation in Industry Equilibrium: A Case Study of the Global Automobile Industry** by Aamir Rafique Hashmi and Johannes Van Biesebroeck. The paper was published in *The Review of Economics and Statistics 98 (1)* in 2016.    
You can download the paper from <a href="http://www.mitpressjournals.org/doi/abs/10.1162/REST_a_00494?journalCode=rest#.WB8AzPnhCUk" target = "_blank"> MIT Press Journals</a>.

## 1. Installation

RTutor and this package is hosted on Github. To install everything, run the following code in your R console.
```s
if (!require(devtools))
  install.packages("devtools")
source_gist("gist.github.com/skranz/fad6062e5462c9d0efe4")
install.rtutor(update.github=TRUE)

devtools::install_github("sebmerk/RTutorInnoComp", upgrade_dependencies=FALSE)
```

## 2. Show and work on the problem set
To start the problem set first create a working directory in which files like the data sets and your solution will be stored. Then adapt and run the following code.
```s
library(InnovationMarketStructure)

# Adapt your working directory to an existing folder
setwd("C:/problemsets/")
# Adapt your user name
run.ps(user.name="Jon Doe", package="RTutorInnoComp",
       load.sav=TRUE, sample.solution=FALSE)
```
If everything works fine, a browser window should open, in which you can start exploring the problem set.
