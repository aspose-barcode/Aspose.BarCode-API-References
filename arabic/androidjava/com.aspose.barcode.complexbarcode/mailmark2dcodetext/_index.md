---
title: Mailmark2DCodetext
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: فئة لتشفير وفك تشفير النص المضمن في رمز Royal Mail 2D Mailmark.
type: docs
weight: 23
url: /ar/androidjava/com.aspose.barcode.complexbarcode/mailmark2dcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class Mailmark2DCodetext implements IComplexCodetext
```

فئة لتشفير وفك تشفير النص المضمن في رمز Royal Mail 2D Mailmark.
## Constructors

| Constructor | الوصف |
| --- | --- |
| [Mailmark2DCodetext()](#Mailmark2DCodetext--) | Create default instance of Mailmark2DCodetext class. |
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | يحصل على نوع الباركود. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construct codetext from Mailmark data. |
| [getCustomerContent()](#getCustomerContent--) | Optional space for use by customer. |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getDataMatrixType()](#getDataMatrixType--) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. |
| [getInformationTypeID()](#getInformationTypeID--) | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [getItemID()](#getItemID--) | Identifies the unique item within the Supply Chain ID. |
| [getRTSFlag()](#getRTSFlag--) | العلم الذي يشير إلى مستوى خدمة الإرجاع إلى المرسل المطلوب. |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | يحتوي على رمز البريد للإرجاع إلى المرسل ولكن بدون DPS. |
| [getSupplyChainID()](#getSupplyChainID--) | يحدد مجموعة العملاء الفريدة المشاركة في الإرسال. |
| [getUPUCountryID()](#getUPUCountryID--) | يحدد معرف الدولة UPU. الحد الأقصى للطول: 4 أحرف. |
| [getVersionID()](#getVersionID--) | يحدد إصدار الباركود المتعلق بكل معرف نوع المعلومات. |
| [getclass()](#getclass--) | يحدد فئة العنصر. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initializes Mailmark data from constructed codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Optional space for use by customer. |
| [setCustomerContentEncodeMode(DataMatrixEncodeMode value)](#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setDataMatrixType(Mailmark2DType value)](#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [setItemID(int value)](#setItemID-int-) | Identifies the unique item within the Supply Chain ID. |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | العلم الذي يشير إلى مستوى خدمة الإرجاع إلى المرسل المطلوب. |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | يحتوي على رمز البريد للإرجاع إلى المرسل ولكن بدون DPS. |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | يحدد مجموعة العملاء الفريدة المشاركة في الإرسال. |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | يحدد معرف الدولة UPU. الحد الأقصى للطول: 4 أحرف. |
| [setVersionID(String value)](#setVersionID-java.lang.String-) | يحدد إصدار الباركود المتعلق بكل معرف نوع المعلومات. |
| [setclass(String value)](#setclass-java.lang.String-) | يحدد فئة العنصر. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mailmark2DCodetext() {#Mailmark2DCodetext--}
```
public Mailmark2DCodetext()
```


Create default instance of Mailmark2DCodetext class.

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
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


يحصل على نوع الباركود.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Construct codetext from Mailmark data.

**Returns:**
java.lang.String - نص الرمز المُنشأ
### getCustomerContent() {#getCustomerContent--}
```
public String getCustomerContent()
```


مساحة اختيارية للاستخدام من قبل العميل. الحد الأقصى للطول حسب النوع: النوع 7: 6 أحرف النوع 9: 45 حرفًا النوع 29: 25 حرفًا

**Returns:**
java.lang.String - محتوى العميل
### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public DataMatrixEncodeMode getCustomerContentEncodeMode()
```


وضع الترميز لباركود Datamatrix. القيمة الافتراضية: DataMatrixEncodeMode.C40.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) - Encode mode of Datamatrix barcode.
### getDataMatrixType() {#getDataMatrixType--}
```
public Mailmark2DType getDataMatrixType()
```


2D Mailmark Type defines size of Data Matrix barcode.

**Returns:**
[Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) - Size of Data Matrix barcode
### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public String getDestinationPostCodeAndDPS()
```


يحتوي على الرمز البريدي لعنوان التسليم مع DPS. إذا كان داخليًا، يحتوي الرمز البريدي/DP على عدد الأحرف التالي: المنطقة (حرف أو حرفان) الحي (حرف أو حرفان) القطاع (حرف واحد) الوحدة (حرفان) DPS (حرفان). يجب أن يتوافق الرمز البريدي وDPS مع تنسيق PAF® صالح.

**Returns:**
java.lang.String - الرمز البريدي لعنوان التسليم مع DPS
### getInformationTypeID() {#getInformationTypeID--}
```
public String getInformationTypeID()
```


يحدد حمولة باركود Mailmark من Royal Mail لكل نوع منتج. القيم الصالحة: '0' - محلي مُصنَّف وغير مُصنَّف 'A' - بريد عبر الإنترنت 'B' - طباعة الفرانكينغ 'C' - دمج

**Returns:**
java.lang.String - معرف نوع المعلومات
### getItemID() {#getItemID--}
```
public int getItemID()
```


يحدد العنصر الفريد داخل معرف سلسلة الإمداد. يجب أن يحمل كل باركود Mailmark معرفًا حتى يمكن التعرف عليه بشكل فريد لمدة لا تقل عن 90 يومًا. الحد الأقصى للقيمة: 99999999.

**Returns:**
int - العنصر داخل معرف سلسلة الإمداد
### getRTSFlag() {#getRTSFlag--}
```
public String getRTSFlag()
```


العلم الذي يشير إلى مستوى خدمة الإرجاع إلى المرسل المطلوب.

**Returns:**
java.lang.String - علم RTS
### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public String getReturnToSenderPostCode()
```


