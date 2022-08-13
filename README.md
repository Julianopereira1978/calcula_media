# calcula_media

# -*- coding: utf-8 -*-
"""
Created on Sat Aug 13 19:13:36 2022
@author: Juliano
"""
import os

nota1 = float(input('Informe a primeira nota: '))

nota2 = float(input('Informe a segunda nota: '))

nota3 = float(input('Informe a terceira nota: '))

media = (nota1 + nota2 + nota3)/3

if media >= 7.0:

    print('Aprovado')
    print('Boas férias')
else:
    print('Reprovado')
    
os.system('pause')
