---
title: MaxiCodeStandardCodetext
second_title: Aspose.BarCode for Android via Java API-referens
description: Klass för kodning och avkodning av MaxiCode‑kodtext för lägena 4, 5 och 6.
type: docs
weight: 29
url: /sv/androidjava/com.aspose.barcode.complexbarcode/maxicodestandardcodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext)
```
public class MaxiCodeStandardCodetext extends MaxiCodeCodetext
```

Klass för kodning och avkodning av MaxiCode‑kodtext för lägena 4, 5 och 6.

```
//Mode 4
 MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
 maxiCodeCodetext.setMode(MaxiCodeMode.MODE_4);
 maxiCodeCodetext.setMessage("Test message");
 ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
 complexGenerator.generateBarCodeImage();

 //Mode 5
 MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
 maxiCodeCodetext.setMode(MaxiCodeMode.MODE_5);
 maxiCodeCodetext.setMessage("Test message");
 ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
 complexGenerator.generateBarCodeImage();

 //Mode 6
 MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
 maxiCodeCodetext.setMode(MaxiCodeMode.MODE_6);
 maxiCodeCodetext.setMessage("Test message");
 ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
 complexGenerator.generateBarCodeImage();
```
## Constructors

| Constructor | Beskrivning |
| --- | --- |
| [MaxiCodeStandardCodetext()](#MaxiCodeStandardCodetext--) |  |
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om detta objekt är lika med ett angivet MaxiCodeStandardCodetext‑värde. |
| [getBarcodeType()](#getBarcodeType--) | Hämtar streckkodstyp. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Konstruerar kodtext |
| [getECIEncoding()](#getECIEncoding--) | Gets ECI encoding. |
| [getEncodeMode()](#getEncodeMode--) | Hämtar ett MaxiCode-kodningsläge. |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | Hämtar ett MaxiCode-kodningsläge. |
| [getMessage()](#getMessage--) | Hämtar meddelandet. |
| [getMode()](#getMode--) | Gets MaxiCode mode. |
| [hashCode()](#hashCode--) | Returnerar hash‑koden för detta objekt. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initierar instans från konstruerad kodtext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Ställer in ECI‑kodning. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Ställer in ett MaxiCode‑kodningsläge. |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Ställer in ett MaxiCode‑kodningsläge. |
| [setMessage(String value)](#setMessage-java.lang.String-) | Ställer in meddelandet. |
| [setMode(int mode)](#setMode-int-) | Ställer in MaxiCode‑läge. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeStandardCodetext() {#MaxiCodeStandardCodetext--}
```
public MaxiCodeStandardCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returnerar ett värde som indikerar om detta objekt är lika med ett angivet MaxiCodeStandardCodetext‑värde.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Ett MaxiCodeStandardCodetext‑värde att jämföra med detta objekt. |

**Returns:**
boolean - om obj har samma värde som detta objekt; annars, **false**.
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
public String getConstructedCodetext()
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
### getMessage() {#getMessage--}
```
public String getMessage()
```


Hämtar meddelandet.

**Returns:**
java.lang.String
### getMode() {#getMode--}
```
public int getMode()
```


Gets MaxiCode mode.

**Returns:**
int - MaxiCode‑läge
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hash‑koden för detta objekt.

**Returns:**
int - En 32‑bit signerad heltals‑hashkod
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
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

### setMessage(String value) {#setMessage-java.lang.String-}
```
public void setMessage(String value)
```


Ställer in meddelandet.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setMode(int mode) {#setMode-int-}
```
public void setMode(int mode)
```


Ställer in MaxiCode‑läge. Standardkodtext kan endast användas med lägena 4, 5 och 6.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| läge | int |  |

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

