# Version 0.1-7, January 22, 2024

* Fixed Rd files to pass latest R CMD checks.
* Changed Maintainer's email address.

# Version 0.1-6, March 11, 2016

* Name matching was confused by diagnostic scale names
  for the confint method when fixed parameters were in the model.
  Method now use the reporting scale with an optional argument
  diagn_scale=FALSE by default. Sorting of names is now fixed.
  Reported by Cheyenne Gerdes (Missouri State Univ.).

# Version 0.1-5, Jan 14, 2016

* dcmle package updates led to errors when fitting models
  due to object coercion issues. This now fixed,
  and dcmle >= 0.3-0 version dependency introduced.

# Version 0.1-4, Jan 12, 2016

* R CMD check error fixed: dcmle no longer exports as.mcmc.list.
* NAMESPACE changes to satisfy R CMD check.

# Version 0.1-3, Nov 22, 2015

* Various fixes to satisfy R-devel checks.

# Version 0.1-2, May 19, 2014

* Fixed argument in growth model functions can be a list.
* Alternative prior specifications can be supplied via
  the fixed argument (but only numeric values stored in @fixed).
* Documentation updated.

# Version 0.1-1, August 23, 2012

* Songsparrow data added.
* Theta-Logistic, Theta-Logistic-D and Generalized
 Beverton-Holt growth models added.
* Testing and cleanup with minor modifications to the
  model selection facility.

# Version 0.1-0, June 28, 2012

* Package with model fitting and model selection capabilities
  is ready for 1st CRAN submission. Gompertz and Ricker
  growth models are implemented.
