---
title: "MaxiCodeStandardCodetext"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "فئة لتشفير وفك تشفير نص MaxiCode للأوضاع 4 و5 و6."
type: docs
weight: 29
url: /ar/java/com.aspose.barcode.complexbarcode/maxicodestandardcodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext)
```
public class MaxiCodeStandardCodetext extends MaxiCodeCodetext
```

فئة لتشفير وفك تشفير نص MaxiCode للطور 4، 5 و6.

```
//Mode 4
 MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
 maxiCodeCodetext.setMode(MaxiCodeMode.MODE_4);
 maxiCodeCodetext.setMessage("Test message");
 ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
 complexGenerator.generateBarCodeImage();

 //Mode 5
 MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
 maxiCodeCodetext.setMode(MaxiCodeMode.MODE_5);
 maxiCodeCodetext.setMessage("Test message");
 ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
 complexGenerator.generateBarCodeImage();

 //Mode 6
 MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
 maxiCodeCodetext.setMode(MaxiCodeMode.MODE_6);
 maxiCodeCodetext.setMessage("Test message");
 ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
 complexGenerator.generateBarCodeImage();
```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [MaxiCodeStandardCodetext()](#MaxiCodeStandardCodetext--) |  |
## الدوال

| دالة | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يعيد قيمة تشير إلى ما إذا كان هذا الكائن يساوي قيمة MaxiCodeStandardCodetext المحددة. |
| [getBarcodeType()](#getBarcodeType--) | يحصل على نوع الباركود. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | يبني نص الشيفرة. |
| [getECIEncoding()](#getECIEncoding--) | يحصل على ترميز ECI. |
| [getEncodeMode()](#getEncodeMode--) | يحصل على وضع ترميز MaxiCode. |
| [getMessage()](#getMessage--) | يحصل على الرسالة. |
| [getMode()](#getMode--) | يحصل على وضع MaxiCode. |
| [hashCode()](#hashCode--) | يعيد رمز التجزئة لهذه المثيلة. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | يُهيئ المثيلة من نص الشيفرة المُنشأ. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | يضبط ترميز ECI. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | يضبط وضع ترميز MaxiCode. |
| [setMessage(String value)](#setMessage-java.lang.String-) | يضبط الرسالة. |
| [setMode(MaxiCodeMode mode)](#setMode-com.aspose.barcode.generation.MaxiCodeMode-) | يضبط وضع MaxiCode. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeStandardCodetext() {#MaxiCodeStandardCodetext--}
```
public MaxiCodeStandardCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يعيد قيمة تشير إلى ما إذا كان هذا الكائن يساوي قيمة MaxiCodeStandardCodetext المحددة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة MaxiCodeStandardCodetext للمقارنة مع هذا الكائن. |

**Returns:**
boolean - إذا كان الكائن obj له نفس القيمة كهذا الكائن؛ وإلا، **false**.
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


يحصل على ترميز ECI. يُستخدم عندما يكون MaxiCodeEncodeMode على الوضع التلقائي. القيمة الافتراضية: ISO-8859-1

**Returns:**
int - ترميز ECI.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


يحصل على وضع ترميز MaxiCode. القيمة الافتراضية: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMessage() {#getMessage--}
```
public String getMessage()
```


يحصل على الرسالة.

**Returns:**
java.lang.String
### getMode() {#getMode--}
```
public MaxiCodeMode getMode()
```


يحصل على وضع MaxiCode.

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) - MaxiCode mode
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد رمز التجزئة لهذه المثيلة.

**Returns:**
int - رمز تجزئة صحيح موقّع 32-بت.
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




### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


يضبط ترميز ECI. يُستخدم عندما يكون MaxiCodeEncodeMode هو Auto. القيمة الافتراضية: ISO-8859-1

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int | ترميز ECI. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


يضبط وضع ترميز MaxiCode. القيمة الافتراضية: Auto.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | وضع ترميز MaxiCode. |

### setMessage(String value) {#setMessage-java.lang.String-}
```
public void setMessage(String value)
```


يضبط الرسالة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setMode(MaxiCodeMode mode) {#setMode-com.aspose.barcode.generation.MaxiCodeMode-}
```
public void setMode(MaxiCodeMode mode)
```


يضبط وضع MaxiCode. يمكن استخدام نص الكود القياسي فقط مع الأوضاع 4 و5 و6.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| mode | [MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) |  |

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

