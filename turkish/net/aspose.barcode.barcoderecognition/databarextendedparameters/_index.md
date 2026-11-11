---
title: "DataBarExtendedParameters Sınıfı"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.BarCodeRecognition.DataBarExtendedParameters sınıfı. Tanınan barkodun DataBar ek bilgilerini depolar"
type: docs
weight: 210
url: /tr/net/aspose.barcode.barcoderecognition/databarextendedparameters/
---
## DataBarExtendedParameters class

Tanımlanan barkodun DataBar ek bilgilerini depolar

```csharp
public sealed class DataBarExtendedParameters : BaseExtendedParameters
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Is2DCompositeComponent](../../aspose.barcode.barcoderecognition/databarextendedparameters/is2dcompositecomponent/) { get; } | DataBar 2D birleşik bileşen bayrağını alır. Varsayılan değer false'tur. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Tüm parametrelerin yalnızca varsayılan değerlere sahip olup olmadığını test eder |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/databarextendedparameters/equals/)(object) | Bu örneğin belirtilen `DataBarExtendedParameters` değerine eşit olup olmadığını gösteren bir değer döndürür. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/databarextendedparameters/gethashcode/)() | Bu örnek için karma kodunu döndürür. |
| override [ToString](../../aspose.barcode.barcoderecognition/databarextendedparameters/tostring/)() | Bu `DataBarExtendedParameters` nesnesinin insan tarafından okunabilir bir dize temsilini döndürür. |
| [operator ==](../../aspose.barcode.barcoderecognition/databarextendedparameters/op_equality/) | İlk `DataBarExtendedParameters` değerinin ikinciye eşit olup olmadığını gösteren bir değer döndürür. |
| [operator !=](../../aspose.barcode.barcoderecognition/databarextendedparameters/op_inequality/) | İlk `DataBarExtendedParameters` değerinin ikinciye farklı olup olmadığını gösteren bir değer döndürür. |

## Örnekler

Bu örnek, DataBar ek bilgilerini nasıl alacağınızı gösterir

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DatabarOmniDirectional))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.DatabarOmniDirectional)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
    Next
End Using
```

### Ayrıca Bakınız

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


