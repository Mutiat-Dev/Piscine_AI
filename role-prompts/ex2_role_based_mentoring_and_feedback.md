# Use role-based prompts for personalized feedback.

# The prompt

    "As a coding mentor, provide a simple piece of code hat prints a greeting with my name"

# Model output

Here’s a basic example in Python that prints a greeting with your name:

```
name = "Katibi"

print("Hello, " + name + "!")
```

```
How it works:

name = "Katibi" → stores your name in a variable.

print() → displays text on the screen.

"Hello, " + name + "!" → combines (concatenates) the greeting with your name.
```

# Prompt the model: "Act as a mentor reviewing this code. Provide corrections and explain improvements."

# Model output

🔎 Improvements & Corrections
1️⃣ Avoid Hardcoding the Name (Make It Dynamic)

Right now, the program only greets one specific name. A better approach is to make it reusable:

```
name = input("Enter your name: ")

print(f"Hello, {name}!")
```

Why this is better:

Makes the program interactive.

More flexible.

Teaches user input handling.

2️⃣ Handle Extra Spaces

Users sometimes type " Katibi " accidentally.

Improved version:

```
name = input("Enter your name: ").strip()

print(f"Hello, {name}!")
```

.strip() removes extra spaces at the beginning and end.

3️⃣ Capitalize Properly (Optional Enhancement)

To ensure consistent formatting:

name = input("Enter your name: ").strip().title()

print(f"Hello, {name}!")


.title() capitalizes the first letter.

4️⃣ Add Basic Validation (Mentor-Level Improvement)

What if the user presses Enter without typing anything?

name = input("Enter your name: ").strip()

if name:
    print(f"Hello, {name}!")
else:
    print("Hello, Stranger!")


This introduces:

Conditional logic

Defensive programming

Better user experience

🧠 Key Mentorship Insight

Your original code works.

But good programmers ask:

Is it reusable?

Is it user-friendly?

Does it handle edge cases?

Is it clean and modern?

    After prompting the model to review the code above, the role had a big effect on the response as it focused more on correcting, identifying gaps in the code performance and provided insight on improving usability 
