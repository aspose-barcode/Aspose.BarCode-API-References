---
title: "Класс DotCodeExtCodetextBuilder"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Класс Aspose.BarCode.Generation.DotCodeExtCodetextBuilder. Расширенный генератор кодового текста для 2D штрихкодов DotCode в режиме ExtendedCodetext режима DotCodeEncodeMode"
type: docs
weight: 1250
url: /ru/net/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class

Расширенный генератор кодового текста для 2D штрихкодов DotCode в режиме ExtendedCodetext режима DotCodeEncodeMode

```csharp
public class DotCodeExtCodetextBuilder : ExtCodetextBuilder
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DotCodeExtCodetextBuilder](dotcodeextcodetextbuilder/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Добавляет кодовый текст с расширенным идентификатором канала |
| [AddFNC1FormatIdentifier](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc1formatidentifier/)() | Добавляет идентификатор формата FNC1 к элементам расширенного кодового текста |
| [AddFNC3ReaderInitialization](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3readerinitialization/)() | Добавляет инициализацию считывателя FNC3 к элементам расширенного кодового текста |
| [AddFNC3SymbolSeparator](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3symbolseparator/)() | Добавляет разделитель символа FNC3 к расширенным элементам codetext |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Добавляет простой кодовый текст к элементам расширенного кодового текста |
| [AddStructuredAppendMode](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addstructuredappendmode/)(int, int) | Добавляет режим структурного добавления к расширенным элементам codetext |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Очищает элементы расширенного кодового текста |
| override [GetExtendedCodetext](../../aspose.barcode.generation/dotcodeextcodetextbuilder/getextendedcodetext/)() | Генерирует расширенный кодовый текст из списка расширенного кодового текста. |

## Примеры

```csharp
[C#]
//Режим расширенного кодового текста
//создать кодовый текст
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

//сгенерировать кодовый текст
string codetext = textBuilder.GetExtendedCodetext();    

//сгенерировать
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### См. также

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


