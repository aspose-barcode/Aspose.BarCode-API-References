---
title: "класс Aspose::BarCode::ComplexBarcode::GS1DigitalLink"
linktitle: "GS1DigitalLink"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink класс. Представляет GS1 Digital Link codetext для кодирования и декодирования как упорядоченную последовательность элементов Application Identifier. Порядок источника и повторяющиеся Application Identifier сохраняются. Сконструированный codetext является несжатым GS1 Digital Link URI. Параметры запроса и фрагменты URI, не относящиеся к GS1, игнорируются при разборе в C++."
type: docs
weight: 600
url: /ru/cpp/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class


Представляет GS1 Digital Link кодтекст для кодирования и декодирования в виде упорядоченной последовательности элементов идентификаторов приложений. Порядок исходных элементов и повторяющиеся идентификаторы приложений сохраняются. Сформированный кодтекст представляет собой несжатый URI GS1 Digital Link. Параметры запроса и фрагменты URI, не относящиеся к GS1, игнорируются при разборе.

```cpp
class GS1DigitalLink : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Описание |
| --- | --- |
| [Add](./add/)(System::String, System::String) | Добавляет проверенный элемент Application Identifier. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>) | Создаёт GS1 Digital Link, копируя все элементы из GS1 codetext и выбирая единственный доступный основной ключ. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>, System::String) | Создаёт GS1 Digital Link, копируя все элементы из GS1 codetext и используя указанный основной ключ. |
| [get_BarcodeType](./get_barcodetype/)() const | Возвращает тип штрихкода, используемый для кодирования этого GS1 Digital Link. Поддерживаемые типы: QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF и Code128. Значение по умолчанию — QR. |
| [get_Count](./get_count/)() | Возвращает количество элементов Application Identifier. |
| [get_Elements](./get_elements/)() | Возвращает копию всех элементов в порядке источника. |
| [get_PrimaryApplicationIdentifier](./get_primaryapplicationidentifier/)() const | Возвращает Application Identifier, используемый в качестве основного ключа Digital Link. Null означает, что основной ключ выбирается автоматически при построении URI. |
| [get_UriStem](./get_uristem/)() const | Возвращает абсолютный префикс URI до сегмента пути основного ключа GS1. Ствол не содержит строку запроса или фрагмент. |
| [GetAll](./getall/)(System::String) | Получает все значения для идентификатора приложения в исходном порядке. |
| [GetBarcodeType](./getbarcodetype/)() override | Получает тип штрихкода, используемый для кодирования этой GS1 Digital Link. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Создаёт несжатый URI GS1 Digital Link. |
| [GetFirst](./getfirst/)(System::String) | Получает первое значение для идентификатора приложения. |
| [GS1DigitalLink](./gs1digitallink/)(System::String) | Инициализирует пустой GS1 Digital Link с указанным основанием URI. Первичный ключ выбирается автоматически, когда присутствует ровно один кандидат на первичный ключ. |
| [GS1DigitalLink](./gs1digitallink/)(System::String, System::String) | Инициализирует пустой GS1 Digital Link с указанным основанием URI и первичным ключом. |
| [idx_get](./idx_get/)(int32_t) | Получает элемент по его позиции в упорядоченной последовательности. |
| [InitFromString](./initfromstring/)(System::String) override | Инициализирует этот экземпляр из несжатого URI GS1 Digital Link. Существующее состояние заменяется только после успешного разбора предоставленного URI. Выбранный тип штрихкода сохраняется. |
| static [Parse](./parse/)(System::String) | Разбирает несжатый URI GS1 Digital Link. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Устанавливает тип штрихкода, используемый для кодирования этой GS1 Digital Link. Поддерживаемые типы: QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF и Code128. Значение по умолчанию — QR. |
| [ToGS1Codetext](./togs1codetext/)() | Создаёт независимый GS1 codetext, содержащий текущие элементы GS1. Информация только о URI не включается. |
| [ToString](./tostring/)() const override | Возвращает несжатый URI GS1 Digital Link. |
| [ToUriString](./touristring/)() | Форматирует текущее состояние объекта как несжатый URI GS1 Digital Link. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1DigitalLink\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | Пытается разобрать несжатый URI GS1 Digital Link и возвращает структурированные ошибки валидации. |
| static [Validate](./validate/)(System::String) | Проверяет несжатый URI GS1 Digital Link без создания объекта. |
## См. также

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
