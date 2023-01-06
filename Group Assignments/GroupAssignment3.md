# Group Assignment #3: A "functional" notebook

There are two components to this group assignment.

## A "clean" notebook

The midterm was an exploration of the many datasets and methods for your final project. It documented experimentations, failures, and successes along the way. It also exposed the challenges of working on a team, with potentially multiple notebooks to deliver different outputs. For this group assignment, take the time to eliminate the unnecessary content, and boil it down to the bare minimum necessary components that will dictate your final project. Your clean notebook should only include data that will be used in your project, followed by charts and maps that inform your research inquiry. Each data wrangling step and data visualization should be followed by a markdown cell that succinctly explains what you are visualizing and why it is interesting. What story does it tell? How do the visuals enrich, confirm, or contradict the descriptive statistics you calculated earlier? Begin to explain the "why" and not just the "how" of your narrative: Why does this data address your research question? You are welcome to submit multiple notebooks, as long as they are sequenced in a clear and logical manner. Feel free to add any additional material that advances your project.

## Add a function and a loop

In addition to the task of cleaning up the notebook(s), include one or more functions in your data workflow. Functions can dramatically cut down the amount of code needed in your project. For example, consider a situation where you may want to produce multiple maps that display crime for different neighborhoods. You could create multiple cells with the code to create these maps... or, you can create a function that takes in an argument for `neighborhood` that then generates the map. You can then create a loop that produces a desired map for a list of geographic entities. For example:

```python
# function
def crime_by_neighborhood(place):
    # code to create the crime map

# list of neighborhoods
neighborhoods = ['Downtown','Korea Town','Boyle Heights', ...]

# call the function with a loop
for neighborhood in neighborhoods:
    crime_by_neighborhood(place=neighborhood)

````

At the end of the notebook, include a markdown cell that identifies each group member and describes their contribution to this assignment (one sentence each).

Make sure your notebook runs from the top without any errors and that all the visuals can be seen inline (without me having to re-run your notebook). 

## If you have already done a function and a loop...

For those of you who are ahead of the game, congratulations! But let's not get our foot off the pedal. You are welcome to:

- Submit a notebook that does spatial autocorrelation: Find tendencies for spatial clustering in your data by conducting a spatial autocorrelation analysis. Your results must include a global Moran's I statistic, followed by a local spatial autocorrelation with a moran's plot that indicates a P-value and a scatterplot with HH, HL, LH, and LL values. Produce a final output in the form of a map that indicates the location of statistically significant spatial clusters.
- Suggest a different notebook: this may be a cleaned up or new version of your function/loop, or an experimentation on something we have not covered in class. Convince me, I am open as long as it advances your project in a meaningful way.

## Submit

Submit a link to your jupyter notebook [here](https://github.com/yohman/21F-UP206A/discussions/14)

