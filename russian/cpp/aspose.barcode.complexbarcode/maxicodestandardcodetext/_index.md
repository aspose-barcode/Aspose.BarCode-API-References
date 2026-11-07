---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext класс"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext класс. Класс для кодирования и декодирования MaxiCode codetext для режимов 4, 5 и 6 в C++."
type: docs
weight: 2000
url: /ru/cpp/aspose.barcode.complexbarcode/maxicodestandardcodetext/
---
## MaxiCodeStandardCodetext class


Класс для кодирования и декодирования текста кода MaxiCode для режимов 4, 5 и 6.

```cpp
class MaxiCodeStandardCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## Methods

| Method | Описание |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению [MaxiCodeStandardCodetext](./). |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | Получает кодировку ECI. Используется, когда MaxiCodeEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Получает режим кодирования MaxiCode. Значение по умолчанию: Auto. |
| [get_Message](./get_message/)() const | Получает сообщение. |
| [get_Mode](./get_mode/)() | Получает режим MaxiCode. Стандартный codetext может использоваться только с режимами 4, 5 и 6. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Получает тип штрихкода. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Создаёт текст кода |
| [GetHashCode](./gethashcode/)() const override | Возвращает хеш-код для данного экземпляра. |
| [GetMode](./getmode/)() const override | Получает режим MaxiCode. |
| [InitFromString](./initfromstring/)(System::String) override | Инициализирует экземпляр из построенного текста кода. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/)() |  |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | Устанавливает кодировку ECI. Используется, когда MaxiCodeEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | Устанавливает режим кодирования MaxiCode. Значение по умолчанию: Auto. |
| [set_Message](./set_message/)(System::String) | Устанавливает сообщение. |
| [set_Mode](./set_mode/)(Generation::MaxiCodeMode) | Устанавливает режим MaxiCode. Стандартный codetext может использоваться только с режимами 4, 5 и 6. |
## Примечания


//Режим 4 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode4; maxiCodeCodetext.Message = "Тестовое сообщение"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //Режим 5 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode5; maxiCodeCodetext.Message = "Тестовое сообщение"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //Режим 6 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode6; maxiCodeCodetext.Message = "Тестовое сообщение"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); }
## См. также

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
