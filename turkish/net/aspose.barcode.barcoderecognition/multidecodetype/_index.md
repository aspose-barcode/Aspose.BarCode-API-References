---
title: "Sınıf MultiDecodeType"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.BarCodeRecognition.MultiDecodeType sınıfı. Bileşik çözümleme türü"
type: docs
weight: 320
url: /tr/net/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class

Kompozit çözümleme türü.

```csharp
public class MultiDecodeType : BaseDecodeType, IEquatable<MultiDecodeType>
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [MultiDecodeType](multidecodetype/#constructor)(params BaseDecodeType[]) | `MultiDecodeType` sınıfının yeni bir örneğini başlatır. |
| [MultiDecodeType](multidecodetype/#constructor_1)(params SingleDecodeType[]) | `MultiDecodeType` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [GetSingleTypesCount](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypescount/) { get; } | Tek tiplerin sayısını döndürür. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Add](../../aspose.barcode.barcoderecognition/multidecodetype/add/)(SingleDecodeType) | MultiDecodeType'a bir tane daha [`SingleDecodeType`](../singledecodetype/) ekler. |
| [ContainsAll](../../aspose.barcode.barcoderecognition/multidecodetype/containsall/)(params BaseDecodeType[]) | Barkod türlerinden tüm tipleri içerip içermediğini kontrol edin. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/multidecodetype/containsany/)(params BaseDecodeType[]) | Herhangi bir tipi içeriyor mu |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | Bu örneğin belirtilen [`BaseDecodeType`](../basedecodetype/) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_1)(MultiDecodeType) | Bu örneğin belirtilen `MultiDecodeType` değerine eşit olup olmadığını gösteren bir değer döndürür. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_3)(object) | Bu örneğin belirtilen `MultiDecodeType` değerine eşit olup olmadığını gösteren bir değer döndürür. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_2)(SingleDecodeType) | Bu kod çözme tipleri koleksiyonunun yalnızca belirtilen [`SingleDecodeType`](../singledecodetype/) değerini içerip içermediğini gösteren bir değer döndürür. |
| [Exclude](../../aspose.barcode.barcoderecognition/multidecodetype/exclude/)(SingleDecodeType) | `MultiDecodeType`'tan [`SingleDecodeType`](../singledecodetype/) dışarı çıkarır ve yeni bir MultiDecodeType örneği döndürür. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/multidecodetype/gethashcode/)() | Bu örnek için karma kodunu döndürür. |
| [GetSingleTypes](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypes/)() | Tek tiplerin bir listesini temsil eder. |
| override [ToString](../../aspose.barcode.barcoderecognition/multidecodetype/tostring/)() | MultiDecodeType'ı bir dize olarak temsil eden geçersiz kılınmış yöntem. |
| static [TryParse](../../aspose.barcode.barcoderecognition/multidecodetype/tryparse/)(string, out MultiDecodeType) | MultiDecodeType'ın dize temsilini örneğine dönüştürür. Dönen değer dönüşümün başarılı olup olmadığını gösterir. |

## Örnekler

Bu örnek, SingleDecodeType ve MultiDecode tiplerini birleştiren bileşik MultiDecode tiplerinin nasıl oluşturulacağını gösterir.

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

### Ayrıca Bakınız

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


