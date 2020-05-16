# Tables of content

In the previous sections you examined how files were organized in a repository, now you will shift to what is inside the files themselves. The focus of this section is not on the statistical validty of your analysis, but on the content **organization** and **presentation**. 

## Learning Goals
In this lesson you will:
- Review the minimum expectations of written data science project
- List what enhances a project from the minimum to the exceptional
- Compare the impact of rewriten sections to their originial content

## Data Science Project Components

In [The Elements of Data Analytic Style](https://leanpub.com/datastyle), by [Jeff Leek](http://jtleek.com/) states: 

> A written analysis should always include: 
> -  A title
> -  An introduction or motivation
> -  A description of the statistics or machine learning models you used
> -  Results including measures of uncertainty
> -  Conclusions including potential problems
> -  References

Data science projects at flatiron school include two forms of documentation, the **Jupyer Notebook** and the **Readme**. The jupyter notebook is the long-form documentation of the analysis and the readme is a short summary and provides guidance to navigate the repository structure. 

## Jupyter Notebook Content
In the Jupyter notebook, you capture the requirements Jeff Leek describes in these sections

- **Title**
- **Business understanding**
- **Data understanding**
- **Data preparation**
- **Modeling**
- **Evaluation**

Each section has a set of requirements and questions it should be able to address.

### Title

As with the name of you files  and repository, the title of the notebook should also be descriptive. "Flatiron Capstone Project Analysis"  is  not as  informative as [Lindsey put new title here, like "An Analysis of the impact of...  etc]. An even  catchier title  would be [another fill in here].

### Business Understanding

This section clearly explains the real-world value the project has for a specific stakeholder and how a problem will be addressed by this analysis.

**Example questions to be answered:** <br>
- How much time will this solution save?
- Who will this solution help?
- What need does this analysis address?
- How well does the metric or target variable directly relate to the real world problem?

### Data Understanding

This section relates data source and properties of variables to the real-world problem of interest. Jumping straight into the modeling without demonstrating a thoruogh understanding of the data is amateur hour. A robust data understanding section will describe the source and properties of all the variables used in the data preperation and modeling sections.

**Example questions to be answered:** <br>
- Where does the data come from?
- What do the variables mean in actual language?
- What is the target varialbe?
- What is the range or scale of each variable?
- Who is in the sample  or how was the data colllected?
- What elements of the data will or will not address the business question?
- Are there any issues in term of data permissions, copy right, ethical issues, or confidential information?
- Are there any interesting aspects or anomolies in the data such as outliers or missing data?
- What additional data would be really helpful in your analysis? 

### Data Preparation

An employer should be replicate your data cleaning and preparation from the raw data to right before analysis using your data preparation code. A quality data preparation fully documents and justifies decisions to merge, drop, or transform  variables. 

**Example questions to be answered:** <br>
- Can someone  else replicate your entire data preparation process?
- If you created the data through scraping or an API, can someone repeat that process?
- In what form is the data stored?
- There should be code that can take the raw data and get it ready for analysis, can be run again
- Is the code in pipeline form?
- Is all the  preprocessing code in the notebook or is it in separate `py` files?

### Modeling

While model development is an interative process, not every analysis explored should be in your final project notebook.
correct, iterative, and fully documented, including valid justification for decisions	Models are developed iteratively and justifiably, proceeding from a simple baseline model to more complex models.

**Example questions to be answered:** <br>
- Is the information you are including absolutley relelvant?
- Is your final model specified in an equation or pseudocode, and not just specified in code?
- When you describe the parameter or ceoficients, do you describe it in real terms?
- Have you examined any problems with the data that might be impacting the quallity of your analysi or model?

### Evaluation

Evaluation is not just about accuracy or r-squared. While those metrics are important, the evaluation section also needs to address how well (or not) the model solves the original business problem. The limitiations are just as important as the successes. 

**Example questions about _the model_:** <br>
- What evaluation metrics did you use?
- Were there special considerations you made when choosing that evaluation metric?
- How does your model's metric compare to industry standards or what is already out there?
- Was cross vallidation included in your process and what concerns did that address?

**Example questions about _the application_:** <br>
- What are the limitations of interpreting your analysis?
- What next steps would you take in this analysis? What new data would you want to incorperate?
- How well does your analysis answer the actual business question and concern?
- What sort of impact would your results actually have?

## README Content

The README is at once an abstract, a road map, and a how-to manual. While not labeled explicity, a quality readme includeds: 
### Content summary
- Detailed description of your business question
- A summary of your data science process, findings, and ideas future improvment
- At least one interesting visuallization from your analysis
### Road map
- Repository navigation
- Links to the presentation slides, notebook, and other relevant documentatin
- Links to sources, such as the data, papers referenced, or other important material
### How-to manual
- Reproduction instructions
- How to contact you information

***

## Exercises

### Notebook

Examine the following selection from the jupyter notebook and identify what is missing...
[ LINDSEY - do this a few times]

### Readme
Examine the Readme [here](link) and identify which of these aspects is missing or incomplete(could be more than one)...

- Detailed description of your business question
- Repository navigation (want this to be missing and point them towards the `tree` package to create it)
- Links to the presentation slides, notebook, and other relevant documentatin
- Links to sources, such as the data, papers referenced, or other important material
- Reproduction instructions (also want this to be missing)
- How to contact you information

## Other approaches and inspiration

In [Randal Olsen](http://www.randalolson.com/)'s [sample analysis](https://nbviewer.jupyter.org/github/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb) of the iris data, he by  uses the data analysis checklist from [The Elements of Data Analytic Style](https://leanpub.com/datastyle) to ensure his analysis is not mediocre. You don't want a mediocre analysis either. 

[another good example analysis](https://github.com/guillaume-chevalier/LSTM-Human-Activity-Recognition)

[yet another good example](https://nbviewer.jupyter.org/github/brianckeegan/Bechdel/blob/master/Bechdel_test.ipynb)





