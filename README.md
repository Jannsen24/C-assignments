## Cousera project: Development of a R package

## Building R Packages
The previous weeks have been spent on learning and understanding the 
development of R packaging in R. This document has the purpose to help you 
get started with the package! 

### Step 1 

First install and load the 'devtools' package using the following code: 

```R
install.packages('devtools')
library(devtools)
```
### Step 2

Install and load the downloaded package from github with the following code: 

```R
install_github('tybyers/DataX')
library(DataX)
```

### Vignette

Read the following instruction to get up 
and running for the package : `vignette('introduction', package = 'DataX')`.

### Travis Badge

[![Travis-CI Build Status] (replace with actual Travic badge)

(https://travis-ci.org/tybyers/DataX.svg?branch=master)](https://travis-ci.org/tybyers/DataX)


