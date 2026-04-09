---
title: HIBCPASCodetext
second_title: Aspose.BarCode for Android via Java API-referentie
description: Klasse voor het coderen en decoderen van de tekst die is ingebed in de HIBC PAS-code.
type: docs
weight: 18
url: /nl/androidjava/com.aspose.barcode.complexbarcode/hibcpascodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class HIBCPASCodetext implements IComplexCodetext
```

Klasse voor het coderen en decoderen van de tekst die is ingebed in de HIBC PAS-code.

--------------------

> ```
> This sample shows how to encode and decode HIBC PAS using HIBCPASCodetext.
>   
> 
>   HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
>   complexCodetext.setDataLocation(HIBCPASDataLocation.PATIENT);
>   complexCodetext.addRecord(HIBCPASDataType.LABELER_IDENTIFICATION_CODE, "A123");
>   complexCodetext.addRecord(HIBCPASDataType.MANUFACTURER_SERIAL_NUMBER, "SERIAL123");
>   complexCodetext.setBarcodeType(EncodeTypes.HIBC_DATA_MATRIX_PAS);
>   ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext);
>   BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.HIBC_DATA_MATRIX_PAS);
>   reader.readBarCodes();
>   String codetext = reader.getFoundBarCodes()[0].getCodeText();
>  	HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.tryDecodeHIBCPAS(codetext);
>   System.out.println("Data location: {0}", readCodetext.getDataLocation());
>   System.out.print("Data type: {0}. ", readCodetext.getRecords()[0].getDataType());
>   System.out.println("Data: {0}", readCodetext.getRecords()[0].getData());
>   System.out.print("Data type: {0}. ", readCodetext.getRecords()[1].getDataType());
>   System.out.println("Data: {0}", readCodetext.getRecords()[1].getData());
>       }
>   }
> ```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [HIBCPASCodetext()](#HIBCPASCodetext--) |  |
## Methods

| Method | Beschrijving |
| --- | --- |
| [addRecord(HIBCPASRecord record)](#addRecord-com.aspose.barcode.complexbarcode.HIBCPASRecord-) | Voegt nieuw record toe |
| [addRecord(int dataType, String data)](#addRecord-int-java.lang.String-) | Voegt nieuw record toe |
| [clear()](#clear--) | Leegt recordlijst |
| [equals(Object obj)](#equals-java.lang.Object-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een gespecificeerde  HIBCPASCodetext  waarde. |
| [getBarcodeType()](#getBarcodeType--) | Haalt barcode‑type op. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construeert codetext |
| [getDataLocation()](#getDataLocation--) | Identificeert gegevenslocatie. |
| [getRecords()](#getRecords--) | Haalt recordlijst op |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze instantie. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initialiseert instantie vanuit geconstrueerde codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Haalt het barcode-type op of stelt het in. |
| [setDataLocation(int value)](#setDataLocation-int-) | Identificeert gegevenslocatie. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIBCPASCodetext() {#HIBCPASCodetext--}
```
public HIBCPASCodetext()
```


### addRecord(HIBCPASRecord record) {#addRecord-com.aspose.barcode.complexbarcode.HIBCPASRecord-}
```
public void addRecord(HIBCPASRecord record)
```


Voegt nieuw record toe

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| record | [HIBCPASRecord](../../com.aspose.barcode.complexbarcode/hibcpasrecord) | Record om toe te voegen |

### addRecord(int dataType, String data) {#addRecord-int-java.lang.String-}
```
public void addRecord(int dataType, String data)
```


Voegt nieuw record toe

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dataType | int | Gegevenstype |
| gegevens | java.lang.String | Gegevensreeks |

### clear() {#clear--}
```
public void clear()
```


Leegt recordlijst

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Retourneert een waarde die aangeeft of deze instantie gelijk is aan een gespecificeerde  HIBCPASCodetext  waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Een  HIBCPASCodetext  waarde om te vergelijken met deze instantie. |

**Returns:**
boolean -  **true**  als obj dezelfde waarde heeft als deze instantie; anders,  **false** .
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Haalt barcode‑type op.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Construeert codetext

**Returns:**
java.lang.String - Gemaakt codetext
### getDataLocation() {#getDataLocation--}
```
public int getDataLocation()
```


Identificeert gegevenslocatie.

**Returns:**
int
### getRecords() {#getRecords--}
```
public List<HIBCPASRecord> getRecords()
```


Haalt recordlijst op

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.HIBCPASRecord> - Lijst met records
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode voor deze instantie.

**Returns:**
int - Een 32-bits ondertekend geheel getal hashcode.
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Initialiseert instantie vanuit geconstrueerde codetext.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Gemaakt codetext. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


Haalt of stelt het barcode-type in. HIBC PAS codetext kan worden gecodeerd met behulp van HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS en HIBCQRPAS coderings types. Standaardwaarde: HIBCCode39PAS.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setDataLocation(int value) {#setDataLocation-int-}
```
public void setDataLocation(int value)
```


Identificeert gegevenslocatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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

