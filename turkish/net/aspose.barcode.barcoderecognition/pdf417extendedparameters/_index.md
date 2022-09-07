---
title: Pdf417ExtendedParameters
second_title: Aspose.BarCode for .NET API Referansı
description: Tanınan barkodun MacroPdf417 meta veri bilgilerini saklar
type: docs
weight: 220
url: /tr/net/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class

Tanınan barkodun MacroPdf417 meta veri bilgilerini saklar

```csharp
public sealed class Pdf417ExtendedParameters : BaseExtendedParameters
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty) { get; } | Tüm parametrelerin yalnızca varsayılan değerlere sahip olup olmadığını test eder |
| [MacroPdf417Addressee](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417addressee) { get; } | Makro PDF417 muhatap adı (isteğe bağlı). |
| [MacroPdf417Checksum](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417checksum) { get; } | Makro PDF417 sağlama toplamı (isteğe bağlı). |
| [MacroPdf417FileID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417fileid) { get; } | Yalnızca MacroPdf417 ile kullanılabilen barkodun dosya kimliğini alır. |
| [MacroPdf417FileName](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filename) { get; } | Makro PDF417 dosya adı (isteğe bağlı). |
| [MacroPdf417FileSize](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filesize) { get; } | Makro PDF417 dosya boyutu (isteğe bağlı). |
| [MacroPdf417SegmentID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentid) { get; } | Yalnızca MacroPdf417 ile kullanılabilen barkodun segment kimliğini alır. |
| [MacroPdf417SegmentsCount](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentscount) { get; } | Makro pdf417 barkod segment sayısını alır. Varsayılan değer -1'dir. |
| [MacroPdf417Sender](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417sender) { get; } | Makro PDF417 gönderen adı (isteğe bağlı). |
| [MacroPdf417TimeStamp](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417timestamp) { get; } | Makro PDF417 zaman damgası (isteğe bağlı). |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/equals)(object) | Bu örneğin belirtilen bir örnekle eşit olup olmadığını gösteren bir değer döndürür[`Pdf417ExtendedParameters`](../pdf417extendedparameters) değer. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/gethashcode)() | Bu örnek için karma kodu döndürür. |
| override [ToString](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/tostring)() | Bunun insan tarafından okunabilir bir dize temsilini döndürür[`Pdf417ExtendedParameters`](../pdf417extendedparameters) . |
| [operator ==](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_equality) | İlkinin olup olmadığını gösteren bir değer döndürür.[`Pdf417ExtendedParameters`](../pdf417extendedparameters) değer saniyeye eşittir. |
| [operator !=](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_inequality) | İlkinin olup olmadığını gösteren bir değer döndürür.[`Pdf417ExtendedParameters`](../pdf417extendedparameters) değer ikinciden farklı. |

### Örnekler

Bu örnek, Makro Pdf417 meta verilerinin nasıl alınacağını gösterir

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345"))
{
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1;
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MacroPdf417))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID);
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount);
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.MacroPdf417, "12345")
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.MacroPdf417)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID)
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount)
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID)
    Next
End Using
```

### Ayrıca bakınız

* class [BaseExtendedParameters](../baseextendedparameters)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* toplantı [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
