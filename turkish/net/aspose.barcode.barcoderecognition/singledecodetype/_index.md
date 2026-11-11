---
title: "Sınıf SingleDecodeType"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.BarCodeRecognition.SingleDecodeType sınıfı. Tek çözümleme türü. Örneği almak için decode type'ına bakın"
type: docs
weight: 390
url: /tr/net/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class

Tek çözümleme türü. Örneği almak için decode type'a bakın.

```csharp
public sealed class SingleDecodeType : BaseDecodeType, IEquatable<SingleDecodeType>
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [TypeIndex](../../aspose.barcode.barcoderecognition/singledecodetype/typeindex/) { get; } | Çözümleme türünün bir indeksini alır |
| [TypeName](../../aspose.barcode.barcoderecognition/singledecodetype/typename/) { get; } | Çözümleme türünün adını alır |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [Parse](../../aspose.barcode.barcoderecognition/singledecodetype/parse/)(string) | Bir SingleDecodeType adının dize temsiliğini örneğine dönüştürür. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/singledecodetype/containsany/)(params BaseDecodeType[]) | Bu örneğin belirtilen listeye dahil olup olmadığını gösteren bir değer döndürür. |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | Bu örneğin belirtilen [`BaseDecodeType`](../basedecodetype/) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_1)(MultiDecodeType) | Belirtilen [`MultiDecodeType`](../multidecodetype/) koleksiyonunun yalnızca bu çözümleme türünü içerip içermediğini gösteren bir değer döndürür. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_3)(object) | Bu örneğin belirtilen `SingleDecodeType` değerine eşit olup olmadığını gösteren bir değer döndürür. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_2)(SingleDecodeType) | Bu örneğin belirtilen `SingleDecodeType` değerine eşit olup olmadığını gösteren bir değer döndürür. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/singledecodetype/gethashcode/)() | Bu örnek için karma kodunu döndürür. |
| [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)() | SingleDecodeType örneğini eşdeğer dize temsiline dönüştürür. Dize formatı: "Index:-1; Name:None". |
| override [ToString](../../aspose.barcode.barcoderecognition/singledecodetype/tostring/)() | Verilen SingleDecodeType'ın adını dize olarak döndürür. |
| static [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)(SingleDecodeType) | SingleDecodeType örneğini eşdeğer dize temsiline dönüştürür. Dize formatı: "Index:-1; Name:None". |

## Örnekler

Bu örnek, tek çözümleme türünün örneğinin nasıl alınacağını gösterir

```csharp
[C#]
SingleDecodeType singleType = DecodeType.QR 
 
[VB.NET]
Dim singleType As SingleDecodeType 
singleType = DecodeType.QR
```

### Ayrıca Bakınız

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


