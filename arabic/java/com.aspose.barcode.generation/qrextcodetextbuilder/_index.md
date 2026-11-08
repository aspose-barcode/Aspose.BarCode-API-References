---
title: "QrExtCodetextBuilder"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: 
type: docs
weight: 61
url: /ar/java/com.aspose.barcode.generation/qrextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class QrExtCodetextBuilder extends ExtCodetextBuilder
```

مولد نص شفرة موسع لباركود QR ثنائي الأبعاد لوضع ExtendedCodetext في EncodeMode

استخدم الخاصية TwoDDisplayText في BarcodeGenerator لتعيين النص الظاهر وإزالة الأحرف الإدارية.

يوضح هذا المثال كيفية استخدام FNC1 في الموضع الأول في الوضع الموسع.

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1FirstPosition();
 textBuilder.addPlainCodetext("000%89%%0");
 textBuilder.addFNC1GroupSeparator();
 textBuilder.addPlainCodetext("12345<FNC1>");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```

يوضح هذا المثال كيفية استخدام FNC1 في الموضع الثاني في الوضع الموسع.

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1SecondPosition("12");
 textBuilder.addPlainCodetext("TRUE3456");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```

يوضح هذا المثال كيفية استخدام وضع ECI المتعدد في الوضع الموسع.

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.WIN_1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF_8, "Right");
 textBuilder.addECICodetext(ECIEncodings.UTF_16_BE, "Power");
 textBuilder.addPlainCodetext("t\\e\\\\st");
 textBuilder.addCodetextWithCompactionMode(QrExtCompactionMode.ALPHA_NUMERIC, "ASPOSE2001");
 textBuilder.addCodetextWithCompactionMode(QrExtCompactionMode.NUMERIC, "20012026");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [QrExtCodetextBuilder()](#QrExtCodetextBuilder--) |  |
## الدوال

| دالة | الوصف |
| --- | --- |
| [addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext)](#addCodetextWithCompactionMode-com.aspose.barcode.generation.QrExtCompactionMode-java.lang.String-) | يضيف نص الشفرة مع وضع ضغط QR المحدد إلى عناصر النص المشفر الموسعة. |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | يضيف codetext مع Extended Channel Identifier |
| [addFNC1FirstPosition()](#addFNC1FirstPosition--) | يضبط FNC1 في الموضع الأول. |
| [addFNC1GroupSeparator()](#addFNC1GroupSeparator--) | يضيف فاصل المجموعة (GS - '\\\\\\u001D') إلى عناصر النص المشفر الموسعة |
| [addFNC1SecondPosition(String codetext)](#addFNC1SecondPosition-java.lang.String-) | يضبط FNC1 في الموضع الثاني. |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | يضيف codetext عادي إلى عناصر codetext الموسعة |
| [clear()](#clear--) | يمسح عناصر codetext الموسعة |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | ينشئ codetext الموسع من قائمة codetext الموسعة. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### QrExtCodetextBuilder() {#QrExtCodetextBuilder--}
```
public QrExtCodetextBuilder()
```


### addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext) {#addCodetextWithCompactionMode-com.aspose.barcode.generation.QrExtCompactionMode-java.lang.String-}
```
public final void addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext)
```


يضيف نص الشفرة مع وضع ضغط QR المحدد إلى عناصر النص المشفر الموسعة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| mode | [QrExtCompactionMode](../../com.aspose.barcode.generation/qrextcompactionmode) | وضع ضغط QR للنص المشفر. |
| codetext | java.lang.String | نص مشفر في Unicode لإضافته كعنصر نص مشفر موسع. |

### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public final void addECICodetext(int ECIEncoding, String codetext)
```


يضيف codetext مع Extended Channel Identifier

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| ECIEncoding | int | Extended Channel Identifier |
| codetext | java.lang.String | codetext في Unicode لإضافته كعنصر codetext موسع مع Extended Channel Identifier |

### addFNC1FirstPosition() {#addFNC1FirstPosition--}
```
public final void addFNC1FirstPosition()
```


يضبط FNC1 في الموضع الأول. إذا تم ضبط وضع FNC1 آخر مسبقًا، يتم استبداله.

### addFNC1GroupSeparator() {#addFNC1GroupSeparator--}
```
public final void addFNC1GroupSeparator()
```


يضيف فاصل المجموعة (GS - '\\\\\\u001D') إلى عناصر النص المشفر الموسعة

### addFNC1SecondPosition(String codetext) {#addFNC1SecondPosition-java.lang.String-}
```
public final void addFNC1SecondPosition(String codetext)
```


يضبط FNC1 في الموضع الثاني. إذا تم ضبط وضع FNC1 آخر مسبقًا، يتم استبداله.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| codetext | java.lang.String | قيمة FNC1 في الموضع الثاني. يجب أن تكون القيمة حرفًا واحدًا من a‑z أو A‑Z، أو رقمًا مكوّنًا من رقمين من 00 إلى 99. |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


يضيف codetext عادي إلى عناصر codetext الموسعة

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| codetext | java.lang.String | نص الترميز في Unicode للإضافة كعنصر نص ترميز ممتد |

### clear() {#clear--}
```
public void clear()
```


يمسح عناصر codetext الموسعة

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
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
### getExtendedCodetext() {#getExtendedCodetext--}
```
public String getExtendedCodetext()
```


ينشئ codetext الموسع من قائمة codetext الموسعة.

**Returns:**
java.lang.String - نص ترميز ممتد كسلسلة
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

