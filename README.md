# Cell Automata Capstone Project/Unit
by Kiana Herr, Sam Lojacono, William LaMorie

-----

### General Overview
2 party cellular automata "game" in python (Full unit project).

This unit would serve as a seminal unit for covering all the material that would be expected in a concurrent enrollment CS I course (followng NYSCC specs). It would include topics such as: polymorphism, object design, arrays, looping, conditionals, and other core programming topics in computing.

The base game is played on a 2d grid (or 2d array) and each locus has the state of either empty, a producer object, or a consumer object. Producer objects can populate quickly, and have very loose criteria for survivability. Consumer objects have a longer life cycle, and require food in the form of moving to a prey object to survive, and do not manage to continue to survive if they have not consumed food recently.

---

### Motivation for Unit
We decided to develop this unit because it fits well into the expectations of a seminal project for Computer Science I with the college now partner institution we are working with, and because it allows for many modes of presentation to adapt to the "skin" we are using/have used in our own courses. For example, it can be paired with a graphics pack to be turned into a more of a game like structure. It could be run on a raspberry pi and output to a light board. It could be extended from its basic presentation with a GUI that allowed alterations to player rules. A finished portable version of the program can also be used more broadly for integrated instruction to look at modeling real world events or processes within a life science curriculum.

Elements of the unit/project can also be built on earlier common activities in the course of focus. For example, a early project like CGOL would have very similar map generation functions, random seeding functions, and it's reproduction functions are similar to the random walk functions for some of the movement of cells. Conditional structures for decision making would share a lot of common structure with smaller projects previously tackled in the year.  

Because it is a relatively complex project for any CS I course, it can also be scaled back to meet any time demands for the particulars of the course. For example, with a 3 period time chunk Groton teachers may wish to present the unit/project as something close to a tabla rosa, with some structured code comments, some break down sessions and a 2-week time table with check ins and then support as needed. Conversely, Dryden teachers, with a single period class, may want to provide a richer code scaffold, and focus on a few key programming topics, such as object design, inheritance, and polymorphism. 

---

### Standards Referenced

|Subcategory|Standard Code|Standard|
|---|---|---|
|Abstraction and Decomposition|9-12.CT.4 |Implement a program using a combination of student-defined and third-party functions to organize the computation.|
|Abstraction and Decomposition|9-12.CT.5 |Modify a function or procedure in a program to perform its computation in a different way over the same inputs, while preserving the result of the overall program.|
|Algorithms and Programming|9-12.CT.7 |Design or remix a program that utilizes a data structure to maintain changes to related pieces of data.|
|Algorithms and Programming|9-12.CT.8 |Develop a program that effectively uses control structures in order to create a computer program for practical intent, personal expression, or to address a societal issue.|
|Algorithms and Programming|9-12.CT.9 |Systematically test and refine programs using a range of test cases, based on anticipating common errors and user behavior.|
|Algorithms and Programming|9-12.CT.10| Collaboratively design and develop a program or computation artifact for a specific audience and create documentation outlining implementation features to inform collaborators and users.|
---

### Tools Used 

Python will be used as the main programming language for the entire duration of the course.  Students will be exposed to different IDEs to use while programming. This may include Python IDLE, to independent third party IDEs such as Jupyter, Sublime Text 3, Eclipse and/or others. Students may also be expected to write out their code by hand using pseudocode first.  Writing out the pseudocode will help students work out the code step by step and eliminate any problems that may arise if coding was to be started first.  Students may also receive paper hadnouts where they can work out solutions on paper.

---

### Resources

[Unit Plan Extension](/resources/Unit_Plan_Supliment.pdf) document for this unit plan (additional standards, planning for student issues, calendar, et. al.).

Sites that students may find useful for reference materal <br>
[W3Schools' Python Resources](https://www.w3schools.com/python/default.asp) <br>
[GeeksforGeeks Python](https://www.geeksforgeeks.org/python-programming-language/?ref=shm) <br>
[StackOverflow](https://stackoverflow.com/)

---

### Lessons
Total length: 2 Weeks

|Lesson|Topics|
|------|------|
|[Lesson 1: Project Launch](/lessons/01_launch/Lesson_01.pdf)|<ul><li>Develop understanding of game rules</li><li>Form groups and plan group self-administration strategy</li></ul>|
|[Lesson 2: Build Arrays](/lessons/02_arrays/Lesson_02.pdf)|<ul><li>Finalize group administration approach</li><li>Develop functions to build the 2D/3D array</li><li>Create "empty" cell structure</li><ul>|
|[Lesson 3: Prey Start](/lessons/03_prey1/Lesson_03.pdf)|<ul><li>Develop prey movement logic.</li></ul>|
|[Lesson 4: Prey Continued](/lessons/04_prey2/Lesson_04.pdf)|<ul><li>Expand prey movement logic</li><li>Add prey breeding logic</li></ul>|
|[Lesson 5: Prey Finish](/lessons/05_prey3/Lesson_05.pdf)|<ul><li>Wrap up prey functions</li><li>Test prey functionality</li></ul>|
|[Lesson 6: Test Prey, Start Loop](/lessons/06_loop/Lesson_06.pdf)|<ul><li>Wrap up single cell logic</li><li>Work on game loop</li></ul>|
|[Lesson 7: Predator Start](/lessons/07_pred1/Lesson_07.pdf)|<ul><li>Finish functions for game loop</li><li>Start to implement predator movement logic</li></ul>|
|[Lesson 8: Predator Continued](/lessons/08_pred2/Lesson_08.pdf)|<ul><li>Expand predator movement logic</li><li>Add predator breeding logic</li></ul>|
|[Lesson 9: Polish](/lessons/09_polish/Lesson_09.pdf)|<ul><li>Finish predator logic</li><li>Clean up user presentation to develop the finished product</li><ul>|
|[Lesson 10: End](/lessons/10_end/Lesson_10.pdf)|<ul><li>Add finishing touches</li><li>Complete group self-evaluation</li></ul>|

---

### Assessments

Students will self-monitor progress using a checklist for each day. Since the unit is a synthesis of prior learning instead of new learning, there should not be a need to assess content understanding so much as group progress. The end result of the project will be assessed by a rubric.
