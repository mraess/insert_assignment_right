# Insert Assignment Operator Right ->

This is a tiny package that functions as an RStudio addin. It lets you add a right assignment operator.

Install with 

``` r 
if (!requireNamespace("devtools", quietly = TRUE))
  install.packages("devtools")
devtools::install_github('mraess/insert_assignment_right')

```

You can now either click on the add-in function at the add-in tab, or add a keyboard shortcut:

![Step1](https://github.com/mraess/insert_assignment_right/insert_pics/pic_1.png)

R-addin to add assignment operator with ALT+R, e.g. ``` r iris %>% select(1:2) -> iris_sub```
