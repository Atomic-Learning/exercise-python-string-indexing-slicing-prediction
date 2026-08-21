In this exercise, you'll strengthen your understanding by predicting output before executing code.

1. For each operation below, <strong>predict what you think the output will be</strong> before running the code
2. Write your predictions by completing the comment
3. Run each code cell in order and check your predictions
4. If you got it wrong, try to understand why before moving on.

# Tips

>[!HIDDEN]
>
> * Remember: Python uses zero-based indexing (starts at 0, not 1)
> * Negative indices count backward from the end
> * In slicing `[start:stop]`, `stop` is exclusive (not included)
> * The step parameter determines how many characters to skip

```py-cell
string = "Python"

print(string[0])      # Prediction: ?
print(string[2])      # Prediction: ?
print(string[-1])     # Prediction: ?
```

```py-cell
print(string[1:4])    # Prediction: ?
print(string[0:3])    # Prediction: ?
print(string[-2:])    # Prediction: ?
```

```py-cell
print(string[::2])    # Prediction: ?
print(string[1::3])   # Prediction: ?
print(string[::-1])   # Prediction: ?
```

```py-cell
print(string[0])      # Prediction: ?
print(string[-1])     # Prediction: ?
print(string[1:4])    # Prediction: ?
print(string[::3])    # Prediction: ?
print(string[1:6:2])  # Prediction: ?
print(string[-3:])    # Prediction: ?
```