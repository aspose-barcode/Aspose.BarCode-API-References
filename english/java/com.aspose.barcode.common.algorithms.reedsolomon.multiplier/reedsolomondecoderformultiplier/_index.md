---
title: ReedSolomonDecoderForMultiplier
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 11
url: /java/com.aspose.barcode.common.algorithms.reedsolomon.multiplier/reedsolomondecoderformultiplier/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.common.algorithms.reedsolomon.ReedSolomonDecoder](../../com.aspose.barcode.common.algorithms.reedsolomon/reedsolomondecoder)
```
public class ReedSolomonDecoderForMultiplier extends ReedSolomonDecoder
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ReedSolomonDecoderForMultiplier(GaloisField field)](#ReedSolomonDecoderForMultiplier-com.aspose.barcode.common.algorithms.reedsolomon.GaloisField-) |  |
## Methods

| Method | Description |
| --- | --- |
| [correct(int[] received, int eccCount)](#correct-int---int-) |  |
| [correctWithSyndromeRecheck(int[] received, int eccCorrectionCount, int eccCheckCount)](#correctWithSyndromeRecheck-int---int-int-) | Corrects input array by Reed Solomon correction with checking on the fake correction. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ReedSolomonDecoderForMultiplier(GaloisField field) {#ReedSolomonDecoderForMultiplier-com.aspose.barcode.common.algorithms.reedsolomon.GaloisField-}
```
public ReedSolomonDecoderForMultiplier(GaloisField field)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| field | [GaloisField](../../com.aspose.barcode.common.algorithms.reedsolomon/galoisfield) |  |

### correct(int[] received, int eccCount) {#correct-int---int-}
```
public int[] correct(int[] received, int eccCount)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| received | int[] |  |
| eccCount | int |  |

**Returns:**
int[]
### correctWithSyndromeRecheck(int[] received, int eccCorrectionCount, int eccCheckCount) {#correctWithSyndromeRecheck-int---int-int-}
```
public int[] correctWithSyndromeRecheck(int[] received, int eccCorrectionCount, int eccCheckCount)
```


Corrects input array by Reed Solomon correction with checking on the fake correction. For 2/4 correction codewords it is needed to use (full correction bytes) - 2 for eccCorrectionCount and (full correction bytes) for eccCheckCount. For correction codewords which is more then 4 it is possible to use full full correction bytes, probability of false detection(fake) is low.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| received | int[] | Array to correct |
| eccCorrectionCount | int | count of correction bytes which is used for correction. Common value is (full correction bytes) - 2 |
| eccCheckCount | int | count of correction bytes which is used for checking fakes. Common value is (full correction bytes) |

**Returns:**
int[] - corrected array
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

