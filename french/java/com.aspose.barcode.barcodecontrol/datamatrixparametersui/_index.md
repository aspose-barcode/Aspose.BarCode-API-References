---
title: "DataMatrixParametersUI"
second_title: "Référence API d'Aspose.BarCode pour Java"
description: "Enveloppe UI pour la classe com.aspose.barcode.generation.DataMatrixParameters."
type: docs
weight: 14
url: /fr/java/com.aspose.barcode.barcodecontrol/datamatrixparametersui/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParametersUI
```

Enveloppe UI pour la classe com.aspose.barcode.generation.DataMatrixParameters.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Rapport hauteur/largeur du module de code-barres 2D. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Obtient l'encodage ECI. |
| [getEccType()](#getEccType--) | Obtient un type ECC Datamatrix. |
| [getEncodeMode()](#getEncodeMode--) | Mode d'encodage du code-barres Datamatrix. |
| [getMacroCharacters()](#getMacroCharacters--) | Protocole pour les caractères macro en première position (ECC 200 uniquement). |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | ID du code-barres pour le mode Structured Append. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Nombre de codes-barres pour le mode Structured Append. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | ID du fichier pour le mode Structured Append. |
| [getVersion()](#getVersion--) | Taille du symbole DataMatrix. |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Rapport hauteur/largeur du module de code-barres 2D. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Définit l'encodage ECI. |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Définit un type ECC Datamatrix. |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Mode d'encodage du code-barres Datamatrix. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Protocole pour les caractères macro en première position (ECC 200 uniquement). |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | ID du code-barres pour le mode Structured Append. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Nombre de codes-barres pour le mode Structured Append. |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | ID du fichier pour le mode Structured Append. |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Taille du symbole DataMatrix. |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible de ce [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters). |
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


Obtient l'encodage ECI. Utilisé lorsque EncodeMode est Auto.

**Returns:**
int - encodage ECI.
### getEccType() {#getEccType--}
```
public final DataMatrixEccType getEccType()
```


Obtient un type ECC Datamatrix. Valeur par défaut : DataMatrixEccType.Ecc200.

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getEncodeMode() {#getEncodeMode--}
```
public final DataMatrixEncodeMode getEncodeMode()
```


Mode d'encodage du code-barres Datamatrix. Valeur par défaut : EncodeMode.Auto.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Protocole pour les caractères macro en première position (ECC 200 uniquement).

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


ID du code-barres pour le mode Structured Append.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Nombre de codes-barres pour le mode Structured Append.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


ID du fichier pour le mode Structured Append.

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


Taille du symbole DataMatrix.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReaderProgramming() {#isReaderProgramming--}
```
public final boolean isReaderProgramming()
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


Rapport hauteur/largeur du module de code-barres 2D.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Définit l'encodage ECI. Utilisé lorsque EncodeMode est Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Encodage ECI. |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


Définit un type ECC Datamatrix. Valeur par défaut : DataMatrixEccType.Ecc200.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | un type ECC Datamatrix. |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


Mode d'encodage du code-barres Datamatrix. Valeur par défaut : EncodeMode.Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Protocole pour les caractères macro en première position (ECC 200 uniquement).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
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


ID du code-barres pour le mode Structured Append.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Nombre de codes-barres pour le mode Structured Append.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


ID du fichier pour le mode Structured Append.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


Taille du symbole DataMatrix.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) |  |

### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne lisible de ce [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters).

**Returns:**
java.lang.String - Une chaîne qui représente ce [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters).
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

