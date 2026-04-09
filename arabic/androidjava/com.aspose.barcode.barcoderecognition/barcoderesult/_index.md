---
title: BarCodeResult
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: يخزن بيانات الباركود المعترف بها مثل SingleDecodeType type string codetext BarCodeRegionParameters region وغيرها من المعلمات
type: docs
weight: 18
url: /ar/androidjava/com.aspose.barcode.barcoderecognition/barcoderesult/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeResult
```

يخزن بيانات الباركود المعترف به مثل النوع SingleDecodeType، النص string codetext، المنطقة BarCodeRegionParameters، ومعلمات أخرى

--------------------

> ```
> This sample shows how to obtain BarCodeResult.
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("BarCode Confidence: " + result.getConfidence());
>      System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>  }
> ```
## Constructors

| Constructor | الوصف |
| --- | --- |
| [BarCodeResult(BarCodeResult result)](#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-) | ينشئ نسخةً من فئة  BarCodeResult  . |
## Methods

| Method | الوصف |
| --- | --- |
| [deepClone()](#deepClone--) | ينشئ نسخةً من فئة  BarCodeResult  . |
| [equals(Object obj)](#equals-java.lang.Object-) | يعيد قيمة تُشير إلى ما إذا كانت هذه الحالة مساوية لقيمة  BarCodeResult  المحددة. |
| [getClass()](#getClass--) |  |
| [getCodeBytes()](#getCodeBytes--) | يحصل على بايتات الشيفرة المشفرة |
| [getCodeText()](#getCodeText--) | يحصل على نص الشيفرة |
| [getCodeText(Charset encoding)](#getCodeText-java.nio.charset.Charset-) | يحصل على نص الشيفرة مع الترميز. |
| [getCodeType()](#getCodeType--) | يحصل على نوع الباركود |
| [getCodeTypeName()](#getCodeTypeName--) | يحصل على اسم نوع الباركود |
| [getConfidence()](#getConfidence--) | يحصل على مستوى ثقة التعرف للباركود المعترف به |
| [getExtended()](#getExtended--) | يحصل على المعلمات الموسعة للباركود المعترف به |
| [getReadingQuality()](#getReadingQuality--) | يحصل على جودة القراءة. |
| [getRegion()](#getRegion--) | يحصل على منطقة الباركود |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | يعيد تمثيلًا نصيًا قابلًا للقراءة للإنسان لهذا  BarCodeResult . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeResult(BarCodeResult result) {#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-}
```
public BarCodeResult(BarCodeResult result)
```


ينشئ نسخةً من فئة  BarCodeResult  .

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| result | [BarCodeResult](../../com.aspose.barcode.barcoderecognition/barcoderesult) | نسخة من كائن  BarCodeResult . |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


ينشئ نسخةً من فئة  BarCodeResult  .

**Returns:**
java.lang.Object - يعيد نسخة من فئة  BarCodeResult .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يعيد قيمة تُشير إلى ما إذا كانت هذه الحالة مساوية لقيمة  BarCodeResult  المحددة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة  BarCodeResult  للمقارنة مع هذه الحالة. |

**Returns:**
boolean -  **true**  إذا كان obj له نفس القيمة كما هذا الكائن؛ وإلا،  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodeBytes() {#getCodeBytes--}
```
public byte[] getCodeBytes()
```


يحصل على بايتات الشيفرة المشفرة

القيمة: بايتات الشيفرة للباركود

**Returns:**
byte[]
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


يحصل على نص الشيفرة

القيمة: نص الرمز الشريطي

**Returns:**
java.lang.String
### getCodeText(Charset encoding) {#getCodeText-java.nio.charset.Charset-}
```
public String getCodeText(Charset encoding)
```


يحصل على نص الشيفرة مع الترميز.

--------------------

> ```
> This example shows how to use ```
> GetCodeText
> ```:
>   
>   BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	gen.setCodeText("\u8eca\u7a2e\u540d", Charset.forName("932"));
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DATA_MATRIX);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText(Charset.forName("932")));
> ```

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| الترميز | java.nio.charset.Charset | الترميز لـ codetext. |

**Returns:**
java.lang.String - سلسلة تحتوي على نص الرمز المعترف به.
### getCodeType() {#getCodeType--}
```
public SingleDecodeType getCodeType()
```


يحصل على نوع الباركود

القيمة: معلومات النوع للرمز الشريطي المعترف به

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getCodeTypeName() {#getCodeTypeName--}
```
public String getCodeTypeName()
```


يحصل على اسم نوع الباركود

القيمة: اسم النوع للرمز الشريطي المعترف به

**Returns:**
java.lang.String
### getConfidence() {#getConfidence--}
```
public int getConfidence()
```


يحصل على مستوى ثقة التعرف للباركود المعترف به

القيمة:  BarCodeConfidence.Strong  لا يحتوي على تزيفات أو أخطاء في التعرف،  BarCodeConfidence.Moderate  قد يحتوي أحيانًا على تزيفات أو نص مشفر غير صحيح لأن هذا المستوى من الثقة للباركودات ذات المجموع الاختباري الضعيف أو حتى بدونها،  BarCodeConfidence.None  دائمًا ما يحتوي على نص مشفر غير صحيح وقد يكون تعرّفًا مزيفًا

**Returns:**
int
### getExtended() {#getExtended--}
```
public BarCodeExtendedParameters getExtended()
```


يحصل على المعلمات الموسعة للباركود المعترف به

القيمة: المعلمات الموسعة للباركود المعترف به

**Returns:**
[BarCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/barcodeextendedparameters)
### getReadingQuality() {#getReadingQuality--}
```
public double getReadingQuality()
```


يحصل على جودة القراءة. يعمل مع الباركودات أحادية البعد والبريدية.

القيمة: نسبة جودة القراءة

**Returns:**
double
### getRegion() {#getRegion--}
```
public BarCodeRegionParameters getRegion()
```


يحصل على منطقة الباركود

القيمة: منطقة الباركود المعترف به

**Returns:**
[BarCodeRegionParameters](../../com.aspose.barcode.barcoderecognition/barcoderegionparameters)
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد قيمة تجزئة (hash code) لهذا الكائن.

**Returns:**
int - رمز تجزئة (hash code) عدد صحيح موقع 32 بت.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


يعيد تمثيلًا نصيًا قابلًا للقراءة للإنسان لهذا  BarCodeResult .

**Returns:**
java.lang.String - سلسلة تمثل هذا  BarCodeResult .
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

