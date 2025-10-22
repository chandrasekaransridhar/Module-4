## Sridhar (25017646)


# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```py
import math
class cse:
    def mech(self):
        radius=int(input())
        c=math.pi*radius**2
        print(c)
muruga=cse()
muruga.mech()
```

## Output
<img width="1413" height="311" alt="image" src="https://github.com/user-attachments/assets/0d3f0037-a39a-49b3-afb2-f13007115d81" />

## Result
successfully wrote Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.


## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```py
dic1={1:"muruga",2:"vel",3:"kantha",4:"palni"}
dic2={5:"vetri",6:"arupadai"}
def merge():
    meg={**dic1,**dic2}
    return meg
c=merge()
print(c)
```

## Output
<img width="1600" height="283" alt="image" src="https://github.com/user-attachments/assets/4657e98f-8938-4325-9d1f-5ab9a964ef13" />

## Result
successfully wrote Python program that merges **two dictionaries** and combines their key-value pairs.


# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```py
l={'apple':2,'banana':1,'orange':3,'watermelon':5}
c=dict(sorted(l.items()))
k=dict(sorted(l.items(),key=lambda item:item[1]))
print(c)
print(k)
```


## Sample Output
<img width="1508" height="176" alt="image" src="https://github.com/user-attachments/assets/343b1f39-9d25-48f0-b9e2-473669f4dcc6" />


## Result
successfully wrote Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order


# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```py
try:
    l=[1,2,3,4]
    c=l[5]
    print(c)
except Exception:
    print("You're out of list range.")
```
## Output
<img width="1241" height="182" alt="image" src="https://github.com/user-attachments/assets/f8c9473f-bb51-4823-92ab-3656299fe3a2" />


## Result
successfully wrote Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.


## File  handeling in python: count lines Not 
## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```py
with open("story.txt","w")as f:
    f.write('This is muruga\n')
    f.write("This is the world\n")
    f.write("not permentent in this  world\n")
    f.write("This is the tamilnadu\n")
    f.write("kanthavela\n")
    f.write("world is biggest")
k=0
with open("story.txt",'r') as f:

    for i in f:
        if not i.startswith("T"):
            k+=1
print("count:",k)

```

## Output
<img width="1430" height="732" alt="Screenshot 2025-10-22 223016" src="https://github.com/user-attachments/assets/5a6b5cc6-c3f8-4501-9ade-a16eac0616c5" />



## Result
successfully wrote  Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.
