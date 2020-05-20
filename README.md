# Tables of content

In the previous sections you examined how files were organized in a repository, now you will shift to what is inside the files themselves. The focus of this section is not on the statistical validity of your analysis, but on the content **organization** and **presentation**. 

## Learning Goals

In this lesson you will:
- Review the minimum expectations of written data science project
- List what enhances a project from the minimum to the exceptional
- Compare the impact of rewritten sections to their original content

## Data Science Project Components

In [The Elements of Data Analytic Style](https://leanpub.com/datastyle), by [Jeff Leek](http://jtleek.com/), he writes: 

> A written analysis should always include: 
> -  A title
> -  An introduction or motivation
> -  A description of the statistics or machine learning models you used
> -  Results including measures of uncertainty
> -  Conclusions including potential problems
> -  References

Data science projects at Flatiron School include two forms of documentation: the **Jupyter Notebook** and the **README**. The Jupyter Notebook contains the long-form documentation of the analysis, while the README contains a short summary and provides guidance to navigate the repository structure. 

## Jupyter Notebook Content
In the Jupyter notebook, you capture the requirements Jeff Leek describes in these sections:

- **Title**
- **Business understanding**
- **Data understanding**
- **Data preparation**
- **Modeling**
- **Evaluation**

Each section has a set of requirements and questions it should be able to address.

### Title

As with the name of you files and repository, the title of the notebook should also be descriptive. "Project Notebook" is not as informative as "EDA, Modeling, and Evaluation". An even more descriptive title might be "House Price Prediction: Data Exploration, Modeling and Results". There should be no question in a viewer's mind as to what is contained in your notebook.

### Business Understanding

This section clearly explains the real-world value the project has for a specific stakeholder, and how a problem will be addressed by this analysis.

**Example questions to be answered:** 

- How much time will this solution save?
- Who will this solution help?
- What need does this analysis address?
- How well does the metric or target variable directly relate to the real world problem?

### Data Understanding

This section relates your data source and the properties of variables to the real-world problem of interest. Jumping straight into the modeling without demonstrating a thorough understanding of the data is amateur hour. A robust data understanding section will describe the source and properties of all the variables used in the data preparation and modeling sections.

**Example questions to be answered:** 

- Where does the data come from?
- What do the variables mean in actual language?
- What is the target variable?
- What is the range, scale, or distribution of each variable?
- Who is in the sample or how was the data colllected?
- What elements of the data will or will not address the business question?
- Are there any issues related to data permissions, copyright, ethical issues, confidential information, etc.?
- Are there any interesting aspects or anomolies in the data such as outliers or missing data?
- What additional data would be really helpful to your analysis? 

### Data Preparation

An employer should be replicate your data cleaning and preparation, from the raw data to what is used in the analysis, using your data preparation code. A quality data preparation section fully documents and justifies decisions to merge, drop, or transform  variables. 

**Example questions to be answered:**

- Can someone else replicate your entire data preparation process?
- If you created the data through scraping or an API, can someone repeat that process?
- In what form is the data stored?
- Can someone else easily run the code to take the raw data and get it ready for analysis?
- Is the code in pipeline form?
- Is all the preprocessing code in the notebook, or is it in separate `py` files?

### Modeling

While model development is an interative process, not every analysis explored should be in your final project notebook.
correct, iterative, and fully documented, including valid justification for decisions. Models are developed iteratively and justifiably, proceeding from a simple baseline model to more complex models.

**Example questions to be answered:**

- Is the information you are including absolutley relevant?
- Is your final model specified in an equation or pseudocode, and not just specified in code?
- When you describe the parameter or coefficients, do you describe them in real terms?
- Have you examined any problems with the data that might be impacting the quality of your analysis or model?

### Evaluation

Evaluation is not just about accuracy or r-squared score. While those metrics are important, the evaluation section also needs to address how well (or not) the model solves the original business problem. The limitations are just as important as the successes. 

**Example questions about _the model_:** 

- What evaluation metrics did you use?
- Were there special considerations you made when choosing that evaluation metric?
- How does your model's metric compare to industry standards or what is already out there?
- Was cross validation included in your process and what concerns did that address?

**Example questions about _the application_:** 

- What are the limitations of interpreting your analysis?
- What next steps would you take in this analysis? What new data would you want to incorporate?
- How well does your analysis answer the actual business question?
- What sort of impact would your results actually have?

## README Content

The README is at once an abstract, a road map, and a how-to manual. While perhaps not labeled explicity, a quality README includeds: 

### Content summary

- Detailed description of your business question
- A summary of your data science process, findings, and ideas for future improvment
- At least one interesting visualization from your analysis

### Road map

- Repository navigation
- Links to the presentation slides, notebook, and other relevant documentation
- Links to sources, such as the data, papers referenced, or other important materials

### How-to manual

- Reproduction instructions
- Contact information

***

## Exercises

### Notebook

Examine the following selection from the Jupyter Notebook and identify what is missing...
[ LINDSEY - do this a few times]

### README

Examine the README [here](https://github.com/learn-co-curriculum/dsc-postgrad_Project-Repository/blob/master/README.md) and identify which of these aspects is missing or incomplete (could be more than one):

- Detailed description of the business question
- Summary of the data science process, findings, and ideas for future improvement
- At least one interesting visualization
- Repository navigation 
- Links to the presentation slides, notebook, and other relevant documentation
- Links to sources, such as the data, papers referenced, or other important material
- Reproduction instructions
- Contact information

## Other Approaches and Inspiration

In [Randal Olsen](http://www.randalolson.com/)'s [sample analysis](https://nbviewer.jupyter.org/github/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb) on the Iris dataset, he uses the data analysis checklist from [The Elements of Data Analytic Style](https://leanpub.com/datastyle) to ensure his analysis is not mediocre. You don't want a mediocre analysis either!

[another good example analysis](https://github.com/guillaume-chevalier/LSTM-Human-Activity-Recognition)

[yet another good example](https://nbviewer.jupyter.org/github/brianckeegan/Bechdel/blob/master/Bechdel_test.ipynb)





