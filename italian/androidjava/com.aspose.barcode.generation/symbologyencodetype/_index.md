---
title: SymbologyEncodeType
second_title: Aspose.BarCode per Android via Java API Reference
description: Tipo di codifica della simbologia.
type: docs
weight: 67
url: /it/androidjava/com.aspose.barcode.generation/symbologyencodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
```
public class SymbologyEncodeType extends BaseEncodeType
```

Tipo di codifica della simbologia. Vedi EncodeTypes per ottenere un'istanza.

--------------------

> ```
> Create symbology encode type
>  
>  SymbologyEncodeType symbologyType = EncodeTypes.GS_1_CODE_128
> ```
## Methods

| Method | Descrizione |
| --- | --- |
| [equals(Object other)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato di BaseEncodeType. |
| [getClass()](#getClass--) |  |
| [getClassification()](#getClassification--) | Ottiene una classificazione di questa simbologia. |
| [getString()](#getString--) | Converte l'istanza di BaseEncodeType nella sua rappresentazione stringa equivalente. |
| [getString(BaseEncodeType instance)](#getString-com.aspose.barcode.generation.BaseEncodeType-) | Converte l'istanza di BaseEncodeType nella sua rappresentazione stringa equivalente. |
| [getTypeIndex()](#getTypeIndex--) | Ottiene un indice del tipo di codifica |
| [getTypeName()](#getTypeName--) | Ottiene un nome del tipo di codifica |
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


Restituisce un valore che indica se questa istanza è uguale a un valore specificato di BaseEncodeType.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| altro | java.lang.Object | Un valore BaseEncodeType da confrontare con questa istanza. |

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
| Parameter | Type | Descrizione |
| --- | --- | --- |
| instance | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | L'istanza di BaseEncodeType da convertire |

**Returns:**
java.lang.String - Una stringa che rappresenta il valore completo del tipo di codifica fornito
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


Ottiene un indice del tipo di codifica

**Returns:**
short
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


Ottiene un nome del tipo di codifica

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
| Parameter | Type | Descrizione |
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


Converte la rappresentazione stringa di un BaseEncodeType nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o è fallita.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| parsingType | java.lang.String | Una stringa nel formato "Index:-1; Name:None" da convertire. |
|  | result | [BaseEncodeType\[\]](../../com.aspose.barcode.generation/baseencodetype) | Un vero SingleEncodeType viene restituito, quando la conversione è completata con successo; |

altrimenti restituisce null. |

**Returns:**
boolean -  **true**  se s è stato convertito con successo; altrimenti,  **false** .
### tryParse(String parsingType, SymbologyEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---}
```
public static boolean tryParse(String parsingType, SymbologyEncodeType[] result)
```


Converte la rappresentazione stringa di un BaseEncodeType nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o è fallita.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| parsingType | java.lang.String | Una stringa nel formato "Index:-1; Name:None" da convertire. |
|  | result | [SymbologyEncodeType\[\]](../../com.aspose.barcode.generation/symbologyencodetype) | Un vero SingleEncodeType viene restituito, quando la conversione è completata con successo; |

altrimenti restituisce null. |

**Returns:**
boolean -  **true**  se s è stato convertito con successo; altrimenti,  **false** .
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

