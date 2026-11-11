---
title: "Класс USADriveIdCodetext.OptionalFields"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Класс Aspose.BarCode.ComplexBarcode.USADriveIdCodetextOptionalFields. Поля необязательных элементов карты"
type: docs
weight: 830
url: /ru/net/aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
## USADriveIdCodetext.OptionalFields class

Опциональные элементы (поля) карты

```csharp
public class OptionalFields
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/.ctor)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AddressStreet2](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/addressstreet2) { get; set; } | DAH, Вторая строка уличной части адреса держателя карты, DL/ID, V35ANS |
| [AliasAKAFamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakafamilyname) { get; set; } | DBN, Другая фамилия, под которой известен держатель карты, DL/ID, V10ANS |
| [AliasAKAGivenName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakagivenname) { get; set; } | DBG, Другое имя, под которым известен держатель карты, DL/ID, V15ANS |
| [AliasAKASuffixName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakasuffixname) { get; set; } | DBS, Другая суффикс, под которым известен держатель карты, DL/ID, V5ANS |
| [AuditInformation](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/auditinformation) { get; set; } | DCJ, Строка букв и/или цифр, идентифицирующая когда, где и кем была изготовлена водительская лицензия/удостоверение личности. Если информация аудита не используется на карте или MRT, она должна быть включена в запись водителя, DL/ID, V25ANS |
| [CardRevisionDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/cardrevisiondate) { get; set; } | DDB, Обязательное поле DHS, указывающее дату последнего изменения версии или модификации видимого формата DL/ID. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N |
| [ComplianceType](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/compliancetype) { get; set; } | DDA, Обязательное поле DHS, указывающее соответствие: “F” = соответствует; “N” = не соответствует, DL/ID, F1A |
| [EndorsementCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/endorsementcodedescription) { get; set; } | DCQ, Текст, объясняющий специфические для юрисдикции коды, указывающие дополнительные водительские привилегии, предоставленные держателю карты сверх класса транспортного средства, DL, V50ANS |
| [HairColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/haircolor) { get; set; } | DAZ, Лысый, черный, блондин, коричневый, серый, рыжий/каштановый, светлый, белый, неизвестно. Если выдающая юрисдикция желает сокращать цвета, необходимо использовать трехсимвольные коды, указанные в AAMVA D20, DL/ID, V12A |
| [HAZMATEndorsementExpDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/hazmatendorsementexpdate) { get; set; } | DDC, Дата, после которой endorsement на опасные материалы, предоставленный документом, более не действителен. (MMDDCCYY для США, CCYYMMDD для Канады), DL, F8N |
| [InventoryControlNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/inventorycontrolnumber) { get; set; } | DCK, Строка букв и/или цифр, прикрепленная к сырьевым материалам (бумага, ламинация и т.д.), используемым при производстве водительских лицензий и удостоверений личности. (рекомендованное поле DHS), DL/ID, V25ANS |
| [LimitedDurationDocIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/limiteddurationdocindicator) { get; set; } | DDD, Обязательное поле DHS, указывающее, что держатель карты имеет временный законный статус = “1”, DL/ID, F1N |
| [NameSuffix](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/namesuffix) { get; set; } | DCU, Суффикс имени (Если юрисдикция участвует в системах, требующих суффикс имени (PDPS, CDLIS и др.), суффикс должен быть собран и отображён в DL/ID и в MRT). JR(Junior), SR(Senior), 1ST или I(First), до 9TH или IX (Ninth), DL/ID, V5ANS |
| [OrganDonorIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/organdonorindicator) { get; set; } | DDK, Поле, указывающее, что держатель карты является донором органов = “1”, DL/ID, F1N |
| [PlaceOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/placeofbirth) { get; set; } | DCI, Страна и муниципалитет и/или штат/провинция, DL/ID, V33A |
| [RaceEthnicity](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/raceethnicity) { get; set; } | DCL, Коды расы или этнической принадлежности держателя карты, как определено в AAMVA D20, DL/ID, V3A |
| [RestrictionCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/restrictioncodedescription) { get; set; } | DCR, Текст, описывающий специфические для юрисдикции коды ограничений, снижающие водительские привилегии, DL, V50ANS |
| [StandardEndorsementCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardendorsementcode) { get; set; } | DCN, Стандартные коды подтверждения для держателя карты. См. коды в D20. Этот элемент данных является заполнительным для будущих усилий по стандартизации кодов подтверждения, DL, F5AN |
| [StandardRestrictionCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardrestrictioncode) { get; set; } | DCO, Стандартные коды ограничений для держателя карты. См. коды в D20. Этот элемент данных является заполнительным для будущих усилий по стандартизации кодов ограничений, DL, F12AN |
| [StandardVehClassification](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardvehclassification) { get; set; } | DCM, Стандартные коды классификации транспортных средств для держателя карты. Этот элемент данных является заполнительным для будущих усилий по стандартизации классификаций транспортных средств, DL, F4AN |
| [Under18Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under18until) { get; set; } | DDH, Дата, когда держателю карты исполняется 18 лет. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N |
| [Under19Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under19until) { get; set; } | DDI, Дата, когда держателю карты исполняется 19 лет. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N |
| [Under21Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under21until) { get; set; } | DDJ, Дата, когда держателю карты исполняется 21 год. (MMDDCCYY для США, CCYYMMDD для Канады), DL/ID, F8N |
| [VehClassDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/vehclassdescription) { get; set; } | DCP, Текст, объясняющий специфические для юрисдикции коды классификаций транспортных средств, которые держатель карты имеет право управлять, DL, V50ANS |
| [VeteranIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/veteranindicator) { get; set; } | DDL, Поле, указывающее, что держатель карты является ветераном = “1”, DL/ID, F1N |
| [WeightKilograms](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightkilograms) { get; set; } | DAX, Вес держателя карты в килограммах, напр. 84 кг = “084”, DL/ID, F3N |
| [WeightPounds](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightpounds) { get; set; } | DAW, Вес держателя карты в фунтах, напр. 185 lb = “185”, DL/ID, F3N |
| [WeightRange](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightrange) { get; set; } | DCE, Указывает приблизительный диапазон веса держателя карты: 0 = до 31 кг (до 70 фунтов), 1 = 32 – 45 кг (71 – 100 фунтов), 2 = 46 - 59 кг (101 – 130 фунтов), 3 = 60 - 70 кг (131 – 160 фунтов), 4 = 71 - 86 кг (161 – 190 фунтов), 5 = 87 - 100 кг (191 – 220 фунтов), 6 = 101 - 113 кг (221 – 250 фунтов), 7 = 114 - 127 кг (251 – 280 фунтов), 8 = 128 – 145 кг (281 – 320 фунтов), 9 = 146+ кг (321+ фунтов), DL/ID, F1N |

### См. также

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


