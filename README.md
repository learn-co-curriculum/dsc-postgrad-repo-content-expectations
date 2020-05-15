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

Data science projects at flatiron school include two forms of documentation, the Jupyer Notebook and the Readme. The jupyter notebook is the long-form documentation of the analysis and the readme is a short summary and provides guidance to navigate the repository structure. 

In the Jupyter notebook, you capture the requirements Jeff Leek describes in these sections

- Title
- Business understanding
- Data understanding
- Data preparation
- Modeling
- Evaluation

Each section has a set of requirements and questions it should be able to answer.

### Title
As with the name of you files  and repository, the title of the notebook should also be descriptive. "Flatiron Capstone Project Analysis"  is  not as  informative as [Lindsey put new title here, like "An Analysis of the impact of...  etc]. An even  catchier title  would be [another fill in here].

### Business Understanding

Clearly explains the real-world value the project has for a specific stakeholder.	
Easy to see how the problem impacts the organization
What is the variable, and how will using it, impact the organization. 

### Data Understanding

Relates data source and properties of variables to the real-world problem of interest.	Describes data source and properties of all variables used in data preparation and modeling.
- where does the data come from
- what do the variables mean
- who is in the sample
- what elements of the data will/won't address the problem you are trying to solve
- look for outliers, nas, examine every variable you plan to use
- Are there any issues in term of permission? copy right? ethical issues? confidential
- What additional data would be really helpful and is there any way to get it?
- What is the target varialbe?

### Data Preparation

Data preparation is fully documented, including valid justification for decisions	All data preparation steps are reproducible and justifiable.

- There should be code that can take the raw data and get it ready for analysis, can be run again
- ideally code to get the data (if scraped or API,etc)
- ideally pipelined code, but that's an AAB aspect
In what form is the data stored?
Did you use a pre-made dataset or did you create your own?
What kind of preprocessing steps do you foresee?
How much data are you expecting to collect?


### Modeling

Model development is correct, iterative, and fully documented, including valid justification for decisions	Models are developed iteratively and justifiably, proceeding from a simple baseline model to more complex models.

### Evaluation

Clearly explains how well the project solves the real-world problem of interest.	Cross validation or another validation process is used correctly to evaluate model performance. 
- not just about evaluation metrics, but also about how well your analysis answers the business question itself
What metrics will you use to determine success?
What are the reach goals of the project?
- what potential problems are there with your analysis?
- next steps
- limitations of analysis

[EXERCISE EXAMPLE OF ADDING LIMITATIONS TO NOTEBOOK - LINDSEY]


## List of questions to be answered in each section
[checklist](https://github.com/learn-co-curriculum/dsc-capstone-submission-checklist)

### Other approaches and inspiration

In [Randal Olsen](http://www.randalolson.com/)'s [sample analysis](https://nbviewer.jupyter.org/github/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb) of the iris data, he by  uses the data analysis checklist from [The Elements of Data Analytic Style](https://leanpub.com/datastyle) to ensure his analysis is not mediocre. You don't want a mediocre analysis either. 

[another good example analysis](https://github.com/guillaume-chevalier/LSTM-Human-Activity-Recognition)

[yet another good example](https://nbviewer.jupyter.org/github/brianckeegan/Bechdel/blob/master/Bechdel_test.ipynb)

The analysis and summaries in your projectYou want an outstanding and thorough analysis to attract employers and showcase your data science skills. 




