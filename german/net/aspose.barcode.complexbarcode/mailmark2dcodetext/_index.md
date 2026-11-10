---
title: "Klasse Mailmark2DCodetext"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.ComplexBarcode.Mailmark2DCodetext Klasse. Klasse zum Codieren und Dekodieren des in den Royal Mail 2D Mailmark-Code eingebetteten Textes"
type: docs
weight: 650
url: /de/net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class

Klasse zum Codieren und Dekodieren des in den Royal‑Mail‑2D‑Mailmark‑Code eingebetteten Textes.

```csharp
public sealed class Mailmark2DCodetext : IComplexCodetext
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Mailmark2DCodetext](mailmark2dcodetext/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmark2dcodetext/class/) { get; set; } | Identifiziert die Klasse des Elements. |
| [CustomerContent](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontent/) { get; set; } | Optionaler Platz für die Verwendung durch den Kunden. |
| [CustomerContentEncodeMode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontentencodemode/) { get; set; } | Kodiermodus des Datamatrix-Barcodes. Standardwert: EncodeMode.C40. |
| [DataMatrixType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/datamatrixtype/) { get; set; } | Der 2D Mailmark-Typ definiert die Größe des Data Matrix-Barcodes. |
| [DestinationPostCodeAndDPS](../../aspose.barcode.complexbarcode/mailmark2dcodetext/destinationpostcodeanddps/) { get; set; } | Enthält die Postleitzahl der Lieferadresse mit DPS. Wenn im Inland, enthält die Postleitzahl/DP die folgende Anzahl von Zeichen: Gebiet (1 oder 2 Zeichen) Bezirk (1 oder 2 Zeichen) Sektor (1 Zeichen) Einheit (2 Zeichen) DPS (2 Zeichen). Die Postleitzahl und DPS müssen einem gültigen PAF®‑Format entsprechen. |
| [InformationTypeID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/informationtypeid/) { get; set; } | Identifiziert die Nutzdaten des Royal Mail Mailmark-Barcodes für jeden Produkttyp. |
| [ItemID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/itemid/) { get; set; } | Identifiziert das eindeutige Element innerhalb der Supply‑Chain‑ID. Jeder Mailmark-Barcode muss eine ID tragen, damit er mindestens 90 Tage eindeutig identifiziert werden kann. Maximalwert: 99999999. |
| [ReturnToSenderPostCode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/returntosenderpostcode/) { get; set; } | Enthält die Rücksende-Postleitzahl, jedoch kein DPS. Die PL (ohne DPS) muss einem PAF®‑Format entsprechen. |
| [RTSFlag](../../aspose.barcode.complexbarcode/mailmark2dcodetext/rtsflag/) { get; set; } | Flag, das angibt, welche Ebene des Rücksende‑Dienstes angefordert wird. |
| [SupplyChainID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/supplychainid/) { get; set; } | Identifiziert die eindeutige Gruppe von Kunden, die am Versand beteiligt sind. Maximalwert: 9999999. |
| [UPUCountryID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/upucountryid/) { get; set; } | Identifiziert die UPU-Ländercode‑ID. Maximale Länge: 4 Zeichen. |
| [VersionID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/versionid/) { get; set; } | Identifiziert die Barcode‑Version, die für jede Informations‑Typ‑ID relevant ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getbarcodetype/)() | Liest den Barcode‑Typ. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getconstructedcodetext/)() | Erstelle Codetext aus Mailmark-Daten. |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmark2dcodetext/initfromstring/)(string) | Initialisiert Mailmark-Daten aus dem erstellten Codetext. |

### Siehe auch

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


