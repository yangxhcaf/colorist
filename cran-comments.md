# Resubmission

- Removed "Tools for" from Title
- Removed back ticks from Description
- There are no references for the theoretical background. We are currently writing a paper on the methods and will add a reference to the package Description once the paper is published.

# colorist 0.1.0

- First CRAN release

## Test environments

- local OS X install, R 3.6.3
- OS X (travis-ci), R 3.6.2
- ubuntu 16.04 (travis-ci), R 3.6.3
- Windows (appveyor), R 3.6.3
- Rhub
  - Ubuntu Linux 16.04 LTS, R-release, GCC
  - Fedora Linux, R-devel, clang, gfortran
  - Windows Server 2008 R2 SP1, R-devel, 32/64 bit
- win-builder (devel and release)

## R CMD check results

0 errors | 0 warnings | 2 note

- This is a new release.
- Possibly mis-spelled words in DESCRIPTION. These words are correct: HCL, chroma, luminance
- This package is 1.8 MB when build, larger than a typical package because it contains 3 example datasets exhibiting the three types of data that can be visualized. This package is designed to visualize spatial data with high spatial and temporal resolution and we feel having good example datasets is critical to users of this package being able to explore its capabilities. The included example datasets are the smallest we could make them while still being realistic.