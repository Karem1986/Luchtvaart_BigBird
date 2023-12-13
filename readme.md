# Hoe zit de financiele landschap en klanttevredenheid van het luchtvaart sector?

In dit dashboard hebben we een aantal datasets gebruikt en geanalyseerd om verschillende factoren van het luchtvaartsector te kunnen analyseren. Op basis van klanttevredenheid, winst en zovoort gaan we er een duidelijker beeld van krijgen. 

Let op dat er alle data bronnen uit de Veregnigde Staten zijn, daarmee kunnen we niet een algemene voorspelling doen. 

Om ervoor te zorgen dat dit ook leuk is, hebben we Big Bird, uit het programma Sesame straat,  voor hulp gevraagd. 

![alt="Sesame Street Big Bird Cartoon](big_bird.png)

Big bird gaat ons vanaf nu precies vertellen wat er gebeurt op het gebied van de datasets en visualisaties die voor dit project worden gebruikt. Volg hem dus op de voet!

# Installatie-instructies:

Om het dashboard te implementeren, heb je hier gedetailleerde instructies:

- Zorg dat je op je computer Power Bi hebt geïnstalleerd
- Vanit Github: kloon de repository binnen een map op je computer
- Van Git Nexed: Download de .pbix bestaande en ook de datasets, zie datasets 1, 2, 3 en 4 verderop
- Laad deze in Power BI: begin met de datasets en dan de .pbix existing
- Zorg ervoor dat het juiste pad is opgegeven

# Gegevensbronnen en datasets:

Een lijst van alle gegevensbronnen en datasets die in het dashboard worden gebruikt.

- Dataset 1: [Vliegtuiguitgaven](https://www.kaggle.com/datasets/xan3011/airline-data-project-mit-1995-2019?select=airline_expenses.csv)
- Dataset 2: [Vliegtuigpassagiers](https://www.kaggle.com/datasets/xan3011/airline-data-project-mit-1995-2019?select=airline_passengers.csv)
- Dataset 3: [Tevredenheid passagiers](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction/)
- Dataset 4: [Inkomsten luchtvaartmaatschappij](https://www.kaggle.com/datasets/xan3011/airline-data-project-mit-1995-2019?select=airline_revenues.csv)

# Navigatiegids:

Instructies om door het dashboard te navigeren, inclusief het selecteren van filters, slicers en interactieve elementen.

Er zijn drie dashboards: 
- Inkomsten (bladwijzers)
- Tevredenheid passagiers
- Tevredenheidsdemografie (met Dax).

# Dashboardfuncties:

Een overzicht van de belangrijkste dashboardfuncties en interactieve elementen, waaronder grafieken, tabellen, filters, enz.

## Eerste dashboard: Inkomsten (Bladwijzers).

Je begint met het Dashboard 'Inkomsten' waarin twee bladwijzers staan. De eerste bladwijzer 'Jaren groeien' helpt bij het visualiseren van de groei door de jaren 1995-2005-2018. We zien een grote toename in inkomsten vanaf 2005.
De tweede bladwijzer 'Alle gegevens bekijken' helpt bij het visualiseren van alle gegevens voor elk gewenst jaar, wat ook handig is voor belanghebbenden. 

Daarnaast heb je ook de mogelijkheid om 'Inkomsten per luchtvaartmaatschappij' in de donutgrafiek te zien. Als je een gegevenspunt selecteert, bijvoorbeeld 'American', zie je het deel % inkomsten voor deze specifieke luchtvaartmaatschappij. 

Tot slot komen we tot enkele conclusies via de 'Narrative smart' voor Revenue waarin een korte uitleg staat en een suggestie voor mogelijk onderzoek. 

## Tweede dashboard: Tevredenheid van passagiers - Belangrijkste beïnvloeders

In dit dashboard gebruiken we de visual 'Key influencers' in Power BI.

Het doel van de Key Influcers visual is dat je de belangrijkste factoren kunt zien die invloed hebben op de tevredenheid van passagiers, maar ook de 'Top segmenten' die daarbij horen. Op deze manier kun je dieper gaan en meer bruikbare inzichten krijgen voordat je belanghebbenden adviseert of zelfs verkeerde conclusies trekt. 

Aan de linkerkant zie je de filter 'Reistype'. Deze filter helpt om de 'Belangrijkste beïnvloeders' te filteren op basis van het soort reis dat de passagier heeft gemaakt. 


Stel bijvoorbeeld dat passagiers die om persoonlijke redenen reisden tevredener zijn dan passagiers die voor zaken reisden, dan komen we hier om deze hyphoteïs te kunnen testen. Als vogel weet ik dat het moeilijk kan zijn om passagiers tevreden te stellen, omdat ik alles van bovenaf zie en soms voor de lol naast vliegtuigen vlieg! Maar op dit dashboard geen veronderstellingen maar feiten! :laughing:


## Derde dashboard: Tevredenheidsdemografie (met DAX)


Hierin hebben we goed 'DAX' aangepaste metingen gebruikt. 


De reden hiervoor is dat we het exacte percentage van tevredenheid van passagiers afhankelijk van de 'Klasse' wilden weten: Business, Eco en Eco Plus. 


We hebben ook een 'aangepaste kolom' toegevoegd om de tevredenheid per leeftijdsgroep te analyseren of te segmenteren. 


Passagiers die vrouwelijk zijn, een trouwe klant zijn, tussen de 30-49 jaar oud zijn en 'Reistype' Business is, zijn met 52,06% tevreden als het gaat om de 'Eco Plus'-klasse. hetzelfde geldt voor mannen.


De Eco Plus-klasse heeft de meest tevreden klanten in vergelijking met de 'Business Class' die een zeer laag tevredenheidspercentage van 24 % heeft. Wat interessanter is, is dat dit ook geldt voor andere leeftijdsgroepen, zoals jonger dan 30 jaar, het type reis is persoonlijk en het type klant is loyaal of niet loyaal.


# Demonstratie

Eventueel een korte stapsgewijze demonstratie van hoe je een specifieke taak uitvoert of inzichten uit het dashboard haalt.

Hierbij een korte video introductie om je te laat zien hoe kan je door een dashboard navigeren om inzichten te halen door gebruik van bookmarks:

[Demonstratie Revenue Dashboard-inzichten halen uit Bookmarks](https://youtu.be/gWAClQ5AHu4)
