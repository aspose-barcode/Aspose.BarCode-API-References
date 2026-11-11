---
title: "QrParameters.EncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode för .NET API-referens"
description: "QrParameters egenskap. Hämtar eller anger ett värde som indikerar om GS1-specialtecken ska kodas i byte-läge för QR- och RectMicroQR-streckkoder"
type: docs
weight: 30
url: /sv/net/aspose.barcode.generation/qrparameters/encodegs1separatorinbytemode/
---
## QrParameters.EncodeGS1SeparatorInByteMode property

Hämtar eller anger ett värde som indikerar om GS1-specialtecken ska kodas i byte-läge för QR- och RectMicroQR-streckkoder.

Om falskt, kan GS1-separatorer kodas som '%' i alfanumeriskt läge enligt QR-specifikationen.

Om sant, kodas GS1-gruppseparatorer i byte-läge som tecknet 0x1D, och '%' tecken kodas också i byte-läge för att bevara dem som data.

Detta alternativ kan förbättra kompatibiliteten med avkodare som förväntar sig byte-nivå GS1-gruppseparatorer och förhindrar att '%' datatecken tolkas som GS1-separatorer.

```csharp
public bool EncodeGS1SeparatorInByteMode { get; set; }
```

### Se även

* class [QrParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


