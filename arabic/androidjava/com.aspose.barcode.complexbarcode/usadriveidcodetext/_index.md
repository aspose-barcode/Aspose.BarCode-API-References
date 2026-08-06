---
title: USADriveIdCodetext
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: فئة لتشفير وفك تشفير النص المضمن في رمز USA Driving License PDF417.
type: docs
weight: 38
url: /ar/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class USADriveIdCodetext implements IComplexCodetext
```

فئة لتشفير وفك تشفير النص المضمن في رمز USA Driving License PDF417.
## Constructors

| Constructor | الوصف |
| --- | --- |
| [USADriveIdCodetext()](#USADriveIdCodetext--) | المُنشئ الافتراضي |
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAAMVAVersionNumber()](#getAAMVAVersionNumber--) | رقم إصدار AAMVA 00-99 |
| [getBarcodeType()](#getBarcodeType--) | يعيد نوع الباركود لبطاقة تعريف USA (Pdf417) |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | إنشاء نص الترميز من بيانات USA DL |
| [getIssuerIdentificationNumber()](#getIssuerIdentificationNumber--) | هذا الرقم يحدد الاختصاص الصادر بشكل فريد ويمكن الحصول عليه عن طريق التواصل مع سلطة الإصدار ISO (AAMVA). |
| [getJurisdictionSpecificSubfile()](#getJurisdictionSpecificSubfile--) | حقول الاختصاص القضائي المحددة |
| [getJurisdictionVersionNumber()](#getJurisdictionVersionNumber--) | رقم إصدار الاختصاص القضائي 00-99 |
| [getMandatoryElements()](#getMandatoryElements--) | العناصر (الحقول) الإلزامية للبطاقة |
| [getNumberOfEntries()](#getNumberOfEntries--) | عدد 00-99 من الملفات الفرعية |
| [getOptionalElements()](#getOptionalElements--) | العناصر الاختيارية (الحقول) للبطاقة |
| [getSubfileDesignator()](#getSubfileDesignator--) | يحتوي على معلومات حول الملفات الفرعية التالية، الأنواع، الإزاحات والطول. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | تهيئة كائن USA DL من نص الترميز |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveToXml(OutputStream stream)](#saveToXml-java.io.OutputStream-) | يحفظ إلى XML |
| [setAAMVAVersionNumber(String value)](#setAAMVAVersionNumber-java.lang.String-) | رقم إصدار AAMVA 00-99 |
| [setIssuerIdentificationNumber(String value)](#setIssuerIdentificationNumber-java.lang.String-) | هذا الرقم يحدد الاختصاص الصادر بشكل فريد ويمكن الحصول عليه عن طريق التواصل مع سلطة الإصدار ISO (AAMVA). |
| [setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value)](#setJurisdictionSpecificSubfile-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile-) | حقول الاختصاص القضائي المحددة |
| [setJurisdictionVersionNumber(String value)](#setJurisdictionVersionNumber-java.lang.String-) | رقم إصدار الاختصاص القضائي 00-99 |
| [setMandatoryElements(USADriveIdCodetext.MandatoryFields value)](#setMandatoryElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields-) | العناصر (الحقول) الإلزامية للبطاقة |
| [setNumberOfEntries(int value)](#setNumberOfEntries-int-) | عدد 00-99 من الملفات الفرعية |
| [setOptionalElements(USADriveIdCodetext.OptionalFields value)](#setOptionalElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields-) | العناصر الاختيارية (الحقول) للبطاقة |
| [setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value)](#setSubfileDesignator-java.util.List-com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties--) | يحتوي على معلومات حول الملفات الفرعية التالية، الأنواع، الإزاحات والطول. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### USADriveIdCodetext() {#USADriveIdCodetext--}
```
public USADriveIdCodetext()
```


المُنشئ الافتراضي

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
### getAAMVAVersionNumber() {#getAAMVAVersionNumber--}
```
public final String getAAMVAVersionNumber()
```


رقم إصدار AAMVA 00-99

**Returns:**
java.lang.String
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


يعيد نوع الباركود لبطاقة تعريف USA (Pdf417)

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type (Pdf417)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public final String getConstructedCodetext()
```


إنشاء نص الترميز من بيانات USA DL

**Returns:**
java.lang.String - نص الرمز المُنشأ
### getIssuerIdentificationNumber() {#getIssuerIdentificationNumber--}
```
public final String getIssuerIdentificationNumber()
```


