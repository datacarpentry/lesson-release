# Contributing when lessons have RMarkdown files

From the [How to Contribute](how-to-contribute.md) document, this a caveat
for lessons using Rmarkdown for the episodes.

In the lessons with Rmarkdown files (for the Data Carpentry Ecology lessons, that's just the R lesson), previewing changes and the files to push are slightly different.

- To make the changes, edit the .Rmd files. You likely will be doing this in RStudio.
- To preview those changes, you can either:
  * click on the "knit" button in RStudio
  * type `rmarkdown::render_site("03-dplyr.Rmd")` at the R terminal (to render the dplyr lesson for instance)
  * if you have `Make` installed on your system, type `make` at your shell terminal.
- Once you're happy with your changes, commit and push the .Rmd files (and not the html files) to your repository.

Everything else is the same for submitting a pull request. 

