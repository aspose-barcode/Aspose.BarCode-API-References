---
title: "MultyDecodeType"
second_title: "Riferimento API di Aspose.BarCode per Android via Java"
description: 
type: docs
weight: 36
url: /it/androidjava/com.aspose.barcode.barcoderecognition/multydecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public class MultyDecodeType extends BaseDecodeType
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MultyDecodeType(BaseDecodeType[] arg0)](#MultyDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) |  |
| [MultyDecodeType(SingleDecodeType[] arg0)](#MultyDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add(SingleDecodeType arg0)](#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-) |  |
| [containsAll(BaseDecodeType[] arg0)](#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) |  |
| [containsAny(BaseDecodeType[] arg0)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) |  |
| [describeContents()](#describeContents--) |  |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Restituisce un valore che indica se questa istanza è uguale a un valore [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) specificato. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Restituisce un valore che indica se questa istanza è uguale a un valore [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) specificato. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getGetSingleTypesCount()](#getGetSingleTypesCount--) |  |
| [getSingleTypes()](#getSingleTypes--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Converte la rappresentazione stringa di un BaseDecodeType nella sua istanza, avendo determinato il tipo concreto. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Converte la rappresentazione stringa di un MultiDecodeType nella sua istanza. |
| [tryParseMultyDecodeType(String arg0)](#tryParseMultyDecodeType-java.lang.String-) |  |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Converte la rappresentazione stringa di un SingleDecodeType nella sua istanza. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel arg0, int arg1)](#writeToParcel-android.os.Parcel-int-) |  |
### MultyDecodeType(BaseDecodeType[] arg0) {#MultyDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public MultyDecodeType(BaseDecodeType[] arg0)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) |  |

### MultyDecodeType(SingleDecodeType[] arg0) {#MultyDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public MultyDecodeType(SingleDecodeType[] arg0)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

### containsAll(BaseDecodeType[] arg0) {#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAll(BaseDecodeType[] arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) |  |

**Returns:**
boolean
### containsAny(BaseDecodeType[] arg0) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] arg0)
```


Determina se uno qualsiasi dei tipi di decodifica forniti è incluso in

**Parameters:**
| Parametro | Tipo | Descrizione |
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


Restituisce un valore che indica se questa istanza è uguale a un valore [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) | Un valore java.lang.Object da confrontare con questa istanza. |

**Returns:**
boolean - True se obj ha lo stesso valore di questa istanza; altrimenti, false.
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Restituisce un valore che indica se questa istanza è uguale a un valore [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Un valore java.lang.Object da confrontare con questa istanza. |

**Returns:**
boolean - True se obj ha lo stesso valore di questa istanza; altrimenti, false.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```


Restituisce un valore che indica se questa istanza è uguale a un valore [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
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


Converte la rappresentazione stringa di un BaseDecodeType nella sua istanza, dopo aver determinato il tipo concreto. Un valore di ritorno indica se la conversione è riuscita o è fallita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parsingType | java.lang.String | Una stringa contenente una rappresentazione MultiDecodeType da convertire. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

altrimenti restituisce un tipo indefinito. o MultiDecodeType ("None").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


Converte la rappresentazione stringa di un MultiDecodeType nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o è fallita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parsingType | java.lang.String | Una stringa contenente una rappresentazione MultiDecodeType da convertire. |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

altrimenti restituisce un tipo indefinito. o MultiDecodeType ("None").
### tryParseMultyDecodeType(String arg0) {#tryParseMultyDecodeType-java.lang.String-}
```
public static MultyDecodeType tryParseMultyDecodeType(String arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.String |  |

**Returns:**
com.aspose.barcode.barcoderecognition.MultyDecodeType
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Converte la rappresentazione stringa di un SingleDecodeType nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o è fallita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parsingType | java.lang.String | Una stringa contenente un SingleDecodeType nel formato "EAN8" o "EAN13" o "CodaBar"... da convertire. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

altrimenti restituisce un tipo indefinito. o SingleDecodeType (-1, "None").
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

### writeToParcel(Parcel arg0, int arg1) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | android.os.Parcel |  |
| arg1 | int |  |

