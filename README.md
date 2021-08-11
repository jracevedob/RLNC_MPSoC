<p align="center">
<img alt="fast_Optics" src="https://github.com/jracevedob/RLNC_MPSoC/blob/main/Logo/fast.png" width="800">
</p>


[![MIT Licensed](https://img.shields.io/github/license/jracevedob/RLNC_MPSoC)](https://github.com/jracevedob/RLNC_MPSoC/blob/main/LICENSE)
[![Build Status](https://github.com//jracevedob/RLNC_MPSoC/actions/workflows/blank.yml/badge.svg)](https://github.com//jracevedob/RLNC_MPSoC/actions)
[![Documentation Status](https://readthedocs.org/projects/post-shannon-sdr/badge/?version=latest)](https://post-shannon-sdr.readthedocs.io/en/latest/?badge=latest)
[![Github All Releases](https://img.shields.io/github/downloads/jracevedob/RLNC_MPSoC/total.svg)]()

# RLNC_MPSoC
This directory contains the source code for implementing Random Linear Network Coding (RLNC) into Multi-Processor System-on-Chips (MPSoC). By exploiting data vectorization, we obtained latency and throughputs gains during the matrix multiplication operations. Therefore, we envision this implementation as the first real processor design for secure data wireless transmission in lossy media. 


## Overview

In this repository, you will find the source code and data blocks for implementing different types of digital transmission in GNURadio.
For this test, the Ettus Research N310 SDR was under use and the data analysis was performed using Python, C and C++. For more information about the developing hardware, please refer to the vendor [Website](https://kb.ettus.com/N300/N310)

# Table of Contents

## Quick Start
The implementation of this 
### Driver and Software Installation
The installation of GNURadio is taken directly for the official Ettus Research website under the following [Link](
https://kb.ettus.com/Building_and_Installing_the_USRP_Open-Source_Toolchain_(UHD_and_GNU_Radio)_on_Linux)
In our case, we have done the installation in an Ubuntu 18.04 system. For a more detailed and step-by-step description of the setup,
please refer to the [Installation](./Installation) repository.

### Examples

Some examples about the simulation of different modulation schemes is provided
### Implementation


## Citations

Currently, we are working in the writing of a publication where we are going to condense all the results and findings of this project. The ethernet communication is under development following this reference:

We are going to be really content and encouraged if you can cite our scientific works in your own publications 
and distribute our works among your research collaborators and colleagues.

```
@Article{Acevedo2021,
AUTHOR = {Acevedo, Javier and Sabouri, Shahryar  and Shen, Shiwei and Dietrich, Marco and Kambiz, Jamshidi and Fitzek, Frank H. P. },
TITLE = {Blink: Ultrafast Optical Ethernet Communication using Multi-processor System-on-Chip},
JOURNAL = {Electronics},
VOLUME = {},
YEAR = {2021},
NUMBER = {},
ARTICLE-NUMBER = {180},
URL = {},
ISSN = {},
ABSTRACT = {}
}
```

## Contributing

This project exists thanks to all people who contribute.
The [list](./CONTRIBUTORS) of all contributors.

Please refer to the following [Link](https://de.fast-zwanzig20.de/) to get access to more detailed information about the project.

## Contact

* **Javier Acevedo** - *Contributor and Project Maintainer* javier.acevedo@tu-dresden.de

## License

This project is licensed under the [MIT license](./LICENSE).

## Documentation

### Networking
Vendor documentation [Link](https://xilinx-wiki.atlassian.net/wiki/spaces/A/pages/862912682/Networking+in+QEMU)

### Hardware-Software Codesign

### Driver integration

## News

* **09.08.2021** - *First release of the fastOptics repository*
* **10.08.2021** - *Hardware modules for the communication between the PS and PL released*
* **14.08.2021** - *Hardware-Software integration*

