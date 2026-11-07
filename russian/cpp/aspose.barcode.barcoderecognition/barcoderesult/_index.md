---
title: "Класс Aspose::BarCode::BarCodeRecognition::BarCodeResult"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Класс Aspose::BarCode::BarCodeRecognition::BarCodeResult. Сохраняет распознанные данные штрихкода, такие как тип SingleDecodeType, System::String codetext, BarCodeRegionParameters region и другие параметры в C++."
type: docs
weight: 700
url: /ru/cpp/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class


Сохраняет распознанные данные штрихкода, такие как тип [SingleDecodeType](../singledecodetype/), **System::String** codetext, регион [BarCodeRegionParameters](../barcoderegionparameters/) и другие параметры

```cpp
class BarCodeResult : public System::ICloneable,
                      public System::IEquatable<System::SharedPtr<BarCodeResult>>
```

## Methods

| Method | Описание |
| --- | --- |
| [BarCodeResult](./barcoderesult/)(System::SharedPtr\<BarCodeResult\>) | Создает копию класса [BarCodeResult](./). |
| [Clone](./clone/)() override | Создает копию класса [BarCodeResult](./). |
| [Equals](./equals/)(System::SharedPtr\<BarCodeResult\>) override | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению [BarCodeResult](./). |
| [get_CodeBytes](./get_codebytes/)() const | Получает закодированные байты кода |
| [get_CodeText](./get_codetext/)() const | Получает текст кода |
| [get_CodeType](./get_codetype/)() const | Получает тип штрихкода |
| [get_CodeTypeName](./get_codetypename/)() | Получает название типа штрихкода |
| [get_Confidence](./get_confidence/)() const | Получает уровень уверенности распознавания распознанного штрихкода |
| [get_Extended](./get_extended/)() const | Получает расширенные параметры распознанного штрихкода |
| [get_IsoSymbolQuality](./get_isosymbolquality/)() const | Получает результаты оценки качества символов ISO/IEC для распознанного штрихкода. |
| [get_ReadingQuality](./get_readingquality/)() const | Получает качество чтения. Работает с 1D и почтовыми штрихкодами. |
| [get_Region](./get_region/)() const | Получает регион штрихкода |
| [GetCodeText](./getcodetext/)(System::SharedPtr\<System::Text::Encoding\>) | Получает текст кода с кодировкой. |
| [GetHashCode](./gethashcode/)() const override | Возвращает хеш-код для данного экземпляра. |
| [ToString](./tostring/)() const override | Возвращает человекочитаемое строковое представление этого [BarCodeResult](./). |
## Примечания


Этот пример показывает, как получить [BarCodeResult](./).
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

## См. также

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
