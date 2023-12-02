# Software developed by RIKEN R-CCS

[RIKEN R-CCS](http://www.r-ccs.riken.jp/en) is a research center for computational sciences and computer science for simulations with supercomputers, and it hosts [Fugaku supercomputer](https://www.r-ccs.riken.jp/en/fugaku/). (RIKEN R-CCS is formerly named RIKEN AICS, renamed in April 2018).  R-CCS distributes developed software as open source software.

## R-CCS Software Ceter

[R-CCS Software Center](https://www.r-ccs.riken.jp/software_center/) presents special promotion pages for distinguished software.  They are currently:

* [FrontFlow/red-HPC](https://www.r-ccs.riken.jp/software_center/software/frontflow-red-hpc/overview/): General-purpose thermal fluid modeling software for analyzing large flow fields with complicated geometries, like those arising in studies of gas turbines or automobile aerodynamics.
* [OACIS](https://www.r-ccs.riken.jp/software_center/software/oacis/overview/): Job management software for large scale simulations.
* [NTChem](https://www.r-ccs.riken.jp/software_center/software/ntchem/overview/): Comprehensive software for ab initio quantum chemistry calculations of large and complicated molecular systems.
* [SCALE](https://www.r-ccs.riken.jp/software_center/software/scale/overview/): Basic library for the analysis and simulation of the climate system of the Earth and planets.
* [GENESIS](https://www.r-ccs.riken.jp/software_center/software/genesis/overview/): Molecular dynamics and modeling software for biomolecular systems such as proteins, lipids, glycans, and their complexes.

## Projects under GitHub.com

Projects distribute their software in GitHub.com organizations (the list is incomplete):

* [Fiber Miniapp Suite](http://fiber-miniapp.github.io)
* [https://github.com/avr-aics-riken](https://github.com/avr-aics-riken)
* [Evidence-Based performance Tuning (EBT-HPC)](https://github.com/ebt-hpc)
* [https://github.com/crest-cassia](https://github.com/crest-cassia)
* [XcalableMP Specification](https://github.com/XcalableMP/Specification)
* [Omni compiler](https://github.com/omni-compiler/omni-compiler)
* [Extrae](https://github.com/bsc-performance-tools/extrae) 

Other projects distribute their software in a common organization at
[https://github.com/RIKEN-RCCS/](https://github.com/RIKEN-RCCS/):

{% for repository in site.github.public_repositories %}
* [{{repository.name}}]({{repository.html_url}}) ☆{{repository.stargazers_count}}: {{repository.description}}
{% endfor %}
