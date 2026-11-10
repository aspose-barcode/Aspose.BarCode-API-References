---
title: "Klasse SecondaryAndAdditionalData"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.ComplexBarcode.SecondaryAndAdditionalData Klasse. Klasse zum Speichern von sekundären und zusätzlichen HIBC LIC Daten"
type: docs
weight: 770
url: /de/net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class

Klasse zum Speichern von HIBC‑LIC‑Sekundär‑ und Zusatzdaten.

```csharp
public class SecondaryAndAdditionalData
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SecondaryAndAdditionalData](secondaryandadditionaldata/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DateOfManufacture](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/dateofmanufacture/) { get; set; } | Identifiziert das Herstellungsdatum. Das Herstellungsdatum kann auf DateTime.MinValue gesetzt werden, um dieses Feld nicht zu verwenden. Standardwert: DateTime.MinValue |
| [ExpiryDate](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydate/) { get; set; } | Identifiziert das Ablaufdatum. Wird verwendet, wenn ExpiryDateFormat nicht auf None gesetzt ist. |
| [ExpiryDateFormat](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydateformat/) { get; set; } | Identifiziert das Ablaufdatumsformat. |
| [LotNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/lotnumber/) { get; set; } | Identifiziert Los- oder Chargennummer. Los-/Chargennummer muss eine alphanumerische Zeichenkette mit bis zu 18 Symbolen sein. |
| [Quantity](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/quantity/) { get; set; } | Identifiziert die Menge, muss ein ganzzahliger Wert von 0 bis 500 sein. Menge kann auf -1 gesetzt werden, um dieses Feld nicht zu verwenden. Standardwert: -1 |
| [SerialNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/serialnumber/) { get; set; } | Identifiziert die Seriennummer. Seriennummer muss eine alphanumerische Zeichenkette mit bis zu 18 Symbolen sein. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/equals/)(object) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `SecondaryAndAdditionalData`‑Wert entspricht. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/gethashcode/)() | Gibt den Hash‑Code für diese Instanz zurück. |
| [ParseFromString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/parsefromstring/)(string) | Instanziert sekundäre und zusätzliche Ergänzungsdaten aus dem Zeichenkettenformat gemäß HIBC LIC‑Spezifikation. |
| override [ToString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/tostring/)() | Konvertiert Daten in das Zeichenkettenformat gemäß HIBC LIC‑Spezifikation. |

### Siehe auch

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


