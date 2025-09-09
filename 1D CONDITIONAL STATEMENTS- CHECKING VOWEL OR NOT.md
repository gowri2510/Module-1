## Experiment No: 1d – Conditional Statements- Checking Vowel or not

## AIM  
To Write a Python program to check whether the given character is a vowel or not using if..else statement
## ALGORITHM  
1. Begin the program.  
2. Take a character input from the user
3. Convert the character to lowercase
4. Check if the lowercase character is one of the vowels: 'a', 'e', 'i', 'o', 'u'
5. If it is a vowel, display "The given character is a vowel"
6. Otherwise, display "The given character is NOT a vowel"
4. Terminate the program.

## PROGRAM
```python
# Reg.No-212223060072
# Name-Gowri.M
# Write your code here

char = input("Enter a character: ")
char_lower = char.lower()

if char_lower in ['a', 'e', 'i', 'o', 'u']:
    print("The given character is a vowel")
else:
    print("The given character is NOT a vowel")
```

## OUTPUT
<img width="811" height="292" alt="{A908E662-1EDE-40E1-8050-E81F8C5B4B20}" src="https://github.com/user-attachments/assets/3944eb30-863b-42b9-bc43-f31c0aa2b340" />

## RESULT
The program was successfully executed. It correctly identified whether the given character was a vowel or not.
