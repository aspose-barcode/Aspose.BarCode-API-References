---
title: "Klass USADriveIdCodetext.SubfileProperties"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextSubfileProperties-klass. USA DL-subfilens egenskaper för offset och längd sätts automatiskt"
type: docs
weight: 840
url: /sv/net/aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
## USADriveIdCodetext.SubfileProperties class

USA DL-subfilens egenskaper, offset och längd sätts automatiskt.

```csharp
public class SubfileProperties
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/.ctor)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Length](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/length) { get; set; } | 4 Dessa byte innehåller ett 4‑siffrigt numeriskt värde som specificerar subfilens längd i byte. Segmentavslutaren måste inkluderas vid beräkning av subfilens längd. En segmentavslutare = 1. Varje subfil måste börja med den tvåtecken långa Subfile-typen och dessa två tecken måste också inkluderas i längden. |
| [Offset](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/offset) { get; set; } | 4‑siffrigt numeriskt värde som specificerar antalet byte från filens början till där data relaterad till den specifika subfilen är placerad. Den första byten i filen har offset 0. |
| [Type](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/type) { get; set; } | 2-byte typ av subfil, till exempel "DL" |

### Se även

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


