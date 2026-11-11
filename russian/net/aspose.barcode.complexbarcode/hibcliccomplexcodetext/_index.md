---
title: "Класс HIBCLICComplexCodetext"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Aspose.BarCode.ComplexBarcode.HIBCLICComplexCodetext класс. Базовый класс для кодирования и декодирования текста, встроенного в код HIBC LIC"
type: docs
weight: 560
url: /ru/net/aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
## HIBCLICComplexCodetext class

Базовый класс для кодирования и декодирования текста, встроенного в код HIBC LIC.

```csharp
public abstract class HIBCLICComplexCodetext : IComplexCodetext
```

## Свойства

| Имя | Описание |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | Получает или задает тип штрихкода. Текст кода HIBC LIC может быть закодирован с использованием типов кодирования HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC и HIBCQRLIC. Значение по умолчанию: HIBCCode39LIC. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | Получает тип штрихкода. |
| abstract [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getconstructedcodetext/)() | Создаёт текст кода |
| abstract [InitFromString](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/initfromstring/)(string) | Инициализирует экземпляр из построенного текста кода. |

## Примеры

Этот пример показывает, как декодировать необработанный код текста HIBC LIC в экземпляр HIBCLICComplexCodetext.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.HIBCAztecLIC))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        HIBCLICComplexCodetext resultHIBCLICComplexCodetext = ComplexCodetextReader.TryDecodeHIBCLIC(result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

### См. также

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


