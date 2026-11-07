---
title: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext класс"
linktitle: "USADriveIdCodetext"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext class. Класс для кодирования и декодирования текста, встроенного в код PDF417 водительского удостоверения США в C++."
type: docs
weight: 2900
url: /ru/cpp/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class


Класс для кодирования и декодирования текста, встроенного в код PDF417 водительского [License](../../aspose.barcode/license/) США.

```cpp
class USADriveIdCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Описание |
| --- | --- |
| [get_AAMVAVersionNumber](./get_aamvaversionnumber/)() const | Номер версии AAMVA 00-99 |
| [get_IssuerIdentificationNumber](./get_issueridentificationnumber/)() const | Этот номер уникально идентифицирует юрисдикцию-эмитент и может быть получен путем обращения в ISO Issuing Authority (AAMVA). Полный 6-значный IIN должен быть закодирован. |
| [get_JurisdictionSpecificSubfile](./get_jurisdictionspecificsubfile/)() const | Специфические поля юрисдикции |
| [get_JurisdictionVersionNumber](./get_jurisdictionversionnumber/)() const | Номер версии юрисдикции 00-99 |
| [get_MandatoryElements](./get_mandatoryelements/)() const | Обязательные элементы (поля) карты |
| [get_NumberOfEntries](./get_numberofentries/)() const | Номер 00-99 подпфайлов |
| [get_OptionalElements](./get_optionalelements/)() const | Опциональные элементы (поля) карты |
| [get_SubfileDesignator](./get_subfiledesignator/)() const | Содержит информацию о следующих подпфайлах, типах, смещениях и длинах. Важно: задайте только тип, смещение и длина будут установлены автоматически. |
| [GetBarcodeType](./getbarcodetype/)() override | Возвращает тип штрихкода USA DL (Pdf417) |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Создать кодовый текст из данных USA DL |
| [InitFromString](./initfromstring/)(System::String) override | Инициализировать объект USA DL из кодового текста |
| [SaveToXml](./savetoxml/)(System::SharedPtr\<System::IO::Stream\>) | Сохраняет в XML |
| [set_AAMVAVersionNumber](./set_aamvaversionnumber/)(System::String) | Номер версии AAMVA 00-99 |
| [set_IssuerIdentificationNumber](./set_issueridentificationnumber/)(System::String) | Этот номер уникально идентифицирует юрисдикцию-эмитент и может быть получен путем обращения в ISO Issuing Authority (AAMVA). Полный 6-значный IIN должен быть закодирован. |
| [set_JurisdictionSpecificSubfile](./set_jurisdictionspecificsubfile/)(System::SharedPtr\<USADriveIdJurisdSubfile\>) | Специфические поля юрисдикции |
| [set_JurisdictionVersionNumber](./set_jurisdictionversionnumber/)(System::String) | Номер версии юрисдикции 00-99 |
| [set_MandatoryElements](./set_mandatoryelements/)(System::SharedPtr\<USADriveIdCodetext::MandatoryFields\>) | Обязательные элементы (поля) карты |
| [set_NumberOfEntries](./set_numberofentries/)(int32_t) | Номер 00-99 подпфайлов |
| [set_OptionalElements](./set_optionalelements/)(System::SharedPtr\<USADriveIdCodetext::OptionalFields\>) | Опциональные элементы (поля) карты |
| [set_SubfileDesignator](./set_subfiledesignator/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<USADriveIdCodetext::SubfileProperties\>>>) | Содержит информацию о следующих подпфайлах, типах, смещениях и длинах. Важно: задайте только тип, смещение и длина будут установлены автоматически. |
| [USADriveIdCodetext](./usadriveidcodetext/)() | Конструктор по умолчанию |
## См. также

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
