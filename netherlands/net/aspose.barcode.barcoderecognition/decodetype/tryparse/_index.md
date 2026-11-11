---
title: "DecodeType.TryParse"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "DecodeType methode. Converteert de tekenreeksrepresentatie van een SingleDecodeType naar zijn instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is"
type: docs
weight: 980
url: /nl/net/aspose.barcode.barcoderecognition/decodetype/tryparse/
---
## TryParse(string, out SingleDecodeType) {#tryparse_1}

Converteert de tekenreeksrepresentatie van een SingleDecodeType naar de bijbehorende instantie. Een retourwaarde geeft aan of de conversie geslaagd is of mislukt.

```csharp
public static bool TryParse(string parsingType, out SingleDecodeType result)
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

---

## TryParse(string, out MultiDecodeType) {#tryparse}

Converteert de tekenreeksrepresentatie van een MultiDecodeType naar de bijbehorende instantie. Een retourwaarde geeft aan of de conversie geslaagd is of mislukt.

```csharp
public static bool TryParse(string parsingType, out MultiDecodeType result)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | String | Een tekenreeks in het formaat "AllSupportedTypes" of "EAN8,EAN13,CodaBar" om te converteren. |
| result | MultiDecodeType& | Er wordt een daadwerkelijke MultiDecodeType geretourneerd wanneer de conversie succesvol is voltooid; anders retourneert het een onbepaalde type: new MultiDecodeType(DecodeType.None) |

### Retourwaarde

**true** if parsingType was converted successfully; otherwise, **false**.

### Zie ook

* class [MultiDecodeType](../../multidecodetype/)
* class [DecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


