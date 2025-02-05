# Table Of Contents

- [Print Function Tutorial](#print-function-tutorial)
- [Advanced Print Function](#advanced-print-function)

---

# Print Function Tutorial

### Code and Its Explanation

```python
print("Dad!")
print("Mom!!")
```

#### Line 1:
```python
print("Dad!")
```
- The `print` function is used to output text to the console.
- The text inside the parentheses, enclosed in double quotes (`" "`), is called a **string**.
- In this case, the string is `"Dad!"`, so the console will display:
  ```
  Dad!
  ```

#### Line 2:
```python
print("Mom!!")
```
- The `print` function is again used to output text.
- The string `"Mom!!"` is passed as an argument to `print`.
- This will output:
  ```
  Mom!!
  ```

### Understanding the `print` Function
- `print()` is a built-in Python function that outputs text to the console.
- It takes one or more arguments, typically strings, and displays them as output.
- Strings can be enclosed in either single quotes (`'`) or double quotes (`"`).
- The `print` function automatically adds a newline (`\n`) at the end, meaning each `print` statement starts on a new line in the output.

### Expected Output:
```
Dad!
Mom!!
```

---

# Advanced Print Function 

### Code and Its Explanation

1. **String Concatenation with the `+` Operator**

    ```python
    print("Hello" + " world" + "!")
    ```
    - **Explanation:**  
      This statement concatenates three string literals: `"Hello"`, `" world"`, and `"!"` using the `+` operator. The result is a single string: `"Hello world!"`, which is then printed.

2. **Using Different Quote Styles to Include Quotes in Strings**

    ```python
    print('He said "good!"')
    ```
    - **Explanation:**  
      The outer quotes are single quotes, which allows the inclusion of double quotes inside the string without any need for escaping. This prints:
      ```
      He said "good!"
      ```

3. **Another Example of Quote Usage**

    ```python
    print("He said 'good!'")
    ```
    - **Explanation:**  
      Here, the outer quotes are double quotes, so single quotes can be used directly inside the string. The output is:
      ```
      He said 'good!'
      ```

4. **Escaping Quotes Inside Strings**

    ```python
    print("He said \"Let\'s go!\"")
    ```
    - **Explanation:**  
      This statement demonstrates escaping characters using the backslash (`\`). The double quotes inside the string are escaped (`\"`) so that they are not mistaken for the string delimiters. Similarly, the single quote in `"Let's go!"` is escaped (`\'`) to ensure it is treated as part of the string. The output is:
      ```
      He said "Let's go!"
      ```

5. **Printing a Newline**

    ```python
    print("\n")
    ```
    - **Explanation:**  
      The string `"\n"` represents a newline character. When printed, it outputs a blank line. This is useful for adding vertical spacing in the output.

6. **Using Newline Characters Within a String**

    ```python
    print("Hello!\nHi!")
    ```
    - **Explanation:**  
      This string contains an embedded newline character (`\n`). When printed, `"Hello!"` is printed on the first line and `"Hi!"` on the second line:
      ```
      Hello!
      Hi!
      ```

7. **Printing a Multiline String with Triple Quotes**

    ```python
    print('''No man is an island,
    Entire of itself,
    Every man is a piece of the continent,
    A part of the main.
    If a clod be washed away by the sea,
    Europe is the less.
    As well as if a promontory were.
    As well as if a manor of thy friend’s
    Or of thine own were:
    Any man’s death diminishes me,
    Because I am involved in mankind,
    And therefore never send to know for whom the bell tolls;
    It tolls for thee.
    ''')
    ```
    - **Explanation:**  
      Triple quotes (`'''...'''`) allow for the creation of a multiline string. This statement prints the entire block of text exactly as it appears, preserving all line breaks and spaces. This is especially useful for printing large blocks of text, such as paragraphs or formatted data.

### Advanced `print` Usage Summary

- **String Concatenation:**  
  Use the `+` operator to combine multiple strings into one before printing.

- **Handling Quotes:**  
  Choose different types of quotes (single vs. double) to include quotes within your string without escaping, or use the backslash (`\`) to escape them when necessary.

- **Special Characters and Escape Sequences:**  
  Use escape sequences like `\n` for newline, `\t` for tab, etc., to format the output.

- **Multiline Strings:**  
  Use triple quotes (`'''...'''` or `"""..."""`) to create strings that span multiple lines. This helps in preserving the format and layout of the text.

```python
print("Hello" + " world" + "!")
print('He said "good!"')
print("He said 'good!'")
print("He said \"Let\'s go!\"")

print("\n")
print("Hello!\nHi!")

print("\n")
print('''No man is an island,
Entire of itself,
Every man is a piece of the continent,
A part of the main.
If a clod be washed away by the sea,
Europe is the less.
As well as if a promontory were.
As well as if a manor of thy friend’s
Or of thine own were:
Any man’s death diminishes me,
Because I am involved in mankind,
And therefore never send to know for whom the bell tolls;
It tolls for thee.
''')
```

### Expected Output:
```
Hello world!
He said "good!"
He said 'good!'
He said "Let's go!"

Hello!
Hi!

No man is an island,
Entire of itself,
Every man is a piece of the continent,
A part of the main.
If a clod be washed away by the sea,
Europe is the less.
As well as if a promontory were.
As well as if a manor of thy friend’s
Or of thine own were:
Any man’s death diminishes me,
Because I am involved in mankind,
And therefore never send to know for whom the bell tolls;
It tolls for thee.
```
