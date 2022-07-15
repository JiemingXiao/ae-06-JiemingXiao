Sales
================
Jieming Xiao

``` r
library(tidyverse)
library(readxl)
```

-   Read in the Excel file called `sales.xlsx` from the `data-raw/`
    folder such that it looks like the following.

<img src="images/sales-1.png" width="20%" />

``` r
sales <- read_excel("data-raw/sales.xlsx")
```

    ## New names:
    ## • `` -> `...2`

``` r
sales
```

    ## # A tibble: 12 × 2
    ##    `This file contains information on sales.`                              ...2 
    ##    <chr>                                                                   <chr>
    ##  1 Data are organized by brand name, and for each brand we have the ID nu… <NA> 
    ##  2 <NA>                                                                    <NA> 
    ##  3 <NA>                                                                    <NA> 
    ##  4 Brand 1                                                                 n    
    ##  5 1234                                                                    8    
    ##  6 8721                                                                    2    
    ##  7 1822                                                                    3    
    ##  8 Brand 2                                                                 n    
    ##  9 3333                                                                    1    
    ## 10 2156                                                                    3    
    ## 11 3987                                                                    6    
    ## 12 3216                                                                    5

-   **Stretch goal:** Manipulate the sales data such such that it looks
    like the following.

<img src="images/sales-2.png" width="25%" />
