MAPY - kontenery na zmienne
$colors: (
    top: gold,
    center: lime,
    bottom: tomato
) - tworzenie mapy SCSS
$colors: (top: gold, center: lime, bottom: tomato) - tworzenie mapy w SASS
background-color: map-get($colors, top) - odwołanie do zmiennej w mapie

MIXIN - tworzymy na samej górze
@mixin nazwa_mixina
    właściwości - tworzenie mixina
@include nazwa_mixina - odwołanie do mixina

Sposób mixina ze zmienną
@mixin color($bgColor)
    background-color: $bgColor - stworzenie
.klasa
    @include color(lime) - odowałanie

IMPORT - importowanie plików sass
@import nazwa_pliku