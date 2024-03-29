# HardwareX 2023 - Replication package
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7897546.svg)](https://doi.org/10.5281/zenodo.7897546)

This repository contains the replication package of the paper published in HardwareX with the title **[ROBOTONT – Open-source and ROS-supported omnidirectional mobile robot for education and research](https://doi.org/10.1016/j.ohx.2023.e00436)**.

The repository contains a snapshot of Robotont's development that is coherent to ensure a workable set of mechanics, electronics, and software to replicate the state presented in the paper. However, we encourage everyone to access the latest state of development in each linked repository.

## How to cite this content
---
If the content in this repository is helping your research, please cite us as follows:

```
@article{robotont_hardwarex_2023,
  title={ROBOTONT – Open-source and ROS-supported omnidirectional mobile robot for education and research},
  author={Renno Raudmäe and Sandra Schumann and Veiko Vunder and Maarika Oidekivi and Madis Kaspar Nigol and Robert Valner and Houman Masnavi and Arun Kumar Singh and Alvo Aabloo and Karl Kruusamäe},
  journal = {HardwareX},
  volume = {14},
  pages = {e00436},
  year = {2023},
  issn = {2468-0672},
  doi = {https://doi.org/10.1016/j.ohx.2023.e00436},
  publisher={Elsevier}
}
```

## Overview of the replication package
---

This replication package is structured as follows:

```
  electronics/                               Production files for ROBOTONT gen2.1 printed circuit boards
    robotont-electronics-driver-board/
    robotont-electronics-nucleo-shield/
    robotont-electronics-power-management-board/
  firmware/                                  Firmware for ROBOTONT gen2.1 microcontroller
    robotont-firmware/
  mechanics/                                 Design files for manufacturing ROBOTONT gen2.1
    robotont-mechanics/
  software/                                  ROS Noetic software packages for ROBOTONT gen2.1
    robotont-setup/
    robotont_demos/
    robotont_description/
    robotont_driver/
    robotont_gazebo/
    robotont_laserscan_to_distance/
    robotont_msgs/
    robotont_navigation/
    robotont_nuc_description/
    robotont_support/
    robotont_webapp/
  robotont-2.1-assembly-instructions.pdf     Assembly instructions for ROBOTONT gen2.1
  robotont-2.1-full-system-bom.ods           Bill of materials for ROBOTONT gen2.1

```
