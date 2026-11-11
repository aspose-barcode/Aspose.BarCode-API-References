---
title: "Sınıf Code128ExtendedParameters"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.BarCodeRecognition.Code128ExtendedParameters sınıf. Tanınan Code128 barkodunun özel verilerini depolar"
type: docs
weight: 180
url: /tr/net/aspose.barcode.barcoderecognition/code128extendedparameters/
---
## Code128ExtendedParameters class

Code128 tanınan barkodun özel verilerini depolar

Tanımlanan barkodun bölgesini ve barkod açısını temsil eder

```csharp
public sealed class Code128ExtendedParameters : BaseExtendedParameters
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Code128DataPortions](../../aspose.barcode.barcoderecognition/code128extendedparameters/code128dataportions/) { get; } | Tanımlanan Code128 barkodunun [`Code128DataPortion`](../code128dataportion/) dizisini alır |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Tüm parametrelerin yalnızca varsayılan değerlere sahip olup olmadığını test eder |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/code128extendedparameters/equals/)(object) | Bu örneğin belirtilen `Code128ExtendedParameters` değerine eşit olup olmadığını gösteren bir değer döndürür. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/code128extendedparameters/gethashcode/)() | Bu örnek için karma kodunu döndürür. |
| override [ToString](../../aspose.barcode.barcoderecognition/code128extendedparameters/tostring/)() | Bu `Code128ExtendedParameters` nesnesinin insan tarafından okunabilir dize temsilini döndürür. |
| [operator ==](../../aspose.barcode.barcoderecognition/code128extendedparameters/op_equality/) | İlk `Code128ExtendedParameters` değerinin ikinciye eşit olup olmadığını gösteren bir değer döndürür. |
| [operator !=](../../aspose.barcode.barcoderecognition/code128extendedparameters/op_inequality/) | İlk `Code128ExtendedParameters` değerinin ikinciye farklı olup olmadığını gösteren bir değer döndürür. |

## Örnekler

Bu örnek, code128 ham değerlerinin nasıl alınacağını gösterir

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128)
    Next
End Using
```

### Ayrıca Bakınız

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


