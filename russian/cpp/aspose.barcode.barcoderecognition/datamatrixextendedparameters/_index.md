---
title: "Класс Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters"
linktitle: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Класс Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters. Сохраняет специальные данные распознанного штрихкода DataMatrix в C++."
type: docs
weight: 1500
url: /ru/cpp/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class


Сохраняет специальные данные распознанного штрихкода [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)

```cpp
class DataMatrixExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Описание |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** проверяет, имеют ли все параметры только значения по умолчанию |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или перепрограммирования считывателя штрихкодов. Значение по умолчанию — false. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Получает ID [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) штрихкода в режиме Structured Append. ID начинается с 1 и должен быть меньше или равен количеству штрихкодов. Значение по умолчанию — -1. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Получает количество штрихкодов [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) в режиме Structured Append. Значение по умолчанию — -1. Количество должно быть в диапазоне от 1 до 35. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Получает ID [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) штрихкода в режиме Structured Append. ID начинается с 1 и должен быть меньше или равен количеству штрихкодов. Значение по умолчанию — -1. |
| [GetHashCode](./gethashcode/)() const override | Возвращает хеш-код для данного экземпляра. |
| [ToString](./tostring/)() const override | Возвращает человекочитаемое строковое представление этого [DataMatrixExtendedParameters](./). |
## Примечания


Этот пример показывает, как получить необработанные значения [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)
```cpp
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

## См. также

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
