---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext класс"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext class. Базовый класс для кодирования и декодирования текста, встроенного в код MaxiCode в C++."
type: docs
weight: 1600
url: /ru/cpp/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class


Базовый класс для кодирования и декодирования текста, встроенного в код MaxiCode.

```cpp
class MaxiCodeCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Описание |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | Получает кодировку ECI. Используется, когда MaxiCodeEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Получает режим кодирования MaxiCode. Значение по умолчанию: Auto. |
| [GetBarcodeType](./getbarcodetype/)() override | Получает тип штрихкода. |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | Создаёт текст кода |
| virtual [GetMode](./getmode/)() const | Получает режим MaxiCode. |
| virtual [InitFromString](./initfromstring/)(System::String) | Инициализирует экземпляр из построенного текста кода. |
| [MaxiCodeCodetext](./maxicodecodetext/)() |  |
| [set_ECIEncoding](./set_eciencoding/)(Generation::ECIEncodings) | Устанавливает кодировку ECI. Используется, когда MaxiCodeEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(Generation::MaxiCodeEncodeMode) | Устанавливает режим кодирования MaxiCode. Значение по умолчанию: Auto. |
## Примечания


Этот пример показывает, как декодировать необработанный код MaxiCode в экземпляр [MaxiCodeCodetext](./).
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("MaxiCode mode: " + resultMaxiCodeCodetext.GetMode());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

## См. также

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
