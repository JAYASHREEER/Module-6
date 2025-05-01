# Exp.No:27  
## Operator Overloading

### AIM  
To write a Python program that overloads the greater than (>) operator using a special method (__gt__) to compare two objects based on a value (e.g., marks or score).

### ALGORITHM
1.Define a class saveetha.
2.Create a constructor (__init__) that accepts a value (e.g., score or marks) and stores it as an instance variable.
3.Overload the > operator using __gt__ method.
This method should compare the instance variable of the current object (self) with that of another object (other).
Return True if self's value is greater than other's value, else False.
4.Create two objects (obj1 and obj2) of the class saveetha with different values.
Use the > operator to compare obj1 and obj2.
5.Print the result.

### PROGRAM
class saveetha:
    def __init__(self, value):
        self.value = value

    def __gt__(self, other):
        return self.value > other.value

obj1 = saveetha(90)
obj2 = saveetha(80)

print(obj1 > obj2)

### OUTPUT
![image](https://github.com/user-attachments/assets/38046c29-f75b-4b54-be0f-c628bb03b06a)

### RESULT
Thus, Python program that overloads the greater than (>) operator using a special method (__gt__) to compare two objects based on a value (e.g., marks or score) was implemented and successfully executed.
