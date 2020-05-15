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

In the Jupyter notebook, you capture the requirements Jeff Leek describes in these sections

- Title
- Business understanding
- Data understanding
- Data preparation
- Modeling
- Evaluation

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

Data preparation is fully documented, including valid justification for decisions	All data preparation steps are reproducible and justifiable.

**Example questions to be answered:** <br>
- There should be code that can take the raw data and get it ready for analysis, can be run again
- ideally code to get the data (if scraped or API,etc)
- ideally pipelined code, but that's an AAB aspect
In what form is the data stored?
Did you use a pre-made dataset or did you create your own?
What kind of preprocessing steps do you foresee?
How much data are you expecting to collect?


### Modeling

Model development is correct, iterative, and fully documented, including valid justification for decisions	Models are developed iteratively and justifiably, proceeding from a simple baseline model to more complex models.
**Example questions to be answered:** <br>

### Evaluation

Clearly explains how well the project solves the real-world problem of interest.	Cross validation or another validation process is used correctly to evaluate model performance.

**Example questions to be answered:** <br>
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




