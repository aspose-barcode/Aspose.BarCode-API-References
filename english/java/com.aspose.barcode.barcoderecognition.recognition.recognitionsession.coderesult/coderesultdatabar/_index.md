---
title: CodeResultDataBar
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 15
url: /java/com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult/coderesultdatabar/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.CodeResult](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult/coderesult), [com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.CodeResult1D](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult/coderesult1d)
```
public class CodeResultDataBar extends CodeResult1D
```
## Constructors

| Constructor | Description |
| --- | --- |
| [CodeResultDataBar()](#CodeResultDataBar--) |  |
| [CodeResultDataBar(SingleDecodeType aReadType, String aCodeText)](#CodeResultDataBar-com.aspose.barcode.barcoderecognition.SingleDecodeType-java.lang.String-) |  |
| [CodeResultDataBar(CodeResultDataBar aResult)](#CodeResultDataBar-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.CodeResultDataBar-) |  |
## Fields

| Field | Description |
| --- | --- |
| [Angle](#Angle) |  |
| [CheckSum](#CheckSum) |  |
| [CodeText](#CodeText) |  |
| [IsRestored](#IsRestored) |  |
| [Quality](#Quality) |  |
| [ReadType](#ReadType) |  |
| [Region](#Region) |  |
| [is2DCompositeComponent](#is2DCompositeComponent) |  |
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getQuadPoints()](#getQuadPoints--) |  |
| [hashCode()](#hashCode--) |  |
| [isDataBarType(BaseDecodeType readType)](#isDataBarType-com.aspose.barcode.barcoderecognition.BaseDecodeType-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CodeResultDataBar() {#CodeResultDataBar--}
```
public CodeResultDataBar()
```


### CodeResultDataBar(SingleDecodeType aReadType, String aCodeText) {#CodeResultDataBar-com.aspose.barcode.barcoderecognition.SingleDecodeType-java.lang.String-}
```
public CodeResultDataBar(SingleDecodeType aReadType, String aCodeText)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aReadType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |
| aCodeText | java.lang.String |  |

### CodeResultDataBar(CodeResultDataBar aResult) {#CodeResultDataBar-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.CodeResultDataBar-}
```
public CodeResultDataBar(CodeResultDataBar aResult)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aResult | [CodeResultDataBar](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult/coderesultdatabar) |  |

### Angle {#Angle}
```
public double Angle
```


### CheckSum {#CheckSum}
```
public String CheckSum
```


### CodeText {#CodeText}
```
public String CodeText
```


### IsRestored {#IsRestored}
```
public boolean IsRestored
```


### Quality {#Quality}
```
public float Quality
```


### ReadType {#ReadType}
```
public SingleDecodeType ReadType
```


### Region {#Region}
```
public QuadPoints Region
```


### is2DCompositeComponent {#is2DCompositeComponent}
```
public boolean is2DCompositeComponent
```


### deepClone() {#deepClone--}
```
public CodeResult deepClone()
```




**Returns:**
[CodeResult](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult/coderesult)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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
### getQuadPoints() {#getQuadPoints--}
```
public QuadPoints getQuadPoints()
```




**Returns:**
[QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDataBarType(BaseDecodeType readType) {#isDataBarType-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean isDataBarType(BaseDecodeType readType)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| readType | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) |  |

**Returns:**
boolean
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

