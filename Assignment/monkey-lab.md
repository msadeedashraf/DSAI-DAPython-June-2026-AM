# 🐵 Pandas Assignment - Monkey Explorer

## Course

**Introduction to Pandas**

## Objective

In this assignment, you will use **Pandas** to explore a real-world JSON dataset containing information about different monkey species from around the world.

By completing this assignment, you will practice:

* Reading JSON files
* Exploring DataFrames
* Selecting rows and columns
* Filtering data
* Sorting data
* Calculating statistics
* Working with text data
* Creating new columns
* Saving cleaned datasets

---

# Scenario

You have just joined **WildLife Analytics**, a company that studies monkey populations around the world.

Your manager has given you a JSON dataset containing information about various monkey species.

Your task is to answer business questions using **Pandas**.

---

# Part 1 – Loading the Dataset (10 Marks)

## Task 1

Import the Pandas library.

```python
import pandas as pd
```

---

## Task 2

Load the JSON dataset.

```python
df = pd.read_json("monkey.json")
```

---

## Task 3

Display the following:

* First 5 rows
* Last 5 rows
* Shape of the DataFrame
* Column names
* Data types

---

# Part 2 – Understanding the Dataset (15 Marks)

Answer the following questions.

### Question 1

How many monkeys are in the dataset?

---

### Question 2

How many columns are there?

---

### Question 3

List all column names.

---

### Question 4

What is the datatype of the **Population** column?

---

### Question 5

Which columns contain text values?

---

# Part 3 – Selecting Data (20 Marks)

Display the following:

### Question 1

Only the **Name** column.

---

### Question 2

Only the **Name** and **Population** columns.

---

### Question 3

Only the **Name** and **Location** columns.

---

### Question 4

Only the **Details** column.

---

### Question 5

Display the first three rows.

---

### Question 6

Display rows 4 through 8 using `.iloc`.

---

### Question 7

Display the **Name** and **Population** columns for rows 2 through 6.

---

# Part 4 – Filtering Data (20 Marks)

Display the monkeys that satisfy each condition.

### Question 1

Population greater than **10,000**.

---

### Question 2

Population less than **5,000**.

---

### Question 3

Located in **Brazil**.

---

### Question 4

Located in **Seattle**.

---

### Question 5

Population equal to **1**.

---

### Question 6

Population between **5,000** and **15,000**.

---

### Question 7

Location contains the word **America**.

---

# Part 5 – Sorting Data (10 Marks)

Sort the dataset by:

1. Highest population
2. Lowest population
3. Monkey name (A-Z)
4. Monkey name (Z-A)
5. Location (A-Z)

---

# Part 6 – Summary Statistics (20 Marks)

Calculate the following:

* Highest population
* Lowest population
* Average population
* Total population
* Median population
* Standard deviation of population

---

# Part 7 – Working with Text (15 Marks)

Answer the following.

### Question 1

Display all monkeys whose **Name** contains the word **Monkey**.

---

### Question 2

Display all monkeys whose **Location** contains the word **America**.

---

### Question 3

Create a new column called **Description Length** containing the number of characters in the **Details** column.

---

### Question 4

Which monkey has the longest description?

---

### Question 5

Which monkey has the shortest name?

---

# Part 8 – Creating New Columns (20 Marks)

## Task 1

Create a column named **Population Category**.

Use the following rules:

| Population          | Category |
| ------------------- | -------- |
| Greater than 15,000 | High     |
| 5,000 – 15,000      | Medium   |
| Less than 5,000     | Low      |

---

## Task 2

Create another column called **Hemisphere**.

Use the latitude values.

| Latitude | Hemisphere |
| -------- | ---------- |
| Positive | Northern   |
| Negative | Southern   |

---

# Part 9 – Geographic Analysis (15 Marks)

Answer the following.

### Question 1

Which monkey lives the furthest north?

---

### Question 2

Which monkey lives the furthest south?

---

### Question 3

Which monkey lives the furthest east?

---

### Question 4

Which monkey lives the furthest west?

---

### Question 5

Display the latitude and longitude of every monkey.

---

# Part 10 – Data Cleaning (15 Marks)

Complete the following tasks.

1. Rename **Details** to **Description**.
2. Remove the **Image** column.
3. Move **Population** to be the second column.
4. Display the updated DataFrame.

---

# Part 11 – Exporting Data (10 Marks)

Save the cleaned DataFrame as:

```
monkeys_clean.csv
```

Then create another file containing only:

* Name
* Location
* Population

Save it as:

```
monkeys_summary.csv
```

---

# ⭐ Bonus Challenge (20 Marks)

Your manager wants a report of the most populated monkey species.

Create a new DataFrame that:

* Includes only monkeys with a population greater than **10,000**
* Displays only:

  * Name
  * Location
  * Population
  * Population Category
* Sorts by **Population** (highest to lowest)

Save the report as:

```
popular_monkeys.csv
```

---

# ⭐⭐ Extra Challenge

Using everything you've learned, answer the following without manually inspecting the dataset.

1. Which monkey has the highest population?
2. Which location appears the most?
3. How many monkeys live in North or South America?
4. Which monkey has the longest description?
5. Which monkey has the shortest name?
6. Display monkeys whose population is greater than the average population.
7. Create a **Population Rank** column.
8. Display the Top 5 most populated monkey species.
9. Display the Bottom 5 least populated monkey species.
10. Save your final cleaned dataset.

---

# Deliverables

Submit the following:

* ✅ Jupyter Notebook (`.ipynb`)
* ✅ `monkeys_clean.csv`
* ✅ `monkeys_summary.csv`
* ✅ `popular_monkeys.csv`

---

# Learning Outcomes

By completing this assignment, you will be able to:

* Read JSON data using Pandas
* Explore a DataFrame
* Select rows and columns
* Filter data using conditions
* Sort datasets
* Calculate descriptive statistics
* Work with string data
* Create new calculated columns
* Clean and transform datasets
* Export data for reporting

Good luck, and think like a **Data Analyst** rather than just writing Pandas code!
