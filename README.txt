# Digital Design
https://github.com/mbits-mirafra/digitalDesignCourse/wiki

# LogicDesign

Operators
Arithmetic, Bitwise, Reduction, Relational, Logical, Shift
https://documentation-rp-test.readthedocs.io/en/latest/tutorfpga04.html#operators-precedence


systemverilog array
  - Static, Dynamic, Associates, Queue
Example:
// bit [2:0][7:0] m_data; // Packed - As the name suggest, they are packed together.  
// bit [15:0] m_mem[10:0]; // Unpacked
Packed : 
  -  Total size: 3 bytes (24 bits)
  -  Often used for hardware reigsters or bus interfaces.

m_data[2] = byte 2 (bits [23:16])
m_data[1] = byte 1 (bits [15:8])
m_data[0] = byte 0 (bits [7:0])

Unpacked :
  -  Contains 11 elements (indexed 10 down to 0).  Each element is 16 bits wide.

// Packed array access
m_data[2] = 8'hAA;     // Set byte 2
m_data[1] = 8'hBB;     // Set byte 1
m_data[0] = 8'hCC;     // Set byte 0

// Unpacked array access
m_mem[10] = 16'hDEAD;  // Set element 10
m_mem[0]  = 16'hBEEF;  // Set element 0



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

mac_phy_txdata[8*lane_idx*PHY_NB +: 8*PHY_NB] where PHY_NB = 2



High-Speed I/O
==============

Source Synchronous Clocking
https://www.reddit.com/r/FPGA/comments/pei1en/source_synchronous_clocking/

Source Synchronus Interface Timing Closure
https://www.reddit.com/r/FPGA/comments/1gw632u/source_synchronus_interface_timing_closure/


