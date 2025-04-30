# Exp.No:28  
## Abstraction

### AIM  
To write a Python program using Abstract Base Class (ABC) to define a generic class named Polygon, and to implement the abstract method sides() in its various subclasses like Triangle, Quadrilateral, Pentagon, and Hexagon. The goal is to demonstrate polymorphism and abstraction using the abc module.

### ALGORITHM
1.Import the ABC and abstractmethod from Python’s abc module to define an abstract base class.
2.Define the abstract base class Polygon:
  Inherit it from ABC.
  Define an abstract method sides() using the @abstractmethod decorator, which must be implemented by all subclasses.
3.Create subclasses for different polygons such as:
Triangle
Quadrilateral
Pentagon
Hexagon
Each of these will inherit from Polygon and implement the sides() method to print the number of sides.
4.Create instances of each subclass and call their sides() method.

### PROGRAM
from abc import ABC, abstractmethod

class Polygon(ABC):
    # Abstract method
    @abstractmethod
    def sides(self):
        pass

class Triangle(Polygon):
    def sides(self):
        print("Triangle has 3 sides")

class Pentagon(Polygon):
    def sides(self):
        print("Pentagon has 5 sides")

class Hexagon(Polygon):
    def sides(self):
        print("Hexagon has 6 sides")

class Square(Polygon):
    def sides(self):
        print("I have 4 sides")

# Driver code   
t = Triangle()
t.sides()

s = Square()
s.sides()

p = Pentagon()
p.sides()

k = Hexagon()
k.sides()

### OUTPUT
![image](https://github.com/user-attachments/assets/fdb07ae6-b288-4ee9-b08b-1231b4dc78b5)

### RESULT
Thus,  Python program using Abstract Base Class (ABC) to define a generic class named Polygon, and to implement the abstract method sides() in its various subclasses like Triangle, Quadrilateral, Pentagon, and Hexagon. The goal is to demonstrate polymorphism and abstraction using the abc module was implemented and successfully executed.
