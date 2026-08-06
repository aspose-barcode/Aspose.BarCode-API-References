---
title: Code128ExtendedParameters
second_title: Aspose.BarCode for Android via Java API-referens
description: Lagrar speciella data för Code128 igenkänd streckkod
type: docs
weight: 28
url: /sv/androidjava/com.aspose.barcode.barcoderecognition/code128extendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class Code128ExtendedParameters extends BaseExtendedParameters
```

Lagrar speciella data för Code128 igenkänd streckkod

Representerar den igenkända streckkodens region och streckkodsvinkel

--------------------

> ```
> This sample shows how to get code128 raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>     System.out.println("Code128 Data Portions: " + result.getExtended().getCode128());
>  }
> ```
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om denna instans är lika med ett specificerat  Code128ExtendedParameters  värde. |
| [getClass()](#getClass--) |  |
| [getCode128DataPortions()](#getCode128DataPortions--) | Hämtar  Code128DataPortion  array av igenkända Code128-streckkoder |
| [hashCode()](#hashCode--) | Returnerar hash‑koden för detta objekt. |
| [isEmpty()](#isEmpty--) | Testar om alla parametrar endast har standardvärden |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta  Code128ExtendedParameters . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returnerar ett värde som indikerar om denna instans är lika med ett specificerat  Code128ExtendedParameters  värde.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Ett System.Object‑värde att jämföra med detta objekt. |

**Returns:**
boolean -  **true**  om obj har samma värde som detta objekt; annars,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCode128DataPortions() {#getCode128DataPortions--}
```
public Code128DataPortion[] getCode128DataPortions()
```


Hämtar  Code128DataPortion  array av igenkända Code128-streckkoder

Värde: Array av  Code128DataPortion .

**Returns:**
com.aspose.barcode.barcoderecognition.Code128DataPortion[]
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hash‑koden för detta objekt.

**Returns:**
int - En 32‑bitars signerad heltals‑hashkod.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Testar om alla parametrar endast har standardvärden

Värde: Returnerar  **true**  om alla parametrar endast har standardvärden; annars,  **false** .

**Returns:**
boolean
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


Returnerar en människoläsbar strängrepresentation av detta  Code128ExtendedParameters .

**Returns:**
java.lang.String - En sträng som representerar detta  Code128ExtendedParameters .
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

