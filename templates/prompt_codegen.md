# AI Prompt Template: Code Generation

Use when you want the AI to write code from a specification.

**System Prompt:**  
*You are a helpful assistant that outputs code in [language]. Follow instructions carefully.*

**User Prompt Template:**  
```
Write a function in [language] that [does X, given Y]. 
Use clear variable names and comments.
```

**Example:**  
User: *“Generate Python code for a function `add_numbers(a, b)` that returns the sum.”*  
AI: *```python
def add_numbers(a: int, b: int) -> int:
    return a + b
```*  
