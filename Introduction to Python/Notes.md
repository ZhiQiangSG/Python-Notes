# What is Python?
- Created by Guido van Rossum, and released in 1991
- A high level programming language
- Designed to be easy to read and write

## Application
1. Data Science and Analytics
2. Artificial Intelligence and Machine Learning
3. Web Development (Server Side)
4. Automation and Scripting
5. Game Development (Simple games)
6. Internet of Things (IOT)

# Print() Function
```python
print("Hello World")
```
- "print" is an in-built function of Python, the command that is used to display information on the screen.
- "Hello World" is the argument of the function, the information that will be displayed on the screen.
- The output of a Print() Function will always be a string data type (explained later).
- The Print() Function allows you have to multiple arguments.
- 

# Data Types: int, float, and str
- **String (str)**: store text. enclosed by double quotation marks ("") or single quotation marks ('')
- **Float (float)**: store numbers that can have decimals (E.g. 12.1)
- **Integer (int)**: store numbers that are only integers (E.g. 5)
- There are more data types, but the focus for this section is this three data types.
- For more data types, refer to [W3 schools](https://www.w3schools.com/python/python_datatypes.asp) and [GeeksforGeeks](https://www.geeksforgeeks.org/python-data-types/)
- The Print() function can print out all data types. Example:

**Code**
```python
print("Hi", 1, 14.5)
```
**Output**
```
Hi, 1, 14.5
```

## Further Formmating with Print() Function
  - To set the data types,
    - For strings, insert the argument within the empty brackets of "str()"
      ```python
      str("Hello World")
      ```
    - For float, insert the argument within the empty brackets of "float()"
      ```python
      float(12.5)
      ```
    - For integer, insert the argument within the empty brackets of "int()"
      ```python
      int(5)
      ```  
  - To separate the string (in this case, "Hello World") into individual lines (i.e. one line, one word), add \n

    **Code**
    ```python
    print("Hello \nWorld")
    ```
    **Output**
    ```python
    Hello
    World
    ```
    Note:
    - Only work for string data type
    - "\n" is an example of an [escape character](https://www.w3schools.com/python/gloss_python_escape_characters.asp). 
  - 

