### Notice
This Perl version of BioNetFit is deprecated, but remains available for archival purposes. The new version of BioNetFit is available at https://github.com/lanl/PyBNF.

### BioNetFit
BioNetFit is a general-purpose fitting program for rule-based models written in the BioNetGen language. 

### Features
 * BioNetFit implements a genetic algorithm for optimization
 * BioNetFit can be used on a stand-alone computer or a Linux-based cluster
 * BioNetFit is compatible with the various simulation capabilities provided by BioNetGen (generate-first deterministic, stochastic and hybrid methods and network-free stochastic methods) can be used with BioNetFit. 
 * BioNetFit can perform a global fit, meaning that it can consider multiple datasets in the course of a fitting run. Preprocessing of data (for example, normalization of the average of the measurement values in each dataset) is advised when considering multiple datasets. 
 * BioNetFit can consider steady-state dose-response data and/or time-series data. 
 * BioNetFit supports bootstrapping to characterize parameter confidence intervals (not fully tested, use at your own peril)
   * the parameter `bootstrap_chi` is the maximum objective function value (numeric) required for accepting a particular bootstrapped fitting run
   * the parameter `bootstrap` takes an integer defining the number of bootstrapped fitting runs to perform

### Support
A user manual is present in the repository

Additional support is generally available by contacting the [BioNetGen developers](mailto:bionetgen.help@gmail.com)
