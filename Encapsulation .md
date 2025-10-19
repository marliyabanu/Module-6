# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
# 1. Define the Class
class Rectangle:
    # 2. Initialize Variables using Constructor
    def __init__(self, length, breadth):
        self.__length = length      # Private attribute
        self.__breadth = breadth    # Private attribute

        # 3. Print Values from within the class
        print("Length:", self.__length)
        print("Breadth:", self.__breadth)

# 4. Instantiate the Object
rect = Rectangle(10, 5)


## Output
<img width="820" height="602" alt="image" src="https://github.com/user-attachments/assets/68110d56-8d88-46c6-a46e-ae789b594396" />



## Result
A **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth` is excuted sucessful.

