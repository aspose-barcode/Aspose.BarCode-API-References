---
title: "Класс DataMatrixExtendedParameters"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Класс Aspose.BarCode.BarCodeRecognition.DataMatrixExtendedParameters. Сохраняет специальные данные распознанного штрихкода DataMatrix"
type: docs
weight: 220
url: /ru/net/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class

Сохраняет специальные данные распознанного штрихкода DataMatrix

```csharp
public sealed class DataMatrixExtendedParameters : BaseExtendedParameters
```

## Свойства

| Имя | Описание |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Проверяет, имеют ли все параметры только значения по умолчанию |
| [IsReaderProgramming](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/isreaderprogramming/) { get; } | Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или перепрограммирования считывателя штрих‑кода. Значение по умолчанию — false. |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodeid/) { get; } | Получает идентификатор штрихкода DataMatrix в режиме структурированного добавления. Идентификатор начинается с 1 и должен быть меньше или равен количеству штрихкодов. Значение по умолчанию — -1. |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodescount/) { get; } | Получает количество штрихкодов DataMatrix в режиме структурированного добавления. Значение по умолчанию — -1. Количество должно быть в диапазоне от 1 до 35. |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendfileid/) { get; } | Получает идентификатор штрихкода DataMatrix в режиме структурированного добавления. Идентификатор начинается с 1 и должен быть меньше или равен количеству штрихкодов. Значение по умолчанию — -1. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/equals/)(object) | Возвращает значение, указывающее, равен ли данный экземпляр указанному значению `DataMatrixExtendedParameters`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/gethashcode/)() | Возвращает хеш-код для данного экземпляра. |
| override [ToString](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/tostring/)() | Возвращает человекочитаемое строковое представление этого `DataMatrixExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_equality/) | Возвращает значение, указывающее, равны ли первое значение `DataMatrixExtendedParameters` и второе. |
| [operator !=](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_inequality/) | Возвращает значение, указывающее, отличается ли первое значение `DataMatrixExtendedParameters` от второго. |

## Примеры

Этот пример показывает, как получить необработанные значения DataMatrix

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DataMatrix))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DataMatrix barcode ID: " + result.Extended.DataMatrix.StructuredAppendBarcodeId);
        Console.WriteLine("DataMatrix barcodes count: " + result.Extended.DataMatrix.StructuredAppendBarcodesCount);
        Console.WriteLine("DataMatrix file ID: " + result.Extended.DataMatrix.StructuredAppendFileId);
        Console.WriteLine("DataMatrix is reader programming: " + result.Extended.DataMatrix.IsReaderProgramming);
    }
}
```

### См. также

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


