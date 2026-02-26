---
title: MaxiCodeCodetext
second_title: Aspose.BarCode for Android via Java API Reference
description: Base class for encoding and decoding the text embedded in the MaxiCode code.
type: docs
weight: 25
url: /androidjava/com.aspose.barcode.complexbarcode/maxicodecodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public abstract class MaxiCodeCodetext implements IComplexCodetext
```

Base class for encoding and decoding the text embedded in the MaxiCode code.

This sample shows how to decode raw MaxiCode codetext to MaxiCodeCodetext instance.

```

 BarCodeReader reader = new BarCodeReader("test.png", DecodeType.MAXI_CODE);
 for (BarCodeResult result : reader.readBarCodes())
 {
      MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMode(), result.getCodeText());
      System.out.println("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
      System.out.println("MaxiCode mode: " + resultMaxiCodeCodetext.getMode());
      System.out.println("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [MaxiCodeCodetext()](#MaxiCodeCodetext--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Gets barcode type. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Constructs codetext |
| [getECIEncoding()](#getECIEncoding--) | Gets ECI encoding. |
| [getEncodeMode()](#getEncodeMode--) | Gets a MaxiCode encode mode. |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | Gets a MaxiCode encode mode. |
| [getMode()](#getMode--) | Gets MaxiCode mode. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initializes instance from constructed codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Sets ECI encoding. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Sets a MaxiCode encode mode. |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Sets a MaxiCode encode mode. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeCodetext() {#MaxiCodeCodetext--}
```
public MaxiCodeCodetext()
```


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
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


Gets barcode type.

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


Constructs codetext

**Returns:**
java.lang.String - Constructed codetext
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Gets ECI encoding. Used when MaxiCodeEncodeMode is Auto. Default value: ISO-8859-1

**Returns:**
int - ECI encoding.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Gets a MaxiCode encode mode. Default value: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeEncodeMode() {#getMaxiCodeEncodeMode--}
```
public final MaxiCodeEncodeMode getMaxiCodeEncodeMode()
```


Gets a MaxiCode encode mode. Default value: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public abstract int getMode()
```


Gets MaxiCode mode.

**Returns:**
int - MaxiCode mode
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


Initializes instance from constructed codetext.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Constructed codetext. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Sets ECI encoding. Used when MaxiCodeEncodeMode is Auto. Default value: ISO-8859-1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ECI encoding. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Sets a MaxiCode encode mode. Default value: Auto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | a MaxiCode encode mode. |

### setMaxiCodeEncodeMode(MaxiCodeEncodeMode value) {#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)
```


Sets a MaxiCode encode mode. Default value: Auto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | a MaxiCode encode mode. |

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

