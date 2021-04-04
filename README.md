## Code Reviews


Code reviews are a very important part of the software development process which involves analysing
the source code to identify bugs. A code review process is typically conducted 
before merging with the codebase.

Code reviews improve code quality making your codebase more stable. They prevent bugs and errors
from getting into your project at an early stage of the software development process. 



![](Images/codeReviewIntro1.png "code review image")

&nbsp;

#### The following  checklist will give you an idea of what you should look for when reviewing the code:

&nbsp;

&nbsp;

### 4. Reviewers guidelines on code reviews

---

A code review is a process where someone other than the engineers of a piece of code examines that code. The following table showcases what code reviewers Look For in a code review:

&nbsp;

| Features  | Explaination |
| ------ | ----------- |
| Design   | well-designed and appropriate system |
| Functionality | code behave as intended by the developer |
| Complexity    | simplicity and ease of read |
| Tests    | correct and well-designed automated tests |


&nbsp;


### 5. Examples of code reviews

---

**1. Comments Where Needed** 

Some comments are unnecessary. Direct transliterations of code into English, for example, do nothing to improve understanding, because you should assume that your reader at least knows Java:

```
while (n != 1) { // test whether n is 1   (don't write comments like this!)
   ++i; // increment i
   l.add(n); // add n to l
}
```

**2. Use Good Names** 

Comments should be avoided by making the code itself more readable using better names that describe the methods and variables:

For example replacing this comment: 
```
int tmp = 86400;  // tmp is the number of seconds in a day (don't do this!)

}
```
with the following name variable:
```
int secondsPerDay = 86400;

}
```

&nbsp;


|References |
|---|
|[12 Best Code Review Tools for Developers](https://kinsta.com/blog/code-review-tools/)|
|[Reviewers guidelines on code reviews](https://google.github.io/eng-practices/review/reviewer/looking-for.html)|
|[Examples of code reviews](https://web.mit.edu/6.005/www/fa15/classes/04-code-review/)|