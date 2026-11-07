---
title: "Aspose::BarCode::Generation::DotCodeExtCodetextBuilder класс"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Как использовать класс Aspose::BarCode::Generation::DotCodeExtCodetextBuilder в C++."
type: docs
weight: 2100
url: /ru/cpp/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class




```cpp
class DotCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Methods

| Method | Описание |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Добавляет текст кода с расширенным идентификатором канала |
| [AddFNC1FormatIdentifier](./addfnc1formatidentifier/)() | Добавляет идентификатор формата FNC1 к элементам расширенного codetext. |
| [AddFNC3ReaderInitialization](./addfnc3readerinitialization/)() | Добавляет инициализацию считывателя FNC3 к элементам расширенного codetext. |
| [AddFNC3SymbolSeparator](./addfnc3symbolseparator/)() | Добавляет разделитель символов FNC3 к элементам расширенного codetext. |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Добавляет простой текст кода к элементам расширенного текста кода |
| [AddStructuredAppendMode](./addstructuredappendmode/)(int32_t, int32_t) | Добавляет режим структурированного добавления к элементам расширенного codetext. |
| virtual [Clear](../extcodetextbuilder/clear/)() | Очищает элементы расширенного текста кода |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Генерирует расширенный текст кода из списка расширенного текста кода. |
## Примечания


Генератор расширенного codetext для 2D штрихкодов DotCode для режима ExtendedCodetext в DotCodeEncodeMode.


```cpp
[C#]
//Режим расширенного текста кода
//создать текст кода
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC3ReaderInitialization();
textBuilder.AddPlainCodetext("Reader initialization info");

//генерировать текст кода
string codetext = textBuilder.GetExtendedCodetext();

//генерировать
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## См. также

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
