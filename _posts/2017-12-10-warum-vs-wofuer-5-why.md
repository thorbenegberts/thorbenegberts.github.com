---
layout:     post
title:      "Warum vs. Wofür: 5-Why"
date:       2017-12-10 15:19
summary:    "Die 5-Why-Methode: Wo sie aufhört zu funktionieren und was stattdessen nützlich ist."
categories: agile
---

![.](/assets/2017-12-10-warum-vs-wofuer-5-why/dreamstime_m_72544239.jpg)

In einem gewissen Alter beginnen Kinder damit, ständig „Warum?” zu fragen. Dabei geben sie sich mit einer einzelnen Antwort oft nicht zufrieden, wodurch lange „Warum-Ketten” entstehen. So eine Kette endet im besten Fall durch eine zufriedenstellende Antwort. Viel öfter jedoch wird die Kette durch ein „Weiß ich nicht!”, „Deshalb!”, „Das ist einfach so!” oder – abhängig davon, wer der Gefragt ist – „Frag eine Mutter!” unterbrochen.

Später in der Arbeitswelt beginnen diese Kinder, egal ob sie nun Chefs oder Angestellte sind, erneut mit den Warum-Fragen. Meist, wenn etwas schief gegangen ist, eine Problemursache analysiert wird oder etwas optimiert werden soll.

