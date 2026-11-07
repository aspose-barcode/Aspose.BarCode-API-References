---
title: "Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters класс"
linktitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters класс. Сохраняет специальные данные распознанного штрихкода Aztec в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class


Сохраняет специальные данные распознанного штрих‑кода Aztec

```cpp
class AztecExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Описание |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** проверяет, имеют ли все параметры только значения по умолчанию |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или перепрограммирования считывателя штрихкодов. Значение по умолчанию — false. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Получает идентификатор штрихкода Aztec в режиме структурированного добавления. Идентификатор начинается с 1 и должен быть меньше или равен количеству штрихкодов. Значение по умолчанию — 0. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Получает количество штрихкодов Aztec в режиме структурированного добавления. Значение по умолчанию — 0. Количество должно быть от 1 до 26. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Получает идентификатор файла режима структурированного добавления Aztec. Значение по умолчанию — пустая строка. |
| [GetHashCode](./gethashcode/)() const override | Возвращает хеш-код для данного экземпляра. |
| [ToString](./tostring/)() const override | Возвращает человекочитаемое строковое представление этого [AztecExtendedParameters](./). |
## Примечания


Этот пример показывает, как получить необработанные значения Aztec.
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Aztec))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("Aztec barcode ID: " + result.Extended.Aztec.StructuredAppendBarcodeId);
        Console.WriteLine("Aztec barcodes count: " + result.Extended.Aztec.StructuredAppendBarcodesCount);
        Console.WriteLine("Aztec file ID: " + result.Extended.Aztec.StructuredAppendFileId);
        Console.WriteLine("Aztec is reader initialization: " + result.Extended.Aztec.IsReaderInitialization);
    }
}
```

## См. также

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
