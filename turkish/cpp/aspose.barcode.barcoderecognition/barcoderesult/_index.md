---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeResult sınıfı"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeResult sınıfı. Tanımlanmış barkod verilerini, SingleDecodeType türü, System::String codetext, BarCodeRegionParameters bölgesi ve diğer parametreler gibi, C++'da depolar."
type: docs
weight: 700
url: /tr/cpp/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class


Tanımlanmış barkod verilerini, [SingleDecodeType](../singledecodetype/) türü, **System::String** codetext, [BarCodeRegionParameters](../barcoderegionparameters/) bölgesi ve diğer parametreler olarak depolar.

```cpp
class BarCodeResult : public System::ICloneable,
                      public System::IEquatable<System::SharedPtr<BarCodeResult>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [BarCodeResult](./barcoderesult/)(System::SharedPtr\<BarCodeResult\>) | Bir [BarCodeResult](./) sınıfının bir kopyasını oluşturur. |
| [Clone](./clone/)() override | Bir [BarCodeResult](./) sınıfının kopyasını oluşturur. |
| [Equals](./equals/)(System::SharedPtr\<BarCodeResult\>) override | Bu örneğin belirtilen bir [BarCodeResult](./) değeriyle eşit olup olmadığını gösteren bir değer döndürür. |
| [get_CodeBytes](./get_codebytes/)() const | Kodlanmış kod baytlarını alır |
| [get_CodeText](./get_codetext/)() const | Kod metnini alır |
| [get_CodeType](./get_codetype/)() const | Barkod tipini alır |
| [get_CodeTypeName](./get_codetypename/)() | Barkod tipinin adını alır |
| [get_Confidence](./get_confidence/)() const | Tanımlanan barkodun tanıma güven düzeyini alır |
| [get_Extended](./get_extended/)() const | Tanımlanan barkodun genişletilmiş parametrelerini alır |
| [get_IsoSymbolQuality](./get_isosymbolquality/)() const | Tanımlanan barkod için ISO/IEC sembol kalite değerlendirme sonuçlarını alır. |
| [get_ReadingQuality](./get_readingquality/)() const | Okuma kalitesini alır. 1D ve posta barkodları için çalışır. |
| [get_Region](./get_region/)() const | Barkod bölgesini alır |
| [GetCodeText](./getcodetext/)(System::SharedPtr\<System::Text::Encoding\>) | Kod metnini kodlamayla birlikte alır. |
| [GetHashCode](./gethashcode/)() const override | Bu örnek için hash kodunu döndürür. |
| [ToString](./tostring/)() const override | Bu [BarCodeResult](./) nesnesinin insan tarafından okunabilir bir dize temsili döndürür. |
## Açıklamalar


Bu örnek, [BarCodeResult](./) elde etmenin nasıl yapılacağını gösterir.
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
    Next
End Using
```

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
