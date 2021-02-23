---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Python Versus R for Machine Learning and Data Science"
subtitle: ""
summary: ""
authors: 
- admin
tags: 
- Python
- R
- Data Science
- Machine Learning
categories: []

date: 2021-02-23T15:22:31+01:00
lastmod: 2021-02-23T15:22:31+01:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  placement: 2
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

**Most people I meet in my daily activities who are interested in both Machine Learning and Data Science, have been asking about the best programming language for data science. Immediately, R and Python both come to mind… but which of these two giants to choose?**

{{% toc %}}

I have searched through the internet and have put together some resources and links to page and blogs which will help us all to decide on which language to settle on. I will start with a summary of the resources from leading machine learning and data science blogs and websites such as _Udacity_, _datacamp_, _reddit_, _elite data science_, _open source_, _kdnuggets_, _quora_ and _data science.stack exchange_.

## Other Resources
[Data Camp](https://www.datacamp.com/community/tutorials/r-or-python-for-data-analysis#gs.GmNbz00)

**Verdict**: Karlijn Willems in her infograhic comparison concluded that: 
> It's a tie! It's up to the you, the data scientist, to pick the language that best fits your needs.

[Udacity](https://blog.udacity.com/2015/01/python-vs-r-learn-first.html)

**Verdict**: Cheng Han Lee in his analysis also concluded that, "In general, you can’t err whether you choose to learn Python first or R first for data analysis. Each language has its pros and cons for different scenarios and tasks. In addition, there are actually libraries to use Python with R, and vice versa—so learning one won’t preclude you from being able to learn and use the other. Perhaps the best solution is to use the these guidelines:
- _Personal preference_:  
Choose the language to begin with based on your personal preference, on which comes more naturally to you, which is easier to grasp from the get-go. To give you a sense of what to expect, mathematicians and statisticians tend to prefer R, whereas computer scientists and software engineers tend to favor Python. The best news is that once you learn to program well in one language, it’s pretty easy to pick up others.

- _Project selection_: 
You can also make the Python vs. R call based on a project you know you’ll be working on in your data studies. If you’re working with data that’s been gathered and cleaned for you, and your main focus is the analysis of that data, go with R. If you have to work with dirty or jumbled data, or to scrape data from websites, files, or other data sources, you should start learning, or advancing your studies in, Python.

- _Collaboration_:
Once you have the basics of data analysis under your belt, another criterion for evaluating which language to further your skills in is what language your teammates are using. If you’re all literally speaking the same language, it’ll make collaboration—as well as learning from each other—much easier.

- _Job market_:
Jobs calling for skill in Python compared to R have increased similarly over the last few years.

[Elite Data Science](https://elitedatascience.com/r-vs-python-for-data-science)

**Verdict**: They concluded that,  
> both languages are actively being developed and have an impressive suite of tools already. It sounds cliché to say this, but there's really no one-size-fits-all answer.

[Open Source](https://opensource.com/article/16/11/python-vs-r-machine-learning-data-analysis)

**Verdict**: Tom Radcliffe made the following comments 
> The main issue with R is its consistency. Algorithms are provided by third parties, which makes them comparatively inconsistent. The resulting decrease in development speed comes from having to learn new ways to model data and make predictions with each new algorithm you use. Every package requires a new understanding. Inconsistency is true of the documentation as well, as R's documentation is almost always incomplete.

[KDnuggets](https://www.kdnuggets.com/2015/05/r-vs-python-data-science.html)

**Verdict**: KDnuggets using their figures and diagrams made the following observations:

> On the web, you can find many numbers comparing the adoption and popularity of R and Python. While these figures often give a good indication of how these two languages are evolving in the overall ecosystem of computer science, it’s hard to compare them side-by-side. The main reason for this is that you will find R only in a data science environment; As a general-purpose language, Python, on the other hand, is widely used in many fields, such as web development. This often biases the ranking results in favor of Python, while the salaries are affected somewhat negatively.
If you look at recent polls that focus on programming languages used for data analysis, R often is a clear winner. If you focus specifically on Python and R's data analysis community, a similar pattern appears.
Despite the above figures, there are signals that more people are switching from R to Python. Furthermore, there is a growing group of individuals using a combination of both languages when appropriate. This is exactly in line with what we recommend to our students as well.

- [Reddit](https://www.reddit.com/r/MachineLearning/comments/1rg8o4/r_vs_python/)
- [Quora](https://www.quora.com/Should-I-learn-Python-or-R-for-machine-learning-if-I%E2%80%99m-pursuing-my-Bachelor%E2%80%99s-in-math-and-computing-engineering-Which-language-is-used-most-in-industries#_=_)
- [Stake Exchange](https://datascience.stackexchange.com/questions/326/python-vs-r-for-machine-learning)

## Personal Opinion
- **My Analysis**:
There are some things one will have to take into consideration before deciding on whether to choose R or Python. Think of the question as a problem statement. Your current inclinations and understanding of what you want in the future will help you reach an answer. 
It depends on the industry and even country and continent. My overall feeling is that Python is stronger in the US and R is stronger in Europe but I have no data to support this. Some companies use one of the other exclusively, whereas others use whatever gets each job done. 
 
### Case for Python: 
Python is a general-purpose programming language that can pretty much do anything you need it to: data munging, data engineering, data wrangling, website scraping, web app building, and more. It’s simpler to master than R if you have previously learned an object-oriented programming language like Java or C++. In addition, because Python is an object-oriented programming language, it’s easier to write large-scale, maintainable, and robust code with it than with R. Using Python, the prototype code that you write on your own computer can be used as production code if needed.
Although Python doesn’t have as comprehensive a set of packages and libraries available to data professionals as R, the combination of Python with tools like Pandas, Numpy, Scipy, Scikit-Learn, and Seaborn will get you pretty darn close. The language is also slowly becoming more useful for tasks like machine learning, and basic to intermediate statistical work (formerly just R’s domain)[1].


- **Why Python is Great for Data Science ?**
  - Python was released in 1989. It has been around for a long time, and it has object-oriented programming baked in.
  - IPython / Jupyter's notebook IDE is excellent.
  - There's a large ecosystem. For example, Scikit-Learn's page receives 150,000 - 160,000 unique visitors per month.
  - There's Anaconda from Continuum Analytics, making package management very easy.
  - The Pandas library makes it simple to work with data frames and time-series data.
- **When and how to use Python?**
  - You can use Python when your data analysis tasks need to be integrated with web apps or if statistics code needs to be incorporated into a production database. Being a fully-fledged programming language, it’s a great tool to implement algorithms for production use.
  - While the infancy of Python packages for data analysis was an issue in the past, this has improved significantly over the years. Make sure to install [NumPy](http://www.numpy.org/) /[SciPy](https://www.scipy.org/) (scientific computing) and [pandas](http://pandas.pydata.org/) (data manipulation) to make Python usable for data analysis.  Also, have a look at [matplotlib](https://matplotlib.org/stable/index.html) to make graphics and [scikit-learn](https://scikit-learn.org/stable/) for machine learning.
  - Unlike R, Python has no clear “winning” IDE. We recommend you to have a look at [Spyder](https://www.spyder-ide.org/), [IPython Notebook](https://ipython.org/notebook.html), and [Rodeo](https://github.com/yhat/rodeo/) to see which one best fits your needs.

### Case for R:

Key quote: 
> "There should be an interface to the very best numerical algorithms available." - John Chambers

R has a long and trusted history and a robust supporting community in the data industry. Together, those facts mean that you can rely on online support from others in the field if you need assistance or have questions about using the language. Plus, there are plenty of publicly released packages, more than 5,000 in fact, that you can download to use in tandem with R to extend its capabilities to new heights. That makes R great for conducting complex exploratory data analysis. R also integrates well with other computer languages like C++, Java, and C.
When you need to do heavy statistical analysis or graphing, R’s your go-to. Common mathematical operations like matrix multiplication work straight out of the box, and the language’s array-oriented syntax makes it easier to translate from math to code, especially for someone with no or minimal programming background [2].


- **Why R is Great for Data Science ?**
  - R was created in 1992, after Python, and was therefore able to learn from Python's lessons.
  - Rcpp makes it very easy to extend R with C++. RStudio is a mature and excellent IDE.
  - CRAN is a candyland filled with machine learning algorithms and statistical tools.
  - The Caret package makes it easy to use different algorithms from 1 single interface, much like what Scikit-Learn has done for Python.

- **When and how to use R?**
  - R is mainly used when the data analysis task requires standalone computing or analysis on individual servers. It’s great for exploratory work, and it's handy for almost any type of data analysis because of the huge number of packages and readily usable tests that often provide you with the necessary tools to get up and running quickly. R can even be part of a big data solution.
  - When getting started with R, a good first step is to install the amazing [RStudio IDE](http://www.rstudio.com/products/rstudio/).  Once this is done, we recommend you to have a look at the following popular packages:
    - [dplyr](https://www.rdocumentation.org/packages/dplyr/versions/0.7.8), [plyr](https://www.rdocumentation.org/packages/plyr/versions/1.8.6) and [data.table](https://www.rdocumentation.org/packages/data.table/versions/1.14.0) to easily manipulate packages,
    - [stringr](https://www.rdocumentation.org/packages/stringr/versions/1.4.0) to manipulate strings,
    - [zoo](https://www.rdocumentation.org/packages/zoo/versions/1.8-8) to work with regular and irregular time series,
    - [ggvis](https://www.rdocumentation.org/packages/ggvis/versions/0.4.7), [lattice](https://www.rdocumentation.org/packages/lattice/versions/0.20-41), and [pggplot2](https://www.rdocumentation.org/packages/ggplot2/versions/3.3.3) to visualize data, and
    - [caret](https://www.rdocumentation.org/packages/caret/versions/6.0-86) for machine learning



## [RECOMMENDATION](https://datascience.stackexchange.com/a/339): 
- **Machine Learning** has 2 phases. Model Building and Prediction phase. Typically, model building is performed as a batch process and predictions are done in realtime. The model building process is a compute-intensive process while the prediction happens in a jiffy. Therefore, the performance of an algorithm in Python or R doesn't really affect the turn-around time of the user. <span style="color:red">**Python - 1**</span>, <span style="color:green">**R -  1**</span>.
- **Production**: The real difference between Python and R comes in being production-ready. Python, as such is a full-fledged programming language and many organizations use it in their production systems. R is a statistical programming software favored by many academia and due to the rise in data science and availability of libraries and being open-source, the industry has started using R. Many of these organizations have their production systems either in Java, C++, C#, Python etc. So, ideally, they would like to have the prediction system in the same language to reduce the latency and maintenance issues. <span style="color:red">**Python - 2**</span>, <span style="color:green">**R -  1**</span>.
- **Libraries**: Both languages have enormous and reliable libraries. R has over 5000 libraries catering to many domains while Python has some incredible packages like Pandas, NumPy, SciPy, Scikit Learn, Matplotlib. <span style="color:red">**Python - 3**</span>, <span style="color:green">**R -  2**</span>.
- **Development**: Both the language are interpreted languages. Many say that python is easy to learn, it's almost like reading English (to put it on a lighter note) but R requires more initial studying effort. Also, both of them have good IDEs (Spyder, etc for Python and RStudio for R). <span style="color:red">**Python - 4**</span>, <span style="color:green">**R -  2**</span>.
- **Speed**: R software initially had problems with large computations (say, like nxn matrix multiplications). But, this issue is addressed with the introduction of R by Revolution Analytics. They have re-written computation-intensive operations in C which is blazingly fast. Python being a high-level language is relatively slow. <span style="color:red">**Python - 4**</span>, <span style="color:green">**R -  3**</span>.
- **Visualizations**: In data science, we frequently tend to plot data to showcase patterns to users. Therefore, visualizations become important criteria in choosing software and R completely kills Python in this regard. Thanks to Hadley Wickham for an incredible ggplot2 package. R wins hands down. <span style="color:red">**Python - 4**</span>, <span style="color:green">**R -  4**</span>.
- **Dealing with Big Data**: One of the constraints of R is it stores the data in system memory (RAM). So, RAM capacity becomes a constraint when you are handling Big Data. Python does well, but I would say, as both R and Python have HDFS connectors, leveraging Hadoop infrastructure would give substantial performance improvement. So, <span style="color:red">**Python - 5**</span>, <span style="color:green">**R -  5**</span>. 


So, both the languages are equally good. Therefore, depending upon your domain and the place you work, you have to smartly choose the right language. The technology world usually prefers using a single language. Business users (marketing analytics, retail analytics) usually go with statistical programming languages like R, since they frequently do quick prototyping and build visualizations (which is faster done in R than Python). 



[1]: https://blog.udacity.com/2015/01/python-vs-r-learn-first.html "python vs R"
[2]: http://blog.udacity.com/2015/01/python-vs-r-learn-first.html/ "Python vs R"