# 2021.10.0
## Features
- MOBIKO ist jetzt auch für Italien verwendbar
## Bugfixes
- Externe Benefits werden nun nicht mehr im Steuerexport ausgewiesen, sofern sie keine Lohnart hinterlegt haben

# 2021.9.2
## Features
### Allgemein
- es ist nun möglich, sich mit einem privaten oder geschäftlichen Microsoft-Konto anzumelden, sofern man mit der gleichen E-Mail-Adresse für MOBIKO registriert ist
- es ist nun möglich, die Anmeldung per externer Authentifizierung (Single Sign-On, aktuell nur Microsoft) für Benutzer zu erzwingen
- das Wording der Datenschutzerklärung wurde vereinfacht

### Web
#### Externe Benefits
- es gibt nun eine Erläuterung zur Angabe von jährlichen Ausgaben

#### Importe
- das "Beispiel Template" heißt jetzt "Muster-Importdatei"
- es gibt nun eine Kurzanleitung zur Bedienung der Importe
- die Felder "Company Mobility..." wurden zur Verdeutlichung in "External Benefit..." umbenannt
- es ist nun möglich, Rollen per Import zu vergeben
- es ist nun möglich, die Budgetgruppe per Import anzugeben
- es ist nun möglich, eine Einladung für neue oder User im Status "Erstellt" zu planen
- es ist nun möglich, die Deaktivierung von Usern im Status "aktiv" zu planen
- Spaltennamen enthalten nun Hinweise zur Benutzung (z.B. Datumsformat, x zum aktivieren etc.)

#### Exporte
- es gibt nun eine neue Version des SAGE-Exports für die Schweiz
- es gibt nun einen neuen Export "KIDICAP für Angestellte"
- es gibt nun einen neuen Export "KIDICAP für Beamte"
- für SAGE Spanien ist es nun möglich, die Mandanten-Id per "Weiteres Abrechnungsmerkmal" pro User anzugeben

#### User-Ansicht
- der Status ist nun in der "Alle"-Ansicht filterbar
- die User-Ansicht zeigt nun an, ob Single Sign-On für User erzwungen wird
- das Feld "Nur Single Sign-On" kann nun gefiltert werden
- es existiert nun ein Icon zum kopieren der E-Mail-Adresse in die Zwischenablage (User-Detailansicht)
- es existiert nun ein Icon zum kopieren der Budgetklasse in die Zwischenablage (User-Detailansicht)

# 2021.9.1
## Features
### Web
- die Einschränkung "MOBIKO-Mailadresse" wurde für Supportuser entfernt

## Bugfixes
### Exporte
- DATEV Lohn und Gehalt-Exporte enthalten nun nur noch die Felder, die dafür bestimmt sind


# 2021.9.0
## Features
### Server
- SAGE für Spanien wurde als neuer Export-Typ hinzugefügt

## Verschiedenes
- alle Exporte haben ein weiteres Sicherheitsnetz durch einen weiteren Typ automatisierter Tests erhalten
- es wurden Vorbereitungen für ein neues Authentifizierungskonzept implementiert

# 2021.8.0
## Features
### Web
- Admins können nun einen CSV-Export von der Usertabelle inklusive gerader aktiver Filter ziehen

## Bugfixes
### PWA
- die Fremdwährungsangaben zeigen nun die Fremdwährung statt Euro an
- das Budgetübertrags-Ablaufdatum ist nun korrekt
- der Partner-Disclaimer ist nun auch im Darkmode lesbar
- die Steuerinformationen werden nun auch in der PWA ausgeblendet, wenn dies konfiguriert ist

### Web
- Budgetgruppen sind nun beim Editieren von usern kein Pflichtfeld mehr
- man kann nun wieder die zusätzlichen Gehaltsmerkmale administrieren


# 2021.7.2
## Features
### PWA
- Users werden nun darauf hingewiesen, den default-browser zum onboarding (Safari unter iOS, Chrome unter Android) zu verwenden

## Bugfixes
### Allgemein
- SAP und VEDA-Exporte berücksichtigen nun wieder die eingestellte Lohnart

# 2021.7.1
## Bugfixes
### Allgemein
- die Reseller-Erkennung funktioniert nun wieder

