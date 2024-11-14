# vishnu
Repo for practicing git
from sympy import*
var('x,y')
y=Function(y,x)
Y1=diff(y,x)
DE=y1+y*tan(x)-y**3*sec(x)
soln=dsolve(DE,y)
pprint(soln)
