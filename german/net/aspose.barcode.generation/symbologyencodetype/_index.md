---
title: "Klasse SymbologyEncodeType"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Generation.SymbologyEncodeType Klasse. Symbologie‑Kodierungstyp. Siehe EncodeTypes, um eine Instanz zu erhalten."
type: docs
weight: 1710
url: /de/net/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class

Kodierungstyp der Symbolik. Siehe EncodeTypes, um eine Instanz zu erhalten.

```csharp
public class SymbologyEncodeType : BaseEncodeType
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Classification](../../aspose.barcode.generation/baseencodetype/classification/) { get; } | Ermittelt eine Klassifizierung dieser Symbologie. |
| [TypeIndex](../../aspose.barcode.generation/baseencodetype/typeindex/) { get; } | Ermittelt einen Index des Kodierungstyps. |
| [TypeName](../../aspose.barcode.generation/baseencodetype/typename/) { get; } | Ermittelt einen Namen des Kodierungstyps. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Equals](../../aspose.barcode.generation/baseencodetype/equals/)(BaseEncodeType) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [`BaseEncodeType`](../baseencodetype/)-Wert entspricht. |
| override [Equals](../../aspose.barcode.generation/baseencodetype/equals/)(object) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [`BaseEncodeType`](../baseencodetype/)-Wert entspricht. |
| override [GetHashCode](../../aspose.barcode.generation/baseencodetype/gethashcode/)() | Gibt den Hash‑Code für diese Instanz zurück. |
| [GetString](../../aspose.barcode.generation/baseencodetype/getstring/)() | Konvertiert die Instanz von BaseEncodeType in ihre entsprechende Zeichenkettenrepräsentation. Das Zeichenkettenformat ist: "Index:0; Name:Codabar". |
| override [ToString](../../aspose.barcode.generation/baseencodetype/tostring/)() | Gibt den Namen des angegebenen BaseEncodeType als Zeichenkette zurück. |

## Beispiele

Dieses Beispiel zeigt, wie man eine Instanz der Klasse SymbologyEncodeType erhält.

```csharp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR 
 
[VB.NET]
Dim symbologyType As SymbologyEncodeType 
symbologyType = EncodeTypes.QR
```

### Siehe auch

* class [BaseEncodeType](../baseencodetype/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


