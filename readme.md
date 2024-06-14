# Digital Research Toolkit for Linguists

Author: `anna.pryslopska[ AT ]ling.uni-stuttgart.de`

These are the original materials from the course "Digital Research Toolkit for Linguists taught by me in the Summer Semester 2024 at the University of Stuttgart.
The materials will be updated weekly. Identifying information of the in-class participants will be removed, so some slides, data or exercises may be missing.

You are more than welcome to follow along but I will not be able to grade or evaluate your homework.

## Course description

This seminar provides a gentle, hands-on introduction to the essential tools for quantitative research for students of linguistics and the humanities overall. During the course of the seminar, the students will familiarize themselves with software that is rarely taught but is invaluable in developing an efficient, transparent, reusable, and scalable research workflow (e.g. R basics, LaTeX, git). From text file, through data visualization, to creating beautiful reports: this course will empower students to improve their skill and help them establish good practices.

The seminar is targeted at **students with little to no experience with programming**. It provides key skills that are useful for research and industry jobs.

We will cover topics such as:  
✔ How can I make sense of my data?  
✔ How can I communicate what I found?  
✔ How do I share my data and collaborate with others?  

We will NOT cover topics such as:  
❌ Experiment design  
❌ Inferential statistics  
❌ Cognitive modelling  
❌ Corpus research  

## Schedule and syllabus

This is a rough overview of the topics discussed every week. These are subject to change, depending on how the class goes.

