Implementação da cifra de uso único (One time pad) em Python

Como funciona?
mensagem:      H O P E ->  000111 001110 001111 000100
one-time pad:  y T 2 5 ->  110010 010011 110110 111001
                           |
                       XOR |
                           V
texto cifrado: 1 d 5 9 ->  110101 011101 111001 111101