---
title: GraphicsUnit
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Spécifie l'unité de mesure pour les données fournies.
type: docs
weight: 88
url: /fr/androidjava/com.aspose.barcode.generation/graphicsunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum GraphicsUnit extends Enum<GraphicsUnit>
```

Spécifie l'unité de mesure pour les données fournies.
## Champs

| Champ | Description |
| --- | --- |
| [DISPLAY](#DISPLAY) | Spécifie l'unité de mesure du dispositif d'affichage. |
| [DOCUMENT](#DOCUMENT) | Spécifie l'unité du document (1/300 pouce) comme unité de mesure. |
| [INCH](#INCH) | Spécifie le pouce comme unité de mesure. |
| [MILLIMETER](#MILLIMETER) | Spécifie le millimètre comme unité de mesure. |
| [PIXEL](#PIXEL) | Spécifie un pixel d'appareil comme unité de mesure. |
| [POINT](#POINT) | Spécifie le point d'une imprimante (1/72 pouce) comme unité de mesure. |
| [WORLD](#WORLD) | Spécifie l'unité du système de coordonnées mondial comme unité de mesure. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getGraphicsUnitName(int graphicsUnit)](#getGraphicsUnitName-int-) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DISPLAY {#DISPLAY}
```
public static final GraphicsUnit DISPLAY
```


Spécifie l'unité de mesure du dispositif d'affichage. Typiquement des pixels pour les écrans vidéo, et 1/100 pouce pour les imprimantes.

### DOCUMENT {#DOCUMENT}
```
public static final GraphicsUnit DOCUMENT
```


Spécifie l'unité du document (1/300 pouce) comme unité de mesure.

### INCH {#INCH}
```
public static final GraphicsUnit INCH
```


Spécifie le pouce comme unité de mesure.

### MILLIMETER {#MILLIMETER}
```
public static final GraphicsUnit MILLIMETER
```


Spécifie le millimètre comme unité de mesure.

### PIXEL {#PIXEL}
```
public static final GraphicsUnit PIXEL
```


Spécifie un pixel d'appareil comme unité de mesure.

### POINT {#POINT}
```
public static final GraphicsUnit POINT
```


Spécifie le point d'une imprimante (1/72 pouce) comme unité de mesure.

### WORLD {#WORLD}
```
public static final GraphicsUnit WORLD
```


Spécifie l'unité du système de coordonnées mondial comme unité de mesure.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getGraphicsUnitName(int graphicsUnit) {#getGraphicsUnitName-int-}
```
public static String getGraphicsUnitName(int graphicsUnit)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| graphicsUnit | int |  |

**Returns:**
java.lang.String
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static GraphicsUnit valueOf(String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[GraphicsUnit](../../com.aspose.barcode.generation/graphicsunit)
### values() {#values--}
```
public static GraphicsUnit[] values()
```




**Returns:**
com.aspose.barcode.generation.GraphicsUnit[]
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

