# vsdRiscv
![Platform](https://img.shields.io/badge/Platform-VirtualBox-orange)
![Toolchain](https://img.shields.io/badge/Toolchain-RISC--V-blue)
![Status](https://img.shields.io/badge/Status-✅%20Complete-brightgreen)
![Environment](https://img.shields.io/badge/Environment-Ubuntu%2022.04-yellow)

# 🚀 Week 0: VLSI System Design (VSD) Program Foundation & Tool Installationn

## 🎯 **System Check**


| **Specification** 💻    | **Details** 📋          |
|-----------------------|-----------------------|
| **Operating System** 🐧  | Ubuntu 20.04+         |
| **RAM** 💾               | 6GB                   |
| **Storage** 💿           | 50GB HDD              |
| **vCPUs** ⚡             | 4                     |

## 🎯 **Tool check**

### 🧠 **1. Yosys**
Converts RTL code into gate-level representations.
#### Yosys install
     $ sudo apt-get update 
     $ git clone https://github.com/YosysHQ/yosys.git 
     $ cd yosys 
     $ sudo apt install make (If make is not installed please install it)  
     $ sudo apt-get install build-essential clang bison flex \ 
       libreadline-dev gawk tcl-dev libffi-dev git \ 
       graphviz xdot pkg-config python3 libboost-system-dev \ 
       libboost-python-dev libboost-filesystem-dev zlib1g-dev 
     $ make config-gcc 
     $ make  
     $ sudo make install 
## 📷 **Installation Verification**

<img width="730" height="530" alt="yosys1" src="https://github.com/user-attachments/assets/81ea9474-fc72-4a75-9bbd-4395604a52a6" />

<img width="733" height="295" alt="yosys2" src="https://github.com/user-attachments/assets/8c15bc94-2e89-4320-9246-38e01951ac57" />

<img width="673" height="70" alt="yosys3" src="https://github.com/user-attachments/assets/bf4c2e9f-b2a7-44b3-91ed-72b34b003e62" />


### 🧠 **2. Iverilog**
Compiles and simulates Verilog designs for functional verification
#### Iverilog install
      sudo apt-get update 
      sudo apt-get install iverilog
## 📷 **Installation Verification**

<img width="745" height="383" alt="iverilog1" src="https://github.com/user-attachments/assets/812cfd0c-f4ad-4e4d-bf4b-c83443c539dc" />

<img width="738" height="365" alt="iverilog2" src="https://github.com/user-attachments/assets/db3f0adc-902d-43e7-ae5d-2121bdb27e4b" />

### 🧠 **3. gtkwave**
Analyzes and visualizes simulation waveforms for debugging
#### gtkwave install
     sudo apt-get update 
     sudo apt install gtkwave
## 📷 **Installation Verification**

<img width="733" height="576" alt="gtkwave1" src="https://github.com/user-attachments/assets/fd33b48d-3127-4d63-9b47-33fe9b83c121" />

<img width="738" height="111" alt="gtkwave2" src="https://github.com/user-attachments/assets/3340a837-41dd-4fc7-8b9e-dea9a36454d3" />

## 📷 **Installation Verification of all**
Just Run Blink.v(led blink verilog code)and testbench also opened the gtkwave

<img width="732" height="317" alt="test1" src="https://github.com/user-attachments/assets/1da7ca45-4542-46d7-af8e-404b12bb0307" />



<img width="732" height="570" alt="gtkwavetest2" src="https://github.com/user-attachments/assets/c99da14c-0728-4c93-b5f7-90f1f03c5d2f" />



      


    
