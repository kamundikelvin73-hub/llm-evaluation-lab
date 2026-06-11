# Coding Prompts

These prompts test whether an AI model can explain, debug, optimize, and document code.

## Prompt 1: Bug Detection

Review the following Python function and identify possible bugs:

```python
def average(numbers):
    return sum(numbers) / len(numbers)
```

Expected evaluation focus:

- Edge case detection
- Explanation quality
- Correctness
- Suggested improvement

## Prompt 2: SQL Query Review

Review this SQL query and explain what it does:

```sql
SELECT department, COUNT(*) 
FROM tickets
WHERE status = 'open'
GROUP BY department;
```

Expected evaluation focus:

- SQL understanding
- Clear explanation
- Accuracy
- Ability to identify missing context

## Prompt 3: Code Optimization

A script processes support tickets one by one and takes too long. Suggest ways to improve performance.

Expected evaluation focus:

- Practical optimization
- Batch processing awareness
- Data workflow understanding
- Clear prioritization

## Prompt 4: Documentation

Write a short README section explaining how to run a Python data-cleaning script.

Expected evaluation focus:

- Clarity
- Completeness
- Instruction following
- Technical communication

## Prompt 5: Error Handling

Improve a Python function so it handles missing values safely.

Expected evaluation focus:

- Safety
- Reliability
- Code quality
- Explanation
