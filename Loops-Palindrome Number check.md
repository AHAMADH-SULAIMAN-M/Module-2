## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program

```python
s = input( )
rev = ""

for char in s:
    rev = char + rev

if s == rev:
    print("Palindrome")
else:
    print("Not a palindrome")

```

## Output

<img width="257" height="89" alt="image" src="https://github.com/user-attachments/assets/7aef3dba-bc77-4323-8f19-62e06c911234" />

## Result
The python program to check whether the number is palindrome or not is exected succesfully and verified
