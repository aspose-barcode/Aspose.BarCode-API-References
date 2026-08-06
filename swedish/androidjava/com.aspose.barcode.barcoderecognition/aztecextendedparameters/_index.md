---
title: AztecExtendedParameters
second_title: Aspose.BarCode for Android via Java API-referens
description: Lagrar speciella data för Aztec‑igenkänd streckkod
type: docs
weight: 12
url: /sv/androidjava/com.aspose.barcode.barcoderecognition/aztecextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class AztecExtendedParameters extends BaseExtendedParameters
```

Lagrar speciella data för Aztec‑igenkänd streckkod

--------------------

> ```
> This sample shows how to get Aztec raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345");
>  generator.save("c:\\test.png");
> 
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.AZTEC);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode type: " + result.getCodeTypeName());
>      System.out.println("BarCode codetext: " + result.getCodeText());
>      System.out.println("Aztec barcode ID: " + result.getExtended.getAztec.getStructuredAppendBarcodeId());
>      System.out.println("Aztec barcodes count: " + result.getExtended.getAztec.getStructuredAppendBarcodesCount());
>      System.out.println("Aztec file ID: " + result.getExtended.getAztec.getStructuredAppendFileId());
>      System.out.println("Aztec is reader initialization: " + result.getExtended.getAztec.isReaderInitialization());
>  }
> ```
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat  AztecExtendedParameters  värde. |
| [getClass()](#getClass--) |  |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Hämtar ID för Aztec structured append mode streckkod. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Hämtar antalet streckkoder för Aztec structured append mode. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Hämtar fil-ID för Aztec structured append mode. |
| [hashCode()](#hashCode--) | Returnerar hash‑koden för detta objekt. |
| [isEmpty()](#isEmpty--) | Testar om alla parametrar endast har standardvärden |
| [isReaderInitialization()](#isReaderInitialization--) | Anger om koden används för att instruera läsaren att tolka följande data som instruktioner för initiering eller omprogrammering av streckkodsläsaren. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta  AztecExtendedParameters . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat  AztecExtendedParameters  värde.

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
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public int getStructuredAppendBarcodeId()
```


Hämtar ID för Aztec structured append mode streckkod. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärdet är 0.

Värde: Streckkodens ID för Aztec structured append mode.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public int getStructuredAppendBarcodesCount()
```


Hämtar antalet streckkoder för Aztec structured append mode. Standardvärdet är 0. Antalet måste vara ett värde mellan 1 och 26.

Värde: Antalet streckkoder för Aztec structured append mode.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public String getStructuredAppendFileId()
```


Hämtar fil-ID för Aztec structured append mode. Standardvärdet är en tom sträng

Värde: Fil-ID för Aztec structured append mode.

**Returns:**
java.lang.String
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
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


Anger om koden används för att instruera läsaren att tolka följande data som instruktioner för initiering eller omprogrammering av streckkodsläsaren. Standardvärdet är false.

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


Returnerar en människoläsbar strängrepresentation av detta  AztecExtendedParameters .

**Returns:**
java.lang.String - En sträng som representerar detta  AztecExtendedParameters .
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

