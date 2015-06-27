<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#sec-1">1. Relevante Themen</a>
<ul>
<li><a href="#sec-1-1">1.1. Qualitätssicherung</a>
<ul>
<li><a href="#sec-1-1-1">1.1.1. Aufgaben eines Qualitätsbeauftragten</a></li>
<li><a href="#sec-1-1-2">1.1.2. Kategorien der Qualitätssicherungsmaßnahmen</a></li>
<li><a href="#sec-1-1-3">1.1.3. Reviewsitzung</a></li>
<li><a href="#sec-1-1-4">1.1.4. Continuous Integration</a></li>
<li><a href="#sec-1-1-5">1.1.5. Tests</a></li>
</ul>
</li>
<li><a href="#sec-1-2">1.2. SCRUM-Überblicksmodell</a></li>
<li><a href="#sec-1-3">1.3. Projektplanung</a>
<ul>
<li><a href="#sec-1-3-1">1.3.1. Aufgaben des Projektleiters</a></li>
<li><a href="#sec-1-3-2">1.3.2. Aufgabenpakete - Eigenschaften</a></li>
<li><a href="#sec-1-3-3">1.3.3. Fertigstellungsgrad</a></li>
<li><a href="#sec-1-3-4">1.3.4. Meilensteine</a></li>
<li><a href="#sec-1-3-5">1.3.5. Schätzverfahren</a></li>
<li><a href="#sec-1-3-6">1.3.6. Projektphasen - Aufgaben dabei (Projektleiter)</a></li>
<li><a href="#sec-1-3-7">1.3.7. Meeting</a></li>
</ul>
</li>
<li><a href="#sec-1-4">1.4. Softwareattribute?</a></li>
<li><a href="#sec-1-5">1.5. Versionsverwaltung</a>
<ul>
<li><a href="#sec-1-5-1">1.5.1. Version und Variante?</a></li>
</ul>
</li>
<li><a href="#sec-1-6">1.6. McCabe-Metrik?(zyklomatische Komplexität?)</a></li>
<li><a href="#sec-1-7">1.7. Meldeklassen im Change-Management</a></li>
<li><a href="#sec-1-8">1.8. Risikomanagement</a>
<ul>
<li><a href="#sec-1-8-1">1.8.1. Häufige Risiken</a></li>
<li><a href="#sec-1-8-2">1.8.2. Aufgaben im Risiskomanagement</a></li>
</ul>
</li>
</ul>
</li>
</ul>
</div>
</div>


# Relevante Themen<a id="sec-1" name="sec-1"></a>

## Qualitätssicherung<a id="sec-1-1" name="sec-1-1"></a>

### Aufgaben eines Qualitätsbeauftragten<a id="sec-1-1-1" name="sec-1-1-1"></a>

### Kategorien der Qualitätssicherungsmaßnahmen<a id="sec-1-1-2" name="sec-1-1-2"></a>

### Reviewsitzung<a id="sec-1-1-3" name="sec-1-1-3"></a>

### Continuous Integration<a id="sec-1-1-4" name="sec-1-1-4"></a>

### Tests<a id="sec-1-1-5" name="sec-1-1-5"></a>

1.  Glas-Box-Tests

    -   PoC - Point of Control - Einfügen der Daten in die zu testende Funktion
    -   PoO - Point of Observation - Überprüfung des Outputs of Korrektheit
    -   PoC und PoO innen
        Direkter Eingriff in Code
        Testdaten aus Struktur
        Im Prinzip: alle Stufen
        •
        Aber: zu viele TF außer bei Unit
    -   Anweisungsüberdeckung (Kontrollflussgraph)
    -   Zweigüberdeckung
    -   Bedingungsüberdeckung
    -   Pfadüberdeckung(u.A. Berücksichtigung aller möglichen Anzahlen von Schleifendurchläufen)

