---
title: "enum"
linktitle: "ChecksumValidation"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "C++'da enum nasıl kullanılır?"
type: docs
weight: 3300
url: /tr/cpp/aspose.barcode.barcoderecognition/checksumvalidation/
---
## ChecksumValidation enum




```cpp
enum class ChecksumValidation
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Varsayılan | 0 | Eğer kontrol toplamı spesifikasyon tarafından gerektiriliyorsa - doğrulanacaktır. |
| Açık | 1 | Mümkünse her zaman kontrol toplamını doğrula. |
| Kapalı | 2 | Kontrol toplamını doğrulama. |

## Açıklamalar


1D ve Posta barkodları için tanıma sırasında kontrol toplamı doğrulamasını etkinleştir.

Varsayılan, kontrol toplamı içermesi zorunlu olan sembolojiler için Evet, sadece mümkün olduğu durumlarda Hayır olarak değerlendirilir.

Kontrol toplamı hiç kullanılmaz: Codabar, PatchCode, Pharmacode, DataLogic2of5

Kontrol toplamı mümkündür: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Kontrol toplamı her zaman kullanılır: Diğer sembolojiler

Bu örnek, ChecksumValidation'ın tanıma kalitesi ve sonuçları üzerindeki etkisini gösterir.
```cpp
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

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
