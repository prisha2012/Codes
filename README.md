# python
#COUNT UPPER CASE,LOWER CASE, ALPHABETS AND DIGIT 
n= input("Enter a string: ")

def analyze_string(n):
    uppercase_count = sum(c.isupper() for c in n)
    lowercase_count = sum(c.islower() for c in n)
    alphabet_count = sum(c.isalpha() for c in n)
    digit_count = sum(c.isdigit() for c in n)

    print(f"Uppercase letters: {uppercase_count}")
    print(f"Lowercase letters: {lowercase_count}")
    print(f"Alphabets: {alphabet_count}")
    print(f"Digits: {digit_count}")

analyze_string(n)

