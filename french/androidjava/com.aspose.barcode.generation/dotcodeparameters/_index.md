---
title: DotCodeParameters
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Paramètres DotCode.
type: docs
weight: 36
url: /fr/androidjava/com.aspose.barcode.generation/dotcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class DotCodeParameters
```

Paramètres DotCode.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Ratio hauteur/largeur du module du code-barres 2D. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Identifies columns count. |
| [getDotCodeEncodeMode()](#getDotCodeEncodeMode--) | Identifies DotCode encode mode. |
| [getDotCodeStructuredAppendModeBarcodeId()](#getDotCodeStructuredAppendModeBarcodeId--) | Identifies the ID of the DotCode structured append mode barcode. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getDotCodeStructuredAppendModeBarcodesCount--) | Identifies DotCode structured append mode barcodes count. |
| [getECIEncoding()](#getECIEncoding--) | Identifies ECI encoding. |
| [getEncodeMode()](#getEncodeMode--) | Identifies DotCode encode mode. |
| [getRows()](#getRows--) | Identifies rows count. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Identifies the ID of the DotCode structured append mode barcode. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Identifies DotCode structured append mode barcodes count. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Indique si le code est utilisé pour demander au lecteur d’interpréter les données suivantes comme des instructions d'initialisation ou de reprogrammation du lecteur de code-barres. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Ratio hauteur/largeur du module du code-barres 2D. |
| [setColumns(int value)](#setColumns-int-) | Identifies columns count. |
| [setDotCodeEncodeMode(DotCodeEncodeMode value)](#setDotCodeEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | Identifies DotCode encode mode. |
| [setDotCodeStructuredAppendModeBarcodeId(int value)](#setDotCodeStructuredAppendModeBarcodeId-int-) | Identifies the ID of the DotCode structured append mode barcode. |
| [setDotCodeStructuredAppendModeBarcodesCount(int value)](#setDotCodeStructuredAppendModeBarcodesCount-int-) | Identifies DotCode structured append mode barcodes count. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identifies ECI encoding. |
| [setEncodeMode(DotCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | Identifies DotCode encode mode. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Indique si le code est utilisé pour demander au lecteur d’interpréter les données suivantes comme des instructions d'initialisation ou de reprogrammation du lecteur de code-barres. |
| [setRows(int value)](#setRows-int-) | Identifies rows count. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Identifies the ID of the DotCode structured append mode barcode. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Identifies DotCode structured append mode barcodes count. |
| [toString()](#toString--) | Returns a human-readable string representation of this [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters). |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumns() {#getColumns--}
```
public final int getColumns()
```


Identifie le nombre de colonnes. La somme du nombre de lignes et du nombre de colonnes d'un symbole DotCode doit être impaire. Le nombre de colonnes doit être au moins de 5. Valeur par défaut : -1

**Returns:**
int
### getDotCodeEncodeMode() {#getDotCodeEncodeMode--}
```
public final DotCodeEncodeMode getDotCodeEncodeMode()
```


Identifie le mode d'encodage DotCode. Valeur par défaut : Auto.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getDotCodeStructuredAppendModeBarcodeId() {#getDotCodeStructuredAppendModeBarcodeId--}
```
public final int getDotCodeStructuredAppendModeBarcodeId()
```


Identifie l'ID du code‑barres en mode d'ajout structuré DotCode. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes‑barres. La valeur par défaut est -1.

**Returns:**
int
### getDotCodeStructuredAppendModeBarcodesCount() {#getDotCodeStructuredAppendModeBarcodesCount--}
```
public final int getDotCodeStructuredAppendModeBarcodesCount()
```


Identifie le nombre de codes‑barres en mode d'ajout structuré DotCode. La valeur par défaut est -1. Le nombre doit être compris entre 1 et 35.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Identifie l'encodage ECI. Utilisé lorsque DotCodeEncodeMode est Auto. Valeur par défaut : ISO-8859-1

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final DotCodeEncodeMode getEncodeMode()
```


Identifie le mode d'encodage DotCode. Valeur par défaut : Auto.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getRows() {#getRows--}
```
public final int getRows()
```


Identifie le nombre de lignes. La somme du nombre de lignes et du nombre de colonnes d'un symbole DotCode doit être impaire. Le nombre de lignes doit être au moins de 5. Valeur par défaut : -1

**Returns:**
int
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Identifie l'ID du code‑barres en mode d'ajout structuré DotCode. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes‑barres. La valeur par défaut est -1.

**Returns:**
int
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Identifie le nombre de codes‑barres en mode d'ajout structuré DotCode. La valeur par défaut est -1. Le nombre doit être compris entre 1 et 35.

**Returns:**
int
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


Indique si le code est utilisé pour demander au lecteur d’interpréter les données suivantes comme des instructions d'initialisation ou de reprogrammation du lecteur de code-barres. La valeur par défaut est false.

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

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Identifie le nombre de colonnes. La somme du nombre de lignes et du nombre de colonnes d'un symbole DotCode doit être impaire. Le nombre de colonnes doit être au moins de 5. Valeur par défaut : -1

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setDotCodeEncodeMode(DotCodeEncodeMode value) {#setDotCodeEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setDotCodeEncodeMode(DotCodeEncodeMode value)
```


Identifie le mode d'encodage DotCode. Valeur par défaut : Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setDotCodeStructuredAppendModeBarcodeId(int value) {#setDotCodeStructuredAppendModeBarcodeId-int-}
```
public final void setDotCodeStructuredAppendModeBarcodeId(int value)
```


Identifie l'ID du code‑barres en mode d'ajout structuré DotCode. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes‑barres. La valeur par défaut est -1.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setDotCodeStructuredAppendModeBarcodesCount(int value) {#setDotCodeStructuredAppendModeBarcodesCount-int-}
```
public final void setDotCodeStructuredAppendModeBarcodesCount(int value)
```


Identifie le nombre de codes‑barres en mode d'ajout structuré DotCode. La valeur par défaut est -1. Le nombre doit être compris entre 1 et 35.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Identifie l'encodage ECI. Utilisé lorsque DotCodeEncodeMode est Auto. Valeur par défaut : ISO-8859-1

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setEncodeMode(DotCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setEncodeMode(DotCodeEncodeMode value)
```


Identifie le mode d'encodage DotCode. Valeur par défaut : Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Indique si le code est utilisé pour demander au lecteur d’interpréter les données suivantes comme des instructions d'initialisation ou de reprogrammation du lecteur de code-barres. La valeur par défaut est false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Identifie le nombre de lignes. La somme du nombre de lignes et du nombre de colonnes d'un symbole DotCode doit être impaire. Le nombre de lignes doit être au moins de 5. Valeur par défaut : -1

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Identifie l'ID du code‑barres en mode d'ajout structuré DotCode. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes‑barres. La valeur par défaut est -1.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


Identifie le nombre de codes‑barres en mode d'ajout structuré DotCode. La valeur par défaut est -1. Le nombre doit être compris entre 1 et 35.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters).

**Returns:**
java.lang.String - Une chaîne qui représente cet [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters).
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

