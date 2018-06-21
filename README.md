# Software developed by RIKEN R-CCS

RIKEN R-CCS ([http://www.r-ccs.riken.jp/en](http://www.r-ccs.riken.jp/en)) is a research center for computational sciences and computer science for simulations with supercomputers. Some software developed by RIKEN R-CCS are hosted by GitHub.  (RIKEN R-CCS is formerly named as RIKEN AICS, renamed in April 2018).

## Projects under GitHub

{% for repository in site.github.public_repositories %}
  * [{{repository.name}}]({{repository.html_url}}): {{repository.description}}
{% endfor %}
(Repositories include some small patches just to port open-source software to K computer).

Some projects have independent GitHub organizations (incomplete list):
* [Fiber Miniapp Suite](http://fiber-miniapp.github.io)
* [https://github.com/avr-aics-riken](https://github.com/avr-aics-riken)
* [https://github.com/pf-aics-riken](https://github.com/pf-aics-riken)
* [Evidence-Based performance Tuning (EBT-HPC)](https://github.com/ebt-hpc)
* [https://github.com/crest-cassia](https://github.com/crest-cassia)
* [XcalableMP Specification](https://github.com/XcalableMP/Specification)
* [Omni compiler](https://github.com/omni-compiler/omni-compiler)
* [Extrae](https://github.com/bsc-performance-tools/extrae) 

## Projects with special promotion pages in RIKEN R-CCS

Some projects have descriptions in RIKEN R-CCS "Software Ceter":
* [http://www.r-ccs.riken.jp/software_center](http://www.r-ccs.riken.jp/software_center)

## Incomplete list of software developed by RIKEN R-CSS

Software developed by RIKEN R-CCS are deployed on K computer, and they can be found in the portals of K computer.
This is a list of them.

|Name|Description
----|----
|<a href="https://www-sys-aics.riken.jp/releasedsoftware/ksoftware/carp/" target="_blank">Carp|Carp is software to parallelize computation for any possible combination of two records in dataset. The software users do not need to write any parallel program, but write just sequential programs. All parallelizing tasks are done by the Carp software.
|<a href="https://www-sys-aics.riken.jp/releasedsoftware/ksoftware/earth/" target="_blank">EARTH on K|EARTH on K is a derivative version of EARTH (Effective Aggregation Rounds with Throttling) optimization framework towards high performance MPI-IO. EARTH on K is optimized to achieve high performance MPI-IO using a local file system (LFS) of the K computer.
|<a href="https://www-sys-aics.riken.jp/releasedsoftware/ksoftware/pnetcdf/" target="_blank">NetCDF|NetCDF is a set of software libraries and self-describing, machine-independent data formats that supports the creation, access, and sharing of array-oriented scientific data. We provide NetCDF library and related libraries (HDF5, Parallel netCDF and Szip) on the K computer compute hosts and frontends.
|<a href="https://www-sys-aics.riken.jp/releasedsoftware/ksoftware/prdma/" target="_blank">PRDMA（Persistent Remote DMA）|The PRDMA library provides a fast implementation of MPI Persistent Communication primitives to reduce the communication latency and to improve the overlap between computation and communication over an RDMA-enabled interconnect.
|<a href="http://graal.ens-lyon.fr/MUMPS" target="_blank">MUMPS|MUMPS(MUltifrontal Massively Parallel sparse direct Solver) is a package for solving sparse linear systems using the direct method. MUMPS supports MPI parallel procedures.
|<a href="http://omni-compiler.org/" target="_blank">Omni XcalableMP|Omni XcalableMP is a compiler for a parallel programming language XcalableMP, which is a directive-based language extension for Fortran and C. Using Omni XcalableMP, you can develop parallel programs effectively.
|<a href="http://www.scalasca.org/start.html" target="_blank">Scalasca|Scalasca is a software tool that supports the performance optimization of parallel programs by measuring and analyzing their runtime behavior. The analysis identifies potential performance bottlenecks - in particular, those concerning communication and synchronization – and offers guidance in exploring their causes.
|<a href="/labs/lpnctrt/en/projects/eigenexa/" target="_blank">EigenExa|EigenExa is a high performance eigenvalue solver, which is developed as a successor of EigenK. It is tuned up on the K computer. As EigenK does, EigenExa also solves a standard eigenvalue problem for a dense real symmetric matrix, and it performs very fast even with large-scale parallel computations and small scale problems.
|<a href="http://ccse.jaea.go.jp/eng/index.html" target="_blank">EigenK|EigenK is an eigenvalue solver, which is developed to work on the K computer efficiently. EigenK solves a standard eigenvalue problem for a dense real symmetric matrix. EigenK performs large-scale parallel computation and small scale problem faster than the existing eigenvalue solvers do.
|<a href="/labs/lpnctrt/projects/kmath-random/" target="_blank">KMATH_RANDOM|A library of random number generator by the Mersenne Twister, a high-quality pseudorandom number generator, for a distributed parallel processing environment. Available for Fortran 90, C, and C++.
|<a href="https://github.com/ebt-hpc/cca" target="_blank">CCA/EBT(Code Comprehension Assistance for Evidence-Based performance Tuning)|For improving the performance of an application, we have to comprehend the application's source code. In order to facilitate comprehension of source code written in Fortran, this utility analyzes its syntactic/semantic structures and then provides outline views of loop-nests and call trees decorated with source code metrics.
|<a href="https://tools.bsc.es/extrae" target="_blank">Extrae|Extrae is the package devoted to generate Paraver trace-files for a post-mortem analysis MPI applications written in Fortran, C, or C++ can be analyzed in detail using the trace files with Paraver.
|Eclipse PTP for K and FX10 computers|This software is necessary for using Eclipse PTP IDE with K and FX10 computers. It consists of 2 packages:(1)<a href="https://github.com/pyotr777/EclipsePTP_Parallelnavi_TSC" target="_blank">Target System Configurationsnecessary for submitting jobs to K and FX10 computers,(2)<a href="https://github.com/pyotr777/LML4PJM" target="_blank">LML DA Driver for PJMto be installed on K and FX10 user home directory to enable Eclipse PTP monitoring feature.
|<a href="https://www.cs.uoregon.edu/research/tau/home.php" target="_blank">TAU|TAU Performance System is a portable profiling and tracing toolkit for performance analysis of parallel programs written in Fortran, C, C++. It supports performance instrumentation, measurement, analysis and visualization. Application profiles show the exclusive and inclusive time spent in each function, how many times each function was called, how many profiled functions did each function invoke, and what the mean inclusive time per call was. Application traces show when and where event occured in terms of the process that executed it and the location in the source code.
|<a href="http://super.para.media.kyoto-u.ac.jp/xcrypt/index.html" target="_blank">Xcrypt|Xcrypt is a scripting language that enables us to easily write a script to manage a number of concurrently running jobs. It provides a unified interface that handles differences in system interfaces of various supercomputers ; users do not need to learn each interface. Furthermore, Xcrypt has a mechanism that allows users to add various useful features as modules ; some important features are integrated in Xcrypt as standard modules.
|<a href="https://github.com/crest-cassia/oacis" target="_blank">OACIS(Organizing Assistant for Comprehensive and Interactive Simulations)|OACIS runs as a web server on Mac or Linux to manage simulation executions and their results. After a user sets simulation parameters, OACIS creates shell script files for these parameters and submits them to the specified remote hosts. After these jobs are finished, the results are automatically downloaded and stored in the specified directory.
|<a href="http://labs.aics.riken.jp/nakajimat_top/ntchem_e.html" target="_blank">NTChem|NTChem is a high-performance software package for the molecular electronic structure calculation for general purpose on the K computer. It is a comprehensive new software of ab initio quantum chemistry made in R-CCS from scratch. NTChem contains not only standard quantum chemistry approaches but also our own original approaches. NTChem is expected to be a useful tool in various computational studies for large and complicated molecular systems.*Web Page: Under construction
|<a href="http://www.r-ccs.riken.jp/labs/cms/DMRG/" target="_blank">2D-DMRG*|The 2D-DMRG is developed to study quantum lattice systems. The 2D-DMRG is optimized to perform high performance massively parallel computings on the K-computer. Although the DMRG method is used to study one-dimensional systems, the 2D-DMRG can be used for higher dimensional systems. Also, the 2D-DMRG can be employed to investigate an arbitrary shape of systems and many kinds of quantum lattice models. *Website is in Japanese
|<a href="http://www.r-ccs.riken.jp/labs/cbrt/" target="_blank">GENESIS|GENESIS is a high performance molecular dynamics and modeling software. It consists of two simulators, ATDYN and SPDYN. SPDYN shows high speed and good scalability on massively parallel computers. ATDYN is capable of multi-scale simulations using coarse grained models and all atom models. Generalized ensemble simulations including replica-exchange molecular dynamics and replica-exchange umbrella sampling methods are available.
|<a href="https://github.com/fdps/fdps" target="_blank">FDPS(Framework for Developing Particle Simulators)|FDPS is an application-development platform. It helps researchers to develop software for particle simulations which run efficiently on massively parallel computers such as K computer. By using FDPS, researchers without much experience in tuning or parallelization can develop applications which run efficiently on tens of thousands of nodes.
|<a href="http://scale.aics.riken.jp/index.html" target="_blank">SCALE|A Library for weather and climate simulations, and an atmospheric large-eddy simulation model using the library. These are developed with co-design by researchers of computational and computer sciences to achieve high performance in massive parallel computer systems.
|<a href="http://www.r-ccs.riken.jp/ungi/soft/kscope" target="_blank">K-scope|K-scope is a source code analysis tool with graphical user interface for Fortran 90 and FORTRAN 77, which visualizes program structures such as loop, branch and procedure call as bottleneck. By the K-scope, application performance engineer can understand overview of source codes for starters. (This software is Java application for Commodity-PC, not the K-computer.)
|Performance Analysis tool by once, "1PAtool"|This software is the tool on the K computer to display the results of the basic performance analysis and time breakdown analysis that are output as profile results by Precision PA visibility function.
|Waiting for the K|This tool calculates a waiting time of a job on the K computer.
