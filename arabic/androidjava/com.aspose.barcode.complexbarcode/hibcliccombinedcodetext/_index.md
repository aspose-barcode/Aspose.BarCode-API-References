---
title: HIBCLICCombinedCodetext
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: فئة لتشفير وفك تشفير النص المضمن في رمز HIBC LIC الذي يخزن البيانات الأولية والثانوية.
type: docs
weight: 14
url: /ar/androidjava/com.aspose.barcode.complexbarcode/hibcliccombinedcodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.HIBCLICComplexCodetext](../../com.aspose.barcode.complexbarcode/hibcliccomplexcodetext)
```
public class HIBCLICCombinedCodetext extends HIBCLICComplexCodetext
```

فئة لتشفير وفك تشفير النص المضمن في رمز HIBC LIC الذي يخزن البيانات الأولية والثانوية.

--------------------

> ```
> This sample shows how to encode and decode HIBC LIC using HIBCLICCombinedCodetext.
>  
> 
>  HIBCLICCombinedCodetext combinedCodetext = new HIBCLICCombinedCodetext();
>  combinedCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
>  combinedCodetext.setPrimaryData(new PrimaryData());
>  combinedCodetext.getPrimaryData().setProductOrCatalogNumber("12345");
>  combinedCodetext.getPrimaryData().setLabelerIdentificationCode("A999");
>  combinedCodetext.getPrimaryData().setUnitOfMeasureID(1);
>  combinedCodetext.setSecondaryAndAdditionalData(new SecondaryAndAdditionalData());
>  combinedCodetext.getSecondaryAndAdditionalData().setExpiryDate(new Date());
>  combinedCodetext.getSecondaryAndAdditionalData().setExpiryDateFormat(HIBCLICDateFormat.MMDDYY);
>  combinedCodetext.getSecondaryAndAdditionalData().setQuantity(30);
>  combinedCodetext.getSecondaryAndAdditionalData().setLotNumber("LOT123");
>  combinedCodetext.getSecondaryAndAdditionalData().setSerialNumber("SERIAL123");
>  combinedCodetext.getSecondaryAndAdditionalData().setDateOfManufacture(new Date());
>  ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(combinedCodetext);
>  BufferedImage image = generator.generateBarCodeImage();
>  BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC);
>  reader.readBarCodes();
>  String codetext = reader.getFoundBarCodes()[0].getCodeText();
>  HIBCLICCombinedCodetext result = (HIBCLICCombinedCodetext)ComplexCodetextReader.tryDecodeHIBCLIC(codetext);
>  System.out.println("Product or catalog number: " + result.getPrimaryData().getProductOrCatalogNumber());
>  System.out.println("Labeler identification code: " + result.getPrimaryData().getLabelerIdentificationCode());
>  System.out.println("Unit of measure ID: " + result.getPrimaryData().getUnitOfMeasureID());
>  System.out.println("Expiry date: " + result.getSecondaryAndAdditionalData().getExpiryDate());
>  System.out.println("Quantity: " + result.getSecondaryAndAdditionalData().getQuantity());
>  System.out.println("Lot number: " + result.getSecondaryAndAdditionalData().getLotNumber());
>  System.out.println("Serial number: " + result.getSecondaryAndAdditionalData().getSerialNumber());
>  System.out.println("Date of manufacture: " + result.getSecondaryAndAdditionalData().getDateOfManufacture());
> ```
## Constructors

| Constructor | الوصف |
| --- | --- |
| [HIBCLICCombinedCodetext()](#HIBCLICCombinedCodetext--) |  |
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يعيد قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة  HIBCLICCombinedCodetext  المحددة. |
| [getBarcodeType()](#getBarcodeType--) | يحصل على أو يعيّن نوع الباركود. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | يبني codetext. |
| [getPrimaryData()](#getPrimaryData--) | يحدد البيانات الأساسية. |
| [getSecondaryAndAdditionalData()](#getSecondaryAndAdditionalData--) | يحدد البيانات الثانوية والبيانات الإضافية التكميلية. |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | يُهيئ المثيلة من codetext المُنشأ. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | يحصل على أو يعيّن نوع الباركود. |
| [setPrimaryData(PrimaryData value)](#setPrimaryData-com.aspose.barcode.complexbarcode.PrimaryData-) | يحدد البيانات الأساسية. |
| [setSecondaryAndAdditionalData(SecondaryAndAdditionalData value)](#setSecondaryAndAdditionalData-com.aspose.barcode.complexbarcode.SecondaryAndAdditionalData-) | يحدد البيانات الثانوية والبيانات الإضافية التكميلية. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIBCLICCombinedCodetext() {#HIBCLICCombinedCodetext--}
```
public HIBCLICCombinedCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يعيد قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة  HIBCLICCombinedCodetext  المحددة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة  HIBCLICCombinedCodetext  للمقارنة مع هذه الحالة. |

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
### getPrimaryData() {#getPrimaryData--}
```
public PrimaryData getPrimaryData()
```


يحدد البيانات الأساسية.

**Returns:**
[PrimaryData](../../com.aspose.barcode.complexbarcode/primarydata)
### getSecondaryAndAdditionalData() {#getSecondaryAndAdditionalData--}
```
public SecondaryAndAdditionalData getSecondaryAndAdditionalData()
```


يحدد البيانات الثانوية والبيانات الإضافية التكميلية.

**Returns:**
[SecondaryAndAdditionalData](../../com.aspose.barcode.complexbarcode/secondaryandadditionaldata)
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

### setPrimaryData(PrimaryData value) {#setPrimaryData-com.aspose.barcode.complexbarcode.PrimaryData-}
```
public void setPrimaryData(PrimaryData value)
```


يحدد البيانات الأساسية.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [PrimaryData](../../com.aspose.barcode.complexbarcode/primarydata) |  |

### setSecondaryAndAdditionalData(SecondaryAndAdditionalData value) {#setSecondaryAndAdditionalData-com.aspose.barcode.complexbarcode.SecondaryAndAdditionalData-}
```
public void setSecondaryAndAdditionalData(SecondaryAndAdditionalData value)
```


يحدد البيانات الثانوية والبيانات الإضافية التكميلية.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [SecondaryAndAdditionalData](../../com.aspose.barcode.complexbarcode/secondaryandadditionaldata) |  |

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

