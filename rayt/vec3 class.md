- almost all graphics programs have some classes to store geometric vectors and colors. 
- In many such systems, vectors are 4D 
	- Either a 3D position plus a homogenous coordinate for geometry 
	- RGB plus an alpha transparency component for colors
- For our use case, we are using 3 coordinates.
- Also use the same class vec3 for colors, locations,directions,offsets etc.
- We also have aliases vec3 like Point3 and Color whenever it made sense.
- 