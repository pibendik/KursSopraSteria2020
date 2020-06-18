## Onsdag

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