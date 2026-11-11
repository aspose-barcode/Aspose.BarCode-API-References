---
title: "Класс DotCodeExtendedParameters"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Aspose.BarCode.BarCodeRecognition.DotCodeExtendedParameters класс. Сохраняет специальные данные распознанного штрихкода DotCode"
type: docs
weight: 250
url: /ru/net/aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
## DotCodeExtendedParameters class

Сохраняет специальные данные распознанного штрихкода DotCode

```csharp
public sealed class DotCodeExtendedParameters : BaseExtendedParameters
```

## Свойства

| Имя | Описание |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Проверяет, имеют ли все параметры только значения по умолчанию |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/isreaderinitialization/) { get; } | Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или перепрограммирования считывателя штрих‑кода. Значение по умолчанию — false. |
| [StructuredAppendModeBarcodeId](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/structuredappendmodebarcodeid/) { get; } | Получает идентификатор штрих‑кода DotCode в режиме структурированного добавления. Идентификатор начинается с 1 и должен быть меньше или равен количеству штрих‑кодов. Значение по умолчанию — -1. |
| [StructuredAppendModeBarcodesCount](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/structuredappendmodebarcodescount/) { get; } | Получает количество штрих‑кодов DotCode в режиме структурированного добавления. Значение по умолчанию — -1. Количество должно быть в диапазоне от 1 до 35. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/equals/)(object) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению `DotCodeExtendedParameters`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/gethashcode/)() | Возвращает хеш-код для данного экземпляра. |
| override [ToString](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/tostring/)() | Возвращает человекочитаемое строковое представление этого `DotCodeExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/op_equality/) | Возвращает значение, указывающее, равны ли первое значение `DotCodeExtendedParameters` и второе. |
| [operator !=](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/op_inequality/) | Возвращает значение, указывающее, отличается ли первое значение `DotCodeExtendedParameters` от второго. |

## Примеры

Этот пример показывает, как получить необработанные значения DotCode

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DotCode))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DotCode barcode ID: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodeId);
        Console.WriteLine("DotCode barcodes count: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodesCount);
    }
}
```

### См. также

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


