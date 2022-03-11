---
layout: default
title: Bill of materials
parent: EN - Handbook
has_children: false
nav_order: 2
---

# Bill of materials
{: .no_toc }

Table of contents

* TOC
{:toc}

## Warning Notice

> Working with high voltage can be deadly! **Always pull the power plug of your coffee maker before touching a screw or opening the housing!** Just switching the machine off is not sufficient. Smart or wifi plugs are not necessarily providing full separation from the mains! **The power plug always has to be pulled from the socket!** You are working at your own risk and carry all responsibility for any modifications.


## List of components

You need the following things, some of them might be even lying around in your toolbox already. Please ensure you order the right amount of each component, you can find the necessary quantity for the different type of installations in the columns.

### Core components

The core components are (usually) not lying around somewhere in the workshop.

Description | Part Number | Quantity (PID Only) | Quantity (Full Expansion) | Link
-|-|-|-|-
Temperature sensor|TSIC 306 TO92|2 (1)|2 (1)|[Reichelt-Link](https://www.reichelt.de/tsic-digitale-halbleiter-temperatursensoren-tsic-306-to92-p82327.html?r=1), [Alternativer Shop](https://shop.bb-sensors.com/Messtechnik-je-Branche/Gebaeudetechnik/Digitaler-TSic-306-Temperatursensor-TO92.html), [Alternativer Sensor](https://www.reichelt.de/de/de/tsic-digitale-halbleiter-temperatursensoren-tsic-206-to92-p82326.html?trstct=pos_1&nbc=1&&r=1)
Power supply|SNT RS 15 5|1|1|[Reichelt-Link](https://www.reichelt.de/schaltnetzteil-geschlossen-15-w-5-v-3-a-snt-rs-15-5-p137080.html?&trstct=pos_0) or [Amazon-Link](https://www.amazon.de/original-RS-15-5-meanwell-Single-Switching/dp/B06XDL7ZPT)
Solid state relay – heating|RA 2425-D06|1|1|[Reichelt-Link](https://www.reichelt.de/solid-state-relais-ust-2-32vdc-ulast-24-280v-ra-2425-d06-p22691.html?&trstct=pos_0) or [Alternative SSR (Amazon)](https://www.amazon.de/heschen-Single-ssr-40da-3-32-VDC-50-60-Hz/dp/B071HP9NJD)
Microcontroller|NodeMCU esp8266 V2|1|1|[Amazon-Link](https://www.amazon.de/AZDelivery-NodeMCU-ESP8266-ESP-12E-Development/dp/B06Y1LZLLY/ref=sr_1_1_sspa?ie=UTF8&qid=1538918768&sr=8-1-spons&keywords=nodemcu+esp8266&psc=1) or [Ebay-Link](https://www.ebay.de/itm/NodeMCU-v3-2-ESP8266-Dev-Kit-WIFI-Lolin-Amica-CP2102-v2-Arduino-IOT/252712258856?hash=item3ad6d30d28:g:TtsAAOSwlkpb3ZkV) or [unsoldered (Amazon)](https://www.amazon.de/-/en/AZDelivery-NodeMCU-Amica-Unsoldered-Parent/dp/B07GYW4T5F/ref=sr_1_3?dchild=1&keywords=nodemcu+v2&qid=1617445906&sr=8-3)
Display (optional but recommended)|128 x 64 Pixel OLED|1|1|[Amazon-Link](https://www.amazon.de/AZDelivery-Display-Arduino-Raspberry-gratis/dp/B01L9GC470/ref=sr_1_3?ie=UTF8&qid=1544291613&sr=8-3&keywords=oled+128x64)
Circuit board|PCB ESPresso Rev1|1|1|[See below](#pcb)
**ALTERNATIVE**|NodeMCU Motor Shield L293D|||[See below](#motor-shield)

### Cables

#### Heat-resistant cables

We strongly recommend to use heat-resistant cables.

Description | Part Number | Quantity (PID Only) | Quantity (Full Expansion) | Link
-|-|-|-|-
Heat-resistant ÖLFLEX® HEAT 180 SIF 1 x 1.50 mm², black|601382|2 m| 2m|[Link](https://www.conrad.de/de/p/lapp-0051001-hochtemperaturader-oelflex-heat-180-sif-1-x-1-50-mm-schwarz-meterware-601382.html)
Heat-resistan ÖLFLEX® HEAT 180 SIF 1 x 1.50 mm², blue|600368|2 m|2 m|[Link](https://www.conrad.de/de/p/lapp-0051002-hochtemperaturader-oelflex-heat-180-sif-1-x-1-50-mm-blau-meterware-600368.html)
Heat-resistan ÖLFLEX® HEAT 180 SIF 1 x 0.25 mm², black|604025|2 m|2 m|[Link](https://www.conrad.de/de/p/lapp-0047001-hochtemperaturader-oelflex-heat-180-sif-1-x-0-25-mm-schwarz-meterware-604025.html)
Heat-resistan ÖLFLEX® HEAT 180 SIF 1 x 0.25 mm², red|603963|2 m|2 m|[Link](https://www.conrad.de/de/p/lapp-0047104-hochtemperaturader-oelflex-heat-180-sif-1-x-0-25-mm-rot-meterware-603963.html)
Heat-resistan ÖLFLEX® HEAT 180 SIF 1 x 0.25 mm², green|609459|2 m|2 m|[Link](https://www.conrad.de/de/p/lapp-0047006-hochtemperaturader-oelflex-heat-180-sif-1-x-0-25-mm-gruen-meterware-609459.html)
Heat-resistan ÖLFLEX® HEAT 180 SIF 1 x 0.25 mm², yellow|602330|2 m|2 m|[Link](https://www.conrad.de/de/p/lapp-0047005-hochtemperaturader-oelflex-heat-180-sif-1-x-0-25-mm-gelb-meterware-602330.html)

#### Normal cables

In case you can't / don't want to use the recommended heat-resistant cables, you can use the below normal cables if you know what you're doing.

Description | Part Number | Quantity (PID Only) | Quantity (Full Expansion) | Link
-|-|-|-|-
Jumper/control litz wire H07 V-K ST1 - 1.5 mm², multi-wire, 10 m, blue|H07VK 1,5-10BL|1|1|[Link](https://www.reichelt.de/schaltlitze-h07v-k-1-5-mm-10-m-blau-h07vk-1-5-10bl-p69504.html?)
Jumper/control litz wire H07 V-K ST1 - 1.5 mm², multi-wire, 10 m, black|H07VK 1,5-10SW|1|1|[Link](https://www.reichelt.de/schaltlitze-h07v-k-1-5-mm-10-m-schwarz-h07vk-1-5-10sw-p69503.html?)
Insulated braided copper wire, 1-core, 1 x 0.14 mm², 10M, black|LITZE SW|1|1|[Link](https://www.reichelt.de/kupferlitze-isoliert-10-m-1-x-0-14-mm-schwarz-litze-sw-p10298.html?)
Insulated braided copper wire, 1-core, 1 x 0.14 mm², 10M,  blue|LITZE BL|1|1|[Link](https://www.reichelt.de/kupferlitze-isoliert-10-m-1-x-0-14-mm-blau-litze-bl-p10292.html?)
Insulated braided copper wire, 1-core, 1 x 0.14 mm², 10M, red|LITZE RT|1|1|[Link](https://www.reichelt.de/kupferlitze-isoliert-10-m-1-x-0-14-mm-rot-litze-rt-p10297.html?)
Insulated braided copper wire, 1-core, 1 x 0.14 mm², 10M, green|LITZE GN|1|1|[Link](https://www.reichelt.de/kupferlitze-isoliert-10-m-1-x-0-14-mm-gruen-litze-gn-p10296.html?)

### Connectors & accessories

These are the recommended connectors and accessories which are more likely you have already.

Description | Part Number | Quantity (PID Only) | Quantity (Full Expansion) | Link
-|-|-|-|-
Female disconnects with shrinking tube – 1.5 - 2.5 mm², blue|WE F602638HS|10|20|[Reichelt-Link](https://www.reichelt.de/flachsteckhuelsen-mit-schrumpfschlauch-1-5-2-5-mm-blau-we-f602638hs-p189402.html?&trstct=pos_0&nbc=1)
Piggy back disconnects Nylon – 1.5 - 2.5 mm², transp., blue|WE F606638.1N|5|5|[Reichelt-Link](https://www.reichelt.de/flachsteckhuelsen-mit-abzweig-1-5-2-5-mm-transp-vollisoli-we-f606638-1n-p189372.html?search=WE+F606638.1N)
Female disconnects with shrinking tube – 1,5 - 2,5 mm², blue|WE F616638HS|10|20|[Reichelt-Link](https://www.reichelt.de/flachstecker-mit-schrumpfschlauch-1-5-2-5-mm-blau-we-f616638hs-p189408.html?&trstct=pos_0&nbc=1)
Ring connector for M3, red|RK-R-3|10|10|[Reichelt-Link](https://www.reichelt.de/ring-kerbschuhe-fuer-m3-rot-rk-r-3-p15259.html?&nbc=1)
Ring connector for M5, red|RK-R-5|10|10|[Reichelt-Link](https://www.reichelt.de/ring-kerbschuhe-fuer-m5-rot-rk-r-5-p142770.html?&nbc=1)
Relays for **Full Expansion** (see below)|DEBO RELAY 4WAY|0|1|[Reichelt-Link](https://www.reichelt.de/entwicklerboards-4-wege-solid-relais-5v-240v-2a-debo-relay-4way-p280064.html?)
Heat-shrink tubing kit|DELOCK 86271|1|1|[Link](https://www.reichelt.de/schrumpfschlauch-sortiment-schwarz-100-teilig-delock-86271-p152924.html?&trstct=pol_0&nbc=1)
Screw M4x16||1|1|
Nut M4||2|2|
Washer M4||2|2|
Thermal glue (non-conductive) for the temperature sensor|Silverbead Thermal Glue Adhesive SG100X [10g]|1|1|[Link](https://www.amazon.de/Silverbead-W%C3%A4rmeleitkleber-10-Gramm-SG100X/dp/B019MNSABG/ref=sr_1_1?ie=UTF8&qid=1538938085&sr=8-1&keywords=w%C3%A4rmeleitkleber)
**ALTERNATIVE:** Thermal paste|ARCTIC MX-4-2|||[Link](https://www.reichelt.de/arctic-mx-4-waermeleitpaste-2g-arctic-mx-4-2-p261247.html?&trstct=pos_14&nbc=1)
Jumper cable (optional)| AZDelivery Jumper Wire cable 3 x 40 STK | 1 | 1 | [Amazon-Link](https://www.amazon.de/Jumper-Wire-Set-M2M-Parent/dp/B07ZP4JLMM)
**ALTERNATIVE:**| See below
Dupont crimp set (optional) |DEBO SET DUPONT|1|1|[Reichelt-Link](https://www.reichelt.de/de/de/entwicklerboards-dupont-crimp-set-610-teilig-debo-set-dupont-p279901.html?trstct=pos_0&nbc=1&&r=1) oder [Amazon-Link](https://www.amazon.de/BESTOMZ-Stecker-m%C3%A4nnlich-weiblich-Anschluss/dp/B073SSV9TL/)
Crimping tool|KN 97 22 240|1|1|[Link](https://www.reichelt.de/crimpzange-240-mm-isolierte-kabelschuhe-kabelverbinder-kn-97-22-240-p122639.html?&trstct=pos_0&nbc=1)
Soldering iron|ERSATZKOLBEN EP5|||[Reichelt-Link](https://www.reichelt.de/loetkolben-ep-5-ersatzkolben-ep5-p58217.html?&trstct=pos_0&nbc=1)


## Notes on the bill of materials

### PCB
In order to buy the PCB kit, [please inquire directly via our chat!](https://chat.rancilio-pid.de/) **Contact @toppo78 via DM**
Using this PCB is highly recommended due to the form factor and well designed connections. However, it's not mandatory to use this board - there are no electronics on it, this is just for connectivity. If you can't opt in for this PCB, you can use a motor shield for the NodeMCU or build your own connectivity.

![PCB KIT components](../img/PCB_Lieferumfang.jpeg)

Included in the PCB kit:
 * Circuit board
 * Screw terminals
 * Pin headers
 * Adhesive pads


### Motor shield
You can buy any L293D Motor shield for ESP8266. Just make sure the NodeMCU fits nicely.

![Motor shield picture](https://cdn.myonlinestore.eu/e40d5160-bac0-4897-baae-d6065a5d5915/image/cache/full/7350212328904bf10cd1ef970b106b44ca3d1572.jpg)


### Thermal adhesive & Thermal paste
Thermal adhesive is controversial (see [Link](https://www.igorslab.de/mythos-waermeleitpaste-edelpaste-zum-apothekenpreis-gegen-guenstiges-massenprodukt-wir-rechnen-gnadenlos-nach/) and below section for more details). Nevertheless, most users use it to attach the thermal sensor directly to the boiler. In a nutshell this is the general rule: Use as little as possible and try to attach the sensor with the existing bracket (and additional screw with nut) if possible. This should help achieving an acceptable level of temperature difference and secure attachment.

<details markdown="block">
  <summary>Discussion on thermal adhesive</summary>
 As mentioned above, thermal adhesive is controversial because of its poor thermal conductivity. One of the few recommended thermal adhesives is from Arctic Silver with a thermal conductivity of 4 W/mK when crosslinked: [Link](https://www.webshop-innovatek.de/waermeleitmittel/waermeleitkleber/368/arctic-silver-waermeleitkleber-2x-4-g-neue-version) (unfortunately difficult to obtain or available at pharmacy prices). The glue linked above, on the other hand, only has a thermal conductivity of around 1 W/mK (assuming the information is correct). 

 As an example for the paste, a layer thickness of 0.05 mm would result in a thermal resistance of 0.29 K/W. At 0.5 mm we are already at 2.9 K/W.

 This means that with a power loss of 1 W, the temperature difference between the source (boiler) and sink (sensor) is 0.29 or 2.9 K.

 For this reason it is very important that the paste or glue in a pinch is applied as **THIN AS POSSIBLE!** In the best case, we are talking about 0.04 mm.
</details>


### Temperature Sensor
We highly recommend to buy at least 2 TSIC sensors. However since we've seen that sensors are often wired incorrectly, we also advise to consider getting a spare while ordering from Reichelt.
Please do not use a sensor with the wrong polarity, as it will break very quickly or display unrealistic values ​​(for details see [how to connect the temperature sensor](./hardware/hardware.md#temperatursensor-anschließen)).


### Microcontroller
Only the NodeMCU V2 fits the PCB board. **You won't be able to fit the V1 or V3.**
However this is only a problem if you plan to use our board.


### Power supply
The linked power supply caused problems for a few people (reboots). Alternatively you can use a simple USB power supply, which provides more stable voltage.

Space could be a bottleneck, especially with the newer Rancilio Silvia E variants. A USB power supply unit may also be preferable here.

### Display & Jumper cables
The display is not strictly necessarily required for any expansion stage, but highly recommended.
Without a display it can be hardly avoided to check the temperature on your smartphone every time you use it.
If you like it simple, you can either place the display next to the machine or fix it to one of the metal sheets. As you can see from the projects [link](https://clevercoffee.de/rancilio-silvia-e-konstantin/), the display can of course also be neatly integrated.

The listed jumper cables are also recommended for easy operation of the display - this means soldering is not necessary. Jumpers are therefore well suited for dry construction. Alternatively, you can get a Dupont connector kit. This has the advantage that you can freely cut the length of the connection. But has the disadvantage that it can only be used with crimping pliers. Dupont connectors are therefore well suited for final installation. However, note the corresponding note on the temperature sensor: [link](https://manual.rancilio-pid.de/de/hardware/hardware.html#tipps-und-tricks)

### Infos zum Vollausbau SSR
Wir haben im Projekt viele diverse Relais für die Pumpe und das Ventil testen „dürfen“ – diese sind leider nicht so stabil wie die der SSR für die Heizung. Folgende Erkenntnisse haben wir dabei gesammelt:

#### Beste Lösung: High Trigger SSR
User im Chat haben zuverlässige Bezugsquellen für High Trigger gefunden: [Link](https://www.roboter-bausatz.de/1450/2-kanal-solid-state-relais-modul-5v/230vac-high-level-trigger). Daher ist dies momentan unsere Favorit. **Aktuell nicht lieferbar**

Alternativ kann bei Reichelt auch folgender High Trigger mitbestellt werden: [Link](https://www.reichelt.de/entwicklerboards-4-wege-solid-relais-5v-240v-2a-debo-relay-4way-p280064.html?&trstct=pos_0&nbc=1).

Bei einigen SSR-Ralais, z.B. dem von Reichelt muss ggf. noch ein Widerstand parallel zu der Pumpe geschaltet werden. Hintergrund hierzu ist, dass die SSRs in der Regel nur bei einem Nulldurchgang der Spannungskennlinie schalten. Die Vibrationspumpe in den Espressomaschinen funktioniert jedoch durch eine interne Diode die nur eine Halbwelle durchlässt. Dementsprechend kommt es nie zu einem Nulldurchgang. Einige Relais funktionieren trotzdem. Um diesem Problem Abhilfe zu schaffen wird ein Widerstand parallel zu der Pumpe geschaltet. Aus Erfahrung funktionieren 200k und 100k Widerstände. Wobei ein 100k Widerstand an dieser Stelle sinnvoller ist. Zu beachten ist hier die Leistung die über dem Widerstand abfällt. Die normalen "Wald und Wiesen" Widerstände die in Sortimentskästen verkauft werden haben nur 1/4 Watt was bei 200k recht grenzwertig und bei 100k unzureichend ist. Auf der sicheren Seite ist man mit einem 100k Widerstand mit 1W. Wie z.B. [Link](https://www.reichelt.de/widerstand-metalloxyd-100-kohm-0207-1-0-w-5--1w-100k-p1778.html?&trstct=pos_1&nbc=1) 

#### Schlechteste Lösung: Spulen Relais
Ja, Spulen Relais kann man verwenden, dabei können durch die Bauweise der Relais Probleme entstehen, die sich nicht immer lösen oder reproduzieren lassen: [Link](https://www.amazon.de/AZDelivery-2-Relais-Optokoppler-Low-Level-Trigger-Arduino/dp/B078Q326KT/ref=sr_1_7_sspa?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=azdelivery%2Bspulen%2Brelais&qid=1603614378&sr=8-7-spons&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUExNDdFUE9JRkxXSkNEJmVuY3J5cHRlZElkPUEwNDU5MDU1OVlVSENDWEZNQTQzJmVuY3J5cHRlZEFkSWQ9QTAwNDA1MTEzUlBCUzUwVFdZSTI3JndpZGdldE5hbWU9c3BfbXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ&th=1). Lösungen mit einer galvanischen Trennung können manchmal helfen [Link](https://www.kollino.de/arduino/4-8-kanal-relais-anleitung/). Daher ist es die schlechteste Lösung bei den Relais.

#### SSR Board von Amazon
Manche gehen ins Spielcasino, wir bestellen bei Amazon – Manchmal hat man Pech und wo „High Trigger“ drauf steht, ist manchmal „Low Trigger“ drin. Einen Low Trigger erkennt ihr an einem „2TY“ auf dem einen Baustein des SSR Boards. „J3Y“ Steht hierbei für den besseren HIGH Trigger. SSR Boards sind besser als die Spulen Relais, aber Low Trigger können auch Probleme verursachen.

#### Alternative: 2x Heizungs SSR
Wenn der Platz vorhanden ist, könnte man auch 2x den Heizung SSR nutzen.
