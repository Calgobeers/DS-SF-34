# DS-SF-34 | Final Project | 3 | Notebook and Final Presentation

> **Submission:**
>
> - Please push your assignment to your GitHub repository and submit a link to it via [this form](https://docs.google.com/a/paspeur.com/forms/d/e/1FAIpQLSecmVqN6KK4QGtcPz78KxN87KUE03DyXd0mZivZlj7cEaaXWA/viewform).
> - Present materials in class.

---

## PROMPT

> **Objectives:**
>
> - Detailed technical Jupyter notebook with a summary of your statistical analysis, model, and evaluation metrics.
> - Presentation deck that relates your data, model, findings, and recommandations to a non-technical audience.

Our goal for this project is to develop a working technical document that can be shared amongst your peers.  Similar to any other technical project, it should surface your work and approach in a human readable format.  Your project should push the reader to ask for more insightful questions, and avoid issues like, "what does this line of code do?"

From a presentation perspective, think about the machine learning applications of your data.  Use your model to display correlations, feature importance, and unexplained variance.  Document your research with a summary, explaining your modeling approach as well as the strengths and weaknesses of any variables in the process.

You should provide insight into your analysis, using best practices like cross validation or any applicable prediction metrics (e.g., MSE for regression; accuracy/AUC for classification).  Remember, there are many metrics to choose from, so be sure to explain why the one(s) you are using is reasonable for your problem.

Look at how your model performs compared to a baseline model, and articulate the benefit gained by using your specific model to solve this problem.  Finally, build visualizations that explain outliers and the relationships of your predicted parameter and independent variables.  You might also identify areas where new data could help improve the model in the future.

---

### DELIVERABLES

#### Jupyter Notebook

- **Requirements:**
  - Create Jupyter notebook with Markdown, code, and visualizations, fully ran from top to bottom.
  - Frame code so as to enhance your explanations.
  - Explain your choice of validation and prediction metrics.
  - Visualize relationships between your dependent variable and the strongest independent variables.
  - Identify areas where new data could help improve the model.

### Final Presentation

- **Requirements:**
  - Include project table of content, background, problem, and hypothesis.
  - Describe dataset and analysis with summary and charts.
  - Demonstrate your model with visualizations.
  - Review the conclusions from your findings.
  - Create a list of recommendations and next steps based on your work.
  - Frame your materials for a non-technical audience.
  - Include an appendix with full technical details

Some ideas on how to break down your presentation:

- **Outline**
  - What is your project about?
  - What is its history?
  - What relevant information is required for a colleague to jump in to understand your project?
- **Summary**  (including data and problem statement)
  - What were you trying to accomplish?
  - What steps did your project take?
  - Where did the data come from?  What does a sample look like?  Was there data you considered but decided to remove?
- **Modeling Insight**
  - What is the visualization explaining?
  - What do the `x` and `y` axis mean?
  - How does the visualization help either prove or disprove your work?
  - What caveats have to be explained to best understand it?
- **Modeling Approach**
  - What was your model trying to optimize for?  Why was it the right metric for optimization?
  - What algorithm did you try?  How does it work?
- **2-3 Results**
  - What worked?  What didn't?  Why?
- **Conclusion**
  - What had the most impact on your work?
  - What can you confirm?  What can you suggest?  What is still to be determined?
- **Next Steps**
  - What should this project do moving forward?
  - What would be the next two or three things you want to try?  What impact might they have?
  - What might your conclusions enable others to do?

---

## RESOURCES

### Suggestions for Getting Started

- Two common ways to start models:
  - "Kitchen Sink Strategy": throw all the variables in and subtract them out, one by one.
  - "Single Variable Strategy": start with the most important variable and slowly add in while paying attention to performance.
    - It may be worth exploring both to understand your data and problem.  How slow is building and predicting the model with all the variables?  How much improvement is made with each variable added?
- Recall that your variables maybe need transformation in order to be most useful.
- Algorithms have different requirements (say, random forest vs. logistic regression), and one may work better for your data than another.
- Strike a balance between writing, code, and visual aids.  Your notebook should feel like a blogpost with some code in it.  Force yourself to write and visualize more than you think!
- A quick outline (e.g., "what do I need" and "where can I find it") can help you prepare.
- Practice your presentation with a friend or family member!  Outside feedback can help you identify gaps in your material.

### Specific Tips

- Limit the amount of visuals and text on your slides for maximum clarity.
  - E.g., try not to use more than 2 visuals or 3-5 bullets per slide.
- Clean & informative presentations > Fancy Presentations!
- Keep your charts simple, and make sure they are clearly labeled.

---

## EVALUATION

| Score | Criteria |
|:---:|:---|
| Outstanding! (4) | Delivered all the assignment requirements |
| Exceeds expectations (3) | Delivered at least 90% of the assignment requirements |
| Meets expectations (2) | Delivered at least 70% of the assignment requirements |
| Does not meet expectations (1) | Delivered less than 50% of the assignment requirements |