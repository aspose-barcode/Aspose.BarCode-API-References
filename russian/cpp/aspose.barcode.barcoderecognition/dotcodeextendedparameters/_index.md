---
title: "Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters class"
linktitle: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters class. Сохраняет специальные данные распознанного штрихкода DotCode в C++."
type: docs
weight: 2000
url: /ru/cpp/aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
## DotCodeExtendedParameters class


Сохраняет специальные данные распознанного штрих‑кода DotCode

```cpp
class DotCodeExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Описание |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** проверяет, имеют ли все параметры только значения по умолчанию |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или перепрограммирования считывателя штрихкодов. Значение по умолчанию — false. |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | Получает ID штрихкода режима структурного добавления DotCode. ID начинается с 1 и должен быть меньше или равен количеству штрихкодов. Значение по умолчанию — -1. |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | Получает количество штрихкодов режима структурного добавления DotCode. Значение по умолчанию — -1. Количество должно быть в диапазоне от 1 до 35. |
| [GetHashCode](./gethashcode/)() const override | Возвращает хеш-код для данного экземпляра. |
| [ToString](./tostring/)() const override | Возвращает человекочитаемое строковое представление этого [DotCodeExtendedParameters](./). |
## Примечания


Этот пример показывает, как получить необработанные значения DotCode.
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DotCode))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DotCode barcode ID: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodeId);
        Console.WriteLine("DotCode barcodes count: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodesCount);
    }
}
```

## См. также

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
