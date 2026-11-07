---
title: "Aspose::BarCode::Generation::QrExtCodetextBuilder class"
linktitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Как использовать класс Aspose::BarCode::Generation::QrExtCodetextBuilder в C++."
type: docs
weight: 4300
url: /ru/cpp/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class




```cpp
class QrExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Methods

| Method | Описание |
| --- | --- |
| [AddCodetextWithCompactionMode](./addcodetextwithcompactionmode/)(QrExtCompactionMode, System::String) | Добавляет кодовый текст с указанным режимом сжатия QR к элементам расширенного кодового текста. |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Добавляет текст кода с расширенным идентификатором канала |
| [AddFNC1FirstPosition](./addfnc1firstposition/)() | Устанавливает FNC1 в первой позиции. Если ранее был установлен другой режим FNC1, он заменяется. |
| [AddFNC1GroupSeparator](./addfnc1groupseparator/)() | Добавляет разделитель группы (GS - '\u001D') к элементам расширенного кодового текста |
| [AddFNC1SecondPosition](./addfnc1secondposition/)(System::String) | Устанавливает FNC1 во второй позиции. Если ранее был установлен другой режим FNC1, он заменяется. |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Добавляет простой текст кода к элементам расширенного текста кода |
| [Clear](./clear/)() override | Очищает элементы расширенного текста кода |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Генерирует расширенный текст кода из списка расширенного текста кода. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/)() |  |
## Примечания


Генератор расширенного кодового текста для 2D QR штрихкодов в режиме ExtendedCodetext режима EncodeMode

Используйте свойство TwoDDisplayText объекта [BarcodeGenerator](../barcodegenerator/), чтобы установить видимый текст, удаляя управляющие символы.

Этот пример показывает, как использовать первое положение FNC1 в расширенном режиме.
```cpp
[C#]
//создать текст кода
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1FirstPosition();
TextBuilder.AddPlainCodetext("000%89%%0");
TextBuilder.AddFNC1GroupSeparator();
TextBuilder.AddPlainCodetext("12345<FNC1>");

//генерировать текст кода
string codetext = TextBuilder.GetExtendedCodetext();

//генерировать
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


Этот пример показывает, как использовать второе положение FNC1 в расширенном режиме.
```cpp
[C#]
//создать текст кода
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456");

//генерировать текст кода
string codetext = TextBuilder.GetExtendedCodetext();

//генерировать
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


Этот пример показывает, как использовать многократный режим ECI в расширенном режиме.
```cpp
[C#]
//создать текст кода
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

//генерировать текст кода
string codetext = TextBuilder.GetExtendedCodetext();

//генерировать
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## См. также

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
