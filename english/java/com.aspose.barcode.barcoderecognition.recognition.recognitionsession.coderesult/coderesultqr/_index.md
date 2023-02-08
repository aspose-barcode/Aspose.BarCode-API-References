---
title: CodeResultQR
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 20
url: /java/com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult/coderesultqr/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.CodeResult](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult/coderesult), [com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.CodeResult2D](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult/coderesult2d)
```
public class CodeResultQR extends CodeResult2D
```
## Constructors

| Constructor | Description |
| --- | --- |
| [CodeResultQR()](#CodeResultQR--) |  |
| [CodeResultQR(SingleDecodeType aReadType, String aCodeText)](#CodeResultQR-com.aspose.barcode.barcoderecognition.SingleDecodeType-java.lang.String-) |  |
| [CodeResultQR(CodeResultQR aResult)](#CodeResultQR-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.CodeResultQR-) |  |
## Fields

| Field | Description |
| --- | --- |
| [Angle](#Angle) |  |
| [CodeText](#CodeText) |  |
| [IsRestored](#IsRestored) |  |
| [Quality](#Quality) |  |
| [ReadType](#ReadType) |  |
| [Region](#Region) |  |
| [qrStructuredAppendModeBarCodeIndex](#qrStructuredAppendModeBarCodeIndex) |  |
| [qrStructuredAppendModeBarCodesQuantity](#qrStructuredAppendModeBarCodesQuantity) |  |
| [qrStructuredAppendModeParityData](#qrStructuredAppendModeParityData) |  |
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
### CodeResultQR() {#CodeResultQR--}
```
public CodeResultQR()
```


### CodeResultQR(SingleDecodeType aReadType, String aCodeText) {#CodeResultQR-com.aspose.barcode.barcoderecognition.SingleDecodeType-java.lang.String-}
```
public CodeResultQR(SingleDecodeType aReadType, String aCodeText)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aReadType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |
| aCodeText | java.lang.String |  |

### CodeResultQR(CodeResultQR aResult) {#CodeResultQR-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.CodeResultQR-}
```
public CodeResultQR(CodeResultQR aResult)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aResult | [CodeResultQR](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult/coderesultqr) |  |

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


### qrStructuredAppendModeBarCodeIndex {#qrStructuredAppendModeBarCodeIndex}
```
public int qrStructuredAppendModeBarCodeIndex
```


### qrStructuredAppendModeBarCodesQuantity {#qrStructuredAppendModeBarCodesQuantity}
```
public int qrStructuredAppendModeBarCodesQuantity
```


### qrStructuredAppendModeParityData {#qrStructuredAppendModeParityData}
```
public int qrStructuredAppendModeParityData
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

