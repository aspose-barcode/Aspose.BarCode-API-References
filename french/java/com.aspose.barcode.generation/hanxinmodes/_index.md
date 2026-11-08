---
title: "HanXinModes"
second_title: "Référence API d'Aspose.BarCode pour Java"
description: "Mode d'encodage Han Xin Code."
type: docs
weight: 89
url: /fr/java/com.aspose.barcode.generation/hanxinmodes/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinModes extends Enum<HanXinModes>
```

Mode d'encodage Han Xin Code. Il est recommandé d'utiliser Auto avec les caractères ASCII / chinois ou Unicode pour les caractères Unicode.
## Champs

| Champ | Description |
| --- | --- |
| [AUTO](#AUTO) | Séquence de modes Numérique, Texte, ECI, Octets binaires et 4 modes GB18030 changeant automatiquement. |
| [BINARY](#BINARY) | Le mode octet binaire encode les données binaires sous n'importe quelle forme et les encode en leur octet binaire. |
| [COMMON_CHINESE_REGION_ONE](#COMMON-CHINESE-REGION-ONE) | Chaque caractère chinois commun de la Région Un est représenté par 12 bits. |
| [COMMON_CHINESE_REGION_TWO](#COMMON-CHINESE-REGION-TWO) | Chaque caractère chinois commun de la Région Deux est représenté par 12 bits. |
| [ECI](#ECI) | Mode d'interprétation de canal étendu (ECI) |
| [GB_18030_FOUR_BYTE](#GB-18030-FOUR-BYTE) | Chaque caractère de la région GB18030 de 4 octets est représenté par 21 bits. |
| [GB_18030_TWO_BYTE](#GB-18030-TWO-BYTE) | Chaque caractère de la région GB18030 de 2 octets est représenté par 15 bits. |
| [GS_1](#GS-1) | Le mode GS1 indique que les données représentées dans le Han Xin Code sont des données GS1 du système GS1 définies par la spécification générale GS1. |
| [NUMERIC](#NUMERIC) | Le mode numérique encode les données à partir de l'ensemble de chiffres décimaux (chiffres 0-9, valeurs d'octet 30HEX à 39HEX). |
| [TEXT](#TEXT) | Le mode texte encode les données à partir des symboles courants définis dans ISO/IEC 646, c.-à-d. |
| [UNICODE](#UNICODE) | Le mode Unicode conçoit une façon de représenter toute référence de données textuelles au codage/jeu de caractères UTF8 dans le code Han Xin. |
| [URI](#URI) | Le mode URI indique que les données représentées dans le code Han Xin sont une Uniform Resource Identifier (URI) selon la RFC 3986. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromValue(int value)](#fromValue-int-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AUTO {#AUTO}
```
public static final HanXinModes AUTO
```


Séquence de modes Numérique, Texte, ECI, Octets binaires et 4 modes GB18030 changeant automatiquement.

### BINARY {#BINARY}
```
public static final HanXinModes BINARY
```


Le mode octet binaire encode les données binaires sous n'importe quelle forme et les encode dans leur octet binaire. Chaque octet en mode Octet Binaire est représenté par 8 bits.

### COMMON_CHINESE_REGION_ONE {#COMMON-CHINESE-REGION-ONE}
```
public static final HanXinModes COMMON_CHINESE_REGION_ONE
```


Chaque caractère chinois commun de la Région Un est représenté par 12 bits. Les caractères chinois communs de la Région un comprennent les caractères dont la première valeur d'octet est comprise entre B0HEX et D7HEX et la deuxième valeur d'octet entre A1HEX et FEHEX (3760 caractères), ainsi que les caractères dont la première valeur d'octet est comprise entre A1HEX et A3HEX et la deuxième valeur d'octet entre A1HEX et FEHEX (282 caractères), et les caractères dont les valeurs d'octet sont comprises entre A8A1HEX et A8C0HEX (32 caractères).

### COMMON_CHINESE_REGION_TWO {#COMMON-CHINESE-REGION-TWO}
```
public static final HanXinModes COMMON_CHINESE_REGION_TWO
```


Chaque caractère chinois commun de la Région Deux est représenté par 12 bits. Les caractères chinois communs de la Région Deux comprennent les caractères dont la première valeur d'octet est comprise entre D8HEX et F7HEX, et la deuxième valeur d'octet entre A1HEX et FEHEX.

### ECI {#ECI}
```
public static final HanXinModes ECI
```


Mode d'interprétation de canal étendu (ECI)

### GB_18030_FOUR_BYTE {#GB-18030-FOUR-BYTE}
```
public static final HanXinModes GB_18030_FOUR_BYTE
```


Chaque caractère de la région GB18030 à 4 octets est représenté par 21 bits. La région GB18030 à 4 octets encode les données de tous les caractères de la région GB18030 à quatre octets (c.-à-d. les caractères dont la première valeur d'octet est comprise entre 81HEX et FEHEX, la deuxième entre 30HEX et 39HEX, la troisième entre 81HEX et FEHEX, et la quatrième entre 30HEX et 39HEX).

### GB_18030_TWO_BYTE {#GB-18030-TWO-BYTE}
```
public static final HanXinModes GB_18030_TWO_BYTE
```


Chaque caractère de la région GB18030 à 2 octets est représenté par 15 bits. La région GB18030 à 2 octets encode les données de tous les caractères (y compris les caractères chinois communs des Régions Un et Deux) de la région GB18030 à double octet, (c.-à-d. les caractères chinois dont la première valeur d'octet est comprise entre 81HEX et FEHEX et la deuxième valeur d'octet entre 40HEX et 7EHEX ou 80HEX et FEHEX).

### GS_1 {#GS-1}
```
public static final HanXinModes GS_1
```


Le mode GS1 indique que les données représentées dans le code Han Xin sont des données GS1 du système GS1 définies par la GS1 General Specification. Exemple de chaîne d'entrée : "(01)03453120000011(17)191125(10)ABCD1234(21)10".

### NUMERIC {#NUMERIC}
```
public static final HanXinModes NUMERIC
```


Le mode numérique encode les données à partir de l'ensemble de chiffres décimaux (chiffres 0-9, valeurs d'octet 30HEX à 39HEX). Normalement, 3 caractères de données sont représentés par 10 bits.

### TEXT {#TEXT}
```
public static final HanXinModes TEXT
```


Le mode texte encode les données à partir des symboles courants définis dans ISO/IEC 646, c.-à-d. les valeurs d'octet 00 HEX à 1B HEX et 20 HEX à 7F HEX.

### UNICODE {#UNICODE}
```
public static final HanXinModes UNICODE
```


Le mode Unicode conçoit une façon de représenter toute référence de données textuelles au codage/jeu de caractères UTF8 dans le code Han Xin.

### URI {#URI}
```
public static final HanXinModes URI
```


Le mode URI indique que les données représentées dans le code Han Xin sont une Uniform Resource Identifier (URI) selon la RFC 3986.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static HanXinModes fromValue(int value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

**Returns:**
com.aspose.barcode.generation.HanXinModes
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static HanXinModes valueOf(String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
com.aspose.barcode.generation.HanXinModes
### values() {#values--}
```
public static HanXinModes[] values()
```




**Returns:**
com.aspose.barcode.generation.HanXinModes[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
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

