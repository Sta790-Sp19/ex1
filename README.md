Exercise 1 - Week 1
----------------------

### Task 0 - Setup

* Make sure you have a working VM via [Duke VCM](https://vcm.duke.edu), make sure to use a Plain VM with either RHEL 7 or Ubuntu 18.04.

* Install R and its dependencies on your VM.


### Task 1 - Install `sf`

* `sf` is an R package used for reading and working with spatial geometry data, it depends on a number of system libraries which 
  makes it difficult to install. Based on the feedback you get from `install.packages` attempt to get the package and all of its 
  dependencies installed correctly. You should be able to run `library(sf)` successfully after the install.
  
  * Hint - using multiple concurrent ssh sessions will let you keep your R session alive while you install system packages.

  * Hint - if the install error messages are not verbose enough the next place to check is the package's documentation and or website.

### Task 2 - Install `rjags`

* `rjags` should not need any introduction in this department, it depends on a system library called `jags`. Install this package 
  and any necessary depencies. You should be able to run `library(rjags)` successfully after the install.
  
  * Hint - `jags` is available as part of the package management system on Ubuntu, it is not RHEL - try getting it to work on both    
  distros.


