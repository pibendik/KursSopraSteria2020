## Tirsdag

### CSS: Klærne og ansiktet

1. Vise eksempler, hjemmesider med og uten css
    * http://www.tjelvar.se/
    * https://stripe.com/
    * https://www.creativebloq.com/news/pure-css-art

2. Vise eksempler!
    * ting som kan gjøres _inspect_ devtools:
        * Background-color
        * ...og så vise eksempelsiden vi lager i dev tools også!

3. legge til css-dokument til Fudge-siden, eller hvilken vi nå ender opp med å bruke

4. stil på tekst:
    * font/style, weight
    * fonter, fallback fonter (se under)
    * alignment
    * Skalering: em/rem vs px/pt/%

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
* Noen av oppgavene kan vi ha js som validerer om de har gitt riktig farge til ting.

    * Ulike måter å style på (_inline, separat fil_(source), \<style> (i samme fil) )
    * Husker dere selector-bruken for å highlighte alle correct-answer="true"?? Vi har flere slike selectorer, main er:
        * Class: ``.`` (punktum)
        * Lag en klasse, gjør mange elementer til del av den.
        * ID: ``#`` (skigard, pound, etc)
        * Gi noen elementer en unik ID.
    * **background-color** (fint for å vise grensene til objektene du lager)
    * **border** (rounded corners, dotted/dashed, etc...)
    * **margin, padding**
    * **position**: absolute, relative, fixed
    * **font**: med fallback font-valg
    * Gi en egen styling til alle \<a> (for eksempel).
    * Gjør teksten til alle \<h> (for eksempel) mye større.
    * Gjør alle (utfordring: besøkte) lenker turkise.
    * Gjør alle _first childs_ til \<div>-elementer til blå tekst

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


7. Selectors, Flexbox og css grid
    * http://flukeout.github.io/ (selectors)
    * https://flexboxfroggy.com/ (flex-box)
    * https://cssgridgarden.com/ (css-grid)
    * https://www.youtube.com/watch?v=uuOXPWCh-6o (CSS-grid)

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


<hr>

## Pensum CSS:
    Style HTML text properties
    Apply styles to text appearance; apply styles to text font, including WOFF, @font-face, size, and understudy fonts; apply styles to text alignment, spacing, and indentation; apply styles to text hyphenation; apply styles for a text drop shadow
    Style HTML box properties
    Apply styles to alter appearance attributes, including size, borders, rounded corners, outline, padding, and margin; apply styles to alter graphic effects, including transparency, opacity, background image, gradients, shadow, and clipping; apply styles to establish and change an element’s position
    Create a flexible content layout
    Implement a layout using a flexible box model; implement a multi-column layout; implement a layout using position floating and exclusions; implement a layout using grid alignment; implement a layout using regions, grouping, and nesting
    Create an animated and adaptive UI
    Animate objects by applying CSS transitions; apply 3-D and 2-D transformations; adjust UI based on media queries, including device adaptations for output formats, displays, and representations; hide or disable controls
    Find elements by using CSS selectors and JQuery
    Choose the correct selector to reference an element; define element, style, and attribute selectors; find elements by using pseudo-elements and pseudo-classes
    Structure a CSS file by using CSS selectors
    Reference elements correctly; implement inheritance; override inheritance by using !important; style an element based on pseudo-elements and pseudo-classes