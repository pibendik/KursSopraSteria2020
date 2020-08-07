

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








### Javascript: Muskler og sener

*Bruke et eller anna javascript shell for å vise*

## Rask intro til Javascript
0. først ser vi denne: https://www.youtube.com/watch?v=9emXNzqCKyg
1. la dem følge med på repl.it mens vi forklarer alle konseptene en om gangen. Da prøver vi gjerne å ta det i et forholdvis rolig tempo, slik at de rekker å leke litt og prøve seg fram underveis.
    * `let` vs `const`, `var` (fyfy)
    * Primitives (immutable):  `number`, `boolean`, `String`
    * Types:
        * Functions
            * Standard function declaration
            * Anonymous function
            * Arrow function ` =>`
        * Objects
            * Enums?
            * Dict?
            * Javascript objects
            ```
            let dog = {
                ears : 2,
                age : 12,
                bark : function(){console.log("wof!") },
                barkLoud : () => console.log("wof!"),
                function barkLouder : console.log("WOFF!!!"),
            }
            ```

        * Arrays ( `new Array(0)`,`[]`,`[0]`,`split()`,`splice()`,`push()`,`pop()`,`shift()` osv.)
        * Operators
            * `<`, `<=`,    `!=`
            * ``*``, ``++``, ``&&``
            * Fancy: return falsy || 3; !!variable;
            * Control expression:
                * `if`
                * `if-then-else` shorthand
                * `switch`
        * For loops:
            * `continue`, `break`
            * `for i` vs `for each` vs `for in`
        * Higher order functions: forEach map filter reduce ...

2. DOM API
    * Manipulere DOM `GetElementByID()`, `InnerHTML()` Canvas api
    * DOM Document Object
        * Lage og slette elementer :
            * createElement
            * removeChild
            * appendChild
            * (replaceChild, write)
        * (Finding HTML Objects, document.anchors, . scripts, embeds, etc...)
    * Finding HTML Elements:
        * 
    * Event handlers: onclick, onblur, onfocus
        
3. Consume **JSON** and XML data; retrieve data by using **web services**. load data or get data from other sources by using XMLHTTPRequest
    * JSON.parse / JSON.stringify
    ```
    { 
        Odd : "snill",
        Bendik : "også snill"
    }
    ```
    * XMLHttpRequest eksempel --> Fetch
    * Promises, async await
    * ``sync`` vs ``async``

8. Vise eksempler på DOM-manipulasjon
    * 

# oppgaver
1. evaluer uttrykk som `(asdf == 2)`
1. velg utfall av programm-flyt med `switch` statements, `if/then`, og operatorer.
1. Iterere over `collections` og `array` (og json?).
    * For eksempel: _console.log() alle elementene i en array som inneholder alle landene du har vært i_
    * Eller: _vi har gitt dere en array, print ut summen av alle elementene_ osv...
1. lag inputfelt (DOM manipulering, regex, validering if)
    * legg på validering
    * legg på sjekk at det er riktig type data
    * regex-sjekk at det er rett format
    * if("Hello There") return "General Kenobi"
1. Handle common events exposed by DOM
    * `OnBlur()`, `OnFocus()`, `OnClick()` declare and handle bubbled events https://www.w3schools.com/jsref/event_onblur.asp
    * handle an event by using an anonymous function.


1. lag en paragraf som påvirkes av inputen
    * vis teksten i input-feltet hele tiden
    * vis når du trykker enter
    * vis noe spesielt når teksten matcher noe, for eksempel, teksten er rød mens den ikke matcher regex for for eksempel riktig format av telefonnummer

1. Implement exception handling
    * Set and respond to error codes; throw an exception; request for null checks; implement try-catch-finally blocks

# Fra pensum om javascript:

Implement asynchronous programming
Receive messages from the HTML5 WebSocket API;

use JQuery to make an AJAX call; wire up an event; implement a callback by using anonymous functions;

handle the “this” pointer  **vise this-dot sangen?** https://www.youtube.com/watch?v=M5d7vygUPoQ

Create a web worker process
Start and stop a web worker; pass data to a web worker; configure timeouts and intervals on the web worker; register an event listener for the web worker; limitations of a web worker

Validate user input by using JavaScript
Evaluate a regular expression to validate the input format; validate that you are getting the right kind of data type by using built-in functions; prevent code injection
Consume data

Serialize, deserialize, and transmit data
Handle binary data; handle text data such as JSON and XML; implement the JQuery serialize method; use Form.Submit; parse data; send data by using XMLHTTPRequest; sanitize input by using URI/form encoding




# Fredag

* Intro til Typescript
* https://www.destroyallsoftware.com/talks/wat