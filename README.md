# <img src="https://github.com/EOS-OS/EOS/blob/main/images/EOS%401x.png" width="130" height="130" alt="EOS">

## Introduction

**EOS** is an embodied intelligence operating system release based on the dual-kernel real-time kernel [RROS](https://github.com/BUPT-OS/RROS).
It aims to build **an easy-to-use platform to collect all the software needed to create an intelligent robot application**.
Specifically, there are three important steps:
   - Build a robot package manager to collect related libraries/framworks/algorithms
   - Improve the RROS ability in the robot development
   - Optimize the package performance in the package platform

## Usage

[Instructions on how to use the system go here.]

## Contributing

[Guidelines for contributing to the project go here.]

## Where you can find us

TODO

## Who are we

We are a group of robotic developers from Research institutes, Schools, and robotics enterprises.
We hope `EOS` can unite the strength from different aspects to accelerate robot development and shorten the communication path between developers and end users.

## Roadmap

1. **Estabiliing a package manager tool for the robot development**
   - [ ] A package image source
   - [ ] A client for package management
     - [ ] **Kernel Layer**: Integrate core system libraries to ensure system stability and compatibility.
        - [ ] A platform based on the `Copr` to collect packages
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
3. **Development of upper-layer applications based on the RROS kernel**
   - [ ] Provide a rich API to support application developers in fully leveraging the powerful features of the RROS kernel, accelerating application development and deployment.
   - [ ] Accelerate the applications with the RROS APIS.
