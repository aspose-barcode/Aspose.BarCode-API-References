---
title: TryParse
second_title: Aspose.BarCode voor .NET API-referentie
description: Converteert de tekenreeksrepresentatie van een SingleDecodeType naar zijn instantie. Een geretourneerde waarde geeft aan of de conversie is geslaagd of mislukt.
type: docs
weight: 920
url: /nl/net/aspose.barcode.barcoderecognition/decodetype/tryparse/
---
## TryParse(string, out SingleDecodeType) {#tryparse_1}

Converteert de tekenreeksrepresentatie van een SingleDecodeType naar zijn instantie. Een geretourneerde waarde geeft aan of de conversie is geslaagd of mislukt.

```csharp
public static bool TryParse(string parsingType, out SingleDecodeType result)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | String | Een tekenreeks in de notatie "Index:-1; Naam:Geen" om te converteren. |
| result | SingleDecodeType& | Een werkelijke SingleDecodeType keert terug, wanneer de conversie met succes is voltooid; |

### Winstwaarde

**WAAR** als s met succes is geconverteerd; anders, **vals**.

### Zie ook

* class [SingleDecodeType](../../singledecodetype/)
* class [DecodeType](../)
* naamruimte [Aspose.BarCode.BarCodeRecognition](../../decodetype/)
* montage [Aspose.BarCode](../../../)

---

## TryParse(string, out MultyDecodeType) {#tryparse}

Converteert de tekenreeksrepresentatie van een MultyDecodeType naar zijn instantie. Een geretourneerde waarde geeft aan of de conversie is geslaagd of mislukt.

```csharp
public static bool TryParse(string parsingType, out MultyDecodeType result)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | String | Een tekenreeks in de indeling "AllSupportedTypes" of "EAN8,EAN13,CodaBar" om te converteren. |
| result | MultyDecodeType& | Er wordt een werkelijk MultyDecodeType geretourneerd wanneer de conversie met succes is voltooid; |

### Winstwaarde

**WAAR** als s met succes is geconverteerd; anders, **vals**.

### Zie ook

* class [MultyDecodeType](../../multydecodetype/)
* class [DecodeType](../)
* naamruimte [Aspose.BarCode.BarCodeRecognition](../../decodetype/)
* montage [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->