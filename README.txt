# Digital Design
https://github.com/mbits-mirafra/digitalDesignCourse/wiki

# LogicDesign

Operators
Arithmetic, Bitwise, Reduction, Relational, Logical, Shift
https://documentation-rp-test.readthedocs.io/en/latest/tutorfpga04.html#operators-precedence


systemverilog array
  - Static, Dynamic, Associates, Queue
Example:
logic [x-1:-0] some_variable [y] // Unpacked
- There will be x array of width y 
logic [x][y] some_variable // packed
- Combined array size of x*y.  x number of some_variable with width y.
Link : https://www.chipverify.com/systemverilog/systemverilog-arrays

reg arrary[2:0] vs reg array[0:2] vs reg array[3]
Difference between array[2:0] and array[0:2] 
reg array[0:2] is equivalent to reg array[3]
Link : https://www.reddit.com/r/Verilog/comments/tg506z/reg_array20_vs_reg_array02_vs_reg_array3/

Verilog conditional hardware based on parameter value
https://stackoverflow.com/questions/52061466/verilog-conditional-hardware-based-on-parameter-value

Latch Time Borrowing
https://adaptivesupport.amd.com/s/article/651529?language=en_US



High-Speed I/O
==============

Source Synchronous Clocking
https://www.reddit.com/r/FPGA/comments/pei1en/source_synchronous_clocking/

Source Synchronus Interface Timing Closure
https://www.reddit.com/r/FPGA/comments/1gw632u/source_synchronus_interface_timing_closure/


