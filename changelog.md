# Deutsch
## 2021.6
### Features
#### Allgemein
![PWA Logo](./img/pwa.svg)
- Unsere neue Progressive Web App ist jetzt für alle Kunden verfügbar
- Alle Mailtemplates enthalten nun die Links auf unsere Progressive Web App
- MOBIKO unterstützt nun auch Spanien und Portugal als Zielländer mit Individualversteuerung

#### Externe Benefits:
- "Tankkarte" ist als externer Benefit hinzugefügt worden

#### Progressive Web App (PWA) vs. Native App
- Währungen, Sprachen und Zeitzonen sind nun per Textsuche auffindbar
- Die Bildvorschau kann nun auf Originalgröße vergrößert werden (double-tap)
- Die Optik und Usability der "Gutscheine und Vorteile" wurde verbessert

### Bugfixes
#### Allgemein
- Budgetgruppen in der Useransicht werden nun nach Betrag sortiert
- das Datumsformat entspricht nun der Sprache des Users
- Exporte duplizieren nun keine Zeilen mehr, wenn Exporte mehrfach schnell hintereinander ausgelöst werden
- die "Externe Benefit"-Berechnung für vergangene Monate berücksichtigt nun die Historie
- in den Benutzerdetails kann man nun wieder Informationen in die Zwischenablage kopieren
- in den Benutzerdetails wird die Externer Benefit Beschreibung nun nur noch einmal angezeigt
- in der Belegprüfung wurde eine fehlende Lokalisierung ergänzt
- man kann nun wieder Administratoren über die Benutzerverwaltung anlegen
- man kann nun wieder User in der Zukunft einladen


### Änderungen
#### Allgemein:
- "Geplant"-Tabs in der Useransicht werden nun der Übersichtlichkeit halber ausgeblendet, wenn sie keine Einträge haben
- Wenn Einladungen / Deaktivierungen / Reaktivierungen geplant werden, scrollt die Ansicht der Einfachheit halber nun automatisch zum Ende der Seite

## 2021.5
### Hinweis
Die Versionsnummer orientiert sich nun an dem monatlichen Release-Zyklus (z.B. 2021.5 für Mai 2021)

### Features
#### Allgemein:
- Der Bereich "Nutzer" verwendet nun eine neue Technologie
- die Userliste verwendet nun eine Paginierung um die Benutzererfahrung zu verbessern
- die Userliste kann nun gefiltert werden
- die Budgetklassen können nun per Massenaktion geändert werden
- ein "External Benefit" kann nun konfiguriert werden, um bereits vorhandene Ausgaben vom MOBIKO-Budget abzuziehen
- Geplante Änderungen (Einladungen / Dekativierungen / Reaktivierungen) haben nun einen eigenen Tab
- beim VEDA Export wurde "Korr.Monat" und "Korr.Jahr" in ein Feld "Korr.Monat" zusammengefasst
- Checkboxen und Radioboxen haben ein hübscheres Design erhalten
- die Webapplikation hat nun einen Link ins FAQ

#### Datenschutz:
- das Firebase-Tracking wurde aus der Webapplikation entfernt
- der Onboarding-Dialog zur Datenschutzerklärung wurde entfernt

#### Neue Ablehngründe in der Belegprüfung:
- "Leider ist kein Rechnungsdatum auf dem Beleg ersichtlich"
- "Leider ist kein Preis auf dem Beleg ersichtlich"

#### Der MOBIKO Import 2.0 ist jetzt verfügbar:
- der Import kann nun auch vorhandene Einträge ändern
- der Import hat nun ein Log, dass die Transaktionen und den Verlauf anzeigt
- Importe ignorieren nun (sofern möglich) fehlerhafte Leerzeichen und Zeilenumbrüche

### Änderungen
- E-Mails werden nun via no-reply@mobiko.de versendet

### Bugfixes
- einige fehlende Lokalisierungen wurden hinzugefügt
- wenn das Passwort geändert wird, zeigt der Hinweis nun die Anzahl der benötigten Zeichen korrekt an
- die Steuerinformationen in der App sind nun farbkodiert

## 6.3.0
### Features
#### Datenschutz:
- locize wurde durch Übersetzungen im Produkt ersetzt
- bugsnag wurde durch einen internen Buganalyse-Mechanismus ersetzt
- alle Mails werden nun über einen MOBIKO-eigenen Server verschickt

