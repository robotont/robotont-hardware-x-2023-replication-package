# HardwareX 2023 - Replication package

This repository contains the replication package of the paper submitted to HardwareX with the title **ROBOTONT – open-source and ROS-supported omnidirectional mobile robot for education and research**.

The repository contains a snapshot of Robotont's development that is coherent to ensure a workable set of mechanics, electronics, and software to replicate the state presented in the paper. However, we encourage everyone to access the latest state of development in each linked repository.


## How to cite this content
---
If the content in this repository is helping your research, please cite us as follows:

```
@article{robotont_hardwarex_2023,
  title={ROBOTONT – open-source and ROS-supported omnidirectional mobile robot for education and research},
  author={Renno Raudmäe and Sandra Schumann and Veiko Vunder and Maarika Oidekivi and Madis Kaspar Nigol and Robert Valner and Houman Masnavi and Arun Kumar Singh and Alvo Aabloo and Karl Kruusamäe},
  journal = {HardwareX},
  year = {2023},
  doi={tbd},
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
  firmware/                                  Firmware for ROBOTONT gen2.1 driver
    robotont-firmware/
  mechanics/                                 Design files for manufacturing ROBOTONT gen2.1
    robotont-mechanics/
  software/                                  ROS Noetic software packages for ROBOTONT gen2.1
    robotont_demos/
    robotont_description/
    robotont_driver/
    robotont_gazebo/
    robotont_laserscan_to_distance/
    robotont_msgs/
    robotont_navigation/
    robotont_nuc_description/
    robotont-setup/
    robotont_support/
    robotont_webapp/
  robotont-2.1-assembly-instructions.pdf     Assembly instructions for ROBOTONT gen2.1
  robotont-2.1-full-system-bom.ods           Bill of materials for ROBOTONT gen2.1

```
