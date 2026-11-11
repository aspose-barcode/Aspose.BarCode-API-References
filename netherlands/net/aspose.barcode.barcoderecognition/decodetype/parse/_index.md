---
title: "DecodeType.Parse"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "DecodeType methode. Converteert de tekenreeksrepresentatie van een SingleDecodeType naar zijn instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is"
type: docs
weight: 960
url: /nl/net/aspose.barcode.barcoderecognition/decodetype/parse/
---
## DecodeType.Parse method

Converteert de tekenreeksrepresentatie van een SingleDecodeType naar de bijbehorende instantie. Een retourwaarde geeft aan of de conversie geslaagd is of mislukt.

```csharp
public static bool Parse(string parsingType, out SingleDecodeType result)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | String | Een string die een SingleDecodeType bevat in het formaat "EAN8" of "EAN13" of "CodaBar"... om te converteren. |
| result | SingleDecodeType& | Een daadwerkelijke SingleDecodeType wordt geretourneerd wanneer de conversie succesvol is voltooid; anders wordt een onbepaald type geretourneerd: DecodeType.None. |

### Retourwaarde

**true** if parsingType was converted successfully; otherwise, **false**.

### Zie ook

* class [SingleDecodeType](../../singledecodetype/)
* class [DecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