### Bugfixes
- alle Umrechnungskurse kommen nun direkt von der europäischen Zentralbank
## 6.2.3
### Features
- MOBIKO unterstützt nun [VEDA](https://www.veda.net/software/veda-hr-entgelt/) als Lohnbuchhaltungssystem
- DATEV LODAS und DATEV Lohn und Gehalt unterstützen nun die Erstattung via Nachberechnungsfunktion

## 6.1.5
### Bugfixes
- Mobilitätstypen werden im Bereich Belegprüfung nun korrekt Privat- und Firmenfahrten zugeordnet

## 6.1.4
### Features
- Reseller können nun eigene E-Mail-Templates erhalten
- Mailchimp wurde durch einen internen E-Mail-Prozess ersetzt (Datenschutzverbesserung)
- Bilder in Mails verweisen nun auf MOBIKO-gehostete Bilder (Datenschutzverbesserung)
- ein neues Feld "Weiteres Abrechnungsmerkmal" ermöglicht nun Zusatzinformationen in den Steuerexporten
- der LOGA-Export verwendet das Feld "Weiteres Abrechnungsmerkmal" nun für die Vertragsnumemr

### Bugfixes
#### Allgemein
- die Zuverlässigkeit zeitgesteuerter Aktionen wurde erhöht
### Mobile App
- der Upload von Bild- und PDF-Dateien funktioniert nun auch unter der aktuellsten Android-Version
- sporadisch konnte es vorkommen, dass die Zugangsdaten während des Logins verloren gingen. Dies wurde behoben.

# Englisch
## 2021.6
### Features
#### General
![PWA Logo](./img/pwa.svg)
- our new Progressive Web App is now available for all customers
- all mail templates now contain the links to our Progressive Web App
- MOBIKO now supports Spain and Portugal as target countries with individual taxation

#### Externe Benefits:
- "Fuel Card" was added as external benefit type

#### Progressive Web App (PWA) vs. Native App
- Currencies, languages and timezones are now searchable via text search
- the picture preview can now be extended to original picture size (double tap)
- the user interface and usability of "Deals and Vouchers" was improved

### Bugfixes
#### General
- Budget groups in the user view are now sorted by amount
- the date format is now respecting the users language
- Exports no longer duplicate lines, when they are executed multiple times while they are in progress
- the "External Benefit"-calculation now respects the history of previous months
- it's now possible again to copy information from the user details dialog
- the "External Benefit" description is now only shown once in the user view
- a missing localization was added into the expense checking view
- Administrators can now be created again via user management
- users can now be scheduled for invitation again

## 2021.5
### Please note
The version number now reflects monthly releases (e.g. 2021.5 is for May 2021)

### Features
#### General
- User list with new technology
- the user list now has pagination to enhance UI
- the user list can now be filtered
- budget classes can now be bulk-changed from the user list
- External Benefit can now be configured to deduct the monthly budget
- scheduled invitations / deactivations / reactivations now have an own tab
- VEDA Export: Korr.Monat and Korr.Jahr combined into one field
- checkboxes and radio boxes now have better visuals
- the web application now has a link to the FAQ

#### Data Privacy:
- the tracking from firebase was removed in the web application
- the onboarding data privacy dialog was removed

#### New Rejection reasons:
- no invoice date on receipt
- no price stated on receipt

#### The MOBIKO import 2.0 was introduced:
- the import can now modify existing entries
- the import now has a log about the executed transactions
- imports now ignore unnecessary line breaks that could lead to wrong data in the database

### Changes
- Mails are now send via no-reply@mobiko.de

### Bugfixes
- some missing localizations were added
- when changing the password, the hint now correctly shows how many characters are needed
- the taxation in web apps are now color-coded

## 6.3.0
### Features
#### Data Privacy:
- locize is now replaced by in-product-translations
- bugsnag is now replaced by an internal bug report mechanism
- all mails are now sent by an internal mail server

### Bugfixes
- all exchange rates are now retrieved from the european central bank

## 6.2.3
### Features
- MOBIKO now supports [VEDA](https://www.veda.net/software/veda-hr-entgelt/) as target payroll system
- "DATEV LODAS" and "DATEV Lohn und Gehalt" are now supporting the recalculation functionality

## 6.1.5
### General
- Mobility types are now correctly assigned to private / commute trips in the expense checking view

## 6.1.4
### Features
- Reseller are now able to get their own email branding
- E-Mails are now sent by the product rather than Mailchimp (increase of data privacy)
- Images in mail templates are now hosted by MOBIKO (increase of data privacy)
- a new Field "Additional salary property" now makes it possible to print out additional information in tax exports
- the LOGA-Export now uses the field "Additional salary property" for the contract number

### Bugfixes
#### General
- the reliability of time-based actions was increased
#### Mobile
- the upload of pictures and PDF-files is now also compatible with the latest android version
- the login screen sporadically lost the entered credentials on login. This was now fixed.
