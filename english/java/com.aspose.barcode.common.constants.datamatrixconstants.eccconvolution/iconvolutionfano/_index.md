---
title: IConvolutionFano
second_title: Aspose.BarCode for Java API Reference
description: Convolution strategy for a Fano algorithm.
type: docs
weight: 16
url: /java/com.aspose.barcode.common.constants.datamatrixconstants.eccconvolution/iconvolutionfano/
---```
public interface IConvolutionFano
```

Convolution strategy for a Fano algorithm. It is used in the inner convolution algorithms.
## Methods

| Method | Description |
| --- | --- |
| [blockLength()](#blockLength--) |  |
| [continueConvolution(List<Byte> inBytes)](#continueConvolution-java.util.List-java.lang.Byte--) |  |
| [deltaFactor()](#deltaFactor--) |  |
| [doConvolution(List<Byte> inBytes)](#doConvolution-java.util.List-java.lang.Byte--) |  |
| [inBlockLength()](#inBlockLength--) |  |
| [penaltyFactor()](#penaltyFactor--) |  |
| [possibleBlocks()](#possibleBlocks--) |  |
| [stoppageConvolution(List<Byte> inBytes, List<Byte> outBytes)](#stoppageConvolution-java.util.List-java.lang.Byte--java.util.List-java.lang.Byte--) |  |
### blockLength() {#blockLength--}
```
public abstract int blockLength()
```




**Returns:**
int
### continueConvolution(List<Byte> inBytes) {#continueConvolution-java.util.List-java.lang.Byte--}
```
public abstract List<Byte> continueConvolution(List<Byte> inBytes)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inBytes | java.util.List<java.lang.Byte> |  |

**Returns:**
[List](../../java.util/list)
### deltaFactor() {#deltaFactor--}
```
public abstract int deltaFactor()
```




**Returns:**
int
### doConvolution(List<Byte> inBytes) {#doConvolution-java.util.List-java.lang.Byte--}
```
public abstract List<Byte> doConvolution(List<Byte> inBytes)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inBytes | java.util.List<java.lang.Byte> |  |

**Returns:**
[List](../../java.util/list)
### inBlockLength() {#inBlockLength--}
```
public abstract int inBlockLength()
```




**Returns:**
int
### penaltyFactor() {#penaltyFactor--}
```
public abstract int penaltyFactor()
```




**Returns:**
int
### possibleBlocks() {#possibleBlocks--}
```
public abstract List<List<Byte>> possibleBlocks()
```




**Returns:**
[List](../../java.util/list)
### stoppageConvolution(List<Byte> inBytes, List<Byte> outBytes) {#stoppageConvolution-java.util.List-java.lang.Byte--java.util.List-java.lang.Byte--}
```
public abstract void stoppageConvolution(List<Byte> inBytes, List<Byte> outBytes)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inBytes | java.util.List<java.lang.Byte> |  |
| outBytes | java.util.List<java.lang.Byte> |  |

