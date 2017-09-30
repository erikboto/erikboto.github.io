---
layout: page
title: Monark-ANT
permalink: /monark-ant/
---

## Introduktion
Monark-ANT är ett program ger nyare monarkcyklar stöd för ANT+.

## Vilka cyklar stöds
- Monark LT2
- Monark LC4r
- Monark LC6/LC7

## Vilken funktionalitet stöd över ANT+?

Monark-ANT stöder två ANT+-profiler, ANT+ Bike Power samt ANT+ FE-C

# ANT+ Bike Power

Bike Power profilen används för att sända aktuell effekt och kadens
på samma sätt som t ex en vanlig effektmätare kan göra.

# ANT+ FE-C

FE-C (Fitness Equipment - Control) profilen används när man vill
kunna styra effekten från t ex TrainerRoad, Zwift eller en nyare 
cykeldator. 

Det finns två olika lägen som man kan använda, ett där man styr
önskad effekt och ett där man styr ett antal simulationsparametrar
som t ex lutning och luftmotstånd för att simulera utomhuskörning.
Eftersom det inte finns växlar eller något bakhjul som har en
hastighet så har inte simuleringsläget så stor relevans för en
monarkcykel och stöds därför inte. Zwift använder i vanliga fall
simuleringsläget för att ge den bästa upplevelsen, men är ändå 
användsbart i "Workout Mode" där den styr önskad effekt. Man kan
också använda Zwift ihop med ANT+ Bike Power, men då får man styra
önskad effekt. Så det blir inte tyngre när man kommer till en backe.

## Vilken funktionalitet stöd över Bluetooth?

Det som sänds över Bluetooth är effekt samt kadens, och det över effektmätarprofilen. Det fungerar bra med Zwift, men en användare av en Polar V650 har rapporterat att den rapporterar fel efter ca 30 s med meddelande om att den tappat signal från ena sidan precis som om den förväntar sig en dubbelsidig mätning.
