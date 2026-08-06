---
title: DeconvolutionMode
second_title: Aspose.BarCode for Android via Java API-referentie
description: 
type: docs
weight: 55
url: /nl/androidjava/com.aspose.barcode.barcoderecognition/deconvolutionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DeconvolutionMode extends Enum<DeconvolutionMode>
```

Deconvolutie (beeldherstel) modus die het niveau van beelddegradatie definieert. Oorspronkelijk is deconvolutie een functie die een afbeelding kan herstellen die is gedegradeerd (geconvolueerd) door een natuurlijke functie zoals vervaging, tijdens het verkrijgen van een afbeelding met een camera. Omdat we de beeldfunctie die de afbeelding corrumpeert niet kunnen detecteren, moeten we de meest bekende functies controleren, zoals verscherping of wiskundige morfologie.

--------------------

> ```
> This sample shows how to use Deconvolution mode
>   
>   BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   reader.getQualitySettings().setDeconvolution(DeconvolutionMode.SLOW);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println(result.getCodeText());
> ```
## Velden

| Veld | Beschrijving |
| --- | --- |
| [FAST](#FAST) | Schakelt snelle deconvolutiemethoden in voor afbeeldingen van hoge kwaliteit. |
| [NORMAL](#NORMAL) | Schakelt normale deconvolutiemethoden in voor gangbare afbeeldingen. |
| [SLOW](#SLOW) | Schakelt trage deconvolutiemethoden in voor afbeeldingen van lage kwaliteit. |
## Methods

| Method | Beschrijving |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
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
### FAST {#FAST}
```
public static final DeconvolutionMode FAST
```


Schakelt snelle deconvolutiemethoden in voor afbeeldingen van hoge kwaliteit.

### NORMAL {#NORMAL}
```
public static final DeconvolutionMode NORMAL
```


Schakelt normale deconvolutiemethoden in voor gangbare afbeeldingen.

### SLOW {#SLOW}
```
public static final DeconvolutionMode SLOW
```


Schakelt trage deconvolutiemethoden in voor afbeeldingen van lage kwaliteit.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static DeconvolutionMode fromValue(int value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
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
public static DeconvolutionMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### values() {#values--}
```
public static DeconvolutionMode[] values()
```




**Returns:**
com.aspose.barcode.barcoderecognition.DeconvolutionMode[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

