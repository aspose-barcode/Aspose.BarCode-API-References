---
title: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters sınıfı"
linktitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters sınıfı. C++'da tanınan barkodun MacroPdf417 meta verilerini depolar."
type: docs
weight: 2800
url: /tr/cpp/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class


Tanımlanan barkodun MacroPdf417 meta veri bilgilerini depolar

```cpp
class Pdf417ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | MicroPdf417 barkodunun 908, 909, 910 veya 911 Code 128 taklit kod kelimeleriyle kodlandığını gösteren bayrak. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** tüm parametrelerin yalnızca varsayılan değerleri içerip içermediğini. |
| [get_IsLinked](./get_islinked/)() const | Barkodun 1D barkoda bağlanması gerektiğini gösteren bayrak. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Sembolde bulunan verileri okuyucu başlatma programlaması olarak yorumlaması için okuyucuya talimat vermek amacıyla kullanılır. |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | Macro PDF417 alıcı adı (isteğe bağlı). |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | Macro PDF417 checksum (isteğe bağlı). |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | MacroPdf417 ile yalnızca mevcut olan barkodun dosya kimliğini alır. |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | Macro PDF417 dosya adı (isteğe bağlı). |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | Macro PDF417 dosya boyutu (isteğe bağlı). |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | MacroPdf417 ile yalnızca mevcut olan barkodun segment kimliğini alır. |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | Macro pdf417 barkod segment sayısını alır. Varsayılan değer -1'dir. |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | Macro PDF417 gönderici adı (isteğe bağlı). |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | Segmentin bir Macro PDF417 dosyasının son segmenti olup olmadığını gösterir. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | Macro PDF417 zaman damgası (isteğe bağlı). |
| [GetHashCode](./gethashcode/)() const override | Bu örnek için hash kodunu döndürür. |
| [ToString](./tostring/)() const override | Bu [Pdf417ExtendedParameters](./) nesnesinin insan tarafından okunabilir dize temsilini döndürür. |
## Açıklamalar


Bu örnek, Macro Pdf417 meta verilerini nasıl alacağınızı gösterir.
```cpp
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

## Ayrıca Bakınız

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
