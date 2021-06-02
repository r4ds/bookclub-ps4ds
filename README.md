# R4DS Practical Statistics for Data Scientists Book Club

Welcome to the R4DS Practical Statistics for Data Scientists Book Club!

We are working together to read [_Practical Statistics for Data Scientists_](https://www.oreilly.com/library/view/practical-statistics-for/9781492072935/) by Peter Bruce, Andrew Bruce, and Peter Gedeck (O'Reilly, copyright 2020, 978-1-492-07294-2).
Join the #book_club-practical_stats_for_ds channel on the [R4DS Slack](https://r4ds.io/join) to participate.
As we read, we are producing [notes about the book](https://r4ds.github.io/bookclub-ps4ds/).

## Meeting Schedule

If you would like to present, please add your name next to a chapter using the [GitHub Web Editor](https://youtu.be/d41oc2OMAuI)!

*Cohort 1: (starts 2021-05-10) - Mondays, 10:00am EST/EDT*

- 2021-05-10: Introduction - Jon Harmon
- 2021-05-17: Chapter 1: Exploratory Data Analysis - Jon Harmon
- 2021-05-24: Chapter 2: Data and Sampling Distributions - Jonathan Bratt
- **2021-06-07: Chapter 3: Statistical Experiments and Significance Testing - Priyanka
- 2021-06-14: Chapter 4: Regression and Prediction - Morgan Grovenburg
- 2021-06-21: Chapter 5: Classification - PRESENTER(s) TBD
- 2021-06-28: Chapter 6: Statistical Machine Learning - PRESENTER(s) TBD
- 2021-07-12: Chapter 7: Unsupervised Learning - PRESENTER(s) TBD

<hr>


## How to Present

This repository is structured as a [{bookdown}](https://CRAN.R-project.org/package=bookdown) site.
To present, follow these instructions:

1. [Setup Github Locally](https://www.youtube.com/watch?v=hNUNPkoledI)
2. Fork this repository.
3. Create a New Project in RStudio using your fork.
4. Install dependencies for this book with `devtools::install_dev_deps()` (technically optional but it's nice to be able to rebuild the full book).
5. Create a New Branch in your fork for your work.
6. Edit the appropriate chapter file. Use `##` to indicate new slides (new sections).
7. If you use any packages that are not already in the `DESCRIPTION`, add them. You can use `usethis::use_package("myCoolPackage")` to add them quickly!
8. Commit your changes.
9. Push your changes to your branch.
10. Open a Pull Request (PR) to let us know that your slides are ready.

When your PR is checked into the main branch, the bookdown site will rebuild, adding your slides to [this site](https://r4ds.github.io/bookclub-ps4ds/).
