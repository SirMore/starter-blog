---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "How To Learn Optimization"
subtitle: ""
summary: ""
authors: 
- admin
tags: 
- operations research
- optimization
- skills
categories: []
date: 2021-02-25T22:08:10+01:00
lastmod: 2021-02-25T22:08:10+01:00
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

**I have been searching on google for an answer to the above question and I came across this question [here](https://or.stackexchange.com/questions/5650/how-to-learn-optimization?newreg=edc254feb853439abf592aea13b8e93f) on [Stack Exchange Operations Research](https://or.stackexchange.com/)**

{{% toc %}}
## Question:
This was the question asked by [OP](https://or.stackexchange.com/users/4563/user56202):
> I am a 2nd year PhD student in a (mostly) pure Mathematics department. I do not have any prior experience in applied mathematics, but I've recently had a change of heart and decided to study Optimization, with the purpose of going into industry after I graduate. I have started reading a couple optimization books (_[Nonlinear Programming](https://www.amazon.com/Nonlinear-Programming-Dimitri-P-Bertsekas/dp/1886529000)_ by Bersekas and _[Numerical Optimization](https://www.csie.ntu.edu.tw/~r97002/temp/num_optimization.pdf)_ by Nocedal and Wright).

> I have a few basic questions about the field:
- Are there dedicated "optimizers" who do nothing but Optimization? 
- What is the job market like?
- Do most optimizers work for a company, or do they work as freelancers?
- From what I understand, an optimizer must have 3 skills
  - Be familiar with many (most?) of the optimization algorithms currently known
  - Have a deep, intuitive understanding of the algorithms so that you can guess which algorithm is best for which problem
  - Know how to model a real world problem into an optimization one.

How do I go about acquiring these skills? The first one I can get from textbooks, and I would guess for the second two I just have to develop experience by studying lots of real world problems. But where can I see examples of real world problems and solutions that I can learn from? Are there textbooks, papers, or websites about this?

## Answers:
**This is a very good answer provided by [Joris Kinable](https://or.stackexchange.com/users/49/joris-kinable)**

The answer to this question is mostly opinion based and hence not so practical for stackexchange.

Nevertheless, here is my take on this, having both experience in academia and industry. I would first distinguish between knowledge and skills:

- understanding of different optimization models and techniques (knowledge)
  - you must develop a toolbox of optimization methods, such that given a problem, you can apply the 'right' tool to solve the problem. This requires in-depth knowledge of various approaches to be able to assess what will and what won't work.
- understanding of a problem domain (knowledge)
  - it helps if you have at least 1 problem domain in which you are specialized, understand the different models commonly used to solve problems in that domain, know who else works in this domain, and know the state-of-the-art. Think about domains such as healthcare (e.g. nurse rostering), transportation (e.g. routing), or scheduling. You might argue that a person with optimization skills can tackle any problem domain, but in practice it helps a lot if you have prior knowledge in a particular domain.
- ability to implement models, programming (skills)
  - particularly in industry, you must be able to implement, test and evaluate your models. Most companies require familiarity with a programming language (Java/C++/C#/Python), a solver (xpress/gurobi/cplex) and sometimes matlab.
- ability to process and analyse data, as well as to make results interpretable (skills)
  - in the era of big-data, data processing and analysis skills are indispensable. Python and matlab are currently the most common. Knowledge of statistics is also a must.
- ability to distill the right optimization problem (skills)
  - this is perhaps more of a soft-skill. Very often, when working in industry, the problems given to you will be highly ambiguous. Your task is to ask the right questions, and to distill the right problem to solve. More often than not, the people owning the problems are non-technical, have no optimization background and it will take a considerable amount of effort to understand the actual problem that requires solving (which might be very different from what is being asked by the problem owners).

When interviewing with a company, you will be tested on all of the above. If you have the knowledge but not the skills, or vice versa, you have a clear direction on what to improve. Obviously, the above knowledge and skills list is substantial and you won't master them all at once. The most natural approach is to get hands-on experience by working on practical problems. Read papers in a domain you are interested in, look for papers that are motivated by real-world problems (as opposed to a stylized academic problem), and pay attention to what data sources these papers use to perform their experimental evaluation. Just to give an example, both prof Bertsimas as well as prof van Hentenryck have some very interesting papers on online, large scale vehicle routing and ride-sharing/transit problems.

Finally, there is often a difference between models you will find in academic papers and models that are used to solve industry problems. Models in industry are often required to be scalable, implementable, maintainable, interpretable, extendable, must often be developed within a very limited amount of time, must be able to handle all sorts of real-world side-constraints as well as uncertainty and inaccuracies in data input. In practice you will often have to make a compromise between performance and complexity.

Some more practical suggestions: 
1. Participate in the INFORMS career fair. There are often technical people from the companies (not just general recruiters). Ask them what they work on, and what they are looking for.  
2. During their annual meeting, Informs hosts a career breakfast where they typically invite an academic and an industry speaker. This also gives you an idea what companies are looking for.  
3. If you have the opportunity, do an internship in a company that has a major optimization team.