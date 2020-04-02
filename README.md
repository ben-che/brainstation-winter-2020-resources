# Resources for 2020 Winter Brainstation Grads [WIP]

Resources for your post-bootcamp career! I'll keep updating this README as time passes - if you want updates, you can either `watch` or `star` this repo! If there's anything you'd like me to add, feel free to message me on Slack, or [create an issue](https://github.com/ben-che/brainstation-winter-2020-resources/issues)

### CS fundamentals
- [Ossu's CS Fnndamentals on Github](https://github.com/ossu/computer-science#core-cs) - REALLY good course that goes over all aspects of computer science; not only does it go over theory, but it touches on mathematics and other programming languages that are used in machine learning and software engineering
- [Teach Yourself CS](https://teachyourselfcs.com/) - Learn about specific parts of computer science that aren't covered in bootcamps, you know how to write JS, and now you can understand what's going on under the hood

### Data structures and algorithms 
When I was doing my initial set of interviews, I found a really good reddit post that explained the concept of a data structure. From there, I was able to google things I didn't udnerstand, and that's where I got the majority of my initial learnings from:

[What are data structures?](https://www.reddit.com/r/learnprogramming/comments/2b16g8/eli5_what_are_data_structures/cj0sx9a/)

Simply put, data structures are ways in which we can organize information to make use of it for computation. Data structures and Algorithms are the core pillars of Computer Science. Almost all code consists of some sort of algorithms operating on one or more data structures. As a real-life example of a data structure, consider a dictionary. A dictionary is a book which associates words with definitions of those words, and is organized alphabetically. The way it is organized allows you to search for a particular word quickly, and access the definition for that word. In programming, we actually have a data structure called a dictionary, also known as an "associative array" or a "hash table", which does something similar. There are lots of other data structures such as linked lists, arrays, trees and so on which all have different strengths and weaknesses. As you learn more about programming you will become familiar with several of the most common data structures no doubt.

> Is it a piece of code? Is it particular to one language?

A data structure is really a theoretical construct. In textbooks and computer science papers you can find lots of definitions of data structures which are completely abstracted away from any particular real-world programming language. In principle any data structure could be implemented in any programming language.

However life is not all theory. In practical programming we need to use various data structures all the time. So every programming language include concrete implementations of different data structures, either as a built-in part of the language or with the standard libraries. All programming languages support some primitive data structures but which ones precisely and how they are implemented depends on the language.

> Who comes up with a better data structure?

Algorithms and data structures go hand-in-hand and both are very much still active areas of research. Computer science researchers are always trying to come up with better data structures that can solve various problems. There are many many specialized data structures that are relevant in different fields from databases to artificial intelligence to computer graphics, computational biology, etc. A lot of computer science papers are essentially like: "We identified a problem, so we created this new algorithm based on this new data structure that is some % faster than the previous best one, here are some benchmark results."

> Can all programmers write data structures?

A programmer with a formal education in computer science will certainly know how to write their own implementations of all the classic data structures. However in the industry, programmers don't often have to resort to reinventing the wheel. For most problems you will encounter as you make your iPhone app or your web service or whatever you might be working on you will be able to use the very finely-tuned, efficient, thoroughly tested and debugged data structures provided with your language or there will be some library available that gives you what you need.

> What makes one better than another?

Sometimes two data structures can be used to solve the same problem, but one will be faster than the other at the cost of taking up more memory. Often times it there will be tradeoffs like that which a programmer has to weigh up against one another as they choose the best approach to the task. Every data structure supports a certain set of operations that allow you to read from / write to / change the structure. Each structure can do some operations faster than others, and which structure you choose usually has to do with what exactly you intend to use it for.

#### Here are some courses / readings for this topic:

- [Different types of algorithms](https://towardsdatascience.com/top-algorithms-and-data-structures-you-really-need-to-know-ab9a2a91c7b5) - Touches on different types of algorithms, and the most common search and sorting algos in interviews
- [Easy to Medium Data Structures](https://www.udemy.com/course/introduction-to-data-structures/) - Really good course that covers a lot of commonly asked questions about common data structures. Here, you'll learn about stacks, queues, linked lists, hash tables and trees - all of which are pretty standard questions that one might get in an engineering interview
- [Introduction to Data Structures and Algos](https://www.coursera.org/learn/algorithms-part1) - The code itself is in Java, but a lot of the concepts can be reimplemented in Javascript. The algorithms can also be applied universally to most programming languages as well.
- [Advanced Algorithms](https://www.coursera.org/learn/algorithms-part2) - Probably won't run into any of these questions in an entry level web development job, but it could be cool to just listen and read up on if you're interested

### Whitebording questions
I'll flesh this part out a bit more, but some of the commonly asked interview questions for entry level devs are:
- fizzbuzz
- isPalindrome
- contians substring?

Some common algo questions involve:
- array sorting algorithms
- Matricies (2D, 3D, nD arrays)

Some architecture and systems designs questions are:
- Google's elevator problem
- Design a parking lot system
- Traffic light system

### Portfolio inspo
Some links to get some inspiration on different portfolios around the world. Keep in mind that a developer's portfolio might differ greatly from a designer's, data scientist's or PM's portfolio:
- [Awwwards](https://www.awwwards.com/)
- [One Page Love](https://onepagelove.com/)

