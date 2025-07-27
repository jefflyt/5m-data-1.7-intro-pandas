# Assignment

## Brief

Write the Python codes for the following questions.

## Instructions

Paste the answer as Python in the answer code section below each question.

### Question 1

Question: Select all numeric columns except float from the DataFrame `dft`.

Answer:

```python
dft.select_dtypes(exclude=['float'])

```

### Question 2

Question: How do you return the last 3 rows of a DataFrame `df`?

Answer:

```python
dft.tail(3)
```

### Question 3

Question: Return the minimum and maximum of a Series `x` as a new Series with the index `["min", "max"]`.

Answer:

```python
pd.Series([dft.min(), dft.max()], index = ["min", "max"])
```

### Question 4

Question: Multiply `df1` and `df2` (two DataFrames) with a `fill_value` of 1.

Answer:

```python
df1.multiply(df2, fill_value=1) 
```

### Question 5

Question: How do you create a DataFrame from a nested dictionary of dictionaries?

```python
nested_dict = {'A': {'a': 1, 'b': 2}, 'B': {'a': 3, 'b': 4}}
```

Answer:

```python
frame = pd.DataFrame(nested_dict)
```

## Submission

- Submit the URL of the GitHub Repository that contains your work to NTU black board.
- Should you reference the work of your classmate(s) or online resources, give them credit by adding either the name of your classmate or URL.
