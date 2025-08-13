# EPX Portabel R BINARY LINUX

This repositor contains the R bas environment for the EPX Classifier Desktop Tool. It is a public repository for the the epx-r-installer to fetch the clean R environment for installing epx packages and its dependencies.


- Current R version: 4.2

### Reference ###


This repo is derived from: https://github.com/selkamand/r-portable-mac which includes the file R-Portable-Mac/bin/R that tells R to use local paths  (incl. the local libraries).


### How do I get set up? ###

1. Download desired release, unzip, then run R using r-portable-mac/bin/R
2. Install any packages you want with .libpath() (will install to r-portable-mac/library)

#### Changing Version of R ####
1. Backup r-portable-mac/bin/R
2. Delete everything in repo
3. Copy-Paste the Resources/ folder of any standard R installation into the r-portable-mac folder
3. Replace r-portable-mac/bin/R with the backed up version (tells R to use local paths)

#### Maintainer ####
Heidelberg Epignostix GmbH