---
title: "ChecksumValidation Enumı"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.BarCodeRecognition.ChecksumValidation enumı. 1D ve Posta barkodları için tanıma sırasında sağlama toplamı doğrulamasını etkinleştirir"
type: docs
weight: 150
url: /tr/net/aspose.barcode.barcoderecognition/checksumvalidation/
---
## ChecksumValidation enumeration

1D ve Posta barkodları için tanıma sırasında kontrol toplamı doğrulamasını etkinleştir.

Varsayılan, sağlama toplamı içermesi gereken sembolojiler için Evet, sadece mümkün olduğu durumlarda Hayır olarak değerlendirilir.

Sağlama toplamı asla kullanılmaz: Codabar, PatchCode, Pharmacode, DataLogic2of5

Kontrol toplamı mümkündür: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Kontrol toplamı her zaman kullanılır: Diğer sembolojiler

```csharp
public enum ChecksumValidation
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Default | `0` | Eğer kontrol toplamı spesifikasyon tarafından gerektiriliyorsa - doğrulanacaktır. |
| On | `1` | Mümkünse her zaman kontrol toplamını doğrulayın. |
| Off | `2` | Kontrol toplamını doğrulamayın. |

## Örnekler

Bu örnek, ChecksumValidation'ın tanı kalitesi ve sonuçları üzerindeki etkisini gösterir

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //checksum devre dışı
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.Off;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //checksum etkin
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.On;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
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
    'checksum disabled
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.Off
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    'checksum enabled
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.On
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


