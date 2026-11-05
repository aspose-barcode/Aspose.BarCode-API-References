---
title: "Unité"
second_title: "Référence d'API Aspose.BarCode pour Android via Java"
description: "Spécifie la valeur de taille dans différentes unités Pixel, Pouces, etc.."
type: docs
weight: 67
url: /fr/androidjava/com.aspose.barcode.generation/unit/
---
**Inheritance:**
java.lang.Object
```
public final class Unit
```

Spécifie la valeur de taille dans différentes unités (pixels, pouces, etc.).

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>  	  generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
>     generator.save("test.png");
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Unit(Unit source)](#Unit-com.aspose.barcode.generation.Unit-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si cette instance et un objet spécifié, qui doit également être un objet  Unit , ont la même valeur. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Obtient la valeur de taille en unités du document. |
| [getInches()](#getInches--) | Obtient la valeur de taille en pouces. |
| [getMillimeters()](#getMillimeters--) | Obtient la valeur de taille en millimètres. |
| [getPixels()](#getPixels--) | Obtient la valeur de taille en pixels. |
| [getPoint()](#getPoint--) | Obtient la valeur de taille en point. |
| [getResolution()](#getResolution--) |  |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cet objet. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDocument(float value)](#setDocument-float-) | Définit la valeur de taille en unités du document. |
| [setInches(float value)](#setInches-float-) | Définit la valeur de taille en pouces. |
| [setMillimeters(float value)](#setMillimeters-float-) | Définit la valeur de taille en millimètres. |
| [setPixels(float value)](#setPixels-float-) | Définit la valeur de taille en pixels. |
| [setPoint(float value)](#setPoint-float-) | Définit la valeur de taille en point. |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible par l'homme de cet  Unit . |
| [updateResolution(float dpi)](#updateResolution-float-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Unit(Unit source) {#Unit-com.aspose.barcode.generation.Unit-}
```
public Unit(Unit source)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [Unit](../../com.aspose.barcode.generation/unit) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si cette instance et un objet spécifié, qui doit également être un objet  Unit , ont la même valeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'  Unit  à comparer à cette instance. |

**Returns:**
booléen - vrai si obj est un  Unit  et que sa valeur est identique à celle de cette instance ; sinon, faux. Si obj est nul, la méthode renvoie faux.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDocument() {#getDocument--}
```
public float getDocument()
```


Obtient la valeur de taille en unités du document.

**Returns:**
float
### getInches() {#getInches--}
```
public float getInches()
```


Obtient la valeur de taille en pouces.

**Returns:**
float
### getMillimeters() {#getMillimeters--}
```
public float getMillimeters()
```


Obtient la valeur de taille en millimètres.

**Returns:**
float
### getPixels() {#getPixels--}
```
public float getPixels()
```


Obtient la valeur de taille en pixels.

**Returns:**
float
### getPoint() {#getPoint--}
```
public float getPoint()
```


Obtient la valeur de taille en point.

**Returns:**
float
### getResolution() {#getResolution--}
```
public float getResolution()
```




**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie le code de hachage pour cet objet.

**Returns:**
int - Un code de hachage entier signé de 32 bits.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDocument(float value) {#setDocument-float-}
```
public void setDocument(float value)
```


Définit la valeur de taille en unités du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setInches(float value) {#setInches-float-}
```
public void setInches(float value)
```


Définit la valeur de taille en pouces.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setMillimeters(float value) {#setMillimeters-float-}
```
public void setMillimeters(float value)
```


Définit la valeur de taille en millimètres.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setPixels(float value) {#setPixels-float-}
```
public void setPixels(float value)
```


Définit la valeur de taille en pixels.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setPoint(float value) {#setPoint-float-}
```
public void setPoint(float value)
```


Définit la valeur de taille en point.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne lisible par l'homme de cet  Unit .

**Returns:**
java.lang.String - Une chaîne qui représente ce  Unit .
### updateResolution(float dpi) {#updateResolution-float-}
```
public void updateResolution(float dpi)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dpi | float |  |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

