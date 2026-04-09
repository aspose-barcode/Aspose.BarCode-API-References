---
title: DataMatrixParameters
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Paramètres DataMatrix.
type: docs
weight: 34
url: /fr/androidjava/com.aspose.barcode.generation/datamatrixparameters/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParameters
```

Paramètres DataMatrix.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Ratio hauteur/largeur du module du code-barres 2D. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Nombre de colonnes. |
| [getDataMatrixEcc()](#getDataMatrixEcc--) | Obtient un type ECC Datamatrix. |
| [getDataMatrixEncodeMode()](#getDataMatrixEncodeMode--) | Mode d’encodage du code-barres Datamatrix. |
| [getDataMatrixVersion()](#getDataMatrixVersion--) | Obtient une taille de symbole Datamatrix. |
| [getECIEncoding()](#getECIEncoding--) | Gets ECI encoding. |
| [getEccType()](#getEccType--) | Obtient un type ECC Datamatrix. |
| [getEncodeMode()](#getEncodeMode--) | Mode d’encodage du code-barres Datamatrix. |
| [getMacroCharacters()](#getMacroCharacters--) | Les valeurs des caractères macro 05 et 06 sont utilisées pour obtenir un encodage plus compact dans les modes spéciaux. |
| [getRows()](#getRows--) | Nombre de lignes. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | ID du code-barres pour le mode Structured Append du code-barres Datamatrix. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Nombre de codes-barres pour le mode Structured Append du code-barres Datamatrix. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | ID du fichier pour le mode Structured Append du code-barres Datamatrix. |
| [getVersion()](#getVersion--) | Obtient une taille de symbole Datamatrix. |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Ratio hauteur/largeur du module du code-barres 2D. |
| [setColumns(int value)](#setColumns-int-) | Nombre de colonnes. |
| [setDataMatrixEcc(DataMatrixEccType value)](#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-) | Définit un type ECC Datamatrix. |
| [setDataMatrixEncodeMode(DataMatrixEncodeMode value)](#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Mode d’encodage du code-barres Datamatrix. |
| [setDataMatrixVersion(DataMatrixVersion value)](#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Définit une taille de symbole Datamatrix. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Définit l'encodage ECI. |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Définit un type ECC Datamatrix. |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Mode d’encodage du code-barres Datamatrix. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Les valeurs des caractères macro 05 et 06 sont utilisées pour obtenir un encodage plus compact dans les modes spéciaux. |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur. |
| [setRows(int value)](#setRows-int-) | Nombre de lignes. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | ID du code-barres pour le mode Structured Append du code-barres Datamatrix. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Nombre de codes-barres pour le mode Structured Append du code-barres Datamatrix. |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | ID du fichier pour le mode Structured Append du code-barres Datamatrix. |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Définit une taille de symbole Datamatrix. |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters). |
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


Nombre de colonnes.

**Returns:**
int
### getDataMatrixEcc() {#getDataMatrixEcc--}
```
public final DataMatrixEccType getDataMatrixEcc()
```


Obtient un type ECC Datamatrix. Valeur par défaut : DataMatrixEccType.Ecc200.

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getDataMatrixEncodeMode() {#getDataMatrixEncodeMode--}
```
public final DataMatrixEncodeMode getDataMatrixEncodeMode()
```


Mode d'encodage du code-barres Datamatrix. Valeur par défaut : EncodeMode.Auto.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getDataMatrixVersion() {#getDataMatrixVersion--}
```
public final DataMatrixVersion getDataMatrixVersion()
```


Obtient une taille de symbole Datamatrix. Valeur par défaut : Version.Auto.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Obtient l'encodage ECI. Utilisé lorsque EncodeMode est Auto. Valeur par défaut : ISO-8859-1

**Returns:**
int - encodage ECI.
### getEccType() {#getEccType--}
```
public final DataMatrixEccType getEccType()
```


Obtient un type ECC Datamatrix. Valeur par défaut : DataMatrixEccType.Ecc200.

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getEncodeMode() {#getEncodeMode--}
```
public final DataMatrixEncodeMode getEncodeMode()
```


Mode d'encodage du code-barres Datamatrix. Valeur par défaut : EncodeMode.Auto.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Les valeurs des caractères macro 05 et 06 sont utilisées pour obtenir un encodage plus compact dans des modes spéciaux. Elles ne peuvent être utilisées qu'avec DataMatrixEccType.Ecc200 ou DataMatrixEccType.EccAuto. Elles ne peuvent pas être utilisées avec EncodeTypes.GS1DataMatrix Valeur par défaut : MacroCharacters.None.

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getRows() {#getRows--}
```
public final int getRows()
```


Nombre de lignes.

**Returns:**
int
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


ID du code-barres pour le mode Structured Append du code-barres Datamatrix. Valeur par défaut : 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Nombre de codes-barres pour le mode Structured Append du code-barres Datamatrix. Valeur par défaut : 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


ID du fichier pour le mode Structured Append du code-barres Datamatrix. Valeur par défaut : 0

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


Obtient une taille de symbole Datamatrix. Valeur par défaut : Version.Auto.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
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


Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur. Valeur par défaut : false

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


Nombre de colonnes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setDataMatrixEcc(DataMatrixEccType value) {#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setDataMatrixEcc(DataMatrixEccType value)
```


Définit un type ECC Datamatrix. Valeur par défaut : DataMatrixEccType.Ecc200.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | un type ECC Datamatrix. |

### setDataMatrixEncodeMode(DataMatrixEncodeMode value) {#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setDataMatrixEncodeMode(DataMatrixEncodeMode value)
```


Mode d'encodage du code-barres Datamatrix. Valeur par défaut : EncodeMode.Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setDataMatrixVersion(DataMatrixVersion value) {#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setDataMatrixVersion(DataMatrixVersion value)
```


Définit une taille de symbole Datamatrix. Valeur par défaut : Version.Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | une taille de symbole Datamatrix. |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Définit l'encodage ECI. Utilisé lorsque EncodeMode est Auto. Valeur par défaut : ISO-8859-1

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Encodage ECI. |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


Définit un type ECC Datamatrix. Valeur par défaut : DataMatrixEccType.Ecc200.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | un type ECC Datamatrix. |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


Mode d'encodage du code-barres Datamatrix. Valeur par défaut : EncodeMode.Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Les valeurs des caractères macro 05 et 06 sont utilisées pour obtenir un encodage plus compact dans des modes spéciaux. Elles ne peuvent être utilisées qu'avec DataMatrixEccType.Ecc200 ou DataMatrixEccType.EccAuto. Elles ne peuvent pas être utilisées avec EncodeTypes.GS1DataMatrix Valeur par défaut : MacroCharacters.None.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur. Valeur par défaut : false

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Nombre de lignes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


ID du code-barres pour le mode Structured Append du code-barres Datamatrix. Valeur par défaut : 0

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Nombre de codes-barres pour le mode Structured Append du code-barres Datamatrix. Valeur par défaut : 0

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


ID du fichier pour le mode Structured Append du code-barres Datamatrix. Valeur par défaut : 0

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


Définit une taille de symbole Datamatrix. Valeur par défaut : Version.Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | une taille de symbole Datamatrix. |

### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne lisible par l'homme de ce [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters).

**Returns:**
java.lang.String - Une chaîne qui représente ce [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters).
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

