Problema 11
================
Álvarez Letona Manuel
31/1/2022

``` r
library(tidyverse)
```

    ## -- Attaching packages --------------------------------------- tidyverse 1.3.1 --

    ## v ggplot2 3.3.5     v purrr   0.3.4
    ## v tibble  3.1.5     v dplyr   1.0.7
    ## v tidyr   1.1.4     v stringr 1.4.0
    ## v readr   2.1.1     v forcats 0.5.1

    ## -- Conflicts ------------------------------------------ tidyverse_conflicts() --
    ## x dplyr::filter() masks stats::filter()
    ## x dplyr::lag()    masks stats::lag()

### Problema 11

``` r
##Calculo de Pendiente
J<-110/1200
##Formacion de la Función
t<-function(L,J){
  0.3*(L/(J**(1/4)))**0.76
}
##Comprobación
t(1200,J)
```

    ## [1] 103.3901

### Problema 13

``` r
#gbif_peru
#gbif_peru %>% select(stateProvince) %>% unique
#gbif_peru %>% group_by(stateProvince) %>% count() %>% view()
#Con dia y año
#gbif_peru %>% select(stateProvince) %>% unique
#gbif_peru %>% group_by(stateProvince,year,day) %>% count() %>% arrange(day,year)
```
