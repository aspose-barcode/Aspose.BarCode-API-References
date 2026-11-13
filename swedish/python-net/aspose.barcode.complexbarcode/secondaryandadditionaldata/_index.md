---
title: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode för Python via .NET API-referens"
description: 
type: docs
url: /sv/python-net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

Klass för lagring av HIBC LIC‑sekundär‑ och tilläggsdata.

Typen SecondaryAndAdditionalData exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| SecondaryAndAdditionalData() | Initierar en ny instans av klassen SecondaryAndAdditionalData |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| expiry_date_format | Identifierar utgångsdatumsformat. |
| expiry_date | Identifierar utgångsdatum. Kommer att användas om ExpiryDateFormat inte är satt till None. |
| lot_number | Identifierar parti- eller batchnummer. Parti-/batchnummer måste vara en alfanumerisk sträng med upp till 18 tecken längd. . |
| serial_number | Identifierar serienummer. Serienummer måste vara en alfanumerisk sträng med upp till 18 tecken längd. |
| date_of_manufacture | Identifierar tillverkningsdatum.<br/>            Tillverkningsdatum kan sättas till DateTime.MinValue för att inte använda detta fält.<br/>            Standardvärde: DateTime.MinValue |
| quantity | Identifierar kvantitet, måste vara ett heltal mellan 0 och 500. <br/>            Kvantitet kan sättas till -1 för att inte använda detta fält.<br/>            Standardvärde: -1 |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| parse_from_string(secondary_data_codetext) | Instansierar sekundär och ytterligare kompletterande data från strängformat enligt HIBC LIC-specifikationen. |

### Se även

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

