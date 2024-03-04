# Release Notes für GoogleAnalytics

## v2.1.0 (2024-04-03)

### Geändert
- Das Plugin wurde um den Consent Mode V2 erweitert. Im Standard funktioniert das Plugin mit dem Basis Modus und wird in einer zukünftigen Version erweitert.

## v2.0.2 (2023-12-04)

### Behoben
- Fehler im Zusammenhang mit dem PurchaseEvent behoben.

## v2.0.1 (2023-14-04)

### Geändert
- Cookie Einstellungen angepasst.

## v2.0.0 (2023-13-04)

### Geändert
- Die Kompatibilität zu Google Analytics 4 wurde hergestellt.

### TODO
- Diese Plugin-Version kommuniziert ausschließlich mit GA4 Properties. Prüfe daher, ob eine GA4-kompatible <a href="https://support.google.com/analytics/answer/12270356?hl=de" target="_blank">Mess-ID</a> im Format (G-XXXXX) in den Plugin-Einstellungen eingetragen wurde.
- In den Plugin-Einstellungen muss die Container-Verknüpfung **Google Analytics purchase event code** gesetzt werden.

## v1.1.4 (2022-25-07)

### Geändert
- Cookie Informationen angepasst und Hinweis zur Rechtslage hinzugefügt. 
- Flag für PHP Kompatibilität hinzugefügt. 

## v1.1.3 (2021-11-03)

### Geändert
- User Guide angepasst
- plentyShop Rebranding

## v1.1.1 (2021-03-03)

### Geändert
- Die von Google Analytics verwendeten Cookies werden jetzt per Callback Funktion registriert.

### Behoben
- Die Versandkosten werden nicht mehr als zusätzliche Artikelposition übermittelt.

## v1.1.0 (2019-12-03)
### Geändert
- Die von Google Analytics verwendeten Cookies werden an der Consent-Schnittstelle für plentyShop LTS-Shops registriert.

## v1.0.6 (2018-03-12)
### Behoben
- Aufträge werden nur noch einmalig an Google Analytics übermittelt.

## v1.0.5 (2018-07-05)
### Behoben
- Es gab einen JavaScript-Fehler. Das Verhalten wurde behoben.

## v1.0.4 (2018-06-14)
### Behoben
- Fehler beim setzten des Opt-out Cookies. Das Verhalten wurde behoben.

## v1.0.3 (2018-05-23)
### Features
- Möglichkeit zum Opt-out von GoogleAnalytics

## v1.0.2 (2018-05-11)
### Features
- Konfiguration zum Anonymsieren von IPs

## v1.0.1 (2017-10-20)
### Behoben
- Transaktionen und Artikel werden jetzt korrekt an Google Analytics übermittelt

## v1.0.0 (2017-02-24)
### Features
- Tracking für Seitenaufrufe
- Tracking von getätigten Bestellungen und gekauften Artikeln
