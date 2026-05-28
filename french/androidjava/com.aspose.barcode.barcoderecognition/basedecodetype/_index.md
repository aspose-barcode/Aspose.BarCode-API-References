---
title: BaseDecodeType
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Classe de base pour MultiDecodeType et SingleDecodeType.
type: docs
weight: 23
url: /fr/androidjava/com.aspose.barcode.barcoderecognition/basedecodetype/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseDecodeType
```

Classe de base pour MultiDecodeType et SingleDecodeType.

--------------------

> ```
> This sample shows how to use BaseDecodeType with SingleDecodeType and MultiDecodeType
>  
>  BaseDecodeType decodeOne = DecodeType.CODE_128;
>  BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.CODE_128, DecodeType.CODE_39_STANDARD, DecodeType.CODE_39_FULL_ASCII);
> ```
## Méthodes

| Méthode | Description |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Détermine si l'un des types de décodage fournis est inclus dans |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Renvoie une valeur indiquant si cette instance est égale à une valeur [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) spécifiée. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Renvoie une valeur indiquant si cette instance est égale à une valeur [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) spécifiée. |
| [equals(Object other)](#equals-java.lang.Object-) | Renvoie une valeur indiquant si cette instance est égale à une valeur [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) spécifiée. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Convertit la représentation chaîne d'un BaseDecodeType en son instance, après avoir déterminé le type concret. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Convertit la représentation chaîne d'un MultiDecodeType en son instance. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Convertit la représentation chaîne d'un SingleDecodeType en son instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public abstract boolean containsAny(BaseDecodeType[] types)
```


Détermine si l'un des types de décodage fournis est inclus dans

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Types à vérifier. |

**Returns:**
boolean - La valeur est vraie si un type quelconque est inclus dans.
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Renvoie une valeur indiquant si cette instance est égale à une valeur [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| autre | com.aspose.barcode.barcoderecognition.MultiDecodeType | Une valeur java.lang.Object à comparer à cette instance. |

**Returns:**
booléen - Vrai si l'objet a la même valeur que cette instance ; sinon, faux.
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
booléen - Vrai si l'objet a la même valeur que cette instance ; sinon, faux.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Renvoie une valeur indiquant si cette instance est égale à une valeur [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| autre | java.lang.Object | Une valeur java.lang.Object à comparer à cette instance. |

**Returns:**
booléen - Vrai si l'objet a la même valeur que cette instance ; sinon, faux.
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

