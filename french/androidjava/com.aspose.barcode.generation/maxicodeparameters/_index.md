---
title: MaxiCodeParameters
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Paramètres MaxiCode.
type: docs
weight: 57
url: /fr/androidjava/com.aspose.barcode.generation/maxicodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class MaxiCodeParameters
```

Paramètres MaxiCode.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Ratio hauteur/largeur du module du code-barres 2D. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Gets ECI encoding. |
| [getEncodeMode()](#getEncodeMode--) | Obtient un mode d'encodage MaxiCode. |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | Obtient un mode d'encodage MaxiCode. |
| [getMaxiCodeMode()](#getMaxiCodeMode--) | Obtient un mode d'encodage MaxiCode. |
| [getMaxiCodeStructuredAppendModeBarcodeId()](#getMaxiCodeStructuredAppendModeBarcodeId--) | Obtient un identifiant de code-barres MaxiCode en mode d'ajout structuré. |
| [getMaxiCodeStructuredAppendModeBarcodesCount()](#getMaxiCodeStructuredAppendModeBarcodesCount--) | Obtient le nombre de codes-barres MaxiCode en mode d'ajout structuré. |
| [getMode()](#getMode--) | Obtient un mode d'encodage MaxiCode. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Obtient un identifiant de code-barres MaxiCode en mode d'ajout structuré. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Obtient le nombre de codes-barres MaxiCode en mode d'ajout structuré. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Ratio hauteur/largeur du module du code-barres 2D. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Définit l'encodage ECI. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Définit un mode d'encodage MaxiCode. |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Définit un mode d'encodage MaxiCode. |
| [setMaxiCodeMode(int value)](#setMaxiCodeMode-int-) | Définit un mode d'encodage MaxiCode. |
| [setMaxiCodeStructuredAppendModeBarcodeId(int value)](#setMaxiCodeStructuredAppendModeBarcodeId-int-) | Définit un identifiant de code-barres MaxiCode en mode d’ajout structuré. |
| [setMaxiCodeStructuredAppendModeBarcodesCount(int value)](#setMaxiCodeStructuredAppendModeBarcodesCount-int-) | Définit le nombre de codes-barres MaxiCode en mode d’ajout structuré. |
| [setMode(int value)](#setMode-int-) | Définit un mode d'encodage MaxiCode. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Définit un identifiant de code-barres MaxiCode en mode d’ajout structuré. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Définit le nombre de codes-barres MaxiCode en mode d’ajout structuré. |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible de cet [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters). |
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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Obtient l'encodage ECI. Utilisé lorsque MaxiCodeEncodeMode est Auto. Valeur par défaut : ISO-8859-1

**Returns:**
int - encodage ECI.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Obtient un mode d'encodage MaxiCode. Valeur par défaut : Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeEncodeMode() {#getMaxiCodeEncodeMode--}
```
public final MaxiCodeEncodeMode getMaxiCodeEncodeMode()
```


Obtient un mode d'encodage MaxiCode. Valeur par défaut : Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeMode() {#getMaxiCodeMode--}
```
public final int getMaxiCodeMode()
```


Obtient un mode d'encodage MaxiCode.

**Returns:**
int - un mode d'encodage MaxiCode.
### getMaxiCodeStructuredAppendModeBarcodeId() {#getMaxiCodeStructuredAppendModeBarcodeId--}
```
public final int getMaxiCodeStructuredAppendModeBarcodeId()
```


Obtient un identifiant de code-barres MaxiCode en mode d’ajout structuré. L’ID doit être une valeur comprise entre 1 et 8. Valeur par défaut : 0

**Returns:**
int - un identifiant de code-barres MaxiCode en mode d'ajout structuré.
### getMaxiCodeStructuredAppendModeBarcodesCount() {#getMaxiCodeStructuredAppendModeBarcodesCount--}
```
public final int getMaxiCodeStructuredAppendModeBarcodesCount()
```


Obtient le nombre de codes-barres MaxiCode en mode d’ajout structuré. Le nombre doit être une valeur comprise entre 2 et 8 (nombre maximal de codes-barres). Valeur par défaut : -1

**Returns:**
int - un nombre de codes-barres MaxiCode en mode d'ajout structuré.
### getMode() {#getMode--}
```
public final int getMode()
```


Obtient un mode d'encodage MaxiCode.

**Returns:**
int - un mode d'encodage MaxiCode.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Obtient un identifiant de code-barres MaxiCode en mode d’ajout structuré. L’ID doit être une valeur comprise entre 1 et 8. Valeur par défaut : 0

**Returns:**
int - un identifiant de code-barres MaxiCode en mode d'ajout structuré.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Obtient le nombre de codes-barres MaxiCode en mode d’ajout structuré. Le nombre doit être une valeur comprise entre 2 et 8 (nombre maximal de codes-barres). Valeur par défaut : -1

**Returns:**
int - un nombre de codes-barres MaxiCode en mode d'ajout structuré.
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




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


Ratio hauteur/largeur du module du code-barres 2D.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Définit l'encodage ECI. Utilisé lorsque MaxiCodeEncodeMode est Auto. Valeur par défaut : ISO-8859-1

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Encodage ECI. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Définit un mode d'encodage MaxiCode. Valeur par défaut : Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | un mode d'encodage MaxiCode. |

### setMaxiCodeEncodeMode(MaxiCodeEncodeMode value) {#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)
```


Définit un mode d'encodage MaxiCode. Valeur par défaut : Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | un mode d'encodage MaxiCode. |

### setMaxiCodeMode(int value) {#setMaxiCodeMode-int-}
```
public final void setMaxiCodeMode(int value)
```


Définit un mode d'encodage MaxiCode.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | un mode d'encodage MaxiCode. |

### setMaxiCodeStructuredAppendModeBarcodeId(int value) {#setMaxiCodeStructuredAppendModeBarcodeId-int-}
```
public final void setMaxiCodeStructuredAppendModeBarcodeId(int value)
```


Définit un identifiant de code-barres MaxiCode en mode d’ajout structuré. L’ID doit être une valeur comprise entre 1 et 8. Valeur par défaut : 0

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | un identifiant de code-barres MaxiCode en mode d’ajout structuré. |

### setMaxiCodeStructuredAppendModeBarcodesCount(int value) {#setMaxiCodeStructuredAppendModeBarcodesCount-int-}
```
public final void setMaxiCodeStructuredAppendModeBarcodesCount(int value)
```


Définit le nombre de codes-barres MaxiCode en mode d’ajout structuré. Le nombre doit être une valeur comprise entre 2 et 8 (nombre maximal de codes-barres). Valeur par défaut : -1

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | un nombre de codes-barres MaxiCode en mode d'ajout structuré. |

### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Définit un mode d'encodage MaxiCode.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | un mode d'encodage MaxiCode. |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Définit un identifiant de code-barres MaxiCode en mode d’ajout structuré. L’ID doit être une valeur comprise entre 1 et 8. Valeur par défaut : 0

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | un identifiant de code-barres MaxiCode en mode d’ajout structuré. |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


Définit le nombre de codes-barres MaxiCode en mode d’ajout structuré. Le nombre doit être une valeur comprise entre 2 et 8 (nombre maximal de codes-barres). Valeur par défaut : -1

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | un nombre de codes-barres MaxiCode en mode d'ajout structuré. |

### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne lisible de cet [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters).

**Returns:**
java.lang.String - Une chaîne qui représente ce [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters).
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

