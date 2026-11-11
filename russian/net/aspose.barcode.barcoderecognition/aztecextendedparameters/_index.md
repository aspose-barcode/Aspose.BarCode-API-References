---
title: "Класс AztecExtendedParameters"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Класс Aspose.BarCode.BarCodeRecognition.AztecExtendedParameters. Сохраняет специальные данные распознанного штрих‑кода Aztec"
type: docs
weight: 40
url: /ru/net/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class

Сохраняет специальные данные распознанного штрих‑кода Aztec

```csharp
public sealed class AztecExtendedParameters : BaseExtendedParameters
```

## Свойства

| Имя | Описание |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Проверяет, имеют ли все параметры только значения по умолчанию |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/aztecextendedparameters/isreaderinitialization/) { get; } | Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или перепрограммирования считывателя штрих‑кода. Значение по умолчанию — false. |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendbarcodeid/) { get; } | Получает ID штрих‑кода Aztec в режиме структурированного добавления. ID начинается с 1 и должен быть меньше или равен количеству штрих‑кодов. Значение по умолчанию — 0. |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendbarcodescount/) { get; } | Получает количество штрих‑кодов в режиме структурированного добавления Aztec. Значение по умолчанию — 0. Количество должно быть от 1 до 26. |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendfileid/) { get; } | Получает идентификатор файла в режиме структурированного добавления Aztec. Значение по умолчанию — пустая строка |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/aztecextendedparameters/equals/)(object) | Возвращает значение, указывающее, равен ли данный экземпляр указанному значению `AztecExtendedParameters`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/aztecextendedparameters/gethashcode/)() | Возвращает хеш-код для данного экземпляра. |
| override [ToString](../../aspose.barcode.barcoderecognition/aztecextendedparameters/tostring/)() | Возвращает человекочитаемое строковое представление этого `AztecExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/aztecextendedparameters/op_equality/) | Возвращает значение, указывающее, равны ли первое значение `AztecExtendedParameters` и второе. |
| [operator !=](../../aspose.barcode.barcoderecognition/aztecextendedparameters/op_inequality/) | Возвращает значение, указывающее, отличается ли первое значение `AztecExtendedParameters` от второго. |

## Примеры

Этот пример показывает, как получить необработанные значения Aztec

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Aztec))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("Aztec barcode ID: " + result.Extended.Aztec.StructuredAppendBarcodeId);
        Console.WriteLine("Aztec barcodes count: " + result.Extended.Aztec.StructuredAppendBarcodesCount);
        Console.WriteLine("Aztec file ID: " + result.Extended.Aztec.StructuredAppendFileId);
        Console.WriteLine("Aztec is reader initialization: " + result.Extended.Aztec.IsReaderInitialization);
    }
}
```

### См. также

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


