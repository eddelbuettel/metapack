## Resubmission
This is a resubmission. In this version I have:

* Removed ListBuilder.h to fix the rchk errors, which were related to protected SEXP objects
* Changed all 'return Listbuilder()' in the source files to 'Rcpp::List::create(...)'
* Added DOI information for the network meta-regression model in the DESCRIPTION file

## Test environments
* local x64 Windows 10 (Intel(R) Core(TM) i7-8700K CPU @ 3.70GHz) R version 4.0.2 
* local macOS Big Sur 11.1 R 4.0.3
* ubuntu 20.04 (release and devel on R CMD check)
* ubuntu 16.04 (on travis-ci), R 4.0.2
* win-builder (devel and release)

## R CMD check results
There were no ERRORs, or WARNINGs.

There was 1 NOTE:

* checking installed package size ... NOTE
  installed size is  5.8Mb
  sub-directories of 1Mb or more:
    libs   5.5Mb


## Downstream dependencies
There are no downstream dependencies for this package.

