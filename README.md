# tcomp
Teoria da Computação

Entrada - BnB
BnB CPY1 -> BnBnB
BnBnB CPY2 -> BnBnBnBnB
BnBnBnBnB CPY4 -> BnBnBnBnBnBnBnBnB
BnBnBnBnBnBnBnBnB MULT -> Bn^2BnBnBnBnBnBnB
Bn^2BnBnBnBnBnBnB MR1 + MULT -> Bn^2Bn^2BnBnBnBnB
Bn^2Bn^2BnBnBnBnB MR1 + MULT -> Bn^2Bn^2Bn^2BnBnB
Bn^2Bn^2Bn^2BnBnB ML2 + A -> B 2*(n^2)Bn^2BnBnB
B 2*(n^2)Bn^2BnBnB A -> B 3*(n^2)BnBnB
B 3*(n^2)BnBnB A -> B 3*(n^2) + n BnB
B 3*(n^2) + n BnB A -> B 3*(n^2) + 2n B

Resultado final = B 3*(n^2) + 2n B
