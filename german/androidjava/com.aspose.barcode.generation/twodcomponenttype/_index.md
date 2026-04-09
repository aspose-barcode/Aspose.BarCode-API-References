---
title: TwoDComponentType
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Type of 2D component  This sample shows how to create and save a GS1 Composite Bar image.
type: docs
weight: 110
url: /de/androidjava/com.aspose.barcode.generation/twodcomponenttype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TwoDComponentType extends Enum<TwoDComponentType>
```

Typ der 2D-Komponente  Dieses Beispiel zeigt, wie man ein GS1 Composite Bar-Bild erstellt und speichert. Beachten Sie, dass 1D‑Codetext und 2D‑Codetext durch das Symbol '/' getrennt sind `String codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8"; BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext); generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128); generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A); // Aspect ratio of 2D component generator.getParameters().getBarcode().getPdf417().setAspectRatio(3); // X-Dimension of 1D and 2D components generator.getParameters().getBarcode().getXDimension().setPixels(3); // Height of 1D component generator.getParameters().getBarcode().getBarHeight().setPixels(100); generator.save("test.png");`
## Felder

| Feld | Beschreibung |
| --- | --- |
| [AUTO](#AUTO) | Automatische Auswahl des Typs der 2D-Komponente |
| [CC_A](#CC-A) | CC-A Typ der 2D-Komponente. |
| [CC_B](#CC-B) | CC-B Typ der 2D-Komponente. |
| [CC_C](#CC-C) | CC-C Typ der 2D-Komponente. |
## Methods

| Method | Beschreibung |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
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
### AUTO {#AUTO}
```
public static final TwoDComponentType AUTO
```


Automatische Auswahl des Typs der 2D-Komponente

### CC_A {#CC-A}
```
public static final TwoDComponentType CC_A
```


CC-A Typ einer 2D-Komponente. Es ist eine strukturelle Variante von MicroPDF417

### CC_B {#CC-B}
```
public static final TwoDComponentType CC_B
```


CC-B Typ einer 2D-Komponente. Es ist ein MicroPDF417‑Symbol.

### CC_C {#CC-C}
```
public static final TwoDComponentType CC_C
```


CC-C Typ einer 2D-Komponente. Es ist ein PDF417‑Symbol.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
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
| Parameter | Type | Beschreibung |
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
| Parameter | Type | Beschreibung |
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
public static TwoDComponentType valueOf(String name)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[TwoDComponentType](../../com.aspose.barcode.generation/twodcomponenttype)
### values() {#values--}
```
public static TwoDComponentType[] values()
```




**Returns:**
com.aspose.barcode.generation.TwoDComponentType[]
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

