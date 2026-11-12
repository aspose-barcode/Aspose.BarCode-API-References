---
title: "OptionalFields"
linktitle: "OptionalFields"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "العناصر (الحقول) الاختيارية للبطاقة."
type: docs
weight: 730
url: /ar/nodejs/aspose.barcode/optionalfields/
---

## OptionalFields class

العناصر (الحقول) الاختيارية للبطاقة.

```js
new OptionalFields()
```

## طرق

| اسم | الوصف |
| --- | --- |
| [getAliasAKAFamilyName()](#getaliasakafamilyname) | DBN، الاسم العائلي الآخر المعروف به حامل البطاقة، DL/ID، V10ANS |
| [getAliasAKAGivenName()](#getaliasakagivenname) | DBG، الاسم الأول الآخر المعروف به حامل البطاقة، DL/ID، V15ANS |
| [getAliasAKASuffixName()](#getaliasakasuffixname) | DBS، اللواحق الأخرى المعروفة بها حامل البطاقة، DL/ID، V5ANS |
| [getAuditInformation()](#getauditinformation) | DCJ، سلسلة من الأحرف و/أو الأرقام تحدد متى وأين ومن قام بإنشاء رخصة القيادة/بطاقة الهوية. إذا كان |
| [getCardRevisionDate()](#getcardrevisiondate) | DDB، حقل مطلوب من DHS يشير إلى تاريخ أحدث تغيير في الإصدار أو تعديل لتنسيق العرض of t |
| [getComplianceType()](#getcompliancetype) | DDA، حقل مطلوب من DHS يشير إلى الامتثال: “F” = متوافق؛ و “N” = غير متوافق، DL/ID، F1A |
| [getEndorsementCodeDescription()](#getendorsementcodedescription) | DCQ، نص يشرح الرموز الخاصة بالولاية التي تشير إلى امتيازات قيادة إضافية ممنوحة للـ ca |
| [getHairColor()](#gethaircolor) | DAZ، أصلع، أسود، أشقر، بني، رمادي، أحمر/كستنائي، رملي، أبيض، غير معروف. إذا رغبت الولاية المصدرة في اختصار |
| [getHAZMATEndorsementExpDate()](#gethazmatendorsementexpdate) | DDC، التاريخ الذي يصبح فيه اعتماد المواد الخطرة الممنوح بواسطة الوثيقة غير صالح. (MMDDCCYY للولايات المتحدة، CC |
| [getInventoryControlNumber()](#getinventorycontrolnumber) | DCK، سلسلة من الأحرف و/أو الأرقام تُلصق على المواد الخام (ورق الكرتون، اللصق، إلخ.) المستخدمة في إنتاج |
| [getLimitedDurationDocIndicator()](#getlimiteddurationdocindicator) | DDD، حقل مطلوب من DHS يشير إلى أن حامل البطاقة لديه وضع قانوني مؤقت = “1”، DL/ID، F1N |
| [getNameSuffix()](#getnamesuffix) | DCU، لاحقة الاسم (إذا شاركت الولاية في الأنظمة التي تتطلب لاحقة الاسم (PDPS، CDLIS، إلخ)، يجب أن تكون اللاحقة |
| [getOrganDonorIndicator()](#getorgandonorindicator) | DDK، حقل يشير إلى أن حامل البطاقة متبرع بأعضاء = “1”، DL/ID، F1N |
| [getPlaceOfBirth()](#getplaceofbirth) | DCI، الدولة والبلدية و/أو الولاية/المقاطعة، DL/ID، V33A |
| [getRaceEthnicity()](#getraceethnicity) | DCL، رموز للعرق أو الإثنية لحامل البطاقة، كما هو معرف في AAMVA D20، DL/ID، V3A |
| [getRestrictionCodeDescription()](#getrestrictioncodedescription) | DCR، نص يصف رموز القيود الخاصة بالولاية التي تقيد امتيازات القيادة، DL، V50ANS |
| [getStandardEndorsementCode()](#getstandardendorsementcode) | DCN، رموز الاعتماد القياسية لحامل البطاقة. راجع الرموز في D20. هذا العنصر البيانات هو عنصر نائب للجهود المستقبلية |
| [getStandardRestrictionCode()](#getstandardrestrictioncode) | DCO، رموز القيود القياسية لحامل البطاقة. راجع الرموز في D20. هذا العنصر البيانات هو عنصر نائب للجهود المستقبلية |
| [getStandardVehClassification()](#getstandardvehclassification) | DCM، رموز تصنيف المركبة القياسية لحامل البطاقة. هذا العنصر البيانات هو عنصر نائب للجهود المستقبلية لـ |
| [getUnder18Until()](#getunder18until) | DDH، التاريخ الذي يصبح فيه حامل البطاقة في الثامنة عشرة من عمره. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N |
| [getUnder21Until()](#getunder21until) | DDJ، التاريخ الذي يصبح فيه حامل البطاقة في الحادية والعشرين من عمره. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N |
| [getVehClassDescription()](#getvehclassdescription) | DCP، نص يشرح الرموز الخاصة بالولاية لتصنيفات المركبات التي يُسمح لحامل البطاقة بقيادتها |
| [getVeteranIndicator()](#getveteranindicator) | DDL، حقل يشير إلى أن حامل البطاقة هو محارب قديم = “1”، DL/ID، F1N |
| [getWeightKilograms()](#getweightkilograms) | DAX، وزن حامل البطاقة بالكيلوغرام، مثال: 84 كغ = “084”، DL/ID، F3N |
| [getWeightPounds()](#getweightpounds) | DAW، وزن حامل البطاقة بالرطل، مثال: 185 رطل = “185”، DL/ID، F3N |
| [getWeightRange()](#getweightrange) | DCE، يشير إلى نطاق الوزن التقريبي لحامل البطاقة: 0 = حتى 31 كغ (حتى 70 رطلاً)، 1 = 32 – 45 كغ (71 – 100 رطلاً |
| [setAddressStreet2()](#setaddressstreet2) | DAH، السطر الثاني من جزء الشارع في عنوان حامل البطاقة، DL/ID، V35ANS |
| [setAliasAKAFamilyName()](#setaliasakafamilyname) | DBN، الاسم العائلي الآخر المعروف به حامل البطاقة، DL/ID، V10ANS |
| [setAliasAKAGivenName()](#setaliasakagivenname) | DBG، الاسم الأول الآخر المعروف به حامل البطاقة، DL/ID، V15ANS |
| [setAliasAKASuffixName()](#setaliasakasuffixname) | DBS، اللواحق الأخرى المعروفة بها حامل البطاقة، DL/ID، V5ANS |
| [setAuditInformation()](#setauditinformation) | DCJ، سلسلة من الأحرف و/أو الأرقام تحدد متى وأين ومن قام بإنشاء رخصة القيادة/بطاقة الهوية. إذا كان |
| [setCardRevisionDate()](#setcardrevisiondate) | DDB، حقل مطلوب من DHS يشير إلى تاريخ أحدث تغيير في الإصدار أو تعديل لتنسيق العرض of t |
| [setComplianceType()](#setcompliancetype) | DDA، حقل مطلوب من DHS يشير إلى الامتثال: “F” = متوافق؛ و “N” = غير متوافق، DL/ID، F1A |
| [setEndorsementCodeDescription()](#setendorsementcodedescription) | DCQ، نص يشرح الرموز الخاصة بالولاية التي تشير إلى امتيازات قيادة إضافية ممنوحة للـ ca |
| [setHairColor()](#sethaircolor) | DAZ، أصلع، أسود، أشقر، بني، رمادي، أحمر/كستنائي، رملي، أبيض، غير معروف. إذا رغبت الولاية المصدرة في اختصار |
| [setInventoryControlNumber()](#setinventorycontrolnumber) | DCK، سلسلة من الأحرف و/أو الأرقام تُلصق على المواد الخام (ورق الكرتون، اللصق، إلخ.) المستخدمة في إنتاج |
| [setLimitedDurationDocIndicator()](#setlimiteddurationdocindicator) | DDD، حقل مطلوب من DHS يشير إلى أن حامل البطاقة لديه وضع قانوني مؤقت = “1”، DL/ID، F1N |
| [setNameSuffix()](#setnamesuffix) | DCU، لاحقة الاسم (إذا شاركت الولاية في الأنظمة التي تتطلب لاحقة الاسم (PDPS، CDLIS، إلخ)، يجب أن تكون اللاحقة |
| [setOrganDonorIndicator()](#setorgandonorindicator) | DDK، حقل يشير إلى أن حامل البطاقة متبرع بأعضاء = “1”، DL/ID، F1N |
| [setPlaceOfBirth()](#setplaceofbirth) | DCI، الدولة والبلدية و/أو الولاية/المقاطعة، DL/ID، V33A |
| [setRaceEthnicity()](#setraceethnicity) | DCL، رموز للعرق أو الإثنية لحامل البطاقة، كما هو معرف في AAMVA D20، DL/ID، V3A |
| [setRestrictionCodeDescription()](#setrestrictioncodedescription) | DCR، نص يصف رموز القيود الخاصة بالولاية التي تقيد امتيازات القيادة، DL، V50ANS |
| [setStandardEndorsementCode()](#setstandardendorsementcode) | DCN، رموز الاعتماد القياسية لحامل البطاقة. راجع الرموز في D20. هذا العنصر البيانات هو عنصر نائب للجهود المستقبلية |
| [setStandardRestrictionCode()](#setstandardrestrictioncode) | DCO، رموز القيود القياسية لحامل البطاقة. راجع الرموز في D20. هذا العنصر البيانات هو عنصر نائب للجهود المستقبلية |
| [setStandardVehClassification()](#setstandardvehclassification) | DCM، رموز تصنيف المركبة القياسية لحامل البطاقة. هذا العنصر البيانات هو عنصر نائب للجهود المستقبلية لـ |
| [setUnder18Until()](#setunder18until) | DDI، التاريخ الذي يصبح فيه حامل البطاقة في التاسعة عشرة من عمره. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N |
| [setUnder19Until()](#setunder19until) | DDI، التاريخ الذي يصبح فيه حامل البطاقة في التاسعة عشرة من عمره. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N |
| [setUnder21Until()](#setunder21until) | DDJ، التاريخ الذي يصبح فيه حامل البطاقة في الحادية والعشرين من عمره. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N |
| [setVehClassDescription()](#setvehclassdescription) | DCP، نص يشرح الرموز الخاصة بالولاية لتصنيفات المركبات التي يُسمح لحامل البطاقة بقيادتها |
| [setVeteranIndicator()](#setveteranindicator) | DDL، حقل يشير إلى أن حامل البطاقة هو محارب قديم = “1”، DL/ID، F1N |
| [setWeightKilograms()](#setweightkilograms) | DAX، وزن حامل البطاقة بالكيلوغرام، مثال: 84 كغ = “084”، DL/ID، F3N |
| [setWeightPounds()](#setweightpounds) | DAW، وزن حامل البطاقة بالرطل، مثال: 185 رطل = “185”، DL/ID، F3N |
| [setWeightRange()](#setweightrange) | DCE، يشير إلى نطاق الوزن التقريبي لحامل البطاقة: 0 = حتى 31 كغ (حتى 70 رطلاً)، 1 = 32 – 45 كغ (71 – 100 رطلاً |

### getAliasAKAFamilyName() {#getaliasakafamilyname}

DBN، الاسم العائلي الآخر المعروف به حامل البطاقة، DL/ID، V10ANS

### getAliasAKAGivenName() {#getaliasakagivenname}

DBG، الاسم الأول الآخر المعروف به حامل البطاقة، DL/ID، V15ANS

### getAliasAKASuffixName() {#getaliasakasuffixname}

DBS، اللواحق الأخرى المعروفة بها حامل البطاقة، DL/ID، V5ANS

### getAuditInformation() {#getauditinformation}

DCJ، سلسلة من الأحرف و/أو الأرقام تحدد متى وأين ومن قام بصنع رخصة القيادة/بطاقة الهوية. إذا لم تُستخدم معلومات التدقيق على البطاقة أو MRT، يجب تضمينها في سجل السائق، DL/ID، V25ANS

### getCardRevisionDate() {#getcardrevisiondate}

DDB، حقل مطلوب من DHS يشير إلى تاريخ أحدث تغيير في الإصدار أو تعديل لتنسيق DL/ID المرئي. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N

### getComplianceType() {#getcompliancetype}

DDA، حقل مطلوب من DHS يشير إلى الامتثال: “F” = متوافق؛ و “N” = غير متوافق، DL/ID، F1A

### getEndorsementCodeDescription() {#getendorsementcodedescription}

DCQ، نص يشرح الرموز الخاصة بالولاية التي تشير إلى امتيازات قيادة إضافية ممنوحة لحامل البطاقة بما يتجاوز فئة المركبة، DL، V50ANS

### getHairColor() {#gethaircolor}

DAZ، أصلع، أسود، أشقر، بني، رمادي، أحمر/كستنائي، رملي، أبيض، غير معروف. إذا رغبت الولاية المصدرة في اختصار الألوان، يجب استخدام الرموز المكوّنة من ثلاثة أحرف الواردة في AAMVA D20، DL/ID، V12A

### getHAZMATEndorsementExpDate() {#gethazmatendorsementexpdate}

DDC، التاريخ الذي يصبح فيه اعتماد المواد الخطرة الممنوح من الوثيقة غير صالح. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL، F8N

### getInventoryControlNumber() {#getinventorycontrolnumber}

DCK، سلسلة من الأحرف و/أو الأرقام تُلصق بالمواد الخام (ورق البطاقات، اللصق، إلخ) المستخدمة في إنتاج رخص القيادة وبطاقات الهوية. (حقل موصى به من DHS)، DL/ID، V25ANS

### getLimitedDurationDocIndicator() {#getlimiteddurationdocindicator}

DDD، حقل مطلوب من DHS يشير إلى أن حامل البطاقة لديه وضع قانوني مؤقت = “1”، DL/ID، F1N

### getNameSuffix() {#getnamesuffix}

DCU، لاحقة الاسم (إذا شاركت الولاية في أنظمة تتطلب لاحقة الاسم (PDPS، CDLIS، إلخ)، يجب جمع اللاحقة وعرضها على DL/ID وفي MRT). JR (Junior)، SR (Senior)، 1ST أو I (First)، حتى 9TH أو IX (Ninth)، DL/ID، V5ANS

### getOrganDonorIndicator() {#getorgandonorindicator}

DDK، حقل يشير إلى أن حامل البطاقة متبرع بأعضاء = “1”، DL/ID، F1N

### getPlaceOfBirth() {#getplaceofbirth}

DCI، الدولة والبلدية و/أو الولاية/المقاطعة، DL/ID، V33A

### getRaceEthnicity() {#getraceethnicity}

DCL، رموز للعرق أو الإثنية لحامل البطاقة، كما هو معرف في AAMVA D20، DL/ID، V3A

### getRestrictionCodeDescription() {#getrestrictioncodedescription}

DCR، نص يصف رموز القيود الخاصة بالولاية التي تقيد امتيازات القيادة، DL، V50ANS

### getStandardEndorsementCode() {#getstandardendorsementcode}

DCN، رموز الاعتماد القياسية لحامل البطاقة. راجع الرموز في D20. هذا العنصر البيانات هو عنصر نائب لجهود مستقبلية لتوحيد رموز الاعتماد، DL، F5AN

### getStandardRestrictionCode() {#getstandardrestrictioncode}

DCO، رموز القيود القياسية لحامل البطاقة. راجع الرموز في D20. هذا العنصر البيانات هو عنصر نائب لجهود مستقبلية لتوحيد رموز القيود، DL، F12AN

### getStandardVehClassification() {#getstandardvehclassification}

DCM، رموز تصنيف المركبة القياسية لحامل البطاقة. هذا العنصر البيانات هو عنصر نائب لجهود مستقبلية لتوحيد تصنيفات المركبات، DL، F4AN

### getUnder18Until() {#getunder18until}

DDH، التاريخ الذي يصبح فيه حامل البطاقة في الثامنة عشرة من عمره. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N

### getUnder21Until() {#getunder21until}

DDJ، التاريخ الذي يصبح فيه حامل البطاقة في الحادية والعشرين من عمره. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N

### getVehClassDescription() {#getvehclassdescription}

DCP، نص يشرح الرموز الخاصة بالولاية لتصنيفات المركبات التي يُسمح لحامل البطاقة بقيادتها، DL، V50ANS

### getVeteranIndicator() {#getveteranindicator}

DDL، حقل يشير إلى أن حامل البطاقة هو محارب قديم = “1”، DL/ID، F1N

### getWeightKilograms() {#getweightkilograms}

DAX، وزن حامل البطاقة بالكيلوغرام، مثال: 84 كغ = “084”، DL/ID، F3N

### getWeightPounds() {#getweightpounds}

DAW، وزن حامل البطاقة بالرطل، مثال: 185 رطل = “185”، DL/ID، F3N

### getWeightRange() {#getweightrange}

DCE، يحدد النطاق التقريبي لوزن حامل البطاقة: 0 = حتى 31 كغ (حتى 70 رطلاً)، 1 = 32 – 45 كغ (71 – 100 رطلاً)، 2 = 46 - 59 كغ (101 – 130 رطلاً)، 3 = 60 - 70 كغ (131 – 160 رطلاً)، 4 = 71 - 86 كغ (161 – 190 رطلاً)، 5 = 87 - 100 كغ (191 – 220 رطلاً)، 6 = 101 - 113 كغ (221 – 250 رطلاً)، 7 = 114 - 127 كغ (251 – 280 رطلاً)، 8 = 128 – 145 كغ (281 – 320 رطلاً)، 9 = 146+ كغ (321+ رطلاً)، DL/ID، F1N

### setAddressStreet2() {#setaddressstreet2}

DAH، السطر الثاني من جزء الشارع في عنوان حامل البطاقة، DL/ID، V35ANS

### setAliasAKAFamilyName() {#setaliasakafamilyname}

DBN، الاسم العائلي الآخر المعروف به حامل البطاقة، DL/ID، V10ANS

### setAliasAKAGivenName() {#setaliasakagivenname}

DBG، الاسم الأول الآخر المعروف به حامل البطاقة، DL/ID، V15ANS

### setAliasAKASuffixName() {#setaliasakasuffixname}

DBS، اللواحق الأخرى المعروفة بها حامل البطاقة، DL/ID، V5ANS

### setAuditInformation() {#setauditinformation}

DCJ، سلسلة من الأحرف و/أو الأرقام تحدد متى وأين ومن قام بصنع رخصة القيادة/بطاقة الهوية. إذا لم تُستخدم معلومات التدقيق على البطاقة أو MRT، يجب تضمينها في سجل السائق، DL/ID، V25ANS

### setCardRevisionDate() {#setcardrevisiondate}

DDB، حقل مطلوب من DHS يشير إلى تاريخ أحدث تغيير في الإصدار أو تعديل لتنسيق DL/ID المرئي. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N

### setComplianceType() {#setcompliancetype}

DDA، حقل مطلوب من DHS يشير إلى الامتثال: “F” = متوافق؛ و “N” = غير متوافق، DL/ID، F1A

### setEndorsementCodeDescription() {#setendorsementcodedescription}

DCQ، نص يشرح الرموز الخاصة بالولاية التي تشير إلى امتيازات قيادة إضافية ممنوحة لحامل البطاقة بما يتجاوز فئة المركبة، DL، V50ANS

### setHairColor() {#sethaircolor}

DAZ، أصلع، أسود، أشقر، بني، رمادي، أحمر/كستنائي، رملي، أبيض، غير معروف. إذا رغبت الولاية المصدرة في اختصار الألوان، يجب استخدام الرموز المكوّنة من ثلاثة أحرف الواردة في AAMVA D20، DL/ID، V12A

### setInventoryControlNumber() {#setinventorycontrolnumber}

DCK، سلسلة من الأحرف و/أو الأرقام تُلصق بالمواد الخام (ورق البطاقات، اللصق، إلخ) المستخدمة في إنتاج رخص القيادة وبطاقات الهوية. (حقل موصى به من DHS)، DL/ID، V25ANS

### setLimitedDurationDocIndicator() {#setlimiteddurationdocindicator}

DDD، حقل مطلوب من DHS يشير إلى أن حامل البطاقة لديه وضع قانوني مؤقت = “1”، DL/ID، F1N

### setNameSuffix() {#setnamesuffix}

DCU، لاحقة الاسم (إذا شاركت الولاية في أنظمة تتطلب لاحقة الاسم (PDPS، CDLIS، إلخ)، يجب جمع اللاحقة وعرضها على DL/ID وفي MRT). JR (Junior)، SR (Senior)، 1ST أو I (First)، حتى 9TH أو IX (Ninth)، DL/ID، V5ANS

### setOrganDonorIndicator() {#setorgandonorindicator}

DDK، حقل يشير إلى أن حامل البطاقة متبرع بأعضاء = “1”، DL/ID، F1N

### setPlaceOfBirth() {#setplaceofbirth}

DCI، الدولة والبلدية و/أو الولاية/المقاطعة، DL/ID، V33A

### setRaceEthnicity() {#setraceethnicity}

DCL، رموز للعرق أو الإثنية لحامل البطاقة، كما هو معرف في AAMVA D20، DL/ID، V3A

### setRestrictionCodeDescription() {#setrestrictioncodedescription}

DCR، نص يصف رموز القيود الخاصة بالولاية التي تقيد امتيازات القيادة، DL، V50ANS

### setStandardEndorsementCode() {#setstandardendorsementcode}

DCN، رموز الاعتماد القياسية لحامل البطاقة. راجع الرموز في D20. هذا العنصر البيانات هو عنصر نائب لجهود مستقبلية لتوحيد رموز الاعتماد، DL، F5AN

### setStandardRestrictionCode() {#setstandardrestrictioncode}

DCO، رموز القيود القياسية لحامل البطاقة. راجع الرموز في D20. هذا العنصر البيانات هو عنصر نائب لجهود مستقبلية لتوحيد رموز القيود، DL، F12AN

### setStandardVehClassification() {#setstandardvehclassification}

DCM، رموز تصنيف المركبة القياسية لحامل البطاقة. هذا العنصر البيانات هو عنصر نائب لجهود مستقبلية لتوحيد تصنيفات المركبات، DL، F4AN

### setUnder18Until() {#setunder18until}

DDI، التاريخ الذي يصبح فيه حامل البطاقة في التاسعة عشرة من عمره. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N

### setUnder19Until() {#setunder19until}

DDI، التاريخ الذي يصبح فيه حامل البطاقة في التاسعة عشرة من عمره. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N

### setUnder21Until() {#setunder21until}

DDJ، التاريخ الذي يصبح فيه حامل البطاقة في الحادية والعشرين من عمره. (MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا)، DL/ID، F8N

### setVehClassDescription() {#setvehclassdescription}

DCP، نص يشرح الرموز الخاصة بالولاية لتصنيفات المركبات التي يُسمح لحامل البطاقة بقيادتها، DL، V50ANS

### setVeteranIndicator() {#setveteranindicator}

DDL، حقل يشير إلى أن حامل البطاقة هو محارب قديم = “1”، DL/ID، F1N

### setWeightKilograms() {#setweightkilograms}

DAX، وزن حامل البطاقة بالكيلوغرام، مثال: 84 كغ = “084”، DL/ID، F3N

### setWeightPounds() {#setweightpounds}

DAW، وزن حامل البطاقة بالرطل، مثال: 185 رطل = “185”، DL/ID، F3N

### setWeightRange() {#setweightrange}

DCE، يحدد النطاق التقريبي لوزن حامل البطاقة: 0 = حتى 31 كغ (حتى 70 رطلاً)، 1 = 32 – 45 كغ (71 – 100 رطلاً)، 2 = 46 - 59 كغ (101 – 130 رطلاً)، 3 = 60 - 70 كغ (131 – 160 رطلاً)، 4 = 71 - 86 كغ (161 – 190 رطلاً)، 5 = 87 - 100 كغ (191 – 220 رطلاً)، 6 = 101 - 113 كغ (221 – 250 رطلاً)، 7 = 114 - 127 كغ (251 – 280 رطلاً)، 8 = 128 – 145 كغ (281 – 320 رطلاً)، 9 = 146+ كغ (321+ رطلاً)، DL/ID، F1N
