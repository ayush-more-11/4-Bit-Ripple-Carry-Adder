# 4-Bit-Ripple-Carry-Adder
Design and simulation of 4 Bit Ripple Carry Adder using Verilog HDL, implemented with Dataflow and Behavioral Modelling, full adder instantiation modules and a verified testbench.


# Module Instantiation In Verilog

Module is basic building block in Verilog where we can describe any hardware block. When design is very big or complex it is not easy to describe entire hardware block in a module. Instead of describing entire hardware in a single modlue, we can break the hardware into smaller modules and we can instantiate any module in out main module.

First of all your main module and sub-module should be in same path/folder. You can instntiate sub-module in main module, to do this write sub-module name inside the main module followed by a unique instance name.
