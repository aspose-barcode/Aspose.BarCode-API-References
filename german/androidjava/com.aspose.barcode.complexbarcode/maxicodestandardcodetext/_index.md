---
title: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: "Klasse zum Kodieren und Dekodieren von MaxiCode-Codetext für die Modi 4, 5 und 6."
type: docs
weight: 29
url: /de/androidjava/com.aspose.barcode.complexbarcode/maxicodestandardcodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext)
```
public class MaxiCodeStandardCodetext extends MaxiCodeCodetext
```

Klasse zum Codieren und Dekodieren des MaxiCode‑Codetextes für die Modi 4, 5 und 6.

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
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MaxiCodeStandardCodetext()](#MaxiCodeStandardCodetext--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen MaxiCodeStandardCodetext-Wert entspricht. |
| [getBarcodeType()](#getBarcodeType--) | Liest den Barcode-Typ. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Erstellt Codetext |
| [getECIEncoding()](#getECIEncoding--) | Liest die ECI-Kodierung. |
| [getEncodeMode()](#getEncodeMode--) | Ermittelt einen MaxiCode-Kodierungsmodus. |
| [getMessage()](#getMessage--) | Liest die Nachricht. |
| [getMode()](#getMode--) | Liest den MaxiCode-Modus. |
| [hashCode()](#hashCode--) | Gibt den Hashcode für diese Instanz zurück. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initialisiert die Instanz aus dem konstruierten Codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Setzt die ECI-Kodierung. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Setzt einen MaxiCode-Kodiermodus. |
| [setMessage(String value)](#setMessage-java.lang.String-) | Setzt die Nachricht. |
| [setMode(MaxiCodeMode mode)](#setMode-com.aspose.barcode.generation.MaxiCodeMode-) | Setzt den MaxiCode-Modus. |
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


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen MaxiCodeStandardCodetext-Wert entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Ein MaxiCodeStandardCodetext-Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolean - wenn obj denselben Wert wie diese Instanz hat; andernfalls **false**.
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


Liest den Barcode-Typ.

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


Erstellt Codetext

**Returns:**
java.lang.String - Konstruktierter Codetext
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Liest die ECI-Kodierung. Wird verwendet, wenn MaxiCodeEncodeMode auf Auto steht. Standardwert: ISO-8859-1

**Returns:**
int - ECI-Kodierung.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Liest einen MaxiCode-Kodiermodus. Standardwert: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMessage() {#getMessage--}
```
public String getMessage()
```


Liest die Nachricht.

**Returns:**
java.lang.String
### getMode() {#getMode--}
```
public MaxiCodeMode getMode()
```


Liest den MaxiCode-Modus.

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) - MaxiCode mode
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese Instanz zurück.

**Returns:**
int – ein 32‑Bit vorzeichenbehafteter Ganzzahl-Hashcode
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Initialisiert die Instanz aus dem konstruierten Codetext.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Konstruktierter Codetext. |

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


Setzt die ECI-Kodierung. Wird verwendet, wenn MaxiCodeEncodeMode auf Auto steht. Standardwert: ISO-8859-1

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | ECI-Kodierung. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Setzt einen MaxiCode-Kodiermodus. Standardwert: Auto.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | ein MaxiCode-Kodiermodus. |

### setMessage(String value) {#setMessage-java.lang.String-}
```
public void setMessage(String value)
```


Setzt die Nachricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setMode(MaxiCodeMode mode) {#setMode-com.aspose.barcode.generation.MaxiCodeMode-}
```
public void setMode(MaxiCodeMode mode)
```


Setzt den MaxiCode-Modus. Standard‑Codetext kann nur mit den Modi 4, 5 und 6 verwendet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mode | [MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

