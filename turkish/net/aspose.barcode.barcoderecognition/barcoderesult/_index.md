---
title: "Class BarCodeResult"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.BarCodeRecognition.BarCodeResult sınıfı. SingleDecodeType tipi, String kodmetni, BarCodeRegionParameters bölgesi ve diğer parametreler gibi tanınan barkod verilerini depolar."
type: docs
weight: 100
url: /tr/net/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class

[`SingleDecodeType`](../singledecodetype/) tipi, String kodmetni, [`BarCodeRegionParameters`](../barcoderegionparameters/) bölgesi ve diğer parametreler gibi tanınan barkod verilerini depolar.

```csharp
public sealed class BarCodeResult : ICloneable, IEquatable<BarCodeResult>
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [BarCodeResult](barcoderesult/)(BarCodeResult) | `BarCodeResult` sınıfının bir kopyasını oluşturur. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [CodeBytes](../../aspose.barcode.barcoderecognition/barcoderesult/codebytes/) { get; } | Kodun kodlanmış baytlarını alır. |
| [CodeText](../../aspose.barcode.barcoderecognition/barcoderesult/codetext/) { get; } | Kod metnini alır. |
| [CodeType](../../aspose.barcode.barcoderecognition/barcoderesult/codetype/) { get; } | Barkod tipini alır. |
| [CodeTypeName](../../aspose.barcode.barcoderecognition/barcoderesult/codetypename/) { get; } | Barkod tipinin adını alır. |
| [Confidence](../../aspose.barcode.barcoderecognition/barcoderesult/confidence/) { get; } | Tanınan barkodun tanıma güven düzeyini alır. |
| [Extended](../../aspose.barcode.barcoderecognition/barcoderesult/extended/) { get; } | Tanınan barkodun genişletilmiş parametrelerini alır. |
| [IsoSymbolQuality](../../aspose.barcode.barcoderecognition/barcoderesult/isosymbolquality/) { get; } | Tanımlanan barkod için ISO/IEC sembol kalite değerlendirme sonuçlarını alır. |
| [ReadingQuality](../../aspose.barcode.barcoderecognition/barcoderesult/readingquality/) { get; } | Okuma kalitesini alır. 1D ve posta barkodları için çalışır. |
| [Region](../../aspose.barcode.barcoderecognition/barcoderesult/region/) { get; } | Barkod bölgesini alır |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Clone](../../aspose.barcode.barcoderecognition/barcoderesult/clone/)() | `BarCodeResult` sınıfının bir kopyasını oluşturur. |
| [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals/#equals)(BarCodeResult) | Bu örneğin belirtilen bir `BarCodeResult` değerine eşit olup olmadığını gösteren bir değer döndürür. |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals/#equals_1)(object) | Bu örneğin belirtilen bir `BarCodeResult` değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [GetCodeText](../../aspose.barcode.barcoderecognition/barcoderesult/getcodetext/)(Encoding) | Kod metnini kodlamasıyla birlikte alır. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderesult/gethashcode/)() | Bu örnek için karma kodunu döndürür. |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderesult/tostring/)() | Bu `BarCodeResult` nesnesinin insan tarafından okunabilir bir dize temsilini döndürür. |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderesult/op_equality/) | İlk `BarCodeResult` değerinin ikinciye eşit olup olmadığını gösteren bir değer döndürür. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderesult/op_inequality/) | İlk `BarCodeResult` değerinin ikinciye farklı olup olmadığını gösteren bir değer döndürür. |

## Örnekler

Bu örnek, BarCodeResult elde etmenin nasıl yapılacağını gösterir.

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
    Next
End Using
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


