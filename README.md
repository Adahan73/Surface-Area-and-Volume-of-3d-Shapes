# Surface-Area-and-Volume-of-3d-Shapes

Description

This Java project demonstrates the concept of polymorphism by using a common interface, Shape3DInterface, to define methods for calculating the surface area and volume of different 3D shapes. Three classes, Sphere, Cylinder, and Cube, implement this interface, each with their own specific formulas for these calculations. The project randomly generates instances of these shapes, calculates their properties, and displays the results.

Features

Polymorphism: The Shape3DInterface allows different shape classes to be used interchangeably, enabling a uniform way to call surfaceArea() and volume() methods regardless of the actual shape type.

Randomization: Shapes are created with randomly generated dimensions within specified ranges, ensuring diverse outputs for each run.

Extensibility: Additional 3D shapes can be easily added by implementing the Shape3DInterface.

How Polymorphism is Used

Polymorphism is a fundamental concept of object-oriented programming that allows objects of different types to be treated as objects of a common super type. In this project:

The Shape3DInterface defines two methods: surfaceArea() and volume().

The Sphere, Cylinder, and Cube classes implement these methods.

A list of Shape3DInterface references stores objects of different shape types, demonstrating that they can be handled uniformly despite their differences.

The program uses these references to call the appropriate implementation of surfaceArea() and volume() based on the actual object type at runtime.

How to Run the Program

Compile the Shape3DDemo class.

Run the compiled program.

The program will generate 10 random 3D shapes and output their details (name, surface area, and volume).

# Sample Output
Sphere (radius = 3.45)
Surface Area: 149.64
Volume: 171.99

Cube (side = 7.89)
Surface Area: 373.08
Volume: 491.90

Cylinder (radius = 4.12, height = 15.67)
Surface Area: 518.43
Volume: 845.10


# File Structure

Shape3DInterface: The interface defining methods for surface area and volume.

Sphere: Class implementing the Shape3DInterface for spheres.

Cylinder: Class implementing the Shape3DInterface for cylinders.

Cube: Class implementing the Shape3DInterface for cubes.

Shape3DDemo: Main class to generate shapes, calculate properties, and display results.
