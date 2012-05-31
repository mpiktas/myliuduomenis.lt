---
layout: post
title: "Rožiniai akiniai II"
description: ""
category: Ekonomika
author_name: Vaidotas Zemlys
author_link: http://vzemlys.wordpress.com
tags: [A. Butkevičius, valstybės skola, skolos santykis su BVP, I. Šimonytė, 15min.lt]
---
{% include JB/setup %}
Prieš tai rašytą [tekstą](http://myliuduomenis.lt/Ekonomika/2012/05/23/roziniai-akiniai) sutiko atspausdinti [15.min](http://www.15min.lt). Aišku teko prieš tai jį [paredaguoti](http://www.15min.lt/naujiena/ziniosgyvai/nuomones/vaidotas-zemlys-apie-klaidingus-a-butkeviciaus-svarstymus-del-bvp-augimo-18-216502?preview), nes "...mes dedame straipsnius su daugiau argumentų, išvystyta mintimi", dėl ko negali prieštarauti :). 

Į išspausdintą nuomonę gana greitai buvo [atsakyta](http://www.15min.lt/naujiena/ziniosgyvai/nuomones/algirdas-butkevicius-ar-sulauksime-ekonomikos-pavasario-18-216786). Ne kasdieną pasiseka apsikeisti nuomonėmis su Seimo opozicijos lyderiu (pabandykite tai padaryti didesnėje valstybėje), tai jaučiuosi pamalonintas. 

Galima sakyti iš dalies mano straipsnis pasiekė tikslą, nes atsakyme A. Butkevičius jau cituoja realaus BVP augimo skaičius ir pakeičia BVP kritimo žinią į lėtėjančio augimo. Kodėl jis nusprendžia, kad aš kitokiu pjūviu nagrinėjau duomenis, tai nėra aišku. Grafike buvo tie duomenys, kuriuos jis citavo originaliame straipsnyje, tik pratęsta istorinė eilutė. 

Kad nebūtų nusukta kalba nuo "tragiškos" Lietuvos padėties straipsnį A. Butkevičius baigia pasvarstymu apie Lietuvos valstybės skolą. A. Butkevičius teigia, kad:

> Rekordiniai šie metai ir skolinimosi mastais. Vos per pusketvirto mėnesio Vyriausybė sugebėjo pasiskolinti 6,8 mlrd. litų, kuriuos panaudosime senesnėms skoloms grąžinti ir didėjančioms biudžeto skylėms lopyti. Šią sumą pridėjus prie 41,74 mlrd., kuriuos Lietuva buvo skolinga praėjusių metų gruodžio 31-ąją, susidaro grėsminga skola, dabar jau sudaranti maždaug 46 proc. BVP. Matant tokią situaciją, apgailėtinai skamba Vyriausybės pranešimas, kad pirmąjį šių metų ketvirtį valstybės biudžetas pasipildė 104,7 mln. litų pajamų daugiau, nei planuota.

Čia demonstruojama ypatinga aritmetika. Vyriausybė skolinasi 6,8 mlrd litų skolom **grąžinti** bet ši suma pridedama prie jau esamos skolos. Taigi jeigu esi skolingas 1 litą ir pasiskolini 1 litą grąžinti skolai, lieki skolingas 2 litus. Priminsiu, kad A. Butkevičius 2 metus buvo finansų ministras.

Kita įdomi mintis yra apie grėsmingą skolą sudarančią net 46% BVP. [Maastrichto sutartyje](http://en.wikipedia.org/wiki/Maastricht_Treaty) nurodyta, kad skola metų pabaigoje neturi viršyti 60%. [Eurostato duomenimis](http://epp.eurostat.ec.europa.eu/tgm/table.do?tab=table&init=1&plugin=1&language=en&pcode=tsieb090) (be įmantrių A. Butkevičiaus finansinių skaičiavimų), Lietuvos skola sudaro 38,5% BVP. Palyginimui galima pažiūrėti į grafiką, kaip atrodo kitų šalių skolos su BVP santykiai:

<!-- GeoChart generated in R 2.15.0 by googleVis 0.2.15 package -->
<!-- Thu May 31 06:03:59 2012 -->


<!-- jsHeader -->
<script type="text/javascript" src="http://www.google.com/jsapi">
</script>
<script type="text/javascript">
 
// jsData 
function gvisDataGeoChartID13239147173 ()
{
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 "Bulgaria",
       16.3 
],
[
 "Czech Republic",
       41.2 
],
[
 "Denmark",
       46.5 
],
[
 "Germany",
       81.2 
],
[
 "Estonia",
          6 
],
[
 "Ireland",
      108.2 
],
[
 "Greece",
      165.3 
],
[
 "Spain",
       68.5 
],
[
 "France",
       85.8 
],
[
 "Italy",
      120.1 
],
[
 "Cyprus",
       71.6 
],
[
 "Latvia",
       42.6 
],
[
 "Lithuania",
       38.5 
],
[
 "Luxembourg",
       18.2 
],
[
 "Hungary",
       80.6 
],
[
 "Malta",
         72 
],
[
 "Netherlands",
       65.2 
],
[
 "Austria",
       72.2 
],
[
 "Poland",
       56.3 
],
[
 "Portugal",
      107.8 
],
[
 "Romania",
       33.3 
],
[
 "Slovenia",
       47.6 
],
[
 "Slovakia",
       43.3 
],
[
 "Finland",
       48.6 
],
[
 "Sweden",
       38.4 
],
[
 "United Kingdom",
       85.7 
],
[
 "Iceland",
       98.8 
],
[
 "Norway",
         29 
] 
];
data.addColumn('string','Country');
data.addColumn('number','Skolos.santykis');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartGeoChartID13239147173() {
  var data = gvisDataGeoChartID13239147173();
  var options = {};
options["width"] =    556;
options["height"] =    347;
options["region"] = "150";
options["colorAxis"] = {colors: ['blue', 'red']};

     var chart = new google.visualization.GeoChart(
       document.getElementById('GeoChartID13239147173')
     );
     chart.draw(data,options);
    

}
  
 
// jsDisplayChart 
function displayChartGeoChartID13239147173()
{
  google.load("visualization", "1", { packages:["geochart"] }); 
  google.setOnLoadCallback(drawChartGeoChartID13239147173);
}
 
// jsChart 
displayChartGeoChartID13239147173()
 
<!-- jsFooter -->  
//-->
</script>
 
<!-- divChart -->
  
<div id="GeoChartID13239147173"
  style="width: 556px; height: 347px;">
</div>




Matome, kad Lietuvos situacija palyginus su kitomis šalimis yra visai nebloga. Iki Estijos mums toli, bet visą Europą išlaikančios Vokietijos skolos santykis su BVP yra daugiau nei dvigubai didesnis negu Lietuvos. 

A. Butkevičiaus svarstymų apie skolą neiškentė nepakomentavus ir [I. Šimonytė.](http://www.15min.lt/naujiena/ziniosgyvai/nuomones/ingrida-simonyte-miegokite-ramiai-daktare-algirdai-butkeviciau-kitai-vyriausybei-teks-rupintis-jusu-valdzios-isleista-skola-18-218787) Matosi, kad tai skaudi jai tema, nes jai teko spręsti problemas, kurias paliko Vyriausybė, kurios finansų ministru 2004-2006 metais buvo tas pats A. Butkevičius.

Tęsiant "tragiškos" Lietuvos ekonominės situacijos temą, gana linksmai atrodo tuojau pat po A. Butkevičiaus komentaro pasirodę [Lietuvos banko](http://vz.lt/?PublicationId=92a1d1de-e31a-4fd4-93a8-95e3665d2989&ref=rss) ir [Europos Komisijos](http://vz.lt/article/2012/5/11/ek-pagerino-lietuvos-bvp-prognoze) pranešimai apie padidintas Lietuvos BVP metinio augimo prognozes. 

Pabaigai norėčiau pasakyti, kad čia pateikta informacija nereiškia, kad Lietuvoje staiga pradėjo plaukti pieno upės. Bet gal nėra viskas taip blogai, kaip nori parodyti A. Butkevičius.

[Straipsniui naudota medžiaga](http://github.com/mpiktas/myliuduomenis.lt/tree/master/2012-05-24-roziniai-akiniai-ii)
