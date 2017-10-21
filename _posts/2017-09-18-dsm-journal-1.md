---
layout: post
title: "DSM Journal 1"
date: 2017-09-18
---

I plagiarized my homework this week. I don't mean just poorly paraphrasing Foucalt in an essay either; I copied and pasted text from the internet. This is something I would normally feel ashamed of, but I am coming to learn that gaining a semblance of code literacy involves activities that easily meet the definition of cheating in other classes.

The practice project I was working on from *Automate the Boring Stuff with Python* required I write a function with two key tasks: figure out the longest word in each of three columns to determine column width, and print a list of words to each column. I was especially proud of coding the first task - it was my first experience using a nested loop in Python!


 ```   colWidths = [0] * len(table)
    for i in range(len(table)):
        for j in range(len(table[i])):
            if len(table[i][j]) >= colWidths[i]:
                colWidths[i] = len(table[i][j])
            else:
                colWidths[i] = colWidths[i]
```
<sub>Hell yeah, look at that sweet baby.</sub>

Error messages began to appear in the code written to complete the second task, and my Google searching lead me to forums that described the cause of the problem in very specific computational jargon. I reluctantly searched for the chapter number of the book, which lead me to [this thread on Stack Overflow](https://stackoverflow.com/questions/34488115/automate-the-boring-stuff-chapter-6-table-printer-almost-done). What initially surprised me was the variety of solutions, each utilising different programming structures to produce the required effect.

I struggled ethically with the act of of copy-pasting, despite it becoming a somewhat normalised technique in software development. Bergman et. al.'s (2004) ethnographic study demonstrates that copy-pasting is a common practice among programmers, but Pheatt and Rogers (2009, p. 187) discourage 'using code out of context' of its source program, as it could potentially interfere with your existing code in unexpected ways.

To mediate this decision I felt somewhat uneasy with, I spent a while on the Stack Overflow thread comparing the code I had written with the various solutions proposed. The example that was closest to mine differed by only a line or two. I then stepped through the section of the example code I was struggling with, recording the variable values at each line, in order to understand what was going on. This method allowed me to understand what was going wrong with code, rather than blindly trusting someone else’s code.

The textbook I am working from states bluntly: 'an everyday part of any software developer's job is looking up answers to technical questions' (Sweigart 2015, p.9). My experiences with coding this week have developed my understanding of what I can expect from these answers, and how to reconcile the difference between this kind of research and the kind I am used to with my usual academic subjects.

**References:**

Bergman, L., Kim, M., Lau, T. & Notkin, D. 2004, 'An Ethnographic Study of Copy and Paste Programming Practices in OOPL', *Proceedings of the 2004 International Symposium on Empirical Software Engineering (ISESE’04)*, IEEE, Redondo Beach, CA, pp. 83-92.

Pheatt, C. & Rogers, J. 2009, 'Integrating antipatterns into the computer science curriculum', *Journal of Computing Sciences in Colleges*, vol. 24, no. 5, pp. 183-189.

Stack Overflow 2017, *Automate the Boring Stuff Chapter 6 Table Printer Almost Done*, Stack Exchange Inc, viewed 20 October 2017, <https://stackoverflow.com/questions/34488115/automate-the-boring-stuff-chapter-6-table-printer-almost-done>.

Sweigart, A. 2015, *Automate the boring stuff with python : practical programming for total beginners*, No Starch Press, San Francisco.