| Week | Topic | Description | Assignments | Materials |
| ---- | ----- | ----------- | ----------- | --------- |
| 1    | Introduction & overview | Course overview and expectations, classroom management and assignments/grading etc. Data collection. | Complete [Experiment 1](https://farm.pcibex.net/p/glQRwV/) and [Experiment 2](https://farm.pcibex.net/p/ceZUkj/) and recruit one more person. [Install R](https://www.r-project.org/) and [RStudio](https://posit.co/download/rstudio-desktop/), install [Texmaker](https://www.xm1math.net/texmaker/) or make an [Overleaf](https://www.overleaf.com/) account. | [Slides](https://github.com/a-nap/DRTfL2024/blob/1e3ac235f6957eaaebf8a19f1889d0b6a6f79fb7/Week%201/week1handout.pdf) |
| 2    | Data, R and RStudio | Intro recap, directories, R and RStudio, installing and loading packages, working with scripts | Read chapters 2, 6 and 7 of [R for Data Science](https://r4ds.hadley.nz/), complete [assignment 1](https://github.com/a-nap/DRTfL2024/blob/main/Week%202/week2assignment.md) | [Slides](https://github.com/a-nap/DRTfL2024/blob/main/Week%202/week2handout.pdf), [code](https://github.com/a-nap/DRTfL2024/blob/main/Week%202/code_APR15.r) |
| 3    | Reading data, data inspection and manipulation | Looking at your data, data types, importing, making sense of the data, intro to sorting, filtering, subsetting, removing missing data, data manipulation | Read chapters 3, 4 and 5 of [R for Data Science](https://r4ds.hadley.nz/), complete [assignment 2](https://github.com/a-nap/DRTfL2024/blob/main/Week%203/week3assignment.md). | [Slides](https://github.com/a-nap/DRTfL2024/blob/main/Week%203/week3handout.pdf), [code](https://github.com/a-nap/DRTfL2024/blob/main/Week%203/code_APR22.r), data |
| 4    | Data manipulation | Basic operators, data manipulation (filtering, sorting, subsetting, arranging), pipelines, tidy code, practice. | Compete [assignment 3](https://github.com/a-nap/DRTfL2024/blob/main/Week%204/week4assignment.md) | [Slides](https://github.com/a-nap/DRTfL2024/blob/main/Week%204/week4handout.pdf), [code](https://github.com/a-nap/DRTfL2024/blob/main/Week%204/code_APR29.r), data |
| 5    | Data manipulation and error handling | Summary statistics, grouping, merging, if ... else, naming variables, tidy code, error handling and getting help. | [Assignment 4](https://github.com/a-nap/DRTfL2024/blob/main/Week%205/week5assignment.md), read the slides from the QCBS R Workshop Series [*Workshop 3: Introduction to data visualisation with `ggplot2`*](https://r.qcbs.ca/workshop03/pres-en/workshop03-pres-en.html) | [Slides](https://github.com/a-nap/DRTfL2024/blob/main/Week%205/week5handout.pdf), [code](https://github.com/a-nap/DRTfL2024/blob/main/Week%205/code_MAY06.r) |
| 6    | Data visualization | Communicating with graphics, choice of visualization, plot types, best practices, visualizing in R (`ggplot2`, `esquisse`), exporting plots and data | Complete [assignment 5](https://github.com/a-nap/DRTfL2024/blob/main/Week%206/week6assignment.md). If you haven't yet, install the package `esquisse` | [Slides](https://github.com/a-nap/DRTfL2024/blob/main/Week%206/week6handout.pdf), [code](https://github.com/a-nap/DRTfL2024/blob/main/Week%206/code_MAY13.r) |
| 7    | No class | Holiday | | |
| 8    | Data visualization | Data visualization recap, best practices, lying with plots, practical exercises, exporting/saving plots and data. | Complete [assignment 6](https://github.com/a-nap/DRTfL2024/blob/main/Week%208/week8assignment.md). Install [Quarto](https://quarto.org/docs/get-started/). Watch [the introductory video](https://www.youtube.com/watch?v=_f3latmOhew) | Slides [large](https://github.com/a-nap/DRTfL2024/blob/main/Week%208/week8.pdf) and [compressed](https://github.com/a-nap/DRTfL2024/blob/main/Week%208/week8handout.pdf), [code](https://github.com/a-nap/DRTfL2024/blob/main/Week%208/code_MAY27.r) |
| 9    | Creating reports with Quarto and knitr | Pandoc, markdown, Quarto, basic syntax and elements, export, document, and chunk options, documentation | Complete [assignment 7](https://github.com/a-nap/DRTfL2024/blob/main/Week%209/week9assignment.md). | [Slides](https://github.com/a-nap/DRTfL2024/blob/main/Week%209/week9handout.pdf), [compressed Quarto files](https://github.com/a-nap/DRTfL2024/blob/main/Week%209/quarto-demo.zip) |
| 10    | Typesetting documents with LaTeX | What is LaTeX, basic document and file structure, advantages and disadvantages, from R to LaTeX | tbd | Slides, code |
| 11    | Typesetting documents with LaTeX | Editing text (commands, whitespace, environments, font properties, figures, and tables), glosses, IPA symbols, semantic formulae, syntactic trees | tbd | Slides, code |
| 12   | Typesetting documents with LaTeX and bibliography management | Large projects, citations, references, bibliography styles, bib file structure | tbd | Slides, code |
| 13   | Literature and reference management, common command line commands | Reference managers, looking up literature, text editors, command line commands (grep, diff, ping, cd, etc.) | tbd | Slides, code |
| 14   | Version control and Git | Git, GitHub, version control | tbd | Slides |
| 15   | Version control and Git | Git, GitHub, SSH, reverting to older versions | tbd | Slides, code |
| 16   | Course wrap-up | | | Slides |

## Recommended reading

### R

- QCBS R Workshop Series [https://r.qcbs.ca/](https://r.qcbs.ca/)
- Wickham, Hadley, Mine Çetinkaya-Rundel, and Garrett Grolemund (2023). [*R for data science: import, tidy, transform, visualize, and model data*](https://r4ds.hadley.nz/). 2nd ed. O’Reilly Media, Inc. URL: `https://r4ds.hadley.nz/`.


### Experiments

- Free-response: Erickson, Thomas D and Mark E Mattson (1981). “From words to meaning: A semantic illusion”. In: *Journal of Verbal Learning and Verbal Behavior* 20.5, pp. 540–551. DOI: [10.1016/s0022-5371(81)90165-1](https://www.sciencedirect.com/science/article/abs/pii/S0022537181901651).
- Self-paced reading with acceptability judgments: Gibson, Edward, Leon Bergen, and Steven T Piantadosi (2013). “Rational integration of noisy evidence and prior semantic expectations in sentence interpretation”. In: *Proceedings of the National Academy of Sciences* 110.20, pp. 8051–8056. DOI: [10.1073/pnas.1216438110](https://www.pnas.org/doi/full/10.1073/pnas.1216438110).