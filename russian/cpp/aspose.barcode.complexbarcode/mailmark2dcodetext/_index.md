---
title: "Класс Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext"
linktitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Класс Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext. Класс для кодирования и декодирования текста, встроенного в код Royal Mail 2D Mailmark, на C++."
type: docs
weight: 1400
url: /ru/cpp/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class


Класс для кодирования и декодирования текста, встроенного в код Royal Mail 2D Mailmark.

```cpp
class Mailmark2DCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Описание |
| --- | --- |
| [get_Class](./get_class/)() const | Определяет класс элемента. |
| [get_CustomerContent](./get_customercontent/)() const | Опциональное пространство для использования клиентом. |
| [get_CustomerContentEncodeMode](./get_customercontentencodemode/)() const | Режим кодирования штрихкода Datamatrix. Значение по умолчанию: EncodeMode.C40. |
| [get_DataMatrixType](./get_datamatrixtype/)() const | Тип 2D Mailmark определяет размер штрихкода Data Matrix. |
| [get_DestinationPostCodeAndDPS](./get_destinationpostcodeanddps/)() const | Содержит почтовый индекс доставки [Address](../address/) с DPS. Если внутри страны, почтовый индекс/DP содержит следующее количество символов. Область (1 или 2 символа) Округ (1 или 2 символа) Сектор (1 символ) Блок (2 символа) DPS (2 символа). Почтовый индекс и DPS должны соответствовать действительному формату PAF®. |
| [get_InformationTypeID](./get_informationtypeid/)() const | Определяет полезную нагрузку штрихкода Royal Mail Mailmark для каждого типа продукта. |
| [get_ItemID](./get_itemid/)() const | Определяет уникальный элемент в рамках идентификатора цепочки поставок. Каждый штрихкод Mailmark должен содержать ID, чтобы его можно было уникально идентифицировать минимум 90 дней. Максимальное значение: 99999999. |
| [get_ReturnToSenderPostCode](./get_returntosenderpostcode/)() const | Содержит почтовый индекс возврата отправителю, но без DPS. PC (без DPS) должен соответствовать формату PAF®. |
| [get_RTSFlag](./get_rtsflag/)() const | Флаг, указывающий, какой уровень услуги возврата отправителю запрашивается. |
| [get_SupplyChainID](./get_supplychainid/)() const | Определяет уникальную группу клиентов, участвующих в рассылке. Максимальное значение: 9999999. |
| [get_UPUCountryID](./get_upucountryid/)() const | Определяет идентификатор страны UPU. Максимальная длина: 4 символа. |
| [get_VersionID](./get_versionid/)() const | Определяет версию штрихкода, соответствующую каждому идентификатору типа информации. |
| [GetBarcodeType](./getbarcodetype/)() override | Получает тип штрихкода. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Создать кодовый текст из данных Mailmark. |
| [InitFromString](./initfromstring/)(System::String) override | Инициализирует данные Mailmark из построенного кодового текста. |
| [Mailmark2DCodetext](./mailmark2dcodetext/)() | Конструктор. Создаёт экземпляр по умолчанию класса [Mailmark2DCodetext](./). |
| [set_Class](./set_class/)(System::String) | Определяет класс элемента. |
| [set_CustomerContent](./set_customercontent/)(System::String) | Опциональное пространство для использования клиентом. |
| [set_CustomerContentEncodeMode](./set_customercontentencodemode/)(Generation::DataMatrixEncodeMode) | Режим кодирования штрихкода Datamatrix. Значение по умолчанию: EncodeMode.C40. |
| [set_DataMatrixType](./set_datamatrixtype/)(Mailmark2DType) | Тип 2D Mailmark определяет размер штрихкода Data Matrix. |
| [set_DestinationPostCodeAndDPS](./set_destinationpostcodeanddps/)(System::String) | Содержит почтовый индекс доставки [Address](../address/) с DPS. Если внутри страны, почтовый индекс/DP содержит следующее количество символов. Область (1 или 2 символа) Округ (1 или 2 символа) Сектор (1 символ) Блок (2 символа) DPS (2 символа). Почтовый индекс и DPS должны соответствовать действительному формату PAF®. |
| [set_InformationTypeID](./set_informationtypeid/)(System::String) | Определяет полезную нагрузку штрихкода Royal Mail Mailmark для каждого типа продукта. |
| [set_ItemID](./set_itemid/)(int32_t) | Определяет уникальный элемент в рамках идентификатора цепочки поставок. Каждый штрихкод Mailmark должен содержать ID, чтобы его можно было уникально идентифицировать минимум 90 дней. Максимальное значение: 99999999. |
| [set_ReturnToSenderPostCode](./set_returntosenderpostcode/)(System::String) | Содержит почтовый индекс возврата отправителю, но без DPS. PC (без DPS) должен соответствовать формату PAF®. |
| [set_RTSFlag](./set_rtsflag/)(System::String) | Флаг, указывающий, какой уровень услуги возврата отправителю запрашивается. |
| [set_SupplyChainID](./set_supplychainid/)(int32_t) | Определяет уникальную группу клиентов, участвующих в рассылке. Максимальное значение: 9999999. |
| [set_UPUCountryID](./set_upucountryid/)(System::String) | Определяет идентификатор страны UPU. Максимальная длина: 4 символа. |
| [set_VersionID](./set_versionid/)(System::String) | Определяет версию штрихкода, соответствующую каждому идентификатору типа информации. |
## См. также

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
