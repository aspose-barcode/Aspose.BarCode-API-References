---
title: "Sınıf OneDExtendedParameters"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.BarCodeRecognition.OneDExtendedParameters sınıfı. Ayrı kod metni ve kontrol toplamı gibi tanınan 1D barkodun özel verilerini depolar."
type: docs
weight: 330
url: /tr/net/aspose.barcode.barcoderecognition/onedextendedparameters/
---
## OneDExtendedParameters class

Ayrı kod metni ve kontrol toplamı gibi 1D tanımlanan barkodun özel verilerini depolar

```csharp
public sealed class OneDExtendedParameters : BaseExtendedParameters
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [CheckSum](../../aspose.barcode.barcoderecognition/onedextendedparameters/checksum/) { get; } | 1D barkodlar için kontrol toplamını alır. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Tüm parametrelerin yalnızca varsayılan değerlere sahip olup olmadığını test eder |
| [Value](../../aspose.barcode.barcoderecognition/onedextendedparameters/value/) { get; } | Kontrol toplamı olmadan 1D barkodların kod metnini alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/onedextendedparameters/equals/)(object) | Bu örneğin belirtilen `OneDExtendedParameters` değerine eşit olup olmadığını gösteren bir değer döndürür. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/onedextendedparameters/gethashcode/)() | Bu örnek için karma kodunu döndürür. |
| override [ToString](../../aspose.barcode.barcoderecognition/onedextendedparameters/tostring/)() | Bu `OneDExtendedParameters`'ın insan tarafından okunabilir dize temsilini döndürür. |
| [operator ==](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_equality/) | İlk `OneDExtendedParameters` değerinin ikinciye eşit olup olmadığını gösteren bir değer döndürür. |
| [operator !=](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_inequality/) | İlk `OneDExtendedParameters` değerinin ikinciden farklı olup olmadığını gösteren bir değer döndürür. |

## Örnekler

Bu örnek, 1D barkod değerini ve kontrol toplamını nasıl alacağınızı gösterir.

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.EAN13, "1234567890128")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

### Ayrıca Bakınız

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


