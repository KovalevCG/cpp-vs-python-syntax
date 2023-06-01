# C++ vs Python Syntax Comparison

Comments
```
// -  Single line comment

/*
*  -  Multi line comment
*/
```
```
# -  Single line comment

"""
      -  Multi line comment. Doesn't always work.
"""
```

Variables
```
int myNum = 15;
string myText = "Hello";
int i, j, k;
const float PI = 3.14;
```
```
myNum = 15
z = float(3)     # If you want to specify the data type of a variable
x, y, z = "Orange", "Banana", "Cherry"
x = y = z = "Orange"

fruits = ["apple", "banana", "cherry"]     # List
x, y, z = fruits    # Unpacking of values
```

For loop
```
for (int i = 0; i < 5; i++) {
  cout << i << "\n";
}


```
```
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)
  if x == "banana":
    break      # Exit the loop when x is "banana"

for x in "banana":     # Loop through the letters in the word "banana":
  print(x)
  
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  if x == "banana":
    continue      # Stop the current iteration of the loop, and continue with the next
  print(x) 

for x in range(6):
  print(x)
```



While Loop

Function

Class





