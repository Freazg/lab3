## lab3
##Stim.do

force A 0 0ns, 0 20ns, 1 40ns, 1 60ns;
force B 0 0ns, 1 20ns, 0 40ns, 1 60ns;

##half_add_lab1.v

// half_add.v
`timescale 1 ns/1 ps

  //------------------------------------------------------

module half_add (S, C, A, B);
    output S, C; 
    input  A, B;
    wire   S, C;
  
    assign C = A & B;
    assign S = A ^ B;
            

endmodule


