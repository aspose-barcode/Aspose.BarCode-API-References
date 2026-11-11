---
title: "Sınıf MaxiCodeCodetext"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.ComplexBarcode.MaxiCodeCodetext sınıfı. MaxiCode koduna gömülü metni kodlamak ve kodunu çözmek için temel sınıf."
type: docs
weight: 680
url: /tr/net/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class

MaxiCode kodunda gömülü metni kodlamak ve çözmek için temel sınıf.

```csharp
public abstract class MaxiCodeCodetext : IComplexCodetext
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ECIEncoding](../../aspose.barcode.complexbarcode/maxicodecodetext/eciencoding/) { get; set; } | ECI kodlamasını alır veya ayarlar. MaxiCodeEncodeMode otomatik olduğunda kullanılır. Varsayılan değer: ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.complexbarcode/maxicodecodetext/encodemode/) { get; set; } | MaxiCode kodlama modunu alır veya ayarlar. Varsayılan değer: Auto. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/maxicodecodetext/getbarcodetype/)() | Barkod tipini alır. |
| abstract [GetConstructedCodetext](../../aspose.barcode.complexbarcode/maxicodecodetext/getconstructedcodetext/)() | Kod metnini oluşturur |
| abstract [GetMode](../../aspose.barcode.complexbarcode/maxicodecodetext/getmode/)() | MaxiCode modunu alır. |
| abstract [InitFromString](../../aspose.barcode.complexbarcode/maxicodecodetext/initfromstring/)(string) | Oluşturulmuş kod metninden örneği başlatır. |

## Örnekler

Bu örnek, ham MaxiCode kod metnini MaxiCodeCodetext örneğine nasıl çözeceğinizi gösterir.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("MaxiCode mode: " + resultMaxiCodeCodetext.GetMode());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

### Ayrıca Bakınız

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


