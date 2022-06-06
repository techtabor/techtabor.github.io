# Techtábor weblap

Copyright A Gondolkodás Öröme Alapítvány All rights reserved.

Linkek:

1. [Weblap](https://techtabor.github.io/)
1. [A projekt leírása](https://docs.google.com/document/d/1wEQbOkPK2Q9OjjDVYJZye2mSDG0rDqPA2ZywXxd887Y/edit#)
1. [fejlesztési tervek](https://docs.google.com/spreadsheets/d/126HncEzTPGTDOcDf5XMPYJDlPySwhHqp8Qm6wMip0Cg/edit#gid=0)

## Használat

Nézd meg a [jekyll útmutatót](https://jekyllrb.com/docs/usage/).

* install jekyll (Windows: https://labs.sverrirs.com/jekyll/1-ruby-and-devkit.html)
* `gem install jekyll-paginate`
* `gem install jekyll-feed`

A legegyszerűbb, ha clone-ozod a repositoryt, majd futtatod a `jekyll serve` parancsot. Ekkor a weblap elérhető lesz a [http://localhost:4000/](http://localhost:4000/) címen.

Ha a master branch-re pusholsz, automatikusan frissül a honlap.

## Leírás hozzáadása új projektről

- A `_posts` mappában hozz létre egy fájlt a meglévő projektleírások mintájára. A fájl neve kezdődjön a dátummal.
- Ha a leírás yaml headerjében a tagek között szerepel a featured, akkor a főoldalon is meg fog jelenni a projekt, egyéb esetben az összes projekt listáján fog megjelenni.
- Hivatkozz az `img/projektek/{csoportnev}` mappába feltöltött képekre. Egy header-img kötelező, a többi kép opcionális.
- A `header-img` képaránya legyen 2:1

Küldj pull requestet, vagy küldd el a fájlokat a szervezőknek.
