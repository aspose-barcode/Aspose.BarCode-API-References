---
title: "Klasse SymbologyEncodeType"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.SymbologyEncodeType klasse. Symbologie‑codeertype. Zie EncodeTypes om een instantie te krijgen"
type: docs
weight: 1710
url: /nl/net/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class

Symboolcoderingstype. Zie EncodeTypes om een instantie te krijgen.

```csharp
public class SymbologyEncodeType : BaseEncodeType
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Classification](../../aspose.barcode.generation/baseencodetype/classification/) { get; } | Haalt een classificatie van deze symbologie op. |
| [TypeIndex](../../aspose.barcode.generation/baseencodetype/typeindex/) { get; } | Haalt een index van het coderingstype op. |
| [TypeName](../../aspose.barcode.generation/baseencodetype/typename/) { get; } | Haalt een naam van het coderingstype op. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Equals](../../aspose.barcode.generation/baseencodetype/equals/)(BaseEncodeType) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [`BaseEncodeType`](../baseencodetype/) waarde. |
| override [Equals](../../aspose.barcode.generation/baseencodetype/equals/)(object) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [`BaseEncodeType`](../baseencodetype/) waarde. |
| override [GetHashCode](../../aspose.barcode.generation/baseencodetype/gethashcode/)() | Retourneert de hashcode voor deze instantie. |
| [GetString](../../aspose.barcode.generation/baseencodetype/getstring/)() | Converteert de instantie van BaseEncodeType naar de equivalente tekenreeksrepresentatie. Het tekenreeksformaat is: "Index:0; Name:Codabar". |
| override [ToString](../../aspose.barcode.generation/baseencodetype/tostring/)() | Retourneert de naam van de opgegeven BaseEncodeType als een tekenreeks. |

## Voorbeelden

Dit voorbeeld toont hoe een instantie van de SymbologyEncodeType‑klasse te verkrijgen.

```csharp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR 
 
[VB.NET]
Dim symbologyType As SymbologyEncodeType 
symbologyType = EncodeTypes.QR
```

### Zie ook

* class [BaseEncodeType](../baseencodetype/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


