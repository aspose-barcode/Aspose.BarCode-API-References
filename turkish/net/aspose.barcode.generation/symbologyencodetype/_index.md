---
title: "Sınıf SymbologyEncodeType"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.SymbologyEncodeType sınıfı. Sembololoji kodlama türü. Örnek almak için EncodeTypes'a bakın."
type: docs
weight: 1710
url: /tr/net/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class

Sembol kodlama türü. Örnek almak için EncodeTypes'a bakın.

```csharp
public class SymbologyEncodeType : BaseEncodeType
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Classification](../../aspose.barcode.generation/baseencodetype/classification/) { get; } | Bu sembolojinin sınıflandırmasını alır. |
| [TypeIndex](../../aspose.barcode.generation/baseencodetype/typeindex/) { get; } | Kodlama türünün bir indeksini alır |
| [TypeName](../../aspose.barcode.generation/baseencodetype/typename/) { get; } | Kodlama türünün adını alır |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Equals](../../aspose.barcode.generation/baseencodetype/equals/)(BaseEncodeType) | Bu örneğin belirtilen [`BaseEncodeType`](../baseencodetype/) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| override [Equals](../../aspose.barcode.generation/baseencodetype/equals/)(object) | Bu örneğin belirtilen [`BaseEncodeType`](../baseencodetype/) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| override [GetHashCode](../../aspose.barcode.generation/baseencodetype/gethashcode/)() | Bu örnek için karma kodunu döndürür. |
| [GetString](../../aspose.barcode.generation/baseencodetype/getstring/)() | BaseEncodeType örneğini eşdeğer dize temsiline dönüştürür. Dize biçimi şu şekildedir: "Index:0; Name:Codabar". |
| override [ToString](../../aspose.barcode.generation/baseencodetype/tostring/)() | Verilen BaseEncodeType'ın adını dize olarak döndürür. |

## Örnekler

Bu örnek, SymbologyEncodeType sınıfının örneğini nasıl alacağınızı gösterir.

```csharp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR 
 
[VB.NET]
Dim symbologyType As SymbologyEncodeType 
symbologyType = EncodeTypes.QR
```

### Ayrıca Bakınız

* class [BaseEncodeType](../baseencodetype/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


