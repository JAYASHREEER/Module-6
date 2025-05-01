# Exp.No:29  
## Encapsulation

### AIM  
To implement getter and setter methods in a class to access and modify private variables (__name and __age) and demonstrate their use through object invocation.

### ALGORITHM
1.Define the class Class1Students.
Initialize private variables __name and __age using the constructor (__init__).
2.Define the speak() method.
This method prints the current values of __name and __age.
3.Create getter methods:
  get_name() returns the value of __name.
  get_age() returns the value of __age.
4.Create setter methods:
  set_name(new_name) sets the value of __name.
  set_age(new_age) sets the value of __age.
5.Create an object of the class.
  Use the setter methods to change the name and age.
  Use the getter methods to print the updated values.
  Call the speak() method to display the final result.
  
### PROGRAM
class Class1Students:
    def __init__(self, name, age):
        self.__name = name
        self.__age   = age

    def speak(self):
        print(f"my name is {self.__name}, and I am {self.__age} years old.")
    
    def get_name(self):
        print(self.__name())
    
    def set_name(self,n):
        self.__name=n
        
    def get_age(self):
        print(self.__age())
        
    def set_age(self,a):
        self.__age=a
obj=Class1Students("Michael",40)
obj.speak()
obj.set_name("John")
obj.set_age(25)
obj.speak()

### OUTPUT
![image](https://github.com/user-attachments/assets/d638e99a-6136-4829-9e99-0de86dbe6591)

### RESULT
Thus, the python program using encapsulation was implemented and successfully executed.

