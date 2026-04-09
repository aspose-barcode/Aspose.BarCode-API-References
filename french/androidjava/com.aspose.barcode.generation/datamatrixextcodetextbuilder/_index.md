---
title: DataMatrixExtCodetextBuilder
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: 
type: docs
weight: 33
url: /fr/androidjava/com.aspose.barcode.generation/datamatrixextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DataMatrixExtCodetextBuilder extends ExtCodetextBuilder
```

Générateur de texte de code étendu pour les codes-barres DataMatrix 2D en mode ExtendedCodetext de EncodeMode.

--------------------

> ```
> //Extended codetext mode
>  //create codetext
>  DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
>  codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.BYTES, "World");
>  codetextBuilder.addPlainCodetext("Will");
>  codetextBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  codetextBuilder.addCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");
>  //generate codetext
>  String codetext = textBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DataMatrixExtCodetextBuilder()](#DataMatrixExtCodetextBuilder--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext)](#addCodetextWithEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-) | Ajoute du texte de code avec le mode d’encodage défini aux éléments de texte de code étendu. |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Ajoute du codetext avec un identifiant de canal étendu. |
| [addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext)](#addECICodetextWithEncodeMode-int-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-) | Ajoute du texte de code avec l’identifiant de canal étendu avec le mode d’encodage défini. |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Ajoute du texte de code simple aux éléments de texte de code étendu |
| [clear()](#clear--) | Efface les éléments de texte de code étendu |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Génère du texte de code étendu à partir de la liste de texte de code étendu. |
| [hashCode()](#hashCode--) |  |
| [isNeedToShieldItemFromPrevECI(int Index)](#isNeedToShieldItemFromPrevECI-int-) | Vérifie la nécessité de protéger l'élément précédent par "\\000000" |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataMatrixExtCodetextBuilder() {#DataMatrixExtCodetextBuilder--}
```
public DataMatrixExtCodetextBuilder()
```


### addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext) {#addCodetextWithEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-}
```
public void addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext)
```


Ajoute du texte de code avec le mode d’encodage défini aux éléments de texte de code étendu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encodeMode | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Valeur du mode d’encodage |
| texte de code | java.lang.String | Texte de code en Unicode à ajouter en tant qu'élément de texte de code étendu |

### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public void addECICodetext(int ECIEncoding, String codetext)
```


Ajoute du codetext avec un identifiant de canal étendu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ECIEncoding | int | Identifiant de canal étendu |
| texte de code | java.lang.String | Texte de code en Unicode à ajouter en tant qu'élément de texte de code étendu avec l'identifiant de canal étendu |

### addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext) {#addECICodetextWithEncodeMode-int-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-}
```
public void addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext)
```


Ajoute du texte de code avec l’identifiant de canal étendu avec le mode d’encodage défini.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ECIEncoding | int | Identifiant de canal étendu |
| encodeMode | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Valeur du mode d’encodage |
| texte de code | java.lang.String | Texte de code en Unicode à ajouter comme élément de texte de code étendu avec l’identifiant de canal étendu et le mode d’encodage défini. |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public void addPlainCodetext(String codetext)
```


Ajoute du texte de code simple aux éléments de texte de code étendu

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte de code | java.lang.String | Texte de code en Unicode à ajouter en tant qu'élément de texte de code étendu |

### clear() {#clear--}
```
public void clear()
```


Efface les éléments de texte de code étendu

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
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
### getExtendedCodetext() {#getExtendedCodetext--}
```
public String getExtendedCodetext()
```


Génère du texte de code étendu à partir de la liste de texte de code étendu.

**Returns:**
java.lang.String - Texte de code étendu en tant que chaîne
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isNeedToShieldItemFromPrevECI(int Index) {#isNeedToShieldItemFromPrevECI-int-}
```
public boolean isNeedToShieldItemFromPrevECI(int Index)
```


Vérifie la nécessité de protéger l'élément précédent par "\\000000"

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| Indice | int | Indice dans m\_List |

**Returns:**
booléen - Nécessité de protéger
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

