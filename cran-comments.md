## Note
* fixes ASAN error by not including testthat.h
* uses configure script to determine C++11 compatibility

## Test environments
* Ubuntu 17.04 R 3.4.0, clang 4.0
* Ubuntu 12.04 (on travis-ci) R-devel, gcc
* Debian testing/unstable in docker with R-devel, ASAN+UBSAN GCC 7.1, clang 4.0, trunk

# R CMD check results

There is one note:

* checking installed package size ... NOTE
  installed size is 13.0Mb
  sub-directories of 1Mb or more:
    R      1.5Mb
    data   1.3Mb
    doc    2.1Mb
    libs   7.6Mb
