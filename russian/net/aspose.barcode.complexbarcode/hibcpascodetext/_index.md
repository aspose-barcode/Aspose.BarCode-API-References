---
title: "Класс HIBCPASCodetext"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Класс Aspose.BarCode.ComplexBarcode.HIBCPASCodetext. Класс для кодирования и декодирования текста, встроенного в код HIBC PAS"
type: docs
weight: 600
url: /ru/net/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class

Класс для кодирования и декодирования текста, встроенного в код HIBC PAS.

```csharp
public class HIBCPASCodetext : IComplexCodetext
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [HIBCPASCodetext](hibcpascodetext/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcpascodetext/barcodetype/) { get; set; } | Получает или задает тип штрихкода. Текст кода HIBC PAS может быть закодирован с использованием типов кодирования HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS и HIBCQRPAS. Значение по умолчанию: HIBCCode39PAS. |
| [DataLocation](../../aspose.barcode.complexbarcode/hibcpascodetext/datalocation/) { get; set; } | Определяет расположение данных. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddRecord](../../aspose.barcode.complexbarcode/hibcpascodetext/addrecord/#addrecord_1)(HIBCPASRecord) | Добавляет новую запись |
| [AddRecord](../../aspose.barcode.complexbarcode/hibcpascodetext/addrecord/#addrecord)(HIBCPASDataType, string) | Добавляет новую запись |
| [Clear](../../aspose.barcode.complexbarcode/hibcpascodetext/clear/)() | Очищает список записей |
| override [Equals](../../aspose.barcode.complexbarcode/hibcpascodetext/equals/)(object) | Возвращает значение, указывающее, равен ли данный экземпляр указанному значению `HIBCPASCodetext`. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcpascodetext/getbarcodetype/)() | Получает тип штрихкода. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibcpascodetext/getconstructedcodetext/)() | Создаёт текст кода |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibcpascodetext/gethashcode/)() | Возвращает хеш-код для данного экземпляра. |
| [GetRecords](../../aspose.barcode.complexbarcode/hibcpascodetext/getrecords/)() | Получает список записей |
| [InitFromString](../../aspose.barcode.complexbarcode/hibcpascodetext/initfromstring/)(string) | Инициализирует экземпляр из построенного текста кода. |

## Примеры

Этот пример показывает, как кодировать и декодировать HIBC PAS с помощью HIBCPASCodetext.

```csharp
[C#]
HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
complexCodetext.DataLocation = HIBCPASDataLocation.Patient;
complexCodetext.AddRecord(HIBCPASDataType.LabelerIdentificationCode, "A123");
complexCodetext.AddRecord(HIBCPASDataType.ManufacturerSerialNumber, "SERIAL123");
complexCodetext.BarcodeType = EncodeTypes.HIBCDataMatrixPAS;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.HIBCDataMatrixPAS))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText; 
		HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.TryDecodeHIBCPAS(codetext);
		Console.WriteLine("Data location: {0}", readCodetext.DataLocation);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[0].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[0].Data);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[1].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[1].Data);

    }
}
```

### См. также

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


