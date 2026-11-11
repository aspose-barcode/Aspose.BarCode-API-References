---
title: "Класс HIBCLICSecondaryAndAdditionalDataCodetext"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Класс Aspose.BarCode.ComplexBarcode.HIBCLICSecondaryAndAdditionalDataCodetext. Класс для кодирования и декодирования текста, встроенного в код HIBC LIC, который хранит вторичные данные"
type: docs
weight: 590
url: /ru/net/aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/
---
## HIBCLICSecondaryAndAdditionalDataCodetext class

Класс для кодирования и декодирования текста, встроенного в код HIBC LIC, который хранит вторичные данные.

```csharp
public class HIBCLICSecondaryAndAdditionalDataCodetext : HIBCLICComplexCodetext
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [HIBCLICSecondaryAndAdditionalDataCodetext](hibclicsecondaryandadditionaldatacodetext/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | Получает или задает тип штрихкода. Текст кода HIBC LIC может быть закодирован с использованием типов кодирования HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC и HIBCQRLIC. Значение по умолчанию: HIBCCode39LIC. |
| [Data](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/data/) { get; set; } | Определяет вторичные и дополнительные вспомогательные данные. |
| [LinkCharacter](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/linkcharacter/) { get; set; } | Определяет символ ссылки. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/equals/)(object) | Возвращает значение, указывающее, равен ли данный экземпляр указанному значению `HIBCLICSecondaryAndAdditionalDataCodetext`. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | Получает тип штрихкода. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/getconstructedcodetext/)() | Создаёт текст кода |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/gethashcode/)() | Возвращает хеш-код для данного экземпляра. |
| override [InitFromString](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/initfromstring/)(string) | Инициализирует экземпляр из построенного текста кода. |

## Примеры

Этот пример показывает, как кодировать и декодировать HIBC LIC с использованием HIBCLICSecondaryAndAdditionalDataCodetext.

```csharp
[C#]
HIBCLICSecondaryAndAdditionalDataCodetext complexCodetext = new HIBCLICSecondaryAndAdditionalDataCodetext();
complexCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
complexCodetext.LinkCharacter = 'L';
complexCodetext.Data = new SecondaryAndAdditionalData();
complexCodetext.Data.ExpiryDate = DateTime.Now;
complexCodetext.Data.ExpiryDateFormat = HIBCLICDateFormat.MMDDYY;
complexCodetext.Data.Quantity = 30;
complexCodetext.Data.LotNumber = "LOT123";
complexCodetext.Data.SerialNumber = "SERIAL123";
complexCodetext.Data.DateOfManufacture = DateTime.Now;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICSecondaryAndAdditionalDataCodetext result = (HIBCLICSecondaryAndAdditionalDataCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Expiry date: " + result.Data.ExpiryDate);
        Console.WriteLine("Quantity: " + result.Data.Quantity);
        Console.WriteLine("Lot number: " + result.Data.LotNumber);
        Console.WriteLine("Serial number: " + result.Data.SerialNumber);
        Console.WriteLine("Date of manufacture: " + result.Data.DateOfManufacture);
    }
}
```

### См. также

* class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


