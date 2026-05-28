---
title: SingleDecodeType
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Type de décodage unique.
type: docs
weight: 48
url: /fr/androidjava/com.aspose.barcode.barcoderecognition/singledecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public final class SingleDecodeType extends BaseDecodeType
```

Type de décodage unique. Voir le type de décodage pour obtenir une instance.

--------------------

> ```
> This sample shows how to get instance of single decode type.
>  
>  SingleDecodeType singleType = DecodeType.QR
> ```
## Méthodes

| Méthode | Description |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Renvoie une valeur indiquant si cette instance est incluse dans la liste spécifiée. |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) |  |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Renvoie une valeur indiquant si cette instance est égale à une valeur [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) spécifiée. |
| [getClass()](#getClass--) |  |
| [getString()](#getString--) | Convertit l'instance de SingleDecodeType en sa représentation chaîne équivalente, en utilisant le format suivant : "Index:-1; Name:None". |
| [getString(SingleDecodeType instance)](#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Convertit l'instance de SingleDecodeType en sa représentation chaîne équivalente, en utilisant le format suivant : "Index:-1; Name:None". |
| [getTypeIndex()](#getTypeIndex--) | Obtient l'index du type de décodage |
| [getTypeName()](#getTypeName--) | Obtient le nom du type de décodage |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseSingleDecodeType(String stringDecodeType)](#parseSingleDecodeType-java.lang.String-) | Convertit la représentation chaîne du nom d'un SingleDecodeType en son instance. |
| [toString()](#toString--) | Méthode remplacée représentant SingleDecodeType sous forme de chaîne Name. |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Convertit la représentation chaîne d'un BaseDecodeType en son instance, après avoir déterminé le type concret. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Convertit la représentation chaîne d'un MultiDecodeType en son instance. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Convertit la représentation chaîne d'un SingleDecodeType en son instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] types)
```


Renvoie une valeur indiquant si cette instance est incluse dans la liste spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tableau de types de décodage simples et multiples |

**Returns:**
booléen - La valeur est vraie si un ou plusieurs types sont inclus dans
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Renvoie une valeur indiquant si cette instance est égale à une valeur [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| autre | com.aspose.barcode.barcoderecognition.MultiDecodeType |  |

**Returns:**
boolean
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Renvoie une valeur indiquant si cette instance est égale à une valeur [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Renvoie une valeur indiquant si cette instance est égale à une valeur [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Une valeur System.Object à comparer à cette instance. |

**Returns:**
booléen - Vrai si l'objet a la même valeur que cette instance ; sinon, faux.
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


Convertit l'instance de SingleDecodeType en sa représentation chaîne équivalente, en utilisant le format suivant : "Index:-1; Name:None".

**Returns:**
java.lang.String - Une chaîne représentant la valeur complète du type de décodage unique
### getString(SingleDecodeType instance) {#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public static String getString(SingleDecodeType instance)
```


Convertit l'instance de SingleDecodeType en sa représentation chaîne équivalente, en utilisant le format suivant : "Index:-1; Name:None".

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| instance | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | L'instance SingleDecodeType à convertir |

**Returns:**
java.lang.String - Une chaîne représentant la valeur complète du type de décodage unique donné
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


Obtient l'index du type de décodage

**Returns:**
short - L'index du type de décodage
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


Obtient le nom du type de décodage

**Returns:**
java.lang.String - Le nom du type de décodage
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie le code de hachage pour cette instance.

**Returns:**
int - Un code de hachage entier signé de 32 bits.
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


Convertit la représentation chaîne du nom d'un SingleDecodeType en son instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stringDecodeType | java.lang.String | Une chaîne contenant le nom d'un SingleDecodeType à convertir. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - the instance of , if conversion was successful; otherwise, it returns \{@link \}.
### toString() {#toString--}
```
public String toString()
```


Méthode remplacée représentant SingleDecodeType sous forme de chaîne Name.

**Returns:**
java.lang.String - Une chaîne représentant le nom du type de décodage unique
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
com.aspose.barcode.barcoderecognition.MultiDecodeType - Un MultiDecodeType réel est renvoyé lorsque la conversion s'est terminée avec succès;

sinon, elle renvoie un type indéfini. ou MultiDecodeType ("None").
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

