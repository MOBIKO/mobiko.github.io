# 2021.7.0
## Features
### General
- logos in the partner section are now always in rectangle shape with rounded corners
- the partner deals can now have a describing category (e.g. Carsharing etc.)
- the partner section now tells the user, that they might not be eligible for reimbursement for some deals, but they can still use them
### External Benefits
- the order of the fields in the external benefit section of the user administration was enhanced
- now you can explicitly choose, wether or not you want to grant an external benefit
- the information for external benefits can now be imported
- external benefits can now be configured, if they should be granted **on top of** or by **deducting** the mobility budget
- "Laden, pauschaler Auslagenersatz Firmenwagen" is a new, tax relevant external benefit type
- "BahnCard" is a new external benefit type
- for "Jobticket" and "Laden, pauschaler Auslagenersatz Firmenwagen" it's now possible to add a salary type for exports
- the fields "Description" and "Employer costs" are now mandatory
- if a salary type is given, the export will now respect the external benefit
- if "SAP" is configured as company export type, you can additionally provide an INFTY number

## Bugfixes
### General
- tax exports for DATEV now behave the same for Mac and Windows

### PWA
- you can now also enter amounts with decimal places on Samsung phones

# 2021.6.1
## Features
### General
- a new partner deal will appear on the 01.07.2021
- the categories "E-Charging" and "E-Leasing" were added

## Bugfixes
### PWA
- partner links now all have the same size
- the image preview has now applied the dark theme in dark mode
- the PDF-Preview does now also work for uploaded PDFs
- the "used" budget amount can no longer become large than the users budget
- the status "checked" is now visualized in the PWA
- all deals now spell MOBIKO in uppercase
### Web
- the status "invoiced" is now visualized in web

# 2021.6
## Features
### General
![PWA Logo](./img/pwa.png)

- our new Progressive Web App is now available for all customers
- all mail templates now contain the links to our Progressive Web App
- MOBIKO now supports Spain and Portugal as target countries with individual taxation

### External Benefits:
- "Fuel Card" was added as external benefit type

### Progressive Web App (PWA) vs. Native App
- Currencies, languages and timezones are now searchable via text search
- the picture preview can now be extended to original picture size (double tap)
- the user interface and usability of "Deals and Vouchers" was improved

## Bugfixes
### General
- Budget groups in the user view are now sorted by amount
- the date format is now respecting the users language
- Exports no longer duplicate lines, when they are executed multiple times while they are in progress
- the "External Benefit"-calculation now respects the history of previous months
- it's now possible again to copy information from the user details dialog
- the "External Benefit" description is now only shown once in the user view
- a missing localization was added into the expense checking view
- Administrators can now be created again via user management
- users can now be scheduled for invitation again

# 2021.5
## Please note
The version number now reflects monthly releases (e.g. 2021.5 is for May 2021)

## Features
### General
- User list with new technology
- the user list now has pagination to enhance UI
- the user list can now be filtered
- budget classes can now be bulk-changed from the user list
- External Benefit can now be configured to deduct the monthly budget
- scheduled invitations / deactivations / reactivations now have an own tab
- VEDA Export: Korr.Monat and Korr.Jahr combined into one field
- checkboxes and radio boxes now have better visuals
- the web application now has a link to the FAQ

### Data Privacy:
- the tracking from firebase was removed in the web application
- the onboarding data privacy dialog was removed

### New Rejection reasons:
- no invoice date on receipt
- no price stated on receipt

### The MOBIKO import 2.0 was introduced:
- the import can now modify existing entries
- the import now has a log about the executed transactions
- imports now ignore unnecessary line breaks that could lead to wrong data in the database

## Changes
- Mails are now send via no-reply@mobiko.de

## Bugfixes
- some missing localizations were added
- when changing the password, the hint now correctly shows how many characters are needed
- the taxation in web apps are now color-coded

# 6.3.0
## Features
### Data Privacy:
- locize is now replaced by in-product-translations
- bugsnag is now replaced by an internal bug report mechanism
- all mails are now sent by an internal mail server

## Bugfixes
- all exchange rates are now retrieved from the european central bank

# 6.2.3
## Features
- MOBIKO now supports [VEDA](https://www.veda.net/software/veda-hr-entgelt/) as target payroll system
- "DATEV LODAS" and "DATEV Lohn und Gehalt" are now supporting the recalculation functionality

# 6.1.5
## General
- Mobility types are now correctly assigned to private / commute trips in the expense checking view

# 6.1.4
## Features
- Reseller are now able to get their own email branding
- E-Mails are now sent by the product rather than Mailchimp (increase of data privacy)
- Images in mail templates are now hosted by MOBIKO (increase of data privacy)
- a new Field "Additional salary property" now makes it possible to print out additional information in tax exports
- the LOGA-Export now uses the field "Additional salary property" for the contract number

## Bugfixes
### General
- the reliability of time-based actions was increased

### Mobile App
- the upload of pictures and PDF-files is now also compatible with the latest android version
- the login screen sporadically lost the entered credentials on login. This was now fixed.
