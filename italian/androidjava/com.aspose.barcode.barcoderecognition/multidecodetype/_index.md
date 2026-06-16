---
title: MultiDecodeType
second_title: Aspose.BarCode per Android via Java API Reference
description: Tipo di decodifica composita.
type: docs
weight: 37
url: /it/androidjava/com.aspose.barcode.barcoderecognition/multidecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public class MultiDecodeType extends BaseDecodeType
```

Tipo di decodifica composita.

Questo esempio mostra come creare tipi MultiDecode composti che combinano SingleDecodeType e MultiDecode

```

```
## Constructors

| Constructor | Descrizione |
| --- | --- |
| [MultiDecodeType(SingleDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | Inizializza una nuova istanza della classe MultiDecodeType. |
| [MultiDecodeType(BaseDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Inizializza una nuova istanza della classe MultiDecodeType. |
## Methods

| Method | Descrizione |
| --- | --- |
| [add(SingleDecodeType singleType)](#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Aggiunge un altro [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) al MultiDecodeType. |
| [containsAll(BaseDecodeType[] barcodeTypes)](#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Verifica se contiene tutti i tipi di codici a barre. |
| [containsAny(BaseDecodeType[] decodeTypes)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Contiene uno dei tipi |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Restituisce un valore che indica se questa istanza è uguale a un valore MultiDecodeType specificato. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Restituisce un valore che indica se questa collezione di tipi di decodifica contiene solo il valore [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) specificato. |
| [equals(Object obj)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un valore MultiDecodeType specificato. |
| [exclude(SingleDecodeType singleType)](#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Esclude [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) dal MultiDecodeType e restituisce una nuova istanza di MultiDecodeType. |
| [getClass()](#getClass--) |  |
| [getSingleTypes()](#getSingleTypes--) | Rappresenta un elenco di tipi singoli. |
| [getSingleTypesCount()](#getSingleTypesCount--) | Restituisce il numero di tipi singoli. |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa istanza. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Metodo sovrascritto che rappresenta MultiDecodeType come stringa. |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Converte la rappresentazione stringa di un BaseDecodeType nella sua istanza, avendo determinato il tipo concreto. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Converte la rappresentazione stringa di un MultiDecodeType nella sua istanza. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Converte la rappresentazione stringa di un SingleDecodeType nella sua istanza. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiDecodeType(SingleDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public MultiDecodeType(SingleDecodeType[] barcodeTypes)
```


Inizializza una nuova istanza della classe MultiDecodeType.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Array di tipi di decodifica singoli |

### MultiDecodeType(BaseDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public MultiDecodeType(BaseDecodeType[] barcodeTypes)
```


Inizializza una nuova istanza della classe MultiDecodeType.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Array di tipi di decodifica multipli e singoli |

### add(SingleDecodeType singleType) {#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final void add(SingleDecodeType singleType)
```


Aggiunge un altro [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) al MultiDecodeType.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Un Single DecodeType da aggiungere all'elenco |

### containsAll(BaseDecodeType[] barcodeTypes) {#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public final boolean containsAll(BaseDecodeType[] barcodeTypes)
```


Verifica se contiene tutti i tipi di codici a barre.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Inserisci tipi di codici a barre singoli o multipli |

**Returns:**
boolean - Il valore è true se tutti i tipi sono inclusi in
### containsAny(BaseDecodeType[] decodeTypes) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] decodeTypes)
```


Contiene uno dei tipi

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipi di decodifica |

**Returns:**
boolean - Il valore è true se sono inclusi dei tipi
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Restituisce un valore che indica se questa istanza è uguale a un valore MultiDecodeType specificato.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| altro | com.aspose.barcode.barcoderecognition.MultiDecodeType | Un valore MultiDecodeType da confrontare con questa istanza. |

**Returns:**
boolean -  **true**  se obj ha lo stesso valore di questa istanza; altrimenti,  **false** .
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Restituisce un valore che indica se questa collezione di tipi di decodifica contiene solo il valore [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) specificato.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Un valore [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) da confrontare con questa collezione di tipi di decodifica. |

**Returns:**
boolean -  **true**  se questa collezione contiene solo il tipo di decodifica specificato; altrimenti,  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Restituisce un valore che indica se questa istanza è uguale a un valore MultiDecodeType specificato.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Un valore System.Object da confrontare con questa istanza. |

**Returns:**
boolean -  **true**  se obj ha lo stesso valore di questa istanza; altrimenti,  **false** .
### exclude(SingleDecodeType singleType) {#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final MultiDecodeType exclude(SingleDecodeType singleType)
```


Esclude [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) dal MultiDecodeType e restituisce una nuova istanza di MultiDecodeType.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Un singolo DecodeType da escludere. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - Nuova istanza di MultiDecodeType con SingleDecodeType escluso.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSingleTypes() {#getSingleTypes--}
```
public final List<SingleDecodeType> getSingleTypes()
```


Rappresenta un elenco di tipi singoli.

**Returns:**
java.util.List<com.aspose.barcode.barcoderecognition.SingleDecodeType> - Elenco di tipi singoli
### getSingleTypesCount() {#getSingleTypesCount--}
```
public final int getSingleTypesCount()
```


Restituisce il numero di tipi singoli.

**Returns:**
int
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




### toString() {#toString--}
```
public String toString()
```


Metodo sovrascritto che rappresenta MultiDecodeType come stringa.

**Returns:**
java.lang.String - Una stringa che rappresenta l'istanza MultiDecodeType come "singleDecodeType1, singleDecodeType2, ..."

 **"AllSupportedTypes"**  returns when all types are included.
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

