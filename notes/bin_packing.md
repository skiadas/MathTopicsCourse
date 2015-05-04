# Bin Packing and Vertex Coloring

Read the book chapters first, then make sure you can answer the questions in the notes. Following that, work on some skills-check problems and exercises. Then take the online quizzes.

Reading
  ~ 3.4, 3.5

Skills Check
  ~ 15, 17, 18, 19, 20, 21, 23, 25, 26, 28, 29

Exercises
  ~ 50, 51, 52, 54, 55, 56, 58, 59, 61, 65, 66, 71, 72, 73, 74, 75, 78, 80, 89

Quiz
  ~ [Take the quiz](https://moodle.hanover.edu/mod/quiz/view.php?id=4892)

## 3.4

- Describe the *bin-packing problem*.
- How does the bin-packing problem differ from the problem of scheduling independent tasks that we saw in section 3.3?
- Describe situations from your experience where you might encounter bin-packing problems.
- Do we know efficient algorithms that give us the best solution in a bin-packing problem? Or is this one of those "NP" problems we talked about?
- How can we obtain a natural lower bound for the smallest number of bins we might have to use, regardless of algorithm?
- Can you think of examples of weights where no matter what algorithm you use you end up with bins that are only about half-full?
- There are in total 6 algorithms discussed in this section: "next-fit", "first-fit", "worst-fit" and versions of these where we first order the weights in decreasing order, starting from the highest value. Describe how these algorithms work and demonstrate in specific examples. Discuss advantages and disadvantages of each algorithm.
- Exercise 56 describes one more heuristic algorithm, called "best-fit". Make sure you understand how it works.

## 3.5

- Describe the *vertex-coloring problem*.
- How does the vertex-coloring problem help us with conflict resolution?
- Describe some situations from your experience where you might need to resolve conflicts and might use vertex-coloring for it.
- What do we call the *chromatic number* of a graph?
- How does the valence of a vertex affect the chromatic number?
- What is the chromatic number of a complete graph?
- If we have a tree, then its chromatic number is always 2. Try to think of why, try out some examples of trees to get started.
- When the college schedules our term exams, they have to avoid conflicts between the classes: If a student is taking two classes, we cannot have those classes have their exam at the same time slot. Ideally we wouldn't want them to have it at the same day either, but that would be hard to accomplish.
    - How can we think of this as a vertex-coloring problem? What are the vertices, what are the edges? Roughly how many vertices and edges do we have? What factors did we leave out in order to achieve this simplification?
    - We have only 5 days of classes, and we can fit at most 4 exam time slots each day. What does that mean about the chromatic number that we would like to have in this graph?
    - If you want to try a little practical experiment, collect information from 20-30 of your classmates as to what classes they would take in the fall, and construct the corresponding graph that shows the conflicts these students impose on the exam schedule.
