---
title: "HanXinParameters"
second_title: "Référence API d'Aspose.BarCode pour Java"
description: "Paramètres Han Xin."
type: docs
weight: 48
url: /fr/java/com.aspose.barcode.generation/hanxinparameters/
---
**Inheritance:**
java.lang.Object
```
public class HanXinParameters
```

Paramètres Han Xin.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Identifiants d'interprétation de canal étendu. |
| [getEncodeMode()](#getEncodeMode--) | Mode d'encodage HanXin. |
| [getErrorLevel()](#getErrorLevel--) | Niveau de correction d'erreurs Reed-Solomon pour le code-barres Han Xin. |
| [getVersion()](#getVersion--) | Version du code HanXin. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identifiants d'interprétation de canal étendu. |
| [setEncodeMode(HanXinEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-) | Mode d'encodage HanXin. |
| [setErrorLevel(HanXinErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-) | Niveau de correction d'erreurs Reed-Solomon pour le code-barres Han Xin. |
| [setVersion(HanXinVersion value)](#setVersion-com.aspose.barcode.generation.HanXinVersion-) | Version du code HanXin. |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails concernant les références utilisées pour l'encodage des données dans le symbole. L'implémentation actuelle contient tous les encodages de jeu de caractères bien connus.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final HanXinEncodeMode getEncodeMode()
```


Mode d'encodage HanXin. Valeur par défaut : EncodeMode.Mixed.

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final HanXinErrorLevel getErrorLevel()
```


Niveau de correction d'erreurs Reed-Solomon pour le code-barres Han Xin. Du plus bas au plus haut : L1, L2, L3, L4. voir ErrorLevel.

**Returns:**
[HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel)
### getVersion() {#getVersion--}
```
public final HanXinVersion getVersion()
```


Version du code HanXin. De Version01 à Version84 pour le code Han Xin. La valeur par défaut est Version.Auto.

**Returns:**
[HanXinVersion](../../com.aspose.barcode.generation/hanxinversion)
### hashCode() {#hashCode--}
```
public final int hashCode()
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




### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails concernant les références utilisées pour l'encodage des données dans le symbole. L'implémentation actuelle contient tous les encodages de jeu de caractères bien connus.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setEncodeMode(HanXinEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-}
```
public final void setEncodeMode(HanXinEncodeMode value)
```


Mode d'encodage HanXin. Valeur par défaut : EncodeMode.Mixed.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode) |  |

### setErrorLevel(HanXinErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-}
```
public final void setErrorLevel(HanXinErrorLevel value)
```


Niveau de correction d'erreurs Reed-Solomon pour le code-barres Han Xin. Du plus bas au plus haut : L1, L2, L3, L4. voir ErrorLevel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel) |  |

### setVersion(HanXinVersion value) {#setVersion-com.aspose.barcode.generation.HanXinVersion-}
```
public final void setVersion(HanXinVersion value)
```


Version du code HanXin. De Version01 à Version84 pour le code Han Xin. La valeur par défaut est Version.Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [HanXinVersion](../../com.aspose.barcode.generation/hanxinversion) |  |

### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne lisible par l'homme de ce [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters).

**Returns:**
java.lang.String - Une chaîne qui représente ce [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters).
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

