# TimeManagement
Waterfall software engineering project

**Requirements**
	Monatliche Zeiterfassung 
	Welche Tage arbeiten sie
	Feste Mitarbeiter 38h, 30 Tage Urlaub. Ab 2 Jahre Zusatzurlaub
	Überstunden beantragen max. 10 Überstunden im Monat, nicht mehr als 100h. 6-21h
	Überstunden werden als Urlaub "ausbezahlt"
	8h -> 60min Pause !bezahlt!. Einzeln ausstechen -> Rauchen, Frühstück
	Ab 3 Tage Bescheinigung
	Home Office muss eingetragen werden. Max 2 Tage die Woche

# 1. Einleitung
## 1.1 Ziel des Systems

Das System soll eine umfassende, regelbasierte Zeiterfassung für feste Mitarbeitende ermöglichen. 
Es soll die Arbeitszeiten, Überstunden, Urlaubsansprüche sowie Home-Office-Tage erfassen und verwalten.

## 1.2 Zielgruppe

Das System richtet sich an Mitarbeitende und das Personalwesen (HR) eines Unternehmens mit festen Arbeitszeitregelungen und 
einer Home-Office-Policy.

# 2. Funktionale Anforderungen
## 2.1 Zeiterfassung

Mitarbeitende müssen ihre täglichen Arbeitszeiten erfassen können.

Es muss erkennbar sein, an welchen Tagen gearbeitet wurde.

Es wird eine monatliche Übersicht der erfassten Arbeitszeiten bereitgestellt.

## 2.2 Arbeitszeitregelung für feste Mitarbeitende

Feste Mitarbeitende haben eine vertraglich geregelte Wochenarbeitszeit von 38 Stunden.

Der jährliche Urlaubsanspruch beträgt 30 Tage.

Ab dem zweiten Beschäftigungsjahr erhalten Mitarbeitende Zusatzurlaub (Anzahl der Tage wird gesondert definiert).

## 2.3 Überstundenregelung

Überstunden müssen beantragt und genehmigt werden.

Pro Monat dürfen maximal 10 Überstunden erfasst werden.

Es dürfen insgesamt nicht mehr als 100 Überstunden angesammelt werden.

Überstunden dürfen nur im Zeitraum zwischen 06:00 und 21:00 Uhr geleistet werden.

Überstunden werden nicht ausbezahlt, sondern in Form von zusätzlichem Urlaub gewährt.

## 2.4 Pausenregelung

Bei einer Tagesarbeitszeit von 8 Stunden ist eine 60-minütige Pause verpflichtend, die nicht bezahlt wird.

Mitarbeitende können zusätzliche kurze Pausen einzeln ausstechen, z. B. für Raucherpausen oder Frühstück.

## 2.5 Krankmeldung

Bei Krankheit ist ab dem 3. Krankheitstag eine ärztliche Bescheinigung erforderlich.

Die Bescheinigung muss im System hochgeladen werden können.

## 2.6 Home Office

Mitarbeitende dürfen maximal zwei Tage pro Woche im Home Office arbeiten.

Home-Office-Tage müssen vorab im System eingetragen werden.

## 3. Nicht-funktionale Anforderungen

Das System muss eine deutsche Benutzungseroberfläche bieten.

Die Benutzeroberfläche soll intuitiv und leicht bedienbar sein.

Zugriffsschutz durch Benutzerauthentifizierung (z. B. Passwort)

Einhaltung des Arbeitszeitgesetz (ArbZG)

## 4. Annahmen und Einschränkungen

Die genaue Anzahl der Zusatzurlaubstage nach zwei Jahren wird separat vom HR definiert.

Die Genehmigungsprozesse (z. B. für Überstunden) werden manuell durch HR oder Vorgesetzte durchgeführt, sofern nicht anders spezifiziert.
