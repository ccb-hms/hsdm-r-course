# HSDM R Course
Website for materials for the R component of HSDM's Research Design and Analaysis Course

# Compile Instructions

This quarto project is designed to render to both html and pdf versions of most pages. 
In order to do this, run the command:

```r
quarto::quarto_render(output_format = "all")
```

from an R session in the project's base directory. 

HTML outputs such as DataTables are captured in the PDF render as screenshots via (webshot)[http://wch.github.io/webshot/].