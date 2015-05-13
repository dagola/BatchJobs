# BatchJobs

[![Build Status](https://travis-ci.org/tudo-r/BatchJobs.png)](https://travis-ci.org/tudo-r/BatchJobs)
[![Build status](https://ci.appveyor.com/api/projects/status/pkcy60csbp8k1ms9/branch/master?svg=true)](https://ci.appveyor.com/project/mllg/batchjobs/branch/master)

Provides Map, Reduce and Filter variants to generate jobs on batch computing systems like PBS/Torque, LSF and Sun Grid Engine. Multicore and SSH systems are also supported.

* Offical CRAN release site:
  http://cran.r-project.org/web/packages/BatchJobs/

* R Documentation in HTML:
  http://www.rdocumentation.org/packages/BatchJobs

* Run this in R to install the current GitHub version:
  ```splus
  devtools::install_github("tudo-r/BatchJobs")
  ```

* [Further installation instructions](https://github.com/tudo-r/PackagesInfo/wiki/Installation-Information)


## Core features
* Create, submit and control [R](http://www.r-project.org/) jobs on batch systems
* Provides the functional programming tools Map, Reduce and Filter to operate on the cluster
* Supported systems include Torque/PBS, SGE, SLURM and LSF
* Support for makeshift SSH clusters and local (multicore) execution
* Convenient collection and aggregation of results
* Further Map and Reduce results from previous jobs as batch jobs
* Optional mail sending using [sendmailR](http://cran.r-project.org/web/packages/sendmailR) after job completion
* Query status of jobs and display log files inside R
* Possibility to write your own simple cluster interface if your architecture is not supported
* [BatchExperiments](https://github.com/tudo-r/Batchexperiments) extends this package with functionality required for comprehensive computer experiments and simulation studies.


## Configuration
A fresh installation defaults to a local execution mode.
Proceed to [Configuration](../../wiki/Configuration) to set up cluster execution.
The package also allows a few R options to be set, see [here](http://www.rdocumentation.org/packages/BatchJobs/functions/BatchJobs).

## Documentation
Probably the best way to get started in 5 minutes is to read Henrik Bengtsson [intro slides](http://goo.gl/s1eqBz).
If you have more time, read our [technical report](http://sfb876.tu-dortmund.de/PublicPublicationFiles/bischl_etal_2012a.pdf).
For more detailed information on the functions consult the [R documentation](http://www.rdocumentation.org/packages/BatchJobs)
We also provide a [FAQ](../../wiki/FAQ) in our [wiki](../../wiki).

We also have a [mailing list](http://groups.google.com/group/batchjobs).
