---
title: "HanXinParameters"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: "Han Xin-Parameter."
type: docs
weight: 49
url: /de/androidjava/com.aspose.barcode.generation/hanxinparameters/
---
**Inheritance:**
java.lang.Object
```
public class HanXinParameters
```

Han Xin-Parameter.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Erweiterte Kanalinterpretationskennungen. |
| [getEncodeMode()](#getEncodeMode--) | HanXin‑Kodierungsmodus. |
| [getErrorLevel()](#getErrorLevel--) | Stufe der Reed‑Solomon-Fehlerkorrektur für den Han‑Xin‑Barcode. |
| [getVersion()](#getVersion--) | Version des HanXin‑Codes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Erweiterte Kanalinterpretationskennungen. |
| [setEncodeMode(HanXinEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-) | HanXin‑Kodierungsmodus. |
| [setErrorLevel(HanXinErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-) | Stufe der Reed‑Solomon-Fehlerkorrektur für den Han‑Xin‑Barcode. |
| [setVersion(HanXinVersion value)](#setVersion-com.aspose.barcode.generation.HanXinVersion-) | Version des HanXin‑Codes. |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters) zurück. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Extended Channel Interpretation Identifiers. Sie werden verwendet, um dem Barcode-Leser Details zu den verwendeten Referenzen für die Kodierung der Daten im Symbol mitzuteilen. Die aktuelle Implementierung enthält alle bekannten Zeichensatzkodierungen.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final HanXinEncodeMode getEncodeMode()
```


HanXin‑Kodierungsmodus. Standardwert: EncodeMode.Mixed.

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final HanXinErrorLevel getErrorLevel()
```


Stufe der Reed‑Solomon-Fehlerkorrektur für den Han‑Xin‑Barcode. Von niedrig bis hoch: L1, L2, L3, L4. Siehe ErrorLevel.

**Returns:**
[HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel)
### getVersion() {#getVersion--}
```
public final HanXinVersion getVersion()
```


Version des HanXin‑Codes. Von Version01 bis Version84 für den Han‑Xin‑Code. Standardwert ist Version.Auto.

**Returns:**
[HanXinVersion](../../com.aspose.barcode.generation/hanxinversion)
### hashCode() {#hashCode--}
```
public final int hashCode()
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




### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Extended Channel Interpretation Identifiers. Sie werden verwendet, um dem Barcode-Leser Details zu den verwendeten Referenzen für die Kodierung der Daten im Symbol mitzuteilen. Die aktuelle Implementierung enthält alle bekannten Zeichensatzkodierungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setEncodeMode(HanXinEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-}
```
public final void setEncodeMode(HanXinEncodeMode value)
```


HanXin‑Kodierungsmodus. Standardwert: EncodeMode.Mixed.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode) |  |

### setErrorLevel(HanXinErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-}
```
public final void setErrorLevel(HanXinErrorLevel value)
```


Stufe der Reed‑Solomon-Fehlerkorrektur für den Han‑Xin‑Barcode. Von niedrig bis hoch: L1, L2, L3, L4. Siehe ErrorLevel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel) |  |

### setVersion(HanXinVersion value) {#setVersion-com.aspose.barcode.generation.HanXinVersion-}
```
public final void setVersion(HanXinVersion value)
```


Version des HanXin‑Codes. Von Version01 bis Version84 für den Han‑Xin‑Code. Standardwert ist Version.Auto.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [HanXinVersion](../../com.aspose.barcode.generation/hanxinversion) |  |

### toString() {#toString--}
```
public String toString()
```


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters) zurück.

**Returns:**
java.lang.String – Eine Zeichenkette, die dieses [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters) repräsentiert.
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

