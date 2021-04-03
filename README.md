# Handbook of Best Practices

## Coding Standards

In the Software Development Industry, standardization has a positive impact in every business therefore certain coding
standards are essential for successful software development. They are an array of actions that can be defined for a
particular programming language specifying a programming style, the methods and different procedures that need to be
followed.

A coding standard makes sure that all developers working on a project follow certain guidelines. It is very important
for the programmers to maintain the coding standard, so it can be easily understood and maintained with proper
consistency.

&nbsp;

#### Purpose of Having Coding Standards:

* A coding standard gives a uniform appearance to the code written by various developers.
* It increases the efficiency of developers and promotes robust programming.
* It improves reliability, helps maintain the code and reduce its complexity.
* It reduces code duplication and helps code reuse making it easier to detect errors.

&nbsp;

##### Some of the coding standards are given below:

### 1. Indentation

---
Proper and consistent indentation should be followed throughout the code to increase the readability of the code. For
this, developers should make proper use of whitespaces:

* Between two function arguments there must be a space after a comma.
* Appropriate indentation should be there at the start and the end of each block in the program.
* Nested blocks of code should be properly spaced and indented.
* All braces should start from a new line, and the code that follows the braces should also start on a new line.

```html

<div style=”background-color: blue”> <! –div start–>

    <h2> A heading</h2>

    <p> A paragraph.</p>

</div> <! — div end –>

```

&nbsp;

### 2. Principle of DRY

When coding, developers should remember the principle of DRY, which means
**"Don't Repeat Yourself"**. It is a good practice to avoid duplication of code as it can eventually lead to
unmaintainable and buggy systems. Therefore, the code in the application should be such that the same code is not
repeated over and over.

```python
def my_function():
    print("I will not repeat my code!")
    print("I will not repeat my code!")
    print("I will not repeat my code!")
    print("I will not repeat my code!")
    print("I will not repeat my code!")
```

&nbsp;

### 3. Writing Test Cases

---

By writing test cases you will know what your methods do, what they take and what they return. This way you know when
your function should work or when it should fail. Functions should always be based on test cases, not the other way
around.

&nbsp;

### 4. Avoid Commenting on Obvious Things

---

While following the standards, make sure that you do not comment unnecessarily. Too much explanation will make your code
look clumsy. For example:

```java
for(int i=0;i<10;i++) //for loop starts here
        { //starting brace

        // logic starts here

        } //ending brace
```

&nbsp;

|References |
|---|
|[Coding Standards and Guidelines](https://www.geeksforgeeks.org/coding-standards-and-guidelines/)|
[Importance of Code Quality and Coding Standard](https://www.multidots.com/importance-of-code-quality-and-coding-standard-in-software-development/)|
|[Coding Standards and Best Practices](https://www.aversan.com/coding-standards-and-best-practices-2/)|
|[Best coding practices](https://en.wikipedia.org/wiki/Best_coding_practices)|
