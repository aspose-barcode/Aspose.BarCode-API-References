---
title: MailmarkCodetext
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Classe pour encoder et décoder le texte intégré dans le code Royal Mailmark à 4 états.
type: docs
weight: 24
url: /fr/androidjava/com.aspose.barcode.complexbarcode/mailmarkcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class MailmarkCodetext implements IComplexCodetext
```

Classe pour encoder et décoder le texte intégré dans le code Royal Mailmark à 4 états.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MailmarkCodetext()](#MailmarkCodetext--) | Initialise une nouvelle instance de la classe MailmarkCodetext. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Obtient le type de code-barres. |
| [getClass()](#getClass--) |  |
| [getClass_()](#getClass---) | "0" - Null ou Test "1" - 1C (Vente au détail) "2" - 2C (Vente au détail) "3" - 3C (Vente au détail) "4" - Premium (Mail de Publication au détail) (pour une utilisation future éventuelle) "5" - Différé (Vente au détail) "6" - Air (Vente au détail) (pour une utilisation future éventuelle) "7" - Surface (Vente au détail) (pour une utilisation future éventuelle) "8" - Premium (Accès réseau) "9" - Standard (Accès réseau) |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construire le texte de code à partir des données Mailmark. |
| [getDestinationPostCodePlusDPS()](#getDestinationPostCodePlusDPS--) | Le PC et le DP doivent être conformes à un format PAF. |
| [getFormat()](#getFormat--) | "0" \\u2013 Null ou Test "1" \\u2013 Lettre "2" \\u2013 Grande Lettre |
| [getItemID()](#getItemID--) | La valeur maximale est 99999999. |
| [getSupplychainID()](#getSupplychainID--) | Les valeurs maximales sont 99 pour le code-barres C et 999999 pour le code-barres L. |
| [getVersionID()](#getVersionID--) | Actuellement "1" \\u2013 Pour le code-barres Mailmark (0 et 2 à 9 ainsi que A à Z réservés pour une utilisation future) |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initialise les données Mailmark à partir du texte de code construit. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClass(String value)](#setClass-java.lang.String-) | "0" - Null ou Test "1" - 1C (Vente au détail) "2" - 2C (Vente au détail) "3" - 3C (Vente au détail) "4" - Premium (Mail de Publication au détail) (pour une utilisation future éventuelle) "5" - Différé (Vente au détail) "6" - Air (Vente au détail) (pour une utilisation future éventuelle) "7" - Surface (Vente au détail) (pour une utilisation future éventuelle) "8" - Premium (Accès réseau) "9" - Standard (Accès réseau) |
| [setDestinationPostCodePlusDPS(String value)](#setDestinationPostCodePlusDPS-java.lang.String-) | Le PC et le DP doivent être conformes à un format PAF. |
| [setFormat(int value)](#setFormat-int-) | "0" \\u2013 Null ou Test "1" \\u2013 Lettre "2" \\u2013 Grande Lettre |
| [setItemID(int value)](#setItemID-int-) | La valeur maximale est 99999999. |
| [setSupplychainID(int value)](#setSupplychainID-int-) | Les valeurs maximales sont 99 pour le code-barres C et 999999 pour le code-barres L. |
| [setVersionID(int value)](#setVersionID-int-) | Actuellement "1" \\u2013 Pour le code-barres Mailmark (0 et 2 à 9 ainsi que A à Z réservés pour une utilisation future) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailmarkCodetext() {#MailmarkCodetext--}
```
public MailmarkCodetext()
```


Initialise une nouvelle instance de la classe MailmarkCodetext.

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
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Obtient le type de code-barres.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClass_() {#getClass---}
```
public String getClass_()
```


"0" - Null ou Test "1" - 1C (Vente au détail) "2" - 2C (Vente au détail) "3" - 3C (Vente au détail) "4" - Premium (Mail de Publication au détail) (pour une utilisation future éventuelle) "5" - Différé (Vente au détail) "6" - Air (Vente au détail) (pour une utilisation future éventuelle) "7" - Surface (Vente au détail) (pour une utilisation future éventuelle) "8" - Premium (Accès réseau) "9" - Standard (Accès réseau)

**Returns:**
java.lang.String
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Construire le texte de code à partir des données Mailmark.

**Returns:**
java.lang.String - Texte de code construit
### getDestinationPostCodePlusDPS() {#getDestinationPostCodePlusDPS--}
```
public String getDestinationPostCodePlusDPS()
```


Le PC et le DP doivent être conformes à un format PAF. Chaîne de neuf caractères désignant l’international "XY11 " (notez les 5 espaces de fin) ou un motif de caractères désignant un code de tri domestique. Un code de tri domestique se compose d’un code postal extérieur, d’un code postal intérieur et d’un suffixe de point de livraison.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public int getFormat()
```


"0" \\u2013 Null ou Test "1" \\u2013 Lettre "2" \\u2013 Grande Lettre

**Returns:**
int
### getItemID() {#getItemID--}
```
public int getItemID()
```


La valeur maximale est 99999999.

**Returns:**
int
### getSupplychainID() {#getSupplychainID--}
```
public int getSupplychainID()
```


Les valeurs maximales sont 99 pour le code-barres C et 999999 pour le code-barres L.

**Returns:**
int
### getVersionID() {#getVersionID--}
```
public int getVersionID()
```


Actuellement "1" \\u2013 Pour le code-barres Mailmark (0 et 2 à 9 ainsi que A à Z réservés pour une utilisation future)

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Initialise les données Mailmark à partir du texte de code construit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Texte de code construit. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setClass(String value) {#setClass-java.lang.String-}
```
public void setClass(String value)
```


"0" - Null ou Test "1" - 1C (Vente au détail) "2" - 2C (Vente au détail) "3" - 3C (Vente au détail) "4" - Premium (Mail de Publication au détail) (pour une utilisation future éventuelle) "5" - Différé (Vente au détail) "6" - Air (Vente au détail) (pour une utilisation future éventuelle) "7" - Surface (Vente au détail) (pour une utilisation future éventuelle) "8" - Premium (Accès réseau) "9" - Standard (Accès réseau)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setDestinationPostCodePlusDPS(String value) {#setDestinationPostCodePlusDPS-java.lang.String-}
```
public void setDestinationPostCodePlusDPS(String value)
```


Le PC et le DP doivent être conformes à un format PAF. Chaîne de neuf caractères désignant l’international "XY11 " (notez les 5 espaces de fin) ou un motif de caractères désignant un code de tri domestique. Un code de tri domestique se compose d’un code postal extérieur, d’un code postal intérieur et d’un suffixe de point de livraison.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setFormat(int value) {#setFormat-int-}
```
public void setFormat(int value)
```


"0" \\u2013 Null ou Test "1" \\u2013 Lettre "2" \\u2013 Grande Lettre

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


La valeur maximale est 99999999.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setSupplychainID(int value) {#setSupplychainID-int-}
```
public void setSupplychainID(int value)
```


Les valeurs maximales sont 99 pour le code-barres C et 999999 pour le code-barres L.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setVersionID(int value) {#setVersionID-int-}
```
public void setVersionID(int value)
```


Actuellement "1" \\u2013 Pour le code-barres Mailmark (0 et 2 à 9 ainsi que A à Z réservés pour une utilisation future)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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

