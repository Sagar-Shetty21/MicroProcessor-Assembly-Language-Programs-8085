
;<2B. Subtraction of 2 8-bit hex numbers>


;




LXI H,8500
MVI C,00
MOV A,M
INX H
SUB M
JNC Next
INR C
Next: STA 8502
MOV A,C
STA 8503
HLT