---
title: "Aspose::BarCode::Generation::AztecExtCodetextBuilder class"
linktitle: "AztecExtCodetextBuilder"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Как использовать класс Aspose::BarCode::Generation::AztecExtCodetextBuilder в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.barcode.generation/aztecextcodetextbuilder/
---
## AztecExtCodetextBuilder class




```cpp
class AztecExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Methods

| Method | Описание |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Добавляет текст кода с расширенным идентификатором канала |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Добавляет простой текст кода к элементам расширенного текста кода |
| virtual [Clear](../extcodetextbuilder/clear/)() | Очищает элементы расширенного текста кода |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Генерирует расширенный текст кода из списка расширенного текста кода. |
## Примечания


Генератор расширенного текста кода для штрих‑кодов Aztec в режиме ExtendedCodetext режима AztecEncodeMode

Используйте свойство TwoDDisplayText объекта [BarcodeGenerator](../barcodegenerator/), чтобы установить видимый текст, удаляя управляющие символы.

Этот пример показывает, как использовать [AztecExtCodetextBuilder](./) в расширенном режиме.
```cpp
[C#]
//создать текст кода
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//генерировать текст кода
string codetext = textBuilder.GetExtendedCodetext();

//генерировать
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## См. также

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
