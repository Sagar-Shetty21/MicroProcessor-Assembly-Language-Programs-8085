
;<Program title>

jmp start

;data


;code
start: nop
LXI H, 3000H
MOV A, M
INX H
MOV B, M
MVI C,00H
SUB B
JNC Next
INR C
CMA
ADI 01H
INX H
MOV M,A 
INX H
MOV M,C
HLT 


hlt