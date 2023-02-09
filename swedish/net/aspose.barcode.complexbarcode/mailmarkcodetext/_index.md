---
title: MailmarkCodetext
second_title: Aspose.BarCode för .NET API-referens
description: Klass för kodning och avkodning av texten inbäddad i Royal Mailmark-koden med fyra tillstånd.
type: docs
weight: 380
url: /sv/net/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class

Klass för kodning och avkodning av texten inbäddad i Royal Mailmark-koden med fyra tillstånd.

```csharp
public sealed class MailmarkCodetext : IComplexCodetext
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [MailmarkCodetext](mailmarkcodetext)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmarkcodetext/class) { get; set; } | "0" - Null eller Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (för potentiell framtida användning) "5" - Deferred (Retail) "6" - Air (Retail) (för potentiell framtida användning) "7" - Surface (Retail) (för potentiell framtida användning) "8" - Premium (nätverksåtkomst) "9" - Standard (nätverksåtkomst) |
| [DestinationPostCodePlusDPS](../../aspose.barcode.complexbarcode/mailmarkcodetext/destinationpostcodeplusdps) { get; set; } | PC:n och DP måste överensstämma med ett PAF-format. Nio teckensträng som anger internationell "XY11 " (observera de 5 efterföljande mellanslagen) eller ett mönster med tecken som anger en inhemsk sorteringskod. En inhemsk sorteringskod består av ett utgående postnummer ett inåtriktat postnummer och ett leveranspunktssuffix. |
| [Format](../../aspose.barcode.complexbarcode/mailmarkcodetext/format) { get; set; } | "0" – Null eller Test "1" – Letter "2" – Large Letter |
| [ItemID](../../aspose.barcode.complexbarcode/mailmarkcodetext/itemid) { get; set; } | Maximalt värde är 99999999. |
| [SupplychainID](../../aspose.barcode.complexbarcode/mailmarkcodetext/supplychainid) { get; set; } | Maximala värden är 99 för streckkod C och 999999 för streckkod L. |
| [VersionID](../../aspose.barcode.complexbarcode/mailmarkcodetext/versionid) { get; set; } | För närvarande "1" – För postmärkesstreckkod (0 och 2 till 9 och reservdelar från A till Ö för framtida bruk) |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmarkcodetext/getbarcodetype)() | Får streckkodstyp. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmarkcodetext/getconstructedcodetext)() | Konstruera kodtext från Mailmark-data. |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmarkcodetext/initfromstring)(string) | Initierar postmärkesdata från konstruerad kodtext. |

### Se även

* interface [IComplexCodetext](../icomplexcodetext)
* namnutrymme [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode)
* hopsättning [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->