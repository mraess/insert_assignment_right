# Insert Assignment Operator Right ->

This is a tiny package that functions as an RStudio addin. It lets you add a right assignment operator.

Install with 

``` r 
if (!requireNamespace("devtools", quietly = TRUE))
  install.packages("devtools")
devtools::install_github('mraess/insert_assignment_right')

```

You can now either click on the add-in function at the add-in tab, or add a keyboard shortcut:

EXAMPLE: ALT+R, ``` r iris %>% select(1:2) -> iris_sub```


<img src="https://github.com/mraess/insert_assignment_right/blob/master/insert_screenshots/pic_1.png" alt="Step 1" width="50%" />

<img src="https://github.com/mraess/insert_assignment_right/blob/master/insert_screenshots/pic_2.png" alt="Step 2" width="50%" />

<img src="https://github.com/mraess/insert_assignment_right/blob/master/insert_screenshots/pic_3.png" alt="Step 3" width="50%" />


