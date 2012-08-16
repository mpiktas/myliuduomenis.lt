---
layout: post
title: "Kodėl naujausias tyrimas nerodo, kad jūsų vaikui būtinai nesiseks?"
description: ""
category: 
tags: []
---
{% include JB/setup %}




Neseniai [lrytas.lt](http://lrytas.lt) pasirodė [straipsnis](http://www.lrytas.lt/-13444074971344337991-dar%C5%BEelinukai-gebantys-geriau-koncentruoti-d%C4%97mes%C4%AF-turi-daugiau-galimybi%C5%B3-baigti-auk%C5%A1t%C4%85j%C4%85-mokykl%C4%85.htm) apie Oregono universiteto tyrėjų atliktą tyrimą, kurio išvada buvo ta, kad 

> Maži vaikai, kurie sugeba sukaupti dėmesį atlikdami užduotis, turi net 50 procentų didesnį 
> šansą siekti aukštojo mokslo.

Taigi jeigu tavo vaikas nesugeba sukaupti dėmesio, apie universitetą svajok. Taip? Juk net 50 procentų didesnis šansas, tai atrodo tikrai nemažas skirtumas. Bet Einšteinas ir universitetą baigė ir Nobelio premiją gavo, nors vaikystėje buvo laikomas visišku nevėkšla. Taigi kaip čia yra? Viskas paaiškėja šansus konvertavus į tikimybes. Štai šitame grafike atidėta tikimybė vaikui baigti universitetą, kai jis geriau sukaupia dėmesį ir kai jo šansai yra 50% didesni, palyginus su tikimybe vaiko, kuris dėmesį sukaupia prasčiau:



```r
library(ggplot2)
ff <- function(q, z) 1 - 1/(z * (q/(1 - q)) + 1)
q <- seq(0, 1, by = 0.001)
qplot(q, ff(q, 1.5), geom = "line", xlab = "Tikimybė, kad baigs universitetą, jei prasčiau susikaupia", 
    ylab = "Tikimybė, kad baigs universitetą, jei susikaupia geriau") + opts(title = "Universiteto baigimo tikimybių palyginimas")
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei susikaupia geriau' dans 'mbcsToSbcs' : le point est substitué pour <c4>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei susikaupia geriau' dans 'mbcsToSbcs' : le point est substitué pour <97>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei susikaupia geriau' dans 'mbcsToSbcs' : le point est substitué pour <c4>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei susikaupia geriau' dans 'mbcsToSbcs' : le point est substitué pour <85>
```



```
## Warning message: erreur de conversion de 'Universiteto baigimo tikimybių palyginimas' dans 'mbcsToSbcs' : le point est substitué pour <c5>
```



```
## Warning message: erreur de conversion de 'Universiteto baigimo tikimybių palyginimas' dans 'mbcsToSbcs' : le point est substitué pour <b3>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei prasčiau susikaupia' dans 'mbcsToSbcs' : le point est substitué pour <c4>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei prasčiau susikaupia' dans 'mbcsToSbcs' : le point est substitué pour <97>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei prasčiau susikaupia' dans 'mbcsToSbcs' : le point est substitué pour <c4>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei prasčiau susikaupia' dans 'mbcsToSbcs' : le point est substitué pour <85>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei prasčiau susikaupia' dans 'mbcsToSbcs' : le point est substitué pour <c4>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei prasčiau susikaupia' dans 'mbcsToSbcs' : le point est substitué pour <8d>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei susikaupia geriau' dans 'mbcsToSbcs' : le point est substitué pour <c4>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei susikaupia geriau' dans 'mbcsToSbcs' : le point est substitué pour <97>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei susikaupia geriau' dans 'mbcsToSbcs' : le point est substitué pour <c4>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei susikaupia geriau' dans 'mbcsToSbcs' : le point est substitué pour <85>
```



```
## Warning message: erreur de conversion de 'Universiteto baigimo tikimybių palyginimas' dans 'mbcsToSbcs' : le point est substitué pour <c5>
```



```
## Warning message: erreur de conversion de 'Universiteto baigimo tikimybių palyginimas' dans 'mbcsToSbcs' : le point est substitué pour <b3>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei prasčiau susikaupia' dans 'mbcsToSbcs' : le point est substitué pour <c4>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei prasčiau susikaupia' dans 'mbcsToSbcs' : le point est substitué pour <97>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei prasčiau susikaupia' dans 'mbcsToSbcs' : le point est substitué pour <c4>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei prasčiau susikaupia' dans 'mbcsToSbcs' : le point est substitué pour <85>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei prasčiau susikaupia' dans 'mbcsToSbcs' : le point est substitué pour <c4>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei prasčiau susikaupia' dans 'mbcsToSbcs' : le point est substitué pour <8d>
```



```
## Warning message: erreur de conversion de 'Universiteto baigimo tikimybių palyginimas' dans 'mbcsToSbcs' : le point est substitué pour <c5>
```



```
## Warning message: erreur de conversion de 'Universiteto baigimo tikimybių palyginimas' dans 'mbcsToSbcs' : le point est substitué pour <b3>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei prasčiau susikaupia' dans 'mbcsToSbcs' : le point est substitué pour <c4>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei prasčiau susikaupia' dans 'mbcsToSbcs' : le point est substitué pour <97>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei prasčiau susikaupia' dans 'mbcsToSbcs' : le point est substitué pour <c4>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei prasčiau susikaupia' dans 'mbcsToSbcs' : le point est substitué pour <85>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei prasčiau susikaupia' dans 'mbcsToSbcs' : le point est substitué pour <c4>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei prasčiau susikaupia' dans 'mbcsToSbcs' : le point est substitué pour <8d>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei susikaupia geriau' dans 'mbcsToSbcs' : le point est substitué pour <c4>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei susikaupia geriau' dans 'mbcsToSbcs' : le point est substitué pour <97>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei susikaupia geriau' dans 'mbcsToSbcs' : le point est substitué pour <c4>
```



```
## Warning message: erreur de conversion de 'Tikimybė, kad baigs universitetą, jei susikaupia geriau' dans 'mbcsToSbcs' : le point est substitué pour <85>
```

![plot of chunk unnamed-chunk-1](https://github.com/mpiktas/myliuduomenis.lt/raw/master/2012-08-16-kodl-naujausias-tyrimas-nerodo-kad-js-vaikui-btinai-nesiseks/figure/unnamed-chunk-1.png) 






tyrimo [aprašymą](http://www.sciencedirect.com/science/article/pii/S0885200612000762). 
