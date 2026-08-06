---
title: Pdf417EncodeMode
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Mode d'encodage du code-barres Pdf417
type: docs
weight: 99
url: /fr/androidjava/com.aspose.barcode.generation/pdf417encodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Pdf417EncodeMode extends Enum<Pdf417EncodeMode>
```

Mode d'encodage du code-barres Pdf417
## Champs

| Champ | Description |
| --- | --- |
| [AUTO](#AUTO) | En mode Auto, le CodeText est encodé avec une compacité maximale des données. |
| [BINARY](#BINARY) | En mode Binaire, le CodeText est encodé avec une compacité maximale des données. |
| [ECI](#ECI) | En mode ECI, le message complet est ré‑encodé dans l’encodage spécifié ECIEncoding avec l’insertion d’un identifiant ECI. |
| [EXTENDED](#EXTENDED) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
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
public static final Pdf417EncodeMode AUTO
```


En mode Auto, le CodeText est encodé avec une compacité maximale des données. Les caractères Unicode sont ré‑encodés dans l’encodage spécifié ECIEncoding avec l’insertion d’un identifiant ECI. Si un caractère est trouvé qui n’est pas pris en charge par l’encodage ECI sélectionné, une exception est levée.

### BINARY {#BINARY}
```
public static final Pdf417EncodeMode BINARY
```


En mode Binaire, le CodeText est encodé avec une compacité maximale des données. Si un caractère Unicode est trouvé, une exception est levée.

### ECI {#ECI}
```
public static final Pdf417EncodeMode ECI
```


En mode ECI, le message complet est ré‑encodé dans l’encodage spécifié ECIEncoding avec l’insertion d’un identifiant ECI. Si un caractère est trouvé qui n’est pas pris en charge par l’encodage ECI sélectionné, une exception est levée. Veuillez noter que certains scanners anciens (pré‑2006) peuvent ne pas prendre en charge ce mode.

### EXTENDED {#EXTENDED}
```
public static final Pdf417EncodeMode EXTENDED
```


Mode étendu qui prend en charge plusieurs modes ECI.

Il est préférable d'utiliser Pdf417ExtCodetextBuilder pour la génération de texte de code étendu.

Utilisez la propriété Display2DText pour définir le texte visible en supprimant les caractères de gestion.

Les identifiants ECI sont définis comme une barre oblique unique et un identifiant à six chiffres "\\000026" - identifiant ECI UTF‑8.

Tous les caractères Unicode après l’identifiant ECI sont automatiquement encodés dans le jeu de caractères correct.

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
### fromValue(int value) {#fromValue-int-}
```
public static Pdf417EncodeMode fromValue(int value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
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
public static Pdf417EncodeMode valueOf(String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### values() {#values--}
```
public static Pdf417EncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.Pdf417EncodeMode[]
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