2.  Black-Box-Tests

    -   PoC und PoO außen
        Keine Info über Inneres
        Testdaten aus Requirements
        Alle Teststufen
    -   Testfall - Auswahlkriterien
        -   Funktionsüberdeckung
        -   Eingabeüberdeckung
        -   Ausgabeüberdeckung
    -   Testfallermittlung
        -   Äquivalenzklassen (2 < n <= 5 führt zu Ergebnis x)
        -   Grenzwertüberprüfung (2, 3, 5, 6 für obiges Beispiel z.B.)
        -   Entscheidungstabellen / Ursache-Wirkungsgraphen
        -   Zustandsbasierter Test (Zustandsautomaten)
        -   Anwendungsfallbasierter Test (Use Cases prüfen)

## SCRUM-Überblicksmodell<a id="sec-1-2" name="sec-1-2"></a>

## Projektplanung<a id="sec-1-3" name="sec-1-3"></a>

Definition:

-   begrenzt: zeitlich, finanziell, personell, Anforderungen
-   eindeutige Ziele
-   individuell: keine Routine
-   hat einen oder mehrere Abnehmer
-   verbindet Menschen, Hilfsmittel/Resourcen und Resultate/Produkte

### Aufgaben des Projektleiters<a id="sec-1-3-1" name="sec-1-3-1"></a>

### Aufgabenpakete - Eigenschaften<a id="sec-1-3-2" name="sec-1-3-2"></a>

### Fertigstellungsgrad<a id="sec-1-3-3" name="sec-1-3-3"></a>

### Meilensteine<a id="sec-1-3-4" name="sec-1-3-4"></a>

### Schätzverfahren<a id="sec-1-3-5" name="sec-1-3-5"></a>

### Projektphasen - Aufgaben dabei (Projektleiter)<a id="sec-1-3-6" name="sec-1-3-6"></a>

### Meeting<a id="sec-1-3-7" name="sec-1-3-7"></a>

1.  Ablauf

    1.  Entscheiden wer einzuladen ist.
    2.  Agenda erstellen und mind. einen Tag vorher verteilen.
    3.  Pünktlich beginnen, nicht auf jemanden warten, nicht unterbrechen
        wenn jemand eintrifft.
    4.  Protokol (währenddessen!) führen und sofort anschließend verteilen.
        Um Konflikte zu vermeiden, verkünden was ins Protokoll aufgenommen wird.
        "So haben wir das aber nicht besprochen."

2.  Action-Item-Protokolierung

    Motivation: Echte Ergebnisse eindeutig festhalten
    Fester Rahmen durch standardisierte Methode aus dem militärischen Bereich
    Mögliche Punkte:

    -   Aufforderung("Action")
        -   Umfang ist immer begrenzt und verpflichtet den Verantwortliche zum handeln
        -   erfordert immer eine Zustimmung des Betroffenen
        -   Dauer und Kosten lassen sich abschätzen
        -   Eindeutiger Endtermin zur Lösung der Aufgabe
    -   Beschluss
        -   für alle verbindlich
        -   erfordert die Einigung aller Beteiligten
        -   (Kosten und Arbeitsumfang lassen sich nicht begrenzen oder sind gleich Null)
    -   Empfehlung
        -   ausgesprochen, wenn der Betroffene nicht anwesend ist oder wenn keine Einigung möglich
        -   darf einseitig ausgesprochen werden
        -   ist nicht verplichtend
    -   Feststellung
        -   gibt Tatbestände, Sachverhalte und persönliche Sichtweisen wieder
        -   nicht verpflichtend

    Jedes Item nur als Konsensentscheidung.
    Jedes Item bekommt fortlaufende Nummerierung.
    Items die noch offen sind werden aus dem alten Protokol ins neue Protokol übertragen.

## Softwareattribute?<a id="sec-1-4" name="sec-1-4"></a>

## Versionsverwaltung<a id="sec-1-5" name="sec-1-5"></a>

### Version und Variante?<a id="sec-1-5-1" name="sec-1-5-1"></a>

## McCabe-Metrik?(zyklomatische Komplexität?)<a id="sec-1-6" name="sec-1-6"></a>

## Meldeklassen im Change-Management<a id="sec-1-7" name="sec-1-7"></a>

## Risikomanagement<a id="sec-1-8" name="sec-1-8"></a>

### Häufige Risiken<a id="sec-1-8-1" name="sec-1-8-1"></a>

### Aufgaben im Risiskomanagement<a id="sec-1-8-2" name="sec-1-8-2"></a>