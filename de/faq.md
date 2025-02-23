---
layout: default
title: FAQ
parent: DE - Handbuch
has_children: false
nav_order: 8
---

# FAQ

Frage: Auf dem Display erscheint eine „emergency stop“ Warnung ab 120°C, warum?

> Die Notabschaltung greift ab 120°C, um ein Überhitzen der Maschine durch unvorhergesehenes Reglerverhalten zu vermeiden. Ab einer Temperatur <100°C wird die Notabschaltung wieder außer Kraft gesetzt. Während des Dampfbezuges erscheint diese Meldung regelmäßig (da mehr als 120°C), hat allerdings keinen Einfluss, da der Dampf nicht über den Regler gesteuert wird.

Frage: Warum schaltet der Heizungs-SSR nicht?

> Häufig passiert es, dass der Signal des Pins nicht am + Pol sondern – Pol des SSRs angeschlossen ist. Bitte prüft, ob ihr richtig den SSR angeschlossen habt. Mit einem Messgerät kann man den Durchgang bei einem SSR nicht prüfen. Höchstens, ob die gewünschten 3,3 Volt am SSR anliegen.

Frage: Meine PID-Werte passen nicht, meine Maschine schwingt über o.ä.

> Schaut bitte zu erst in unsere PID-Wert Liste [PID-Werte](./customization/pid-werte.md), hier sind für viele PID-Werte dokumentiert für den Kaltstart, den normalen Betrieb und für die Brüherkennung. Bei Fragen im Chat bitte genau sagen, was genau nicht passt und schickt am besten Werte aus eurem Blynk dazu. Am besten im jeweiligen Chat zu den Maschinen.
