---
title: DataMatrixExtendedParameters
second_title: Aspose.BarCode for Android via Java API-referens
description: Lagrar speciella data för DataMatrix igenkänd streckkod
type: docs
weight: 31
url: /sv/androidjava/com.aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DataMatrixExtendedParameters extends BaseExtendedParameters
```

Lagrar speciella data för DataMatrix igenkänd streckkod

--------------------

> ```
> This sample shows how to get DataMatrix raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345");
>  generator.save("c:\\test.png");
> 
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.DATA_MATRIX);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode type: " + result.getCodeTypeName());
>      System.out.println("BarCode codetext: " + result.getCodeText);
>      System.out.println("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId());
>      System.out.println("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount());
>      System.out.println("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId());
>      System.out.println("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming)_);
>  }
> ```
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat  DataMatrixExtendedParameters  värde. |
| [getClass()](#getClass--) |  |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Hämtar ID för DataMatrix strukturerade tilläggsläge streckkod. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Hämtar antalet DataMatrix strukturerade tilläggslägesstreckkoder. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Hämtar ID för DataMatrix strukturerade tilläggsläge streckkod. |
| [hashCode()](#hashCode--) | Returnerar hash‑koden för detta objekt. |
| [isEmpty()](#isEmpty--) | Testar om alla parametrar endast har standardvärden |
| [isReaderProgramming()](#isReaderProgramming--) | Anger om koden används för att instruera läsaren att tolka följande data som instruktioner för initiering eller omprogrammering av streckkodsläsaren. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-) | Returnerar ett värde som indikerar om det första DataMatrixExtendedParameters‑värdet är lika med det andra. |
| [op_Inequality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-) | Returnerar ett värde som indikerar om det första DataMatrixExtendedParameters‑värdet är annorlunda än det andra. |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta DataMatrixExtendedParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat  DataMatrixExtendedParameters  värde.

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


Hämtar ID för DataMatrix strukturerade tilläggslägesstreckkod. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärdet är -1.

Värde: ID för DataMatrix strukturerade tilläggslägesstreckkod.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public int getStructuredAppendBarcodesCount()
```


Hämtar antalet DataMatrix strukturerade tilläggslägesstreckkoder. Standardvärdet är -1. Antalet måste vara ett värde mellan 1 och 35.

Värde: Antalet DataMatrix strukturerade tilläggslägesstreckkod.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public int getStructuredAppendFileId()
```


Hämtar ID för DataMatrix strukturerade tilläggslägesstreckkod. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärdet är -1.

Värde: ID för DataMatrix strukturerade tilläggslägesstreckkod.

**Returns:**
int
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
### isReaderProgramming() {#isReaderProgramming--}
```
public boolean isReaderProgramming()
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




### op_Equality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-}
```
public static boolean op_Equality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)
```


Returnerar ett värde som indikerar om det första DataMatrixExtendedParameters‑värdet är lika med det andra.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| first | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Ett första jämfört värde |
| second | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Ett andra jämfört värde |

**Returns:**
boolean -  **true**  om första har samma värde som andra; annars,  **false** .
### op_Inequality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-}
```
public static boolean op_Inequality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)
```


Returnerar ett värde som indikerar om det första DataMatrixExtendedParameters‑värdet är annorlunda än det andra.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| first | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Ett första jämfört värde |
| second | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Ett andra jämfört värde |

**Returns:**
boolean -  **true**  om första har ett annat värde än andra; annars,  **false** .
### toString() {#toString--}
```
public String toString()
```


Returnerar en människoläsbar strängrepresentation av detta DataMatrixExtendedParameters.

**Returns:**
java.lang.String - En sträng som representerar detta DataMatrixExtendedParameters.
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

