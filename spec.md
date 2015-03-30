This is the specification for HVM

Instructions:
=============

SET X Y: set the register specified in X to the literal word in Y
ADD X Y: add the words in the registers specified by X and Y and store the result in the RETURN register (0)
OUT X: output the word of register X
LOD X Y: load the word at memory word X into register Y
SAV X Y: save the word at register X into memory word Y
INP X: store a word from input in register X
