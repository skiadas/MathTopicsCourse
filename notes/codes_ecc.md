# Identification Numbers and Error Correcting

Read the book chapters first, then make sure you can answer the questions in the notes. Following that, work on some skills-check problems and exercises. Then take the online quizzes.

Reading
  ~ 16.1

Skills Check
  ~ 1, 2, 3, 4, 5, 6, 7, 10, 11, 12, 14, 18, 19, 20, 23

Exercises
  ~ 1, 2, 4, 5, 6, 9, 10, 13, 14, 15, 17, 18, 19, 21, 23, 26, 27, 31, 45, 46

Quiz
  ~ [Take the quiz](https://moodle.hanover.edu/mod/quiz/view.php?id=5106)

## 16.1

- What is the idea behind the notion of a *check digits*?
- Review how to do integer division of two numbers, and obtain a *quotient* and a *remainder*.
- Way to perform an integer division in your calculator:
    - Say we want to divide 56 by 11.
    - First ask it to do the division $56/11$. You get something like $5.090909$.
    - Keep the integer part: 5. That is your *quotient*.
    - Multiply by the divisor and subtract from the divident: $56 - 5\times 11 = 1$. This is your *remainder*.
    - The four numbers now satisfy the relation: $56 = 5\times 11 + 1$.
    - Can we recover a digit, if it somehow got corrupted and we didn't know its value?
- In all of the following schemes here are questions you should be asking:
    - How is the last digit (check digit) determined? Work out some examples.
    - Would this scheme detect any changes in the numbers (e.g. a 2 instead of a 3, a 0 instead of a 9 etc)?
    - Would this scheme detect any transpositions (i.e. if two numbers switch places)? What if the check digit switches places?
    - Can we recover a digit, if it somehow got corrupted and we didn't know its value?
- The *American Express traveler's cheque* scheme uses 10 digits.
- The *USPS money order* scheme is based on 11 digits.
- *Airline tickets* follow a "divide by 7" scheme, with a total of 7 digits.
- *Universal Product Code*, or UPC, is a 12 digit scheme.
    - What do the different digits represent?
- *Bank Identification Numbers* use a 9 digit scheme.
    - What is the advantage of using 3 weights?
- The *codabar* scheme is a 16 digit scheme used by all credit card companies. Make sure you understand how it works.
    - Verify it on your credit card, if you have one.
- *ISBN* numbers come in a 10 digit scheme and a 13 digit scheme. These questions pertain to the 10 digit scheme.
    - Verify the schemes in various books you have.
    - How can we be sure these schemes detect 100% of single digit errors?
    - How can we be sure these schemes detect 100% of transposition errors?
    - Why do we some times see an X instead of a digit in ISBN codes?
- How does the *ISBN* 13 digit scheme work?
