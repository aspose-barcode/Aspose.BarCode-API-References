---
title: "MailmarkCodetext"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: "Klasse zum Codieren und Dekodieren des im 4‑Stufen‑Royal‑Mailmark‑Code eingebetteten Textes."
type: docs
weight: 24
url: /de/androidjava/com.aspose.barcode.complexbarcode/mailmarkcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class MailmarkCodetext implements IComplexCodetext
```

Klasse zum Codieren und Dekodieren des im 4‑Stufen‑Royal‑Mailmark‑Code eingebetteten Textes.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MailmarkCodetext()](#MailmarkCodetext--) | Initialisiert eine neue Instanz der  MailmarkCodetext  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Liest den Barcode-Typ. |
| [getClass()](#getClass--) |  |
| [getClass_()](#getClass---) | "0" - Null oder Test "1" - 1C (Einzelhandel) "2" - 2C (Einzelhandel) "3" - 3C (Einzelhandel) "4" - Premium (RetailPublishing Mail) (für potenzielle zukünftige Verwendung) "5" - Deferred (Einzelhandel) "6" - Air (Einzelhandel) (für potenzielle zukünftige Verwendung) "7" - Surface (Einzelhandel) (für potenzielle zukünftige Verwendung) "8" - Premium (Netzzugang) "9" - Standard (Netzzugang) |
| [getConstructedCodetext()](#getConstructedCodetext--) | Erstelle Codetext aus Mailmark-Daten. |
| [getDestinationPostCodePlusDPS()](#getDestinationPostCodePlusDPS--) | Der PC und DP müssen dem PAF-Format entsprechen. |
| [getFormat()](#getFormat--) | "0" \\u2013 Null oder Test "1" \\u2013 Brief "2" \\u2013 Großbrief |
| [getItemID()](#getItemID--) | Maximalwert ist 99999999. |
| [getSupplychainID()](#getSupplychainID--) | Maximale Werte sind 99 für Barcode C und 999999 für Barcode L. |
| [getVersionID()](#getVersionID--) | Derzeit "1" \\u2013 Für Mailmark-Barcode (0 und 2 bis 9 sowie A bis Z für zukünftige Verwendung reserviert) |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initialisiert Mailmark-Daten aus konstruiertem Codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClass(String value)](#setClass-java.lang.String-) | "0" - Null oder Test "1" - 1C (Einzelhandel) "2" - 2C (Einzelhandel) "3" - 3C (Einzelhandel) "4" - Premium (RetailPublishing Mail) (für potenzielle zukünftige Verwendung) "5" - Deferred (Einzelhandel) "6" - Air (Einzelhandel) (für potenzielle zukünftige Verwendung) "7" - Surface (Einzelhandel) (für potenzielle zukünftige Verwendung) "8" - Premium (Netzzugang) "9" - Standard (Netzzugang) |
| [setDestinationPostCodePlusDPS(String value)](#setDestinationPostCodePlusDPS-java.lang.String-) | Der PC und DP müssen dem PAF-Format entsprechen. |
| [setFormat(int value)](#setFormat-int-) | "0" \\u2013 Null oder Test "1" \\u2013 Brief "2" \\u2013 Großbrief |
| [setItemID(int value)](#setItemID-int-) | Maximalwert ist 99999999. |
| [setSupplychainID(int value)](#setSupplychainID-int-) | Maximale Werte sind 99 für Barcode C und 999999 für Barcode L. |
| [setVersionID(int value)](#setVersionID-int-) | Derzeit "1" \\u2013 Für Mailmark-Barcode (0 und 2 bis 9 sowie A bis Z für zukünftige Verwendung reserviert) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailmarkCodetext() {#MailmarkCodetext--}
```
public MailmarkCodetext()
```


Initialisiert eine neue Instanz der  MailmarkCodetext  Klasse.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
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
### getClass_() {#getClass---}
```
public String getClass_()
```


"0" - Null oder Test "1" - 1C (Einzelhandel) "2" - 2C (Einzelhandel) "3" - 3C (Einzelhandel) "4" - Premium (RetailPublishing Mail) (für potenzielle zukünftige Verwendung) "5" - Deferred (Einzelhandel) "6" - Air (Einzelhandel) (für potenzielle zukünftige Verwendung) "7" - Surface (Einzelhandel) (für potenzielle zukünftige Verwendung) "8" - Premium (Netzzugang) "9" - Standard (Netzzugang)

**Returns:**
java.lang.String
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Erstelle Codetext aus Mailmark-Daten.

**Returns:**
java.lang.String - Konstruktierter Codetext
### getDestinationPostCodePlusDPS() {#getDestinationPostCodePlusDPS--}
```
public String getDestinationPostCodePlusDPS()
```


Der PC und DP müssen dem PAF-Format entsprechen. Neun Zeichen lange Zeichenkette, die den internationalen "XY11 " (beachten Sie die 5 nachfolgenden Leerzeichen) bezeichnet, oder ein Muster von Zeichen, das einen nationalen Sortiercode bezeichnet. Ein nationaler Sortiercode besteht aus einer Außenpostleitzahl, einer Innenpostleitzahl und einem Lieferpunkt‑Suffix.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public int getFormat()
```


