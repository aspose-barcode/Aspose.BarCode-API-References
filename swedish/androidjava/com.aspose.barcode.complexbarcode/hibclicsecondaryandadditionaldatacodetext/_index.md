---
title: HIBCLICSecondaryAndAdditionalDataCodetext
second_title: Aspose.BarCode for Android via Java API-referens
description: Klass för kodning och avkodning av text som är inbäddad i HIBC LIC‑koden som lagrar sekundära data.
type: docs
weight: 17
url: /sv/androidjava/com.aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.HIBCLICComplexCodetext](../../com.aspose.barcode.complexbarcode/hibcliccomplexcodetext)
```
public class HIBCLICSecondaryAndAdditionalDataCodetext extends HIBCLICComplexCodetext
```

Klass för kodning och avkodning av text som är inbäddad i HIBC LIC‑koden som lagrar sekundära data.
## Constructors

| Constructor | Beskrivning |
| --- | --- |
| [HIBCLICSecondaryAndAdditionalDataCodetext()](#HIBCLICSecondaryAndAdditionalDataCodetext--) |  |
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat HIBCLICSecondaryAndAdditionalDataCodetext‑värde. |
| [getBarcodeType()](#getBarcodeType--) | Hämtar eller anger streckkodstyp. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Konstruerar kodtext |
| [getData()](#getData--) | Identifierar sekundär och ytterligare kompletterande data. |
| [getLinkCharacter()](#getLinkCharacter--) | Identifierar länktecken. |
| [hashCode()](#hashCode--) | Returnerar hash‑koden för detta objekt. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initierar instans från konstruerad kodtext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Hämtar eller anger streckkodstyp. |
| [setData(SecondaryAndAdditionalData value)](#setData-com.aspose.barcode.complexbarcode.SecondaryAndAdditionalData-) | Identifierar sekundär och ytterligare kompletterande data. |
| [setLinkCharacter(char value)](#setLinkCharacter-char-) | Identifierar länktecken. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIBCLICSecondaryAndAdditionalDataCodetext() {#HIBCLICSecondaryAndAdditionalDataCodetext--}
```
public HIBCLICSecondaryAndAdditionalDataCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat HIBCLICSecondaryAndAdditionalDataCodetext‑värde.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Ett  HIBCLICSecondaryAndAdditionalDataCodetext  värde att jämföra med detta objekt. |

**Returns:**
boolean -  **true**  om obj har samma värde som detta objekt; annars,  **false** .
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Hämtar eller anger streckkodstyp. HIBC LIC codetext kan kodas med HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC och HIBCQRLIC kodningstyper. Standardvärde: HIBCCode39LIC.

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
### getData() {#getData--}
```
public SecondaryAndAdditionalData getData()
```


Identifierar sekundär och ytterligare kompletterande data.

**Returns:**
[SecondaryAndAdditionalData](../../com.aspose.barcode.complexbarcode/secondaryandadditionaldata)
### getLinkCharacter() {#getLinkCharacter--}
```
public char getLinkCharacter()
```


Identifierar länktecken.

**Returns:**
char
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hash‑koden för detta objekt.

**Returns:**
int - En 32‑bitars signerad heltals‑hashkod.
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




### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


Hämtar eller anger streckkodstyp. HIBC LIC codetext kan kodas med HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC och HIBCQRLIC kodningstyper. Standardvärde: HIBCCode39LIC.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setData(SecondaryAndAdditionalData value) {#setData-com.aspose.barcode.complexbarcode.SecondaryAndAdditionalData-}
```
public void setData(SecondaryAndAdditionalData value)
```


Identifierar sekundär och ytterligare kompletterande data.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [SecondaryAndAdditionalData](../../com.aspose.barcode.complexbarcode/secondaryandadditionaldata) |  |

### setLinkCharacter(char value) {#setLinkCharacter-char-}
```
public void setLinkCharacter(char value)
```


Identifierar länktecken.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | char |  |

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

