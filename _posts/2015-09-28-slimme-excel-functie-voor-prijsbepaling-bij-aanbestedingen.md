---
layout: post
title: "Slimme Excel functie voor prijsbepaling bij aanbestedingen"
date: 2015-09-28
categories: Offertes schrijven
---

Naarmate je vaker aan aanbestedingen hebt meegedaan, weet je meer over je eigen kwaliteit en prijsstelling ten opzichte van je belangrijkste concurrenten. Elke keer als je een aanbesteding verloren hebt, ontvang je informatie over de beoordeling van jouw aanbieding en die van de concurrent. Prijsinformatie wordt daarbij niet gegeven, maar is redelijk goed af te leiden. Immers, zowel je eigen scores op de kwaliteitsaspecten als die van de concurrent worden inzichtelijk gemaakt in de brief over de voorlopige gunning. Aangezien je je eigen prijs kent, kun je afleiden wat de maximale prijs is geweest van je concurrent. Bij prijsbepaling is de kostprijs en de marge vaak het uitgangspunt. Een andere benadering is om af te gaan op wat je van je concurrenten weet. Daarvoor moet je wel systematisch bij gaan houden wat concurrenten hebben gescoord op de aanbestedingen waaraan je zelf hebt meegedaan. Op die manier bouw je met verloop van tijd een zeer waardevolle kennisdatabase op.

**Prijsbepaling op basis van concurrentieanalyse**

Een gangbare formule voor het toekennen van punten aan de prijs is LP/P*100 (Laagst geboden prijs/Prijs * 100). De aanbieder met de laagste prijs krijgt dus 100 punten. Daarnaast is de waardering van de prijs ten opzichte van de kwaliteit natuurlijk van belang. Die waardering kan uiteenlopen van 80/20 tot 20/80. Puur op prijs inkopen is tegenwoordig verboden voor aanbestedende diensten, tenzij ze dat uitstekend weten te motiveren en een verhouding 90/10 is dan ongeloofwaardig.

Als je nu een redelijk goed inzicht hebt opgebouwd in het kwaliteitsniveau van je belangrijkste concurrenten en in de prijsstellingen die ze ongeveer hanteren, dan kun je afleiden wat je prijs moet zijn om een goede kans te maken op het winnen van de aanbesteding.

Bovenstaand een fictief voorbeeld. In deze aanbesteding kun je maximaal 100 punten behalen op kwaliteit. Elke vraag levert maximaal 25 punten op. Nu schat je in dat je eigen kwaliteit behoorlijk lager zal liggen dan die van je concurrent. In totaal denk je 65 punten te halen, en je schat in dat je concurrent er misschien wel 86 haalt. Met een weging van 70/30 op kwaliteit versus prijs betekent dat, dat er een fors prijsverschil nodig is om deze aanbesteding te winnen. Als je vermoedt, dat de concurrent rond 1 miljoen gaat aanbieden, ligt jouw winnende prijs onder de 510k. Wellicht kun je het voor die prijs niet eens uitvoeren en kun je dus maar beter stoppen met het maken van een offerte.

Heel anders is het als de weging geen 70/30 is, maar juist andersom. In dat geval moet jouw prijs onder de 910k blijven om de aanbesteding te kunnen winnen. Uiteraard is deze prijs dan op het randje en moet je enige marge inbouwen om met meer zekerheid te winnen.

**Doelzoeken in Excel**

Met de functie “Doelzoeken” in Excel kun je dit allemaal snel uitrekenen. Het werkt als volgt.

Onder de scores per vraag tel je de totale kwaliteitsscore op. In dit geval komt je eigen score uit op 65, die van de concurrent op 86. Vervolgens vermenigvuldig je deze scores met de weging, in dit geval 30. Daarmee komt het totaal voor kwaliteit op 65*30=1950 en die van je concurrent op 86*30=2580. De score op prijs wordt bepaald door de gegeven formule. Om te winnen met een lagere kwaliteit je de laagste prijs aanbieden. Je verdient dus per definitie de maximale score op prijs: 100 punten. Met een weging van 70 verdien je dus met de laagste prijs 7.000 punten. Jouw eigen inschatting voor kwaliteit was 1950 punten, dus je totaalscore komt op 1950+7000=8950. De prijsscore van je concurrent wordt bepaald door jouw prijs. Je schat in, dat je concurrent 2580 punten gaat scoren op kwaliteit. De prijsscore van de concurrent moet dan lager uitkomen dan jouw totaalscore minus de kwaliteitsscore van de concurrent, dus: 8950–2580=6370. Dat kun je bereiken door jouw prijs te laten zakken, totdat ook de concurrent een totaalscore van 8950 heeft. Daarvoor gebruik je de functie Doelzoeken in Excel. Je vindt die functie onder Gegevens/Wat-als-analyse. In die functie geef je aan dat je de cel met de prijsscore van je concurrent wilt instellen op 6370, door de cel waarin jouw prijs staat te wijzigen. Eén druk op de knop en daar komt dan die 910k uit. Bied voor de veiligheid een prijs aan van 890k en je hebt de opdracht binnen.

**Soortgelijke berekeningen**

Een soortgelijke berekening kun je opzetten voor als je weet dat jouw kwaliteit veel hoger ligt dan die van je concurrent. Als die kwaliteit dan ook nog heel zwaar telt, kun je dus een fors hogere prijs vragen en de aanbesteding toch nog winnen. Ook kun je een Excel sheet opzetten om de prijs van de concurrent af te leiden uit de terugkoppeling van de aanbestedende dienst als je de aanbesteding verloren hebt. Meer weten? Neem contact op via [info@smarttenders.nl](mailto:info@smarttenders.nl) of bel: 06 511 22 552.
