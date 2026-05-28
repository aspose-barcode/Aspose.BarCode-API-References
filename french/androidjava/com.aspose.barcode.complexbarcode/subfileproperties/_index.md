---
title: USADriveIdCodetext.SubfileProperties
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Les décalages et longueurs des sous‑fichiers du permis de conduire américain (USA DL) sont définis automatiquement.
type: docs
weight: 12
url: /fr/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.SubfileProperties
```

Les propriétés du sous-fichier USA DL, le décalage et la longueur sont définis automatiquement.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SubfileProperties(String type)](#SubfileProperties-java.lang.String-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 4 Ces octets contiennent une valeur numérique à 4 chiffres qui indique la longueur du Subfile en octets. Le terminateur de segment doit être inclus dans le calcul de la longueur du sous‑fichier. Un terminateur de segment = 1. |
| [getOffset()](#getOffset--) | Valeur numérique à 4 chiffres qui indique le nombre d'octets depuis le début du fichier jusqu'à l'emplacement des données liées au sous‑fichier particulier. Le premier octet du fichier se trouve à l'offset 0. |
| [getType()](#getType--) | Type de sous‑fichier sur 2 octets, comme "DL" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLength(int value)](#setLength-int-) | 4 Ces octets contiennent une valeur numérique à 4 chiffres qui indique la longueur du Subfile en octets. Le terminateur de segment doit être inclus dans le calcul de la longueur du sous‑fichier. Un terminateur de segment = 1. |
| [setOffset(int value)](#setOffset-int-) | Valeur numérique à 4 chiffres qui indique le nombre d'octets depuis le début du fichier jusqu'à l'emplacement des données liées au sous‑fichier particulier. Le premier octet du fichier se trouve à l'offset 0. |
| [setType(String value)](#setType-java.lang.String-) | Type de sous‑fichier sur 2 octets, comme "DL" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SubfileProperties(String type) {#SubfileProperties-java.lang.String-}
```
public SubfileProperties(String type)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | java.lang.String |  |

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
### getLength() {#getLength--}
```
public final int getLength()
```


4 Ces octets contiennent une valeur numérique à 4 chiffres qui spécifie la longueur du Subfile en octets. Le terminateur de segment doit être inclus dans le calcul de la longueur du sous‑fichier. Un terminateur de segment = 1. Chaque sous‑fichier doit commencer par le Type de Subfile à deux caractères et ces deux caractères doivent également être inclus dans la longueur.

**Returns:**
int
### getOffset() {#getOffset--}
```
public final int getOffset()
```


Valeur numérique à 4 chiffres qui indique le nombre d'octets depuis le début du fichier jusqu'à l'emplacement des données liées au sous‑fichier particulier. Le premier octet du fichier se trouve à l'offset 0.

**Returns:**
int
### getType() {#getType--}
```
public final String getType()
```


Type de sous‑fichier sur 2 octets, comme "DL"

**Returns:**
java.lang.String
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




### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


4 Ces octets contiennent une valeur numérique à 4 chiffres qui spécifie la longueur du Subfile en octets. Le terminateur de segment doit être inclus dans le calcul de la longueur du sous‑fichier. Un terminateur de segment = 1. Chaque sous‑fichier doit commencer par le Type de Subfile à deux caractères et ces deux caractères doivent également être inclus dans la longueur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setOffset(int value) {#setOffset-int-}
```
public final void setOffset(int value)
```


Valeur numérique à 4 chiffres qui indique le nombre d'octets depuis le début du fichier jusqu'à l'emplacement des données liées au sous‑fichier particulier. Le premier octet du fichier se trouve à l'offset 0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setType(String value) {#setType-java.lang.String-}
```
public final void setType(String value)
```


Type de sous‑fichier sur 2 octets, comme "DL"

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

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

