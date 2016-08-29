# Öppna frågor kring eIDAS och Svensk e-legitimation

## Allmänna frågor

### Terminologi

* Om jag i tekniskt ramverk pratar om att en användare autentiseras av en IdP i medlemsstaten så stämmer ju inte det egentligen. Det kan ju vara vilken teknik som helst. Det enda vi vet är ju att MS eIDAS-nod förser oss med attribut. Lite osäker på hur vi ska angripa detta. Vi skulle behöva "sätta" några formuleringar och definitioner som kan användas i tekniskt ramverk.

## Väntrum

### Centraliserat väntrum eller varje myndighets ansvar?

Ponera att en myndighet accepterar eIDAS-inloggningar, men att myndigheten redan från början vet att den endast kan betjäna individer som kan presentera ett personnummer, eller samordningsnummer, i samband med inloggningen. Ska vi då tillåta att inget intyg levereras till myndigheten i de fall då inget personnummer/samordningsnummer kan inkluderas i intyget? I dessa fall skulle användaren hamna i ett väntrum (egentligen felsida) hos den svenska eIDAS-connectorn.
* Enkel anslutning för myndigheter som endast kan hantera personnummer/samordningsnummer.
* Är det verkligen OK? Bryter denna myndighet mot förordningen?
* Det kan ju vara så att endast myndigheten ”vet” vilken information som användaren behöver ges för att ”komma vidare”.

## Attributhantering

### Filtrera bort eIDAS-attribut?

I princip räcker det med ProvisionalId (+ quality), samt namn och födelsedatum, och ev. personnummer/samordningsnummer, för en myndighet. Hur ställer vi oss att skicka med alla eIDAS-attribut också? Måste vi det? Kan en myndighet välja att bara få ”minimum set”, eller måste vi skicka på dem allt?

### Bara vidarebefordra eIDAS-attributen?

Och alltså inte berika intyg med ProvisionalID (och personnummer). Är detta ett relevant use-case?


### Ska vi införa ett attribut för notified/non-notified?

Denna information får vi inte från eIDAS, men vi kanske kan upprätthålla ett register som håller denna information.

Måste tas upp med expertgruppen igen.

