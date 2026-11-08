---
title: "BarCodeResult"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "يخزن بيانات الباركود المعترف بها مثل النوع SingleDecodeType، النص codetext، معلمات BarCodeRegionParameters region، وغيرها من المعلمات"
type: docs
weight: 17
url: /ar/java/com.aspose.barcode.barcoderecognition/barcoderesult/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeResult
```

يخزن بيانات الباركود المعترف به مثل النوع SingleDecodeType، السلسلة string codetext، المنطقة BarCodeRegionParameters، ومعلمات أخرى

--------------------

> ```
> This sample shows how to obtain BarCodeResult.
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("BarCode Confidence: " + result.getConfidence());
>      System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>  }
> ```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [BarCodeResult(BarCodeResult result)](#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-) | ينشئ نسخة من فئة BarCodeResult. |
## الدوال

| دالة | الوصف |
| --- | --- |
| [deepClone()](#deepClone--) | ينشئ نسخة من فئة BarCodeResult. |
| [equals(Object obj)](#equals-java.lang.Object-) | يرجع قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة BarCodeResult المحددة. |
| [getClass()](#getClass--) |  |
| [getCodeBytes()](#getCodeBytes--) | يحصل على بايتات الشيفرة المشفرة |
| [getCodeText()](#getCodeText--) | يحصل على نص الشيفرة |
| [getCodeText(Charset charset)](#getCodeText-java.nio.charset.Charset-) | يحصل على نص الشيفرة مع الترميز. |
| [getCodeType()](#getCodeType--) | يحصل على نوع الباركود |
| [getCodeTypeName()](#getCodeTypeName--) | يحصل على اسم نوع الباركود |
| [getConfidence()](#getConfidence--) | يحصل على مستوى ثقة التعرف للباركود المعترف به |
| [getExtended()](#getExtended--) | يحصل على المعلمات الموسعة للباركود المعترف به |
| [getReadingQuality()](#getReadingQuality--) | يحصل على جودة القراءة. |
| [getRegion()](#getRegion--) | يحصل على منطقة الباركود |
| [hashCode()](#hashCode--) | يعيد رمز التجزئة لهذه المثيلة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | يرجع تمثيلًا نصيًا قابلًا للقراءة للإنسان من فئة BarCodeResult هذه. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeResult(BarCodeResult result) {#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-}
```
public BarCodeResult(BarCodeResult result)
```


ينشئ نسخة من فئة BarCodeResult.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| result | [BarCodeResult](../../com.aspose.barcode.barcoderecognition/barcoderesult) | نسخة من كائن BarCodeResult. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


ينشئ نسخة من فئة BarCodeResult.

**Returns:**
java.lang.Object - يرجع نسخة من فئة BarCodeResult.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يرجع قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة BarCodeResult المحددة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة BarCodeResult للمقارنة مع هذه الحالة. |

**Returns:**
boolean -  **true**  إذا كان obj له نفس القيمة كهذه المثيلة؛ وإلا،  **false** .
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

القيمة: نص الشيفرة للباركود

**Returns:**
java.lang.String
### getCodeText(Charset charset) {#getCodeText-java.nio.charset.Charset-}
```
public String getCodeText(Charset charset)
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
| معامل | النوع | الوصف |
| --- | --- | --- |
| charset | java.nio.charset.Charset | الترميز للنص codetext. |

**Returns:**
java.lang.String - سلسلة تحتوي على نص الكود المعترف به.
### getCodeType() {#getCodeType--}
```
public SingleDecodeType getCodeType()
```


يحصل على نوع الباركود

القيمة: معلومات النوع للباركود المعترف به

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getCodeTypeName() {#getCodeTypeName--}
```
public String getCodeTypeName()
```


يحصل على اسم نوع الباركود

القيمة: اسم النوع للباركود المعترف به

**Returns:**
java.lang.String
### getConfidence() {#getConfidence--}
```
public BarCodeConfidence getConfidence()
```


يحصل على مستوى ثقة التعرف للباركود المعترف به

القيمة:  BarCodeConfidence.Strong  لا يحتوي على تزوير أو أخطاء في التعرف،  BarCodeConfidence.Moderate  قد يحتوي أحيانًا على تزوير أو نص كود غير صحيح لأن هذا المستوى من الثقة للباركود مع تدقيق ضعيف أو حتى بدونه،  BarCodeConfidence.None  دائمًا ما يكون نصه غير صحيح وقد يكون تعارفًا مزيفًا

**Returns:**
[BarCodeConfidence](../../com.aspose.barcode.barcoderecognition/barcodeconfidence)
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


يحصل على جودة القراءة. يعمل مع الباركود أحادي الأبعاد والبريدية.

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


يعيد رمز التجزئة لهذه المثيلة.

**Returns:**
int - رمز تجزئة عدد صحيح موقع 32-بت.
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


يرجع تمثيلًا نصيًا قابلًا للقراءة للإنسان من فئة BarCodeResult هذه.

**Returns:**
java.lang.String - سلسلة تمثل هذا  BarCodeResult .
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

