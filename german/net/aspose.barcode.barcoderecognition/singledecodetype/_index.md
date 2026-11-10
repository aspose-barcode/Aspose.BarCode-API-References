---
title: "Klasse SingleDecodeType"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.BarCodeRecognition.SingleDecodeType Klasse. Einzelner Dekodierungstyp. Siehe Dekodierungstyp, um eine Instanz zu erhalten."
type: docs
weight: 390
url: /de/net/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class

Einzelner Dekodierungstyp. Siehe Dekodierungstyp, um eine Instanz zu erhalten.

```csharp
public sealed class SingleDecodeType : BaseDecodeType, IEquatable<SingleDecodeType>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [TypeIndex](../../aspose.barcode.barcoderecognition/singledecodetype/typeindex/) { get; } | Liefert einen Index des Dekodierungstyps |
| [TypeName](../../aspose.barcode.barcoderecognition/singledecodetype/typename/) { get; } | Liefert einen Namen des Dekodierungstyps |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Parse](../../aspose.barcode.barcoderecognition/singledecodetype/parse/)(string) | Konvertiert die Zeichenkettenrepräsentation des Namens eines SingleDecodeType in seine Instanz. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/singledecodetype/containsany/)(params BaseDecodeType[]) | Gibt einen Wert zurück, der angibt, ob diese Instanz in die angegebene Liste aufgenommen wurde. |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [`BaseDecodeType`](../basedecodetype/) Wert entspricht. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_1)(MultiDecodeType) | Gibt einen Wert zurück, der angibt, ob die angegebene [`MultiDecodeType`](../multidecodetype/) Sammlung ausschließlich diesen Dekodierungstyp enthält. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_3)(object) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `SingleDecodeType`-Wert entspricht. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_2)(SingleDecodeType) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `SingleDecodeType`-Wert entspricht. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/singledecodetype/gethashcode/)() | Gibt den Hash‑Code für diese Instanz zurück. |
| [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)() | Konvertiert die Instanz von SingleDecodeType in ihre entsprechende Zeichenkettenrepräsentation. Das Zeichenkettenformat ist: "Index:-1; Name:None". |
| override [ToString](../../aspose.barcode.barcoderecognition/singledecodetype/tostring/)() | Gibt den Namen des angegebenen SingleDecodeType als Zeichenkette zurück. |
| static [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)(SingleDecodeType) | Konvertiert die Instanz von SingleDecodeType in ihre entsprechende Zeichenkettenrepräsentation. Das Zeichenkettenformat ist: "Index:-1; Name:None". |

## Beispiele

Dieses Beispiel zeigt, wie man eine Instanz des SingleDecodeType erhält.

```csharp
[C#]
SingleDecodeType singleType = DecodeType.QR 
 
[VB.NET]
Dim singleType As SingleDecodeType 
singleType = DecodeType.QR
```

### Siehe auch

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


