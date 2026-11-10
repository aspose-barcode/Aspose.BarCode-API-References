---
title: "الفئة USADriveIdCodetext.MandatoryFields"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "الفئة Aspose.BarCode.ComplexBarcode.USADriveIdCodetextMandatoryFields. الحقول الإلزامية لعناصر البطاقة"
type: docs
weight: 820
url: /ar/net/aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
## USADriveIdCodetext.MandatoryFields class

العناصر (الحقول) الإلزامية للبطاقة

```csharp
public class MandatoryFields
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/.ctor)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AddressCity](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresscity) { get; set; } | DAI، الجزء المتعلق بالمدينة في عنوان حامل البطاقة، DL/ID، V20ANS |
| [AddressPostalCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresspostalcode) { get; set; } | DAK، الجزء المتعلق بالرمز البريدي في عنوان حامل البطاقة في الولايات المتحدة وكندا. إذا كان الجزء الأخير من الرمز البريدي في الولايات المتحدة غير معروف، سيتم استخدام الأصفار لملء المجموعة الأخيرة من الأرقام حتى 9 أرقام، DL/ID، F11ANS |
| [AddressState](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstate) { get; set; } | DAJ، الجزء المتعلق بالولاية في عنوان حامل البطاقة، DL/ID، F2A |
| [AddressStreet1](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstreet1) { get; set; } | DAG، الجزء المتعلق بالشارع في عنوان حامل البطاقة، DL/ID، V35ANS |
| [CountryIdentification](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/countryidentification) { get; set; } | DCG، الدولة التي صُدر فيها DL/ID. الولايات المتحدة = USA، كندا = CAN، DL/ID، F3A |
| [CustomerIDNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/customeridnumber) { get; set; } | DAQ، الرقم المخصص أو المحسوب من قبل السلطة المصدرة، DL/ID، V25ANS |
| [DateOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/dateofbirth) { get; set; } | DBB، تاريخ إصدار المستند، MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا، DL/ID، F8N |
| [DocumentDiscriminator](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/documentdiscriminator) { get; set; } | DCF، يجب أن يحدد الرقم مستندًا معينًا صُدر لهذا العميل بشكل فريد عن غيره من المستندات التي قد صدرت في الماضي. قد يُستخدم هذا الرقم لأغراض متعددة مثل تمييز المستند، رقم معلومات التدقيق، أو التحكم في المخزون، DL/ID، V25ANS |
| [EndorsementCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/endorsementcodes) { get; set; } | DCD، رموز التأييد الخاصة بالاختصاص القضائي، DL، V5ANS |
| [ExpirationDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/expirationdate) { get; set; } | DBA، تاريخ انتهاء صلاحية المستند، MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا، DL/ID، F8N |
| [EyeColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/eyecolor) { get; set; } | DAY، لون عيون حامل البطاقة. (رموز ANSI D-20). DL/ID، F3A |
| [FamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familyname) { get; set; } | DCS، اسم عائلة حامل البطاقة، DL/ID، V40ANS |
| [FamilyNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familynametruncation) { get; set; } | DDE، رمز يشير إلى ما إذا كان الحقل قد تم تقصيره (T)، لم يتم تقصيره (N)، أو غير معروف ما إذا تم تقصيره (U)، DL/ID، F1A |
| [FirstName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstname) { get; set; } | DAC، الاسم الأول لحامل البطاقة، DL/ID، V40ANS |
| [FirstNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstnametruncation) { get; set; } | DDF، رمز يشير إلى ما إذا كان الحقل قد تم تقصيره (T)، لم يتم تقصيره (N)، أو غير معروف ما إذا تم تقصيره (U)، DL/ID، F1A |
| [Height](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/height) { get; set; } | DAU، ارتفاع حامل البطاقة. بوصات (in): عدد البوصات متبوعًا بـ " in" مثال 6'1'' = "073 in" سنتيمترات (cm): عدد السنتيمترات متبوعًا بـ " cm" مثال 181 سنتيمتر = "181 cm"، DL/ID، F6ANS |
| [IssueDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/issuedate) { get; set; } | DBD، تاريخ إصدار المستند، MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا، DL/ID، F8N |
| [MiddleName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlename) { get; set; } | DAD، اسم (أسماء) الوسط لحامل البطاقة. في حالة وجود أكثر من اسم وسط يجب فصلها بفاصلة ",". ، DL/ID، V40ANS |
| [MiddleNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlenametruncation) { get; set; } | DDG، رمز يشير إلى ما إذا كان الحقل قد تم تقصيره (T)، لم يتم تقصيره (N)، أو غير معروف ما إذا تم تقصيره (U)، DL/ID، F1A |
| [RestrictionCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/restrictioncodes) { get; set; } | DCB، رموز القيود الخاصة بالاختصاص القضائي، DL، V12ANS |
| [Sex](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/sex) { get; set; } | DBC، جنس حامل البطاقة. 1 = ذكر، 2 = أنثى، 9 = غير محدد، DL/ID، F1N |
| [VehicleClass](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/vehicleclass) { get; set; } | DCA، رمز فئة/مجموعة المركبة الخاص بالاختصاص القضائي، DL، V6ANS |

### انظر أيضًا

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


