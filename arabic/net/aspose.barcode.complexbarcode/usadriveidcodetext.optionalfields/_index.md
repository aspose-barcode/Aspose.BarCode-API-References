---
title: "الفئة USADriveIdCodetext.OptionalFields"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "الفئة Aspose.BarCode.ComplexBarcode.USADriveIdCodetextOptionalFields. حقول العناصر الاختيارية للبطاقة"
type: docs
weight: 830
url: /ar/net/aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
## USADriveIdCodetext.OptionalFields class

العناصر (الحقول) الاختيارية للبطاقة

```csharp
public class OptionalFields
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/.ctor)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AddressStreet2](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/addressstreet2) { get; set; } | DAH، السطر الثاني من جزء الشارع في عنوان حامل البطاقة، DL/ID، V35ANS |
| [AliasAKAFamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakafamilyname) { get; set; } | DBN، اسم العائلة الآخر الذي يُعرف به حامل البطاقة، DL/ID، V10ANS |
| [AliasAKAGivenName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakagivenname) { get; set; } | DBG، الاسم الأول الآخر الذي يُعرف به حامل البطاقة، DL/ID، V15ANS |
| [AliasAKASuffixName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakasuffixname) { get; set; } | DBS، اللقب الآخر الذي يُعرف به حامل البطاقة، DL/ID، V5ANS |
| [AuditInformation](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/auditinformation) { get; set; } | DCJ، سلسلة من الأحرف و/أو الأرقام تحدد متى وأين ومن قام بصنع رخصة القيادة/بطاقة الهوية. إذا لم تُستخدم معلومات التدقيق على البطاقة أو MRT، يجب تضمينها في سجل السائق، DL/ID، V25ANS |
| [CardRevisionDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/cardrevisiondate) { get; set; } | DDB، حقل مطلوب من DHS يشير إلى تاريخ أحدث تغيير نسخة أو تعديل لتنسيق DL/ID الظاهر. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N |
| [ComplianceType](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/compliancetype) { get; set; } | DDA، حقل مطلوب من DHS يشير إلى الامتثال: “F” = متوافق؛ و “N” = غير متوافق، DL/ID، F1A |
| [EndorsementCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/endorsementcodedescription) { get; set; } | DCQ، نص يشرح الرموز الخاصة بالاختصاص القضائي التي تشير إلى امتيازات قيادة إضافية ممنوحة لحامل البطاقة تتجاوز فئة المركبة، DL، V50ANS |
| [HairColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/haircolor) { get; set; } | DAZ، أصلع، أسود، أشقر، بني، رمادي، أحمر/كستنائي، رملي، أبيض، غير معروف. إذا رغبت الجهة المصدرة في اختصار الألوان، يجب استخدام الرموز الثلاثية الأحرف المتوفرة في AAMVA D20، DL/ID، V12A |
| [HAZMATEndorsementExpDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/hazmatendorsementexpdate) { get; set; } | DDC، التاريخ الذي يصبح فيه اعتماد المواد الخطرة الممنوح بالوثيقة غير صالح. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL، F8N |
| [InventoryControlNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/inventorycontrolnumber) { get; set; } | DCK، سلسلة من الأحرف و/أو الأرقام تُلصق بالمواد الخام (ورق البطاقات، اللصق، إلخ) المستخدمة في إنتاج رخص القيادة وبطاقات الهوية. (حقل موصى به من DHS)، DL/ID، V25ANS |
| [LimitedDurationDocIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/limiteddurationdocindicator) { get; set; } | DDD، حقل مطلوب من DHS يشير إلى أن حامل البطاقة لديه حالة قانونية مؤقتة = “1”، DL/ID، F1N |
| [NameSuffix](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/namesuffix) { get; set; } | DCU، لاحقة الاسم (إذا كانت الولاية تشارك في الأنظمة التي تتطلب لاحقة الاسم (PDPS، CDLIS، إلخ)، يجب جمع اللاحقة وعرضها على رخصة القيادة/الهوية وفي MRT). JR (Junior)، SR (Senior)، 1ST أو I (First)، حتى 9TH أو IX (التاسع)، DL/ID، V5ANS |
| [OrganDonorIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/organdonorindicator) { get; set; } | DDK، الحقل الذي يشير إلى أن حامل البطاقة متبرع بأعضاء = “1”، DL/ID، F1N |
| [PlaceOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/placeofbirth) { get; set; } | DCI، الدولة والبلدية و/أو الولاية/المقاطعة، DL/ID، V33A |
| [RaceEthnicity](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/raceethnicity) { get; set; } | DCL، رموز العرق أو الأصل العرقي لحامل البطاقة، كما هو معرف في AAMVA D20، DL/ID، V3A |
| [RestrictionCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/restrictioncodedescription) { get; set; } | DCR، نص يصف رمز(ات) القيود الخاصة بالولاية التي تقيد امتيازات القيادة، DL، V50ANS |
| [StandardEndorsementCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardendorsementcode) { get; set; } | DCN، رموز الاعتماد القياسية لحامل البطاقة. راجع الرموز في D20. هذا العنصر هو عنصر نائب للجهود المستقبلية لتوحيد رموز الاعتماد، DL، F5AN |
| [StandardRestrictionCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardrestrictioncode) { get; set; } | DCO، رموز القيود القياسية لحامل البطاقة. راجع الرموز في D20. هذا العنصر هو عنصر نائب للجهود المستقبلية لتوحيد رموز القيود، DL، F12AN |
| [StandardVehClassification](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardvehclassification) { get; set; } | DCM، رموز تصنيف المركبة القياسية لحامل البطاقة. هذا العنصر هو عنصر نائب للجهود المستقبلية لتوحيد تصنيفات المركبات، DL، F4AN |
| [Under18Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under18until) { get; set; } | DDH، التاريخ الذي يصبح فيه حامل البطاقة في الثامنة عشرة من عمره. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N |
| [Under19Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under19until) { get; set; } | DDI، التاريخ الذي يصبح فيه حامل البطاقة في التاسعة عشرة من عمره. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N |
| [Under21Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under21until) { get; set; } | DDJ، التاريخ الذي يصبح فيه حامل البطاقة في الحادية والعشرين من عمره. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N |
| [VehClassDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/vehclassdescription) { get; set; } | DCP، نص يوضح الرموز الخاصة بالولاية لتصنيفات المركبات التي يصرّح لحامل البطاقة بقيادتها، DL، V50ANS |
| [VeteranIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/veteranindicator) { get; set; } | DDL، الحقل الذي يشير إلى أن حامل البطاقة من المحاربين القدامى = “1”، DL/ID، F1N |
| [WeightKilograms](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightkilograms) { get; set; } | DAX، وزن حامل البطاقة بالكيلوغرام، مثال: 84 كغ = “084”، DL/ID، F3N |
| [WeightPounds](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightpounds) { get; set; } | DAW، وزن حامل البطاقة بالرطل، مثال: 185 رطل = “185”، DL/ID، F3N |
| [WeightRange](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightrange) { get; set; } | DCE، يشير إلى نطاق الوزن التقريبي لحامل البطاقة: 0 = حتى 31 كغ (حتى 70 رطلاً)، 1 = 32 – 45 كغ (71 – 100 رطلاً)، 2 = 46 - 59 كغ (101 – 130 رطلاً)، 3 = 60 - 70 كغ (131 – 160 رطلاً)، 4 = 71 - 86 كغ (161 – 190 رطلاً)، 5 = 87 - 100 كغ (191 – 220 رطلاً)، 6 = 101 - 113 كغ (221 – 250 رطلاً)، 7 = 114 - 127 كغ (251 – 280 رطلاً)، 8 = 128 – 145 كغ (281 – 320 رطلاً)، 9 = 146+ كغ (321+ رطلاً)، DL/ID، F1N |

### انظر أيضًا

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


