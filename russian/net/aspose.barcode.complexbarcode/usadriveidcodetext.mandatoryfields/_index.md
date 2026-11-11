---
title: "Класс USADriveIdCodetext.MandatoryFields"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Класс Aspose.BarCode.ComplexBarcode.USADriveIdCodetextMandatoryFields. Обязательные элементы (поля) карты"
type: docs
weight: 820
url: /ru/net/aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
## USADriveIdCodetext.MandatoryFields class

Обязательные элементы (поля) карты

```csharp
public class MandatoryFields
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/.ctor)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AddressCity](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresscity) { get; set; } | DAI, часть адреса держателя карты — город, DL/ID, V20ANS |
| [AddressPostalCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresspostalcode) { get; set; } | DAK, часть адреса держателя карты — почтовый индекс в США и Канаде. Если конечная часть почтового индекса в США неизвестна, для заполнения до 9 цифр будут использованы нули, DL/ID, F11ANS |
| [AddressState](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstate) { get; set; } | DAJ, часть адреса держателя карты — штат, DL/ID, F2A |
| [AddressStreet1](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstreet1) { get; set; } | DAG, часть адреса держателя карты — улица, DL/ID, V35ANS |
| [CountryIdentification](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/countryidentification) { get; set; } | DCG, страна, в которой выдан DL/ID. США = USA, Канада = CAN, DL/ID, F3A |
| [CustomerIDNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/customeridnumber) { get; set; } | DAQ, Номер, присвоенный или рассчитанный выдающим органом, DL/ID, V25ANS |
| [DateOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/dateofbirth) { get; set; } | DBB, Дата выдачи документа, MMDDCCYY для США, CCYYMMDD для Канады, DL/ID, F8N |
| [DocumentDiscriminator](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/documentdiscriminator) { get; set; } | DCF, Номер, который должен уникально идентифицировать конкретный документ, выданный этому клиенту, среди других, которые могли быть выданы ранее. Этот номер может использоваться для различных целей: различения документов, номера аудита и/или контроля инвентаря, DL/ID, V25ANS |
| [EndorsementCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/endorsementcodes) { get; set; } | DCD, Коды одобрения, специфичные для юрисдикции, DL, V5ANS |
| [ExpirationDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/expirationdate) { get; set; } | DBA, Дата истечения срока действия документа, MMDDCCYY для США, CCYYMMDD для Канады, DL/ID, F8N |
| [EyeColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/eyecolor) { get; set; } | DAY, Цвет глаз держателя карты. (Коды ANSI D-20). DL/ID, F3A |
| [FamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familyname) { get; set; } | DCS, Фамилия держателя карты, DL/ID, V40ANS |
| [FamilyNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familynametruncation) { get; set; } | DDE, Код, указывающий, было ли поле усечено (T), не было усечено (N) или неизвестно, усечено ли (U), DL/ID, F1A |
| [FirstName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstname) { get; set; } | DAC, Имя держателя карты, DL/ID, V40ANS |
| [FirstNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstnametruncation) { get; set; } | DDF, Код, указывающий, было ли поле усечено (T), не было усечено (N) или неизвестно, усечено ли (U), DL/ID, F1A |
| [Height](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/height) { get; set; } | DAU, Рост держателя карты. Дюймы (in): количество дюймов, за которым следует \" in\" пример 6'1'' = \"073 in\" Сантиметры(cm): количество сантиметров, за которым следует \" cm\" пример 181 сантиметров = \"181 cm\", DL/ID, F6ANS |
| [IssueDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/issuedate) { get; set; } | DBD, Дата выдачи документа, MMDDCCYY для США, CCYYMMDD для Канады, DL/ID, F8N |
| [MiddleName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlename) { get; set; } | DAD, Отчество(а) держателя карты. В случае нескольких отчеств они должны быть разделены запятой \",\"., DL/ID, V40ANS |
| [MiddleNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlenametruncation) { get; set; } | DDG, Код, указывающий, было ли поле усечено (T), не было усечено (N) или неизвестно, усечено ли (U), DL/ID, F1A |
| [RestrictionCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/restrictioncodes) { get; set; } | DCB, Коды ограничений, специфичные для юрисдикции, DL, V12ANS |
| [Sex](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/sex) { get; set; } | DBC, Пол держателя карты. 1 = мужской, 2 = женский, 9 = не указано, DL/ID, F1N |
| [VehicleClass](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/vehicleclass) { get; set; } | DCA, Код класса/группы транспортного средства, специфичный для юрисдикции, DL, V6ANS |

### См. также

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


