# Grip op data in Drechtsteden!

In Drechtsteden wordt continu gewerkt aan het realiseren van maatschappelijk toegevoegde waarde door het verbeteren van dienstverlening. De maatschappij van vandaag vraagt veel van de organisatie, mede door technologische ontwikkelingen. Het werken met én het gebruiken van data, speelt hier bij een essentiële rol. 

## Datamanagement

Aan de basis van de digitale transformatie ligt het managen van data. Kwalitatieve data verzamelen is belangrijk, maar door het gebruik ervan creëer je pas echt waarde. Drechtsteden werkt met een regionale aanpak, hiervoor hebben we kaders en richtlijnen opgesteld. Er zijn processen ingericht, een centraal integratie-team samengesteld en een integratievoorziening opgezet. Hierdoor kunnen we data gecontroleerd laten stromen. Het onderstaande dashboard geeft de huidige status van de aansluitingen weer. 

![alt text](https://github.com/Drechtsteden/CentraleDistributieVoorziening/blob/master/Dashboard%20CDV%20aansluitingen%20-%20jan%202020.jpg "Dashboard januari 2020")

De landelijke beweging ‘Common Ground’ benadrukt het belang van datamanagement. Transparantie, flexibiliteit en duurzaamheid speelt hierbij een belangrijke rol. Of het nu gaat om delen van data rondom de omgevingswet, de energietransitie of ondermijning.  De integrale aanpak van Drechtsteden sluit hier perfect op aan.

Drechtsteden heeft een [animatiefilm](https://www.youtube.com/watch?v=kednu5b_8ew) gemaakt waarin de integrale aanpak op het gebied van data wordt gevisualiseerd. 

## Integratievoorziening 
De integratievoorziening wordt in Drechtsteden aangeduid als Centrale Distributie Voorziening (CDV). De CDV bevindt zich in de integratielaag als we het plotten op de architectuurlagen die ook voor Common Ground gehanteerd worden (zie onderstaande visualisatie). De CDV biedt momenteel tooling op het gebied van:
-	Gemeentelijke servicebus
-	ETL
-	Digikoppeling adapter

Hieraan worden binnen afzienbare tijd toegevoegd:
-	Lokale API Gateway (als onderdeel van de tooling aangeduid met het container begrip 'API-Management tooling')
-	[NLX](https://https://nlx.io/) (indien succesvol en implementeerbaar) 

## Ontwikkeling
Het beheren van datastromen voor Basis- en Kernregistraties was nog maar het begin van het CDV. Nieuwe aandachtsgebieden en technieken brengen continue nieuwe datastromen met zich mee. Om zowel bestaande als nieuwe datastromen te ondersteunen wordt tooling toegevoegd aan de gereedschapskist van het integratie-team, zie onderstaande visualisatie waarin de brokken functionaliteit genoemd worden.

<p align="center">
  <img src="functionaliteit%20API-Management.png" width="450" alt="Functionaliteit API-Management">
</p>

In de architectuur krijgen de API-Gateway en NLX de volgende positie (de API-Manager en de API-Portal zijn hierin niet ingetekend):

![alt text](https://github.com/Drechtsteden/CentraleDistributieVoorziening/blob/master/API-Management%20Drechtsteden.jpg
"Invulling Gemeentelijke Gegevenslandschap")

## as a Service 
Het toekomstbeeld van Drechtsteden is om het gehele integratievraagstuk als dienst af te nemen bij een dienstverlenende partij. Daarbij is het voor Drechtsteden ondergeschikt welke technieken daarvoor vereist zijn (dit zal namelijk de komende jaren steeds aan verandering onderhevig blijven). Het past in de beelden van Drechtsteden dat de benodigde tooling op een integratieplatform vanuit de Cloud worden aangeboden.

De eisen die Drechtsteden stelt aan de tooling en het beheer van het gehele API-verkeer staan beschreven in de door Drechtsteden opgestelde [Requirements specificatie](https://github.com/Drechtsteden/CentraleDistributieVoorziening/blob/master/Requirements%20specificatie%20API-Management.pdf).

Voor vragen neem contact op met Dennis de Wit, Chief Data Officer Drechtsteden (d.de.wit@drechtsteden.nl of [LinkedIn](https://www.linkedin.com/in/dennis-de-wit-57ba8a20/
"Dennis de Wit"))).
