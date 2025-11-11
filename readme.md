***Tanulj meg!***
===========
## justify-content

**Mit csinál:** A grid vagy flex container vízszintes tengelyen (inline axis) történő elhelyezését szabályozza, amikor a tartalom nem tölti ki a teljes elérhető helyet.

**Lehetséges értékek:** start, end, center, space-between, space-around, space-evenly.

## align-content


**Mit csinál:** A grid vagy flex container függőleges tengelyen (blokkszintű axis) történő elhelyezését szabályozza, amikor a több soros tartalom nem tölti ki a teljes magasságot.

## align-items


**Mit csinál:** A container minden egyes elemét függőlegesen igazítja az adott sorban, a sor magasságához képest.

## display: grid

**Mit csinál:** A konténert grid konténerré alakítja, amiben a gyerek elemeket sorok és oszlopok mentén lehet elhelyezni.

## grid-template-columns: repeat(auto-fit, minmax(200px, 1fr))

**Mit csinál:** Meghatározza a grid oszlopait:

**repeat(auto-fit, ...):** annyi oszlopot hoz létre, amennyi belefér a konténer szélességébe.

**minmax(200px, 1fr):** az oszlop minimum 200px, maximum a maradék helyet kitöltő rugalmas szélesség.

## grid-auto-flow: columns / rows

**Mit csinál:** Meghatározza, hogy a további (automatikus) grid elemek hogyan helyezkedjenek el:

row (alapértelmezett) → új elem a következő sorba kerül.

column → új elem a következő oszlopba kerül.

## grid-template-rows: 100px 1fr auto

**Mit csinál:** Meghatározza a grid sorok magasságát:

100px → az első sor fix 100px

1fr → a második sor rugalmasan kitölti a maradék helyet

auto → az utolsó sor magassága a tartalomhoz igazodik

## direction: rtl / ltr

**Mit csinál:** Meghatározza a szöveg és a tartalom írási irányát:

ltr → balról jobbra (alapértelmezett)

rtl → jobbról balra

## grid-template-areas: "h h"

**Mit csinál:** Nevet ad a grid területeknek, így vizuálisan egyszerűen el lehet helyezni az elemeket.

"h h" → a grid első sorában két oszlopot hoz létre, mindkettő az "h" területhez tartozik.

## grid-area: h

**Mit csinál:** Megmondja, hogy a gyerek elem melyik grid-template-areas területet foglalja el.

## order

**Mit csinál:** A flex vagy grid gyermekek vizuális sorrendjét állítja, anélkül, hogy megváltoztatná a HTML struktúrát.