يحتوي على رمز البريد للإرجاع إلى المرسل ولكن بدون DPS. يجب أن يتوافق الرمز البريدي (بدون DPS) مع تنسيق PAF®.

**Returns:**
java.lang.String - رمز البريد للإرجاع إلى المرسل بدون DPS
### getSupplyChainID() {#getSupplyChainID--}
```
public int getSupplyChainID()
```


يحدد مجموعة العملاء الفريدة المشاركة في الإرسال. الحد الأقصى للقيمة: 9999999.

**Returns:**
int - معرف سلسلة الإمداد
### getUPUCountryID() {#getUPUCountryID--}
```
public String getUPUCountryID()
```


يحدد معرف الدولة UPU. الحد الأقصى للطول: 4 أحرف.

**Returns:**
java.lang.String - معرف الدولة
### getVersionID() {#getVersionID--}
```
public String getVersionID()
```


يحدد إصدار الباركود المتعلق بكل معرف نوع المعلومات. القيم الصالحة: حاليًا '1'. '0' و'2' إلى '9' و'A' إلى 'Z' محجوزة للاستخدام المستقبلي المحتمل.

**Returns:**
java.lang.String - معرف الإصدار
### getclass() {#getclass--}
```
public String getclass()
```


يحدد فئة العنصر. القيم الصالحة: '1' - 1C (تجزئة) '2' - 2C (تجزئة) '3' - اقتصاد (تجزئة) '5' - مؤجل (تجزئة) '8' - مميز (وصول شبكة) '9' - قياسي (وصول شبكة)

**Returns:**
java.lang.String - فئة العنصر
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Initializes Mailmark data from constructed codetext.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| constructedCodetext | java.lang.String | نص الرمز المُنشأ. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public void setCustomerContent(String value)
```


مساحة اختيارية للاستخدام من قبل العميل. الحد الأقصى للطول حسب النوع: النوع 7: 6 أحرف النوع 9: 45 حرفًا النوع 29: 25 حرفًا

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | Customer content |

### setCustomerContentEncodeMode(DataMatrixEncodeMode value) {#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public void setCustomerContentEncodeMode(DataMatrixEncodeMode value)
```


Encode mode of Datamatrix barcode. Default value: EncodeMode.C40.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Encode mode of Datamatrix barcode. |

### setDataMatrixType(Mailmark2DType value) {#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-}
```
public void setDataMatrixType(Mailmark2DType value)
```


2D Mailmark Type defines size of Data Matrix barcode.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) | Size of Data Matrix barcode |

### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public void setDestinationPostCodeAndDPS(String value)
```


يحتوي على الرمز البريدي لعنوان التسليم مع DPS. إذا كان داخليًا، يحتوي الرمز البريدي/DP على عدد الأحرف التالي: المنطقة (حرف أو حرفان) الحي (حرف أو حرفان) القطاع (حرف واحد) الوحدة (حرفان) DPS (حرفان). يجب أن يتوافق الرمز البريدي وDPS مع تنسيق PAF® صالح.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | the Postcode of the Delivery Address with DPS |

### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public void setInformationTypeID(String value)
```


يحدد حمولة باركود Mailmark من Royal Mail لكل نوع منتج. القيم الصالحة: '0' - محلي مُصنَّف وغير مُصنَّف 'A' - بريد عبر الإنترنت 'B' - طباعة الفرانكينغ 'C' - دمج

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | Information type ID |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


يحدد العنصر الفريد داخل معرف سلسلة الإمداد. يجب أن يحمل كل باركود Mailmark معرفًا حتى يمكن التعرف عليه بشكل فريد لمدة لا تقل عن 90 يومًا. الحد الأقصى للقيمة: 99999999.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int | item within the Supply Chain ID |

### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public void setRTSFlag(String value)
```


العلم الذي يشير إلى مستوى خدمة الإرجاع إلى المرسل المطلوب.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public void setReturnToSenderPostCode(String value)
```


يحتوي على رمز البريد للإرجاع إلى المرسل ولكن بدون DPS. يجب أن يتوافق الرمز البريدي (بدون DPS) مع تنسيق PAF®.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | Return to Sender Post Code but no DPS |

### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public void setSupplyChainID(int value)
```


يحدد مجموعة العملاء الفريدة المشاركة في الإرسال. الحد الأقصى للقيمة: 9999999.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int | Supply chain ID |

### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public void setUPUCountryID(String value)
```


يحدد معرف الدولة UPU. الحد الأقصى للطول: 4 أحرف.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | Country ID |

### setVersionID(String value) {#setVersionID-java.lang.String-}
```
public void setVersionID(String value)
```


يحدد إصدار الباركود المتعلق بكل معرف نوع المعلومات. القيم الصالحة: حاليًا '1'. '0' و'2' إلى '9' و'A' إلى 'Z' محجوزة للاستخدام المستقبلي المحتمل.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | Version ID |

### setclass(String value) {#setclass-java.lang.String-}
```
public void setclass(String value)
```


يحدد فئة العنصر. القيم الصالحة: '1' - 1C (تجزئة) '2' - 2C (تجزئة) '3' - اقتصاد (تجزئة) '5' - مؤجل (تجزئة) '8' - مميز (وصول شبكة) '9' - قياسي (وصول شبكة)

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | class of the item |

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

