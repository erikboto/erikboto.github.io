---
layout: page
title: Filer
permalink: /filer/
---

## Här kan du hitta aktuella versioner av mjukvaran

# Testversion med stöd för Bluetooth FTMS protokoll
Här finns versioner där det vanliga bluetoothstöder är utbytt mot det nyare Fitness Machine Service (FTMS) protokollet, som också tillåter styrning av motstånd på de cyklar som stöder det.

Fil för Raspberry Pi 4 finns [här][rpi4-ftms-v20230515]  
Fil för Raspberry Pi 3(+) finns [här][rpi3-ftms-v1]  
Fil för Raspberry Pi Zero W finns [här][rpi0w-ftms-v1]

# Raspberry Pi 4
En version för Raspberry Pi 4 finns [här][rpi4-v1].

# Raspberry Pi 3
Version med stöd för puls över BT (nu med unikt ID med i namnet) samt stöd för Raspberry Pi 3B+ finns [här][rpi3-v3rc3]

Jag fick låna en Polar M450 att testa lite med, och fick till effektmätning men inte kadens. Det finns två olika images, en där puls från Monarken också sänds ut via BT och en där det inte görs. De flesta som har Polar kör väl med pulsband som stöder BT och behöver kanske inte den funktionen.

Polar-version med puls finns [här][rpi3-polar-hrm].  
Polar-version med utan puls finns [här][rpi3-polar-no-hrm].

Tidigare versioner:  
Version (2) finns [här][rpi3-v2].  
BT-testversion  [här][rpi3-bttest].

Version (1) finns [här][rpi3-v1].

# Raspberry Pi 2
Aktuell version (1) finns [här][rpi2-v1].

# Windows
Aktuell version (3) för Windows 64-bit finns [här][win-64-v3].  
Aktuell version (3) för Windows 32-bit finns [här][win-32-v3].


[rpi2-v1]: http://linode.unixshell.se/monark/image-monark-raspberrypi2_v1.zip
[rpi3-v1]: http://linode.unixshell.se/monark/image-monark-raspberrypi3_v1.zip
[rpi3-v2]: http://linode.unixshell.se/monark/image-monark-raspberrypi3_v2.zip
[rpi3-polar-hrm]: http://linode.unixshell.se/monark/image-monark-polar-with-hr.zip
[rpi3-polar-no-hrm]: http://linode.unixshell.se/monark/image-monark-polar-without-hr.zip
[win-32-v3]: http://linode.unixshell.se/monark/Monark-ANT-32_v3.zip
[win-64-v3]: http://linode.unixshell.se/monark/Monark-ANT_v3.zip
[rpi3-bttest]: http://linode.unixshell.se/monark/image-monark-raspberrypi3-bt-test.zip
[rpi3-v3rc1]: http://linode.unixshell.se/monark/image-monark-raspberrypi3_v3-rc1.zip
[rpi3-v3rc3]: http://linode.unixshell.se/monark/image-monark-raspberrypi3_v3-rc3.zip
[rpi4-v1]: http://linode.unixshell.se/monark/image-monark-raspberrypi4_v1.zip
[rpi4-ftms-v20230515]: http://linode.unixshell.se/monark/image-monark-ftms-raspberrypi4_v20230515.zip
[rpi4-ftms-v1]: http://linode.unixshell.se/monark/image-monark-ftms-pi4_v1.zip
[rpi3-ftms-v1]: http://linode.unixshell.se/monark/image-monark-ftms-pi3_v1.zip
[rpi0w-ftms-v1]: http://linode.unixshell.se/monark/image-monark-ftms-pi0w_v1.zip
