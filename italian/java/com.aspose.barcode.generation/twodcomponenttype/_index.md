---
title: "TwoDComponentType"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Tipo di componente 2D  Questo esempio mostra come creare e salvare un'immagine GS1 Composite Bar."
type: docs
weight: 108
url: /it/java/com.aspose.barcode.generation/twodcomponenttype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TwoDComponentType extends Enum<TwoDComponentType>
```

Tipo di componente 2D  Questo esempio mostra come creare e salvare un'immagine GS1 Composite Bar. Nota che il codetext 1D e il codetext 2D sono separati dal simbolo '/' `String codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8"; BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext); generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128); generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A); // Rapporto d'aspetto del componente 2D generator.getParameters().getBarcode().getPdf417().setAspectRatio(3); // Dimensione X dei componenti 1D e 2D generator.getParameters().getBarcode().getXDimension().setPixels(3); // Altezza del componente 1D generator.getParameters().getBarcode().getBarHeight().setPixels(100); generator.save("test.png");`
## Campi

| Campo | Descrizione |
| --- | --- |
| [AUTO](#AUTO) | Seleziona automaticamente il tipo di componente 2D |
| [CC_A](#CC-A) | Tipo di componente 2D CC-A. |
| [CC_B](#CC-B) | Tipo di componente 2D CC-B. |
| [CC_C](#CC-C) | Tipo di componente 2D CC-C. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromValue(int value)](#fromValue-int-) |  |
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


Seleziona automaticamente il tipo di componente 2D

### CC_A {#CC-A}
```
public static final TwoDComponentType CC_A
```


Tipo di componente 2D CC-A. È una variante strutturale di MicroPDF417

### CC_B {#CC-B}
```
public static final TwoDComponentType CC_B
```


Tipo di componente 2D CC-B. È un simbolo MicroPDF417.

### CC_C {#CC-C}
```
public static final TwoDComponentType CC_C
```


Tipo di componente 2D CC-C. È un simbolo PDF417.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static TwoDComponentType fromValue(int value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

**Returns:**
[TwoDComponentType](../../com.aspose.barcode.generation/twodcomponenttype)
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

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
public final native void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

