---
title: BaseDecodeType
second_title: Aspose.BarCode für .NET-API-Referenz
description: Basisklasse für MultyDecodeType und SingleDecodeType.
type: docs
weight: 120
url: /de/net/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class

Basisklasse für MultyDecodeType und SingleDecodeType.

```csharp
public abstract class BaseDecodeType : IEquatable<BaseDecodeType>
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| abstract [ContainsAny](../../aspose.barcode.barcoderecognition/basedecodetype/containsany)(params BaseDecodeType[]) | Bestimmt, ob einer der angegebenen Dekodierungstypen in enthalten ist |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals#equals)(BaseDecodeType) | Gibt einen Wert zurück, der angibt, ob diese Instanz gleich einer angegebenen ist[`BaseDecodeType`](../basedecodetype) wert. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals#equals_1)(MultyDecodeType) | Gibt einen Wert zurück, der angibt, ob diese Instanz gleich einer angegebenen ist[`MultyDecodeType`](../multydecodetype) wert. |
| override [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals#equals_3)(object) | Gibt einen Wert zurück, der angibt, ob diese Instanz gleich einer angegebenen ist[`BaseDecodeType`](../basedecodetype) wert. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals#equals_2)(SingleDecodeType) | Gibt einen Wert zurück, der angibt, ob diese Instanz gleich einer angegebenen ist[`SingleDecodeType`](../singledecodetype) wert. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/basedecodetype/gethashcode)() | Gibt den Hashcode für diese Instanz zurück. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse#tryparse)(string, out BaseDecodeType) | Konvertiert die Zeichenfolgendarstellung eines BaseDecodeType in seine Instanz, nachdem der konkrete Typ bestimmt wurde. Ein Rückgabewert zeigt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse#tryparse_1)(string, out MultyDecodeType) | Konvertiert die Zeichenfolgendarstellung eines MultyDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse#tryparse_2)(string, out SingleDecodeType) | Konvertiert die Zeichenfolgendarstellung eines SingleDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |

### Beispiele

Dieses Beispiel zeigt die Verwendung von BaseDecodeType mit SingleDecodeType und MultyDecodeType

```csharp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultyDecodeType(DecodeType.Code128, DecodeType.Code39Standard, DecodeType.Code39Extended);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultyDecodeType(DecodeType.Code128, DecodeType.Code39Standard, DecodeType.Code39Extended)
```

### Siehe auch

* namensraum [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* Montage [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->