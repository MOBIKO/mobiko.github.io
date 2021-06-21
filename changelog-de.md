# 2021.6
## Features
### Allgemein
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