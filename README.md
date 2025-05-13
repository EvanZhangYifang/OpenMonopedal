# OpenMonopedal

**An open-source monopedal robot leg with passive elastic actuation (PEA) for load compensation and a 3D-printed cycloidal actuator**

This repository contains the open-source CAD files and documentation for a monopedal robot leg that implements a **novel passive parallel elastic actuation (PEA) principle** for torque compensation. This system has been presented in the research publication:

> **"A Novel Passive Parallel Elastic Actuation Principle for Load Compensation in Legged Robots"**  
> *Y. Zhang, J. Jiang, and N. G. Tsagarakis*  
> IEEE Robotics and Automation Letters, vol. 9, no. 10, pp. 8881–8888, Oct. 2024  
> [DOI: 10.1109/LRA.2024.3448131](https://doi.org/10.1109/LRA.2024.3448131)

---

## 🔍 Abstract

This work introduces a novel **parallel elastic actuation (PEA)** principle designed to provide **torque compensation** for legged robots. Unlike existing solutions, the proposed concept combines a **nitrogen (N₂) gas spring** with a **custom cam roller module**, enabling highly customizable torque compensation profiles tailored to specific leg joints.

An **optimization-based design approach** determines gas spring specifications and cam geometry to best match a target compensation profile. This mechanism was implemented and experimentally validated in the **knee joint** of a **two-degree-of-freedom (DoF)** monopedal robot actuated by **3D-printed cycloidal gear drives**.

**Key results** include:
- Effective generation of desired compensation torque profiles
- **71.92% reduction** in additional energy consumption from payload forces
- A **compact**, **easy-to-integrate**, and **customizable** solution for nonlinear torque compensation

---

## 📦 Features

- **Passive load compensation** using gas spring and cam mechanism
- Customizable **nonlinear torque profiles**
- **3D-printed cycloidal actuators**
- Optimized using an **analytical and simulation-based pipeline**
- Designed for **lightweight legged robot applications**

---

## 🛠️ Getting Started

To explore or edit the mechanical design:

1. Install **PTC Creo 9.0** or newer.
2. Open the main assembly file:  
monopedal_asm.asm.2


---

![Monopedal Assembly](https://github.com/user-attachments/assets/ce782c3d-0360-489f-8c4f-20c11978af90)

---

## 📖 Citation

If you use this repository in your research, please cite:

```text
Y. Zhang, J. Jiang and N. G. Tsagarakis, 
"A Novel Passive Parallel Elastic Actuation Principle for Load Compensation in Legged Robots," 
IEEE Robotics and Automation Letters, vol. 9, no. 10, pp. 8881–8888, Oct. 2024, 
doi: 10.1109/LRA.2024.3448131
