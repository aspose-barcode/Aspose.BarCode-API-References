---
title: "Класс Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings"
linktitle: "AustraliaPostSettings"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Класс Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings. Параметры декодирования AustraliaPost. Содержит параметры, влияющие на распознанные данные символогии AustraliaPost в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.barcode.barcoderecognition/australiapostsettings/
---
## AustraliaPostSettings class


Параметры декодирования AustraliaPost. Содержит параметры, влияющие на распознанные данные символьной системы AustraliaPost.

```cpp
class AustraliaPostSettings : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [get_CustomerInformationDecoder](./get_customerinformationdecoder/)() const | Публичный интерфейс для декодирования поля Customer Information, используемого в символогии AustraliaPost. |
| [get_CustomerInformationInterpretingType](./get_customerinformationinterpretingtype/)() const | Получает тип интерпретации для Customer Information AustralianPost. [BarCode.Default](../checksumvalidation/) — [CustomerInformationInterpretingType.Other](../../aspose.barcode/customerinformationinterpretingtype/). |
| [get_IgnoreEndingFillingPatternsForCTable](./get_ignoreendingfillingpatternsforctable/)() const | Флаг, заставляющий декодер AustraliaPost игнорировать последние шаблоны заполнения в поле Customer Information при декодировании методом CTable. Метод кодирования CTable не имеет пробелов в таблице кодов, и последовательность "333" шаблонов заполнения декодируется как буква "z". |
| [set_CustomerInformationDecoder](./set_customerinformationdecoder/)(System::SharedPtr\<AustraliaPostCustomerInformationDecoder\>) | Публичный интерфейс для декодирования поля Customer Information, используемого в символогии AustraliaPost. |
| [set_CustomerInformationInterpretingType](./set_customerinformationinterpretingtype/)(Aspose::BarCode::CustomerInformationInterpretingType) | Устанавливает тип интерпретации для Customer Information AustralianPost. [BarCode.Default](../checksumvalidation/) — [CustomerInformationInterpretingType.Other](../../aspose.barcode/customerinformationinterpretingtype/). |
| [set_IgnoreEndingFillingPatternsForCTable](./set_ignoreendingfillingpatternsforctable/)(bool) | Флаг, заставляющий декодер AustraliaPost игнорировать последние шаблоны заполнения в поле Customer Information при декодировании методом CTable. Метод кодирования CTable не имеет пробелов в таблице кодов, и последовательность "333" шаблонов заполнения декодируется как буква "z". |
## См. также

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
