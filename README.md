# Gravitational-Lensing-Analysis
Example of Python Code
The purpose of this code is to align gravitational lensed images to a giving simulation outcome of the Bullet Cluster. 
The optimization process minimize the chi_sq function using sciypy powell optimization routine.
1. The 3D Enzo simulation is projected to 2D surface density given a set of viewing angle using yt camera projection routine.
2. Solving the Possion Equation use Multiple Grid Gauss-Seidel for the gravitational lensing potential.
3. Solving the deflection angle of strong lensed galaxies and the distortion shear of weak lensed galaxies.
4. Register the images position by minimizing the chi_sq function.
