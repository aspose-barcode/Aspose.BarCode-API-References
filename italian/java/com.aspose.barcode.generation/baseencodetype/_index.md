---
title: "BaseEncodeType"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Classe base per SymbologyEncodeType."
type: docs
weight: 16
url: /it/java/com.aspose.barcode.generation/baseencodetype/
---
**Inheritance:**
java.lang.Object
```
public class BaseEncodeType
```

Classe base per SymbologyEncodeType.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object other)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un valore BaseEncodeType specificato. |
| [getClass()](#getClass--) |  |
| [getClassification()](#getClassification--) | Ottiene una classificazione di questa simbologia. |
| [getString()](#getString--) | Converte l'istanza di BaseEncodeType nella sua rappresentazione stringa equivalente. |
| [getString(BaseEncodeType instance)](#getString-com.aspose.barcode.generation.BaseEncodeType-) | Converte l'istanza di BaseEncodeType nella sua rappresentazione stringa equivalente. |
| [getTypeIndex()](#getTypeIndex--) | Ottiene l'indice del tipo di codifica. |
| [getTypeName()](#getTypeName--) | Ottiene il nome del tipo di codifica. |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa istanza. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String stringEncodeType)](#parse-java.lang.String-) | Converte la rappresentazione stringa del nome di un BaseEncodeType nella sua istanza. |
| [toString()](#toString--) | Restituisce il nome del BaseEncodeType fornito come stringa. |
| [tryParse(String parsingType, BaseEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---) | Converte la rappresentazione stringa di un BaseEncodeType nella sua istanza. |
| [tryParse(String parsingType, SymbologyEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---) | Converte la rappresentazione stringa di un BaseEncodeType nella sua istanza. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Restituisce un valore che indica se questa istanza è uguale a un valore BaseEncodeType specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | java.lang.Object | Un valore BaseEncodeType da confrontare con questa istanza. |

**Returns:**
boolean -  **true**  se obj ha lo stesso valore di questa istanza; altrimenti,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassification() {#getClassification--}
```
public BarcodeClassifications getClassification()
```


Ottiene una classificazione di questa simbologia.

**Returns:**
[BarcodeClassifications](../../com.aspose.barcode.generation/barcodeclassifications)
### getString() {#getString--}
```
public String getString()
```


Converte l'istanza di BaseEncodeType nella sua rappresentazione stringa equivalente. Il formato della stringa è: "Index:0; Name:Codabar".

**Returns:**
java.lang.String - Una stringa che rappresenta il valore completo del tipo di codifica
### getString(BaseEncodeType instance) {#getString-com.aspose.barcode.generation.BaseEncodeType-}
```
public static String getString(BaseEncodeType instance)
```


Converte l'istanza di BaseEncodeType nella sua rappresentazione stringa equivalente. Il formato della stringa è: "Index:-1; Name:None".

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| instance | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | L'istanza BaseEncodeType da convertire |

**Returns:**
java.lang.String - Una stringa che rappresenta il valore completo del tipo di codifica fornito
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


Ottiene l'indice del tipo di codifica.

**Returns:**
short
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


Ottiene il nome del tipo di codifica.

**Returns:**
java.lang.String
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




### parse(String stringEncodeType) {#parse-java.lang.String-}
```
public static BaseEncodeType parse(String stringEncodeType)
```


Converte la rappresentazione stringa del nome di un BaseEncodeType nella sua istanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stringEncodeType | java.lang.String | Una stringa contenente il nome di un BaseEncodeType da convertire. |

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - the instance of , if conversion was successful; otherwise, it returns   .
### toString() {#toString--}
```
public String toString()
```


Restituisce il nome del BaseEncodeType fornito come stringa.

**Returns:**
java.lang.String - Una stringa che rappresenta il nome del tipo di codifica
### tryParse(String parsingType, BaseEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---}
```
public static boolean tryParse(String parsingType, BaseEncodeType[] result)
```


Converte la rappresentazione stringa di un BaseEncodeType nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o meno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parsingType | java.lang.String | Una stringa nel formato "Index:-1; Name:None" da convertire. |
|  | result | [BaseEncodeType\[\]](../../com.aspose.barcode.generation/baseencodetype) | Un valore SingleEncodeType reale viene restituito quando la conversione è completata con successo; |

altrimenti restituisce null. |

**Returns:**
boolean -  **true**  se s è stato convertito con successo; altrimenti,  **false** .
### tryParse(String parsingType, SymbologyEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---}
```
public static boolean tryParse(String parsingType, SymbologyEncodeType[] result)
```


Converte la rappresentazione stringa di un BaseEncodeType nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o meno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parsingType | java.lang.String | Una stringa nel formato "Index:-1; Name:None" da convertire. |
|  | result | [SymbologyEncodeType\[\]](../../com.aspose.barcode.generation/symbologyencodetype) | Un valore SingleEncodeType reale viene restituito quando la conversione è completata con successo; |

altrimenti restituisce null. |

**Returns:**
boolean -  **true**  se s è stato convertito con successo; altrimenti,  **false** .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
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

