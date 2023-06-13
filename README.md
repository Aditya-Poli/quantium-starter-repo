# Quantium starter repo
This repo contains everything you need to get started on the program! Good luck!

## Task 1: Set Up Your Local Development Environment
---

**Here is your task**

1. To begin, get your hands on the starter repo - fork and clone it to your machine: https://github.com/vagabond-systems/quantium-starter-repo. If this step is confusing, read the first two chapters of the Git book linked below.
 
2. Open the project in your IDE of choice — feel free to use any Python IDE you’re comfortable with. If you don’t have a favourite Python IDE yet, look at Pycharm Community Edition. It’s a well-designed IDE by Jetbrains packed with features and plugins, powerful enough to work on the most complex projects, and entirely free.
 
3. One of the best ways to manage dependencies in Python is with virtual environments. Each virtual environment contains a Python interpreter and a collection of project dependencies. They are entirely encapsulated in a single folder, and easy to work with once you get the hang of them. For this project, you will set up a Python 3.9 virtual environment. Review the resources linked below for more information.
 
4. Next, add the dash and pandas packages as dependencies to your virtual environment. Instructions for this step can be found in the Resources section below.
 
5. With your virtual environment active, run `pip install "dash[testing]"` (without backticks) to install all the necessary dash testing dependencies.

Congratulations! You’ve completed the bulk of the work for this task and now have access to a fully-featured workbench. All that’s left is to submit your work. Commit your changes and push them to GitHub!

You’re done! Submit a link to your repo on the next step.
Estimated time for task completion: 30-60 minutes depending on your learning style.
<br>

### Task 1 - Resources

* [Download PyCharm](https://www.jetbrains.com/pycharm/download/#section=linux)
* [Python Virtual Environments: A Primer](https://realpython.com/python-virtual-environments-a-primer/)
* [Dash Installation](https://dash.plotly.com/installation)

**Task 1: Status ✅**

---

## Task 2: Data Processing
---
1. Soul Foods has provided you with three CSV files, all of which are in the data folder of the starter repo you cloned in the last task. These CSV files contain transaction data for Soul Foods’s entire morsel line. Each row indicates the quantity of a given type of morsel sold in a given region at a given price on a given day. Take a moment to acquaint yourself with the data contained in each one of these files.
 
2. Next, we’ll go field by field and think about how we can use each one:
    1. The first field, “product”, contains many different types of morsels. Soul Foods is only interested in Pink Morsels, so we can remove any row which contains another type of product.
    2. Next come “quantity” and “price”. Since we’re interested in the total sales for a given day, these can be combined into a single field, “sales,” by multiplying them together.
    3. The date field is useful as is and can remain untouched.
    4. It would be nice to filter by region in the final visualisation, so we’ll also leave the region field untouched.
 
3. Your task is to use the above instructions to convert the three CSV files into a single formatted output file. Your output file should contain three fields:
    1. Sales
    2. Date
    3. Region
 
4. When you are finished, commit and push your changes, then submit a link to your repo on the next step!.


### Task 2 - Resources

* [CSV File Reading and Writing](https://docs.python.org/3/library/csv.html)
* [Reading and Writing CSV Files in Python](https://realpython.com/python-csv/)

**Task 2 : Status ✅**


