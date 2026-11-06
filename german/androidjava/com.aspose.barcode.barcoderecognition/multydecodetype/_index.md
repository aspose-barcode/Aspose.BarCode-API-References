---
title: "MultyDecodeType"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: 
type: docs
weight: 36
url: /de/androidjava/com.aspose.barcode.barcoderecognition/multydecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public class MultyDecodeType extends BaseDecodeType
```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MultyDecodeType(BaseDecodeType[] arg0)](#MultyDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) |  |
| [MultyDecodeType(SingleDecodeType[] arg0)](#MultyDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add(SingleDecodeType arg0)](#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-) |  |
| [containsAll(BaseDecodeType[] arg0)](#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) |  |
| [containsAny(BaseDecodeType[] arg0)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) |  |
| [describeContents()](#describeContents--) |  |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)-Wert entspricht. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)-Wert entspricht. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getGetSingleTypesCount()](#getGetSingleTypesCount--) |  |
| [getSingleTypes()](#getSingleTypes--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Konvertiert die Zeichenkettenrepräsentation eines BaseDecodeType in seine Instanz, nachdem der konkrete Typ ermittelt wurde. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Konvertiert die Zeichenkettenrepräsentation eines MultiDecodeType in seine Instanz. |
| [tryParseMultyDecodeType(String arg0)](#tryParseMultyDecodeType-java.lang.String-) |  |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Konvertiert die Zeichenkettenrepräsentation eines SingleDecodeType in seine Instanz. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel arg0, int arg1)](#writeToParcel-android.os.Parcel-int-) |  |
### MultyDecodeType(BaseDecodeType[] arg0) {#MultyDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public MultyDecodeType(BaseDecodeType[] arg0)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) |  |

### MultyDecodeType(SingleDecodeType[] arg0) {#MultyDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public MultyDecodeType(SingleDecodeType[] arg0)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<BaseDecodeType> CREATOR
```


### add(SingleDecodeType arg0) {#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public void add(SingleDecodeType arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

### containsAll(BaseDecodeType[] arg0) {#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAll(BaseDecodeType[] arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) |  |

**Returns:**
boolean
### containsAny(BaseDecodeType[] arg0) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] arg0)
```


Bestimmt, ob einer der angegebenen Dekodierungstypen enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) |  |

**Returns:**
boolean
### describeContents() {#describeContents--}
```
public int describeContents()
```




**Returns:**
int
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)-Wert entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) | Ein java.lang.Object-Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolean - Wahr, wenn obj denselben Wert wie diese Instanz hat; andernfalls falsch.
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)-Wert entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Ein java.lang.Object-Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolean - Wahr, wenn obj denselben Wert wie diese Instanz hat; andernfalls falsch.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)-Wert entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
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
### getGetSingleTypesCount() {#getGetSingleTypesCount--}
```
public int getGetSingleTypesCount()
```




**Returns:**
int
### getSingleTypes() {#getSingleTypes--}
```
public List<SingleDecodeType> getSingleTypes()
```




**Returns:**
java.util.List<com.aspose.barcode.barcoderecognition.SingleDecodeType>
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
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




**Returns:**
java.lang.String
### tryParseBaseDecodeType(String parsingType) {#tryParseBaseDecodeType-java.lang.String-}
```
public static BaseDecodeType tryParseBaseDecodeType(String parsingType)
```


Konvertiert die Zeichenkettenrepräsentation eines BaseDecodeType in seine Instanz, nachdem der konkrete Typ ermittelt wurde. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parsingType | java.lang.String | Eine Zeichenkette, die eine MultiDecodeType-Darstellung enthält, die konvertiert werden soll. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

Andernfalls gibt es einen unbestimmten Typ zurück, z. B. MultiDecodeType ("None").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


Konvertiert die Zeichenkettenrepräsentation eines MultiDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parsingType | java.lang.String | Eine Zeichenkette, die eine MultiDecodeType-Darstellung enthält, die konvertiert werden soll. |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

Andernfalls gibt es einen unbestimmten Typ zurück, z. B. MultiDecodeType ("None").
### tryParseMultyDecodeType(String arg0) {#tryParseMultyDecodeType-java.lang.String-}
```
public static MultyDecodeType tryParseMultyDecodeType(String arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.String |  |

**Returns:**
com.aspose.barcode.barcoderecognition.MultyDecodeType
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Konvertiert die Zeichenkettenrepräsentation eines SingleDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parsingType | java.lang.String | Eine Zeichenkette, die einen SingleDecodeType im Format "EAN8" oder "EAN13" oder "CodaBar"... enthält, um ihn zu konvertieren. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

Andernfalls gibt es einen unbestimmten Typ zurück, z. B. SingleDecodeType (-1, "None").
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel arg0, int arg1) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | android.os.Parcel |  |
| arg1 | int |  |

