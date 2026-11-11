---
title: "Class Mailmark2DCodetext"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.ComplexBarcode.Mailmark2DCodetext class. Klasse voor het coderen en decoderen van de tekst die is ingebed in de Royal Mail 2D Mailmark-code."
type: docs
weight: 650
url: /nl/net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class

Klasse voor het coderen en decoderen van de in de Royal Mail 2D Mailmark-code ingebedde tekst.

```csharp
public sealed class Mailmark2DCodetext : IComplexCodetext
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [Mailmark2DCodetext](mailmark2dcodetext/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmark2dcodetext/class/) { get; set; } | Identificeert de klasse van het item. |
| [CustomerContent](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontent/) { get; set; } | Optionele ruimte voor gebruik door de klant. |
| [CustomerContentEncodeMode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontentencodemode/) { get; set; } | Encodeermodus van Datamatrix-barcode. Standaardwaarde: EncodeMode.C40. |
| [DataMatrixType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/datamatrixtype/) { get; set; } | 2D Mailmark-type definieert de grootte van de Data Matrix-barcode. |
| [DestinationPostCodeAndDPS](../../aspose.barcode.complexbarcode/mailmark2dcodetext/destinationpostcodeanddps/) { get; set; } | Bevat de postcode van het afleveradres met DPS. Indien landinwaarts bevat de postcode/DP het volgende aantal tekens: Gebied (1 of 2 tekens) District (1 of 2 tekens) Sector (1 teken) Eenheid (2 tekens) DPS (2 tekens). De postcode en DPS moeten voldoen aan een geldig PAF®-formaat. |
| [InformationTypeID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/informationtypeid/) { get; set; } | Identificeert de payload van de Royal Mail Mailmark-barcode voor elk producttype. |
| [ItemID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/itemid/) { get; set; } | Identificeert het unieke item binnen de Supply Chain ID. Elke Mailmark-barcode moet een ID dragen zodat deze gedurende minimaal 90 dagen uniek kan worden geïdentificeerd. Maximale waarde: 99999999. |
| [ReturnToSenderPostCode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/returntosenderpostcode/) { get; set; } | Bevat de Return to Sender-postcode maar geen DPS. De PC (zonder DPS) moet voldoen aan een PAF®-formaat. |
| [RTSFlag](../../aspose.barcode.complexbarcode/mailmark2dcodetext/rtsflag/) { get; set; } | Vlag die aangeeft welk niveau van Return to Sender-service wordt aangevraagd. |
| [SupplyChainID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/supplychainid/) { get; set; } | Identificeert de unieke groep klanten die bij de mailing betrokken zijn. Maximale waarde: 9999999. |
| [UPUCountryID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/upucountryid/) { get; set; } | Identificeert de UPU-land-ID. Maximale lengte: 4 tekens. |
| [VersionID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/versionid/) { get; set; } | Identificeert de barcodeversie die relevant is voor elke Information Type ID. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getbarcodetype/)() | Haalt het barcode-type op. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getconstructedcodetext/)() | Construeer codetekst vanuit Mailmark-gegevens. |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmark2dcodetext/initfromstring/)(string) | Initialiseert Mailmark-gegevens vanuit geconstrueerde codetekst. |

### Zie ook

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


