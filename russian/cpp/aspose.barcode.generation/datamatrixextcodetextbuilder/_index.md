---
title: "Класс Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Как использовать класс Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder в C++."
type: docs
weight: 1900
url: /ru/cpp/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class




```cpp
class DataMatrixExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Methods

| Method | Описание |
| --- | --- |
| [AddCodetextWithEncodeMode](./addcodetextwithencodemode/)(DataMatrixEncodeMode, System::String) | Добавляет codetext с заданным режимом кодирования к элементам расширенного codetext. |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Добавляет текст кода с расширенным идентификатором канала |
| [AddECICodetextWithEncodeMode](./addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, System::String) | Добавляет codetext с Extended Channel Identifier с заданным режимом кодирования. |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Добавляет простой текст кода к элементам расширенного текста кода |
| virtual [Clear](../extcodetextbuilder/clear/)() | Очищает элементы расширенного текста кода |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Генерирует расширенный текст кода из списка расширенного текста кода. |
## Примечания


Генератор расширенного codetext для 2D DataMatrix штрихкодов в режиме ExtendedCodetext EncodeMode.


```cpp
[C#]
//Режим расширенного текста кода

//создать текст кода
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//генерировать текст кода
string codetext = textBuilder.GetExtendedCodetext();

//генерировать
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## См. также

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
