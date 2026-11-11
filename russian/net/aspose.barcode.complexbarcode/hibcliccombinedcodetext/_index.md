---
title: "Класс HIBCLICCombinedCodetext"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Aspose.BarCode.ComplexBarcode.HIBCLICCombinedCodetext класс. Класс для кодирования и декодирования текста, встроенного в код HIBC LIC, который хранит первичные и вторичные данные"
type: docs
weight: 550
url: /ru/net/aspose.barcode.complexbarcode/hibcliccombinedcodetext/
---
## HIBCLICCombinedCodetext class

Класс для кодирования и декодирования текста, встроенного в код HIBC LIC, который хранит первичные и вторичные данные.

```csharp
public class HIBCLICCombinedCodetext : HIBCLICComplexCodetext
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [HIBCLICCombinedCodetext](hibcliccombinedcodetext/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | Получает или задает тип штрихкода. Текст кода HIBC LIC может быть закодирован с использованием типов кодирования HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC и HIBCQRLIC. Значение по умолчанию: HIBCCode39LIC. |
| [PrimaryData](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/primarydata/) { get; set; } | Определяет первичные данные. |
| [SecondaryAndAdditionalData](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/secondaryandadditionaldata/) { get; set; } | Определяет вторичные и дополнительные вспомогательные данные. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/equals/)(object) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению `HIBCLICCombinedCodetext`. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | Получает тип штрихкода. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/getconstructedcodetext/)() | Создаёт текст кода |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/gethashcode/)() | Возвращает хеш-код для данного экземпляра. |
| override [InitFromString](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/initfromstring/)(string) | Инициализирует экземпляр из построенного текста кода. |

## Примеры

Этот пример показывает, как кодировать и декодировать HIBC LIC с использованием HIBCLICCombinedCodetext.

```csharp
[C#]
HIBCLICCombinedCodetext combinedCodetext = new HIBCLICCombinedCodetext();
combinedCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
combinedCodetext.PrimaryData = new PrimaryData();
combinedCodetext.PrimaryData.ProductOrCatalogNumber = "12345";
combinedCodetext.PrimaryData.LabelerIdentificationCode = "A999";
combinedCodetext.PrimaryData.UnitOfMeasureID = 1;
combinedCodetext.SecondaryAndAdditionalData = new SecondaryAndAdditionalData();
combinedCodetext.SecondaryAndAdditionalData.ExpiryDate = DateTime.Now;
combinedCodetext.SecondaryAndAdditionalData.ExpiryDateFormat = HIBCLICDateFormat.MMDDYY;
combinedCodetext.SecondaryAndAdditionalData.Quantity = 30;
combinedCodetext.SecondaryAndAdditionalData.LotNumber = "LOT123";
combinedCodetext.SecondaryAndAdditionalData.SerialNumber = "SERIAL123";
combinedCodetext.SecondaryAndAdditionalData.DateOfManufacture = DateTime.Now;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(combinedCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICCombinedCodetext result = (HIBCLICCombinedCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Product or catalog number: " + result.PrimaryData.ProductOrCatalogNumber);
        Console.WriteLine("Labeler identification code: " + result.PrimaryData.LabelerIdentificationCode);
        Console.WriteLine("Unit of measure ID: " + result.PrimaryData.UnitOfMeasureID);
        Console.WriteLine("Expiry date: " + result.SecondaryAndAdditionalData.ExpiryDate);
        Console.WriteLine("Quantity: " + result.SecondaryAndAdditionalData.Quantity);
        Console.WriteLine("Lot number: " + result.SecondaryAndAdditionalData.LotNumber);
        Console.WriteLine("Serial number: " + result.SecondaryAndAdditionalData.SerialNumber);
        Console.WriteLine("Date of manufacture: " + result.SecondaryAndAdditionalData.DateOfManufacture);
    }
}
```

### См. также

* class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


