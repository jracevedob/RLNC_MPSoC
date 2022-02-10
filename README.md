<p align="center">
<img alt="fast_Optics" src="https://github.com/jracevedob/RLNC_MPSoC/blob/main/Logo/fast.png" width="800">
</p>


[![MIT Licensed](https://img.shields.io/github/license/jracevedob/RLNC_MPSoC)](https://github.com/jracevedob/RLNC_MPSoC/blob/main/LICENSE)
[![Build Status](https://github.com//jracevedob/RLNC_MPSoC/actions/workflows/blank.yml/badge.svg)](https://github.com//jracevedob/RLNC_MPSoC/actions)
[![Documentation Status](https://readthedocs.org/projects/post-shannon-sdr/badge/?version=latest)](https://post-shannon-sdr.readthedocs.io/en/latest/?badge=latest)
[![Github All Releases](https://img.shields.io/github/downloads/jracevedob/RLNC_MPSoC/total.svg)]()

# RLNC in Xilinx's MPSoC
This directory contains the source code for implementing Random Linear Network Coding (RLNC) into Multi-Processor System-on-Chips (MPSoC). By exploiting data vectorization, we obtained latency and throughputs gains during the matrix multiplication operations. Therefore, we envision this implementation as the first real processor design for secure data wireless transmission in lossy media. 


## Overview

# Table of Contents

## Quick Start
The implementation of this hardware-software codesign finds itself in a verification stage. A new release will be available soon.

### Hardware setup

### Software development

### OpenCL integration

### Results


## Citations

Currently, we are working in the writing of a publication where we are going to condense all the results and findings of this project. The ethernet communication is under development following this reference:

https://github.com/jracevedob/MPSoC_Networking

We are going to be really content and encouraged if you can cite our scientific work in your own publications 
and distribute our work among your research collaborators and colleagues.

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

* **09.08.2021** - *First release of the Random Linear Network Coding based on Kodo repository*
* **10.08.2021** - *Integration of OpenCL C++ code for RLNC with the Multi-processor System-on-Chip*
* **14.08.2021** - *Software development of the RLNC-kodo library*
* **10.02.2022** - *Migration to private repository for testing.*


## Acknowledgement

The project underlying this publication was supported by the Federal Ministry of Education and Research of Germany (BMBF) within the programme “Zwanzig20 – Partnership for Innovation” as part of the project consortium “fast” (funding reference number 03ZZ0532D).
