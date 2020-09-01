# sorter
Verilog implementation of an AXIS number sorter


The sorter module receives four numbers from the AXIS bus and presents them on output ports lvl1, lvl2, lvl3, and lvl4, where level 1 is the largest value and level 4 is the smallest value. A done flag is asserted when lvl1-4 are valid.


Simulatuion passed with DATA_WIDTH 16, 32, and 64. To run, cd to sim/xsim and run ./sorter_tb.sh


Platform: Vivado 2019.2 on Ubuntu 18.04.4 LTS