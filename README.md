## Code Reviews

Code reviews are a very important part of the software development process which involves analysing
the source code to identify bugs. A code review process is typically conducted 
before merging with the codebase.

Code reviews improve code quality making your codebase more stable. They prevent bugs and errors
from getting into your project at an early stage of the software development process. 

![](Images/codeReviewIntro1.png "code review image")

&nbsp;

#### The following steps will give you an idea of what you should look for when reviewing the code:

### 1. How to perform a Tool-Assisted code review

---
A tool-assisted code review process involves the use of a specialised tool to facilitate the process of code review such as Crucible, Review Board and GitHub. A tool generally helps reviewers with the following tasks:

> <em> "you may be losing efficiency if you haven’t switched to a code review tool" (Daityari) </em>

+ Assess the efficacy of the code review process with metrics.
+ Facilitate a conversation between reviewers and developers.
+ Organise and display the updated files in a change.

&nbsp;

### 2. How to Make Code Reviews Better

---
One of the ways to make code reviews better is through tone of the review which can greatly influence morale within teams.

**Good code reviews**: is when a reviewer has an open mind and not judge and make opinionated statements. These views should be clarified instead of forcing correction.

**Better code reviews**: the reviewer is more empathetic and takes time to go through every single line of the code. They have positive feedback and applaud nice solutions.

&nbsp;


### 3. Code Review Checklist

---
The following code review checklist gives an idea about the various aspects you need to consider while reviewing the code:

**1. Non-functional requirements:** The code should meet the non-functional requirements such as Maintainability (Supportability) where The application should require the least amount of effort to support in near future. It should be easy to identify to fix any defects.

**2. Code formatting:** includes the use of alignments, proper naming conventions and it should fit the standard 14 inch laptop screen.

**3. Object-Oriented Analysis and Design (OOAD) Principles:** such as Single Responsibility Principle (SRS), Open Closed Principle and Liskov substitutability principle.

&nbsp;

### 4. Reviewers guidelines on code reviews

---

A code review is a process where someone other than the engineers of a piece of code examines that code. The following table showcases what code reviewers Look For in a code review:

&nbsp;

| Features  | Explanation |
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
|[How to perform a Tool-Assisted code review](https://stackoverflow.blog/2019/09/30/how-to-make-good-code-reviews-better/)|
|[How to Make Good Code Reviews Better](https://stackoverflow.blog/2019/09/30/how-to-make-good-code-reviews-better/)|
|[Code Review Checklist](https://www.evoketechnologies.com/blog/code-review-checklist-perform-effective-code-reviews/)|

