# GResearch-Interview
Question bank

Agenda

-  What is the difference between the code-pair types? Is this group comfortable with the content

-  We have >100 questions in the bank. Can we reduce this to 10 for each interview category as example questions or shall we simply have them all? If not, can we use today to put these into the various categories?

-  For those we decide on, can we collate a scoring schema so anyone can pick them up and know how to approach the question and assess consistently against other candidates? If so, how best to achieve this?

Code-Pair

QP: https://confluence.uberit.net/display/DEVREC/Phone+Screening+Questions

DD: https://confluence.uberit.net/display/DEVGLO/Phone+screen+interview+questions

Technical Interviews

https://confluence.uberit.net/pages/viewpage.action?pageId=30966440

https://confluence.uberit.net/pages/viewpage.action?pageId=70294043

https://confluence.uberit.net/display/LLE/Interview+Questions

https://confluence.uberit.net/display/DEVREC/Interview+Questions+List

https://confluence.uberit.net/display/DEVREC/1a.+Coding+exercise

https://confluence.uberit.net/display/ENG/%5BProgramming%5D+RPN -- algo

https://confluence.uberit.net/display/ENG/%5BProgramming%5D+Implement+tail -- algo

https://confluence.uberit.net/display/ENG/%5BDesign%5D+Scaling+data+loading+in+a+trading+system -- design 

https://confluence.uberit.net/display/ENG/%5BProgramming%5D+Scripting -- design

https://confluence.uberit.net/pages/viewpage.action?pageId=55134829 -- design 

https://confluence.uberit.net/display/ENG/%5BProgramming%5D+SQL -- practical code

https://confluence.uberit.net/display/ENG/OS+and+Linux+questions -- practical code

https://confluence.uberit.net/display/ENG/%5BProgramming%5D+Code+comprehension -- practical code

- [ALGO] Solve the Dutch national flag problem - https://en.wikipedia.org/wiki/Dutch_national_flag_problem

- [ALGO] Array Rotation https://confluence.uberit.net/display/DEVGLO/%5BAlgo%5D+Array+Rotation

- [CODING] https://confluence.uberit.net/download/attachments/70294043/bad-code-exercise.pdf?api=v2

- [DESIGN] Describe how to scale up a website -- (open question)

- Various -- see sub-pages https://confluence.uberit.net/x/kpp0Aw

1:

Q) A fairly simple coding-on-paper exercise ("triangular string")

(write a function to recognise strings like "xyyzzz", "abbcccdddd", "rooyyygggg")

Hoping to see if they:

- Can reasonably quickly write reasonably correct code

Follow up questions: None

Q) What's a deadlock, techniques for preventing them / coping with them

Hoping to see if they:

- Have knowledge of concurrency

- Have practical experience of dealing with nasty concurrency problems

Follow up questions: None, though can be opportunity to ask about nastiest bug seen.

Q) How do databases (or other storage systems) you've worked with handle concurrency

Hoping to see if they:

- Have experience with some sort of database systems

- Have some awareness of transactions / multi-version-concurrency

Follow up questions: None

Q) How does the internet work

Hoping to see if they:

- Can structure their explanation sensibly

- Demonstrate some level of web/networking knowledge

- Admit to what they don't know

Follow up questions: None, though can drill-down into particular area (e.g. TCP).

Q) Fairly easy algorithm question - "change one letter a time" puzzle solver

(e.g. given HEAD and LOAF produce HEAD -> LEAD -> LEAF -> LOAF)

Hoping to see if they:

- Ask sensible questions to clarify requirements / take feedback on-board

- Identify problem as breadth-first-search (not depth-first)

- Come up with sensible solution without actually writing code

Has possible extension questions like:

- what if want to solve many of these problems

- what if want to find a non-optimal solution very quickly

Q) Ask about trade-offs of unit vs integration/regression testing and use of mocks

Hoping to see if they:

- have experiencing testing complex systems, since this is relevant to our work

- hold some opinions but aren't too extreme, can get a bit of a discussion going

Has possible extension questions like:

- particular libraries used

- experiences on particular projects from CV

Q) Tell me about your choice of recent project from CV

Hoping to see if they:

- can explain something I know nothing about well

- made significant contribution to something interesting/difficult/relevant

Follow up questions: None

2:

Programming Question

-  Ask candidate to Implement a sorted doubly linked list or implement a concurrent q

-  Follow up with discussion of threading issues [locking, lock free ...]

-  Follow up with discussion of cache issues (false sharing)

Garbage Collection

-  Ask candidate to explain what they know about Garbage collection

-  Expecting to hear about GC roots

-  Maybe something about Mark/Sweep

-  Maybe something about generations

-  Follow ups on object moving & reference updating

-  Any other information they have about it

Describe some bit of work they did

-  What did they do?

-  What they think could have been better?

Describe the architecture of some system they worked on

-  Thoughts about microservices

-  Experience of messaging between services

-  Long term storage options (database, nosql, filesystems...)

We've not actually interviewed / hired anyone new since the original team (RQUX) was formed back in May last year.  The skillset I was looking for was quite specialised (UI/UX) so I freestyled a lot with the types of questions that I asked, rather than it being a formally structured interview.  Most of the focus did to be around themes of "what is good design?" and how the candidates worked with users to generate requirements.  There were technical questions, but they were more general (and of the sort that you would get from other hiring managers I assume)

For the practical, I asked candidates to build me a web app to display a set of data (5 items, 3 fields each), but with any framework of their choice.  It was more to see that they could actually walk the walk and for me to see if how they would take it design-wise.

Thanks

Alex

Alex Whitlock

Talent Acquisition
