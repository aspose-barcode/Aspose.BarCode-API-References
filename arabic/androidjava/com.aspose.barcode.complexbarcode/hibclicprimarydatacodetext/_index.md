---
title: HIBCLICPrimaryDataCodetext
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: فئة لتشفير وفك تشفير النص المضمن في رمز HIBC LIC الذي يخزن البيانات الأولية.
type: docs
weight: 16
url: /ar/androidjava/com.aspose.barcode.complexbarcode/hibclicprimarydatacodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.HIBCLICComplexCodetext](../../com.aspose.barcode.complexbarcode/hibcliccomplexcodetext)
```
public class HIBCLICPrimaryDataCodetext extends HIBCLICComplexCodetext
```

فئة لتشفير وفك تشفير النص المضمن في رمز HIBC LIC الذي يخزن البيانات الأولية.

--------------------

> ```
> This sample shows how to encode and decode HIBC LIC using HIBCLICPrimaryDataCodetext.
>  
>  HIBCLICPrimaryDataCodetext complexCodetext  = new HIBCLICPrimaryDataCodetext();
>  complexCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
>  complexCodetext.setData(new PrimaryData());
>  complexCodetext.getData().setProductOrCatalogNumber("12345");
>  complexCodetext.getData().setLabelerIdentificationCode("A999");
>  complexCodetext.getData().setUnitOfMeasureID(1);
>  ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext);
>  {
>      BufferedImage image = generator.generateBarCodeImage();
>      BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC);
>      {
>          reader.readBarCodes();
>          HIBCLICPrimaryCodetext result = (HIBCLICPrimaryCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
>          HIBCLICPrimaryCodetext result = (HIBCLICPrimaryCodetext)ComplexCodetextReader.tryDecodeHIBCLIC(codetext);
>          System.out.println("Product or catalog number: " + result.getData().getProductOrCatalogNumber());
>          System.out.println("Labeler identification code: " + result.getData().getLabelerIdentificationCode());
>          System.out.println("Unit of measure ID: " + result.getData().getUnitOfMeasureID());
>      }
>  }
> ```
## Constructors

| Constructor | الوصف |
| --- | --- |
| [HIBCLICPrimaryDataCodetext()](#HIBCLICPrimaryDataCodetext--) |  |
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يرجع قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة HIBCLICPrimaryDataCodetext المحددة. |
| [getBarcodeType()](#getBarcodeType--) | يحصل على أو يعيّن نوع الباركود. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | يبني codetext. |
| [getData()](#getData--) | يحدد البيانات الأساسية. |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | يُهيئ المثيلة من codetext المُنشأ. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | يحصل على أو يعيّن نوع الباركود. |
| [setData(PrimaryData value)](#setData-com.aspose.barcode.complexbarcode.PrimaryData-) | يحدد البيانات الأساسية. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIBCLICPrimaryDataCodetext() {#HIBCLICPrimaryDataCodetext--}
```
public HIBCLICPrimaryDataCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يرجع قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة HIBCLICPrimaryDataCodetext المحددة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة HIBCLICPrimaryDataCodetext للمقارنة مع هذه المثيلة. |

**Returns:**
boolean -  **true**  إذا كان obj له نفس القيمة كما هذا الكائن؛ وإلا،  **false** .
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
public String getConstructedCodetext()
```


يبني codetext.

**Returns:**
java.lang.String - نص الرمز المُنشأ
### getData() {#getData--}
```
public PrimaryData getData()
```


يحدد البيانات الأساسية.

**Returns:**
[PrimaryData](../../com.aspose.barcode.complexbarcode/primarydata)
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




### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


يحصل أو يعيّن نوع الباركود. يمكن ترميز نص رمز HIBC LIC باستخدام الأنواع HIBCCode39LIC، HIBCCode128LIC، HIBCAztecLIC، HIBCDataMatrixLIC و HIBCQRLIC. القيمة الافتراضية: HIBCCode39LIC.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setData(PrimaryData value) {#setData-com.aspose.barcode.complexbarcode.PrimaryData-}
```
public void setData(PrimaryData value)
```


يحدد البيانات الأساسية.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [PrimaryData](../../com.aspose.barcode.complexbarcode/primarydata) |  |

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

