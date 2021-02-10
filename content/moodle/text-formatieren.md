---
title: "Texte formatieren"
date: 2021-02-07T20:53:36+01:00

---
{{< hint ok >}}

<img src="/images/noun_Info_817970.svg" height="80px"
     alt="info"
     style="float: left; margin-right: 10px;" />
**Darum geht es**\
 Textseiten innerhalb des LMS Moodle (auch Logineo LMS, Mebis etc.) lassen sich mit ein paar Kniffen und Handgriffen optisch ansprechend und didaktisch wertvoll gestalten. Hier sind ein paar dieser Ideen gesammelt.
{{< /hint >}}





{{< toc >}}

## Emojis einbinden

Zur optischen Strukturierung von Kursen und Kursenmaterialien können Bilder und Icons eine hilfreiche Unterstützung sein. Diese lassen sich nicht nur in Textfeldern einsetzen, sondern auch in Themenbezeichnung oder sogar Kursnamen. Wie das geht? Na so: 

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/zP-xiFmdIN8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Text mit Filtercodes personalisieren

Wenn man seinen Texten in Logineo LMS einen persönlichen Touch verleihen möchte, kann man hierzu das Plugin "Filtercodes" verwenden. Was hiermit alles möglich ist erkläre ich in diesem Video!

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/y6ev99CXZS0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Textseiten mehrspaltig gestalten

Bei der Gestaltung von Logineoseiten möchte man ggf. Text und/oder Bilder in mehreren Spalten darstellen werden. Hier greift man bei der Umsetzung schnell zu einer Tabelle, erhält dann aber ggf. Ergebnisse, die auf kleinen Displays nicht schön sind. Besser gelingt dies mit den Bootstrap-Containern.

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/FwnCZ2Vib84" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Textseiten mit iFrame-Einbindungen erweitern

Per iFrame lassen sich zahlreiche externe Dienste in LogineoLMS einbinden. Wie das funktioniert, erkläre ich in diesem Video.

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/fjPC13PqYjA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Texte mit der Grundschrift (oder anderen Schriften) gestalten

Dieses Video richtet sich an die User*innen, die an Grund- und Förderschulen arbeiten. Dort kann es insbesondere für Leseanfänger*innen sinnvoll sein, die Grundschrift für Texte zu verwenden. Die hierzu nötigen Schritte werden in diesem Video erklärt.

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/MFrLZhnpbeI" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Code für den HEAD-Bereich:

```
.grundschrift { font-family: GrundschriftRegular; font-size:14pt; }
```

Code für die Gestaltungsvorlage:

```
{
    "title": "Grundschrift",
    "type": "block",
    "classes": "grundschrift"
},
```

## Texte mit Gestaltungsvorlagen formatieren

Mit dem Atto-Editor von Logineo LMS lassen sich Texte mit grundlegende Funktionen formatieren. Für die erweiterte Textgestaltung, insbesondere für die Gestaltung von farbigen Hintergründen und Rahmen um Textabsätze bietet sich die Verwendung von Gestaltungsvorlagen an. Wie das funktioniert, erkläre ich in diesem Video.

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/_BZN3uW75Fc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## ausklappbare Felder 

Ausklappbare Felder können zum Beispiel verwendet werden, um Lösungen oder Lösungshinweise in Aufgabenstellung einzubinden, aber vorerst zu verstecken.

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/wHLHjku8s5U" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Code zum Erzeugen der ausklappbaren Felder:
```
<p>
    <a class="btn btn-primary" data-toggle="collapse" href="#collapsexample" role="button" aria-expanded="true" aria-controls="collapsexample">
    Klick mich an!
  </a>
</p>
<div class="collapse show" id="collapsexample" style="">
    <div class="card card-body">
        Sehet und staunet! Es funktioniert!
    </div>
</div>
```