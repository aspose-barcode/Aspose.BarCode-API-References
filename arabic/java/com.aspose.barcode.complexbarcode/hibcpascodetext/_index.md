---
title: "HIBCPASCodetext"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "فئة لتشفير وفك تشفير النص المدمج في رمز HIBC PAS."
type: docs
weight: 18
url: /ar/java/com.aspose.barcode.complexbarcode/hibcpascodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class HIBCPASCodetext implements IComplexCodetext
```

فئة لتشفير وفك تشفير النص المدمج في رمز HIBC PAS.

--------------------

> ```
> This sample shows how to encode and decode HIBC PAS using HIBCPASCodetext.
>   
> 
>   HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
>   complexCodetext.setDataLocation(HIBCPASDataLocation.PATIENT);
>   complexCodetext.addRecord(HIBCPASDataType.LABELER_IDENTIFICATION_CODE, "A123");
>   complexCodetext.addRecord(HIBCPASDataType.MANUFACTURER_SERIAL_NUMBER, "SERIAL123");
>   complexCodetext.setBarcodeType(EncodeTypes.HIBC_DATA_MATRIX_PAS);
>   ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext);
>   BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.HIBC_DATA_MATRIX_PAS);
>   reader.readBarCodes();
>   String codetext = reader.getFoundBarCodes()[0].getCodeText();
>  	HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.tryDecodeHIBCPAS(codetext);
>   System.out.println("Data location: {0}", readCodetext.getDataLocation());
>   System.out.print("Data type: {0}. ", readCodetext.getRecords()[0].getDataType());
>   System.out.println("Data: {0}", readCodetext.getRecords()[0].getData());
>   System.out.print("Data type: {0}. ", readCodetext.getRecords()[1].getDataType());
>   System.out.println("Data: {0}", readCodetext.getRecords()[1].getData());
>       }
>   }
> ```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [HIBCPASCodetext()](#HIBCPASCodetext--) |  |
## الدوال

| دالة | الوصف |
| --- | --- |
| [addRecord(HIBCPASRecord record)](#addRecord-com.aspose.barcode.complexbarcode.HIBCPASRecord-) | إضافة سجل جديد |
| [addRecord(int dataType, String data)](#addRecord-int-java.lang.String-) | إضافة سجل جديد |
| [clear()](#clear--) | مسح قائمة السجلات |
| [equals(Object obj)](#equals-java.lang.Object-) | إرجاع قيمة تشير إلى ما إذا كانت هذه النسخة مساوية لقيمة HIBCPASCodetext المحددة. |
| [getBarcodeType()](#getBarcodeType--) | يحصل على نوع الباركود. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | يبني نص الشيفرة. |
| [getDataLocation()](#getDataLocation--) | تحديد موقع البيانات. |
| [getRecords()](#getRecords--) | الحصول على قائمة السجلات |
| [hashCode()](#hashCode--) | يعيد رمز التجزئة لهذه المثيلة. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | يُهيئ المثيلة من نص الشيفرة المُنشأ. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | يحصل أو يعيّن نوع الباركود. |
| [setDataLocation(int value)](#setDataLocation-int-) | تحديد موقع البيانات. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIBCPASCodetext() {#HIBCPASCodetext--}
```
public HIBCPASCodetext()
```


### addRecord(HIBCPASRecord record) {#addRecord-com.aspose.barcode.complexbarcode.HIBCPASRecord-}
```
public void addRecord(HIBCPASRecord record)
```


إضافة سجل جديد

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| record | [HIBCPASRecord](../../com.aspose.barcode.complexbarcode/hibcpasrecord) | السجل المراد إضافته |

### addRecord(int dataType, String data) {#addRecord-int-java.lang.String-}
```
public void addRecord(int dataType, String data)
```


إضافة سجل جديد

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| dataType | int | نوع البيانات |
| بيانات | java.lang.String | سلسلة البيانات |

### clear() {#clear--}
```
public void clear()
```


مسح قائمة السجلات

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


إرجاع قيمة تشير إلى ما إذا كانت هذه النسخة مساوية لقيمة HIBCPASCodetext المحددة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة HIBCPASCodetext للمقارنة مع هذه النسخة. |

**Returns:**
boolean -  **true**  إذا كان obj له نفس القيمة كهذه المثيلة؛ وإلا،  **false** .
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


يبني نص الشيفرة.

**Returns:**
java.lang.String - نص الكود المُنشأ
### getDataLocation() {#getDataLocation--}
```
public int getDataLocation()
```


تحديد موقع البيانات.

**Returns:**
int
### getRecords() {#getRecords--}
```
public System.Collections.Generic.List<HIBCPASRecord> getRecords()
```


الحصول على قائمة السجلات

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.complexbarcode.HIBCPASRecord> - قائمة السجلات
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد رمز التجزئة لهذه المثيلة.

**Returns:**
int - رمز تجزئة عدد صحيح موقع 32-بت.
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


يُهيئ المثيلة من نص الشيفرة المُنشأ.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| constructedCodetext | java.lang.String | نص الكود المُنشأ. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


الحصول على أو تعيين نوع الباركود. يمكن ترميز نص HIBC PAS باستخدام الأنواع HIBCCode39PAS، HIBCCode128PAS، HIBCAztec:PAS، HIBCDataMatrixPAS و HIBCQRPAS. القيمة الافتراضية: HIBCCode39PAS.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setDataLocation(int value) {#setDataLocation-int-}
```
public void setDataLocation(int value)
```


تحديد موقع البيانات.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

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

