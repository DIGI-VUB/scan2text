# scan2text

Shiny application to **easily extract text from areas in images or scanned pdf files**

### Installation

Install the following R packages 

```
install.packages("shinydashboard")
install.packages("shiny")
install.packages("shinyFiles")
install.packages("data.table")
install.packages("jsonlite")
install.packages("magick")
install.packages("pdftools")
install.packages("tesseract")
install.packages("digest")
```

### Usage

Either

- If you downloaded this repository just run `shiny::runApp("app.R")` to launch the Shiny application
- If you did not download this repository just run `shiny::runGitHub("DIGI-VUB/scan2text")` to launch the Shiny application
- Or in RStudio open the file `app.R` and press the `> Run App` button

![](example/example.gif)


- Selected areas from the images or pdf files and the optionally extracted text contained in these areas are saved in de www folder of your current directory

### DIGI

By DIGI: Brussels Platform for Digital Humanities: https://digi.research.vub.be

![](example/logo.png)
