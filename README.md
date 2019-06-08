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

![Step1](https://github.com/mraess/insert_assignment_right/blob/master/insert_screenshots/pic_1.png)

![Step2](https://github.com/mraess/insert_assignment_right/blob/master/insert_screenshots/pic_2.png)

![Step3](https://github.com/mraess/insert_assignment_right/blob/master/insert_screenshots/pic_3.png)


