## Tirsdag

### CSS: Klærne og ansiktet

1. Vise eksempler, hjemmesider med og uten css
    * http://www.tjelvar.se/
    * https://www.vg.no/
    * https://no.wikipedia.org/wiki/JavaScript
    * https://www.creativebloq.com/news/pure-css-art


2. Vise eksempler!
    * ting som kan gjøres både i _inspect_ devtools:
        * Background-color
        * font/style, weight
        * Scalering: Em/rem vs px/pt %
        * og så vise eksempelsiden vi lager i dev tools også!

4. stil på tekst:
    * tekst
    * fonter, fallback fonter
    * spacing
    * alignment

```css
.serif {
    font-family: "Times New Roman", Times, serif;
}

.sansserif {
    font-family: Arial, Helvetica, sans-serif;
}

.monospace {
    font-family: "Lucida Console", Courier, monospace;
}
```


3. Introdusere CSS - properties
    * Ulike måter å style på (_inline, separat fil_(source), \<style> (i samme fil) )
    * CLASS!!!! og ID!!  (vise i vs-code, ``#`` vs ``.``)
    * **background-color** (fint for å vise grensene til objektene du lager)
    * **border** (rounded corners, dotted/dashed, etc...)
    * **margin, padding**
    * **position**: absolute, relative, fixed
    * **font**: med fallback font-valg

4. (Disse viser vi shorthand på under veis)
    * background
    * border
    * padding
    * margin
    * font


5. Pseudo class
    * https://www.youtube.com/watch?v=e1KpKBHJOrA
    * https://www.youtube.com/watch?v=kpXKwDGtjGE
    * ``:hover``
    * ``<a\> :link, :active, :visited``
    * ``:first-child :last-child :nth-child``
    * ``:only-child``
    * ``:checked``
    * ``:focus``

6. Display
    * ``none`` vs ``hidden``
    * ``block``
    * ``inline``
    * ``inline-block``
    * ``inline-flex``


7. Flexbox og css grid
    * https://flexboxfroggy.com/
    * https://cssgridgarden.com/
    * https://www.youtube.com/watch?v=uuOXPWCh-6o (evt. som ekstra oppg.)


8. Tilpasse skjerm
    * @media
    * skalere tekst
    * flex-box (row --> column))
    * bredde på bokser, skal kanskje ikke ha død-plass i sidene, når du går til mobil, for eksempel (500px --> 100%)
    * https://www.youtube.com/watch?v=biOMz4puGt8 (evt. som ekstra oppg.)

9. Vise og skjule elementer
    * (none/hidden)

## Oppgaver:
1.  Legge på css på _krig_-siden (som ikke har css)
    * Velg en font-familie med fallback
    * Spesifiser font-størrelse og farge i alle`` <h1>``, `<article>`, `<a>` osv.
    * skrive css for visning/ dimensjoner av bilder (og noe svg?)
2. Position: ``absolute`` vs ``fixed`` vs `relative`
3. Spille flex-box froggy
4. Spille css grid-garden

## Eventuelt, hvis tid:

1. Bra vs. dårlig implementering av parallakse
    * Hvis man gjør dette i javascript, blir det tregt, laggete, og ubehagelig
    * Hvis man gjør det i ren css, så kan det bli smooooth #snoopdogg
1. Inherit, set,
1. Animere css: https://www.youtube.com/watch?v=HZHHBwzmJLk
1. Legge til "cards" der hvor det var bilder av svenske krigs-piloter:
    * https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_cards
