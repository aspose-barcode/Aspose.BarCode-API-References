---
title: MaxiCodeStructuredCodetext
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: الفئة الأساسية لتشفير وفك تشفير النص المضمن في رمز MaxiCode للأوضاع 2 و3.
type: docs
weight: 32
url: /ar/androidjava/com.aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
**Inheritance:**
java.lang.Object، [com.aspose.barcode.complexbarcode.MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext)
```
public abstract class MaxiCodeStructuredCodetext extends MaxiCodeCodetext
```

الفئة الأساسية للترميز وفك الترميز للنص المضمن في رمز MaxiCode للوضعي 2 و3. يوضح هذا المثال كيفية فك ترميز نص MaxiCode الخام إلى كائن MaxiCodeStructuredCodetext.

```
BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MAXI_CODE);
  for (BarCodeResult result : reader.readBarCodes())
  {
      MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
      if (resultMaxiCodeCodetext instanceof MaxiCodeStructuredCodetext)
      {
          MaxiCodeStructuredCodetext maxiCodeStructuredCodetext = (MaxiCodeStructuredCodetext)resultMaxiCodeCodetext;
          System.out.println("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
          System.out.println("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
          System.out.println("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
      }
  }
```
## Constructors

| Constructor | الوصف |
| --- | --- |
| [MaxiCodeStructuredCodetext()](#MaxiCodeStructuredCodetext--) |  |
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة MaxiCodeStructuredCodetext المحددة. |
| [getBarcodeType()](#getBarcodeType--) | يحصل على نوع الباركود. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | يبني codetext. |
| [getCountryCode()](#getCountryCode--) | يحدد رمز الدولة المكوّن من 3 أرقام. |
| [getECIEncoding()](#getECIEncoding--) | يسترجع ترميز ECI. |
| [getEncodeMode()](#getEncodeMode--) | يحصل على وضع ترميز MaxiCode. |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | يحصل على وضع ترميز MaxiCode. |
| [getMode()](#getMode--) | يحصل على وضع MaxiCode. |
| [getPostalCode()](#getPostalCode--) | يحدد الرمز البريدي. |
| [getSecondMessage()](#getSecondMessage--) | يحدد الرسالة الثانية للباركود. |
| [getServiceCategory()](#getServiceCategory--) | يحدد فئة الخدمة المكوّنة من 3 أرقام. |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | يُهيئ المثيلة من codetext المُنشأ. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCountryCode(int value)](#setCountryCode-int-) | يحدد رمز الدولة المكوّن من 3 أرقام. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | يضبط ترميز ECI. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | يضبط وضع ترميز MaxiCode. |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | يضبط وضع ترميز MaxiCode. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | يحدد الرمز البريدي. |
| [setSecondMessage(MaxiCodeSecondMessage value)](#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-) | يحدد الرسالة الثانية للباركود. |
| [setServiceCategory(int value)](#setServiceCategory-int-) | يحدد فئة الخدمة المكوّنة من 3 أرقام. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeStructuredCodetext() {#MaxiCodeStructuredCodetext--}
```
public MaxiCodeStructuredCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة MaxiCodeStructuredCodetext المحددة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة MaxiCodeStructuredCodetext للمقارنة مع هذه المثيلة |

**Returns:**
منطقي - **true** إذا كان obj له نفس القيمة كهذه المثيلة؛ وإلا، **false**
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


يبني codetext.

**Returns:**
java.lang.String - نص الرمز المُنشأ
### getCountryCode() {#getCountryCode--}
```
public int getCountryCode()
```


يحدد رمز الدولة المكوّن من 3 أرقام.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


يحصل على ترميز ECI. يُستخدم عندما يكون MaxiCodeEncodeMode تلقائيًا. القيمة الافتراضية: ISO-8859-1

**Returns:**
عدد صحيح - ترميز ECI.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


يحصل على وضع ترميز MaxiCode. القيمة الافتراضية: تلقائي.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeEncodeMode() {#getMaxiCodeEncodeMode--}
```
public final MaxiCodeEncodeMode getMaxiCodeEncodeMode()
```


يحصل على وضع ترميز MaxiCode. القيمة الافتراضية: تلقائي.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public abstract int getMode()
```


يحصل على وضع MaxiCode.

**Returns:**
عدد صحيح - وضع MaxiCode
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


يحدد الرمز البريدي. يجب أن يكون 9 أرقام في الوضع 2 أو 6 رموز أبجدية رقمية في الوضع 3.

**Returns:**
java.lang.String
### getSecondMessage() {#getSecondMessage--}
```
public MaxiCodeSecondMessage getSecondMessage()
```


يحدد الرسالة الثانية للباركود.

**Returns:**
[MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage)
### getServiceCategory() {#getServiceCategory--}
```
public int getServiceCategory()
```


يحدد فئة الخدمة المكوّنة من 3 أرقام.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد قيمة تجزئة (hash code) لهذا الكائن.

**Returns:**
int - رمز تجزئة (hash code) عدد صحيح موقع 32 بت.
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


يُهيئ المثيلة من codetext المُنشأ.

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




### setCountryCode(int value) {#setCountryCode-int-}
```
public void setCountryCode(int value)
```


يحدد رمز الدولة المكوّن من 3 أرقام.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


يضبط ترميز ECI. يُستخدم عندما يكون MaxiCodeEncodeMode تلقائيًا. القيمة الافتراضية: ISO-8859-1

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int | ترميز ECI. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


يضبط وضع ترميز MaxiCode. القيمة الافتراضية: تلقائي.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | وضع ترميز MaxiCode. |

### setMaxiCodeEncodeMode(MaxiCodeEncodeMode value) {#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)
```


يضبط وضع ترميز MaxiCode. القيمة الافتراضية: تلقائي.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | وضع ترميز MaxiCode. |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


يحدد الرمز البريدي. يجب أن يكون 9 أرقام في الوضع 2 أو 6 رموز أبجدية رقمية في الوضع 3.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setSecondMessage(MaxiCodeSecondMessage value) {#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-}
```
public void setSecondMessage(MaxiCodeSecondMessage value)
```


يحدد الرسالة الثانية للباركود.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage) |  |

### setServiceCategory(int value) {#setServiceCategory-int-}
```
public void setServiceCategory(int value)
```


يحدد فئة الخدمة المكوّنة من 3 أرقام.

**Parameters:**
| Parameter | Type | الوصف |
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

