---
title: QrExtCodetextBuilder
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: مولد نص الترميز الموسع لباركودات 2D QR لوضع ExtendedCodetext في QrEncodeMode. استخدم خاصية TwoDDisplayText في BarcodeGenerator لتعيين النص الظاهر وإزالة الأحرف الإدارية.
type: docs
weight: 63
url: /ar/androidjava/com.aspose.barcode.generation/qrextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class QrExtCodetextBuilder extends ExtCodetextBuilder
```

مولد النص الموسع للباركودات QR ثنائية الأبعاد لوضع ExtendedCodetext في QrEncodeMode. استخدم خاصية TwoDDisplayText في BarcodeGenerator لتعيين النص المرئي وإزالة الأحرف الإدارية. يوضح هذا المثال كيفية استخدام FNC1 في الموضع الأول في الوضع الموسع: QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder(); lTextBuilder.addFNC1FirstPosition(); lTextBuilder.addPlainCodetext("000%89%%0"); lTextBuilder.addFNC1GroupSeparator(); lTextBuilder.addPlainCodetext("12345<FNC1>"); //generate codetext String lCodetext = lTextBuilder.getExtendedCodetext(); //generate BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.ExtendedCodetext); generator.getParameters().getBarcode().getQR().setQrErrorLevel(QRErrorLevel.LevelL); generator.setCodeText(lCodetext); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("test.bmp"); يوضح هذا المثال كيفية استخدام FNC1 في الموضع الثاني في الوضع الموسع. //create codetext QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder(); TextBuilder.addFNC1SecondPosition("12"); TextBuilder.addPlainCodetext("TRUE3456"); //generate codetext String lCodetext = lTextBuilder.getExtendedCodetext(); //generate BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR); generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.ExtendedCodetext); generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LevelL); generator.setCodeText(lCodetext); generatorgenerator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("test.bmp"); يوضح هذا المثال كيفية استخدام وضع ECI المتعدد في الوضع الموسع. //create codetext QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder(); TextBuilder.addECICodetext(ECIEncodings.Win1251, "Will"); TextBuilder.addECICodetext(ECIEncodings.UTF8, "Right"); TextBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power"); TextBuilder.addPlainCodetext(@"t\\e\\\\st"); //generate codetext String lCodetext = lTextBuilder.getExtendedCodetext(); //generate BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR); generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.ExtendedCodetext); generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LevelL); generator.setCodeText(lCodetext); generatorgenerator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("test.bmp");
## Constructors

| Constructor | الوصف |
| --- | --- |
| [QrExtCodetextBuilder()](#QrExtCodetextBuilder--) |  |
## Methods

| Method | الوصف |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | يضيف نص رمز مع معرف القناة الموسعة |
| [addFNC1FirstPosition()](#addFNC1FirstPosition--) | يضيف FNC1 في الموضع الأول إلى عناصر النص الموسع. |
| [addFNC1GroupSeparator()](#addFNC1GroupSeparator--) | يضيف فاصل المجموعة (GS - '\\u001D') إلى عناصر النص الموسع. |
| [addFNC1SecondPosition(String codetext)](#addFNC1SecondPosition-java.lang.String-) | يضيف FNC1 في الموضع الثاني إلى عناصر النص الموسع. |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Adds plain codetext to the extended codetext items |
| [clear()](#clear--) | Clears extended codetext items |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Generates Extended codetext from the extended codetext list. |
| [hashCode()](#hashCode--) |  |
| [isNeedToShieldItemFromPrevECI(int Index)](#isNeedToShieldItemFromPrevECI-int-) | Checks necessity to shield previous item by "\\000000" |
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


### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public void addECICodetext(int ECIEncoding, String codetext)
```


يضيف نص رمز مع معرف القناة الموسعة

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| ECIEncoding | int | Extended Channel Identifier |
| codetext | java.lang.String | Codetext in unicode to add as extended codetext item with Extended Channel Identifier |

### addFNC1FirstPosition() {#addFNC1FirstPosition--}
```
public void addFNC1FirstPosition()
```


يضيف FNC1 في الموضع الأول إلى عناصر النص الموسع.

### addFNC1GroupSeparator() {#addFNC1GroupSeparator--}
```
public void addFNC1GroupSeparator()
```


يضيف فاصل المجموعة (GS - '\\u001D') إلى عناصر النص الموسع.

### addFNC1SecondPosition(String codetext) {#addFNC1SecondPosition-java.lang.String-}
```
public void addFNC1SecondPosition(String codetext)
```


يضيف FNC1 في الموضع الثاني إلى عناصر النص الموسع.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| codetext | java.lang.String | قيمة FNC1 في الموضع الثاني |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public void addPlainCodetext(String codetext)
```


Adds plain codetext to the extended codetext items

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| codetext | java.lang.String | Codetext in unicode to add as extended codetext item |

### clear() {#clear--}
```
public void clear()
```


Clears extended codetext items

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
### getExtendedCodetext() {#getExtendedCodetext--}
```
public String getExtendedCodetext()
```


Generates Extended codetext from the extended codetext list.

**Returns:**
java.lang.String - Extended codetext as string
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isNeedToShieldItemFromPrevECI(int Index) {#isNeedToShieldItemFromPrevECI-int-}
```
public boolean isNeedToShieldItemFromPrevECI(int Index)
```


Checks necessity to shield previous item by "\\000000"

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| Index | int | Index in m\_List |

**Returns:**
boolean - Necessity to shield
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

