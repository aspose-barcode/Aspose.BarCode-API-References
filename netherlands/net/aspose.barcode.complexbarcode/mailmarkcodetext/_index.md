---
title: "Class MailmarkCodetext"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.ComplexBarcode.MailmarkCodetext class. Klasse voor het coderen en decoderen van de tekst die is ingebed in de 4state Royal Mailmark-code"
type: docs
weight: 670
url: /nl/net/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class

Klasse voor het coderen en decoderen van de in de 4-state Royal Mailmark-code ingebedde tekst.

```csharp
public sealed class MailmarkCodetext : IComplexCodetext
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [MailmarkCodetext](mailmarkcodetext/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmarkcodetext/class/) { get; set; } | \"0\" - Null of Test \"1\" - 1C (Retail) \"2\" - 2C (Retail) \"3\" - 3C (Retail) \"4\" - Premium (RetailPublishing Mail) (voor mogelijk toekomstig gebruik) \"5\" - Deferred (Retail) \"6\" - Air (Retail) (voor mogelijk toekomstig gebruik) \"7\" - Surface (Retail) (voor mogelijk toekomstig gebruik) \"8\" - Premium (Network Access) \"9\" - Standard (Network Access) |
| [DestinationPostCodePlusDPS](../../aspose.barcode.complexbarcode/mailmarkcodetext/destinationpostcodeplusdps/) { get; set; } | De PC en DP moeten voldoen aan een PAF-formaat. Een tekenreeks van negen tekens die een internationale \"XY11 \" aangeeft (let op de 5 volgende spaties) of een patroon van tekens dat een binnenlandse sorteer‑code aangeeft. Een binnenlandse sorteer‑code bestaat uit een outward postcode, een inward postcode en een Delivery Point Suffix. |
| [Format](../../aspose.barcode.complexbarcode/mailmarkcodetext/format/) { get; set; } | \"0\" – Null of Test \"1\" – Letter \"2\" – Large Letter |
| [ItemID](../../aspose.barcode.complexbarcode/mailmarkcodetext/itemid/) { get; set; } | Maximumwaarde is 99999999. |
| [SupplychainID](../../aspose.barcode.complexbarcode/mailmarkcodetext/supplychainid/) { get; set; } | Maximumwaarden zijn 99 voor Barcode C en 999999 voor Barcode L. |
| [VersionID](../../aspose.barcode.complexbarcode/mailmarkcodetext/versionid/) { get; set; } | Momenteel \"1\" – Voor Mailmark-barcode (0 en 2 tot 9 en A tot Z gereserveerd voor toekomstig gebruik) |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmarkcodetext/getbarcodetype/)() | Haalt het barcode-type op. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmarkcodetext/getconstructedcodetext/)() | Construeer codetekst vanuit Mailmark-gegevens. |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmarkcodetext/initfromstring/)(string) | Initialiseert Mailmark-gegevens vanuit geconstrueerde codetekst. |

### Zie ook

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


