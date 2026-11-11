---
title: "Класс DataMatrixExtCodetextBuilder"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Класс Aspose.BarCode.Generation.DataMatrixExtCodetextBuilder. Генератор расширенного кодового текста для 2D штрихкодов DataMatrix в режиме ExtendedCodetext EncodeMode."
type: docs
weight: 1210
url: /ru/net/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class

Генератор расширенного кодового текста для 2D штрихкодов DataMatrix в режиме ExtendedCodetext EncodeMode.

```csharp
public class DataMatrixExtCodetextBuilder : ExtCodetextBuilder
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DataMatrixExtCodetextBuilder](datamatrixextcodetextbuilder/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddCodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addcodetextwithencodemode/)(DataMatrixEncodeMode, string) | Добавляет кодовый текст с заданным режимом кодирования к элементам расширенного кодового текста |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Добавляет кодовый текст с расширенным идентификатором канала |
| [AddECICodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, string) | Добавляет кодовый текст с расширенным идентификатором канала и заданным режимом кодирования |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Добавляет простой кодовый текст к элементам расширенного кодового текста |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Очищает элементы расширенного кодового текста |
| override [GetExtendedCodetext](../../aspose.barcode.generation/datamatrixextcodetextbuilder/getextendedcodetext/)() | Генерирует расширенный кодовый текст из списка расширенного кодового текста. |

## Примеры

```csharp
[C#]
//Режим расширенного кодового текста

//создать кодовый текст
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//сгенерировать кодовый текст
string codetext = textBuilder.GetExtendedCodetext();    

//сгенерировать
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### См. также

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


