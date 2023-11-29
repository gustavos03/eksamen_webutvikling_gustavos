# eksamen_webutvikling_gustavos
Jeg har valgt å gå for ambisjons nivå D, da jeg så at C ble for vanskelig for meg å nå. 

Kilder jeg har brukt:
https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-examples

https://css-tricks.com/snippets/css/complete-guide-grid/

https://fontawesome.com/icons/arrow-up?f=classic&s=solid&sz=xl

https://www.w3schools.com/howto/tryit.asp?filename=tryhow_js_scroll_to_top
 
Jeg har brukt Github Copilot får å skrive repeterende kode, da det tar tid å skrive de samme artikkelkortene om og om igjen. 

Chat gpt har også blitt brukt for å hjelpe meg å feilsøke hvorfor en kode ikke har fungert. Det har hjulpet meg delvis men på mange områder ikke. 

You:
jeg vil at denne teksten skal være på høyresiden av netttsiden
ChatGPT:
For å plassere teksten på høyresiden av nettstedet, kan du bruke CSS-reglene for justering av tekst og layout. Her er et eksempel:

css
Copy code
.branding {
    display: flex;
    flex-wrap: wrap;
    flex-direction: row-reverse; /* Endre rekkefølgen på elementene til høyre-venstre */
    gap: 10px;
    justify-content: space-between;
    margin: auto;
    text-align: left;
    padding: 10px;
}
Ved å endre flex-direction til row-reverse, endrer du rekkefølgen på elementene i flex-containeren til høyre-venstre. Dette vil plassere teksten på høyresiden av nettstedet. Juster gjerne gap og padding-verdier i henhold til dine preferanser.

I Dette tilfellet fungerte dette ikke pga annet eksisterende kode som jeg ikke fikk løst. Dette gjaldt about siden. Som er en av sidene jeg slet med. 

Bilder er det som ble gitt av foreleser i form av zip mappe, som jeg hadde da lagt inn som ressurs mappen. Der ligger alle bildene jeg har brukt og resten er placeholder bilder. 

Alle ikoner har blitt tatt fra fontawesome. 
inkludert pilen som sender deg til toppen av siden som er linket til.
Ikonene nederst på hver side er hjulpet med github copilot, og endret på slik det passer inn på siden. Som Facebook, Instagram og linkedin.
