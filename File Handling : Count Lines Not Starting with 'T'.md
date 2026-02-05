# File Handling in Python: Count Lines Not Starting with 'T'

##  Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

##  Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

##  Program
```
def returnSum(myDict):
    final=0
    for i in myDict.values():
        final+=i
    return final
#driver functions
myDict = {'a': 100, 'b': 200, 'c': 300}
print("Sum :",returnSum(myDict))

```
## Output
<img width="482" height="192" alt="518002723-a754cd09-ff0e-4941-8029-f74caaaba557" src="https://github.com/user-attachments/assets/f85d7ed2-db50-4d89-a656-911ff05da9c6" />

## Result
Thus,the program has been executed successfully.

