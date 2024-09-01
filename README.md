# <img src="https://github.com/EOS-OS/EOS/blob/main/images/EOS%401x.png" width="130" height="130" alt="EOS">

## Introduction

**EOS** is an embodied intelligence operating system release based on the dual-kernel real-time kernel [RROS](https://github.com/BUPT-OS/RROS).

## Usage

[Instructions on how to use the system go here.]

## Contributing

[Guidelines for contributing to the project go here.]

## Roadmap

1. **Estabiliing a package manager tool for the robot development**
   - [ ] A package image source based on the `Copr` platform to collect packages
   - [ ] A client for package management
     - [ ] **Kernel Layer**: Integrate core system libraries to ensure system stability and compatibility.
     - [ ] **EI Translator (Embodied Intelligence Translator)**: Convert kernel-layer libraries into internal libraries for the middleware layer, facilitating seamless integration across multiple system layers, including ROS/Dart.
     - [ ] **Middleware Layer:**
       - [ ] **ROS**: Provide middleware support for the Robot Operating System, enhancing automation and robotics development capabilities.
       - [ ] **Dora**: Offer advanced middleware support for distributed systems, increasing system scalability and flexibility.
2. **Use RROS kernel to enhance the realtime ability of robot development**
   - [ ] Realtime ability
     - [ ] Adapt ROS
     - [ ] Adapt Dora
     - [ ] Adapt Ethercat protocol
   - [ ] Adaptation and Optimization for Domestic Chips
     - [*] X86 Series
     - [*] ARM Series
     - [*] Loongarch (Works on the signal CPU core)
     - [ ] RISCV

5. **Optimization of the RROS (Rust Realtime) Kernel**
   - [ ] Deeply optimize EOS core components to ensure perfect compatibility between the RROS kernel and ROS2 and EtherCAT, enhancing real-time performance and system efficiency.

6. **Development of Upper Layer Applications Based on the RROS Kernel**
   - [ ] Provide a rich API to support application developers in fully leveraging the powerful features of the RROS kernel, accelerating application development and deployment.