Die [5-Why-Methode](https://de.wikipedia.org/wiki/5-Why-Methode) wird gern für Problemanalysen oder Retrospektiven verwendet. Ausgehend von einer Problemstellung wird fünfmal „Warum?” gefragt. Jede Antwort ist Ausgangspunkt für eine weitere Warum-Frage. Die Annahme ist, nach fünf solcher Fragen auf die Problemursache (Root Cause) zu stoßen. Diese kann nun als Verursacher des Problemsymptoms beseitigt werden.  

## 5-Why für komplizierte Probleme

Für die 5-Why-Methode liefert Wikipedia dieses Beispiel:

**Problemstellung:** Das Fahrzeug startet nicht.

1. Warum startet das Fahrzeug nicht? &rarr; Die Starterbatterie ist leer.
2. Warum ist die Starterbatterie leer? &rarr; Die Lichtmaschine funktioniert nicht.
3. Warum funktioniert die Lichtmaschine nicht? &rarr; Der Keilriemen ist gerissen.
4. Warum ist der Keilriemen gerissen? &rarr; Der Keilriemen wurde nie ausgewechselt.
5. Warum wurde der Keilriemen nie ausgewechselt? &rarr; Das Fahrzeug wurde bisher nie gewartet.

Eine mögliche Maßnahme wäre, das Auto in einer Werkstatt warten zu lassen und von da an regelmäßigen Wartungen zu unterziehen.

Diese Problemstellung bewegt sich in einem kausal-mechanischen Kontext. Ursache und Wirkung ist dem Beobachter bekannt oder kann in einer Dokumentation nachgelesen oder von einem Experten festgestellt werden.

Ähnliche Problemstellungen wären:

- Eine Software hat einen Fehler
- Der Prozess der Buchhaltung im Unternehmen soll optimiert werden
- Eine Fräsmaschine hat ein defektes Teil

Warum-Fragen sind hier zweckmäßig, weil sie rückwärts die Kausalitätsketten aufdecken, die vom eigentlichen Auslöser zum Problemsymptom geführt haben. Die Ursache des Problems lag bereits im Problem selbst. Die Systemtheorie spricht hier auch von einfachen und komplizierten Problemen, von denen die komplexen zu unterscheiden sind — im Gegensatz zum allgemeinen Sprachgebrauch, in dem „komplex” als „besonders kompliziert” verstanden wird.

## 5-Why für komplexe Probleme

Komplex werden Probleme dann, wenn das Verhalten von Menschen eine Rolle spielt. Hier ein Beispiel, an dem wir die 5-Why-Methode ebenfalls durchführen wollen.

**Problemstellung:** Ein Projekt wurde nicht zum vereinbarten Datum fertiggestellt. Frage an den Projektmanager:

1. Warum ist das Projekt nicht pünktlich fertig geworden? &rarr; Weil wir die Vereinbarungen nicht halten konnten.
2. Warum konnten die Vereinbarungen nicht gehalten werden? &rarr; Weil wir nicht unseren vollen Einsatz gegeben haben.
3. Warum habt ihr nicht euren vollen Einsatz gegeben? &rarr; Anna hat nicht so viel programmiert wie sonst.
4. Warum hat Anna nicht so viel programmiert wie sonst? &rarr; Weil sie selten an ihrem Platz war.
5. Warum war Anna so selten an ihrem Platz? &rarr; Sie war einfach nicht da. Vielleicht fehlte ihr die Motivation und war oft Kaffee trinken?

Anna wird daraufhin zum Personalgespräch gebeten. Sie wird mit dem Vorwurf konfrontiert. Die Arme verschränkend faucht empört: „Das stimmt doch garnicht! Ohne mich wäre es noch schlimmer geworden.” Auch Anna durchläuft die 5-Why:

1. Warum ist das Projekt nicht pünktlich fertig geworden? &rarr; Es sah alles gut aus, aber dann gab es Probleme mit einer Programmbibliothek.
2. Warum gab es Probleme mit einer Programmbibliothek? &rarr; Die Programmbibliothek erfüllte nicht die notwendigen Anforderungen.
3. Warum erfüllte die Programmbibliothek nicht die notwendigen Anforderungen? &rarr; Das andere Team, das die Programmbibliothek entwickelt hat, hat diese nicht implementiert.
4. Warum hat das andere Team die Anforderungen nicht implementiert? &rarr; Weil die neuen Anforderungen sich erst kurz vor dem geplanten Fertigstellungstermin ergeben haben.
5. Warum haben sich die Anforderungen erst kurz vor dem Fertigstellungstermin ergeben? &rarr; Weil der Kunde etwas anderes brauchte als zunächst geplant.

Jetzt gäbe es zwei neue Ansatzpunkte, die verfolgt werden können: Warum hat sich der Kunde umentschieden? War das andere Team zu langsam? Wir bleiben bei der ursprünglichen Problemstellung. 5-Why mit einem Mitglied des anderen Teams:

1. Warum ist das Projekt nicht pünktlich fertig geworden? &rarr; Wir konnten die Programmbibliothek nicht mehr rechtzeitig anpassen.
2. Warum konntet ihr die Programmbibliothek nicht rechtzeitig anpassen? &rarr; Weil die Anforderung zu spät bekannt war.
3. Warum war die Anforderung zu spät bekannt? &rarr; Der Projektmanager hat uns zu spät Bescheid gegeben.
4. Warum hat der Projektmanager euch zu spät Bescheid gegeben? &rarr; Ich weiß nicht, er hat es vermutlich vergessen.
5. Warum hat der Projektmanager es vergessen? &rarr; Er ist viel unterwegs und hat viel um die Ohren. Anna hatte Kontakt zum Kunden und hat es von ihm erfahren. Sie hat unser Team darauf intensiv dabei unterstützt, die Programmbibliothek anzupassen. Sie hat sich sogar zu uns ins Büro gesetzt. Aber es war einfach zu viel Arbeit.

So kann es noch sehr lang weitergehen. Es würden immer mehr Sichtweisen und vermeintliche Problemursachen hinzukommen. Auf manche Warum-Fragen gäbe es mehrere Antworten.

Nicht jeder hatte zu jedem Zeitpunkt die Information des anderen. Schuldfragen entstehen, genau wie „Cover-Your-Ass”-Verhalten und politische Manöver. Schuld wird zugewiesen und abgelehnt. Un- und Halbwahrheiten kommen ins Spiel.

Eventuell werden sogar konkrete Maßnahmen getroffen, personelle Konsequenzen entstehen oder es wird alles als verhängnisvolle Kette von ungünstigen Ereignissen deklariert

Irgendwann stellt sich dann die Frage: War das nützlich? Hat sich das gelohnt? Stehen die Mitarbeiter, das Team und die Organisation nun besser da als vorher? Gibt es positive Auswirkungen auf Zusammenarbeit und Vertrauen? Spätestens, wenn es nur noch darum geht, Schuldige zu finden: Vermutlich nein.

Das Problem ist nicht nur die Asymmetrie der Informationen, also dass nicht jeder Person zu jedem Zeitpunkt die selben Fakten vorliegen. Dazu kommt, dass Menschen keine Automaten mit kausal-mechanischem Verhaltenden sind. Jeder Mensch filtert die Fakten und baut sich dadurch seine eigene Realität der Dinge. Dazu kommt, dass diese Fakten auf Basis der bisherigen Lebenserfahrungen bewertet und transformiert werden. Gleichzeitig wird die Lebenserfahrung durch neu erlebtes verändert. Werden die gleichen Fakten oder Situationen noch einmal wahrgenommen, kann es also passieren, dass diese nun zu einem ganz anderen Bewerten und daraus resultierenden Verhalten führen.

Hier wird auch von einer systemisch-konstruktivistischen Perspektive bzw. in der Systemtheorie von Komplexität gesprochen. Der Unterschied zwischen komplexen und einfachen bzw. komplizierten Zusammenhängen ist der, dass komplexe Verhaltensweisen (praktisch) nicht vorhersehbar sind, da es zu viele sich gegenseitig beeinflussende Faktoren gibt, die potentiell selbst neue (Problem-)Faktoren erzeugen können.

Wir also für ein komplexes Problem eine vermeintliche Kausalkette beobachtet, so kann sich diese bei der nächsten Beobachtung unvorhersehbar verändern. Eine Analyse mit der 5-Why-Methode, deren erfolgreiche Anwendung von festen Kausalketten abhängig ist, kann hier also nicht zweckmäßig sein.

## Warum-Fragen schaffen Problemträger

„Warum” zu fragen führt uns rein sprachlich schnell auf Abwege. „Warum machst du das?” „Das mache ich, weil…” Damit landen wir schnell in einer Situation, in der wir uns plötzlich verteidigen und rechtfertigen müssen. Der Gefragte fühlt sich als Problemträger adressiert. Keine gute Grundlage, um Problemlösungen anzugehen, geschweige denn kreativ und kollaborativ.

Eine besseres Fragewort wäre „Wofür”. „Wofür machst du das?” „Ich mache das, damit…” Zwar zielt das „Wofür” ebenfalls auf das Verhalten der Person ab, wird aber durch den Fokus auf den Zweck bzw. das Ergebnis (das „Damit”) entpersonalisiert. Durch den fehlenden Problemträger wird auch das vermeintliche Problem entpersonalisiert. Eine gute Grundlage, um auf der Faktenbasis (statt auf der Beziehungsbasis) an der Problemlösung zu arbeiten.

## Warum-Fragen führen auf Umwege oder nirgendwohin

Warum-Fragen führen auf unnötige Umwege und sind nicht ergebnisorientiert. Sie lassen uns immer weiter in den Problemraum abdriften. Emotionen und (unterschwellige) Schuldzuweisungen nehmen zu. Das kostet viel Zeit, Energie und Motivation.

Stattdessen sollte vom eigentlich gewünschten Ergebnis aus gedacht werden: „Was wollen wir stattdessen?” oder „Wofür brauchen/wollen/machen wir das?” Das folgt dem Lean-Prinzip, Arbeitsweisen vom Ergebnis (Outcome) aus zu denken und zu verbessern. Problemwissen, das für die Lösung notwendig ist, wird ganz von allein aufkommen. Wichtig: Nicht wieder zu sehr in den Problemraum abdriften lassen. Ein Coach oder Facilitator kann (insbesondere bei Gruppen oder Teams) diesen Prozess unterstützen.

## Unterschiedliche Perspektiven erlauben, erkennen und nutzen

Beim ersten Beispiel mit dem nicht startenden Auto könnten wir mit mehreren Kfz-Experten die 5-Why durchgehen, sie würden in der Mehrheit zum selben Schluss kommen. Geht es aber um das Projekt-Beispiel, bei dem menschliches Verhalten involviert ist, könnten wir mehrere Personen fragen: Es kommt fast immer etwas anderes dabei heraus.

Das Beispiel des Projekts, dessen Fertigstellungstermin nicht eingehalten wurde, zeigt, dass es mehrere Perspektiven gibt, aus der die Situation betrachtet werden kann. Der Guardian hat 1986 eine Werbung geschaltet, die das wunderbar verbildlicht:

<center>
  <style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style>
  <p>
    <div class='embed-container'>
      <iframe src='https://www.youtube.com/embed/rjPUZIeeepQ' frameborder='0' allowfullscreen></iframe>
    </div>
  </p>
</center>

Bei der Bearbeitung komplexer Probleme muss also allen Beteiligten bewusst sein, dass:

- Jeder das Problem anders wahrgenommen hat und in seiner „eigenen Realität” lebt
- Informationen unter den Beteiligten asymmetrisch verteilt sein können („Ich weiß nicht, was du nicht weißt”)
- Verhaltensweisen aufgrund der bisherigen Lebenserfahrungen und jetzigen Lebens- und Arbeitsumstände von außen nicht immer rational sind oder erscheinen
- Verhaltensweisen nicht auf den eigentlichen Charakter einer Person hinweisen („Ich bin ein Teil von jener Kraft, die stets das Böse will und stets das Gute schafft.”)

Für die Bildung von Vertrauen und Empathie kann das persönliche Erleben einer Situation bzw. die Schilderung des Problems von allen Beteiligten — möglichst ohne Unterbrechung und Stellungnahme anderer — geschildert werden.

Aber Vorsicht: Das Ausleuchten des Problems in der Vergangenheit kann zusätzliches Leiden verursachen und kostet Kraft, die für die Problemlösung benötigt wird. Der Fokus sollte daher nicht auf der Untersuchung des Problems liegen, sondern auf der Erarbeitung einer Lösung. Die unterschiedlichen Perspektiven können hier nützlich sein, wenn sie mit konstruktiven Fragen kombiniert werden.

## Konstruktive Fragen

Die Problemlösung kann durch konstruktive Fragen unterstützt werden:

- Was wollen wir statt dem Problem (konkret in einem bestimmten Kontext)?
- Wer kann uns dabei unterstützen?
- Welche Hindernisse gibt es?
- Was sind wir bereit, für die Lösung zu investieren?
- Was wäre ein erster Schritt, was ein zweiter?
- Wer macht was?
- Wann treffen wir uns wieder, um über die Lösung zu sprechen (und ggf. den Plan anzupassen)?

## Fazit

Wie alle Werkzeuge ist die 5-Why-Methode weder „gut” noch „schlecht”. Abhängig vom Kontext (kompliziert oder komplex) sind Warum-Fragen entweder nützlich oder unbrauchbar. Die Säge eignet sich nicht gut für das hämmern von Nägeln, auch wenn es der ein oder andere vielleicht doch versucht. Es muss also klar werden: Was habe ich vor mir? Einen Nagel oder ein Stück Holz? Kompliziert oder komplex? Dann wähle ich das passende Werkzeug.
