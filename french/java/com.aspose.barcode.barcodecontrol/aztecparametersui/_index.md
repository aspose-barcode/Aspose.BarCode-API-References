---
title: "AztecParametersUI"
second_title: "Référence API d'Aspose.BarCode pour Java"
description: "Enveloppe UI pour la classe AztecParameters"
type: docs
weight: 10
url: /fr/java/com.aspose.barcode.barcodecontrol/aztecparametersui/
---
**Inheritance:**
java.lang.Object
```
public class AztecParametersUI
```

Enveloppe UI pour la classe AztecParameters
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Rapport hauteur/largeur du module de code-barres 2D. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Obtient l'encodage ECI. |
| [getEncodeMode()](#getEncodeMode--) | Obtient un mode d'encodage Aztec. |
| [getErrorLevel()](#getErrorLevel--) | Niveau de correction d'erreurs des types de code-barres Aztec. |
| [getLayersCount()](#getLayersCount--) | Obtient le nombre de couches du symbole Aztec. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | ID du code-barres pour le mode Structured Append du code-barres Aztec. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Nombre de codes-barres pour le mode Structured Append du code-barres Aztec. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | ID de fichier pour le mode Structured Append du code-barres Aztec (champ facultatif). |
| [getSymbolMode()](#getSymbolMode--) | Obtient un mode de symbole Aztec. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Rapport hauteur/largeur du module de code-barres 2D. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Définit l'encodage ECI. |
| [setEncodeMode(AztecEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Définit un mode d'encodage Aztec. |
| [setErrorLevel(int value)](#setErrorLevel-int-) | Niveau de correction d'erreurs des types de code-barres Aztec. |
| [setLayersCount(int value)](#setLayersCount-int-) | Définit le nombre de couches du symbole Aztec. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | ID du code-barres pour le mode Structured Append du code-barres Aztec. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Nombre de codes-barres pour le mode Structured Append du code-barres Aztec. |
| [setStructuredAppendFileId(String value)](#setStructuredAppendFileId-java.lang.String-) | ID de fichier pour le mode Structured Append du code-barres Aztec (champ facultatif). |
| [setSymbolMode(AztecSymbolMode value)](#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Définit un mode de symbole Aztec. |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible par l'homme de cet [AztecParameters](../../com.aspose.barcode.generation/aztecparameters). |
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
public float getAspectRatio()
```


Rapport hauteur/largeur du module de code-barres 2D.

**Returns:**
float
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


Obtient un mode d'encodage Aztec. Valeur par défaut : Auto.

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode - un mode d'encodage Aztec.
### getErrorLevel() {#getErrorLevel--}
```
public int getErrorLevel()
```


Niveau de correction d'erreurs des codes-barres de type Aztec. La valeur doit être comprise entre 10 et 95.

**Returns:**
int
### getLayersCount() {#getLayersCount--}
```
public final int getLayersCount()
```


Obtient le nombre de couches du symbole Aztec. Le nombre de couches doit être compris entre 1 et 3 pour le mode Compact et entre 1 et 32 pour le mode Full Range. Valeur par défaut : 0 (auto).

**Returns:**
int - nombre de couches du symbole Aztec.
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


ID du code-barres pour le mode Structured Append du code-barres Aztec. L'ID du code-barres doit être compris entre 1 et le nombre de codes-barres. Valeur par défaut : 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Nombre de codes-barres pour le mode Structured Append du code-barres Aztec. Le nombre de codes-barres doit être compris entre 1 et 26. Valeur par défaut : 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final String getStructuredAppendFileId()
```


ID de fichier pour le mode Structured Append du code-barres Aztec (champ optionnel). L'ID de fichier ne doit pas contenir d'espaces. Valeur par défaut : chaîne vide

**Returns:**
java.lang.String
### getSymbolMode() {#getSymbolMode--}
```
public AztecSymbolMode getSymbolMode()
```


Obtient un mode de symbole Aztec.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode)
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
public void setAspectRatio(float value)
```


Rapport hauteur/largeur du module de code-barres 2D.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Définit l'encodage ECI. Utilisé lorsque AztecEncodeMode est Auto. Valeur par défaut : ISO-8859-1

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Encodage ECI. |

### setEncodeMode(AztecEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setEncodeMode(AztecEncodeMode value)
```


Définit un mode d'encodage Aztec. Valeur par défaut : Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.barcode.generation.AztecEncodeMode | un mode d'encodage Aztec. |

### setErrorLevel(int value) {#setErrorLevel-int-}
```
public void setErrorLevel(int value)
```


Niveau de correction d'erreurs des codes-barres de type Aztec. La valeur doit être comprise entre 10 et 95.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setLayersCount(int value) {#setLayersCount-int-}
```
public final void setLayersCount(int value)
```


Définit le nombre de couches du symbole Aztec. Le nombre de couches doit être compris entre 1 et 3 pour le mode Compact et entre 1 et 32 pour le mode Full Range. Valeur par défaut : 0 (auto).

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


ID du code-barres pour le mode Structured Append du code-barres Aztec. L'ID du code-barres doit être compris entre 1 et le nombre de codes-barres. Valeur par défaut : 0

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Nombre de codes-barres pour le mode Structured Append du code-barres Aztec. Le nombre de codes-barres doit être compris entre 1 et 26. Valeur par défaut : 0

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setStructuredAppendFileId(String value) {#setStructuredAppendFileId-java.lang.String-}
```
public final void setStructuredAppendFileId(String value)
```


ID de fichier pour le mode Structured Append du code-barres Aztec (champ optionnel). L'ID de fichier ne doit pas contenir d'espaces. Valeur par défaut : chaîne vide

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setSymbolMode(AztecSymbolMode value) {#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public void setSymbolMode(AztecSymbolMode value)
```


Définit un mode de symbole Aztec.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) |  |

### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne lisible par l'homme de cet [AztecParameters](../../com.aspose.barcode.generation/aztecparameters).

**Returns:**
java.lang.String - Une chaîne qui représente ce [AztecParameters](../../com.aspose.barcode.generation/aztecparameters).
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

