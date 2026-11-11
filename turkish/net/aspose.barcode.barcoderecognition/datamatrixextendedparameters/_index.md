---
title: "Sınıf DataMatrixExtendedParameters"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.BarCodeRecognition.DataMatrixExtendedParameters sınıfı. DataMatrix tanımlanan barkodun özel verilerini depolar"
type: docs
weight: 220
url: /tr/net/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class

DataMatrix tanınan barkodun özel verilerini depolar

```csharp
public sealed class DataMatrixExtendedParameters : BaseExtendedParameters
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Tüm parametrelerin yalnızca varsayılan değerlere sahip olup olmadığını test eder |
| [IsReaderProgramming](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/isreaderprogramming/) { get; } | Kodun, barkod okuyucusunun başlatma veya yeniden programlama talimatları olarak aşağıdaki verileri yorumlamasını sağlamak için okuyucuya talimat vermek amacıyla kullanılıp kullanılmadığını gösterir. Varsayılan değer false'tur. |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodeid/) { get; } | DataMatrix yapılandırılmış ek modundaki barkodun kimliğini alır. Kimlik 1'den başlar ve barkod sayısına eşit ya da daha az olmalıdır. Varsayılan değer -1'dir. |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodescount/) { get; } | DataMatrix yapılandırılmış ek modundaki barkod sayısını alır. Varsayılan değer -1'dir. Sayı 1 ile 35 arasında olmalıdır. |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendfileid/) { get; } | DataMatrix yapılandırılmış ek modundaki barkodun kimliğini alır. Kimlik 1'den başlar ve barkod sayısına eşit ya da daha az olmalıdır. Varsayılan değer -1'dir. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/equals/)(object) | Bu örneğin belirtilen `DataMatrixExtendedParameters` değerine eşit olup olmadığını gösteren bir değer döndürür. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/gethashcode/)() | Bu örnek için karma kodunu döndürür. |
| override [ToString](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/tostring/)() | Bu `DataMatrixExtendedParameters` nesnesinin insan tarafından okunabilir bir dize temsili döndürür. |
| [operator ==](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_equality/) | İlk `DataMatrixExtendedParameters` değerinin ikinciye eşit olup olmadığını gösteren bir değer döndürür. |
| [operator !=](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_inequality/) | İlk `DataMatrixExtendedParameters` değerinin ikinciye farklı olup olmadığını gösteren bir değer döndürür. |

## Örnekler

Bu örnek, DataMatrix ham değerlerini nasıl alacağınızı gösterir

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DataMatrix))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DataMatrix barcode ID: " + result.Extended.DataMatrix.StructuredAppendBarcodeId);
        Console.WriteLine("DataMatrix barcodes count: " + result.Extended.DataMatrix.StructuredAppendBarcodesCount);
        Console.WriteLine("DataMatrix file ID: " + result.Extended.DataMatrix.StructuredAppendFileId);
        Console.WriteLine("DataMatrix is reader programming: " + result.Extended.DataMatrix.IsReaderProgramming);
    }
}
```

### Ayrıca Bakınız

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


