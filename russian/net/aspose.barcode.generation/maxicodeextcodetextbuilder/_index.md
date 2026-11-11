---
title: "Класс MaxiCodeExtCodetextBuilder"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Класс Aspose.BarCode.Generation.MaxiCodeExtCodetextBuilder. Расширенный генератор кодового текста для штрихкодов MaxiCode в режиме ExtendedCodetext режима MaxiCodeEncodeMode"
type: docs
weight: 1470
url: /ru/net/aspose.barcode.generation/maxicodeextcodetextbuilder/
---
## MaxiCodeExtCodetextBuilder class

Расширенный генератор кодового текста для штрихкодов MaxiCode в режиме ExtendedCodetext режима MaxiCodeEncodeMode

Используйте свойство TwoDDisplayText класса BarcodeGenerator, чтобы установить видимый текст, удаляя управляющие символы.

```csharp
public class MaxiCodeExtCodetextBuilder : ExtCodetextBuilder
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MaxiCodeExtCodetextBuilder](maxicodeextcodetextbuilder/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Добавляет кодовый текст с расширенным идентификатором канала |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Добавляет простой кодовый текст к элементам расширенного кодового текста |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Очищает элементы расширенного кодового текста |
| override [GetExtendedCodetext](../../aspose.barcode.generation/maxicodeextcodetextbuilder/getextendedcodetext/)() | Генерирует расширенный кодовый текст из списка расширенного кодового текста. |

## Примеры

Этот пример показывает, как использовать MaxiCodeExtCodetextBuilder в расширенном режиме.

```csharp
[C#]
//создать кодовый текст
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//сгенерировать кодовый текст
string codetext = textBuilder.GetExtendedCodetext();    

//сгенерировать
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### См. также

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


