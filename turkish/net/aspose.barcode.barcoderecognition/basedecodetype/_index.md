---
title: "Sınıf BaseDecodeType"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.BarCodeRecognition.BaseDecodeType sınıfı. MultiDecodeType ve SingleDecodeType için temel sınıf"
type: docs
weight: 130
url: /tr/net/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class

MultiDecodeType ve SingleDecodeType için temel sınıf.

```csharp
public abstract class BaseDecodeType : IEquatable<BaseDecodeType>
```

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| abstract [ContainsAny](../../aspose.barcode.barcoderecognition/basedecodetype/containsany/)(params BaseDecodeType[]) | Verilen kod çözme türlerinden herhangi birinin dahil edilip edilmediğini belirler |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals)(BaseDecodeType) | Bu örneğin belirtilen `BaseDecodeType` değerine eşit olup olmadığını gösteren bir değer döndürür. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_1)(MultiDecodeType) | Bu örneğin belirtilen [`MultiDecodeType`](../multidecodetype/) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| override [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_3)(object) | Bu örneğin belirtilen `BaseDecodeType` değerine eşit olup olmadığını gösteren bir değer döndürür. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_2)(SingleDecodeType) | Bu örneğin belirtilen [`SingleDecodeType`](../singledecodetype/) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/basedecodetype/gethashcode/)() | Bu örnek için karma kodunu döndürür. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse)(string, out BaseDecodeType) | BaseDecodeType'ın dize temsilini, somut tür belirlenerek örneğine dönüştürür. Dönen değer dönüşümün başarılı olup olmadığını gösterir. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse_1)(string, out MultiDecodeType) | MultiDecodeType'ın dize temsilini örneğine dönüştürür. Dönen değer dönüşümün başarılı olup olmadığını gösterir. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse_2)(string, out SingleDecodeType) | SingleDecodeType'ın dize temsilini örneğine dönüştürür. Dönen değer dönüşümün başarılı olup olmadığını gösterir. |

## Örnekler

Bu örnek, BaseDecodeType'ı SingleDecodeType ve MultiDecodeType ile nasıl kullanacağınızı gösterir

```csharp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


