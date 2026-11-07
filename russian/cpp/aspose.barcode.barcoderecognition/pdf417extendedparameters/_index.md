---
title: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters класс"
linktitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters класс. Сохраняет информацию о метаданных MacroPdf417 распознанного штрихкода в C++."
type: docs
weight: 2800
url: /ru/cpp/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class


Сохраняет метаданные MacroPdf417 распознанного штрихкода

```cpp
class Pdf417ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Описание |
| --- | --- |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | Флаг, указывающий, что штрихкод MicroPdf417 закодирован кодовыми словами эмуляции Code 128 908, 909, 910 или 911. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** проверяет, имеют ли все параметры только значения по умолчанию |
| [get_IsLinked](./get_islinked/)() const | Флаг, указывающий, что штрихкод должен быть связан с 1D штрихкодом. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | Имя получателя Macro PDF417 (необязательно). |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | Контрольная сумма Macro PDF417 (необязательно). |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | Получает идентификатор файла штрихкода, доступный только с MacroPdf417. |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | Имя файла Macro PDF417 (необязательно). |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | Размер файла Macro PDF417 (необязательно). |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | Получает идентификатор сегмента штрихкода, доступный только с MacroPdf417. |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | Получает количество сегментов штрихкода macro pdf417. Значение по умолчанию — -1. |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | Имя отправителя Macro PDF417 (необязательно). |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | Указывает, является ли сегмент последним сегментом файла Macro PDF417. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | Метка времени Macro PDF417 (необязательно). |
| [GetHashCode](./gethashcode/)() const override | Возвращает хеш-код для данного экземпляра. |
| [ToString](./tostring/)() const override | Возвращает человекочитаемое строковое представление этого [Pdf417ExtendedParameters](./). |
## Примечания


Этот пример показывает, как получить метаданные Macro Pdf417.
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

## См. также

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
