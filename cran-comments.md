## Re-Re-Re Submission
* Shortened title to less than 65 characters
* replaced all occurrences of F/T with FALSE/TRUE

## Re-Re Submission 
Fixed Spelling
* highlightling   --> highlighting
* drag'n drop --> drag and drop

## Re-Submission
* Changed Title in DESCRIPTION to title case
* All package names in DESCRIPTION are now single quoted

## Test environments
* local Win64, R 3.6.1 (including visual check of htmlwidget)
* local OS64, R 3.6.1 (including visual check of htmlwidget)
* local x86_64-pc-linux-gnu, R 3.6.1 (including visual check of htmlwidget)
* ubuntu 14.04 (on travis-ci), R 3.6.1
* x86_64-w64-mingw32/x64 (on appveyor), R 3.6.1
* Ubuntu Linux 16.04 LTS, R-release, GCC (R-Hub)
* Fedora Linux, R-devel, clang, gfo (R-Hub)
  - PREPERROR `ModelMetrics` (`caret` dependency) not available
* Windows Server 2008 R2 SP1, R-devel, 32/64 bit (R-Hub)
* Ubuntu Linux 16.04 LTS, R-release, GCC (R-Hub)
* Winbuilder Devel
* Winbuilder Release

## R CMD check results

0 errors | 0 warnings | 1 note

* This is a new release.


## Comment on ERRORS
Some build systems give an error due to some dependency that is not available all of which are core packages of the R ecosystem and are well-maintained. I assume these problems for those systems will fix themselves in the future.