---
title: "Klasse MailmarkCodetext"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.ComplexBarcode.MailmarkCodetext Klasse. Klasse zum Kodieren und Dekodieren des in den 4‑State Royal Mailmark‑Code eingebetteten Textes"
type: docs
weight: 670
url: /de/net/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class

Klasse zum Codieren und Dekodieren des in den 4‑Zustands‑Royal‑Mailmark‑Code eingebetteten Textes.

```csharp
public sealed class MailmarkCodetext : IComplexCodetext
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MailmarkCodetext](mailmarkcodetext/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmarkcodetext/class/) { get; set; } | \"0\" - Null oder Test \"1\" - 1C (Einzelhandel) \"2\" - 2C (Einzelhandel) \"3\" - 3C (Einzelhandel) \"4\" - Premium (RetailPublishing Mail) (für potenzielle zukünftige Verwendung) \"5\" - Deferred (Einzelhandel) \"6\" - Air (Einzelhandel) (für potenzielle zukünftige Verwendung) \"7\" - Surface (Einzelhandel) (für potenzielle zukünftige Verwendung) \"8\" - Premium (Netzwerkzugriff) \"9\" - Standard (Netzwerkzugriff) |
| [DestinationPostCodePlusDPS](../../aspose.barcode.complexbarcode/mailmarkcodetext/destinationpostcodeplusdps/) { get; set; } | Der PC und DP müssen dem PAF-Format entsprechen. Neun‑Zeichen‑String, der das internationale \"XY11 \" bezeichnet (beachten Sie die 5 nachfolgenden Leerzeichen) oder ein Muster von Zeichen, das einen inländischen Sortiercode bezeichnet. Ein inländischer Sortiercode besteht aus einer Außenpostleitzahl, einer Innenpostleitzahl und einem Lieferpunkt‑Suffix. |
| [Format](../../aspose.barcode.complexbarcode/mailmarkcodetext/format/) { get; set; } | \"0\" – Null oder Test \"1\" – Brief \"2\" – Großbrief |
| [ItemID](../../aspose.barcode.complexbarcode/mailmarkcodetext/itemid/) { get; set; } | Maximaler Wert ist 99999999. |
| [SupplychainID](../../aspose.barcode.complexbarcode/mailmarkcodetext/supplychainid/) { get; set; } | Maximale Werte sind 99 für Barcode C und 999999 für Barcode L. |
| [VersionID](../../aspose.barcode.complexbarcode/mailmarkcodetext/versionid/) { get; set; } | Derzeit \"1\" – Für Mailmark-Barcode (0 und 2 bis 9 sowie A bis Z sind für zukünftige Verwendung reserviert) |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmarkcodetext/getbarcodetype/)() | Liest den Barcode‑Typ. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmarkcodetext/getconstructedcodetext/)() | Erstelle Codetext aus Mailmark-Daten. |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmarkcodetext/initfromstring/)(string) | Initialisiert Mailmark-Daten aus dem erstellten Codetext. |

### Siehe auch

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


