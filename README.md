# Notebook #1: Python, Pandas, and Movies!

<b>Due</b>: Tuesday, September 13th, 2022 before class

To submit this notebook, please copy and paste the URL from this page (it should look something like: https://github.com/DrakeCS167Spring22/cs167-notebook1-CS167TestStudent.git) to the Blackboard assignment before the due date.

## The Data
For this notebook, we're going to explore a movie dataset!

The data includes the following features:
- **#**: ID for each movie
- **Title**: Title for each movie
- **Year**: Year the movie was released
- **Age**: appropriate age for movie e.g. 7+, 13+, 18+, all
- **IMDb**: International movie database rating (on a scale from 0.0 to 10.0)
- **Rotten Tomatoes**: Rotten Tomatoes rating (on a scale from 0 to 100)
- **Directors**: list of directors
- **Genre**: primary genre for the movie
- **Runtime**: runtime (in minutes)
- **Country**: country the movie was released/produced in
 
The first step is to get the data loaded and ready to go, make sure the data is in your Google Drive and mount your Drive to the notebook. Start by printing out the first several lines of the dataset to get an idea of what the data looks like. 

## What you need to do :exclamation:
<b>Notebook #1 consists of the following exercises</b> [ 1 point each ]:
1. Print out all of the possible values for the Genres. 
  - *Hint: I'm looking for each possible Genre to be ouput once. For example, if I tossed a coin 3 times and got Heads, Tails, Heads, the possible values of the coin flip are Heads and Tails. There is a function for this. It should require one line of code.*
2. Create a subset of data representing movies from the year 2000-2010 (including both 2000 and 2010) with the value "Action" in the Genre column. Save this DataFrame to the variable name `older_action_movies`. Display the first 5 lines of this subset.
3. Using `older_action_movies`, what is the *median* **IMDb** rating?
4. Create a new subset with only movies with `Rotten Tomatoes` values < 20 and `IMDb` values < 3.0 (these should be awful movies!). Include only 4 columns: the `Title`, `Year`, `IMDb`, and `Rotten Tomatoes`. Display all of the rows in this subset.
5. What is the average (mean) IMDb score for each of the different Genres?  (I'm looking at the average of the 'IMDb' column, grouped by Genre--so Action v Adventure v Animation etc.). Look at this list to determine which genre has the highest average.
- In addition to supplying the code to output the averages for each Genre,answer the question of the hightest average in a text cell ...*
6. **Do something cool**. Do something cool. Using the movies dataset, get creative and show me something about the dataset. Use a text cell to explain what you did. 
 - *Need some help gettting started here? Try asking a question about the dataset and see if you can use Python and Pandas to answer the question*

Use a Markup cell to put your name at the top of the file. Submit this assignment through the GitHub Classroom link.

## :white_check_mark: Grading: 
I will update the following rubric with your grade after you have completed the assignment.
### Rubric:
| Exercise #  | Points Awarded (out of 1)  | Notes |
| --------- | ------------------- | --------- |
| 1: genres          |        |    |
| 2: classic_adventure   |        |    | 
| 3: median IMDb        |        |    |
| 4: new subset         |        |    | 
| 5: average per genre|        |    |
| 6: Something cool|        |    |
| <b>Total         |     /6 |     </b>   |
