---
title: "MultyDecodeType"
second_title: "Referencia de API de Aspose.BarCode para Android mediante Java"
description: 
type: docs
weight: 36
url: /es/androidjava/com.aspose.barcode.barcoderecognition/multydecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public class MultyDecodeType extends BaseDecodeType
```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MultyDecodeType(BaseDecodeType[] arg0)](#MultyDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) |  |
| [MultyDecodeType(SingleDecodeType[] arg0)](#MultyDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [add(SingleDecodeType arg0)](#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-) |  |
| [containsAll(BaseDecodeType[] arg0)](#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) |  |
| [containsAny(BaseDecodeType[] arg0)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) |  |
| [describeContents()](#describeContents--) |  |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype). |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype). |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getGetSingleTypesCount()](#getGetSingleTypesCount--) |  |
| [getSingleTypes()](#getSingleTypes--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Convierte la representación en cadena de un BaseDecodeType a su instancia, habiendo determinado el tipo concreto. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Convierte la representación en cadena de un MultiDecodeType a su instancia. |
| [tryParseMultyDecodeType(String arg0)](#tryParseMultyDecodeType-java.lang.String-) |  |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Convierte la representación en cadena de un SingleDecodeType a su instancia. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel arg0, int arg1)](#writeToParcel-android.os.Parcel-int-) |  |
### MultyDecodeType(BaseDecodeType[] arg0) {#MultyDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public MultyDecodeType(BaseDecodeType[] arg0)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) |  |

### MultyDecodeType(SingleDecodeType[] arg0) {#MultyDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public MultyDecodeType(SingleDecodeType[] arg0)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

### containsAll(BaseDecodeType[] arg0) {#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAll(BaseDecodeType[] arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) |  |

**Returns:**
boolean
### containsAny(BaseDecodeType[] arg0) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] arg0)
```


Determina si alguno de los tipos de decodificación proporcionados está incluido en

**Parameters:**
| Parámetro | Tipo | Descripción |
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


Devuelve un valor que indica si esta instancia es igual a un valor especificado de [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) | Un valor java.lang.Object para comparar con esta instancia. |

**Returns:**
boolean - Verdadero si obj tiene el mismo valor que esta instancia; de lo contrario, falso.
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Devuelve un valor que indica si esta instancia es igual a un valor especificado de [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Un valor java.lang.Object para comparar con esta instancia. |

**Returns:**
boolean - Verdadero si obj tiene el mismo valor que esta instancia; de lo contrario, falso.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```


Devuelve un valor que indica si esta instancia es igual a un valor especificado de [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype).

**Parameters:**
| Parámetro | Tipo | Descripción |
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


Convierte la representación en cadena de un BaseDecodeType a su instancia, habiendo determinado el tipo concreto. Un valor de retorno indica si la conversión tuvo éxito o falló.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parsingType | java.lang.String | Una cadena que contiene una representación de MultiDecodeType para convertir. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

de lo contrario devuelve un tipo indefinido. o MultiDecodeType ("None").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


Convierte la representación en cadena de un MultiDecodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parsingType | java.lang.String | Una cadena que contiene una representación de MultiDecodeType para convertir. |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

de lo contrario devuelve un tipo indefinido. o MultiDecodeType ("None").
### tryParseMultyDecodeType(String arg0) {#tryParseMultyDecodeType-java.lang.String-}
```
public static MultyDecodeType tryParseMultyDecodeType(String arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.String |  |

**Returns:**
com.aspose.barcode.barcoderecognition.MultyDecodeType
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Convierte la representación en cadena de un SingleDecodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parsingType | java.lang.String | Una cadena que contiene un SingleDecodeType en el formato "EAN8" o "EAN13" o "CodaBar"... para convertir. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

de lo contrario devuelve un tipo indefinido. o SingleDecodeType (-1, "None").
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | largo |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | largo |  |
| arg1 | int |  |

### writeToParcel(Parcel arg0, int arg1) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | android.os.Parcel |  |
| arg1 | int |  |

