---
title: CodeResult
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult/coderesult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.barcoderecognition.common.algorithms.IQuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/iquadpoints)
```
public class CodeResult implements IQuadPoints
```
## Constructors

| Constructor | Description |
| --- | --- |
| [CodeResult()](#CodeResult--) |  |
| [CodeResult(SingleDecodeType aReadType, String aCodeText)](#CodeResult-com.aspose.barcode.barcoderecognition.SingleDecodeType-java.lang.String-) |  |
| [CodeResult(CodeResult aResult)](#CodeResult-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.CodeResult-) |  |
## Fields

| Field | Description |
| --- | --- |
| [Angle](#Angle) |  |
| [CodeText](#CodeText) |  |
| [IsRestored](#IsRestored) |  |
| [Quality](#Quality) |  |
| [ReadType](#ReadType) |  |
| [Region](#Region) |  |
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getQuadPoints()](#getQuadPoints--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CodeResult() {#CodeResult--}
```
public CodeResult()
```


### CodeResult(SingleDecodeType aReadType, String aCodeText) {#CodeResult-com.aspose.barcode.barcoderecognition.SingleDecodeType-java.lang.String-}
```
public CodeResult(SingleDecodeType aReadType, String aCodeText)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aReadType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |
| aCodeText | java.lang.String |  |

### CodeResult(CodeResult aResult) {#CodeResult-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.CodeResult-}
```
public CodeResult(CodeResult aResult)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aResult | [CodeResult](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult/coderesult) |  |

### Angle {#Angle}
```
public double Angle
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

