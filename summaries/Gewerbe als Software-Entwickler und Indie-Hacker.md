# Unterschied Selbstständigkeit, Freiberufler, Freelancer, Gewerbetreibender

- Selbstständigkeit: Arbeiten, die in keinem Angestelltenverhältnis passieren
  - Freiberufler ist per Definition selbstständig
  - Ein Freelancer existiert steuerrechtlich betrachtet nicht, sondern bezeichnet nur die Form der Zusammenarbeit
  - Gewerbetreibender (ohne GbR, GmbH, etc.)
  
 - Freiberufler sind in [§ 18 EStg](https://www.gesetze-im-internet.de/estg/__18.html) definiert. Software-Entwickler *können* Freiberufler sein.
 - Freelancer arbeiten nur in Projektarbeit für Kunden
 
 ## Angestelltenverhältnis und Selbstständigkeit/Gewerbe
 - Der Hauptarbeitgeber muss immer um Zustimmung gefragt werden
 - Eine Person kann sich gleichzeitig in einem Angestelltenverhältnis befinden und ein Nebengewerbe besitzen und/ode freiberuflich arbeiten

# Gewerbe / Einzelunternehmen
- Ein Gewerbeanmeldung ist nötig, sobald Produkte (E-Books, Online-Kurse, Software-Produkte, SaaS-Lösungen, Affiliates etc.) verkauft werden:
```
Eine selbständige nachhaltige Betätigung, die mit der Absicht, Gewinn zu erzielen, unternommen wird und sich als Beteiligung am allgemeinen wirtschaftlichen Verkehr darstellt, ist Gewerbebetrieb, wenn die Betätigung weder als Ausübung von Land- und Forstwirtschaft noch als Ausübung eines freien Berufs noch als eine andere selbständige Arbeit anzusehen ist.
```

## Gewerbesteuer
- Mit der Anmeldung des Gewerbes ist Gewerbesteuer zu zahlen. Diese fällt an, wenn mehr als € 24.500,00 im Jahr erwirtschaftet worden sind.
- Berechnung: (Gewinn - € 24.500,00) * 0,035 (3,5% Gewerbesteuermessbetrag) * Hebesatz (z. B. 3,6 (360%) in Wolfsburg)
- Sobald das erste Mal Gewerbesteuer bezahlt worden ist, erfolgt eine Vorauszahlung (!) quartalsweise

# Umsatzsteuer
- Muss von den meisten Berufsgruppen gezahlt werden; für Software-Entwickler oder Indie-Hacker wird dies der Fall sein
- Auf jeder Rechnung muss die Umsatzsteuer ausgewiesen werden
- Wenn die Umsatzsteuer ausgewiesen werden muss, wird die Umsatzsteueridentifikationsnummer (aka. USt-Id in Deutschland bzw. VAT-ID im EU-Inland) benötigt. Diese kann unter https://www.bzst.de/DE/Unternehmen/Identifikationsnummern/Umsatzsteuer-Identifikationsnummer/umsatzsteuer-identifikationsnummer_node.html beantragt werden. Beantragung erfolgt elektronisch und dauert ca. 2 Tage wenn das Gewerbe bereits besteht.

## Kleinunternehmerregelung 
- Freiberufler und Gewerbetreibender können die Kleinunternehmerregelung in Anspruch nehmen; Gewerbetreibende können dies bei der Gewerbeanmeldung ankreuzen
- Wenn im vorangegangenem Kalenderjahr der Gewinn € 22.000,00 und im aktuellen Kalenderjahr der Gewinn € 50.000,00 **nicht** übersteigt, wird keine Umsatzsteuer erhoben
- Die Umsatzsteuer darf dann auch **nicht** auf den Rechnungen ausgewiesen werden!
- Der Text "Gemäß % 19 Abs. 1 UStG wird keine Umsatzsteuer ausgewiesen." bzw. "Because of the small business owner state according to § 19 UStG the seller charges no sales tax, and therefore does not show it." **muss** in den Rechnungn explizit angegeben werden.
- Es kann eine Umsatzsteuer-Identifikationsnummer beantragt werden, auch wenn die Kleinunternehmerregelung greift.

## Reverse Charge-Verfahren
- Innerhalb des EU-Auslands (= alles was EU aber nicht Deutschland ist), liegt die Umsatzsteuerpflicht beim Empfänger. Dies ist das so genannte Reverse Charge-Verfahren.
- Das Reverse Charge-Verfahren kommt nur zum Einsatz, wenn der Empfänger ein Unternehmen ist, d.h. eine gültige Umsatsteuer-ID (VAT-ID) vorliegt.
- Der Hinweis `This invoice is subject to the reverse charge rule in the country of receipt.` [muss dann auf den Rechnungen zu finden sein](https://community.xero.com/business/discussion/40695317).

Folgendes gilt bei dem Verkauf **aus** Deutschland in ein anderes Land:

|Zielland|Käufer|Umsatzsteuer|Reverse Charge-Statement
|Deutschland|Privatkunde|Ja|Nein|
|Deutschland|Unternehmen|Ja|Nein|
|EU|Privatkunde|Ja|Nein|
|EU|Unternehmen|Nein|Ja|
|Außerhalb der EU|Privatkunden|Nein|Nein|
|Außerhalb der EU|Unternehmen|Nein|Nein|

Siehe dazu auch https://www.rechnungswesen-portal.de/Fachinfo/Umsatzsteuer-Anwendungsfaelle-und-Vorschriften.html für Kontierungsbeispiele. Daran lässt sich gut ableiten, wann was angegeben werden muss.

# Rechnungen

- Allgemeine Rechnungsregeln sind unter https://ec.europa.eu/taxation_customs/business/vat/eu-vat-rules-topic/vat-invoicing-rules_en zu finden
  - Vollständiger Name und Anschrift von dir
  - Vollständiger Name und Anschrift des Empfängers
  - Eindeutige Rechnungsnummer
  - Wenn vorhanden: VAT-ID des Empfängers und deine VAT-ID
  - Falls keine VAT-ID vorhanden ist, deine Steuernummer (xx/yyy/zzzzz); **nicht** die Steueridentifikationsnummer
  - Rechnungs- und Lieferdatum bzw. Hinweis `If not stated otherwise, the delivery date equals the invoice date.`
  - ggf. Reverse Charge-Hinweis
  - ggf. Hinweis Steuerbefreiung
  - ggf. etwaige Skonti
  - Auflistung der einzelnen Positionen
  - Netto-Betrag
  - Wenn Umsatzsteuer ausgwiesen wird: Brutto-Betrag und Steuersatz
  - Deine Kontodaten
- Rechnungsnummer entweder fortlaufend oder in der Form YYYYMMDD-${NUMMER_DER_RECHNUNG_AM_TAG}; diese **muss** eindeutig sein

# Impressum
siehe http://www.impressum-recht.de/impressum-inhalt.html

- Inhalt des Impressums muss Name, Vorname und E-Mail sein; die Telefonnummer ist nicht relevant
- Die Steueridentfikationsnummer hat da **nichts** zu suchen
- Bei einem Gewerbetreibenden muss - falls vorhanden - die USt.-ID angegeben werden

# Internationale Rechnungen
- Das Stellen von internationalen Rechnungen ist unter https://buchhaltungslexikon.de/lexikon/rechnung-auf-englisch/ sehr gut beschrieben. 
- Spätestens mit dem Verkauf von Produkten in die USA sollte das Steuerbüro kontaktiert werden, Stichwort W-8BEN-E (https://www.schakko.de/2019/08/15/woocommerce-fur-den-verkauf-von-b2b-software-konfigurieren/)

# Affiliates
Falls über Google AdSense, ein Affiliate-Netzwerk oder über individuellen Content Werbung geschaltet wird und daraus Einnahmen entstehen, ist Folgendes zu beachten:
1. Gewerbe anmelden, da es sich um eine Gewinnerzielungsabsicht handelt
2. Pro-Forma Rechnung an Google AdSense erstellen
3. Je nach deinem Status fällt Umsatsteuer an.

```
Die Umsatzsteuer wird nach § 3a UStG dort versteuert, wo der Leistungsempfänger seinen Sitz hat. Für deutsche Google AdSense Nutzer ist dies seit 2009 Irland, wo auch die Umsatzsteuer anfällt. Demnach sind Umsätze in Deutschland nicht steuerbar und damit nicht umsatzsteuerpflichtig.

Da beim Betreiben von Affiliate-Programmen grundsätzlich eine Gewinnerzielungsabsicht unterstellt werden kann, muss auch hier ein Gewerbe vorhanden sein. Bei Affiliate-Programmen greift die gleiche Umsatzsteuerregelung wie bei Einkünften durch Google AdSense. Befindet sich der Affiliate-Partner (also das Affiliate-Netzwerk oder der Produktanbieter) in Deutschland, sind die Einnahmen umsatzsteuerpflichtig. Ansonsten fällt die Umsatzsteuer im Land des Leistungsempfängers an.
```
von https://wirelesslife.de/steuern-digitale-nomaden/?_sf_s=adsense
