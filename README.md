# aanbod-meester

Een Claude-skill die een standaard-aanbod sterker maakt. Voor coaches, dienstverleners en webshops met een aanbod dat klinkt als dat van iedereen.

Je plakt je aanbod. De skill leest het als een klant, zoekt de 4 fouten waarop klanten afhaken, zegt welke vragen klanten stilletjes hebben, en schrijft hetzelfde aanbod opnieuw op. Zelfde dienst, zelfde prijs.

## Voorbeeld
Een echt aanbod van een coach (vertaald):

> 1-op-1 coaching. 6 sessies van een uur via Zoom, binnen 3 maanden (flexibel). Voor professionals die zoeken naar helderheid, zelfvertrouwen en praktische vooruitgang. Kies uit 2 betaalplannen.

Wat de skill vond:
- **Vaag resultaat:** "helderheid en zelfvertrouwen" kan de klant niet zien of tellen.
- **Geen tijdslijn:** "3 maanden, flexibel", maar niet wat je na week 1 hebt.
- **Geen risico weg:** geen garantie, geen proefgesprek.
- **Te veel keuze:** 2 betaalplannen, "vanaf" en "flexibel". Dus schuift de klant het op.

Wat de skill ervan maakte:

> Sta je voor een carrièrestap en kom je er niet uit? In 6 gesprekken van een uur maken we samen een besluit en een plan dat je zelf kunt uitvoeren. Na het eerste gesprek heb je je doel in één zin en je eerste actie. Klikt het na dat gesprek niet, dan stop je en betaal je de volgende termijnen niet.

## Installeren
1. Open Claude Code.
2. Plak de link van deze repo en zeg: `Maak hier de skill aanbod-meester van.` Of zet de map `aanbod-meester` zelf in `~/.claude/skills/`.
3. Typ `/aanbod-meester` en plak je aanbod.

## Wat erin zit
- **Lees als klant:** wat denkt een klant nu dat hij krijgt?
- **De 4 fouten:** vaag resultaat, geen tijdslijn, geen risico weg, te veel keuze.
- **Klantvragen:** "Wat heb ik er na afloop aan?", "Werkt dit ook bij mij?", "Wat als het niks oplevert?", en wat je daarop verandert.
- **Opnieuw geschreven:** oud en nieuw naast elkaar, plus het nieuwe aanbod klaar om te plakken.
- **Regels:** gewone taal, niets verzinnen, geen nepschaarste.

## Waar het op leunt
Openbare bronnen: $100M Offers (Alex Hormozi), The Mom Test (Rob Fitzpatrick), The Paradox of Choice (Barry Schwartz) en Influence (Robert Cialdini). Plus onze eigen regels: gewone taal, bewijs boven belofte, geen verzonnen cijfers. Geschreven door JWRN, in het Nederlands.
