# Webdesign
Web Design gaat over het ontwerpen en testen van Interactie. Het voordeel van een Frontend Developer (of Web Designer) is dat die techniek begrijpt, kan toepassen én verstand heeft van UX en design. Als je Web technieken begrijpt kun je je ideeën snel prototypen en testen met echte gebruikers, in een browser. Je kan dan aanpassingen doorvoeren, uitproberen en weer testen ...

In het vak Web design gaan we dingen ontwerpen voor echte mensen. Is er goede interactie? Kan je 'mens' je product op een prettige manier bedienen? Wat voor principes heb je gebruikt en getest? En zit er wel nonsense in?

# link
https://stijn-aa.github.io/web-design-1819/

### Eerste Interview en idee bedenken
Omdat Larissa blind is, vond ik het moeilijk om te bedenken hoe ik een visuele interface beter kan maken. In eerste instantie denk ik dat veel opgelost kan worden met een spraak assistent. Deze interface vind ik veel logischer voor iemand die niet kan zien. Maar ik denk ook dat het wel mogelijk moet zijn voor blinde mensen om het internet te gebruiken. 

Ik ga een weer site maken waar een blind persoon fijn door heen kan lopen. Het overzicht dat wij hebben als we de pagina zien heeft zij niet. Hierin zit voor mij de uitdaging. Hiërarchie en informatie uit een schema duidelijk laten voor lezen. Een andere aanname die ik nu heb is dat ze, omdat ze blind is, nooit snel even iets kan opzoeken. Dat wil ik ook oplossen.

## Pre test 1

Doel voor test 1 is om een set weer schema's te maken met verschillende invalshoeken. 

Tabel komende week: door verborgen woorden tussen de verschillende cellen te zetten wil ik dat de tabel wordt voorgelezen als een zin. Normaal is de context duidelijk door de visuele rijen en kolommen. De standaard vertelling van een tabel zegt bij elke cel ook het cel nummer, de context van waar de inhoud over gaat en dan de waarde. Dit is wat mij betreft een overlaad aan informatie die de heletijd herhaald wordt.

Tabel komende uren: omdat er niet altijd in elke cel waardevolle informatie staat heb ik gekeken naar het hiërarchisch belangrijker maken van de cellen met interessante informatie. Door deze cellen te vullen met een h2 kop kan hier snel naar toe gesprongen worden. Hierdoor is de belangrijke informatie snel voor handen.

### scenario
Larissa is een blinde jonge vrouw. Ze woont op Texel en werkt als toegankelijkheidsspecialist bij de hogeschool van Amsterdam. Ze is blind en heeft daarom een screenreader en heel soms een Baye regel om het web te navigeren. Naast werken voor de hva is ze ook olympisch sporter. 

Larissa is op het punt om weg te gaan naar de stad. Ze wil nog snel even weten of het komende uur gaat regenen.

Larissa is handig met haar apparatuur maar kan alsnog verdwalen door een slecht ontworpen site. Ze zal de screenreader gebruiken om een overzicht van de site te krijgen. Zoekend naar de juiste menu gaat ze langs alle onderdelen om de juiste link te openen.


### Test resultaat
Tijdens het testen heb de tactiek genomen om zonder iets over de opbouw te zeggen haar de site te laten ervaren. Dit heb ik gedaan zodat ik een beeld kreeg van hoe de site voor blinde mensen zou werken. Dit kwam alleen in conflict met mijn bouw strategie. Daarmee heb ik namelijk gekeken naar het opnieuw en anders gebruiken van de normale site attributen. Hierdoor raakte Larissa de weg kwijt. Nadat ik uitgelegd had wat ik had gedaan kon ze er een stuk beter doorheen maar had het voor mij minder test waarde omdat ik dan al had laten zien wat ik gemaakt had in plaats van hoe ze het ervaarde. Het resultaat van de test was dat de zinnen die met een p tag na elkaar kwamen niet automatisch door liepen. Hierdoor had ze het idee dat ze niet op de goede plek was uitgekomen of te snel door ging naar de volgende p. er kwam geen verhaal uit. Nog een hobbel was dat ik met een invul veld de inhoud laat aan passen maar niet meld dat dat gebeurd is door een doorverwijzing of geluidje. Hierdoor was ze in de war. Ook werkt een scroll to link niet met een screenreader en wanneer ze mijn site bezocht kon ze eigenlijk niet bij de tabel komen met de tab toets.

#### conclusie
Bij het luisteren naar tests van andere heb ik mijn concept herdacht en hoorde ik dat ze mobile sites beter vond werken. Hier ga ik mee door. Ik ga proberen het schema werkend te krijgen maar ga vooral ook door met een mobiele weer sit. Heir komen knoppen die het weer vertellen. 


## Pretest 2
Ik heb 1 iteratie gemaakt van de tabel. Ik vind het belangrijk dat deze dingen die ik onderzoek te implementeren zijn bij een normale site. Ik heb daarom opnieuw de tabel verbetert. Hierdoor zou de screenreader iets beter door de tabel heen moeten gaan. Ik heb na aanleiding van vorige week ook een nieuw conept gemaakt. Een interface zonder visuele infomatie maar met een stuk gesproken tekst. Als je op een van de knoppen drukt gaat de website automatisch het weerbericht voorlezen. Dit doe ik door een aria live tag en javascript. De inhoud kan hierdoor ook makkelijk realtime gemaakt worden. 

### Test restultaat
Deze test was een beter test. larissa wist wat de bedoeling was en daardoor kon ik goed opserveren zonder al te veel te sturen. Mijn verbeterde tabel werkte beter, maar nog niet helemaal zoals ik hem bedacht had. de test kapte hier en daar nog een paar keer af. Dit moest eigenlijk voorgelezen worden als een stuk. Het 2de onderdeel ging wel helemaal goed. Ik heb haar laten testen op de laptop en op mijn iphone. Ze kon de koppen goed vinden en de tekst werd voorgelezen zodra ze er op klikte. ook op de iphone waren er geen hobbels. Ook vond ze de weerteksten erg grappig. ik heb ze geschreven met het idee alsof een vriend of vriendin tegen je over het weer praat. Je verwacht een zakelijke melding maar inplaats daarvan praat de telefoon met gevoel over het weer.

### Eind conclusie

Presentatie: 7.5





