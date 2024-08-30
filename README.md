# EOS
![logo](https://github.com/EOS-OS/EOS/blob/main/images/EOS%401x.png)

## Introduction

**EOS** is an embodied intelligence operating system based on [a dual-kernel real-time operating system](https://github.com/BUPT-OS/RROS).

## Usage

[Instructions on how to use the system go here.]

## Contributing

[Guidelines for contributing to the project go here.]

## Roadmap

1. **Development of the Operating System Distribution and Management Platform**
   - [ ] **Package Management Architecture:**
     - [ ] **Kernel Layer**: Integrate core system libraries to ensure system stability and compatibility.
     - [ ] **EI Translator (Embodied Intelligence Translator)**: Convert kernel-layer libraries into internal libraries for the middleware layer, facilitating seamless integration across multiple system layers, including ROS/Dart.
     - [ ] **Middleware Layer:**
       - [ ] **ROS**: Provide middleware support for the Robot Operating System, enhancing automation and robotics development capabilities.
       - [ ] **Dora**: Offer advanced middleware support for distributed systems, increasing system scalability and flexibility.
   - [ ] **Adaptation and Optimization for Domestic Chips:**
     - [ ] RISCV
     - [ ] Loongarch
     - [ ] **X86/ARM Series**

2. **Optimization of the RROS (Rust Realtime) Kernel**
   - [ ] Deeply optimize EOS core components to ensure perfect compatibility between the RROS kernel and ROS2 and EtherCAT, enhancing real-time performance and system efficiency.

3. **Development of Upper Layer Applications Based on the RROS Kernel**
   - [ ] Provide a rich API to support application developers in fully leveraging the powerful features of the RROS kernel, accelerating application development and deployment.
