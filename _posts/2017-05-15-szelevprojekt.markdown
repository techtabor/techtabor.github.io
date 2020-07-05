---
layout:     post
title:      "Bajnokságszervező"
date:       2017-05-15 09:00:00
author:     "SzeLev"
header-img: "img/projektek/almasderes/szelevprojekt/header.jpg"
categories: projektek
tags: ["almasderes"]
---

# Bevezetés #

Kisebb házi bajnokságok esetén a verseny megszervezése, és az eredmények követése legtöbbször papíron történik, mely nehezíti a
 feldolgozást. Ezért készítettem egy alkalmazást, mellyel mobileszközünket használva tudjuk a mérkőzések eredményeit rögzíteni
és a szoftver segítségével azonnal megtudhatjuk a bajnokság aktuális állását.

# Technológia #

Az alkalmazás azért készült mobileszközre, mivel egy ilyen bajnokság helyszínén nem biztos, hogy van WiFi (pl. tengerparton),
valamint okostelefonja majdnem mindenkinek van.

A fejlesztés során [Android Studio][1]-t használtam, mely főleg java-t és xml-t használ.

# Funkciók #

A szoftver két fajta bajnokságot tud kezelni.

<img src="{{ site.baseurl }}/img/projektek/almasderes/szelevprojekt/modok.jpg" class="img-responsive" alt="Matching">

## Körmérkőzéses bajnokság ##

A játékosok/csapatok eredményeit táblázatba rögzíthetjük. A gyakoribb eredmények külön gombok segítségével elérhetőek. A
rögzítendő mérkőzésben játszó csapatokat kétféleképpen is kiválaszthatjuk: legördülő listából, vagy a mérkőzés eredményére
kattintva.

<img src="{{ site.baseurl }}/img/projektek/almasderes/szelevprojekt/korm1.jpg" class="img-responsive" alt="Matching">

Az eredmények bevitele után/közben megtekinthető a verseny állása. A győzelemért, vereségért és döntetlenért kapható pontokat
menüben lehet állítani, az alapértelmezett beállítás 3, 0, 1.

<img src="{{ site.baseurl }}/img/projektek/almasderes/szelevprojekt/korm2.jpg" class="img-responsive" alt="Matching">

## Egyeneskieséses bajnokság ##

A mérkőzésekre a sorsolás véletlenszerű. Ha egy páratlansok játékost/csapatot kell összesorsolni, akkor közülük az egyiknek nem
 kell játszani, automatikusan továbbjut (jelen esetben Józsi).

<img src="{{ site.baseurl }}/img/projektek/almasderes/szelevprojekt/egy1.jpg" class="img-responsive" alt="Matching">

Miután az összes mérkőzés eredményét rögzítettük, a következő kör párosítását kisorsolhatjuk.

<img src="{{ site.baseurl }}/img/projektek/almasderes/szelevprojekt/egy2.jpg" class="img-responsive" alt="Matching">

A projekt GitHub-ról [letölthető][2].

[1]: https://developer.android.com/studio/index.html
[2]: https://github.com/techtabor/Bajnoksag
