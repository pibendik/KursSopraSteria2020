

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

        ### Eksempel på rekkefølge:
        * `<h1> </h1>` - lag en overskrift
        * `<h3> </h3>` - lag en overskrift for en artikkel
        * `<article> </article>` - fyll inn innhold inne i artikkelen
        * `<section> </section>` - del inn artikkelen i seksjoner
        * `<aside> </aside>` - noe som ikke henger tematisk sammen med innholdet i resten av artikkelen
        * `<b> </b> <strong> </strong> <i> </i>` - slik kan du fremheve tekst
        * `<button> </button>` - lag en knapp, og putt tekst i knappen!

        * `<header> </header>` - Det går an å ha en separat del helt øverst på siden, og da putter man den i en header-tag.
        * `<footer> </footer>` - Fyll inn navn på forfatter, lenker til sosiale media osv., som typisk er å finne nederst på en side
        
        * `<img src="_____">` - legg ved et bilde, se https://www.w3schools.com/TAGs/tag_img.asp
        * `<a> </a>` - gjør noe om til en lenke ("anchor")
        * `<iframe>` - "embed," eller "bygg inn" en youtube-video eller en spotify-spiller, eller en hel annen nettside!
        * `<nav>` - ekstra oppgave! Navigering på siden gjøres med "nav"-tagger.

        ### andre tagger det er godt å vite om:
        * `<head> </head>` - definerer kompliserte ting for nørder (container for metadata)
        * `<body> </body>` - inneholder hele "skjelettet" til siden
        * `<div> </div>` - ALLTID BARE BRUK DENNE
        * `<span> </span>` - litt som \<div>, men typisk for bokstaver og ikke større greier, typisk midt i en setning.
            * Div og span har ikke styling (de er non-semantic, som \<b> og \<i>, vs semantic, som \<span> og \<div>)

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


