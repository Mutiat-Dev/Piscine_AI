# Part A How have you used AI for coding so far?
    For debugging, explanation and checking ideas.

Do you ask AI for solutions before trying yourself?
    No, i make an attempt, then ask AI if my approach works and how to get better.

Can you explain code you've submitted without AI's help?
    Yes, i can
What would happen if AI was suddenly unavailable during an exam or interview?
    I'd do my exam or interview as i would have because i'm not relying on AI. AI is there to help my learning before the exam and not during the exam.

Identify your current pattern: Which learner are you now? Learner A: "AI is my answer generator"
    Asks: "Write a function that does X"
    Copies code without reading carefully
    Moves on once it works
    Cannot explain how the code works

Learner B: "AI is my learning amplifier"
    Attempts the problem first
    Asks: "Why does this approach work? What are the trade-offs?"
    Tests understanding by explaining concepts
    Uses AI to explore deeper, not to avoid thinking

        I'm definitely learner B

Write a brief paragraph: Where are you now, and where do you want to be?
    Currently, i still use AI when i'm stuck to answer questions or just to speed things up, but i want to rely more on my own thinking, on my own abilities.

# Part B: The Wrong Way vs. The Right Way

Challenge: Implement a simple function to check if a string is a palindrome.

Pseudocode 
1. Take a string as input and store it in s.

2. Reverse the string and store it in a new variable reverse.

3. Compare the original string s with the reversed string reverse.

    If they are the same → the string is a palindrome → print true.

    If they are different → the string is not a palindrome → print false.


# Function to check if a string is a palindrome
def is_palindrome(s):
    # Returns True if the string is a palindrome, False otherwise.

    s = s.lower()
    Exact match (case-sensitive, spaces included).
    
    reversed_s = s[::-1]  # Reverse the string
    if s == reversed_s:    # Compare original and reversed
        return True
    else:
        return False

# Test examples
print(is_palindrome("racecar"))  # True
print(is_palindrome("hello"))    # False
print(is_palindrome("A man a plan a canal Panama"))  # False


# Reflection

    What did you learn by struggling first?
        

    How is your understanding different than if you'd just asked for the solution?

    Can you now implement similar functions (reverse a string, find duplicates) without AI?

    What mental model did you build?

Part C: Testing Your Understanding

Without using AI, complete these variations:

    Ignore spaces and punctuation

    Make it case-insensitive

    Return the position where the string stops being a palindrome (if not a palindrome)

Then use AI strategically:

"I modified my palindrome function to handle these cases: [show your modifications] Did I miss any edge cases? How could I make this more efficient?"
Part D: The Fairness Contract

Create ex00_ai_ethics_coder.md with a personal code of ethics for AI use in learning:

    I will use AI when:

    After I've attempted a problem for at least 20 minutes

    To understand why my solution works/doesn't

    To explore alternatives after I have a working solution

    [add your rules]

    I will NOT use AI when:

    I haven't tried the problem myself

    I'm taking an assessment or test

    I need to build fundamentals

    [add your rules]

    I know I'm using AI fairly when:

    I can explain my code without looking at AI's response

    I could solve similar problems without AI

    I feel more confident in my abilities

    [add your rules]

Sign and date this contract.
Part E: Real-World Scenario Analysis

    Interview: "Explain how you'd implement a caching system." If you always relied on AI, can you answer?

    Production bug at 2 AM: AI is unavailable. Can you debug code you don't fully understand?

    New tech with little documentation: If you never learned to read docs and experiment, what happens?

Write a paragraph: How does using AI fairly now prepare you for these scenarios?
Part F: Building Irreplaceable Skills

Rate yourself 1–5 and write an improvement plan for your lowest area:

    Problem decomposition

    Systems thinking

    Critical evaluation

    Debugging mindset

    Conceptual understanding (the "why")

Action plan: 3 specific actions this week to improve it without outsourcing thinking to AI.

Deliverable: ex00_ai_ethics_coder.md containing:

    Your self-assessment (Part A)

    Palindrome solution + reflection (Part B)

    Personal fairness contract (Part D)

    Scenario analysis (Part E)

    Skills assessment + action plan (Part F)

