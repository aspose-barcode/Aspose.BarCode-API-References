---
title: CodeResultCode128
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 14
url: /java/com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult/coderesultcode128/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.CodeResult](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult/coderesult), [com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.CodeResult1D](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult/coderesult1d)
```
public class CodeResultCode128 extends CodeResult1D
```
## Constructors

| Constructor | Description |
| --- | --- |
| [CodeResultCode128()](#CodeResultCode128--) |  |
| [CodeResultCode128(SingleDecodeType aReadType, String aCodeText)](#CodeResultCode128-com.aspose.barcode.barcoderecognition.SingleDecodeType-java.lang.String-) |  |
| [CodeResultCode128(CodeResultCode128 aResult)](#CodeResultCode128-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.CodeResultCode128-) |  |
## Fields

| Field | Description |
| --- | --- |
| [Angle](#Angle) |  |
| [CheckSum](#CheckSum) |  |
| [Code128DataPortions](#Code128DataPortions) |  |
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
### CodeResultCode128() {#CodeResultCode128--}
```
public CodeResultCode128()
```


### CodeResultCode128(SingleDecodeType aReadType, String aCodeText) {#CodeResultCode128-com.aspose.barcode.barcoderecognition.SingleDecodeType-java.lang.String-}
```
public CodeResultCode128(SingleDecodeType aReadType, String aCodeText)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aReadType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |
| aCodeText | java.lang.String |  |

### CodeResultCode128(CodeResultCode128 aResult) {#CodeResultCode128-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.CodeResultCode128-}
```
public CodeResultCode128(CodeResultCode128 aResult)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aResult | [CodeResultCode128](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult/coderesultcode128) |  |

### Angle {#Angle}
```
public double Angle
```


### CheckSum {#CheckSum}
```
public String CheckSum
```


### Code128DataPortions {#Code128DataPortions}
```
public List<Code128DataPortion> Code128DataPortions
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

