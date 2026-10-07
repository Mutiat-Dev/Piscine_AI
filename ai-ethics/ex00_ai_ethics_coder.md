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

        When i try to do a task or make an effort, i

How is your understanding different than if you'd just asked for the solution?

    That way, you're able to look at what you've done, figure where the mistake is and what you have to do to make it right. This helps you to learn and aids better understanding.

Can you now implement similar functions (reverse a string, find duplicates) without AI?

    I believe i can

What mental model did you build?

    Mental model simply means being able to interpret internlly. One mental model i can ive built is the the debugging mindset. Being able to think about why a code isn't right or correct. 


# Part D: The Fairness Contract

I will use AI when:

    After I've attempted a problem for at least 20 minutes

    To understand why my solution works/doesn't

    To explore alternatives after I have a working solution

    I'm stuck after trying

I will NOT use AI when:

    I haven't tried the problem myself

    I'm taking an assessment or test

    I need to build fundamentals

I know I'm using AI fairly when:

    I can explain my code without looking at AI's response

    I could solve similar problems without AI

    I feel more confident in my abilities

    I can explain my solution clearly

        Katibi Mutiat
        12-02-2026

# Part E: Real-World Scenario Analysis

Interview: "Explain how you'd implement a caching system." If you always relied on AI, can you answer?

    It'd be a bit difficult because i'd struggle to explain without understanding the concept.

Production bug at 2 AM: AI is unavailable. Can you debug code you don't fully understand?

    If the AI is offline and the codebase is available, i'd try and understand the error, tackle it and possibly find a solution to it. If i don't have the codebase, that might be difficult. 

New tech with little documentation: If you never learned to read docs and experiment, what happens?

    I'd use the help of Google, documents, examples available and casestudies.

Write a paragraph: How does using AI fairly now prepare you for these scenarios?

    Using AI fairly makes one responsible and upright. It forces one to understand concepts and systems deeply, you're able to think about solutions more quickly. Science shows that the way we use our brain trains it, if one engages in difficult tasks, it increases it's efficiency, adaptability and overall it's intelligence. It helps one to tackle real problems individually without relying on AI or in a case where Artificial Intelligence might be unavaliable.

# Part F: Building Irreplaceable Skills

Rate yourself 1–5 and write an improvement plan for your lowest area:

 Problem decomposition  3/5 

 Systems thinking  3/5 

 Critical evaluation  4/5 

 Debugging mindset  2/5 

 Conceptual understanding (the "why")  3/5  

# Action plan: 3 specific actions this week to improve it without outsourcing thinking to AI.
    1. keeping calm instead of being frustrated
    2. narrowing down the cause or point of error by reading the error message carefully and understand it 
    3. breaking my code into smaller bits, find what works and what doesn't, then go from there



