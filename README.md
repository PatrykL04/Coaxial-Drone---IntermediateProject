# Coaxial-Drone---IntermediateProject

An aerodynamic, 3D-printable ducted fan drone featuring an active thrust vectoring system. This project utilizes a 4-vane cross configuration for precise Pitch, Roll, and Yaw control, governed by ArduPilot.

## 🚀 Project Overview

Unlike traditional quadcopters, this drone operates as a "SingleCopter". The design relies on a modular outer duct and a central core that houses all electronics and the power supply. The geometry is optimized to ensure a perfect Center of Gravity and stable airflow.

### Key Design Features:
* **Modular Central Core:** Houses the flight controller, receiver, and battery, topped with an aerodynamic dome for the magnetometer.
* **Active Thrust Vectoring:** Four independently controlled paddles at the bottom of the duct provide full 3-axis control.
* **Optimized Airflow:** Strategic placement of fixed stators and control flaps minimizes turbulence and maximizes control authority.
* **3D Printing Friendly:** Core shapes are optimized for standard FDM 3D printing, utilizing the 45-degree overhang rule to minimize supports.

## 🛠️ Hardware Specifications

* **Flight Controller:** Matek F405-WMN.
* **Motors:** 2x EMAX MT1806 2280kV (Coaxial setup).
* **ESCs:** 2x 15A.
* **Battery:** Tattu Funfly 1300mAh 11.1V 100C 3S1P.
* **Servos:** 4x MG90S (Metal gear).
* **Magnetometer:** QMC5883L.
* **Receiver:** FlySky FS-X6B.
* **Firmware:** ArduPilot 4.x (Target: `MatekF405-TE` / Frame Class: `SingleCopter`).
