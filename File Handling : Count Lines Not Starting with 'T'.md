
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
    f.write("This is the tamilnadu")

with open("story.txt",'r') as f:
    c=f.read()
    k=0
    for i in c:
        if i.startswith(("T")):
            k+=1
    print("count:",k)

```

## Output
<img width="1448" height="740" alt="image" src="https://github.com/user-attachments/assets/0e2297f4-9f1f-45ab-88f0-f583b92fc6d1" />


## Result
successfully wrote  Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.
