# Digital Design
https://github.com/mbits-mirafra/digitalDesignCourse/wiki

# LogicDesign

Operator
logical vs bit-wise
reduction
https://www.google.com/search?client=firefox-b-d&sca_esv=be4c59a23fd2350a&q=systemverilog+bitwise+or&udm=2&fbs=AEQNm0DYVld7NGDZ8Pi819Yg8r6em07j6rW9d2jUMtr8MB7hthlxj_a5JB7GtKl9Rvi8UOrX6vOKeE8ctU8C4v5SDrHEsrgUOOFp5HvlkBZf4yVP83YajKnrlhAJvHG8uQnJWlvuYz8LvE_lwESvEPu-1v94fKd9xhS49UTuNSe7CMY7I5AuGmdDN0lv5iId0gIyD9wyA5aKEve0q31Gi2kwmyWtccpVrQ&sa=X&ved=2ahUKEwjZte70ideJAxV-R2wGHeRHMC4QtKgLegQIHhAB&biw=1920&bih=919&dpr=1#imgrc=TUGwRZpNTxEpWM&imgdii=niM5ShRuXv3s-M

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
