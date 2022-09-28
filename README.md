# Exercise 2 - Lists and indices (10 points)

The exercise for this week is meant to help you better understand lists in Python, and practice saving changes to your files using Git and GitHub. You will also get to practice the Markdown syntax. 

Exercise 2 consists of 3 problems. For each problem you need to modify the notebook by adding your own solutions. **Remember to save and commit your changes locally, and push your changes to GitHub after each major change**! Regular commits will help you to keep track of your changes (and revert them if needed). Pushing your work to GitHub will ensure that you don't lose any work in case your computer crashes (yes, it can happen!).

**Please don't change the file name**. Do all of your editing in the provided `Exercise-2.ipynb` file. 

- **Exercise 2 is due by the start of the next lesson (9:15 am, 21 September 2022)**.
- **We are [working in pairs](https://geo-python-site.readthedocs.io/en/latest/lessons/L2/why-pairs.html) on this exercise**, and we will only grade the repository of the driver in your pair for this week's exercise.

## Where to find help

- Review the [materials for Lesson 2](https://geo-python-site.readthedocs.io/en/latest/lessons/L2/overview.html)
- Check out [the hints for this week's exercise](https://geo-python-site.readthedocs.io/en/latest/lessons/L2/exercise-2.html#exercise-2-hints) on the course webpage

## Before you start

### Clone the Exercise 2 repository

Make sure you have cloned your own repository (note that repository name contains your GitHub username).
*Check the Lesson 2 materials for instructions on how to use `git clone` to get started.*
After solving the problems, remember to commit your changes and push them to GitHub.
Remember also to answer all written questions in the exercise, in addition to the programming tasks.

## Problems

**Note**: Problems 1-3 are all in one notebook. You can start the exercise by clicking on one of the links below.

 - [Problem 1 - Making changes to code and using Git (3 points)](Exercise-2.ipynb)
 - [Problem 2 - Monthly average temperatures (5 points)](Exercise-2.ipynb)
 - [Problem 3 - Markdown practice (2 points)](Exercise-2.ipynb)

## Exercise 2 grade and feedback: 9.0 / 10.0 points
### Grader
- Justus :sunglasses:
### Problem scores
- Problem 1: 3.0 / 3.0 
- Problem 2: 5.0 / 5.0 
- Problem 3: 1.0 / 2.0 
### Comments
- Always remember to delete the 'raise NotImplementedError()'. We use it to run our tests and if it is not removed the automated graderbot will assume the exercise is not done.
- In problem 1 part 2, instead of appending 3 times a new element to the list, you can also extend() a list with a list:

    ``` 
        station_start_years = [2003, 1989, 2016, 2005, 1844]
        station_start_years.extend([1937, 2012, 1904])
    ```

- You didn't use a Markdown list :pensive:
- A CSC Notebook is not linked to any GitHub username. You clone the gh repository to the notebook. Do you still have issues with it?
- Meow! :cat:
