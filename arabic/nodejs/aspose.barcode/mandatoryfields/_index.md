---
title: "MandatoryFields"
linktitle: "MandatoryFields"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "العناصر الإلزامية (الحقول) للبطاقة"
type: docs
weight: 590
url: /ar/nodejs/aspose.barcode/mandatoryfields/
---

## MandatoryFields class

العناصر الإلزامية (الحقول) للبطاقة

```js
new MandatoryFields()
```

## طرق

| اسم | الوصف |
| --- | --- |
| [getAddressCity()](#getaddresscity) | DAI، الجزء المتعلق بالمدينة من عنوان حامل البطاقة، DL/ID، V20ANS |
| [getAddressPostalCode()](#getaddresspostalcode) | DAK، الجزء المتعلق بالرمز البريدي من عنوان حامل البطاقة في الولايات المتحدة وكندا. إذا كان الجزء اللاحق من الرمز البريدي في |
| [getAddressState()](#getaddressstate) | DAJ، الجزء المتعلق بالولاية من عنوان حامل البطاقة، DL/ID، F2A |
| [getAddressStreet1()](#getaddressstreet1) | DAG، الجزء المتعلق بالشارع من عنوان حامل البطاقة، DL/ID، V35ANS |
| [getCountryIdentification()](#getcountryidentification) | DCG، الدولة التي يُصدر فيها DL/ID. الولايات المتحدة = USA، كندا = CAN، DL/ID، F3A |
| [getCustomerIDNumber()](#getcustomeridnumber) | DAQ، الرقم الذي تُعيّنه أو تُحسبه الجهة المُصدرة، DL/ID، V25ANS |
| [getDateOfBirth()](#getdateofbirth) | DBB، تاريخ إصدار المستند، MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا، DL/ID، F8N |
| [getDocumentDiscriminator()](#getdocumentdiscriminator) | DCF، يجب أن يحدد الرقم المستند المحدد الصادر لهذا العميل بشكل فريد عن غيره من المستندات التي قد تم إصدارها i |
| [getEndorsementCodes()](#getendorsementcodes) | DCD، رموز التأييد الخاصة بالاختصاص القضائي، DL، V5ANS |
| [getEyeColor()](#geteyecolor) | DAY، لون عيون حامل البطاقة. (رموز ANSI D-20). DL/ID، F3A |
| [getFamilyName()](#getfamilyname) | DCS، اسم عائلة حامل البطاقة، DL/ID، V40ANS |
| [getFamilyNameTruncation()](#getfamilynametruncation) | DDE، رمز يُظهر ما إذا كان الحقل قد تم تقصيره (T)، أو لم يُقصر (N)، أو غير معروف ما إذا تم تقصيره |
| [getFirstName()](#getfirstname) | DAC، الاسم الأول لحامل البطاقة، DL/ID، V40ANS |
| [getFirstNameTruncation()](#getfirstnametruncation) | DDF، رمز يُظهر ما إذا كان الحقل قد تم تقصيره (T)، أو لم يُقصر (N)، أو غير معروف ما إذا تم تقصيره |
| [getHeight()](#getheight) | DAU، ارتفاع حامل البطاقة. البوصات (in): عدد البوصات متبوعًا بـ \" in\" مثال 6'1'' = \"073 in\" السنتيمترات (cm): عدد |
| [getMiddleName()](#getmiddlename) | DAD، الاسم (الأسماء) الأوسط لحامل البطاقة. في حالة وجود عدة أسماء وسطى يجب فصلها بفاصلة \",\". ، DL |
| [getMiddleNameTruncation()](#getmiddlenametruncation) | DDG، رمز يُظهر ما إذا كان الحقل قد تم تقصيره (T)، أو لم يُقصر (N)، أو غير معروف ما إذا تم تقصيره |
| [getRestrictionCodes()](#getrestrictioncodes) | DCB، رموز القيود الخاصة بالاختصاص القضائي، DL، V12ANS |
| [getSex()](#getsex) | DBC، جنس حامل البطاقة. 1 = ذكر، 2 = أنثى، 9 = غير محدد، DL/ID، F1N |
| [getVehicleClass()](#getvehicleclass) | DCA، رمز فئة/مجموعة المركبة الخاص بالاختصاص القضائي، DL، V6ANS |
| [setAddressCity()](#setaddresscity) | DAI، الجزء المتعلق بالمدينة من عنوان حامل البطاقة، DL/ID، V20ANS |
| [setAddressPostalCode()](#setaddresspostalcode) | DAK، الجزء المتعلق بالرمز البريدي من عنوان حامل البطاقة في الولايات المتحدة وكندا. إذا كان الجزء اللاحق من الرمز البريدي في |
| [setAddressState()](#setaddressstate) | DAJ، الجزء المتعلق بالولاية من عنوان حامل البطاقة، DL/ID، F2A |
| [setAddressStreet1()](#setaddressstreet1) | DAG، الجزء المتعلق بالشارع من عنوان حامل البطاقة، DL/ID، V35ANS |
| [setCountryIdentification()](#setcountryidentification) | DCG، الدولة التي يُصدر فيها DL/ID. الولايات المتحدة = USA، كندا = CAN، DL/ID، F3A |
| [setCustomerIDNumber()](#setcustomeridnumber) | DAQ، الرقم الذي تُعيّنه أو تُحسبه الجهة المُصدرة، DL/ID، V25ANS |
| [setDateOfBirth()](#setdateofbirth) | DBB، تاريخ إصدار المستند، MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا، DL/ID، F8N |
| [setDocumentDiscriminator()](#setdocumentdiscriminator) | DCF، يجب أن يحدد الرقم المستند المحدد الصادر لهذا العميل بشكل فريد عن غيره من المستندات التي قد تم إصدارها i |
| [setEndorsementCodes()](#setendorsementcodes) | DCD، رموز التأييد الخاصة بالاختصاص القضائي، DL، V5ANS |
| [setEyeColor()](#seteyecolor) | DAY، لون عيون حامل البطاقة. (رموز ANSI D-20). DL/ID، F3A |
| [setFamilyName()](#setfamilyname) | DCS، اسم عائلة حامل البطاقة، DL/ID، V40ANS |
| [setFamilyNameTruncation()](#setfamilynametruncation) | DDE، رمز يُظهر ما إذا كان الحقل قد تم تقصيره (T)، أو لم يُقصر (N)، أو غير معروف ما إذا تم تقصيره |
| [setFirstName()](#setfirstname) | DAC، الاسم الأول لحامل البطاقة، DL/ID، V40ANS |
| [setFirstNameTruncation()](#setfirstnametruncation) | DDF، رمز يُظهر ما إذا كان الحقل قد تم تقصيره (T)، أو لم يُقصر (N)، أو غير معروف ما إذا تم تقصيره |
| [setHeight()](#setheight) | DAU، ارتفاع حامل البطاقة. البوصات (in): عدد البوصات متبوعًا بـ \" in\" مثال 6'1'' = \"073 in\" السنتيمترات (cm): عدد |
| [setMiddleName()](#setmiddlename) | DAD، الاسم (الأسماء) الأوسط لحامل البطاقة. في حالة وجود عدة أسماء وسطى يجب فصلها بفاصلة \",\". ، DL |
| [setMiddleNameTruncation()](#setmiddlenametruncation) | DDG، رمز يُظهر ما إذا كان الحقل قد تم تقصيره (T)، أو لم يُقصر (N)، أو غير معروف ما إذا تم تقصيره |
| [setRestrictionCodes()](#setrestrictioncodes) | DCB، رموز القيود الخاصة بالاختصاص القضائي، DL، V12ANS |
| [setSex()](#setsex) | DBC، جنس حامل البطاقة. 1 = ذكر، 2 = أنثى، 9 = غير محدد، DL/ID، F1N |
| [setVehicleClass()](#setvehicleclass) | DCA، رمز فئة/مجموعة المركبة الخاص بالاختصاص القضائي، DL، V6ANS |

### getAddressCity() {#getaddresscity}

DAI، الجزء المتعلق بالمدينة من عنوان حامل البطاقة، DL/ID، V20ANS

### getAddressPostalCode() {#getaddresspostalcode}

DAK، الجزء الخاص بالرمز البريدي من عنوان حامل البطاقة في الولايات المتحدة وكندا. إذا كان الجزء الأخير من الرمز البريدي في الولايات المتحدة غير معروف، سيتم استخدام الأصفار لملء الجزء الأخير من الأرقام حتى 9 أرقام، DL/ID، F11ANS

### getAddressState() {#getaddressstate}

DAJ، الجزء المتعلق بالولاية من عنوان حامل البطاقة، DL/ID، F2A

### getAddressStreet1() {#getaddressstreet1}

DAG، الجزء المتعلق بالشارع من عنوان حامل البطاقة، DL/ID، V35ANS

### getCountryIdentification() {#getcountryidentification}

DCG، الدولة التي يُصدر فيها DL/ID. الولايات المتحدة = USA، كندا = CAN، DL/ID، F3A

### getCustomerIDNumber() {#getcustomeridnumber}

DAQ، الرقم الذي تُعيّنه أو تُحسبه الجهة المُصدرة، DL/ID، V25ANS

### getDateOfBirth() {#getdateofbirth}

DBB، تاريخ إصدار المستند، MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا، DL/ID، F8N

### getDocumentDiscriminator() {#getdocumentdiscriminator}

DCF، يجب أن يحدد الرقم المستند المحدد الصادر لهذا العميل بشكل فريد عن غيره من المستندات التي قد تم إصدارها في الماضي. قد يُستخدم هذا الرقم لأغراض متعددة مثل تمييز المستند، رقم معلومات التدقيق، و/أو التحكم في المخزون، DL/ID، V25ANS

### getEndorsementCodes() {#getendorsementcodes}

DCD، رموز التأييد الخاصة بالاختصاص القضائي، DL، V5ANS

### getEyeColor() {#geteyecolor}

DAY، لون عيون حامل البطاقة. (رموز ANSI D-20). DL/ID، F3A

### getFamilyName() {#getfamilyname}

DCS، اسم عائلة حامل البطاقة، DL/ID، V40ANS

### getFamilyNameTruncation() {#getfamilynametruncation}

DDE، رمز يُظهر ما إذا كان الحقل قد تم تقصيره (T)، أو لم يُقصر (N)، أو غير معروف ما إذا تم تقصيره (U)، DL/ID، F1A

### getFirstName() {#getfirstname}

DAC، الاسم الأول لحامل البطاقة، DL/ID، V40ANS

### getFirstNameTruncation() {#getfirstnametruncation}

DDF، رمز يُظهر ما إذا كان الحقل قد تم تقصيره (T)، أو لم يُقصر (N)، أو غير معروف ما إذا تم تقصيره (U)، DL/ID، F1A

### getHeight() {#getheight}

DAU، ارتفاع حامل البطاقة. البوصات (in): عدد البوصات متبوعًا بـ \" in\" مثال 6'1'' = \"073 in\" السنتيمترات (cm): عدد السنتيمترات متبوعًا بـ \" cm\" مثال 181 سنتيمتر = \"181 cm\" ، DL/ID، F6ANS

### getMiddleName() {#getmiddlename}

DAD، الاسم (الأسماء) الأوسط لحامل البطاقة. في حالة وجود عدة أسماء وسطى يجب فصلها بفاصلة \",\". ، DL/ID، V40ANS

### getMiddleNameTruncation() {#getmiddlenametruncation}

DDG، رمز يُظهر ما إذا كان الحقل قد تم تقصيره (T)، أو لم يُقصر (N)، أو غير معروف ما إذا تم تقصيره (U)، DL/ID، F1A

### getRestrictionCodes() {#getrestrictioncodes}

DCB، رموز القيود الخاصة بالاختصاص القضائي، DL، V12ANS

### getSex() {#getsex}

DBC، جنس حامل البطاقة. 1 = ذكر، 2 = أنثى، 9 = غير محدد، DL/ID، F1N

### getVehicleClass() {#getvehicleclass}

DCA، رمز فئة/مجموعة المركبة الخاص بالاختصاص القضائي، DL، V6ANS

### setAddressCity() {#setaddresscity}

DAI، الجزء المتعلق بالمدينة من عنوان حامل البطاقة، DL/ID، V20ANS

### setAddressPostalCode() {#setaddresspostalcode}

DAK، الجزء الخاص بالرمز البريدي من عنوان حامل البطاقة في الولايات المتحدة وكندا. إذا كان الجزء الأخير من الرمز البريدي في الولايات المتحدة غير معروف، سيتم استخدام الأصفار لملء الجزء الأخير من الأرقام حتى 9 أرقام، DL/ID، F11ANS

### setAddressState() {#setaddressstate}

DAJ، الجزء المتعلق بالولاية من عنوان حامل البطاقة، DL/ID، F2A

### setAddressStreet1() {#setaddressstreet1}

DAG، الجزء المتعلق بالشارع من عنوان حامل البطاقة، DL/ID، V35ANS

### setCountryIdentification() {#setcountryidentification}

DCG، الدولة التي يُصدر فيها DL/ID. الولايات المتحدة = USA، كندا = CAN، DL/ID، F3A

### setCustomerIDNumber() {#setcustomeridnumber}

DAQ، الرقم الذي تُعيّنه أو تُحسبه الجهة المُصدرة، DL/ID، V25ANS

### setDateOfBirth() {#setdateofbirth}

DBB، تاريخ إصدار المستند، MMDDCCYY للولايات المتحدة، CCYYMMDD لكندا، DL/ID، F8N

### setDocumentDiscriminator() {#setdocumentdiscriminator}

DCF، يجب أن يحدد الرقم المستند المحدد الصادر لهذا العميل بشكل فريد عن غيره من المستندات التي قد تم إصدارها في الماضي. قد يُستخدم هذا الرقم لأغراض متعددة مثل تمييز المستند، رقم معلومات التدقيق، و/أو التحكم في المخزون، DL/ID، V25ANS

### setEndorsementCodes() {#setendorsementcodes}

DCD، رموز التأييد الخاصة بالاختصاص القضائي، DL، V5ANS

### setEyeColor() {#seteyecolor}

DAY، لون عيون حامل البطاقة. (رموز ANSI D-20). DL/ID، F3A

### setFamilyName() {#setfamilyname}

DCS، اسم عائلة حامل البطاقة، DL/ID، V40ANS

### setFamilyNameTruncation() {#setfamilynametruncation}

DDE، رمز يُظهر ما إذا كان الحقل قد تم تقصيره (T)، أو لم يُقصر (N)، أو غير معروف ما إذا تم تقصيره (U)، DL/ID، F1A

### setFirstName() {#setfirstname}

DAC، الاسم الأول لحامل البطاقة، DL/ID، V40ANS

### setFirstNameTruncation() {#setfirstnametruncation}

DDF، رمز يُظهر ما إذا كان الحقل قد تم تقصيره (T)، أو لم يُقصر (N)، أو غير معروف ما إذا تم تقصيره (U)، DL/ID، F1A

### setHeight() {#setheight}

DAU، ارتفاع حامل البطاقة. البوصات (in): عدد البوصات متبوعًا بـ \" in\" مثال 6'1'' = \"073 in\" السنتيمترات (cm): عدد السنتيمترات متبوعًا بـ \" cm\" مثال 181 سنتيمتر = \"181 cm\" ، DL/ID، F6ANS

### setMiddleName() {#setmiddlename}

DAD، الاسم (الأسماء) الأوسط لحامل البطاقة. في حالة وجود عدة أسماء وسطى يجب فصلها بفاصلة \",\". ، DL/ID، V40ANS

### setMiddleNameTruncation() {#setmiddlenametruncation}

DDG، رمز يُظهر ما إذا كان الحقل قد تم تقصيره (T)، أو لم يُقصر (N)، أو غير معروف ما إذا تم تقصيره (U)، DL/ID، F1A

### setRestrictionCodes() {#setrestrictioncodes}

DCB، رموز القيود الخاصة بالاختصاص القضائي، DL، V12ANS

### setSex() {#setsex}

DBC، جنس حامل البطاقة. 1 = ذكر، 2 = أنثى، 9 = غير محدد، DL/ID، F1N

### setVehicleClass() {#setvehicleclass}

DCA، رمز فئة/مجموعة المركبة الخاص بالاختصاص القضائي، DL، V6ANS
