s = input("racecar ")

# Step 1: make it case-insensitive
s = s.lower()

# Step 2: remove spaces and punctuation
cleaned = ""
for char in s:
    if char.isalnum():
        cleaned += char

# Step 3: check palindrome and find where it fails
left = 0
right = len(cleaned) - 1

while left < right:
    if cleaned[left] != cleaned[right]:
        print("false")
        print("Stops being a palindrome at positions:",
              left, "and", right)
        print("Characters:", cleaned[left], "and", cleaned[right])
        break
    left += 1
    right -= 1
else:
    print("true")

# what AI added that i didn't consider initially.
That i needed to clarify my output properly so not to confuse. 
Input matters as much as logic
