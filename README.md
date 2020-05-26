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

This uses R package `pdftools` to convert pdf files into png files. 
- On Mac OS this requires you to install Ghostscript (e.g. as indicated at http://macappstore.org/ghostscript using Homebrew). 
- On Linux this probably means installing Poppler as indicated at https://CRAN.R-project.org/package=pdftools
- On Windows you are probably safe as is

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
