---
title: HIBCLICComplexCodetext
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: الفئة الأساسية لتشفير وفك تشفير النص المضمن في رمز HIBC LIC.
type: docs
weight: 15
url: /ar/androidjava/com.aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public abstract class HIBCLICComplexCodetext implements IComplexCodetext
```

الفئة الأساسية لتشفير وفك تشفير النص المضمن في رمز HIBC LIC.

--------------------

> ```
> This sample shows how to decode raw HIBC LIC codetext to HIBCLICComplexCodetext instance.
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.HIBC_AZTEC_LIC);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      HIBCLICComplexCodetext resultHIBCLICComplexCodetext = ComplexCodetextReader.tryDecodeHIBCLIC(result.getCodeText());
>      System.out.println("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
>      System.out.println("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
>  }
> ```
## Constructors

| Constructor | الوصف |
| --- | --- |
| [HIBCLICComplexCodetext()](#HIBCLICComplexCodetext--) |  |
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | يحصل على أو يعيّن نوع الباركود. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | يبني codetext. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | يُهيئ المثيلة من codetext المُنشأ. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | يحصل على أو يعيّن نوع الباركود. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIBCLICComplexCodetext() {#HIBCLICComplexCodetext--}
```
public HIBCLICComplexCodetext()
```


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


يحصل أو يعيّن نوع الباركود. يمكن ترميز نص رمز HIBC LIC باستخدام الأنواع HIBCCode39LIC، HIBCCode128LIC، HIBCAztecLIC، HIBCDataMatrixLIC و HIBCQRLIC. القيمة الافتراضية: HIBCCode39LIC.

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
public abstract String getConstructedCodetext()
```


يبني codetext.

**Returns:**
java.lang.String - نص الرمز المُنشأ
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public abstract void initFromString(String constructedCodetext)
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




### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


يحصل أو يعيّن نوع الباركود. يمكن ترميز نص رمز HIBC LIC باستخدام الأنواع HIBCCode39LIC، HIBCCode128LIC، HIBCAztecLIC، HIBCDataMatrixLIC و HIBCQRLIC. القيمة الافتراضية: HIBCCode39LIC.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

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

