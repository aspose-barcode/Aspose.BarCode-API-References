---
title: "Класс HIBCLICPrimaryDataCodetext"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Класс Aspose.BarCode.ComplexBarcode.HIBCLICPrimaryDataCodetext. Класс для кодирования и декодирования текста, встроенного в код HIBC LIC, который хранит первичные данные"
type: docs
weight: 580
url: /ru/net/aspose.barcode.complexbarcode/hibclicprimarydatacodetext/
---
## HIBCLICPrimaryDataCodetext class

Класс для кодирования и декодирования текста, встроенного в код HIBC LIC, который хранит первичные данные.

```csharp
public class HIBCLICPrimaryDataCodetext : HIBCLICComplexCodetext
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [HIBCLICPrimaryDataCodetext](hibclicprimarydatacodetext/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | Получает или задает тип штрихкода. Текст кода HIBC LIC может быть закодирован с использованием типов кодирования HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC и HIBCQRLIC. Значение по умолчанию: HIBCCode39LIC. |
| [Data](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/data/) { get; set; } | Определяет первичные данные. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/equals/)(object) | Возвращает значение, указывающее, равен ли данный экземпляр указанному значению `HIBCLICPrimaryDataCodetext`. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | Получает тип штрихкода. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/getconstructedcodetext/)() | Создаёт текст кода |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/gethashcode/)() | Возвращает хеш-код для данного экземпляра. |
| override [InitFromString](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/initfromstring/)(string) | Инициализирует экземпляр из построенного текста кода. |

## Примеры

Этот пример показывает, как кодировать и декодировать HIBC LIC с использованием HIBCLICPrimaryDataCodetext.

```csharp
[C#]
HIBCLICPrimaryDataCodetext complexCodetext  = new HIBCLICPrimaryDataCodetext();
complexCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
complexCodetext.Data = new PrimaryData();
complexCodetext.Data.ProductOrCatalogNumber = "12345";
complexCodetext.Data.LabelerIdentificationCode = "A999";
complexCodetext.Data.UnitOfMeasureID = 1;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICPrimaryDataCodetext result = (HIBCLICPrimaryDataCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Product or catalog number: " + result.Data.ProductOrCatalogNumber);
        Console.WriteLine("Labeler identification code: " + result.Data.LabelerIdentificationCode);
        Console.WriteLine("Unit of measure ID: " + result.Data.UnitOfMeasureID);
    }
}
```

### См. также

* class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


