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
