---
title: Mailmark2DCodetext
second_title: Aspose.BarCode för .NET API-referens
description: Klass för kodning och avkodning av texten inbäddad i Royal Mail 2D Mailmark-koden.
type: docs
weight: 360
url: /sv/net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class

Klass för kodning och avkodning av texten inbäddad i Royal Mail 2D Mailmark-koden.

```csharp
public sealed class Mailmark2DCodetext : IComplexCodetext
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Mailmark2DCodetext](mailmark2dcodetext)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmark2dcodetext/class) { get; set; } | Identifierar objektets klass. |
| [CustomerContent](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontent) { get; set; } | Valfritt utrymme för användning av kunden. |
| [CustomerContentEncodeMode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontentencodemode) { get; set; } | Kodningsläge för Datamatrix streckkod. Standardvärde: DataMatrixEncodeMode.C40. |
| [DataMatrixType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/datamatrixtype) { get; set; } | 2D Mailmark Type definierar storleken på Data Matrix streckkoden. |
| [DestinationPostCodeAndDPS](../../aspose.barcode.complexbarcode/mailmark2dcodetext/destinationpostcodeanddps) { get; set; } | Innehåller postnumret för leveransadressen med DPS Om inlandet innehåller postnumret/DP följande antal tecken. Område (1 eller 2 tecken) Distrikt(1 eller 2 tecken) Sektor(1 tecken) Enhet(2 tecken) DPS (2 tecken). Postnumret och DPS måste överensstämma med ett giltigt PAF®-format. |
| [InformationTypeID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/informationtypeid) { get; set; } | Identifierar Royal Mail Mailmarks streckkodsnyttolast för varje produkttyp. |
| [ItemID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/itemid) { get; set; } | Identifierar den unika artikeln inom Supply Chain ID. Varje Mailmark streckkod krävs för att bära ett ID så att den kan identifieras unikt i minst 90 dagar. Maxvärde: 99999999. |
| [ReturnToSenderPostCode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/returntosenderpostcode) { get; set; } | Innehåller postkoden för retur till avsändaren men ingen DPS. Datorn (utan DPS) måste överensstämma med ett PAF®-format. |
| [RTSFlag](../../aspose.barcode.complexbarcode/mailmark2dcodetext/rtsflag) { get; set; } | Flagga som indikerar vilken nivå av tjänsten Return to Sender som begärs. |
| [SupplyChainID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/supplychainid) { get; set; } | Identifierar den unika grupp kunder som är involverade i utskicket. Maxvärde: 9999999. |
| [UPUCountryID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/upucountryid) { get; set; } | Identifierar UPU-lands-ID. Maxlängd: 4 tecken. |
| [VersionID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/versionid) { get; set; } | Identifierar streckkodsversionen som relevant för varje informationstyp-ID. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getbarcodetype)() | Får streckkodstyp. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getconstructedcodetext)() | Konstruera kodtext från Mailmark-data. |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmark2dcodetext/initfromstring)(string) | Initierar postmärkesdata från konstruerad kodtext. |

### Se även

* interface [IComplexCodetext](../icomplexcodetext)
* namnutrymme [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode)
* hopsättning [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->