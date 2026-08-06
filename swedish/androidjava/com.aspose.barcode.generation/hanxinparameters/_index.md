---
title: HanXinParameters
second_title: Aspose.BarCode for Android via Java API-referens
description: Han Xin-parametrar.
type: docs
weight: 50
url: /sv/androidjava/com.aspose.barcode.generation/hanxinparameters/
---
**Inheritance:**
java.lang.Object
```
public class HanXinParameters
```

Han Xin-parametrar.
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Identifierare för utökad kanalinterpretation. |
| [getEncodeMode()](#getEncodeMode--) | HanXin-kodningsläge. |
| [getErrorLevel()](#getErrorLevel--) | Nivå för Reed-Solomon-felkorrigering för Han Xin-streckkod. |
| [getHanXinECIEncoding()](#getHanXinECIEncoding--) | Identifierare för utökad kanalinterpretation. |
| [getHanXinEncodeMode()](#getHanXinEncodeMode--) | HanXin-kodningsläge. |
| [getHanXinErrorLevel()](#getHanXinErrorLevel--) | Nivå för Reed-Solomon-felkorrigering för Han Xin-streckkod. |
| [getHanXinVersion()](#getHanXinVersion--) | Version av HanXin-kod. |
| [getVersion()](#getVersion--) | Version av HanXin-kod. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identifierare för utökad kanalinterpretation. |
| [setEncodeMode(HanXinEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-) | HanXin-kodningsläge. |
| [setErrorLevel(HanXinErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-) | Nivå för Reed-Solomon-felkorrigering för Han Xin-streckkod. |
| [setVersion(HanXinVersion value)](#setVersion-com.aspose.barcode.generation.HanXinVersion-) | Version av HanXin-kod. |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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


Utökade kanalinterpretationsidentifierare. Det används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Aktuell implementation innehåller alla välkända teckenkodningsuppsättningar.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final HanXinEncodeMode getEncodeMode()
```


HanXin-kodningsläge. Standardvärde: EncodeMode.Mixed.

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final HanXinErrorLevel getErrorLevel()
```


Nivå för Reed-Solomon-felkorrigering för Han Xin-streckkod. Från låg till hög: L1, L2, L3, L4. se ErrorLevel.

**Returns:**
[HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel)
### getHanXinECIEncoding() {#getHanXinECIEncoding--}
```
public final int getHanXinECIEncoding()
```


Utökade kanalinterpretationsidentifierare. Det används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Aktuell implementation innehåller alla välkända teckenkodningsuppsättningar.

**Returns:**
int
### getHanXinEncodeMode() {#getHanXinEncodeMode--}
```
public final HanXinEncodeMode getHanXinEncodeMode()
```


HanXin-kodningsläge. Standardvärde: EncodeMode.Mixed.

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### getHanXinErrorLevel() {#getHanXinErrorLevel--}
```
public final HanXinErrorLevel getHanXinErrorLevel()
```


Nivå för Reed-Solomon-felkorrigering för Han Xin-streckkod. Från låg till hög: L1, L2, L3, L4. se ErrorLevel.

**Returns:**
[HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel)
### getHanXinVersion() {#getHanXinVersion--}
```
public final HanXinVersion getHanXinVersion()
```


Version av HanXin-kod. Från Version01 till Version84 för Han Xin-kod. Standardvärde är Version.Auto.

**Returns:**
[HanXinVersion](../../com.aspose.barcode.generation/hanxinversion)
### getVersion() {#getVersion--}
```
public final HanXinVersion getVersion()
```


Version av HanXin-kod. Från Version01 till Version84 för Han Xin-kod. Standardvärde är Version.Auto.

**Returns:**
[HanXinVersion](../../com.aspose.barcode.generation/hanxinversion)
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




### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Utökade kanalinterpretationsidentifierare. Det används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Aktuell implementation innehåller alla välkända teckenkodningsuppsättningar.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setEncodeMode(HanXinEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-}
```
public final void setEncodeMode(HanXinEncodeMode value)
```


HanXin-kodningsläge. Standardvärde: EncodeMode.Mixed.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode) |  |

### setErrorLevel(HanXinErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-}
```
public final void setErrorLevel(HanXinErrorLevel value)
```


Nivå för Reed-Solomon-felkorrigering för Han Xin-streckkod. Från låg till hög: L1, L2, L3, L4. se ErrorLevel.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel) |  |

### setVersion(HanXinVersion value) {#setVersion-com.aspose.barcode.generation.HanXinVersion-}
```
public final void setVersion(HanXinVersion value)
```


Version av HanXin-kod. Från Version01 till Version84 för Han Xin-kod. Standardvärde är Version.Auto.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [HanXinVersion](../../com.aspose.barcode.generation/hanxinversion) |  |

### toString() {#toString--}
```
public String toString()
```


Returnerar en människoläsbar strängrepresentation av detta [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters).

**Returns:**
java.lang.String - En sträng som representerar detta [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters).
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

