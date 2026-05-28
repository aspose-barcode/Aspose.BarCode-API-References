---
title: MultyDecodeType
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Type de décodage composite.
type: docs
weight: 38
url: /fr/androidjava/com.aspose.barcode.barcoderecognition/multydecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype), com.aspose.barcode.barcoderecognition.MultiDecodeType
```
public class MultyDecodeType extends MultiDecodeType
```

Type de décodage composite.

--------------------

> ```
> CreateThis sample shows how to create compound MultyDecode types that combine SingleDecodeType and MultiDecode types.
>  
>  MultyDecodeType types1 = new MultyDecodeType(DecodeType.QR, DecodeType.DATA_MATRIX);
>  MultyDecodeType types2 = new MultyDecodeType(types1, DecodeType.CODE_128, DecodeType.CODE_39);
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MultyDecodeType(SingleDecodeType[] barcodeTypes)](#MultyDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | Initialise une nouvelle instance de la classe [MultyDecodeType](../../com.aspose.barcode.barcoderecognition/multydecodetype). |
| [MultyDecodeType(BaseDecodeType[] barcodeTypes)](#MultyDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Initialise une nouvelle instance de la classe [MultyDecodeType](../../com.aspose.barcode.barcoderecognition/multydecodetype). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [add(SingleDecodeType singleType)](#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Ajoute un autre [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) au MultiDecodeType. |
| [containsAll(BaseDecodeType[] barcodeTypes)](#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Vérifiez si cela contient tous les types de codes-barres. |
| [containsAny(BaseDecodeType[] decodeTypes)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Contient-il l'un des types |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Renvoie une valeur indiquant si cette instance est égale à une valeur MultiDecodeType spécifiée. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Renvoie une valeur indiquant si cette collection de types de décodage ne contient que la valeur [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) spécifiée. |
| [equals(Object obj)](#equals-java.lang.Object-) | Renvoie une valeur indiquant si cette instance est égale à une valeur MultiDecodeType spécifiée. |
| [exclude(SingleDecodeType singleType)](#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Exclut [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) du MultiDecodeType et renvoie une nouvelle instance de MultiDecodeType. |
| [getClass()](#getClass--) |  |
| [getSingleTypes()](#getSingleTypes--) | Représente une liste de types simples. |
| [getSingleTypesCount()](#getSingleTypesCount--) | Renvoie le nombre de types simples. |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Méthode remplacée représentant le MultiDecodeType sous forme de chaîne. |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Convertit la représentation chaîne d'un BaseDecodeType en son instance, après avoir déterminé le type concret. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Convertit la représentation chaîne d'un MultiDecodeType en son instance. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Convertit la représentation chaîne d'un SingleDecodeType en son instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultyDecodeType(SingleDecodeType[] barcodeTypes) {#MultyDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public MultyDecodeType(SingleDecodeType[] barcodeTypes)
```


Initialise une nouvelle instance de la classe [MultyDecodeType](../../com.aspose.barcode.barcoderecognition/multydecodetype).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Tableau de types de décodage simples |

### MultyDecodeType(BaseDecodeType[] barcodeTypes) {#MultyDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public MultyDecodeType(BaseDecodeType[] barcodeTypes)
```


Initialise une nouvelle instance de la classe [MultyDecodeType](../../com.aspose.barcode.barcoderecognition/multydecodetype).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tableau de types de décodage multiples et simples. |

### add(SingleDecodeType singleType) {#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final void add(SingleDecodeType singleType)
```


Ajoute un autre [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) au MultiDecodeType.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Un Single DecodeType à ajouter à la liste |

### containsAll(BaseDecodeType[] barcodeTypes) {#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public final boolean containsAll(BaseDecodeType[] barcodeTypes)
```


Vérifiez si cela contient tous les types de codes-barres.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Entrée des types de codes-barres simples ou multiples. |

**Returns:**
booléen - La valeur est vraie si tous les types sont inclus dans
### containsAny(BaseDecodeType[] decodeTypes) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] decodeTypes)
```


Contient-il l'un des types

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Types de décodage |

**Returns:**
booléen - La valeur est vraie si un ou plusieurs types sont inclus dans
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Renvoie une valeur indiquant si cette instance est égale à une valeur MultiDecodeType spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| autre | com.aspose.barcode.barcoderecognition.MultiDecodeType | Une valeur MultiDecodeType à comparer à cette instance. |

**Returns:**
boolean -  **true**  si obj a la même valeur que cette instance ; sinon,  **false** .
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Renvoie une valeur indiquant si cette collection de types de décodage ne contient que la valeur [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Une valeur [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) à comparer à cette collection de types de décodage. |

**Returns:**
booléen - **true** si cette collection ne contient que le type de décodage spécifié ; sinon, **false**.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Renvoie une valeur indiquant si cette instance est égale à une valeur MultiDecodeType spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Une valeur System.Object à comparer à cette instance. |

**Returns:**
boolean -  **true**  si obj a la même valeur que cette instance ; sinon,  **false** .
### exclude(SingleDecodeType singleType) {#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final MultiDecodeType exclude(SingleDecodeType singleType)
```


Exclut [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) du MultiDecodeType et renvoie une nouvelle instance de MultiDecodeType.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Un type de décodage unique à exclure. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - Nouvelle instance de MultiDecodeType avec le SingleDecodeType exclu.
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


Représente une liste de types simples.

**Returns:**
java.util.List<com.aspose.barcode.barcoderecognition.SingleDecodeType> - Liste des types uniques
### getSingleTypesCount() {#getSingleTypesCount--}
```
public final int getSingleTypesCount()
```


Renvoie le nombre de types simples.

**Returns:**
int
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




### toString() {#toString--}
```
public String toString()
```


Méthode remplacée représentant le MultiDecodeType sous forme de chaîne.

**Returns:**
java.lang.String - Une chaîne représentant l'instance MultiDecodeType sous la forme "singleDecodeType1, singleDecodeType2, ..."

 **"AllSupportedTypes"**  returns when all types are included.
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

