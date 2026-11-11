---
title: "BaseDecodeType.TryParse"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "BaseDecodeType methode. Converteert de stringrepresentatie van een SingleDecodeType naar zijn instantie. Een retourwaarde geeft aan of de conversie geslaagd is of mislukt"
type: docs
weight: 40
url: /nl/net/aspose.barcode.barcoderecognition/basedecodetype/tryparse/
---
## TryParse(string, out SingleDecodeType) {#tryparse_2}

Converteert de tekenreeksrepresentatie van een SingleDecodeType naar de bijbehorende instantie. Een retourwaarde geeft aan of de conversie geslaagd is of mislukt.

```csharp
public static bool TryParse(string parsingType, out SingleDecodeType result)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | String | Een string die een SingleDecodeType bevat in het formaat "EAN8" of "EAN13" of "CodaBar"... om te converteren. |
| result | SingleDecodeType& | Er wordt een daadwerkelijke SingleDecodeType geretourneerd wanneer de conversie succesvol is voltooid; anders retourneert het een onbepaalde type: DecodeType.None. |

### Retourwaarde

**true** if parsingType was converted successfully; otherwise, **false**.

### Zie ook

* class [SingleDecodeType](../../singledecodetype/)
* class [BaseDecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## TryParse(string, out MultiDecodeType) {#tryparse_1}

Converteert de tekenreeksrepresentatie van een MultiDecodeType naar de bijbehorende instantie. Een retourwaarde geeft aan of de conversie geslaagd is of mislukt.

```csharp
public static bool TryParse(string parsingType, out MultiDecodeType result)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | String | Een string die een MultiDecodeType-representatie bevat om te converteren. |
| result | MultiDecodeType& | Er wordt een daadwerkelijke MultiDecodeType geretourneerd wanneer de conversie succesvol is voltooid; anders retourneert het een onbepaalde type: new MultiDecodeType(DecodeType.None) |

### Retourwaarde

**true** if parsingType was converted successfully; otherwise, **false**.

### Zie ook

* class [MultiDecodeType](../../multidecodetype/)
* class [BaseDecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## TryParse(string, out BaseDecodeType) {#tryparse}

Converteert de tekenreeksrepresentatie van een BaseDecodeType naar de bijbehorende instantie, nadat het concrete type is bepaald. Een retourwaarde geeft aan of de conversie geslaagd is of mislukt.

```csharp
public static bool TryParse(string parsingType, out BaseDecodeType result)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | String | Een string die een MultiDecodeType-representatie bevat om te converteren. |
| result | BaseDecodeType& | Er wordt een daadwerkelijke MultiDecodeType geretourneerd wanneer de conversie succesvol is voltooid; anders retourneert het een onbepaalde type: DecodeType.None. |

### Retourwaarde

**true** if parsingType was converted successfully; otherwise, **false**.

### Zie ook

* class [BaseDecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


