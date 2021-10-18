1. The bug is that both numbers are getting converted to strings, so that when they get concatenated and returned as a result, it is as a string
rather than as an int.
2. My fix would be to take the result from getting the element from the doc (so num1 and num2) and converting it to an int