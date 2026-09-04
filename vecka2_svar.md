# Systemutveckling Vecka 2
## Fråga 1: 
### Skillnaden
Vattenfallsmodellen innebär att man planerar allt från början och gör klart ett steg innan man går vidare till nästa, t.ex planera, designa, koda och testa. Det är svårt att ändra något sent i projektet, ungefär som att flytta köket när ett hus nästan är färdigbyggt.

Agil metodik innebär i stället att man arbetar med små delar i taget, till exempel först inloggning och sedan inlägg och kommentarer. Man testar efter hand och kan enklare ändra eller förbättra saker under projektets gång.

### När passar de?
Vattenfallsmodellen passar bäst när man redan från början vet vad systemet ska göra och kraven inte förväntas ändras. Då kan man planera projektet tydligt och beräkna tid, kostnad och vilka delar som behöver byggas.

Agil metodik passar bäst när man inte vet allt från början eller när kraven kan ändras under projektet. Då är det bäst att arbeta i små delar, eftersom man kan testa, få feedback och förbättra/ändra systemet under vägens gång.

## Fråga 2:
### Vad är en git-commit?:
En git-commit är en sparad version av projektet vid ett specifikt tillfälle.
### Varför är det viktigt?:
Det är viktigt för att om något går fel så kan man alltid gå tillbaka och kolla tidigare versioner och se vad som gått fel eller börja om på den versionen som fungerade sist.
### Exempel:
Du har en sida där du har gjort färdigt inloggnings funktionen, du gör sedan ändringar för att lägga till en registreringsfunktion men sen slutar inloggningsfunktionen fungera av okänd anledning. Då kan du alltid gå tillbaka till versionen där inloggningen fungera om du gjorde en commit.

## Fråga 3:
### Sammarbete med Gitub:
Det innebär att projektets kod finns sparat som ett repositry på Gitub, alla som är med i projektet kan se och göra ändringnar samt se historik och vem som har gjort vad och när.
### Branch:
En branch är en extern arbetsgren. Man kan jobba i en branch och göra ändringar utan att påverka main. Det är fördelaktikt för då har man alltid en fungerande kod i main som inte på verkas av en branch, flera kan sitta och jobba samtidigt på projektet i olika branches som sen mergas med main.
### Pull request:
Det är en förfrågan som skickas om att få lägga in dina ändringar i main ifrån din egen branch där du skrivit kod. Brukar oftast vara en senior som kollar på din kod så att den är godkänd innan den mergas.
### Merge:
Det betyder att man slår ihop en branch med main, alltså att ändringarna man gjort i branch läggs till i main.