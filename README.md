3D Shape Modeling with Abstraction
Project Description
```
This project demonstrates the concept of abstraction and polymorphism in Python by modeling 3D shapes.
We define an abstract base class Shape3D with two abstract methods:
	•	surface_area()
	•	volume()

Three subclasses implement these methods:
	•	Sphere
	•	Cylinder
	•	Cube

The program randomly generates 10 shape objects, calculates their surface area and volume, and displays the results.
```
⸻

``` Classes and Methods Documentation

1. Shape3D (Abstract Base Class)
	•	Purpose: Defines the blueprint for 3D shapes.
	•	Methods:
	•	surface_area(): Abstract method to calculate surface area.
	•	volume(): Abstract method to calculate volume.

2. Sphere
	•	Constructor: __init__(self, radius)
	•	radius (int): Radius of the sphere.
	•	Methods:
	•	surface_area(): Calculates surface area using the formula: 4πr²
	•	volume(): Calculates volume using the formula: (4/3)πr³

3. Cylinder
	•	Constructor: __init__(self, radius, height)
	•	radius (int): Radius of the base circle.
	•	height (int): Height of the cylinder.
	•	Methods:
	•	surface_area(): Calculates surface area using: 2πr(r + h)
	•	volume(): Calculates volume using: πr²h

4. Cube
	•	Constructor: __init__(self, side_length)
	•	side_length (int): Length of a side.
	•	Methods:
	•	surface_area(): Calculates surface area using: 6a²
	•	volume(): Calculates volume using: a³
```
⸻
```     How to Run the Code
	1.	Make sure you have Python 3 installed.
	2.	Save the code in a file named, for example, shapes.py.
	3.	Open a terminal or command prompt.
	4.	Navigate to the directory where your file is saved.
	5.	Run the program:
```
python 3-D.py


<img width="742" alt="Screenshot 2025-04-27 at 8 12 55 PM" src="https://github.com/user-attachments/assets/628975bf-142e-45db-8b59-99dbe84a666d" />

``` ⸻
Sample Input/Output (Screenshots)

Since shapes are randomly generated, your output will vary every time.

Example Run:


Shape 1: Sphere
Surface Area: 384.85
Volume: 1436.76
------------------------------
Shape 2: Cube
Surface Area: 54.00
Volume: 27.00
------------------------------
Shape 3: Cylinder
Surface Area: 471.24
Volume: 942.48
------------------------------
Shape 4: Sphere
Surface Area: 201.06
Volume: 381.70
------------------------------
Shape 5: Cube
Surface Area: 150.00
Volume: 125.00
------------------------------
Shape 6: Cylinder
Surface Area: 376.99
Volume: 753.98
------------------------------
Shape 7: Sphere
Surface Area: 314.16
Volume: 523.60
------------------------------
Shape 8: Cylinder
Surface Area: 615.75
Volume: 1539.38
------------------------------
Shape 9: Cube
Surface Area: 6.00
Volume: 1.00
------------------------------
Shape 10: Sphere
Surface Area: 1256.64
Volume: 4188.79
------------------------------
```


⸻

 Notes:
	•	Each run randomly generates different shapes and sizes.
	•	Surface area and volume values are rounded to two decimal places for clarity.

⸻

 Requirements
	•	Python 3.x
	•	No additional libraries required (uses built-in random, math, and abc modules).

⸻

