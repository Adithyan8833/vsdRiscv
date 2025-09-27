

# 🚀 Day 1: Introduction to verilog RTL Design and Synthesis

### 🧠 **1.Open source Simulator iverilog**



### 🧠 **2.Lab using iverilog and GTKwave**

### Running My Simulation
```shell
# To compile
iverilog good_mux.v tb_good_mux.v

# To Run
./a.out

# To view the waveform in GTKWave
gtkwave tb_good_mux.vcd
```
#### GTKWAVE

<img width="958" height="733" alt="gtkwave" src="https://github.com/user-attachments/assets/b3fe8f33-c5b1-456e-a9af-cf4e9493cb1d" />




### 🧠 **3.Yosys and logic synthesis**

### 🧠 **4.Open source Simulator iverilog**
#### Commands
     yosys
     read_liberty -lib ../my_lib/lib/sky130_fd_sc_hd__tt_025c_1v80.lib
     read_verilog good_mux.v
     synth -top good_mux
     abc -liberty ../my_lib/lib/sky130_fd_sc_hd__tt_025c_1v80.lib
     show
<img width="940" height="539" alt="Screenshot from 2025-09-27 21-17-11" src="https://github.com/user-attachments/assets/04a3721f-561e-4a16-ae8c-86d72c2b09a8" />

### 🧠 **5.Lab using Yosys Sky 130 PDKs**



