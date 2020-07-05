---
layout:     post
title:      "Vízilabda statisztikakezelő applikáció"
subtitle:   "avagy hogyan ismerjük ki játékostársainkat, ellenfeleinket."
date:       2017-04-20 04:20:00
author:     "Csukás Ádám, Székely Mihály"
header-img: "img/projektek/almasderes/WaterPolo2.jpg"
categories: projektek
---

<h2 class="section-heading">Alapelképzelés</h2>

<p>Vízilabda mérkőzéseken előnyt nyújt a csapat számára, hogyha az edző képes specifikusan az ellenfél tulajdonságai alapján felkészíteni a csapatát. Ezen felül hasznosnak bizonyulnak olyan adatok is, amelyek a saját játékosok erősségeit, gyengeségeit mutatják be az edzésterv testreszabása céljából. Applikációnk erre a problémára nyújt megoldást.</p>

<p>Ennek érdekében tájékozódtunk a jelenleg létező hasonló programok felépítéséről, funkcióiról, illetve több vízilabda szakemberrel is egyeztettünk, hogy a lehető leghasznosabb programot hozhassuk létre.</p>

<h2 class="section-heading">Működési elv</h2>

<p>Első lépésként beírjuk az adott mérkőzésen szereplő játékosok neveit, melyeket a hivatalosan aktív játékosok listájából választhatjuk ki.</p>

<a href="#">
    <img src="{{ site.baseurl }}/img/projektek/almasderes/waterpolo_PlayerSelection.jpg" class="img-responsive" alt="Post Sample Image">
</a>

<p>Az ezt követő oldalon van alkalmazásunk magja, ugyanis itt nyílik lehetőségünk a mérkőzés során megtörtént események bevitelére, illetve a eredmény követésére.</p>

<a href="#">
    <img src="{{ site.baseurl }}/img/projektek/almasderes/waterpolo_ActivitySelection.jpg" class="img-responsive" alt="Post Sample Image">
</a>

<p>Végül pedig a mérkőzés befejeztével, vagy akár közben is leolvashatjuk az adatokat, például hőtérkép segítségével.</p>

<a href="#">
    <img src="{{ site.baseurl }}/img/projektek/almasderes/waterpolo_Heatmap.jpg" class="img-responsive" alt="Post Sample Image">
</a>

