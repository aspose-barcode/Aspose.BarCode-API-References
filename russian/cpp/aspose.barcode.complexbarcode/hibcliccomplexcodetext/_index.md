---
title: "Класс Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext"
linktitle: "HIBCLICComplexCodetext"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Класс Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext. Базовый класс для кодирования и декодирования текста, встроенного в код HIBC LIC, на C++."
type: docs
weight: 800
url: /ru/cpp/aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
## HIBCLICComplexCodetext class


Базовый класс для кодирования и декодирования текста, встроенного в код HIBC LIC.

```cpp
class HIBCLICComplexCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Описание |
| --- | --- |
| [get_BarcodeType](./get_barcodetype/)() const | Получает тип штрихкода. Текст кода HIBC LIC может быть закодирован с использованием типов кодирования HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC и HIBCQRLIC. Значение по умолчанию: HIBCCode39LIC. |
| [GetBarcodeType](./getbarcodetype/)() override | Получает тип штрихкода. |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | Создаёт текст кода |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/)() |  |
| virtual [InitFromString](./initfromstring/)(System::String) | Инициализирует экземпляр из построенного текста кода. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Устанавливает тип штрихкода. Текст кода HIBC LIC может быть закодирован с использованием типов кодирования HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC и HIBCQRLIC. Значение по умолчанию: HIBCCode39LIC. |
## Примечания


Этот пример показывает, как декодировать необработанный кодовый текст HIBC LIC в экземпляр [HIBCLICComplexCodetext](./).
```cpp
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

## См. также

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
