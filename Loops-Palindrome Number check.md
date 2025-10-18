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
```
a=int(input())
rev=0
n=a
while n!=0:
    digt=n%10
    rev=(rev*10)+digt
    n=n//10
if rev==a:
    print("The given number {} is a Palindrome".format(a))
else:
    print("The given number {} is not a palindrome".format(a))
```
## Output
<img width="1903" height="632" alt="Screenshot 2025-10-18 232007" src="https://github.com/user-attachments/assets/92ee21dc-9ce0-4452-add1-f3c961007899" />

## Result
The Loops in Python: Palindrome Number Checker is executed successfully.
