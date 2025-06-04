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

```
import math

class cse:
    def mech(self, radius):
        area = math.pi * radius ** 2
        print(f"Area of circle: {area:.2f}")


r = float(input())

obj = cse()
obj.mech(r)
```

## Output
![438927051-0fb24ed2-e483-4f0c-8114-cdb94b36b0cf](https://github.com/user-attachments/assets/e044e969-4432-47ef-afdb-0b573f44167b)

## Result
Thus the program executed successfully.

## Dictionary Operations in Python: Merging Two Dictionaries
## 🎯 Aim
To write a Python program that merges *two dictionaries* and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries dict1 and dict2 with some key-value pairs.
2. Define a function merge() that merges the two dictionaries using the ** unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from dict2 will overwrite that from dict1.
3. Call the merge() function and print the merged dictionary.

## 🧾 Program
```
dict1={'Ten': 10,'Twenty': 20,'Thirty': 30} 
dict2={'Thirty': 30,'Fourty': 40,'Fifty': 50}
 def merge (dict1,dict2): 
res={**dict1 , **dict2}
return res 
dict3=merge(dict1,dict2) 
print(dict3)
```
## Output
![Screenshot (145)](https://github.com/user-attachments/assets/e8333efb-3f5c-488e-bca7-cb30b9252da2)

## Result
thus,the program has been executed successfully.

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

1. *Start the program.*
2. *Define* a dictionary with key-value pairs.
3. *Sort by Keys*:
   - Use sorted(dictionary.items())
   - Convert the result to a dictionary using dict()
4. *Sort by Values*:
   - Use sorted(dictionary.items(), key=lambda item: item[1])
   - Convert the result to a dictionary using dict()
5. *Display* the original and sorted dictionaries.
6. *End the program.*

---

## 🧪Program
```
def dictionairy():  
 key_value ={}   
 key_value[2] = 56      
 key_value[1] = 2
 key_value[5] = 12
 key_value[4] = 24
 key_value[6] = 18     
 key_value[3] = 323
 s=sorted(key_value.items(),key=lambda x:x[1])
 print ("Keys and Values sorted in alphabetical order by the value")
 print(s)
 
def main():
    dictionairy()
           
```

## Sample Output
![image](https://github.com/user-attachments/assets/f19f2bd9-a6f6-4aa4-a418-0d570459faa2)


## Result

The program successfully sorts the dictionary by its keys and values in alphabetical order and prints both sorted versions along with the original dictionary.

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
```
try:
    # Taking 3 elements input from the user
    L = []
    for i in range(3):
        item = ['laptop','mobile','pen']
        L.append(item)

    # Trying to access index 4
    print(L[4])

except IndexError:
    print("check index range")
```

## Output
![438930470-b2acd206-0aeb-4ec2-a40f-e911fa9e5066](https://github.com/user-attachments/assets/6c9076bc-1fff-48fb-8d14-1b42c1c9de32)

## Result
Thus the program executed successfully.

# File Handling in Python: Count Lines Not Starting with 'T'
## 🎯 Aim
To write a Python program that counts the number of lines in a text file story.txt that do *not* start with the alphabet 'T'.

## 🧠 Algorithm
1. Open the file story.txt in *read mode*.
2. Initialize a counter count to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is *not* 'T'.
   - If the line does not start with 'T', increment the count by 1.
4. After processing all lines, print the count value, which represents the number of lines that do not start with 'T'.

## 🧾 Program
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
![Screenshot (148)](https://github.com/user-attachments/assets/584ecff1-9dfb-4670-b1c8-ee354a85ed3d)

## Result
Thus,the program has been executed successfully.
