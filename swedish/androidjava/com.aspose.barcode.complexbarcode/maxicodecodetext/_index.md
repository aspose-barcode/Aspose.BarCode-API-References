---
title: MaxiCodeCodetext
second_title: Aspose.BarCode for Android via Java API-referens
description: Bas‑klass för kodning och avkodning av text som är inbäddad i MaxiCode‑koden.
type: docs
weight: 25
url: /sv/androidjava/com.aspose.barcode.complexbarcode/maxicodecodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public abstract class MaxiCodeCodetext implements IComplexCodetext
```

Bas‑klass för kodning och avkodning av text som är inbäddad i MaxiCode‑koden.

Detta exempel visar hur man avkodar rå MaxiCode‑kodtext till en MaxiCodeCodetext‑instans.

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

| Constructor | Beskrivning |
| --- | --- |
| [MaxiCodeCodetext()](#MaxiCodeCodetext--) |  |
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Hämtar streckkodstyp. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Konstruerar kodtext |
| [getECIEncoding()](#getECIEncoding--) | Gets ECI encoding. |
| [getEncodeMode()](#getEncodeMode--) | Hämtar ett MaxiCode-kodningsläge. |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | Hämtar ett MaxiCode-kodningsläge. |
| [getMode()](#getMode--) | Gets MaxiCode mode. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initierar instans från konstruerad kodtext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Ställer in ECI‑kodning. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Ställer in ett MaxiCode‑kodningsläge. |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Ställer in ett MaxiCode‑kodningsläge. |
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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


Hämtar streckkodstyp.

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


Konstruerar kodtext

**Returns:**
java.lang.String - Konstruerad kodtext
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Hämtar ECI‑kodning. Används när MaxiCodeEncodeMode är Auto. Standardvärde: ISO-8859-1

**Returns:**
int - ECI‑kodning.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Hämtar ett MaxiCode‑kodningsläge. Standardvärde: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeEncodeMode() {#getMaxiCodeEncodeMode--}
```
public final MaxiCodeEncodeMode getMaxiCodeEncodeMode()
```


Hämtar ett MaxiCode‑kodningsläge. Standardvärde: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public abstract int getMode()
```


Gets MaxiCode mode.

**Returns:**
int - MaxiCode‑läge
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


Initierar instans från konstruerad kodtext.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Konstruerad kodtext. |

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


Ställer in ECI‑kodning. Används när MaxiCodeEncodeMode är Auto. Standardvärde: ISO-8859-1

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int | ECI‑kodning. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Ställer in ett MaxiCode‑kodningsläge. Standardvärde: Auto.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | ett MaxiCode‑kodningsläge. |

### setMaxiCodeEncodeMode(MaxiCodeEncodeMode value) {#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)
```


Ställer in ett MaxiCode‑kodningsläge. Standardvärde: Auto.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | ett MaxiCode‑kodningsläge. |

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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

