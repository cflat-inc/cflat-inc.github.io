---
title: cFlat Home-Network
layout: splash
permalink: /cflat-net/
header:
  overlay_image: /assets/images/hd-cFlat.jpg
  overlay_filter: 0.5
  caption: 'Photo credit: [**pixabay**](https://pixabay.com)'
published: true
---
<p></p>

Als ich mir Gedanken, bezüglich eines vernünftigen und sicheren Home-Netzwerk Layout machte und auf die unten stehenden Lösungen gekommen bin, ist mir der aus irgend einem Grund der Film [The Good, the Bad and the Ugly](https://en.wikipedia.org/wiki/The_Good,_the_Bad_and_the_Ugly) in den Sinn gekommen. Die Reihenfolge stimmt nicht ganz, aber etwas hat es schon an sich …  

## The Bad

![homeNetwork-bad.svg!!](/assets/images/homeNetwork-bad.svg){: .align-right style="width: 300px"}
**"Die Dödel-Lösung"**

Ich nenne mal eine Zahl, aber mehr als 95 Prozent (wahrscheinlich ist sie noch höher) der Smart-Home Installationen sehen so wie in diesem Home-Netzwerk Layout aus. Dies ist der Ansatz, den die Internet Service Provider und Hersteller von Smart Home Produkte, vertreten: „Kaufen, App installieren und einschalten“, denn fast jeder „Dödel“ ist fähig, irgendwie die Dinger zum laufen zu bringen. Aber die Sicherheitsrisiken verschweigen sie geflissentlich. Nicht nur, dass der Provider auf all Ihre Daten zugriff hat. Die Smart Home Produkte entwickeln plötzlich ein nicht gewolltes Eigenleben und versenden die persönlichen Daten ins ganze Internet oder sie werden ganz profan für Hacker-Angriffe auf einen fremden Server missbraucht, etc. etc.

Ganz abgesehen davon, weiss man nicht genau, was heutzutage alles mit einer richterlichen Verfügung möglich ist. 

Also Finger weg und neu machen...

## The Ugly

![homeNetwork-ugly.svg!!](/assets/images/homeNetwork-ugly.svg){: .align-right style="width: 300px"}
**"Trau Dir nur selber"**

Dieser Ansatz ist eine „Weder Fisch noch Vogel“ Lösung. Mit der Integration eines zusätzlichen Switches inkl. Firewall (Ich verwendete eine Fritzbox 4040) entsteht eine Trusted-Zone, in die der Provider keinen Zugriff mehr hat. Womit das ISP-Problem gelöst ist.<br>
Das Problem mit dem ungewollten Eigenleben ist leider weniger elegant. Wenn man das Gast-Netz zum IoT-Subnetz erklärt, hat man das Problem, das IoT-Devices die UDP-Broadcast (wie Bonjour etc) zum auffinden benutzen, vom LAN nicht sichtbar sind. Gemäss Aussagen im Netz, müsste es mit einer (My)Router Kaskade (Router hinter Router) funktionieren. Ich habe diese Konfiguration mit einem geliehenen Router (Fritzbox 404) nicht zum laufen gebracht und danach die Versuche frustriert abgebrochen.

// Falls jemand eine einwandfrei funktionierende Lösung hat, wäre ich für [Tips](/contact) dankbar.//

## The Good

![homeNetwork-good.svg!!](/assets/images/homeNetwork-good.svg){: .align-right style="width: 300px"}
**"That's the way"**

Ich nenne Einmahl eine Zahl, aber mehr als 95 Prozent (wahrscheinlich ist sie noch höher) der Smart-Home Installationen sehen so wie in diesem „The Bad“ Home-Netzwerk aus.

Ich nenne Einmahl eine Zahl, aber mehr als 95 Prozent (wahrscheinlich ist sie noch höher) der Smart-Home Installationen sehen so wie in diesem „The Bad“ Home-Netzwerk aus.

Ich nenne Einmahl eine Zahl, aber mehr als 95 Prozent (wahrscheinlich ist sie noch höher) der Smart-Home Installationen sehen so wie in diesem „The Bad“ Home-Netzwerk aus.

Ich nenne Einmahl eine Zahl, aber mehr als 95 Prozent (wahrscheinlich ist sie noch höher) der Smart-Home Installationen sehen so wie in diesem „The Bad“ Home-Netzwerk aus. 

### Aufbau

---

**Anmerkung:**

Während der Recherche zu diesem Thema, bin ich unter anderem auf einen Heise-Artikel [Smart Home? Aber sicher!](https://www.heise.de/ct/ausgabe/2017-8-Wie-Sie-schnueffelnde-Geraete-isolieren-und-Ihre-Privatsphaere-schuetzen-3667338.html) gestossen, der sich genau mit den Themen Home Netzwerk und Security beschäftigt. Ich kann diesen nur empfehlen, leider Paid-Content. Denn in der Artikel-Serie wird gut aufgezeigt, was passiert, wenn man nicht Aufpasst und gewisse Vorkehrungen nicht trifft. 
