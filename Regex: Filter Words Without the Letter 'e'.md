# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
~~~
def remove(s):
    new_string = s[:3] +s[4:]
    print(new_string)
~~~
## Output
<img width="826" height="224" alt="444367455-23c67dfc-fdfe-45b9-895a-1013cba1423f" src="https://github.com/user-attachments/assets/3f4249a0-a0a1-4ef8-b51b-27d2e0144e05" />

## Result
Thus the program that accepts a string and removes the character at a specified index has been executed successfully.
