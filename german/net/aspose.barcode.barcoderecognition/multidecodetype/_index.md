---
title: "Klasse MultiDecodeType"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.BarCodeRecognition.MultiDecodeType Klasse. Zusammengesetzter Dekodierungstyp"
type: docs
weight: 320
url: /de/net/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class

Composite‑Dekodierungstyp.

```csharp
public class MultiDecodeType : BaseDecodeType, IEquatable<MultiDecodeType>
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MultiDecodeType](multidecodetype/#constructor)(params BaseDecodeType[]) | Initialisiert eine neue Instanz der `MultiDecodeType` Klasse. |
| [MultiDecodeType](multidecodetype/#constructor_1)(params SingleDecodeType[]) | Initialisiert eine neue Instanz der `MultiDecodeType` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [GetSingleTypesCount](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypescount/) { get; } | Gibt eine Anzahl einzelner Typen zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.barcode.barcoderecognition/multidecodetype/add/)(SingleDecodeType) | Fügt dem MultiDecodeType einen weiteren [`SingleDecodeType`](../singledecodetype/) hinzu. |
| [ContainsAll](../../aspose.barcode.barcoderecognition/multidecodetype/containsall/)(params BaseDecodeType[]) | Prüft, ob dies alle Typen aus den Barcode‑Typen enthält. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/multidecodetype/containsany/)(params BaseDecodeType[]) | Enthält irgendeinen Typ |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [`BaseDecodeType`](../basedecodetype/) Wert entspricht. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_1)(MultiDecodeType) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `MultiDecodeType`‑Wert entspricht. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_3)(object) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `MultiDecodeType`‑Wert entspricht. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_2)(SingleDecodeType) | Gibt einen Wert zurück, der angibt, ob diese Sammlung von Dekodierungstypen nur den angegebenen [`SingleDecodeType`](../singledecodetype/)‑Wert enthält. |
| [Exclude](../../aspose.barcode.barcoderecognition/multidecodetype/exclude/)(SingleDecodeType) | Schließt [`SingleDecodeType`](../singledecodetype/) aus dem MultiDecodeType aus und gibt eine neue MultiDecodeType‑Instanz zurück. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/multidecodetype/gethashcode/)() | Gibt den Hash‑Code für diese Instanz zurück. |
| [GetSingleTypes](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypes/)() | Stellt eine Liste einzelner Typen dar. |
| override [ToString](../../aspose.barcode.barcoderecognition/multidecodetype/tostring/)() | Überschriebene Methode, die MultiDecodeType als Zeichenkette darstellt. |
| static [TryParse](../../aspose.barcode.barcoderecognition/multidecodetype/tryparse/)(string, out MultiDecodeType) | Konvertiert die Zeichenkettenrepräsentation eines MultiDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |

## Beispiele

Dieses Beispiel zeigt, wie zusammengesetzte MultiDecode‑Typen erstellt werden, die SingleDecodeType und MultiDecode‑Typen kombinieren.

```csharp
[C#]
MultiDecodeType types1 = new MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultiDecodeType types2 = new MultiDecodeType(types1, DecodeType.Code128, DecodeType.Code39);
[VB.NET]
Dim multiType1 As MultiDecodeType 
multiType1 = New MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multiType2 As MultiDecodeType
multiType2 = New MultiDecodeType(multiType1, DecodeType.Code128, DecodeType.Code39)
```

### Siehe auch

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


