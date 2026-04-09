---
title: BaseDecodeType
second_title: Aspose.BarCode per Android via Java API Reference
description: Classe base per MultiDecodeType e SingleDecodeType.
type: docs
weight: 23
url: /it/androidjava/com.aspose.barcode.barcoderecognition/basedecodetype/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseDecodeType
```

Classe base per MultiDecodeType e SingleDecodeType.

--------------------

> ```
> This sample shows how to use BaseDecodeType with SingleDecodeType and MultiDecodeType
>  
>  BaseDecodeType decodeOne = DecodeType.CODE_128;
>  BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.CODE_128, DecodeType.CODE_39_STANDARD, DecodeType.CODE_39_FULL_ASCII);
> ```
## Methods

| Method | Descrizione |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Determina se uno qualsiasi dei tipi di decodifica forniti è incluso in |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Restituisce un valore che indica se questa istanza è uguale a un valore [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) specificato. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Restituisce un valore che indica se questa istanza è uguale a un valore [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) specificato. |
| [equals(Object other)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un valore [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) specificato. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Converte la rappresentazione stringa di un BaseDecodeType nella sua istanza, avendo determinato il tipo concreto. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Converte la rappresentazione stringa di un MultiDecodeType nella sua istanza. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Converte la rappresentazione stringa di un SingleDecodeType nella sua istanza. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public abstract boolean containsAny(BaseDecodeType[] types)
```


Determina se uno qualsiasi dei tipi di decodifica forniti è incluso in

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipi da verificare. |

**Returns:**
boolean - Il valore è true se qualche tipo è incluso in.
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Restituisce un valore che indica se questa istanza è uguale a un valore [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) specificato.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| altro | com.aspose.barcode.barcoderecognition.MultiDecodeType | Un valore java.lang.Object da confrontare con questa istanza. |

**Returns:**
boolean - True se l'oggetto ha lo stesso valore di questa istanza; altrimenti, false.
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Restituisce un valore che indica se questa istanza è uguale a un valore [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) specificato.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Un valore java.lang.Object da confrontare con questa istanza. |

**Returns:**
boolean - True se l'oggetto ha lo stesso valore di questa istanza; altrimenti, false.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Restituisce un valore che indica se questa istanza è uguale a un valore [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) specificato.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| altro | java.lang.Object | Un valore java.lang.Object da confrontare con questa istanza. |

**Returns:**
boolean - True se l'oggetto ha lo stesso valore di questa istanza; altrimenti, false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
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


Converte la rappresentazione stringa di un BaseDecodeType nella sua istanza, avendo determinato il tipo concreto. Un valore di ritorno indica se la conversione è riuscita o è fallita.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| parsingType | java.lang.String | Una stringa contenente una rappresentazione MultiDecodeType da convertire. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

altrimenti restituisce un tipo indefinito. o MultiDecodeType (\"None\").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


Converte la rappresentazione stringa di un MultiDecodeType nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o è fallita.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| parsingType | java.lang.String | Una stringa contenente una rappresentazione MultiDecodeType da convertire. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - Viene restituito un MultiDecodeType reale, quando la conversione è completata con successo;

altrimenti restituisce un tipo indefinito. o MultiDecodeType (\"None\").
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Converte la rappresentazione stringa di un SingleDecodeType nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o è fallita.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| parsingType | java.lang.String | Una stringa contenente un SingleDecodeType nel formato \"EAN8\" o \"EAN13\" o \"CodaBar\"... da convertire. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

altrimenti restituisce un tipo indefinito. o SingleDecodeType (-1, \"None\").
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

