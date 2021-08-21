'''
Write a Python program to calculate the volume of a sphere
using the radius (r) input by the user. V =𝜋𝑟^3 where 𝜋 = 3.14
The user cannot input a radius larger than 100 & if so warn.
'''
import math 
print ("Plese note that the value you enter is between zero to 100")
radius =  int(input("Please input the radius of the sphere:"))
pi = math.pi
print (pi)
if radius < 0 or radius > 100:
      print ("The above condition is not met")
    
else:
      volume = pi * radius**3
      
      print ("The volume of the sphere is", round(volume,1))