# 2021.7.0
## Features
### Allgemein
- die Logos in der Partnersektion sind nun immer rechteckig mit abgerundeten Ecken
- die Partner-Deals können nun eine beschreibende Kategorie (z.B. Carsharing etc.) erhalten
- die Partner-Sektion weist nun darauf hin, dass man je nach Arbeitgeberkonfiguration nicht alle Ausgaben einreichen kann
### Externe Benefits
- die Anordnung des externen Benefits in der Useradministration wurde verbessert
- man kann nun deutlich auswählen, wenn man keinen externen Benefit gewähren möchte
- die Informationen zu externen Benefits können nun importiert werden
- externe Benefits können nun als **zusätzlich** und **abzüglich** konfiguriert werden
- "Laden, pauschaler Auslagenersatz Firmenwagen" ist ein neuer, steuerrelevanter Typ für externe Benefits
- BahnCard ist als neuer Typ hinzugekommen
- bei Jobticket und "Laden, pauschaler Auslagenersatz Firmenwagen" kann man nun eine Lohnart hinterlegen
- die Felder Beschreibung und Arbeitgeberkosten sind nun Pflichtfelder
- sofern eine Lohnart hinterlegt ist, wird dieser nun im Export entsprechend ausgewiesen ausgewiesen
- sofern "SAP" als Lohnbuchhaltungssystem konfiguriert ist, kann man nun auch die INFTY-Nummer konfigurieren

## Bugfixes
### Allgemein
- Steuerexporte für DATEV verhalten sich nun auf Mac und Windows identisch
### PWA
- man kann nun auch mit Samsung-Tastaturen einen Betrag mit Dezimalstellen eingeben

# 2021.6.1
## Features
### Allgemein
- ein neuer Partner deal erscheint zum 01.07.2021
- Die Kategorien "E-Laden" und "E-Leasing" wurden hinzugefügt

## Bugfixes
### PWA
- die Partner Links haben nun immer alle die gleiche Größe
- die Bildvorschau ist nun im dark mode dunkel
- die PDF-Vorschau funktioniert nun auch bei hochgeladenen PDFs
- der "benutzte" Budgetbetrag steigt nun nicht mehr über das eigentliche Budget
- der Status "geprüft" wird nun in der PWA visualisiert
- alle Deals schreiben MOBIKO nun groß
### Web
- der Status "abgerechnet" wird nun in der Webansicht visualisiert

# 2021.6
## Features
### Allgemein
![PWA Logo](./img/pwa.png)

- Unsere neue Progressive Web App ist jetzt für alle Kunden verfügbar
- Alle Mailtemplates enthalten nun die Links auf unsere Progressive Web App
- MOBIKO unterstützt nun auch Spanien und Portugal als Zielländer mit Individualversteuerung

### Externe Benefits:
- "Tankkarte" ist als externer Benefit hinzugefügt worden

### Progressive Web App (PWA) vs. Native App
- Währungen, Sprachen und Zeitzonen sind nun per Textsuche auffindbar
- Die Bildvorschau kann nun auf Originalgröße vergrößert werden (double-tap)
- Die Optik und Usability der "Gutscheine und Vorteile" wurde verbessert

## Bugfixes
### Allgemein
- Budgetgruppen in der Useransicht werden nun nach Betrag sortiert
- das Datumsformat entspricht nun der Sprache des Users
- Exporte duplizieren nun keine Zeilen mehr, wenn Exporte mehrfach schnell hintereinander ausgelöst werden
- die "Externe Benefit"-Berechnung für vergangene Monate berücksichtigt nun die Historie
- in den Benutzerdetails kann man nun wieder Informationen in die Zwischenablage kopieren
- in den Benutzerdetails wird die Externer Benefit Beschreibung nun nur noch einmal angezeigt
- in der Belegprüfung wurde eine fehlende Lokalisierung ergänzt
- man kann nun wieder Administratoren über die Benutzerverwaltung anlegen
- man kann nun wieder User in der Zukunft einladen


