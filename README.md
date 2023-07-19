# Datapath_controller_design
The hardware way of thinking while designing (in verilog) a complex digital circuit
In a complex digital system, the hardware is typically partitioned into two parts:
a) Data Path, which consist of the functional units where all computations 
are carried out.
Typically consist of registers, multiplexers, bus, adders, multipliers, counters, and other functional blocks.

b) Control Path, which implements a finite-state machine and provides control signals to the data path in proper sequence.
In response to the control signals, various operations are carried out by the data path.
Also takes inputs from the data path regarding various status information.

Consider an algorithm, Multiplication using repeated addition, Assuming B is non-zero.
We identify the functional blocks required in the data path, and the corresponding control signals.
then we design the FSM to implement the multiplication algorithm using the data path.


![image](https://github.com/akshayrajMR95/Datapath_controller_design/assets/101858111/4e5ba01b-101b-4bc0-b72f-3312cca288b9)







The overall design architecture is given below for our purpose

![image](https://github.com/akshayrajMR95/Datapath_controller_design/assets/101858111/69190261-808b-4c93-8c0c-4c1e571ad256)









![image](https://github.com/akshayrajMR95/Datapath_controller_design/assets/101858111/1ff2853d-dd45-45e9-93d1-f452c76d9a7d)








For desining a controll path the overall design is divided into different stages and the stages are assigned to different states and 
the state digram is designed accordingly.

![image](https://github.com/akshayrajMR95/Datapath_controller_design/assets/101858111/1a4afeff-c9ac-4db1-bbc3-da13f4d3543e)


