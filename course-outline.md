Chapter 1 – Start with the end goal in mind
  * Lesson 1.1 – The importance of reporting
    * A learning objective: The learner will be able to explain the relevance of R Markdown in reporting findings: R Markdown allows one to efficiently create clear reports to communicate findings.
    * Some syntax introduced/used: the `.Rmd` file, the `Knit` button in RStudio, R code chunks (```` ```{r} some code ``` ````)
  * Lesson 1.2 – Creating your first report
    * A learning objective: The learner will be able to describe how the elements of a .Rmd file contribute to a report.
    * Some syntax introduced/used: the `.Rmd` file, the `Knit` button in RStudio, R code chunks (```` ```{r} some code ``` ````)
  * Lesson 1.3 – Exploring the dataset
    * A learning objective: The learner will be able to explore the dataset of this course using descriptive statistics and graphics.

Chapter 2 – Formatting the text
  * Lesson 2.1 – Styling narrative sections
    * A learning objective: The learner will be able to format plain text using the most popular Pandoc's markdown syntax.
    * Some syntax introduced/used: headings, links, emphasis, Strikeout, Superscripts and subscripts, Math, images, code formatting (`` `some text` ``)
  * Lesson 2.2 – Adding text tables
    * A learning objective: The learner will be able to add tables to their report. The learner will be able to format tables, considering table captions, multiline tables, grid tables, and pipe tables.
  * Lesson 2.3 – Using lists
    * A learning objective: The learner will be able to add bulleted an numbered lists to their report.
    * Some syntax introduced/used: `* Item 1`, `1. Item 1`, blank line before and after list

Chapter 3 – Adding the code
  * Lesson 3.1 – Inline Code & Code chunks
    * A learning objective: The learner will be able to use inline code and code chunks to include code in line with text or include tables, graphics, ..., respectively.
    * Some syntax introduced/used: inline code (`` `r some code` ``), R code chunks (```` ```{r} some code ``` ````)
  * Lesson 3.2 – Code chunk options
    * A learning objective: The learner will be able to cutomize code output using the most popular code chunk options.
    * Some syntax introduced/used: `message`, `warning`, `error`, `echo`, `eval`, `results`, `fig.height`, `fig.width`
  * Lesson 3.3 – Labeling and reusing code chunks
    * A learning objective: The learner will be able to label code chunks and refer to these labelled code chunks in another code chunk using the `ref.label` option.
    * Some syntax introduced/used: Label code chunks by adding label as first option (```` ```{r label, option 1} some code ``` ````), refer in one code chunk to another code chunk with ref.label option (```` ```{r ref.label = label, option 1} some code ``` ````)
  * Lesson 3.4 – Formatting data tables
    * A learning objective: The learner will be able to display data with additional formatting using the `knitr::kable function.
    * Some syntax introduced/used: `knitr::kable`

Chapter 4 – Rendering the document
  * Lesson 4.1 – Behind the scenes
    * A learning objective: The learner will be able to list the steps between their `.Rmd` file and their output file.
    * Some syntax introduced/used:
  * Lesson 4.2 – The YAML header
    * A learning objective: The learner will be able to define the YAML header in function of the desired output format: html_document (default), pdf_document, word_document, beamer_presentation, ioslides_presentation or slidy_presentation. The learner will be able to generate multiple file formats at once.
    * Some syntax introduced/used: `rmarkdown::render render(“doc.rmd”, c(“output_format_1”, “output_format_2”))`
  * Lesson 4.3 – Working with style sheets
    * A learning objective: The learner will be able to customize the style of the output document using specify knitr and pandoc options, or css style sheets.
    * Some syntax introduced/used: `highlight`, `theme`, `toc`, `number_sections`