## Änderungen
### Allgemein:
- "Geplant"-Tabs in der Useransicht werden nun der Übersichtlichkeit halber ausgeblendet, wenn sie keine Einträge haben
- Wenn Einladungen / Deaktivierungen / Reaktivierungen geplant werden, scrollt die Ansicht der Einfachheit halber nun automatisch zum Ende der Seite

# 2021.5
## Hinweis
Die Versionsnummer orientiert sich nun an dem monatlichen Release-Zyklus (z.B. 2021.5 für Mai 2021)

## Features
### Allgemein:
- Der Bereich "Nutzer" verwendet nun eine neue Technologie
- die Userliste verwendet nun eine Paginierung um die Benutzererfahrung zu verbessern
- die Userliste kann nun gefiltert werden
- die Budgetklassen können nun per Massenaktion geändert werden
- ein "External Benefit" kann nun konfiguriert werden, um bereits vorhandene Ausgaben vom MOBIKO-Budget abzuziehen
- Geplante Änderungen (Einladungen / Dekativierungen / Reaktivierungen) haben nun einen eigenen Tab
- beim VEDA Export wurde "Korr.Monat" und "Korr.Jahr" in ein Feld "Korr.Monat" zusammengefasst
- Checkboxen und Radioboxen haben ein hübscheres Design erhalten
- die Webapplikation hat nun einen Link ins FAQ

### Datenschutz:
- das Firebase-Tracking wurde aus der Webapplikation entfernt
- der Onboarding-Dialog zur Datenschutzerklärung wurde entfernt

### Neue Ablehngründe in der Belegprüfung:
- "Leider ist kein Rechnungsdatum auf dem Beleg ersichtlich"
- "Leider ist kein Preis auf dem Beleg ersichtlich"

### Der MOBIKO Import 2.0 ist jetzt verfügbar:
- der Import kann nun auch vorhandene Einträge ändern
- der Import hat nun ein Log, dass die Transaktionen und den Verlauf anzeigt
- Importe ignorieren nun (sofern möglich) fehlerhafte Leerzeichen und Zeilenumbrüche

## Änderungen
- E-Mails werden nun via no-reply@mobiko.de versendet

## Bugfixes
- einige fehlende Lokalisierungen wurden hinzugefügt
- wenn das Passwort geändert wird, zeigt der Hinweis nun die Anzahl der benötigten Zeichen korrekt an
- die Steuerinformationen in der App sind nun farbkodiert

# 6.3.0
## Features
### Datenschutz:
- locize wurde durch Übersetzungen im Produkt ersetzt
- bugsnag wurde durch einen internen Buganalyse-Mechanismus ersetzt
- alle Mails werden nun über einen MOBIKO-eigenen Server verschickt

## Bugfixes
- alle Umrechnungskurse kommen nun direkt von der europäischen Zentralbank

# 6.2.3
## Features
- MOBIKO unterstützt nun [VEDA](https://www.veda.net/software/veda-hr-entgelt/) als Lohnbuchhaltungssystem
- DATEV LODAS und DATEV Lohn und Gehalt unterstützen nun die Erstattung via Nachberechnungsfunktion

# 6.1.5
## Bugfixes
- Mobilitätstypen werden im Bereich Belegprüfung nun korrekt Privat- und Firmenfahrten zugeordnet

# 6.1.4
## Features
- Reseller können nun eigene E-Mail-Templates erhalten
- Mailchimp wurde durch einen internen E-Mail-Prozess ersetzt (Datenschutzverbesserung)
- Bilder in Mails verweisen nun auf MOBIKO-gehostete Bilder (Datenschutzverbesserung)
- ein neues Feld "Weiteres Abrechnungsmerkmal" ermöglicht nun Zusatzinformationen in den Steuerexporten
- der LOGA-Export verwendet das Feld "Weiteres Abrechnungsmerkmal" nun für die Vertragsnumemr

## Bugfixes
### Allgemein
- die Zuverlässigkeit zeitgesteuerter Aktionen wurde erhöht

## Mobile App
- der Upload von Bild- und PDF-Dateien funktioniert nun auch unter der aktuellsten Android-Version
- sporadisch konnte es vorkommen, dass die Zugangsdaten während des Logins verloren gingen. Dies wurde behoben.