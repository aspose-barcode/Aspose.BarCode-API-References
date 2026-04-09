---
title: MaxiCodeStructuredCodetext
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Basisklasse zum Codieren und Dekodieren des im MaxiCode‑Code für die Modi 2 und 3 eingebetteten Textes.
type: docs
weight: 32
url: /de/androidjava/com.aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext)
```
public abstract class MaxiCodeStructuredCodetext extends MaxiCodeCodetext
```

Base class for encoding and decoding the text embedded in the MaxiCode code for modes 2 and 3. This sample shows how to decode raw MaxiCode codetext to MaxiCodeStructuredCodetext instance.

```
BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MAXI_CODE);
  for (BarCodeResult result : reader.readBarCodes())
  {
      MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
      if (resultMaxiCodeCodetext instanceof MaxiCodeStructuredCodetext)
      {
          MaxiCodeStructuredCodetext maxiCodeStructuredCodetext = (MaxiCodeStructuredCodetext)resultMaxiCodeCodetext;
          System.out.println("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
          System.out.println("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
          System.out.println("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
      }
  }
```
## Constructors

| Constructor | Beschreibung |
| --- | --- |
| [MaxiCodeStructuredCodetext()](#MaxiCodeStructuredCodetext--) |  |
## Methods

| Method | Beschreibung |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Returns a value indicating whether this instance is equal to a specified MaxiCodeStructuredCodetext value. |
| [getBarcodeType()](#getBarcodeType--) | Liefert den Barcode-Typ. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Erstellt Codetext. |
| [getCountryCode()](#getCountryCode--) | Identifies 3 digit country code. |
| [getECIEncoding()](#getECIEncoding--) | Gets ECI encoding. |
| [getEncodeMode()](#getEncodeMode--) | Gibt einen MaxiCode-Kodierungsmodus zurück. |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | Gibt einen MaxiCode-Kodierungsmodus zurück. |
| [getMode()](#getMode--) | Gets MaxiCode mode. |
| [getPostalCode()](#getPostalCode--) | Identifies the postal code. |
| [getSecondMessage()](#getSecondMessage--) | Identifies second message of the barcode. |
| [getServiceCategory()](#getServiceCategory--) | Identifies 3 digit service category. |
| [hashCode()](#hashCode--) | Gibt den Hashcode für diese Instanz zurück. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initialisiert die Instanz aus dem erstellten Codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCountryCode(int value)](#setCountryCode-int-) | Identifies 3 digit country code. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Setzt die ECI-Codierung. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Setzt einen MaxiCode-Codierungsmodus. |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Setzt einen MaxiCode-Codierungsmodus. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Identifies the postal code. |
| [setSecondMessage(MaxiCodeSecondMessage value)](#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-) | Identifies second message of the barcode. |
| [setServiceCategory(int value)](#setServiceCategory-int-) | Identifies 3 digit service category. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeStructuredCodetext() {#MaxiCodeStructuredCodetext--}
```
public MaxiCodeStructuredCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returns a value indicating whether this instance is equal to a specified MaxiCodeStructuredCodetext value.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Ein MaxiCodeStructuredCodetext-Wert zum Vergleich mit dieser Instanz |

**Returns:**
boolescher Wert - **true** wenn obj denselben Wert wie diese Instanz hat; andernfalls **false**
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


Liefert den Barcode-Typ.

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


Erstellt Codetext.

**Returns:**
java.lang.String – konstruierter Codetext
### getCountryCode() {#getCountryCode--}
```
public int getCountryCode()
```


Identifies 3 digit country code.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Liest die ECI-Codierung. Wird verwendet, wenn MaxiCodeEncodeMode auf Auto steht. Standardwert: ISO-8859-1

**Returns:**
int - ECI-Codierung.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Liest einen MaxiCode-Codierungsmodus. Standardwert: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeEncodeMode() {#getMaxiCodeEncodeMode--}
```
public final MaxiCodeEncodeMode getMaxiCodeEncodeMode()
```


Liest einen MaxiCode-Codierungsmodus. Standardwert: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public abstract int getMode()
```


Gets MaxiCode mode.

**Returns:**
int - MaxiCode-Modus
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


Identifiziert die Postleitzahl. Muss 9 Ziffern im Modus 2 oder 6 alphanumerische Zeichen im Modus 3 sein.

**Returns:**
java.lang.String
### getSecondMessage() {#getSecondMessage--}
```
public MaxiCodeSecondMessage getSecondMessage()
```


Identifies second message of the barcode.

**Returns:**
[MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage)
### getServiceCategory() {#getServiceCategory--}
```
public int getServiceCategory()
```


Identifies 3 digit service category.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese Instanz zurück.

**Returns:**
int - Ein 32-Bit vorzeichenbehafteter Ganzzahl-Hashcode.
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Initialisiert die Instanz aus dem erstellten Codetext.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Konstruiertes Codetext. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCountryCode(int value) {#setCountryCode-int-}
```
public void setCountryCode(int value)
```


Identifies 3 digit country code.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Setzt die ECI-Codierung. Wird verwendet, wenn MaxiCodeEncodeMode auf Auto steht. Standardwert: ISO-8859-1

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int | ECI-Codierung. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Setzt einen MaxiCode-Codierungsmodus. Standardwert: Auto.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | ein MaxiCode-Codierungsmodus. |

### setMaxiCodeEncodeMode(MaxiCodeEncodeMode value) {#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)
```


Setzt einen MaxiCode-Codierungsmodus. Standardwert: Auto.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | ein MaxiCode-Codierungsmodus. |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


Identifiziert die Postleitzahl. Muss 9 Ziffern im Modus 2 oder 6 alphanumerische Zeichen im Modus 3 sein.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setSecondMessage(MaxiCodeSecondMessage value) {#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-}
```
public void setSecondMessage(MaxiCodeSecondMessage value)
```


Identifies second message of the barcode.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage) |  |

### setServiceCategory(int value) {#setServiceCategory-int-}
```
public void setServiceCategory(int value)
```


Identifies 3 digit service category.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

