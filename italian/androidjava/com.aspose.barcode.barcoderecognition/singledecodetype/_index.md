---
title: SingleDecodeType
second_title: Aspose.BarCode per Android via Java API Reference
description: Tipo di decodifica singola.
type: docs
weight: 48
url: /it/androidjava/com.aspose.barcode.barcoderecognition/singledecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public final class SingleDecodeType extends BaseDecodeType
```

Tipo di decodifica singolo. Vedi tipo di decodifica per ottenere l'istanza.

--------------------

> ```
> This sample shows how to get instance of single decode type.
>  
>  SingleDecodeType singleType = DecodeType.QR
> ```
## Methods

| Method | Descrizione |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Restituisce un valore che indica se questa istanza è inclusa nell'elenco specificato. |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) |  |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un valore [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) specificato. |
| [getClass()](#getClass--) |  |
| [getString()](#getString--) | Converte l'istanza di SingleDecodeType nella sua rappresentazione stringa equivalente, utilizzando il seguente formato: \"Index:-1; Name:None\". |
| [getString(SingleDecodeType instance)](#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Converte l'istanza di SingleDecodeType nella sua rappresentazione stringa equivalente, utilizzando il seguente formato: \"Index:-1; Name:None\". |
| [getTypeIndex()](#getTypeIndex--) | Ottiene un indice del tipo di decodifica |
| [getTypeName()](#getTypeName--) | Ottiene un nome del tipo di decodifica |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa istanza. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseSingleDecodeType(String stringDecodeType)](#parseSingleDecodeType-java.lang.String-) | Converte la rappresentazione stringa del nome di un SingleDecodeType nella sua istanza. |
| [toString()](#toString--) | Metodo sovrascritto che rappresenta SingleDecodeType come stringa Name. |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Converte la rappresentazione stringa di un BaseDecodeType nella sua istanza, avendo determinato il tipo concreto. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Converte la rappresentazione stringa di un MultiDecodeType nella sua istanza. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Converte la rappresentazione stringa di un SingleDecodeType nella sua istanza. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] types)
```


Restituisce un valore che indica se questa istanza è inclusa nell'elenco specificato.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Array di tipi di decodifica singoli e multipli |

**Returns:**
boolean - Il valore è true se sono inclusi dei tipi
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Restituisce un valore che indica se questa istanza è uguale a un valore [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) specificato.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| altro | com.aspose.barcode.barcoderecognition.MultiDecodeType |  |

**Returns:**
boolean
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Restituisce un valore che indica se questa istanza è uguale a un valore [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) specificato.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Restituisce un valore che indica se questa istanza è uguale a un valore [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) specificato.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Un valore System.Object da confrontare con questa istanza. |

**Returns:**
boolean - True se l'oggetto ha lo stesso valore di questa istanza; altrimenti, false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getString() {#getString--}
```
public String getString()
```


Converte l'istanza di SingleDecodeType nella sua rappresentazione stringa equivalente, utilizzando il seguente formato: \"Index:-1; Name:None\".

**Returns:**
java.lang.String - Una stringa che rappresenta il valore completo del tipo di decodifica singolo
### getString(SingleDecodeType instance) {#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public static String getString(SingleDecodeType instance)
```


Converte l'istanza di SingleDecodeType nella sua rappresentazione stringa equivalente, utilizzando il seguente formato: \"Index:-1; Name:None\".

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| instance | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | L'istanza SingleDecodeType da convertire |

**Returns:**
java.lang.String - Una stringa che rappresenta il valore completo del tipo di decodifica singolo fornito
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


Ottiene un indice del tipo di decodifica

**Returns:**
short - L'indice del tipo di decodifica
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


Ottiene un nome del tipo di decodifica

**Returns:**
java.lang.String - Il nome del tipo di decodifica
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce il codice hash per questa istanza.

**Returns:**
int - Un codice hash intero con segno a 32 bit.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parseSingleDecodeType(String stringDecodeType) {#parseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType parseSingleDecodeType(String stringDecodeType)
```


Converte la rappresentazione stringa del nome di un SingleDecodeType nella sua istanza.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| stringDecodeType | java.lang.String | Una stringa contenente il nome di un SingleDecodeType da convertire. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - the instance of , if conversion was successful; otherwise, it returns \{@link \}.
### toString() {#toString--}
```
public String toString()
```


Metodo sovrascritto che rappresenta SingleDecodeType come stringa Name.

**Returns:**
java.lang.String - Una stringa che rappresenta il nome del tipo di decodifica singola
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

