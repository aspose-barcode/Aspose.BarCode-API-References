---
title: "USADriveIdCodetext.OptionalFields"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "حقول العناصر الاختيارية للبطاقة"
type: docs
weight: 11
url: /ar/java/com.aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.OptionalFields
```

العناصر (الحقول) الاختيارية للبطاقة
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [OptionalFields()](#OptionalFields--) |  |
## الدوال

| دالة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressStreet2()](#getAddressStreet2--) | DAH، السطر الثاني من جزء الشارع في عنوان حامل البطاقة، DL/ID، V35ANS |
| [getAliasAKAFamilyName()](#getAliasAKAFamilyName--) | DBN، اسم العائلة الآخر الذي يعرف به حامل البطاقة، DL/ID، V10ANS |
| [getAliasAKAGivenName()](#getAliasAKAGivenName--) | DBG، الاسم الشخصي الآخر الذي يعرف به حامل البطاقة، DL/ID، V15ANS |
| [getAliasAKASuffixName()](#getAliasAKASuffixName--) | DBS، اللقب الآخر الذي يعرف به حامل البطاقة، DL/ID، V5ANS |
| [getAuditInformation()](#getAuditInformation--) | DCJ, سلسلة من الحروف و/أو الأرقام التي تحدد متى وأين ومن قام بصنع رخصة القيادة/بطاقة الهوية. |
| [getCardRevisionDate()](#getCardRevisionDate--) | DDB, حقل مطلوب من DHS يشير إلى تاريخ أحدث تغيير نسخة أو تعديل لتنسيق DL/ID المرئي. |
| [getClass()](#getClass--) |  |
| [getComplianceType()](#getComplianceType--) | DDA, حقل مطلوب من DHS يشير إلى الامتثال: \u201cF\u201d = متوافق؛ و, \u201cN\u201d = غير متوافق، DL/ID، F1A |
| [getEndorsementCodeDescription()](#getEndorsementCodeDescription--) | DCQ, نص يشرح الرموز الخاصة بالولاية التي تشير إلى امتيازات قيادة إضافية ممنوحة لحامل البطاقة بخلاف فئة المركبة، DL، V50ANS |
| [getHAZMATEndorsementExpDate()](#getHAZMATEndorsementExpDate--) | DDC, تاريخ انتهاء صلاحية اعتماد المواد الخطرة الممنوح من الوثيقة. |
| [getHairColor()](#getHairColor--) | DAZ, أصلع، أسود، أشقر، بني، رمادي، أحمر/كستنائي، رملي، أبيض، غير معروف. |
| [getInventoryControlNumber()](#getInventoryControlNumber--) | DCK, سلسلة من الحروف و/أو الأرقام تُلصق على المواد الخام (ورق البطاقات، اللصق، إلخ) المستخدمة في إنتاج رخص القيادة وبطاقات الهوية. |
| [getLimitedDurationDocIndicator()](#getLimitedDurationDocIndicator--) | DDD, حقل مطلوب من DHS يشير إلى أن حامل البطاقة لديه وضع قانوني مؤقت = \u201c1\u201d، DL/ID، F1N |
| [getNameSuffix()](#getNameSuffix--) | DCU, لاحقة الاسم (إذا شاركت الولاية في الأنظمة التي تتطلب لاحقة الاسم (PDPS، CDLIS، إلخ)، يجب جمع اللاحقة وعرضها على DL/ID وفي MRT). |
| [getOrganDonorIndicator()](#getOrganDonorIndicator--) | DDK, حقل يشير إلى أن حامل البطاقة متبرع بأعضاء = \u201c1\u201d، DL/ID، F1N |
| [getPlaceOfBirth()](#getPlaceOfBirth--) | DCI, الدولة والبلدية و/أو الولاية/المقاطعة، DL/ID، V33A |
| [getRaceEthnicity()](#getRaceEthnicity--) | DCL, رموز للعرق أو الإثنية لحامل البطاقة، كما هو معرف في AAMVA D20، DL/ID، V3A |
| [getRestrictionCodeDescription()](#getRestrictionCodeDescription--) | DCR, نص يصف رموز القيود الخاصة بالولاية التي تقيد امتيازات القيادة، DL، V50ANS |
| [getStandardEndorsementCode()](#getStandardEndorsementCode--) | DCN, رموز الاعتماد القياسية لحامل البطاقة. |
| [getStandardRestrictionCode()](#getStandardRestrictionCode--) | DCO, رموز القيود القياسية لحامل البطاقة. |
| [getStandardVehClassification()](#getStandardVehClassification--) | DCM, رموز تصنيف المركبة القياسية لحامل البطاقة. |
| [getUnder18Until()](#getUnder18Until--) | DDH, تاريخ بلوغ حامل البطاقة 18 سنة. |
| [getUnder19Until()](#getUnder19Until--) | DDI, تاريخ بلوغ حامل البطاقة 19 سنة. |
| [getUnder21Until()](#getUnder21Until--) | DDJ, تاريخ بلوغ حامل البطاقة 21 سنة. |
| [getVehClassDescription()](#getVehClassDescription--) | DCP, نص يشرح الرموز الخاصة بالولاية لتصنيفات المركبات التي يُسمح لحامل البطاقة بقيادتها، DL، V50ANS |
| [getVeteranIndicator()](#getVeteranIndicator--) | DDL, حقل يشير إلى أن حامل البطاقة هو محارب قديم = \u201c1\u201d، DL/ID، F1N |
| [getWeightKilograms()](#getWeightKilograms--) | DAX, وزن حامل البطاقة بالكيلوغرام، مثال. |
| [getWeightPounds()](#getWeightPounds--) | DAW, وزن حامل البطاقة بالرطل، مثال. |
| [getWeightRange()](#getWeightRange--) | DCE, يشير إلى النطاق التقريبي لوزن حامل البطاقة: 0 = حتى 31 كغ (حتى 70 رطلاً)، 1 = 32 \u2013 45 كغ (71 \u2013 100 رطلاً)، 2 = 46 - 59 كغ (101 \u2013 130 رطلاً)، 3 = 60 - 70 كغ (131 \u2013 160 رطلاً)، 4 = 71 - 86 كغ (161 \u2013 190 رطلاً)، 5 = 87 - 100 كغ (191 \u2013 220 رطلاً)، 6 = 101 - 113 كغ (221 \u2013 250 رطلاً)، 7 = 114 - 127 كغ (251 \u2013 280 رطلاً)، 8 = 128 \u2013 145 كغ (281 \u2013 320 رطلاً)، 9 = 146+ كغ (321+ رطلاً)، DL/ID، F1N |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressStreet2(String value)](#setAddressStreet2-java.lang.String-) | DAH، السطر الثاني من جزء الشارع في عنوان حامل البطاقة، DL/ID، V35ANS |
| [setAliasAKAFamilyName(String value)](#setAliasAKAFamilyName-java.lang.String-) | DBN، اسم العائلة الآخر الذي يعرف به حامل البطاقة، DL/ID، V10ANS |
| [setAliasAKAGivenName(String value)](#setAliasAKAGivenName-java.lang.String-) | DBG، الاسم الشخصي الآخر الذي يعرف به حامل البطاقة، DL/ID، V15ANS |
| [setAliasAKASuffixName(String value)](#setAliasAKASuffixName-java.lang.String-) | DBS، اللقب الآخر الذي يعرف به حامل البطاقة، DL/ID، V5ANS |
| [setAuditInformation(String value)](#setAuditInformation-java.lang.String-) | DCJ, سلسلة من الحروف و/أو الأرقام التي تحدد متى وأين ومن قام بصنع رخصة القيادة/بطاقة الهوية. |
| [setCardRevisionDate(LocalDate value)](#setCardRevisionDate-java.time.LocalDate-) | DDB, حقل مطلوب من DHS يشير إلى تاريخ أحدث تغيير نسخة أو تعديل لتنسيق DL/ID المرئي. |
| [setComplianceType(String value)](#setComplianceType-java.lang.String-) | DDA, حقل مطلوب من DHS يشير إلى الامتثال: \u201cF\u201d = متوافق؛ و, \u201cN\u201d = غير متوافق، DL/ID، F1A |
| [setEndorsementCodeDescription(String value)](#setEndorsementCodeDescription-java.lang.String-) | DCQ, نص يشرح الرموز الخاصة بالولاية التي تشير إلى امتيازات قيادة إضافية ممنوحة لحامل البطاقة بخلاف فئة المركبة، DL، V50ANS |
| [setHAZMATEndorsementExpDate(LocalDate value)](#setHAZMATEndorsementExpDate-java.time.LocalDate-) | DDC, تاريخ انتهاء صلاحية اعتماد المواد الخطرة الممنوح من الوثيقة. |
| [setHairColor(USADriveIdHairColor value)](#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-) | DAZ, أصلع، أسود، أشقر، بني، رمادي، أحمر/كستنائي، رملي، أبيض، غير معروف. |
| [setInventoryControlNumber(String value)](#setInventoryControlNumber-java.lang.String-) | DCK, سلسلة من الحروف و/أو الأرقام تُلصق على المواد الخام (ورق البطاقات، اللصق، إلخ) المستخدمة في إنتاج رخص القيادة وبطاقات الهوية. |
| [setLimitedDurationDocIndicator(String value)](#setLimitedDurationDocIndicator-java.lang.String-) | DDD, حقل مطلوب من DHS يشير إلى أن حامل البطاقة لديه وضع قانوني مؤقت = \u201c1\u201d، DL/ID، F1N |
| [setNameSuffix(String value)](#setNameSuffix-java.lang.String-) | DCU, لاحقة الاسم (إذا شاركت الولاية في الأنظمة التي تتطلب لاحقة الاسم (PDPS، CDLIS، إلخ)، يجب جمع اللاحقة وعرضها على DL/ID وفي MRT). |
| [setOrganDonorIndicator(String value)](#setOrganDonorIndicator-java.lang.String-) | DDK, حقل يشير إلى أن حامل البطاقة متبرع بأعضاء = \u201c1\u201d، DL/ID، F1N |
| [setPlaceOfBirth(String value)](#setPlaceOfBirth-java.lang.String-) | DCI, الدولة والبلدية و/أو الولاية/المقاطعة، DL/ID، V33A |
| [setRaceEthnicity(String value)](#setRaceEthnicity-java.lang.String-) | DCL, رموز للعرق أو الإثنية لحامل البطاقة، كما هو معرف في AAMVA D20، DL/ID، V3A |
| [setRestrictionCodeDescription(String value)](#setRestrictionCodeDescription-java.lang.String-) | DCR, نص يصف رموز القيود الخاصة بالولاية التي تقيد امتيازات القيادة، DL، V50ANS |
| [setStandardEndorsementCode(String value)](#setStandardEndorsementCode-java.lang.String-) | DCN, رموز الاعتماد القياسية لحامل البطاقة. |
| [setStandardRestrictionCode(String value)](#setStandardRestrictionCode-java.lang.String-) | DCO, رموز القيود القياسية لحامل البطاقة. |
| [setStandardVehClassification(String value)](#setStandardVehClassification-java.lang.String-) | DCM, رموز تصنيف المركبة القياسية لحامل البطاقة. |
| [setUnder18Until(LocalDate value)](#setUnder18Until-java.time.LocalDate-) | DDH, تاريخ بلوغ حامل البطاقة 18 سنة. |
| [setUnder19Until(LocalDate value)](#setUnder19Until-java.time.LocalDate-) | DDI, تاريخ بلوغ حامل البطاقة 19 سنة. |
| [setUnder21Until(LocalDate value)](#setUnder21Until-java.time.LocalDate-) | DDJ, تاريخ بلوغ حامل البطاقة 21 سنة. |
| [setVehClassDescription(String value)](#setVehClassDescription-java.lang.String-) | DCP, نص يشرح الرموز الخاصة بالولاية لتصنيفات المركبات التي يُسمح لحامل البطاقة بقيادتها، DL، V50ANS |
| [setVeteranIndicator(String value)](#setVeteranIndicator-java.lang.String-) | DDL, حقل يشير إلى أن حامل البطاقة هو محارب قديم = \u201c1\u201d، DL/ID، F1N |
| [setWeightKilograms(int value)](#setWeightKilograms-int-) | DAX, وزن حامل البطاقة بالكيلوغرام، مثال. |
| [setWeightPounds(int value)](#setWeightPounds-int-) | DAW, وزن حامل البطاقة بالرطل، مثال. |
| [setWeightRange(String value)](#setWeightRange-java.lang.String-) | DCE, يشير إلى النطاق التقريبي لوزن حامل البطاقة: 0 = حتى 31 كغ (حتى 70 رطلاً)، 1 = 32 \u2013 45 كغ (71 \u2013 100 رطلاً)، 2 = 46 - 59 كغ (101 \u2013 130 رطلاً)، 3 = 60 - 70 كغ (131 \u2013 160 رطلاً)، 4 = 71 - 86 كغ (161 \u2013 190 رطلاً)، 5 = 87 - 100 كغ (191 \u2013 220 رطلاً)، 6 = 101 - 113 كغ (221 \u2013 250 رطلاً)، 7 = 114 - 127 كغ (251 \u2013 280 رطلاً)، 8 = 128 \u2013 145 كغ (281 \u2013 320 رطلاً)، 9 = 146+ كغ (321+ رطلاً)، DL/ID، F1N |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OptionalFields() {#OptionalFields--}
```
public OptionalFields()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAddressStreet2() {#getAddressStreet2--}
```
public final String getAddressStreet2()
```


DAH، السطر الثاني من جزء الشارع في عنوان حامل البطاقة، DL/ID، V35ANS

**Returns:**
java.lang.String
### getAliasAKAFamilyName() {#getAliasAKAFamilyName--}
```
public final String getAliasAKAFamilyName()
```


DBN، اسم العائلة الآخر الذي يعرف به حامل البطاقة، DL/ID، V10ANS

**Returns:**
java.lang.String
### getAliasAKAGivenName() {#getAliasAKAGivenName--}
```
public final String getAliasAKAGivenName()
```


DBG، الاسم الشخصي الآخر الذي يعرف به حامل البطاقة، DL/ID، V15ANS

**Returns:**
java.lang.String
### getAliasAKASuffixName() {#getAliasAKASuffixName--}
```
public final String getAliasAKASuffixName()
```


DBS، اللقب الآخر الذي يعرف به حامل البطاقة، DL/ID، V5ANS

**Returns:**
java.lang.String
### getAuditInformation() {#getAuditInformation--}
```
public final String getAuditInformation()
```


DCJ, سلسلة من الحروف و/أو الأرقام التي تحدد متى وأين ومن قام بصنع رخصة القيادة/بطاقة الهوية. إذا لم تُستخدم معلومات التدقيق على البطاقة أو MRT، يجب تضمينها في سجل السائق، DL/ID، V25ANS

**Returns:**
java.lang.String
### getCardRevisionDate() {#getCardRevisionDate--}
```
public final LocalDate getCardRevisionDate()
```


DDB، حقل مطلوب من DHS يشير إلى تاريخ أحدث تغيير في النسخة أو تعديل لتنسيق DL/ID الظاهر. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N

**Returns:**
java.time.LocalDate
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComplianceType() {#getComplianceType--}
```
public final String getComplianceType()
```


DDA, حقل مطلوب من DHS يشير إلى الامتثال: \u201cF\u201d = متوافق؛ و, \u201cN\u201d = غير متوافق، DL/ID، F1A

**Returns:**
java.lang.String
### getEndorsementCodeDescription() {#getEndorsementCodeDescription--}
```
public final String getEndorsementCodeDescription()
```


DCQ, نص يشرح الرموز الخاصة بالولاية التي تشير إلى امتيازات قيادة إضافية ممنوحة لحامل البطاقة بخلاف فئة المركبة، DL، V50ANS

**Returns:**
java.lang.String
### getHAZMATEndorsementExpDate() {#getHAZMATEndorsementExpDate--}
```
public final LocalDate getHAZMATEndorsementExpDate()
```


DDC، التاريخ الذي يصبح فيه اعتماد المواد الخطرة الممنوح من الوثيقة غير صالح. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL، F8N

**Returns:**
java.time.LocalDate
### getHairColor() {#getHairColor--}
```
public final USADriveIdHairColor getHairColor()
```


DAZ، أصلع، أسود، أشقر، بني، رمادي، أحمر/كستنائي، رملي، أبيض، غير معروف. إذا رغبت السلطة المصدرة في اختصار الألوان، يجب استخدام الرموز الثلاثية الأحرف المتوفرة في AAMVA D20، DL/ID، V12A

**Returns:**
[USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor)
### getInventoryControlNumber() {#getInventoryControlNumber--}
```
public final String getInventoryControlNumber()
```


DCK، سلسلة من الأحرف و/أو الأرقام تُلصق على المواد الخام (ورق البطاقات، اللصق، إلخ) المستخدمة في إنتاج رخص القيادة وبطاقات الهوية. (حقل موصى به من DHS)، DL/ID، V25ANS

**Returns:**
java.lang.String
### getLimitedDurationDocIndicator() {#getLimitedDurationDocIndicator--}
```
public final String getLimitedDurationDocIndicator()
```


DDD, حقل مطلوب من DHS يشير إلى أن حامل البطاقة لديه وضع قانوني مؤقت = \u201c1\u201d، DL/ID، F1N

**Returns:**
java.lang.String
### getNameSuffix() {#getNameSuffix--}
```
public final String getNameSuffix()
```


DCU، لاحقة الاسم (إذا شاركت السلطة في أنظمة تتطلب لاحقة الاسم (PDPS، CDLIS، إلخ)، يجب جمع اللاحقة وعرضها على DL/ID وفي MRT). JR (Junior)، SR (Senior)، 1ST أو I (First)، حتى 9TH أو IX (Ninth)، DL/ID، V5ANS

**Returns:**
java.lang.String
### getOrganDonorIndicator() {#getOrganDonorIndicator--}
```
public final String getOrganDonorIndicator()
```


DDK, حقل يشير إلى أن حامل البطاقة متبرع بأعضاء = \u201c1\u201d، DL/ID، F1N

**Returns:**
java.lang.String
### getPlaceOfBirth() {#getPlaceOfBirth--}
```
public final String getPlaceOfBirth()
```


DCI, الدولة والبلدية و/أو الولاية/المقاطعة، DL/ID، V33A

**Returns:**
java.lang.String
### getRaceEthnicity() {#getRaceEthnicity--}
```
public final String getRaceEthnicity()
```


DCL, رموز للعرق أو الإثنية لحامل البطاقة، كما هو معرف في AAMVA D20، DL/ID، V3A

**Returns:**
java.lang.String
### getRestrictionCodeDescription() {#getRestrictionCodeDescription--}
```
public final String getRestrictionCodeDescription()
```


DCR, نص يصف رموز القيود الخاصة بالولاية التي تقيد امتيازات القيادة، DL، V50ANS

**Returns:**
java.lang.String
### getStandardEndorsementCode() {#getStandardEndorsementCode--}
```
public final String getStandardEndorsementCode()
```


DCN، رمز(ات) الاعتماد القياسي لحامل البطاقة. راجع الرموز في D20. هذا العنصر البيانات هو عنصر نائب للجهود المستقبلية لتوحيد رموز الاعتماد، DL، F5AN

**Returns:**
java.lang.String
### getStandardRestrictionCode() {#getStandardRestrictionCode--}
```
public final String getStandardRestrictionCode()
```


DCO، رمز(ات) القيود القياسي لحامل البطاقة. راجع الرموز في D20. هذا العنصر البيانات هو عنصر نائب للجهود المستقبلية لتوحيد رموز القيود، DL، F12AN

**Returns:**
java.lang.String
### getStandardVehClassification() {#getStandardVehClassification--}
```
public final String getStandardVehClassification()
```


DCM، رمز(ات) تصنيف المركبة القياسي لحامل البطاقة. هذا العنصر البيانات هو عنصر نائب للجهود المستقبلية لتوحيد تصنيفات المركبات، DL، F4AN

**Returns:**
java.lang.String
### getUnder18Until() {#getUnder18Until--}
```
public final LocalDate getUnder18Until()
```


DDH، التاريخ الذي يصبح فيه حامل البطاقة في الثامنة عشرة من عمره. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N

**Returns:**
java.time.LocalDate
### getUnder19Until() {#getUnder19Until--}
```
public final LocalDate getUnder19Until()
```


DDI، التاريخ الذي يصبح فيه حامل البطاقة في التاسعة عشرة من عمره. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N

**Returns:**
java.time.LocalDate
### getUnder21Until() {#getUnder21Until--}
```
public final LocalDate getUnder21Until()
```


DDJ، التاريخ الذي يصبح فيه حامل البطاقة في الحادية والعشرين من عمره. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N

**Returns:**
java.time.LocalDate
### getVehClassDescription() {#getVehClassDescription--}
```
public final String getVehClassDescription()
```


DCP, نص يشرح الرموز الخاصة بالولاية لتصنيفات المركبات التي يُسمح لحامل البطاقة بقيادتها، DL، V50ANS

**Returns:**
java.lang.String
### getVeteranIndicator() {#getVeteranIndicator--}
```
public final String getVeteranIndicator()
```


DDL, حقل يشير إلى أن حامل البطاقة هو محارب قديم = \u201c1\u201d، DL/ID، F1N

**Returns:**
java.lang.String
### getWeightKilograms() {#getWeightKilograms--}
```
public final int getWeightKilograms()
```


DAX، وزن حامل البطاقة بالكيلوغرام، مثال: 84 كغ = \\u201c084\\u201d، DL/ID، F3N

**Returns:**
int
### getWeightPounds() {#getWeightPounds--}
```
public final int getWeightPounds()
```


DAW، وزن حامل البطاقة بالرطل، مثال: 185 رطل = \\u201c185\\u201d، DL/ID، F3N

**Returns:**
int
### getWeightRange() {#getWeightRange--}
```
public final String getWeightRange()
```


DCE, يشير إلى النطاق التقريبي لوزن حامل البطاقة: 0 = حتى 31 كغ (حتى 70 رطلاً)، 1 = 32 \u2013 45 كغ (71 \u2013 100 رطلاً)، 2 = 46 - 59 كغ (101 \u2013 130 رطلاً)، 3 = 60 - 70 كغ (131 \u2013 160 رطلاً)، 4 = 71 - 86 كغ (161 \u2013 190 رطلاً)، 5 = 87 - 100 كغ (191 \u2013 220 رطلاً)، 6 = 101 - 113 كغ (221 \u2013 250 رطلاً)، 7 = 114 - 127 كغ (251 \u2013 280 رطلاً)، 8 = 128 \u2013 145 كغ (281 \u2013 320 رطلاً)، 9 = 146+ كغ (321+ رطلاً)، DL/ID، F1N

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAddressStreet2(String value) {#setAddressStreet2-java.lang.String-}
```
public final void setAddressStreet2(String value)
```


DAH، السطر الثاني من جزء الشارع في عنوان حامل البطاقة، DL/ID، V35ANS

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setAliasAKAFamilyName(String value) {#setAliasAKAFamilyName-java.lang.String-}
```
public final void setAliasAKAFamilyName(String value)
```


DBN، اسم العائلة الآخر الذي يعرف به حامل البطاقة، DL/ID، V10ANS

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setAliasAKAGivenName(String value) {#setAliasAKAGivenName-java.lang.String-}
```
public final void setAliasAKAGivenName(String value)
```


DBG، الاسم الشخصي الآخر الذي يعرف به حامل البطاقة، DL/ID، V15ANS

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setAliasAKASuffixName(String value) {#setAliasAKASuffixName-java.lang.String-}
```
public final void setAliasAKASuffixName(String value)
```


DBS، اللقب الآخر الذي يعرف به حامل البطاقة، DL/ID، V5ANS

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setAuditInformation(String value) {#setAuditInformation-java.lang.String-}
```
public final void setAuditInformation(String value)
```


DCJ, سلسلة من الحروف و/أو الأرقام التي تحدد متى وأين ومن قام بصنع رخصة القيادة/بطاقة الهوية. إذا لم تُستخدم معلومات التدقيق على البطاقة أو MRT، يجب تضمينها في سجل السائق، DL/ID، V25ANS

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setCardRevisionDate(LocalDate value) {#setCardRevisionDate-java.time.LocalDate-}
```
public final void setCardRevisionDate(LocalDate value)
```


DDB، حقل مطلوب من DHS يشير إلى تاريخ أحدث تغيير في النسخة أو تعديل لتنسيق DL/ID الظاهر. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.time.LocalDate |  |

### setComplianceType(String value) {#setComplianceType-java.lang.String-}
```
public final void setComplianceType(String value)
```


DDA, حقل مطلوب من DHS يشير إلى الامتثال: \u201cF\u201d = متوافق؛ و, \u201cN\u201d = غير متوافق، DL/ID، F1A

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setEndorsementCodeDescription(String value) {#setEndorsementCodeDescription-java.lang.String-}
```
public final void setEndorsementCodeDescription(String value)
```


DCQ, نص يشرح الرموز الخاصة بالولاية التي تشير إلى امتيازات قيادة إضافية ممنوحة لحامل البطاقة بخلاف فئة المركبة، DL، V50ANS

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setHAZMATEndorsementExpDate(LocalDate value) {#setHAZMATEndorsementExpDate-java.time.LocalDate-}
```
public final void setHAZMATEndorsementExpDate(LocalDate value)
```


DDC، التاريخ الذي يصبح فيه اعتماد المواد الخطرة الممنوح من الوثيقة غير صالح. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL، F8N

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.time.LocalDate |  |

### setHairColor(USADriveIdHairColor value) {#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-}
```
public final void setHairColor(USADriveIdHairColor value)
```


DAZ، أصلع، أسود، أشقر، بني، رمادي، أحمر/كستنائي، رملي، أبيض، غير معروف. إذا رغبت السلطة المصدرة في اختصار الألوان، يجب استخدام الرموز الثلاثية الأحرف المتوفرة في AAMVA D20، DL/ID، V12A

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor) |  |

### setInventoryControlNumber(String value) {#setInventoryControlNumber-java.lang.String-}
```
public final void setInventoryControlNumber(String value)
```


DCK، سلسلة من الأحرف و/أو الأرقام تُلصق على المواد الخام (ورق البطاقات، اللصق، إلخ) المستخدمة في إنتاج رخص القيادة وبطاقات الهوية. (حقل موصى به من DHS)، DL/ID، V25ANS

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setLimitedDurationDocIndicator(String value) {#setLimitedDurationDocIndicator-java.lang.String-}
```
public final void setLimitedDurationDocIndicator(String value)
```


DDD, حقل مطلوب من DHS يشير إلى أن حامل البطاقة لديه وضع قانوني مؤقت = \u201c1\u201d، DL/ID، F1N

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setNameSuffix(String value) {#setNameSuffix-java.lang.String-}
```
public final void setNameSuffix(String value)
```


DCU، لاحقة الاسم (إذا شاركت السلطة في أنظمة تتطلب لاحقة الاسم (PDPS، CDLIS، إلخ)، يجب جمع اللاحقة وعرضها على DL/ID وفي MRT). JR (Junior)، SR (Senior)، 1ST أو I (First)، حتى 9TH أو IX (Ninth)، DL/ID، V5ANS

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setOrganDonorIndicator(String value) {#setOrganDonorIndicator-java.lang.String-}
```
public final void setOrganDonorIndicator(String value)
```


DDK, حقل يشير إلى أن حامل البطاقة متبرع بأعضاء = \u201c1\u201d، DL/ID، F1N

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setPlaceOfBirth(String value) {#setPlaceOfBirth-java.lang.String-}
```
public final void setPlaceOfBirth(String value)
```


DCI, الدولة والبلدية و/أو الولاية/المقاطعة، DL/ID، V33A

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setRaceEthnicity(String value) {#setRaceEthnicity-java.lang.String-}
```
public final void setRaceEthnicity(String value)
```


DCL, رموز للعرق أو الإثنية لحامل البطاقة، كما هو معرف في AAMVA D20، DL/ID، V3A

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setRestrictionCodeDescription(String value) {#setRestrictionCodeDescription-java.lang.String-}
```
public final void setRestrictionCodeDescription(String value)
```


DCR, نص يصف رموز القيود الخاصة بالولاية التي تقيد امتيازات القيادة، DL، V50ANS

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setStandardEndorsementCode(String value) {#setStandardEndorsementCode-java.lang.String-}
```
public final void setStandardEndorsementCode(String value)
```


DCN، رمز(ات) الاعتماد القياسي لحامل البطاقة. راجع الرموز في D20. هذا العنصر البيانات هو عنصر نائب للجهود المستقبلية لتوحيد رموز الاعتماد، DL، F5AN

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setStandardRestrictionCode(String value) {#setStandardRestrictionCode-java.lang.String-}
```
public final void setStandardRestrictionCode(String value)
```


DCO، رمز(ات) القيود القياسي لحامل البطاقة. راجع الرموز في D20. هذا العنصر البيانات هو عنصر نائب للجهود المستقبلية لتوحيد رموز القيود، DL، F12AN

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setStandardVehClassification(String value) {#setStandardVehClassification-java.lang.String-}
```
public final void setStandardVehClassification(String value)
```


DCM، رمز(ات) تصنيف المركبة القياسي لحامل البطاقة. هذا العنصر البيانات هو عنصر نائب للجهود المستقبلية لتوحيد تصنيفات المركبات، DL، F4AN

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setUnder18Until(LocalDate value) {#setUnder18Until-java.time.LocalDate-}
```
public final void setUnder18Until(LocalDate value)
```


DDH، التاريخ الذي يصبح فيه حامل البطاقة في الثامنة عشرة من عمره. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.time.LocalDate |  |

### setUnder19Until(LocalDate value) {#setUnder19Until-java.time.LocalDate-}
```
public final void setUnder19Until(LocalDate value)
```


DDI، التاريخ الذي يصبح فيه حامل البطاقة في التاسعة عشرة من عمره. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.time.LocalDate |  |

### setUnder21Until(LocalDate value) {#setUnder21Until-java.time.LocalDate-}
```
public final void setUnder21Until(LocalDate value)
```


DDJ، التاريخ الذي يصبح فيه حامل البطاقة في الحادية والعشرين من عمره. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.time.LocalDate |  |

### setVehClassDescription(String value) {#setVehClassDescription-java.lang.String-}
```
public final void setVehClassDescription(String value)
```


DCP, نص يشرح الرموز الخاصة بالولاية لتصنيفات المركبات التي يُسمح لحامل البطاقة بقيادتها، DL، V50ANS

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setVeteranIndicator(String value) {#setVeteranIndicator-java.lang.String-}
```
public final void setVeteranIndicator(String value)
```


DDL, حقل يشير إلى أن حامل البطاقة هو محارب قديم = \u201c1\u201d، DL/ID، F1N

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setWeightKilograms(int value) {#setWeightKilograms-int-}
```
public final void setWeightKilograms(int value)
```


DAX، وزن حامل البطاقة بالكيلوغرام، مثال: 84 كغ = \\u201c084\\u201d، DL/ID، F3N

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setWeightPounds(int value) {#setWeightPounds-int-}
```
public final void setWeightPounds(int value)
```


DAW، وزن حامل البطاقة بالرطل، مثال: 185 رطل = \\u201c185\\u201d، DL/ID، F3N

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setWeightRange(String value) {#setWeightRange-java.lang.String-}
```
public final void setWeightRange(String value)
```


DCE, يشير إلى النطاق التقريبي لوزن حامل البطاقة: 0 = حتى 31 كغ (حتى 70 رطلاً)، 1 = 32 \u2013 45 كغ (71 \u2013 100 رطلاً)، 2 = 46 - 59 كغ (101 \u2013 130 رطلاً)، 3 = 60 - 70 كغ (131 \u2013 160 رطلاً)، 4 = 71 - 86 كغ (161 \u2013 190 رطلاً)، 5 = 87 - 100 كغ (191 \u2013 220 رطلاً)، 6 = 101 - 113 كغ (221 \u2013 250 رطلاً)، 7 = 114 - 127 كغ (251 \u2013 280 رطلاً)، 8 = 128 \u2013 145 كغ (281 \u2013 320 رطلاً)، 9 = 146+ كغ (321+ رطلاً)، DL/ID، F1N

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

