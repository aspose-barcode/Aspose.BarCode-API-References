---
title: PrimaryData
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Classe pour stocker les données primaires HIBC LIC.
type: docs
weight: 34
url: /fr/androidjava/com.aspose.barcode.complexbarcode/primarydata/
---
**Inheritance:**
java.lang.Object
```
public class PrimaryData
```

Classe pour stocker les données primaires HIBC LIC.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PrimaryData()](#PrimaryData--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Renvoie une valeur indiquant si cette instance est égée à une valeur spécifiée PrimaryData. |
| [getClass()](#getClass--) |  |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Identifie la date du code d'identification de l'étiqueteur. |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Identifie le numéro de produit ou de catalogue. |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Identifie l'ID de l'unité de mesure. |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String primaryDataCodetext)](#parseFromString-java.lang.String-) | Instancie les données principales à partir d'un format de chaîne conformément à la spécification HIBC LIC. |
| [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Identifie la date du code d'identification de l'étiqueteur. |
| [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Identifie le numéro de produit ou de catalogue. |
| [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Identifie l'ID de l'unité de mesure. |
| [toString()](#toString--) | Convertit les données au format de chaîne selon la spécification HIBC LIC. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrimaryData() {#PrimaryData--}
```
public PrimaryData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Renvoie une valeur indiquant si cette instance est égée à une valeur spécifiée PrimaryData.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Une valeur PrimaryData à comparer à cette instance. |

**Returns:**
boolean -  **true**  si obj a la même valeur que cette instance ; sinon,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public String getLabelerIdentificationCode()
```


Identifie la date du code d'identification du labelisateur. Le code d'identification du labelisateur doit être une chaîne alphanumérique de 4 symboles, le premier caractère étant toujours alphabétique.

**Returns:**
java.lang.String
### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public String getProductOrCatalogNumber()
```


Identifie le numéro de produit ou de catalogue. Le numéro de produit ou de catalogue doit être une chaîne alphanumérique d'une longueur maximale de 18 symboles.

**Returns:**
java.lang.String
### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public int getUnitOfMeasureID()
```


Identifie l'ID de l'unité de mesure. L'ID de l'unité de mesure doit être une valeur entière de 0 à 9.

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




### parseFromString(String primaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String primaryDataCodetext)
```


Instancie les données principales à partir d'un format de chaîne conformément à la spécification HIBC LIC.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| primaryDataCodetext | java.lang.String | Chaîne formatée. |

### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public void setLabelerIdentificationCode(String value)
```


Identifie la date du code d'identification du labelisateur. Le code d'identification du labelisateur doit être une chaîne alphanumérique de 4 symboles, le premier caractère étant toujours alphabétique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public void setProductOrCatalogNumber(String value)
```


Identifie le numéro de produit ou de catalogue. Le numéro de produit ou de catalogue doit être une chaîne alphanumérique d'une longueur maximale de 18 symboles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public void setUnitOfMeasureID(int value)
```


Identifie l'ID de l'unité de mesure. L'ID de l'unité de mesure doit être une valeur entière de 0 à 9.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### toString() {#toString--}
```
public String toString()
```


Convertit les données au format de chaîne selon la spécification HIBC LIC.

**Returns:**
java.lang.String - Chaîne formatée.
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