هذا الرقم يحدد الاختصاص الصادر بشكل فريد ويمكن الحصول عليه عن طريق التواصل مع سلطة الإصدار ISO (AAMVA). يجب ترميز الرقم الكامل المكوّن من 6 أرقام IIN.

**Returns:**
java.lang.String
### getJurisdictionSpecificSubfile() {#getJurisdictionSpecificSubfile--}
```
public final USADriveIdJurisdSubfile getJurisdictionSpecificSubfile()
```


حقول الاختصاص القضائي المحددة

**Returns:**
[USADriveIdJurisdSubfile](../../com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile)
### getJurisdictionVersionNumber() {#getJurisdictionVersionNumber--}
```
public final String getJurisdictionVersionNumber()
```


رقم إصدار الاختصاص القضائي 00-99

**Returns:**
java.lang.String
### getMandatoryElements() {#getMandatoryElements--}
```
public final USADriveIdCodetext.MandatoryFields getMandatoryElements()
```


العناصر (الحقول) الإلزامية للبطاقة

**Returns:**
com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields
### getNumberOfEntries() {#getNumberOfEntries--}
```
public final int getNumberOfEntries()
```


عدد 00-99 من الملفات الفرعية

**Returns:**
int
### getOptionalElements() {#getOptionalElements--}
```
public final USADriveIdCodetext.OptionalFields getOptionalElements()
```


العناصر الاختيارية (الحقول) للبطاقة

**Returns:**
com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields
### getSubfileDesignator() {#getSubfileDesignator--}
```
public final List<USADriveIdCodetext.SubfileProperties> getSubfileDesignator()
```


يحتوي على معلومات حول الملفات الفرعية التالية، الأنواع، الإزاحات والطول. مهم: قم بتعيين النوع فقط، سيتم ضبط الإزاحة والطول تلقائيًا.

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public final void initFromString(String constructedCodetext)
```


تهيئة كائن USA DL من نص الترميز

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| constructedCodetext | java.lang.String | نص الكود المُنشأ |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### saveToXml(OutputStream stream) {#saveToXml-java.io.OutputStream-}
```
public final void saveToXml(OutputStream stream)
```


يحفظ إلى XML

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| تدفق | java.io.OutputStream | دفق للحفظ |

### setAAMVAVersionNumber(String value) {#setAAMVAVersionNumber-java.lang.String-}
```
public final void setAAMVAVersionNumber(String value)
```


رقم إصدار AAMVA 00-99

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setIssuerIdentificationNumber(String value) {#setIssuerIdentificationNumber-java.lang.String-}
```
public final void setIssuerIdentificationNumber(String value)
```


هذا الرقم يحدد الاختصاص الصادر بشكل فريد ويمكن الحصول عليه عن طريق التواصل مع سلطة الإصدار ISO (AAMVA). يجب ترميز الرقم الكامل المكوّن من 6 أرقام IIN.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value) {#setJurisdictionSpecificSubfile-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile-}
```
public final void setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value)
```


حقول الاختصاص القضائي المحددة

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [USADriveIdJurisdSubfile](../../com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile) |  |

### setJurisdictionVersionNumber(String value) {#setJurisdictionVersionNumber-java.lang.String-}
```
public final void setJurisdictionVersionNumber(String value)
```


رقم إصدار الاختصاص القضائي 00-99

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setMandatoryElements(USADriveIdCodetext.MandatoryFields value) {#setMandatoryElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields-}
```
public final void setMandatoryElements(USADriveIdCodetext.MandatoryFields value)
```


العناصر (الحقول) الإلزامية للبطاقة

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields |  |

### setNumberOfEntries(int value) {#setNumberOfEntries-int-}
```
public final void setNumberOfEntries(int value)
```


عدد 00-99 من الملفات الفرعية

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setOptionalElements(USADriveIdCodetext.OptionalFields value) {#setOptionalElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields-}
```
public final void setOptionalElements(USADriveIdCodetext.OptionalFields value)
```


العناصر الاختيارية (الحقول) للبطاقة

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields |  |

### setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value) {#setSubfileDesignator-java.util.List-com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties--}
```
public final void setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value)
```


يحتوي على معلومات حول الملفات الفرعية التالية، الأنواع، الإزاحات والطول. مهم: قم بتعيين النوع فقط، سيتم ضبط الإزاحة والطول تلقائيًا.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.util.List<com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties> |  |

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

