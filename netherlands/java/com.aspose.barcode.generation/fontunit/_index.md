---
title: "FontUnit"
second_title: "Aspose.BarCode for Java API-referentie"
description: "Definieert een specifiek formaat voor tekst, inclusief lettertypegrootte en stijlkenmerken, waarbij de grootte in de eigenschap Unit‑waarde wordt opgegeven."
type: docs
weight: 42
url: /nl/java/com.aspose.barcode.generation/fontunit/
---
**Inheritance:**
java.lang.Object
```
public final class FontUnit
```

Definieert een specifiek formaat voor tekst, inclusief lettertype, grootte en stijlkenmerken waarbij de grootte in de Unit value‑eigenschap staat.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>          BarCodeGenerator generator = new BarCodeGenerator(EncodeTypes.CODE_128);
>          generator.getCodeTextStyle().getFont().setStyle(FontStyle.ITALIC);
>          generator.getCodeTextStyle().getFont().getSize().setPoint(18);
>          generator.save("test.png");
> ```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFamilyName()](#getFamilyName--) | Haalt de naam van het lettertype op van dit Font. |
| [getSize()](#getSize--) | Haalt de grootte van deze FontUnit op in Unit‑waarde. |
| [getStyle()](#getStyle--) | Haalt stijl‑informatie op voor deze FontUnit. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | Stelt de naam van het lettertype in voor dit Font. |
| [setStyle(int value)](#setStyle-int-) | Stelt stijl‑informatie in voor deze FontUnit. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Haalt de naam van het lettertype op van dit Font.

**Returns:**
java.lang.String
### getSize() {#getSize--}
```
public Unit getSize()
```


Haalt de grootte van deze FontUnit op in Unit‑waarde.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getStyle() {#getStyle--}
```
public int getStyle()
```


Haalt stijl‑informatie op voor deze FontUnit.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
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




### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public void setFamilyName(String value)
```


Stelt de naam van het lettertype in voor dit Font.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


Stelt stijl‑informatie in voor deze FontUnit.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

