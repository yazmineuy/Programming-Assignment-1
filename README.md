# Programming-Assignment-1
A collection of 3 Python programming challenges focusing on string manipulation, dictionary operations, and list unpacking. Includes solutions for Alphabet Soup, Emoticon Converter, and List Unpacking problems.

# Python Programming Assignment 1

## 📋 The Problems

### 1. Alphabet Soup Problem
**Task**: Create a function that takes a string and returns a string with its letters in alphabetical order.

**Example**: 
- `alphabet_soup("hello")` ➞ `"ehllo"`
- `alphabet_soup("hacker")` ➞ `"acehkr"`

**Solution**: 
- Uses Python's built-in `sorted()` function to sort characters
- `join()` method to convert back to string
- Handles user input with `input()`

### 2. Emoticon Problem
**Task**: Create a function that changes specific words into emoticons. Replace words with their corresponding emoticons.

**Emoticon Mapping**:
- `"smile"` → `":)"`
- `"surprised"` → `":0"`
- `"silly"` → `":p"`
- `"shocked"` → `"D:"`

**Example**:
- `emotify("Make me smile")` ➞ `"Make me :)"`
- `emotify("I am surprised")` ➞ `"I am :0"`

**Solution**:
- Dictionary-based word replacement
- Iterates through emotion-emoticon pairs
- Uses `str.replace()` for substitution

### 3. Unpacking List Problem
**Task**: Unpack a list into three variables (first, middle, last) where middle contains all elements between the first and last.

**Example**: 
- Input: `[1, 2, 3, 4, 5, 6]`
- Output: `first: 1 middle: [2, 3, 4, 5] last: 6`

**Solution**:
- List slicing for element extraction
- Multiple variable assignment
- User input parsing with `map()` and `split()`
