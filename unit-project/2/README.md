# DS-SF-34 | Unit Project | 2 | Exploratory Data Analysis

> **Submission:**
>
> - Please push your assignment to your GitHub repository and submit a link to it via [this form](https://docs.google.com/a/paspeur.com/forms/d/e/1FAIpQLSecmVqN6KK4QGtcPz78KxN87KUE03DyXd0mZivZlj7cEaaXWA/viewform).

---

## PROMPT

> **Objective:**
>
> - A Jupyter notebook writeup that provides a dataset overview with visualizations and statistical analysis.

In this project, you will implement the exploratory data analysis plan developed in Project 1.  This will lay the groundwork for our modeling exercise in Project 3.

Before completing an analysis, it is critical to understand your data.  You will need to identify all the biases of the variables in your model in order to accurately assess the strengths and limitations of your analysis and predictions.

Following these steps will help you better understand your dataset.

---

## DELIVERABLES

### Jupyter Notebook with Data Exploratory Analysis

- **Requirements:**
  - Read in your dataset, determine how many samples are present, and identify any missing data.
  - Create a table of descriptive statistics for each of the variables (count, mean, standard deviation, ...).
  - Describe the distributions of your data.
  - Plot boxplots for each variable.
  - Create a covariance matrix.
  - Determine any issues or limitations based on your exploratory analysis.
  - Outline exploratory analysis methods.

---

## RESOURCES

### Dataset

The dataset is available [here](../dataset).

### Starter code

For this project we will be using an Jupyter notebook.  This notebook will use `matplotlib` for plotting and visualizing our data.  This type of visualization is handy for prototyping and quick data analysis.  We will discuss more advanced data visualizations for disseminating your work.

* Open the [starter code notebook](./notebooks/unit-project-2-starter-code.ipynb) in Anaconda.

### Suggestions for Getting Started

- Read in your dataset.
- Try out a few `pandas` commands for describing your data:
  - `df.describe()`,
  - `df['columnName'].sum()`,
  - `df['columnName'].mean()`,
  - `df['columnName'].count()`,
  - `df.corr()`
- **Read the documentation for `pandas`.**  Most of the time, there is a tutorial that you can follow; learning to read documentation is crucial to your success as a data scientist.

### Past Projects

Look at some sample notebooks for an example of the types of visualizations you can use in your notebook.
- [Example Notebook](https://github.com/justmarkham/DAT8/blob/master/notebooks/05_pandas_visualization.ipynb)

### Additional Links

- [`pandas` documentation](http://pandas.pydata.org/pandas-docs/stable)
- [`sklearn` documentation](http://scikit-learn.org/stable/documentation.html)

---

## EVALUATION

| Score | Criteria |
|:---:|:---|
| Outstanding! (4) | Answered correctly all questions but went further in providing more in-depth insights |
| Exceeds expectations (3) | Answered correctly all questions |
| Meets expectations (2) | Answered correctly at least 50% of the questions |
| Does not meet expectations (1) | Answered correctly less than 50% of the questions |
| No assignment (0) | Did not turn in the assignment |