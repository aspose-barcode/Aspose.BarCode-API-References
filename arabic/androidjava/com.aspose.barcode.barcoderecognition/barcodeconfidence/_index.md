---
title: BarCodeConfidence
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: يحتوي على مستوى ثقة التعرف
type: docs
weight: 13
url: /ar/androidjava/com.aspose.barcode.barcoderecognition/barcodeconfidence/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeConfidence
```

يحتوي على مستوى ثقة التعرف

--------------------

> ```
> This sample shows how BarCodeConfidence changed, depending on barcode type
>  
>  //Moderate confidence
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_STANDARD, DecodeType.CODE_128);
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode Type: " + result.getCodeTypeName());
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>          System.out.println("BarCode Confidence: " + result.getConfidence());
>          System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      }
>  //Strong confidence
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_STANDARD, DecodeType.QR);
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode Type: " + result.getCodeTypeName());
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>          System.out.println("BarCode Confidence: " + result.getConfidence());
>          System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      }
> ```
## الحقول

| حقل | الوصف |
| --- | --- |
| [MODERATE](#MODERATE) | ثقة التعرف على الباركود (معظمها باركودات أحادية الأبعاد) مع مجموع تحقق ضعيف أو حتى بدونه. |
| [NONE](#NONE) | ثقة التعرف على الباركود حيث لم يتم التعرف على نص الشيفرة بشكل صحيح أو تم اكتشاف الباركود على أنه ممكن أن يكون fakeBarCodeExtendedParameters. |
| [STRONG](#STRONG) | ثقة التعرف التي تم تأكيدها باستخدام رموز BCH مثل Reed\\u2013Solomon. |
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MODERATE {#MODERATE}
```
public static final int MODERATE
```


ثقة التعرف على الباركود (معظمها باركودات أحادية الأبعاد) مع مجموع تحقق ضعيف أو حتى بدونه. قد يحتوي على بعض الأخطاء في نص الشيفرة أو حتى تعارفات مزيفة إذا كانت منخفضة.

### NONE {#NONE}
```
public static final int NONE
```


ثقة التعرف على الباركود حيث لم يتم التعرف على نص الشيفرة بشكل صحيح أو تم اكتشاف الباركود على أنه ممكن أن يكون fakeBarCodeExtendedParameters.

### STRONG {#STRONG}
```
public static final int STRONG
```


ثقة التعرف التي تم تأكيدها باستخدام رموز BCH مثل Reed\\u2013Solomon. يجب ألا تكون هناك أخطاء في نص الشيفرة المقروء أو تعارفات مزيفة.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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

