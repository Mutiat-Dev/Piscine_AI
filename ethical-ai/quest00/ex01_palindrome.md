# Pseudocode 
1. Take a string as input and store it in s.

2. Reverse the string and store it in a new variable reverse.

3. Compare the original string s with the reversed string reverse.

    If they are the same → the string is a palindrome → print true.

    If they are different → the string is not a palindrome → print false.

 # BEFORE AI

 s = input ("racecar ")

reverse = s[::-1]

if ( s == reverse ):
    print("true")
else:
    print("false")
    

# AFTER AI

# Function to check if a string is a palindrome
def is_palindrome(s):
    """
    Returns True if the string is a palindrome, False otherwise.
    Exact match (case-sensitive, spaces included).
    """
    reversed_s = s[::-1]  # Reverse the string
    if s == reversed_s:    # Compare original and reversed
        return True
    else:
        return False

# Test examples
print(is_palindrome("racecar"))  # True
print(is_palindrome("hello"))    # False
print(is_palindrome("A man a plan a canal Panama"))  # False



# What did you learn from solving it before asking AI?
I understood that the goal of the palindrome is to check whether the string reads the same forward and backwards so i try to break the problem into steps

 # How is your understanding different now?
 I  understand better efficiency and edge cases

# Could you now write similar functions (e.g., reverse a string) without help?
Yes
