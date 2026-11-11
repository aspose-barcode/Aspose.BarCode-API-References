---
title: "Класс AztecExtCodetextBuilder"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Класс Aspose.BarCode.Generation.AztecExtCodetextBuilder. Генератор расширенного текста кода для штрихкодов Aztec в режиме ExtendedCodetext режима AztecEncodeMode."
type: docs
weight: 950
url: /ru/net/aspose.barcode.generation/aztecextcodetextbuilder/
---
## AztecExtCodetextBuilder class

Генератор расширенного текста кода для штрихкодов Aztec в режиме ExtendedCodetext режима AztecEncodeMode.

Используйте свойство TwoDDisplayText класса BarcodeGenerator, чтобы установить видимый текст, удаляя управляющие символы.

```csharp
public class AztecExtCodetextBuilder : ExtCodetextBuilder
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [AztecExtCodetextBuilder](aztecextcodetextbuilder/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Добавляет кодовый текст с расширенным идентификатором канала |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Добавляет простой кодовый текст к элементам расширенного кодового текста |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Очищает элементы расширенного кодового текста |
| override [GetExtendedCodetext](../../aspose.barcode.generation/aztecextcodetextbuilder/getextendedcodetext/)() | Генерирует расширенный кодовый текст из списка расширенного кодового текста. |

## Примеры

Этот пример показывает, как использовать AztecExtCodetextBuilder в расширенном режиме.

```csharp
[C#]
//создать кодовый текст
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//сгенерировать кодовый текст
string codetext = textBuilder.GetExtendedCodetext();    

//сгенерировать
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### См. также

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


