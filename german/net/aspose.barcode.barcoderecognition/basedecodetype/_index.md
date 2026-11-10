---
title: "Klasse BaseDecodeType"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.BarCodeRecognition.BaseDecodeType Klasse. Basisklasse für MultiDecodeType und SingleDecodeType"
type: docs
weight: 130
url: /de/net/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class

Basisklasse für MultiDecodeType und SingleDecodeType.

```csharp
public abstract class BaseDecodeType : IEquatable<BaseDecodeType>
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| abstract [ContainsAny](../../aspose.barcode.barcoderecognition/basedecodetype/containsany/)(params BaseDecodeType[]) | Bestimmt, ob einer der angegebenen Decodetypen enthalten ist in |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals)(BaseDecodeType) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `BaseDecodeType`‑Wert entspricht. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_1)(MultiDecodeType) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [`MultiDecodeType`](../multidecodetype/)‑Wert entspricht. |
| override [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_3)(object) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `BaseDecodeType`‑Wert entspricht. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_2)(SingleDecodeType) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [`SingleDecodeType`](../singledecodetype/)‑Wert entspricht. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/basedecodetype/gethashcode/)() | Gibt den Hash‑Code für diese Instanz zurück. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse)(string, out BaseDecodeType) | Konvertiert die Zeichenkettenrepräsentation eines BaseDecodeType in seine Instanz, nachdem der konkrete Typ ermittelt wurde. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse_1)(string, out MultiDecodeType) | Konvertiert die Zeichenkettenrepräsentation eines MultiDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse_2)(string, out SingleDecodeType) | Konvertiert die Zeichenkettenrepräsentation eines SingleDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |

## Beispiele

Dieses Beispiel zeigt, wie man BaseDecodeType zusammen mit SingleDecodeType und MultiDecodeType verwendet.

```csharp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

### Siehe auch

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


