# Guide the model to solve a problem with explicit reasoning.

# Prompt

    "Jack likes apples more than bananas, Sarah likes bananas more than apples, Mark likes bananas more than Jack.Who likes apples the most?

    Explain your reasoning before giving the final answer"

# Model output

    Step 1: Compare Jack and Sarah

- Jack prefers apples > bananas

- Sarah prefers bananas > apples

So Jack likes apples more than Sarah does.

    Step 2: Consider Mark

- Mark likes bananas more than Jack

- Since Jack already prefers apples over bananas, Mark preferring bananas more than Jack implies Mark prefers bananas the most.

So in terms of apples preference:

- Jack > Sarah

- Mark prefers bananas → apples preference is less than Jack’s

    Step 3: Conclusion

- Jack likes apples the most.


# Verification

    Yes, it did provide the solution in a step by step format followed by the answer.
