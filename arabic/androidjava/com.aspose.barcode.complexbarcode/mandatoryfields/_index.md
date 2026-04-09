---
title: USADriveIdCodetext.MandatoryFields
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: الحقول الإلزامية لعناصر البطاقة
type: docs
weight: 10
url: /ar/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.MandatoryFields
```

العناصر (الحقول) الإلزامية للبطاقة
## Constructors

| Constructor | الوصف |
| --- | --- |
| [MandatoryFields()](#MandatoryFields--) |  |
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressCity()](#getAddressCity--) | DAI, جزء المدينة من عنوان حامل البطاقة, DL/ID, V20ANS |
| [getAddressPostalCode()](#getAddressPostalCode--) | DAK, جزء الرمز البريدي من عنوان حامل البطاقة في الولايات المتحدة وكندا. |
| [getAddressState()](#getAddressState--) | DAJ, جزء الولاية من عنوان حامل البطاقة, DL/ID, F2A |
| [getAddressStreet1()](#getAddressStreet1--) | DAG, جزء الشارع من عنوان حامل البطاقة, DL/ID, V35ANS |
| [getClass()](#getClass--) |  |
| [getCountryIdentification()](#getCountryIdentification--) | DCG, الدولة التي صُدرت فيها رخصة القيادة/الهوية. |
| [getCustomerIDNumber()](#getCustomerIDNumber--) | DAQ, الرقم المخصص أو المحسوب من قبل السلطة المصدرة, DL/ID, V25ANS |
| [getDateOfBirth()](#getDateOfBirth--) | DBB, التاريخ الذي صدر فيه المستند, MMDDCCYY للولايات المتحدة, CCYYMMDD لكندا, DL/ID, F8N |
| [getDocumentDiscriminator()](#getDocumentDiscriminator--) | DCF, يجب أن يحدد الرقم بشكل فريد مستندًا معينًا صُدر لهذا العميل مقارنةً بالآخرين الذين قد صُدروا في الماضي. |
| [getEndorsementCodes()](#getEndorsementCodes--) | DCD, رموز التأييد الخاصة بالاختصاص القضائي, DL, V5ANS |
| [getEyeColor()](#getEyeColor--) | DAY, لون عيون حامل البطاقة. |
| [getFamilyName()](#getFamilyName--) | DCS, اسم العائلة لحامل البطاقة, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getFamilyNameTruncation--) | DDE, رمز يشير إلى ما إذا كان الحقل مقصوصًا (T)، غير مقصوص (N)، أو غير معروف ما إذا كان مقصوصًا (U), DL/ID, F1A |
| [getFirstName()](#getFirstName--) | DAC, الاسم الأول لحامل البطاقة, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getFirstNameTruncation--) | DDF, رمز يشير إلى ما إذا كان الحقل مقصوصًا (T)، غير مقصوص (N)، أو غير معروف ما إذا كان مقصوصًا (U), DL/ID, F1A |
| [getHeight()](#getHeight--) | DAU, ارتفاع حامل البطاقة. |
| [getMiddleName()](#getMiddleName--) | DAD, الاسم (الأسماء) الأوسط لحامل البطاقة. |
| [getMiddleNameTruncation()](#getMiddleNameTruncation--) | DDG, رمز يشير إلى ما إذا كان الحقل مقصوصًا (T)، غير مقصوص (N)، أو غير معروف ما إذا كان مقصوصًا (U), DL/ID, F1A |
| [getRestrictionCodes()](#getRestrictionCodes--) | DCB, رموز القيود الخاصة بالاختصاص القضائي, DL, V12ANS |
| [getSex()](#getSex--) | DBC, جنس حامل البطاقة. |
| [getVehicleClass()](#getVehicleClass--) | DCA, رمز فئة/مجموعة المركبة الخاص بالاختصاص القضائي, DL, V6ANS |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressCity(String value)](#setAddressCity-java.lang.String-) | DAI, جزء المدينة من عنوان حامل البطاقة, DL/ID, V20ANS |
| [setAddressPostalCode(String value)](#setAddressPostalCode-java.lang.String-) | DAK, جزء الرمز البريدي من عنوان حامل البطاقة في الولايات المتحدة وكندا. |
| [setAddressState(String value)](#setAddressState-java.lang.String-) | DAJ, جزء الولاية من عنوان حامل البطاقة, DL/ID, F2A |
| [setAddressStreet1(String value)](#setAddressStreet1-java.lang.String-) | DAG, جزء الشارع من عنوان حامل البطاقة, DL/ID, V35ANS |
| [setCountryIdentification(USADriveIdCountry value)](#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-) | DCG, الدولة التي صُدرت فيها رخصة القيادة/الهوية. |
| [setCustomerIDNumber(String value)](#setCustomerIDNumber-java.lang.String-) | DAQ, الرقم المخصص أو المحسوب من قبل السلطة المصدرة, DL/ID, V25ANS |
| [setDateOfBirth(LocalDate value)](#setDateOfBirth-java.time.LocalDate-) | DBB, التاريخ الذي صدر فيه المستند, MMDDCCYY للولايات المتحدة, CCYYMMDD لكندا, DL/ID, F8N |
| [setDocumentDiscriminator(String value)](#setDocumentDiscriminator-java.lang.String-) | DCF, يجب أن يحدد الرقم بشكل فريد مستندًا معينًا صُدر لهذا العميل مقارنةً بالآخرين الذين قد صُدروا في الماضي. |
| [setEndorsementCodes(String value)](#setEndorsementCodes-java.lang.String-) | DCD, رموز التأييد الخاصة بالاختصاص القضائي, DL, V5ANS |
| [setEyeColor(USADriveIdEyeColor value)](#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-) | DAY, لون عيون حامل البطاقة. |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | DCS, اسم العائلة لحامل البطاقة, DL/ID, V40ANS |
| [setFamilyNameTruncation(String value)](#setFamilyNameTruncation-java.lang.String-) | DDE, رمز يشير إلى ما إذا كان الحقل مقصوصًا (T)، غير مقصوص (N)، أو غير معروف ما إذا كان مقصوصًا (U), DL/ID, F1A |
| [setFirstName(String value)](#setFirstName-java.lang.String-) | DAC, الاسم الأول لحامل البطاقة, DL/ID, V40ANS |
| [setFirstNameTruncation(String value)](#setFirstNameTruncation-java.lang.String-) | DDF, رمز يشير إلى ما إذا كان الحقل مقصوصًا (T)، غير مقصوص (N)، أو غير معروف ما إذا كان مقصوصًا (U), DL/ID, F1A |
| [setHeight(String value)](#setHeight-java.lang.String-) | DAU, ارتفاع حامل البطاقة. |
| [setMiddleName(String value)](#setMiddleName-java.lang.String-) | DAD, الاسم (الأسماء) الأوسط لحامل البطاقة. |
| [setMiddleNameTruncation(String value)](#setMiddleNameTruncation-java.lang.String-) | DDG, رمز يشير إلى ما إذا كان الحقل مقصوصًا (T)، غير مقصوص (N)، أو غير معروف ما إذا كان مقصوصًا (U), DL/ID, F1A |
| [setRestrictionCodes(String value)](#setRestrictionCodes-java.lang.String-) | DCB, رموز القيود الخاصة بالاختصاص القضائي, DL, V12ANS |
| [setSex(USADriveIdSex value)](#setSex-com.aspose.barcode.complexbarcode.USADriveIdSex-) | DBC, جنس حامل البطاقة. |
| [setVehicleClass(String value)](#setVehicleClass-java.lang.String-) | DCA, رمز فئة/مجموعة المركبة الخاص بالاختصاص القضائي, DL, V6ANS |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MandatoryFields() {#MandatoryFields--}
```
public MandatoryFields()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAddressCity() {#getAddressCity--}
```
public final String getAddressCity()
```


DAI, جزء المدينة من عنوان حامل البطاقة, DL/ID, V20ANS

**Returns:**
java.lang.String
### getAddressPostalCode() {#getAddressPostalCode--}
```
public final String getAddressPostalCode()
```


DAK, جزء الرمز البريدي من عنوان حامل البطاقة في الولايات المتحدة وكندا. إذا كان الجزء الأخير من الرمز البريدي في الولايات المتحدة غير معروف، سيتم استخدام الأصفار لملء الجزء الأخير من الأرقام حتى 9 أرقام, DL/ID, F11ANS

**Returns:**
java.lang.String
### getAddressState() {#getAddressState--}
```
public final String getAddressState()
```


DAJ, جزء الولاية من عنوان حامل البطاقة, DL/ID, F2A

**Returns:**
java.lang.String
### getAddressStreet1() {#getAddressStreet1--}
```
public final String getAddressStreet1()
```


DAG, جزء الشارع من عنوان حامل البطاقة, DL/ID, V35ANS

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCountryIdentification() {#getCountryIdentification--}
```
public final USADriveIdCountry getCountryIdentification()
```


DCG، الدولة التي يُصدر فيها رخصة القيادة/هوية. الولايات المتحدة = USA، كندا = CAN، رخصة القيادة/هوية، F3A

**Returns:**
[USADriveIdCountry](../../com.aspose.barcode.complexbarcode/usadriveidcountry)
### getCustomerIDNumber() {#getCustomerIDNumber--}
```
public final String getCustomerIDNumber()
```


DAQ, الرقم المخصص أو المحسوب من قبل السلطة المصدرة, DL/ID, V25ANS

**Returns:**
java.lang.String
### getDateOfBirth() {#getDateOfBirth--}
```
public final LocalDate getDateOfBirth()
```


DBB, التاريخ الذي صدر فيه المستند, MMDDCCYY للولايات المتحدة, CCYYMMDD لكندا, DL/ID, F8N

**Returns:**
java.time.LocalDate
### getDocumentDiscriminator() {#getDocumentDiscriminator--}
```
public final String getDocumentDiscriminator()
```


DCF، يجب أن يكون الرقم فريدًا لتحديد مستند معين صُدر لهذا العميل من غيره التي قد تكون صُدرت في الماضي. قد يُستخدم هذا الرقم لأغراض متعددة مثل تمييز المستند، رقم معلومات التدقيق، و/أو التحكم في المخزون، رخصة القيادة/هوية، V25ANS

**Returns:**
java.lang.String
### getEndorsementCodes() {#getEndorsementCodes--}
```
public final String getEndorsementCodes()
```


DCD, رموز التأييد الخاصة بالاختصاص القضائي, DL, V5ANS

**Returns:**
java.lang.String
### getEyeColor() {#getEyeColor--}
```
public final USADriveIdEyeColor getEyeColor()
```


DAY، لون عيون حامل البطاقة. (رموز ANSI D-20). رخصة القيادة/هوية، F3A

**Returns:**
[USADriveIdEyeColor](../../com.aspose.barcode.complexbarcode/usadriveideyecolor)
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


DCS, اسم العائلة لحامل البطاقة, DL/ID, V40ANS

**Returns:**
java.lang.String
### getFamilyNameTruncation() {#getFamilyNameTruncation--}
```
public final String getFamilyNameTruncation()
```


DDE, رمز يشير إلى ما إذا كان الحقل مقصوصًا (T)، غير مقصوص (N)، أو غير معروف ما إذا كان مقصوصًا (U), DL/ID, F1A

**Returns:**
java.lang.String
### getFirstName() {#getFirstName--}
```
public final String getFirstName()
```


DAC, الاسم الأول لحامل البطاقة, DL/ID, V40ANS

**Returns:**
java.lang.String
### getFirstNameTruncation() {#getFirstNameTruncation--}
```
public final String getFirstNameTruncation()
```


DDF, رمز يشير إلى ما إذا كان الحقل مقصوصًا (T)، غير مقصوص (N)، أو غير معروف ما إذا كان مقصوصًا (U), DL/ID, F1A

**Returns:**
java.lang.String
### getHeight() {#getHeight--}
```
public final String getHeight()
```


DAU، ارتفاع حامل البطاقة. بالبوصة (in): عدد البوصات متبوعًا بـ " in" مثال 6'1'' = "073 in" بالسنتيمتر (cm): عدد السنتيمترات متبوعًا بـ " cm" مثال 181 سنتيمتر = "181 cm" ، رخصة القيادة/هوية، F6ANS

**Returns:**
java.lang.String
### getMiddleName() {#getMiddleName--}
```
public final String getMiddleName()
```


DAD، الاسم الأوسط (الأسماء) لحامل البطاقة. في حالة وجود أسماء وسطى متعددة يجب فصلها بفاصلة ",". ، رخصة القيادة/هوية، V40ANS

**Returns:**
java.lang.String
### getMiddleNameTruncation() {#getMiddleNameTruncation--}
```
public final String getMiddleNameTruncation()
```


DDG, رمز يشير إلى ما إذا كان الحقل مقصوصًا (T)، غير مقصوص (N)، أو غير معروف ما إذا كان مقصوصًا (U), DL/ID, F1A

**Returns:**
java.lang.String
### getRestrictionCodes() {#getRestrictionCodes--}
```
public final String getRestrictionCodes()
```


DCB, رموز القيود الخاصة بالاختصاص القضائي, DL, V12ANS

**Returns:**
java.lang.String
### getSex() {#getSex--}
```
public final USADriveIdSex getSex()
```


DBC، جنس حامل البطاقة. 1 = ذكر، 2 = أنثى، 9 = غير محدد، رخصة القيادة/هوية، F1N

**Returns:**
[USADriveIdSex](../../com.aspose.barcode.complexbarcode/usadriveidsex)
### getVehicleClass() {#getVehicleClass--}
```
public final String getVehicleClass()
```


DCA, رمز فئة/مجموعة المركبة الخاص بالاختصاص القضائي, DL, V6ANS

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




### setAddressCity(String value) {#setAddressCity-java.lang.String-}
```
public final void setAddressCity(String value)
```


DAI, جزء المدينة من عنوان حامل البطاقة, DL/ID, V20ANS

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setAddressPostalCode(String value) {#setAddressPostalCode-java.lang.String-}
```
public final void setAddressPostalCode(String value)
```


DAK, جزء الرمز البريدي من عنوان حامل البطاقة في الولايات المتحدة وكندا. إذا كان الجزء الأخير من الرمز البريدي في الولايات المتحدة غير معروف، سيتم استخدام الأصفار لملء الجزء الأخير من الأرقام حتى 9 أرقام, DL/ID, F11ANS

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setAddressState(String value) {#setAddressState-java.lang.String-}
```
public final void setAddressState(String value)
```


DAJ, جزء الولاية من عنوان حامل البطاقة, DL/ID, F2A

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setAddressStreet1(String value) {#setAddressStreet1-java.lang.String-}
```
public final void setAddressStreet1(String value)
```


DAG, جزء الشارع من عنوان حامل البطاقة, DL/ID, V35ANS

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setCountryIdentification(USADriveIdCountry value) {#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-}
```
public final void setCountryIdentification(USADriveIdCountry value)
```


DCG، الدولة التي يُصدر فيها رخصة القيادة/هوية. الولايات المتحدة = USA، كندا = CAN، رخصة القيادة/هوية، F3A

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [USADriveIdCountry](../../com.aspose.barcode.complexbarcode/usadriveidcountry) |  |

### setCustomerIDNumber(String value) {#setCustomerIDNumber-java.lang.String-}
```
public final void setCustomerIDNumber(String value)
```


DAQ, الرقم المخصص أو المحسوب من قبل السلطة المصدرة, DL/ID, V25ANS

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setDateOfBirth(LocalDate value) {#setDateOfBirth-java.time.LocalDate-}
```
public final void setDateOfBirth(LocalDate value)
```


DBB, التاريخ الذي صدر فيه المستند, MMDDCCYY للولايات المتحدة, CCYYMMDD لكندا, DL/ID, F8N

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.time.LocalDate |  |

### setDocumentDiscriminator(String value) {#setDocumentDiscriminator-java.lang.String-}
```
public final void setDocumentDiscriminator(String value)
```


DCF، يجب أن يكون الرقم فريدًا لتحديد مستند معين صُدر لهذا العميل من غيره التي قد تكون صُدرت في الماضي. قد يُستخدم هذا الرقم لأغراض متعددة مثل تمييز المستند، رقم معلومات التدقيق، و/أو التحكم في المخزون، رخصة القيادة/هوية، V25ANS

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setEndorsementCodes(String value) {#setEndorsementCodes-java.lang.String-}
```
public final void setEndorsementCodes(String value)
```


DCD, رموز التأييد الخاصة بالاختصاص القضائي, DL, V5ANS

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setEyeColor(USADriveIdEyeColor value) {#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-}
```
public final void setEyeColor(USADriveIdEyeColor value)
```


DAY، لون عيون حامل البطاقة. (رموز ANSI D-20). رخصة القيادة/هوية، F3A

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [USADriveIdEyeColor](../../com.aspose.barcode.complexbarcode/usadriveideyecolor) |  |

### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public final void setFamilyName(String value)
```


DCS, اسم العائلة لحامل البطاقة, DL/ID, V40ANS

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setFamilyNameTruncation(String value) {#setFamilyNameTruncation-java.lang.String-}
```
public final void setFamilyNameTruncation(String value)
```


DDE, رمز يشير إلى ما إذا كان الحقل مقصوصًا (T)، غير مقصوص (N)، أو غير معروف ما إذا كان مقصوصًا (U), DL/ID, F1A

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setFirstName(String value) {#setFirstName-java.lang.String-}
```
public final void setFirstName(String value)
```


DAC, الاسم الأول لحامل البطاقة, DL/ID, V40ANS

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setFirstNameTruncation(String value) {#setFirstNameTruncation-java.lang.String-}
```
public final void setFirstNameTruncation(String value)
```


DDF, رمز يشير إلى ما إذا كان الحقل مقصوصًا (T)، غير مقصوص (N)، أو غير معروف ما إذا كان مقصوصًا (U), DL/ID, F1A

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setHeight(String value) {#setHeight-java.lang.String-}
```
public final void setHeight(String value)
```


DAU، ارتفاع حامل البطاقة. بالبوصة (in): عدد البوصات متبوعًا بـ " in" مثال 6'1'' = "073 in" بالسنتيمتر (cm): عدد السنتيمترات متبوعًا بـ " cm" مثال 181 سنتيمتر = "181 cm" ، رخصة القيادة/هوية، F6ANS

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setMiddleName(String value) {#setMiddleName-java.lang.String-}
```
public final void setMiddleName(String value)
```


DAD، الاسم الأوسط (الأسماء) لحامل البطاقة. في حالة وجود أسماء وسطى متعددة يجب فصلها بفاصلة ",". ، رخصة القيادة/هوية، V40ANS

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setMiddleNameTruncation(String value) {#setMiddleNameTruncation-java.lang.String-}
```
public final void setMiddleNameTruncation(String value)
```


DDG, رمز يشير إلى ما إذا كان الحقل مقصوصًا (T)، غير مقصوص (N)، أو غير معروف ما إذا كان مقصوصًا (U), DL/ID, F1A

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setRestrictionCodes(String value) {#setRestrictionCodes-java.lang.String-}
```
public final void setRestrictionCodes(String value)
```


DCB, رموز القيود الخاصة بالاختصاص القضائي, DL, V12ANS

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setSex(USADriveIdSex value) {#setSex-com.aspose.barcode.complexbarcode.USADriveIdSex-}
```
public final void setSex(USADriveIdSex value)
```


DBC، جنس حامل البطاقة. 1 = ذكر، 2 = أنثى، 9 = غير محدد، رخصة القيادة/هوية، F1N

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [USADriveIdSex](../../com.aspose.barcode.complexbarcode/usadriveidsex) |  |

### setVehicleClass(String value) {#setVehicleClass-java.lang.String-}
```
public final void setVehicleClass(String value)
```


DCA, رمز فئة/مجموعة المركبة الخاص بالاختصاص القضائي, DL, V6ANS

**Parameters:**
| Parameter | Type | الوصف |
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
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

