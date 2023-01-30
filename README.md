# FIR
This datapath implements a finite-impulse response (FIR) filter 
y[n]=h0x[n]+h1x[n-1]+h2x[n-2], where h0, h1, and h2 are 
constant coefficients. Write a parametric Verilog HDL 
for realizing this datapath. Use the input values of x={-1,-2,3,4,-
5,1,0,3,4,1,2,3,4,2,-1,3,2,6,1,-1,7}; and coefficients h0=-3, 
h1=3, h2=5; in your testbench to generate the outputs y[n]. 

Write a MIPS program for executing this filter on your pipelined processor. Load the MIPS program 
and the above values for “x” and “h”s into the instruction and data memory, respectively, at initialization
