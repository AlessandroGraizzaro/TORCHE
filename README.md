# PressureDrop
Python Script. Pressure drop calculations for crossflow tube bundles. Based of work by Zukauskas and potentially others.

Author: Jonah Haefner
Contributing and previous work done by: Julien Clayton and Lane Carasik

Inputs:
a = dimensionless transverse pitch
b = dimensionless longitudinal pitch
v = the free stream fluid velocity in m/s 
rho = density in g/cm^3
u = dynamic viscosity in pa*s
N = number of rows in the tube bundle 
Dtube = The diamter of the tubes in the bundle in m

Outputs:
Pressure Drop in kPa

Limitations:
b. Will work for values of b = 1.25, 1.5, or 2
a. Reynolds number needs to be below 150000

References:
1. A. ZUKAUSKAS, R. ULINSKAS, Heat Transfer in Banks of Tubes in Crossflow, Hemisphere Publishing, United States (1988).
