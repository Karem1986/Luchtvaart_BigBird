
# Hoe zit de toekomst van het luchvaart sector?

In dit dashboard hebben we een aantal datasets gebruikt en geanalyseerd om de toekomst van de luchtvaartsector te kunnen voorspellen. Op basis van klanttevredenheid, winst, omzet, CO2-uitstoot gaan we er een duidelijker beeld van krijgen en om ervoor te zorgen dat dit ook leuk wordt, hebben we Big Bird uit het programma Sesame straat voor hulp gevraagd. Let op dat er alle data bronnen uit de Veregnigde Staten zijn, daarvan kunnen we niet een algemeen voorspeld hierdoor doen. 

![alt="Sesame Street Big Bird Cartoon](big_bird.png)

Big bird gaat ons vanaf nu precies vertellen wat er gebeurt op het gebied van de datasets en de visualisaties die op dit project gebruikt zijn. Volg hem dus op de voet!

# Installatie-instructies:

Om het dashboard te implementeren, hier wat gedetailleerde instructies:

- Zorg dat je op je computer, Power Bi geinstallerd hebt
- Vanit Github: cloneert het repository binnen een map op jouw computer
- Vanuit Git Nexed: Download het .pbix bestaand en ook de datasets, zie datasets 1, 2, 3 en 4 verder op
- Laad deze in Power BI: begint met de datasets en vervolgens de .pbix bestaand
- Zorg dat er de juiste path toegegeven is

# Gegevensbronnen en Datasets:

Een lijst van alle gegevensbronnen en datasets die worden gebruikt in het dashboard.

- Dataset 1: [Airline Expenses](https://www.kaggle.com/datasets/xan3011/airline-data-project-mit-1995-2019?select=airline_expenses.csv)
- Dataset 2: [Airline Passengers](https://www.kaggle.com/datasets/xan3011/airline-data-project-mit-1995-2019?select=airline_passengers.csv)
- Dataset 3: [Passengers Satisfaction](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction/)
- Dataset 4: [Airline Revenue](https://www.kaggle.com/datasets/xan3011/airline-data-project-mit-1995-2019?select=airline_revenues.csv)

# Navigatiegids:

Instructies over hoe je door het dashboard kunt navigeren, inclusief het selecteren van filters, slicers en interactieve elementen.

Er zijn drie dashboards: 
- Revenue (Bookmarks)
- Passenger Satisfaction-Key Influencers
- Satisfaction Demographics (using Dax)

# Dashboardfuncties:

Een overzicht van de belangrijkste functies en interactieve elementen in het dashboard, met inbegrip van grafieken, tabellen, filters, enz.

## Eerste Dashboard: Revenue (Bookmarks)

Je begint met het 'Revenue' Dashboard waarin er twee bookmarks zijn. De eerste bookmark 'Grow years' helpt met het visualiseren van het grooien door de jaren 1995-2005-2018. We zien een grote stijging in revenue vanaf 2005.
De tweede bookmark 'See all data' helpt met het visualiseren van alle data voor elke jaar wandt dat is ook nuttig voor stakeholders. 
Daanast, heb je ook de mogelijkheid om 'Revenue per airline'te kunnen zien in de donutgrafiek. Als je een datapoint selecteert, bijvoorveld 'American' gaat je zien de portie % revenue voor dit specifiek airline. 
Eindelijk, komen we tot een aantal conclusies via de 'Narrative smart' voor Revenue waarin een korte uitleg is geschreven en een suggestie voor mogelijkheid onderzoek. 

## Tweede Dashboard: Passenger Satisfaction-Key Influencers

In deze dashboard maken we gebruik van de 'Key influencers' visual in Power BI.

Het doel van de key influencers visual is dat je kunt zien de belangrikste factoren die een invloed hebben op 'passenger satisfaction' maar ook de 'Top segments' die erbij horen. Op deze manier kunt je wat dieper in te gaan en meer nuttige inzichten hebben voor dat je stakeholders gaat adviseren of ze zelfs verkeerde conlclusies gaan trekken. 

Op de linkert kant, ziet je het filter 'Type of Travel'. Deze filter helpt met het filteren van 'Key influencers' gebaseerd op welke type travel de passenger hebt gemaakt. Bijvoorbeld stel voor dat we denken dat passengers die voor personal redenen hebben gevlucht meer tevreden zijn dat passengers die voor businnes hebben gereisd, dan komen we hier op dit hyphotesis te kunnen testen. Als een vogel, weet ik dat passengers kunnen moelijk zijn om ze tevreden te maken want ik zie alles van boven en soms voor de lol vlieg ik naast vliegtuigen! Maar op dit dashboard, geen aannamen maar wel feiten!

## Derde Dashboard: Satisfaction Demographics (using DAX)

Hierin hebben we goed 'DAX' custom measures gebruikt. 

Het reder hiervoor is dat we wilden weten het precies percentage van satisfaction van passengers aanhankelijk van 'Class': Business, Eco and Eco Plus. 

We hebben er ook een 'custom column' toegevoegd om te kunnen satisfaction analyseren of afscheiden per leeftijgroep. 

Passengers die Female zijn, Loyal Customer, tussen 30-49 jaar oud  en 'Travel type' is Business, zijn tevreden bij 52.06 %,  als het gaat om de 'Eco Plus' Class. dezelfde geldt voor males.
De Eco Plus class heeft het meest tevreden klanten in vergelijking met de 'Business Class' die een heel erg laag tevredenheid percentage van 24 % heeft. Wat meer interessant lijkt is dat dit feit geldt ook voor andere leeftijdgroepen net zoals < 30 jaar oud, Type travel is personal en Customer type is Loyal of Disloyal. 


# Demonstratie:

Eventueel een korte stapsgewijze demonstratie van hoe je een specifieke taak uitvoert of inzichten uit het dashboard haalt.

Hierbij een korte video introductie om je te laat zien hoe kan je door een dashboard navigeren om inzichten te halen door gebruik van bookmarks:

[Demonstratie Revenue Dashboard-inzichten halen uit Bookmarks](https://youtu.be/gWAClQ5AHu4)
