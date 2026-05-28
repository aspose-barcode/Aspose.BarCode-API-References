---
title: AztecParameters
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Paramètres Aztec.
type: docs
weight: 12
url: /fr/androidjava/com.aspose.barcode.generation/aztecparameters/
---
**Inheritance:**
java.lang.Object
```
public class AztecParameters
```

Paramètres Aztec.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Ratio hauteur/largeur du module du code-barres 2D. |
| [getAztecEncodeMode()](#getAztecEncodeMode--) | Obtient un mode d’encodage Aztec. |
| [getAztecErrorLevel()](#getAztecErrorLevel--) | Niveau de correction d’erreurs des types de code-barres Aztec. |
| [getAztecSymbolMode()](#getAztecSymbolMode--) | Obtient un mode de symbole Aztec. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Gets ECI encoding. |
| [getEncodeMode()](#getEncodeMode--) | Obtient un mode d’encodage Aztec. |
| [getErrorLevel()](#getErrorLevel--) | Niveau de correction d’erreurs des types de code-barres Aztec. |
| [getLayersCount()](#getLayersCount--) | Obtient le nombre de couches du symbole Aztec. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Identifiant du code-barres pour le mode Structured Append du code-barres Aztec. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Nombre de codes-barres pour le mode Structured Append du code-barres Aztec. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Identifiant de fichier pour le mode Structured Append du code-barres Aztec (champ optionnel). |
| [getSymbolMode()](#getSymbolMode--) | Obtient un mode de symbole Aztec. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Ratio hauteur/largeur du module du code-barres 2D. |
| [setAztecEncodeMode(AztecEncodeMode value)](#setAztecEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Définit un mode d'encodage Aztec. |
| [setAztecErrorLevel(int value)](#setAztecErrorLevel-int-) | Niveau de correction d’erreurs des types de code-barres Aztec. |
| [setAztecSymbolMode(AztecSymbolMode value)](#setAztecSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Définit un mode de symbole Aztec. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Définit l'encodage ECI. |
| [setEncodeMode(AztecEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Définit un mode d'encodage Aztec. |
| [setErrorLevel(int value)](#setErrorLevel-int-) | Niveau de correction d’erreurs des types de code-barres Aztec. |
| [setLayersCount(int value)](#setLayersCount-int-) | Définit le nombre de couches du symbole Aztec. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Identifiant du code-barres pour le mode Structured Append du code-barres Aztec. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Nombre de codes-barres pour le mode Structured Append du code-barres Aztec. |
| [setStructuredAppendFileId(String value)](#setStructuredAppendFileId-java.lang.String-) | Identifiant de fichier pour le mode Structured Append du code-barres Aztec (champ optionnel). |
| [setSymbolMode(AztecSymbolMode value)](#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Définit un mode de symbole Aztec. |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible de cet [AztecParameters](../../com.aspose.barcode.generation/aztecparameters). |
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
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Ratio hauteur/largeur du module du code-barres 2D.

**Returns:**
float
### getAztecEncodeMode() {#getAztecEncodeMode--}
```
public final AztecEncodeMode getAztecEncodeMode()
```


Obtient un mode d'encodage Aztec. Valeur par défaut : Auto.

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode - un mode d'encodage Aztec.
### getAztecErrorLevel() {#getAztecErrorLevel--}
```
public final int getAztecErrorLevel()
```


Niveau de correction d'erreurs des types de code-barres Aztec. La valeur doit être comprise entre 5 et 95.

**Returns:**
int
### getAztecSymbolMode() {#getAztecSymbolMode--}
```
public final AztecSymbolMode getAztecSymbolMode()
```


Obtient un mode de symbole Aztec. Valeur par défaut : AztecSymbolMode.Auto.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
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


Obtient l'encodage ECI. Utilisé lorsque AztecEncodeMode est Auto. Valeur par défaut : ISO-8859-1

**Returns:**
int - encodage ECI.
### getEncodeMode() {#getEncodeMode--}
```
public final AztecEncodeMode getEncodeMode()
```


Obtient un mode d'encodage Aztec. Valeur par défaut : Auto.

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode - un mode d'encodage Aztec.
### getErrorLevel() {#getErrorLevel--}
```
public final int getErrorLevel()
```


Niveau de correction d'erreurs des types de code-barres Aztec. La valeur doit être comprise entre 5 et 95.

**Returns:**
int
### getLayersCount() {#getLayersCount--}
```
public final int getLayersCount()
```


Obtient le nombre de couches du symbole Aztec. Le nombre de couches doit être compris entre 1 et 3 pour le mode Compact et entre 1 et 32 pour le mode Full Range. Valeur par défaut : 0 (auto).

**Returns:**
int - nombre de couches du symbole Aztec.
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Identifiant du code-barres pour le mode Structured Append du code-barres Aztec. L'identifiant du code-barres doit être compris entre 1 et le nombre de codes-barres. Valeur par défaut : 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Nombre de codes-barres pour le mode Structured Append du code-barres Aztec. Le nombre de codes-barres doit être compris entre 1 et 26. Valeur par défaut : 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final String getStructuredAppendFileId()
```


Identifiant de fichier pour le mode Structured Append du code-barres Aztec (champ optionnel). L'identifiant de fichier ne doit pas contenir d'espaces. Valeur par défaut : chaîne vide

**Returns:**
java.lang.String
### getSymbolMode() {#getSymbolMode--}
```
public final AztecSymbolMode getSymbolMode()
```


Obtient un mode de symbole Aztec. Valeur par défaut : AztecSymbolMode.Auto.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


Ratio hauteur/largeur du module du code-barres 2D.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setAztecEncodeMode(AztecEncodeMode value) {#setAztecEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setAztecEncodeMode(AztecEncodeMode value)
```


Définit un mode d'encodage Aztec. Valeur par défaut : Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.barcode.generation.AztecEncodeMode | un mode d'encodage Aztec. |

### setAztecErrorLevel(int value) {#setAztecErrorLevel-int-}
```
public final void setAztecErrorLevel(int value)
```


Niveau de correction d'erreurs des types de code-barres Aztec. La valeur doit être comprise entre 5 et 95.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setAztecSymbolMode(AztecSymbolMode value) {#setAztecSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setAztecSymbolMode(AztecSymbolMode value)
```


Définit un mode de symbole Aztec. Valeur par défaut : AztecSymbolMode.Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | un mode de symbole Aztec. |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Définit l'encodage ECI. Utilisé lorsque AztecEncodeMode est Auto. Valeur par défaut : ISO-8859-1

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Encodage ECI. |

### setEncodeMode(AztecEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setEncodeMode(AztecEncodeMode value)
```


Définit un mode d'encodage Aztec. Valeur par défaut : Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.barcode.generation.AztecEncodeMode | un mode d'encodage Aztec. |

### setErrorLevel(int value) {#setErrorLevel-int-}
```
public final void setErrorLevel(int value)
```


Niveau de correction d'erreurs des types de code-barres Aztec. La valeur doit être comprise entre 5 et 95.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setLayersCount(int value) {#setLayersCount-int-}
```
public final void setLayersCount(int value)
```


Définit le nombre de couches du symbole Aztec. Le nombre de couches doit être compris entre 1 et 3 pour le mode Compact et entre 1 et 32 pour le mode Full Range. Valeur par défaut : 0 (auto).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | nombre de couches du symbole Aztec. |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Identifiant du code-barres pour le mode Structured Append du code-barres Aztec. L'identifiant du code-barres doit être compris entre 1 et le nombre de codes-barres. Valeur par défaut : 0

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Nombre de codes-barres pour le mode Structured Append du code-barres Aztec. Le nombre de codes-barres doit être compris entre 1 et 26. Valeur par défaut : 0

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setStructuredAppendFileId(String value) {#setStructuredAppendFileId-java.lang.String-}
```
public final void setStructuredAppendFileId(String value)
```


Identifiant de fichier pour le mode Structured Append du code-barres Aztec (champ optionnel). L'identifiant de fichier ne doit pas contenir d'espaces. Valeur par défaut : chaîne vide

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setSymbolMode(AztecSymbolMode value) {#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setSymbolMode(AztecSymbolMode value)
```


Définit un mode de symbole Aztec. Valeur par défaut : AztecSymbolMode.Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | un mode de symbole Aztec. |

### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne lisible de cet [AztecParameters](../../com.aspose.barcode.generation/aztecparameters).

**Returns:**
java.lang.String - Une chaîne qui représente ce [AztecParameters](../../com.aspose.barcode.generation/aztecparameters).
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

