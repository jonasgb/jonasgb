from sympy import *
import numpy as np


x, y, z, t = symbols('x y z t')
theta, phi = symbols('theta phi')
r, rho = symbols('r rho', real = True, positive = True)
print("MERK: Hvis svaret er zoo, oo eller lignende betyr det uendelig")
print("Du kan kopiere svarene direkte fra Python inn til øvingen :)")

#Nyttig info
#Kvadratrot skrives på formen: sqrt(...)
#Vanlig deling skrives på formen: x/y
#Eksponenter skrives på formen: x**y (2**2 = 2^2 = 4)
#sin(t) skrives sin(t)
#pi skrives pi
#e skrives E
#log = ln

#Sett inn dine tall under her:

#Oppgave 1

limV = [1, 2] #Grensene til v
limU = [ln(3), ln(7)] #Grensene til u

arr1 = [limV, limU]

#Oppgave 2

fxyz = 1/(x**2+y**2+z**2)

arr2 = fxyz

#Oppgave 3

F = [6*x**2*y**3 + 4*x,
    6*x**3*y**2 + 2*y] #Vektorfelt F

arr3 = F