"0" \\u2013 Null oder Test "1" \\u2013 Brief "2" \\u2013 Großbrief

**Returns:**
int
### getItemID() {#getItemID--}
```
public int getItemID()
```


Maximalwert ist 99999999.

**Returns:**
int
### getSupplychainID() {#getSupplychainID--}
```
public int getSupplychainID()
```


Maximale Werte sind 99 für Barcode C und 999999 für Barcode L.

**Returns:**
int
### getVersionID() {#getVersionID--}
```
public int getVersionID()
```


Derzeit "1" \\u2013 Für Mailmark-Barcode (0 und 2 bis 9 sowie A bis Z für zukünftige Verwendung reserviert)

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Initialisiert Mailmark-Daten aus konstruiertem Codetext.

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




### setClass(String value) {#setClass-java.lang.String-}
```
public void setClass(String value)
```


"0" - Null oder Test "1" - 1C (Einzelhandel) "2" - 2C (Einzelhandel) "3" - 3C (Einzelhandel) "4" - Premium (RetailPublishing Mail) (für potenzielle zukünftige Verwendung) "5" - Deferred (Einzelhandel) "6" - Air (Einzelhandel) (für potenzielle zukünftige Verwendung) "7" - Surface (Einzelhandel) (für potenzielle zukünftige Verwendung) "8" - Premium (Netzzugang) "9" - Standard (Netzzugang)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setDestinationPostCodePlusDPS(String value) {#setDestinationPostCodePlusDPS-java.lang.String-}
```
public void setDestinationPostCodePlusDPS(String value)
```


Der PC und DP müssen dem PAF-Format entsprechen. Neun Zeichen lange Zeichenkette, die den internationalen "XY11 " (beachten Sie die 5 nachfolgenden Leerzeichen) bezeichnet, oder ein Muster von Zeichen, das einen nationalen Sortiercode bezeichnet. Ein nationaler Sortiercode besteht aus einer Außenpostleitzahl, einer Innenpostleitzahl und einem Lieferpunkt‑Suffix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setFormat(int value) {#setFormat-int-}
```
public void setFormat(int value)
```


"0" \\u2013 Null oder Test "1" \\u2013 Brief "2" \\u2013 Großbrief

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


Maximalwert ist 99999999.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSupplychainID(int value) {#setSupplychainID-int-}
```
public void setSupplychainID(int value)
```


Maximale Werte sind 99 für Barcode C und 999999 für Barcode L.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setVersionID(int value) {#setVersionID-int-}
```
public void setVersionID(int value)
```


Derzeit "1" \\u2013 Für Mailmark-Barcode (0 und 2 bis 9 sowie A bis Z für zukünftige Verwendung reserviert)

**Parameters:**
| Parameter | Typ | Beschreibung |
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

