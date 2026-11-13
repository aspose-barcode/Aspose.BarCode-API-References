---
title: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode für Python über .NET API-Referenz"
description: 
type: docs
url: /de/python-net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

Klasse zum Speichern der sekundären und zusätzlichen HIBC LIC-Daten.

Der Typ SecondaryAndAdditionalData stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| SecondaryAndAdditionalData() | Initialisiert eine neue Instanz der Klasse SecondaryAndAdditionalData |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| expiry_date_format | Identifiziert das Ablaufdatumsformat. |
| expiry_date | Identifiziert das Ablaufdatum. Wird verwendet, wenn ExpiryDateFormat nicht auf None gesetzt ist. |
| lot_number | Identifiziert Los- oder Chargennummer. Los-/Chargennummer muss eine alphanumerische Zeichenkette mit bis zu 18 Symbolen Länge sein. . |
| serial_number | Identifiziert Seriennummer. Seriennummer muss eine alphanumerische Zeichenkette mit bis zu 18 Symbolen Länge sein. |
| date_of_manufacture | Identifiziert das Herstellungsdatum.<br/>            Das Herstellungsdatum kann auf DateTime.MinValue gesetzt werden, um dieses Feld nicht zu verwenden.<br/>            Standardwert: DateTime.MinValue |
| quantity | Identifiziert die Menge, muss ein ganzzahliger Wert von 0 bis 500 sein. <br/>            Menge kann auf -1 gesetzt werden, um dieses Feld nicht zu verwenden.<br/>            Standardwert: -1 |
## Methoden
| Name | Beschreibung |
| :- | :- |
| parse_from_string(secondary_data_codetext) | Instanziiert sekundäre und zusätzliche Ergänzungsdaten aus dem Zeichenkettenformat gemäß HIBC LIC-Spezifikation. |

### Siehe auch

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

