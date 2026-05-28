---
title: BaseEncodeType
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Classe de base pour SymbologyEncodeType.
type: docs
weight: 16
url: /fr/androidjava/com.aspose.barcode.generation/baseencodetype/
---
**Inheritance:**
java.lang.Object
```
public class BaseEncodeType
```

Classe de base pour SymbologyEncodeType.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object other)](#equals-java.lang.Object-) | Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée de BaseEncodeType. |
| [getClass()](#getClass--) |  |
| [getClassification()](#getClassification--) | Obtient une classification de cette symbologie. |
| [getString()](#getString--) | Convertit l'instance de BaseEncodeType en sa représentation sous forme de chaîne équivalente. |
| [getString(BaseEncodeType instance)](#getString-com.aspose.barcode.generation.BaseEncodeType-) | Convertit l'instance de BaseEncodeType en sa représentation sous forme de chaîne équivalente. |
| [getTypeIndex()](#getTypeIndex--) | Obtient un index du type d'encodage |
| [getTypeName()](#getTypeName--) | Obtient un nom du type d'encodage |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String stringEncodeType)](#parse-java.lang.String-) | Convertit la représentation sous forme de chaîne du nom d'un BaseEncodeType en son instance. |
| [toString()](#toString--) | Renvoie le nom du BaseEncodeType donné sous forme de chaîne. |
| [tryParse(String parsingType, BaseEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---) | Convertit la représentation sous forme de chaîne d'un BaseEncodeType en son instance. |
| [tryParse(String parsingType, SymbologyEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---) | Convertit la représentation sous forme de chaîne d'un BaseEncodeType en son instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée de BaseEncodeType.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| autre | java.lang.Object | Une valeur BaseEncodeType à comparer à cette instance. |

**Returns:**
boolean -  **true**  si obj a la même valeur que cette instance ; sinon,  **false** .
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


Obtient une classification de cette symbologie.

**Returns:**
[BarcodeClassifications](../../com.aspose.barcode.generation/barcodeclassifications)
### getString() {#getString--}
```
public String getString()
```


Convertit l'instance de BaseEncodeType en sa représentation sous forme de chaîne équivalente. Le format de la chaîne est : "Index:0; Name:Codabar".

**Returns:**
java.lang.String - Une chaîne représentant la valeur complète du type d'encodage
### getString(BaseEncodeType instance) {#getString-com.aspose.barcode.generation.BaseEncodeType-}
```
public static String getString(BaseEncodeType instance)
```


Convertit l'instance de BaseEncodeType en sa représentation sous forme de chaîne équivalente. Le format de la chaîne est : "Index:-1; Name:None".

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| instance | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | L'instance de BaseEncodeType à convertir |

**Returns:**
java.lang.String - Une chaîne représentant la valeur complète du type d'encodage donné
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


Obtient un index du type d'encodage

**Returns:**
short
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


Obtient un nom du type d'encodage

**Returns:**
java.lang.String
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




### parse(String stringEncodeType) {#parse-java.lang.String-}
```
public static BaseEncodeType parse(String stringEncodeType)
```


Convertit la représentation sous forme de chaîne du nom d'un BaseEncodeType en son instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stringEncodeType | java.lang.String | Une chaîne contenant le nom d'un BaseEncodeType à convertir. |

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - the instance of , if conversion was successful; otherwise, it returns   .
### toString() {#toString--}
```
public String toString()
```


Renvoie le nom du BaseEncodeType donné sous forme de chaîne.

**Returns:**
java.lang.String - Une chaîne représentant le nom du type d'encodage
### tryParse(String parsingType, BaseEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---}
```
public static boolean tryParse(String parsingType, BaseEncodeType[] result)
```


Convertit la représentation sous forme de chaîne d'un BaseEncodeType en son instance. La valeur de retour indique si la conversion a réussi ou échoué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | Une chaîne au format "Index:-1; Name:None" à convertir. |
|  | result | [BaseEncodeType\[\]](../../com.aspose.barcode.generation/baseencodetype) | Un SingleEncodeType réel est renvoyé lorsque la conversion s'est terminée avec succès ; |

sinon il renvoie null. |

**Returns:**
boolean -  **true**  si s a été converti avec succès ; sinon,  **false** .
### tryParse(String parsingType, SymbologyEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---}
```
public static boolean tryParse(String parsingType, SymbologyEncodeType[] result)
```


Convertit la représentation sous forme de chaîne d'un BaseEncodeType en son instance. La valeur de retour indique si la conversion a réussi ou échoué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | Une chaîne au format "Index:-1; Name:None" à convertir. |
|  | result | [SymbologyEncodeType\[\]](../../com.aspose.barcode.generation/symbologyencodetype) | Un SingleEncodeType réel est renvoyé lorsque la conversion s'est terminée avec succès ; |

sinon il renvoie null. |

**Returns:**
boolean -  **true**  si s a été converti avec succès ; sinon,  **false** .
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

