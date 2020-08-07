

- skru av og på CSS og JS for en hjemmeside, se hva som skjer.
Bruk Web Developer
  https://www.vg.no/nyheter/innenriks/i/wPaWkM/sjeldent-syn-her-hopper-ubaatmannskapet-i-vannet - for eksempel
- Vise quiz fusk: [link](https://www.nrk.no/kultur/quiz_-noreg-rundt-med-forfattarar-1.15008193)
* [data-correctoption=true]  ny css regel
* document
* querySelectorAll()
* ("[data-correctoption=true]")
* forEach(button => button.click())
* document.querySelectorAll("[data-correctoption=true]").forEach(button => button.click())

* Dette er en god plass å fortelle at front-end og back-end har et tydelig skille, nemlig at i dette tilfellet er 100% _client side_.

Detaljert rekkefølge:



1. Oppsett VSCode
    * Vi får en test-kanin til å skrive extensions.json-fila live forran tavla, pushe til master, og så får alle andre pulle og åpne prosjektet i vs-code og installere extensionene automatisk.
    * De skal vel alle sammen ha live server (ligger i .vscode/extensions)
    * vise extensions.json - hvilke extensions trengs.

5. OPPGAVER:
    * Oppgave 1: De skal lage en side med alle disse tingene I:

        * https://www.w3schools.com/TAGs/ - info om alle taggene!
        * https://lipsum.com/ - her finner dere brødtekst til å fylle på hjemmesidene deres

        ### pause
       
    * Oppgave 2: De skal fylle i riktig i vår, som vi har laget.
    Vi kan vise bilde av hvordan vi vil at resultatet skal bli.
    Vi kan avslutte dagen ved å vise hvordan de un-doer alle endringene vi gjorde, ved å se på git-historikken.

    * Oppgave 3: Finne eksempel-side på internett og lime inn i prosjektet.


Ekstraoppgaver/ting å se på:
* Htmlcheatsheet
* Git cheat sheet
* w33schools
* “husk å legge til alle ressursene vi plukker fram I bokmerke-mappe for kurset”
    * http://www.tjelvar.se/
    * https://stripe.com/
    * https://no.wikipedia.org/wiki/JavaScript
    * w33schools for å finne eksempler også, og stjele
    * https://gitexplorer.com/


## CSS - Eventuelt, hvis tid:

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