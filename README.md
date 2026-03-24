NAME: Deepika.V


REGISTER NUMBER: 212224240030

1. List Operations in Python: Sum of List Items

🎯 Aim:

To write a Python program that calculates the sum of all elements in a list.

🧠 Algorithm:

1.Define a list of numbers.

2.Use Python’s built-in sum() function to calculate the total.

3.Print the result.

🧾 Program:

```
items=[153,147,124,102]
print(sum(items))
```
OUTPUT:

<img width="660" height="176" alt="image" src="https://github.com/user-attachments/assets/d4ca10a2-3e4a-4e62-b1c1-5917c443c019" />


RESULT:

Thus the,Python program that calculates the sum of all elements in a list.

2. Regex in Python: Filter Words Without the Letter 'e'

🎯 Aim:

To write a Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex).

🧠 Algorithm:

1.Import the re module.

2.Initialize an empty list l1 to store results.

3.Define a list of words:

   items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

4.iterate through each word in the list:
   
    Use re.search(r"e", i) to check if the word contains 'e'.
    
    If not, append the word to l1.

5.print the final filtered list.

Program:
```
import re
l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if not re.search(r"e", i):
        l1.append(i)
print("Words without 'e':", l1)
```
OUTPUT:

<img width="508" height="163" alt="image" src="https://github.com/user-attachments/assets/dc04fa02-02fb-4d6b-b363-c15cd1add558" />

3.Strings-Remove Nth Index Character from a String

🎯 Aim:

To write a Python program that accepts a string and removes the character at a specified index.

Algorithm:

1.Define a function named remove that takes the input string as an argument.

2.Read the index n from the user input.

3.Initialize an empty string a to store the new string.

4.Iterate over each index of the string using a for loop.

5.Check if the current index i is not equal to n.

6.If i != n, append the character at index i to string a.

7.After the loop, return the modified string a.

8.Print the final result.

PROGRAM:
```
n=int(input())
def remove(a):
    for i in range(0,len(a)):
        if(i!=n):
            print(a[i],end='')
```
OUTPUT:
<img width="483" height="122" alt="image" src="https://github.com/user-attachments/assets/a431daa9-3eb7-44bb-90f5-ff443273d96f" />

RESULT:
Thus, the program was executed successfully


4.Strings-Palindrome Check in Python (Without Built-in Functions)

🎯 Aim:

To write a Python program to check whether the string "google" is a palindrome or not, without using built-in palindrome checking functions.

🧠 Algorithm:

1.Assign the string "google" to a variable.

2.Reverse the string manually using slicing ([::-1]).

3.Compare the original string with the reversed string

  If they are equal, print that the string is a palindrome.

  Otherwise, print that it is not a palindrome.

4.Execute the program.

PROGRAM:
```

a=input()
s=a[::-1]
if a==s:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")


```

OUTPUT:

<img width="764" height="133" alt="image" src="https://github.com/user-attachments/assets/b5d068a8-e2d4-458f-a4e2-457103542a95" />


RESULT:

Thus, the program was executed successfully.

5. Tuple in Python: Check Element Existence
🎯 Aim:
To write a Python program that checks if the element 'n' and the element 8 exist within a given tuple.

🧠 Algorithm:

1.Define a tuple x with some letters and numbers.

2.Use the in operator to check if the string 'n' exists within the tuple.

3.Use the in operator to check if the integer 8 exists within the tuple.

4.Print the results.


 Program:
 ```
tuplex = input()
print("n" in tuplex)
print("8" in tuplex)

```
Output:

<img width="599" height="170" alt="image" src="https://github.com/user-attachments/assets/f4bf503d-b795-4d9b-b7c7-17baffd4d640" />

RESULT:
Thus, the program was executed successfully.

