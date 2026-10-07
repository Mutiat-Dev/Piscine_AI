# Extract structured data from unstructured input.

# Vague text
 "John Doe, age 29, lives in Paris and works as a software engineer."

# Template prompt

    "John Doe, age 29, lives in Paris and works as a software engineer.

from the text above, extract the following fields from the text: Name, Age, Location, Occupation. Return the output in JSON format." 

# Model output

```    
{
  "Name": "John Doe",
  "Age": 29,
  "Location": "Paris",
  "Occupation": "Software engineer"
}
```
# Validate the output and ensure consistency across multiple inputs.

    Yes, it's in a JSON format
