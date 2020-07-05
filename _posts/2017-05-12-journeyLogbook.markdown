---
layout:     post
title:      "Journey Logbook"
subtitle:   ""
date:       2017-05-12 12:00:00
author:     "Jakab Bence and Martinák Zalán"
header-img: "img/projektek/almasderes/plane-1031681__340.jpg"
categories: projektek-old
---

<h2 class="section-heading">Cél</h2>

<p>Az ember a kezdetektől fogva vándorolt és gyűjtögetett. A modern kori ember is szeret vándorolni, azaz a mai értelemben utazni, és továbbra is megmaradt a gyűjtögetés, mint szenvedély, ami a leutazott kilométerek gyűjtését jelenti ma már. Mivel az ember hiú is, így szereti megmutatni embertársainak „gyűjtögetése” eredményét. Ezt az igényt hivatott kiszolgálni a Journey Logbook (Útinapló) weboldalunk, melyre az utazók feltölthetik repülős utazásaik alapadatait melyből az oldal egy színes, informatív, személyre szabott Útinaplót készít.</p>

<h2 class="section-heading">Működés</h2>

<p>A repülős utazások alapadatait (Honnan, Hová, Mikor) egy egyszerű szerkezetű MS Excel táblázatban kell első körben az utazónak rögzítenie.</p>

<!--kép tábla-->
<a href="#">
    <img src="{{ site.baseurl }}/img/projektek/almasderes/journeyLogbook_excel.png" class="img-responsive" alt="Post Sample Image">
</a>

<p>Az Excel fájl feltöltését követően egy informatív, dashboard jellegű összefoglaló kerül előállításra:</p>

<!--kép logbook-->
<a href="#">
    <img src="{{ site.baseurl }}/img/projektek/almasderes/journeyLogbook_page_top.jpg" class="img-responsive" alt="Post Sample Image">
</a>

<p>Itt térképes formában, ill. különböző grafikonokon keresztül kerülnek megjelenítésre az utazások:</p>

<!--kép charts-->
<a href="#">
    <img src="{{ site.baseurl }}/img/projektek/almasderes/journeyLogbook_page_charts.jpg" class="img-responsive" alt="Post Sample Image">
</a>


<h2 class="section-heading">Megvalósítás</h2>

<p>Az oldal alapfunkciói Javascript-ben lettek megírva. A térképes megjelenítéshez a <a href="https://developers.google.com/maps/">Google Maps API</a>-jai, a grafikonok elkészítéséhez a <a href="https://developers.google.com/chart/">Google Charts</a> szolgáltatása lett használva.</p>

<h4> <a href="https://mazalan01.github.io/"> Élő demo-verzió </a> </h4>
<h4> <a href="https://github.com/mazalan01/mazalan01.github.io"> Elérhető forráskód </a> </h4>
