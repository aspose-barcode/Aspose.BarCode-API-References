---
title: "MultyDecodeType"
second_title: "Référence d'API Aspose.BarCode pour Android via Java"
description: 
type: docs
weight: 36
url: /fr/androidjava/com.aspose.barcode.barcoderecognition/multydecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public class MultyDecodeType extends BaseDecodeType
```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MultyDecodeType(BaseDecodeType[] arg0)](#MultyDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) |  |
| [MultyDecodeType(SingleDecodeType[] arg0)](#MultyDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) |  |
## Champs

| Champ | Description |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [add(SingleDecodeType arg0)](#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-) |  |
| [containsAll(BaseDecodeType[] arg0)](#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) |  |
| [containsAny(BaseDecodeType[] arg0)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) |  |
| [describeContents()](#describeContents--) |  |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Renvoie une valeur indiquant si cette instance est égale à une valeur [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) spécifiée. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Renvoie une valeur indiquant si cette instance est égale à une valeur [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) spécifiée. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getGetSingleTypesCount()](#getGetSingleTypesCount--) |  |
| [getSingleTypes()](#getSingleTypes--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Convertit la représentation sous forme de chaîne d'un BaseDecodeType en son instance, après avoir déterminé le type concret. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Convertit la représentation sous forme de chaîne d'un MultiDecodeType en son instance. |
| [tryParseMultyDecodeType(String arg0)](#tryParseMultyDecodeType-java.lang.String-) |  |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Convertit la représentation sous forme de chaîne d'un SingleDecodeType en son instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel arg0, int arg1)](#writeToParcel-android.os.Parcel-int-) |  |
### MultyDecodeType(BaseDecodeType[] arg0) {#MultyDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public MultyDecodeType(BaseDecodeType[] arg0)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) |  |

### MultyDecodeType(SingleDecodeType[] arg0) {#MultyDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public MultyDecodeType(SingleDecodeType[] arg0)
```


**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

### containsAll(BaseDecodeType[] arg0) {#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAll(BaseDecodeType[] arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) |  |

**Returns:**
boolean
### containsAny(BaseDecodeType[] arg0) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] arg0)
```


Détermine si l'un des types de décodage fournis est inclus dans

**Parameters:**
| Paramètre | Type | Description |
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


Renvoie une valeur indiquant si cette instance est égale à une valeur [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) | Une valeur java.lang.Object à comparer à cette instance. |

**Returns:**
booléen - Vrai si obj a la même valeur que cette instance ; sinon, faux.
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Renvoie une valeur indiquant si cette instance est égale à une valeur [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Une valeur java.lang.Object à comparer à cette instance. |

**Returns:**
booléen - Vrai si obj a la même valeur que cette instance ; sinon, faux.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```


Renvoie une valeur indiquant si cette instance est égale à une valeur [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
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


Convertit la représentation sous forme de chaîne d'un BaseDecodeType en son instance, après avoir déterminé le type concret. Une valeur de retour indique si la conversion a réussi ou échoué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | Une chaîne contenant une représentation MultiDecodeType à convertir. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

sinon, elle renvoie un type indéfini. ou MultiDecodeType ("None").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


Convertit la représentation sous forme de chaîne d'un MultiDecodeType en son instance. Une valeur de retour indique si la conversion a réussi ou échoué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | Une chaîne contenant une représentation MultiDecodeType à convertir. |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

sinon, elle renvoie un type indéfini. ou MultiDecodeType ("None").
### tryParseMultyDecodeType(String arg0) {#tryParseMultyDecodeType-java.lang.String-}
```
public static MultyDecodeType tryParseMultyDecodeType(String arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.String |  |

**Returns:**
com.aspose.barcode.barcoderecognition.MultyDecodeType
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Convertit la représentation sous forme de chaîne d'un SingleDecodeType en son instance. Une valeur de retour indique si la conversion a réussi ou échoué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | Une chaîne contenant un SingleDecodeType au format "EAN8" ou "EAN13" ou "CodaBar"... à convertir. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

sinon, elle renvoie un type indéfini. ou SingleDecodeType (-1, "None").
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel arg0, int arg1) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | android.os.Parcel |  |
| arg1 | int |  |

