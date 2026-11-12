In this exercise, you'll strengthen your understanding by predicting output before executing code.

1. For each operation below, **predict what you think the output will be** before running the code
2. Write your predictions by completing the comment
3. Run each code cell in order and check your predictions
4. If you got it wrong, try to understand why before moving on.

# Hints

Click below to reveal hints.

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

Click below for an explanation of the results of the above code cell.

>[!HIDDEN]
> * The first character of the string is at index 0 (remembering the first character is at index 0), so `string[0]` gives 'P'.
> * `string[2]` gives the third character, which is 't'.
> * `string[-1]` gives the last character (remembering negative indices count from the end), which is 'n'.

```py-cell
print(string[1:4])    # Prediction: ?
print(string[0:3])    # Prediction: ?
print(string[-2:])    # Prediction: ?
```

Click below for an explanation of the results of the above code cell.

>[!HIDDEN]
> * `string[1:4]` gives the substring from index 1 to 3 (stop index is exclusive), which is 'yth'.
> * `string[0:3]` gives the substring from index 0 to 2, which is 'Pyt'.
> * `string[-2:]` gives the last two characters (omitting the stop index means the slice goes to the end), which is 'on'.

```py-cell
print(string[::2])    # Prediction: ?
print(string[1::3])   # Prediction: ?
print(string[::-1])   # Prediction: ?
```

Click below for an explanation of the results of the above code cell.

>[!HIDDEN]
> * `string[::2]` gives every second character starting from index 0 (omitting the start and stop indices means the slice goes from the beginning to the end), which is 'Pto'.
> * `string[1::3]` gives every third character starting from index 1 (omitting the stop index means the slice goes to the end), which is 'yh'.
> * `string[::-1]` gives the string in reverse order (a negative step means the slice goes backward), which is 'nohtyP'.
