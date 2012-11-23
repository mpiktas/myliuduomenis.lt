---
layout: post
title: "Kodėl naujausias tyrimas nerodo, kad jūsų vaikui būtinai nesiseks?"
description: ""
category: Tyrimai
author_name: Vaidotas Zemlys
author_link: http://vzemlys.wordpress.com
tags: [universiteto baigimas, dėmesio sukaupimas, mokslinis tyrimas, šansų santykis, rezultatų interpretavimas]
---
{% include JB/setup %}




Neseniai [lrytas.lt](http://lrytas.lt) pasirodė [straipsnis](http://www.lrytas.lt/-13444074971344337991-dar%C5%BEelinukai-gebantys-geriau-koncentruoti-d%C4%97mes%C4%AF-turi-daugiau-galimybi%C5%B3-baigti-auk%C5%A1t%C4%85j%C4%85-mokykl%C4%85.htm) apie Oregono universiteto tyrėjų atliktą tyrimą, kurio išvada buvo ta, kad 

> Maži vaikai, kurie sugeba sukaupti dėmesį atlikdami užduotis, turi net 50 procentų didesnį 
> šansą siekti aukštojo mokslo.

Taigi jeigu tavo vaikas nesugeba sukaupti dėmesio, apie universitetą svajok. Taip? Juk net 50 procentų didesnis šansas, tai atrodo tikrai nemažas skirtumas. Bet Einšteinas ir universitetą baigė ir Nobelio premiją gavo, nors vaikystėje buvo laikomas visišku nevėkšla. Taigi kaip čia yra? Viskas paaiškėja šansus konvertavus į tikimybes. Štai šitame grafike atidėta tikimybė vaikui baigti universitetą, kai jis geriau sukaupia dėmesį ir kai jo šansai yra 50% didesni, palyginus su tikimybe vaiko, kuris dėmesį sukaupia prasčiau:

![plot of chunk cmp](https://github.com/mpiktas/myliuduomenis.lt/raw/master/2012-08-16-kodl-naujausias-tyrimas-nerodo-kad-js-vaikui-btinai-nesiseks/figure/cmp.png) 


Tarkime kad jūsų vaikas prasčiau sukaupia dėmesį, bet kitos savybės lemia tai, kad tokių vaikų universiteto baigimo tikimybė yra 50%. Tada jeigu jūsų vaikas susikaupia geriau, ir turi tokias pačias savybes kaip prasčiau susikaupiantis vaikas tikimybė baigti universitetą iš grafiko matome yra 60%. Tai neatrodo taip jau beviltiškai, kaip pasirodė iš pirmo karto. 

Iš kur čia gavosi toks skirtumas ir kaip tos tikimybės suskaičiuotos? Daryto tyrimo [aprašyme](http://www.sciencedirect.com/science/article/pii/S0885200612000762) galima rasti kad 50 procentų didesnis šansas reiškia [odds ratio](http://en.wikipedia.org/wiki/Odds_ratio) arba šansų santykį lygų 1,5. Moksliniuose straipsniuose tai nusistovėjęs tyrimo rezultatų pateikimo būdas. Žinant, kas yra tas šansų santykis, nesunku jį konvertuoti į tikimybes. 

Šio įrašo tikslas nėra sumenkinti tyrimo svarbos. Kaip gairė vaikų ugdyme tai labai svarbus tyrimas. Bet reikia turėti omenyje, kad tokiuose tyrimuose dažnai galioja ceteris paribus principas. Tai reiškia, kad teigiamas ar neigiamas poveikis randamas kontroliuojant kitus parametrus, tokius kaip vaiko įgimti sugebėjimai, namuose mokymuisi palanki aplinka, šeimos finansinė padėtis ir kita, kurie gali turėti kur kas didesnę įtaką galutiniam rezultatui, negu tiriamas poveikis. 

[Straipsniui naudota medžiaga](http://github.com/mpiktas/myliuduomenis.lt/tree/master/2012-08-16-kodl-naujausias-tyrimas-nerodo-kad-js-vaikui-btinai-nesiseks)
