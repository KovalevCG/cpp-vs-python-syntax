# C++ and Python Syntax

## Comments
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

## Variables
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

## Flow Control

> **If ... Else**

```
if ( a > 5 ) {
      m = m / 10;
} else if ( a < -5) {
      cout << m << endl;
} else {
      m = m * 10;
}

string result = (time < 18) ? "Good day" : "Good evening";
```
```
if ( a > 5):
      m = m / 10
elif ( a < -5):
      print (m)
else:
      m = m * 10

result = "Good day" if (time < 18) else "Good evening"

print("A") if a > b else print("B")

if b > a:
  pass
```

## Loops

> **For loop**
```
vector<int> v = { 1,4,6,8,10 };
for (auto i : v) {
      cout << i << endl;
}

map<string, int> b = { {"a", 1},{"b",2},{"c",3}};
for (auto i : b) {
      cout << i.first << " - " << i.second << endl;
}

string s = "qwerty";
for (auto i : s) {
      cout << i << endl;
}

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
> **While Loop**
```
int i = 0;
while (i < 10) {
      cout << "While loop: " << i << endl;
      i++;
}

i = 0;
do {
      cout << "Do While loop: " << i << endl;
      i++;
} while (i < 10);
```
```
i = 0
while i < 10:
  print("While loop: ", i)
  i += 1
```

## Functions
```
void myFunction(string fname) {
  cout << fname << " Refsnes\n";
}
```
```
def my_function(fname, lname):
  print(fname + " " + lname)
my_function("Emil", "Refsnes")
```

## Classes





