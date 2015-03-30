This is the specification for HVM

Instructions:
=============

SET X Y: set the register specified in X to the literal word in Y
ADD X Y: add the words in the registers specified by X and Y and store the result in the RETURN register (0)
OUT X: output the word of register X
LOD X Y: load the word at memory address X into register Y
SAV X Y: save the word at register X into memory address Y
INP X: store a word from input in register X
CPY X Y: copy the word from register X to register Y
BRA X Y: if X is not 0, set NEXT register (N-1) to the address in Y
STP: Halt execution
