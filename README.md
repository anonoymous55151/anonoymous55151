import math


def trinome(a,b,c): 
    eq=a*x**2+b*x+c
    a,b,c=1,1,1
    j=-1
    for x in eq:
        if   b**2-4*a*c>0:
            x==(-b+-math.sqrt(b**2-4*a*c))//2*a
        elif b**2-4*a*c<0:
            x==(-b+-j*math.sqrt(-(b**2-4*a*c))//2*a
        else b**2-4*a*c==0:
            x==-b//2*a
    return(x)
            
