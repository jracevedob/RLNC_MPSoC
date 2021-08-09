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
We are going to be really content and encouraged if you can cite our scientific works in your own publications 
and distribute our works among your research collaborators and colleagues.

```
@incollection{ACEVEDO2020413,
title = {Chapter 26 - Integrating software-defined radios},
editor = {Frank H.P. Fitzek and Fabrizio Granelli and Patrick Seeling},
booktitle = {Computing in Communication Networks},
publisher = {Academic Press},
pages = {413-427},
year = {2020},
isbn = {978-0-12-820488-7},
doi = {https://doi.org/10.1016/B978-0-12-820488-7.00042-6},
url = {https://www.sciencedirect.com/science/article/pii/B9780128204887000426},
author = {Javier Acevedo and Marian Ulbricht and Dongho You},
keywords = {Wireless communications, Software-defined radio, Universal software radio peripheral},
abstract = {In this chapter, we extend the emulator ComNetsEmu used throughout the book by implementing foundational wireless communication applications using Software-Defined Radio (SDR) devices, particularly Universal Software Radio Peripherals (USRPs). After an introduction of SDR and some common implmentations, we provide practical hands-on examples. Through a bridge network located between two Docker containers and the emulator, two basic applications are flashed into the SDR hardware to transfer data using OFDM modulation. This deployment allows us to demonstrate how softwarization leverages the integration of emerging and current technologies applied to communication networks.}
}
```

## Contributing

This project exists thanks to all people who contribute.
The [list](./CONTRIBUTORS) of all contributors.

## References

### Internet sources
https://kb.ettus.com/Building_and_Installing_the_USRP_Open-Source_Toolchain_(UHD_and_GNU_Radio)_on_Linux

### Academic and industry sources

## Contact

* **Javier Acevedo** - *Contributor and Project Maintainer* javier.acevedo@tu-dresden.de


## License

This project is licensed under the [MIT license](./LICENSE).

## News

* **Hardware acceleration** - *Through RFSoC, we accelerate the execution of the GNU Radio modules*

