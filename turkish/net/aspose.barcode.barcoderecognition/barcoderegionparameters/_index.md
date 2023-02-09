---
title: BarCodeRegionParameters
second_title: Aspose.BarCode for .NET API Referansı
description: Tanınan barkodun bölgesini ve barkod açısını temsil eder
type: docs
weight: 80
url: /tr/net/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class

Tanınan barkodun bölgesini ve barkod açısını temsil eder

```csharp
public sealed class BarCodeRegionParameters
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Angle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/angle) { get; } | Barkodun açısını alır (0-360). |
| [Points](../../aspose.barcode.barcoderecognition/barcoderegionparameters/points) { get; } | alırPoints dizisi sınırlayıcı barkod bölgesi |
| [Quadrangle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/quadrangle) { get; } | alır[`Quadrangle`](../quadrangle) sınırlayıcı barkod bölgesi |
| [Rectangle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/rectangle) { get; } | alırRectangle sınırlayıcı barkod bölgesi |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderegionparameters/equals)(object) | Bu örneğin belirtilen bir örnekle eşit olup olmadığını gösteren bir değer döndürür[`BarCodeRegionParameters`](../barcoderegionparameters) değer. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderegionparameters/gethashcode)() | Bu örnek için karma kodu döndürür. |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderegionparameters/tostring)() | Bunun insan tarafından okunabilir bir dize temsilini döndürür[`BarCodeRegionParameters`](../barcoderegionparameters) . |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderegionparameters/op_equality) | İlkinin olup olmadığını gösteren bir değer döndürür.[`BarCodeRegionParameters`](../barcoderegionparameters) değer saniyeye eşittir. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderegionparameters/op_inequality) | İlkinin olup olmadığını gösteren bir değer döndürür.[`BarCodeRegionParameters`](../barcoderegionparameters) değer ikinciden farklı. |

### Örnekler

Bu örnek, barkod Açısı ve sınırlayıcı dörtgen değerlerinin nasıl alınacağını gösterir

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle)
    Next
End Using
```

### Ayrıca bakınız

* ad alanı [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* toplantı [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->