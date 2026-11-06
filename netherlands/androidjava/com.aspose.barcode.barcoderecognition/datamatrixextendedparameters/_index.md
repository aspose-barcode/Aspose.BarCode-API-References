---
title: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode voor Android via Java API-referentie"
description: "Slaat speciale gegevens van herkende DataMatrix-barcode op"
type: docs
weight: 29
url: /nl/androidjava/com.aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DataMatrixExtendedParameters extends BaseExtendedParameters
```

Slaat speciale gegevens van herkende DataMatrix-barcode op

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
>      System.out.println("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming));
>  }
> ```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven  DataMatrixExtendedParameters  waarde. |
| [getClass()](#getClass--) |  |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Haalt de ID op van de DataMatrix structured append-modus barcode. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Haalt het aantal barcodes van de DataMatrix structured append-modus op. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Haalt de ID op van de DataMatrix structured append-modus barcode. |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze instantie. |
| [isEmpty()](#isEmpty--) | Test of alle parameters alleen standaardwaarden hebben |
| [isReaderProgramming()](#isReaderProgramming--) | Geeft aan of de code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze  DataMatrixExtendedParameters . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven  DataMatrixExtendedParameters  waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Een System.Object-waarde om te vergelijken met deze instantie. |

**Returns:**
boolean -  **true**  als obj dezelfde waarde heeft als deze instantie; anders,  **false** .
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


Haalt de ID op van de DataMatrix structured append-modus barcode. ID begint bij 1 en moet kleiner of gelijk zijn aan het aantal barcodes. Standaardwaarde is -1.

Waarde: De ID van de DataMatrix structured append-modus barcode.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public int getStructuredAppendBarcodesCount()
```


Haalt het aantal barcodes van de DataMatrix structured append-modus op. Standaardwaarde is -1. Het aantal moet een waarde tussen 1 en 35 zijn.

Waarde: Het aantal van de DataMatrix structured append-modus barcode.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public int getStructuredAppendFileId()
```


Haalt de ID op van de DataMatrix structured append-modus barcode. ID begint bij 1 en moet kleiner of gelijk zijn aan het aantal barcodes. Standaardwaarde is -1.

Waarde: De ID van de DataMatrix structured append-modus barcode.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode voor deze instantie.

**Returns:**
int - Een 32-bit ondertekend geheel getal hashcode.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Test of alle parameters alleen standaardwaarden hebben

Waarde: Retourneert  **true**  als alle parameters alleen standaardwaarden hebben; anders,  **false** .

**Returns:**
boolean
### isReaderProgramming() {#isReaderProgramming--}
```
public boolean isReaderProgramming()
```


Geeft aan of de code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. Standaardwaarde is false.

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


Retourneert een menselijk leesbare tekenreeksrepresentatie van deze  DataMatrixExtendedParameters .

**Returns:**
java.lang.String - Een string die deze  DataMatrixExtendedParameters  vertegenwoordigt.
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

