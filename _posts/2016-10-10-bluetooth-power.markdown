---
layout: post
title:  "Sända effekt över Bluetooth"
date:   2016-10-20 06:22:30 +0200
categories: monark bluetooth
---
Jag började kika för ett tag sedan på att lägga till stöd för att även sända effekt över Bluetooth, så att det skulle vara möjligt att använda t ex TrainerRoad och Zwift på iOS- och Android-enheter som saknar stöd för ANT+. Nu verkar det som att jag fått ordning på detta, men det kvarstår lite jobb för att sy ihop allt. 

Tanken är att presentera två olika sensorer. Dels en effektmätare som sänder ut kadens och effekt, och dels en pulsmätare som sänder ut ev. puls jag kan läsa från Monarken. Anledningen till återutsända pulsen är för att man skall slippa skaffa ett nytt pulsbälte ifall man bara har t ex Garmins variant som endast sänder ANT+, nu kan då Monarken läsa ANT+ och så sänder jag vidare ut det över Bluetooth.
