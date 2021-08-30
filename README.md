>From the book: Automate the Boring Stuff with Python. Writer: Al Sweigart

# Pretty Character Count

It's a practice project for python beginners.

*HINT: If you `import` the `pprint module` into your programs, you’ll have access to the `pprint()` and `pformat()` functions that will `“pretty print” a dictionary values`. This is helpful when you want a cleaner display of the items in a dictionary than what `print()` provides.*

Modify the previous [characterCount.py](https://github.com/mullaghori/Character-Count/blob/main/README.md) program and save it as `prettyCharacterCount.py`.

***👉 No.1 This time, when the program runs, the output should looks much cleaner, with the keys sorted.
```***
{' ': 13,
 ',': 1,
 '.': 1,
 'A': 1,
 'I': 1,
 'a': 4,
 'b': 1,
 'c': 3,
 'd': 3,
 'e': 5,
 'g': 2,
 'h': 3,
 'i': 6,
 'k': 2,
 'l': 3,
 'n': 4,
 'o': 2,
 'p': 1,
 'r': 5,
 's': 3,
 't': 6, 
 'w': 2,
 'y': 1} 
```
*HINT: The `pprint.pprint()` function is especially helpful when the `dictionary` itself contains `nested lists` or `dictionaries`. If you want to obtain the `prettified text as a string value` instead of playing it on the screen, call `pprint.pformat()` instead. These two lines are equivalent to each other:*
*`pprint.pprint(someDictionaryValue)`
`print(pprint.pformat(someDictionaryValue))`*
