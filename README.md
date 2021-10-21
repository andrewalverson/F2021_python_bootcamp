## Fall 2021 DASC Python/R Bootcamp

### Day 1: Python (see `learning_python.ipynb`)

We'll use [Google Colab](https://colab.research.google.com/) to run Python code inside of Jupyter notebooks

You'll need to clone [this GitHub repository](https://github.com/andrewalverson/F2021_python_bootcamp). It will help to copy and paste this web address:

	https://github.com/andrewalverson/F2021_python_bootcamp

One of the files is in GFF3 format. You can learn more about that [here](http://useast.ensembl.org/info/website/upload/gff3.html).

#### We'll cover the following basic concepts and operations in Python:
	
- variables

- integers, floats, and strings

- basic math, adding numbers and strings

- how to build, use, slice, and index lists


<figure align = "center">

![](img/list_indexing.jpg)

</figure>


- how to open, read, and parse a file
	
	- with open() as:

	- for loops

	- next()

- conditionals (if, elif, else)

- how to format and print output
	
	- f'' vs. print()
	
	- '+' vs. ','

- how to use Google to find help

---

### Day 2: R (see `F2021_bootcamp.Rmd and F2021_bootcamp.html`)

The content in this bootcamp is based on Datacamp's "Introduction to the tidyverse" course.

#### Basic concepts and functions in R and the [tidyverse](https://www.tidyverse.org/)

[Tidy data](https://r4ds.had.co.nz/tidy-data.html):

1. Each variable has its own column

2. Each observation has its own row

3. Each value has its own cell


[data frame](http://www.r-tutor.com/r-introduction/data-frame): 2-dimensional table; the fundamental data structure in R

- **columns** are variables that can differ in type (numeric, factor, character, etc.)
	
- **rows** are observations of the different variable types described by the column name/header
	
- each piece of data is called a **cell**

[<-](https://stat.ethz.ch/R-manual/R-devel/library/base/html/assignOps.html) **assignment operator**, saves the data or results on the right side of '<-' to the variable name on the left; similar to how you use '=' in other contexts

[%>%](https://style.tidyverse.org/pipes.html): **pipe**, channel the output of what's before the pipe to the command after the pipe

[filter()](https://dplyr.tidyverse.org/reference/filter.html): use to extract a subset of observations (rows)

[arrange()](https://dplyr.tidyverse.org/reference/arrange.html): sorts a table based on a variable (e.g., sort data for players on a basketball team by player height)

[aes()](https://beanumber.github.io/sds192/lab-ggplot2.html#Aesthetic_Mapping_(aes)): **aesthetic**, something you can see, a mapping between a visual cue and a variable

[summarize()](https://dplyr.tidyverse.org/reference/summarise.html): calculate summary statistics (e.g., mean, median) for one or more variables/columns
