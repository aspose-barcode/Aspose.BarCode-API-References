---
title: "HslaColor"
second_title: "Référence API d'Aspose.BarCode pour Java"
description: "Classe pour représenter la couleur HSLA Teinte Saturation Luminosité Alpha"
type: docs
weight: 49
url: /fr/java/com.aspose.barcode.generation/hslacolor/
---
**Inheritance:**
java.lang.Object
```
public class HslaColor
```

Classe représentant la couleur HSLA (Teinte, Saturation, Luminosité, Alpha)
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [HslaColor(int h, int s, int l, float a)](#HslaColor-int-int-int-float-) | Constructeur pour HslaColor |
## Champs

| Champ | Description |
| --- | --- |
| [A](#A) | Alpha (opacité) [0.0f, 1.0f] |
| [H](#H) | Teinte [0, 360] |
| [L](#L) | Luminosité [0, 100] |
| [S](#S) | Saturation [0, 100] |
## Méthodes

| Méthode | Description |
| --- | --- |
| [convertHslaToRgba(HslaColor hslaColor)](#convertHslaToRgba-com.aspose.barcode.generation.HslaColor-) | Utilise https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HslaColor(int h, int s, int l, float a) {#HslaColor-int-int-int-float-}
```
public HslaColor(int h, int s, int l, float a)
```


Constructeur pour HslaColor

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| h | int | Teinte [0, 360] |
| s | int | Saturation [0, 100] |
| l | int | Luminosité [0, 100] |
| a | float | Alpha (opacité) [0.0f, 1.0f] |

### A {#A}
```
public float A
```


Alpha (opacité) [0.0f, 1.0f]

### H {#H}
```
public final int H
```


Teinte [0, 360]

### L {#L}
```
public final int L
```


Luminosité [0, 100]

### S {#S}
```
public final int S
```


Saturation [0, 100]

### convertHslaToRgba(HslaColor hslaColor) {#convertHslaToRgba-com.aspose.barcode.generation.HslaColor-}
```
public static Color convertHslaToRgba(HslaColor hslaColor)
```


Utilise https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| hslaColor | [HslaColor](../../com.aspose.barcode.generation/hslacolor) | Couleur HSLA à convertir |

**Returns:**
java.awt.Color - Couleur avec des valeurs RGBA
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

