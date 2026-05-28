---
title: HanXinModes
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Mode d'encodage Han Xin Code.
type: docs
weight: 91
url: /fr/androidjava/com.aspose.barcode.generation/hanxinmodes/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinModes extends Enum<HanXinModes>
```

Mode d'encodage Han Xin Code. Il est recommandé d'utiliser Auto avec des caractères ASCII / chinois ou Unicode pour les caractères Unicode.
## Champs

| Champ | Description |
| --- | --- |
| [AUTO](#AUTO) | Séquence des modes Numérique, Texte, ECI, Octets binaires et 4 GB18030 changeant automatiquement. |
| [BINARY](#BINARY) | Le mode octet binaire encode les données binaires sous n'importe quelle forme et les encode dans leur octet binaire. |
| [COMMON_CHINESE_REGION_ONE](#COMMON-CHINESE-REGION-ONE) | Chaque caractère chinois commun de la région un est représenté par 12 bits. |
| [COMMON_CHINESE_REGION_TWO](#COMMON-CHINESE-REGION-TWO) | Chaque caractère chinois commun de la région deux est représenté par 12 bits. |
| [ECI](#ECI) | Mode d'interprétation de canal étendu (ECI) |
| [GB_18030_FOUR_BYTE](#GB-18030-FOUR-BYTE) | Chaque caractère de la région 4 octets GB18030 est représenté par 21 bits. |
| [GB_18030_TWO_BYTE](#GB-18030-TWO-BYTE) | Chaque caractère de la région 2 octets GB18030 est représenté par 15 bits. |
| [GS_1](#GS-1) | Le mode GS1 indique que les données représentées dans Han Xin Code sont des données GS1 du système GS1 définies par la spécification générale GS1. |
| [NUMERIC](#NUMERIC) | Le mode numérique encode les données à partir de l'ensemble de chiffres décimaux (chiffres 0-9, valeurs d'octet 30HEX à 39HEX). |
| [TEXT](#TEXT) | Le mode texte encode les données à partir des symboles courants définis dans ISO/IEC 646, c’est‑à‑dire. |
| [UNICODE](#UNICODE) | Le mode Unicode conçoit une méthode pour représenter toute donnée textuelle référencée à l'encodage/jeu de caractères UTF8 dans Han Xin Code. |
| [URI](#URI) | Le mode URI indique que les données représentées dans Han Xin Code sont une référence Uniform Resource Identifier (URI) à la RFC 3986. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
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


Séquence des modes Numérique, Texte, ECI, Octets binaires et 4 GB18030 changeant automatiquement.

### BINARY {#BINARY}
```
public static final HanXinModes BINARY
```


Le mode octet binaire encode les données binaires sous n'importe quelle forme et les encode dans leur octet binaire. Chaque octet en mode Octet Binaire est représenté par 8 bits.

### COMMON_CHINESE_REGION_ONE {#COMMON-CHINESE-REGION-ONE}
```
public static final HanXinModes COMMON_CHINESE_REGION_ONE
```


Chaque caractère chinois commun de la région un est représenté par 12 bits. Les caractères chinois communs de la région un comprennent les caractères dont la première valeur d'octet est comprise entre B0HEX et D7HEX et la deuxième valeur d'octet entre A1HEX et FEHEX (3760 caractères), ainsi que les caractères dont la première valeur d'octet est comprise entre A1HEX et A3HEX et la deuxième valeur d'octet entre A1HEX et FEHEX (282 caractères), et les caractères dont les valeurs d'octet sont comprises entre A8A1HEX et A8C0HEX (32 caractères).

### COMMON_CHINESE_REGION_TWO {#COMMON-CHINESE-REGION-TWO}
```
public static final HanXinModes COMMON_CHINESE_REGION_TWO
```


Chaque caractère chinois commun de la région deux est représenté par 12 bits. Les caractères chinois communs de la région deux comprennent les caractères dont la première valeur d'octet est comprise entre D8HEX et F7HEX et la deuxième valeur d'octet entre A1HEX et FEHEX.

### ECI {#ECI}
```
public static final HanXinModes ECI
```


Mode d'interprétation de canal étendu (ECI)

### GB_18030_FOUR_BYTE {#GB-18030-FOUR-BYTE}
```
public static final HanXinModes GB_18030_FOUR_BYTE
```


Chaque caractère de la région 4 octets GB18030 est représenté par 21 bits. La région 4 octets GB18030 encode les données de tous les caractères de la région à quatre octets GB18030 (c’est‑à‑dire les caractères dont la première valeur d'octet est comprise entre 81HEX et FEHEX, la deuxième valeur d'octet entre 30HEX et 39HEX, la troisième valeur d'octet entre 81HEX et FEHEX, et la quatrième valeur d'octet entre 30HEX et 39HEX).

### GB_18030_TWO_BYTE {#GB-18030-TWO-BYTE}
```
public static final HanXinModes GB_18030_TWO_BYTE
```


Chaque caractère de la région 2 octets GB18030 est représenté par 15 bits. La région 2 octets GB18030 encode les données de tous les caractères (y compris les caractères chinois communs des régions un et deux) de la région à deux octets GB18030, (c’est‑à‑dire les caractères chinois dont la première valeur d'octet est comprise entre 81HEX et FEHEX et la deuxième valeur d'octet entre 40HEX et 7EHEX ou 80HEX et FEHEX).

### GS_1 {#GS-1}
```
public static final HanXinModes GS_1
```


Le mode GS1 indique que les données représentées dans Han Xin Code sont des données GS1 du système GS1 définies par la spécification générale GS1. Exemple de chaîne d'entrée : "(01)03453120000011(17)191125(10)ABCD1234(21)10".

### NUMERIC {#NUMERIC}
```
public static final HanXinModes NUMERIC
```


Le mode numérique encode les données à partir de l'ensemble de chiffres décimaux (chiffres 0-9, valeurs d'octet 30HEX à 39HEX). Normalement, 3 caractères de données sont représentés par 10 bits.

### TEXT {#TEXT}
```
public static final HanXinModes TEXT
```


Le mode texte encode les données à partir des symboles courants définis dans ISO/IEC 646, c’est‑à‑dire les valeurs d'octet 00 HEX à 1B HEX et 20 HEX à 7F HEX.

### UNICODE {#UNICODE}
```
public static final HanXinModes UNICODE
```


Le mode Unicode conçoit une méthode pour représenter toute donnée textuelle référencée à l'encodage/jeu de caractères UTF8 dans Han Xin Code.

### URI {#URI}
```
public static final HanXinModes URI
```


Le mode URI indique que les données représentées dans Han Xin Code sont une référence Uniform Resource Identifier (URI) à la RFC 3986.

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
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
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

