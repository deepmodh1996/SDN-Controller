# SDN-Controller

This is Software Defined Network controller in VHDL which takes real-time data to send and network
connection information periodically to generate optimum next-hop at each router for every packet. It is the major project in Digital Logic Design course offered by Prof. Supratik Chakraborty.

It is hardware implementable generic system, robust to change in network connection that can prioritise
the packets of higher service levels.

See report for detail information.
Note : controller implements more functionalities than suggested in abstract.

### How to run code :

You must have Xilinx installed.

You can download Xilinx from [here](http://www.xilinx.com/support/documentation/sw_manuals/xilinx14_1/iil.pdf) or go to official Downloads - Xilinx website.

#### Run : 
 1. Extract zip file.
 2. Open xilinx project in extracted folder by double clicking it.
 3. Synthesize code using Radiance_top.vhd. It can take some time. ( Radiance is name of team )
 4. Stimulate the code.
 
If you want to change the traffic or graph matrix, just modify testbench and stimulate again.
