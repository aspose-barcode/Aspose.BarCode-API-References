---
title: "Pdf417ParametersUI"
second_title: "Référence API d'Aspose.BarCode pour Java"
description: "Enveloppe UI pour la classe com.aspose.barcode.generation.Pdf417Parameters."
type: docs
weight: 16
url: /fr/java/com.aspose.barcode.barcodecontrol/pdf417parametersui/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417ParametersUI
```

Enveloppe UI pour la classe com.aspose.barcode.generation.Pdf417Parameters.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Rapport hauteur/largeur du module de code-barres 2D. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Nombre de colonnes. |
| [getECIEncoding()](#getECIEncoding--) | Identifiants d'interprétation de canal étendu. |
| [getEncodeMode()](#getEncodeMode--) | Type de symbologie Pdf417 du mode d'encodage du code-barres. |
| [getErrorLevel()](#getErrorLevel--) | Obtient le type de symbologie Pdf417 du niveau de correction d'erreurs du code-barres, allant de level0 à level8, level0 signifie aucune information de correction d'erreurs, level8 signifie la meilleure correction d'erreurs, ce qui entraîne une image plus grande. |
| [getMacroCharacters()](#getMacroCharacters--) | Les valeurs des caractères macro 05 et 06 sont utilisées pour obtenir un encodage plus compact dans des modes spéciaux. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Nom du destinataire du code-barres MacroPdf417 (champ optionnel). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Somme de contrôle du code-barres MacroPdf417 (champ optionnel). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | Identifiants d'interprétation de canal étendu. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Obtient l'ID de fichier du code-barres macro Pdf417. |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Nom de fichier du code-barres MacroPdf417 (champ optionnel). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Taille du fichier MacroPdf417 (champ optionnel). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Obtient l'ID de segment du code-barres macro Pdf417, qui commence à 0, jusqu'à MacroSegmentsCount - 1. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Obtient le nombre de segments du code-barres macro Pdf417. |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Nom de l'expéditeur du code-barres MacroPdf417 (champ optionnel). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Utilisé pour indiquer à l'encodeur s'il faut ajouter le terminateur Macro PDF417 (codeword 922) au segment. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Horodatage du code-barres MacroPdf417 (champ optionnel). |
| [getRows()](#getRows--) | Nombre de lignes. |
| [getTruncate()](#getTruncate--) | Indique si le type de symbologie Pdf417 du code-barres est tronqué (pour réduire l'espace). |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | Ne peut être utilisé qu'avec MicroPdf417 et encode les modes d'émulation Code 128. Peut encoder FNC1 en deuxième position dans les modes 908 et 909, peut également encoder 910 et 911 qui indiquent simplement que le MicroPdf417 reconnu peut être interprété comme Code 128. |
| [isLinked()](#isLinked--) | Définit les modes liés avec les codes-barres GS1MicroPdf417, MicroPdf417 et Pdf417. Avec la symbologie GS1MicroPdf417, encode 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d modes UCC/EAN-128. Avec les symbologies MicroPdf417 et Pdf417, encode le drapeau de liaison 918 vers le composant linéaire associé autre qu'un EAN.UCC. |
| [isReaderInitialization()](#isReaderInitialization--) | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Rapport hauteur/largeur du module de code-barres 2D. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | Ne peut être utilisé qu'avec MicroPdf417 et encode les modes d'émulation Code 128. Peut encoder FNC1 en deuxième position dans les modes 908 et 909, peut également encoder 910 et 911 qui indiquent simplement que le MicroPdf417 reconnu peut être interprété comme Code 128. |
| [setColumns(int value)](#setColumns-int-) | Nombre de colonnes. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identifiants d'interprétation de canal étendu. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Type de symbologie Pdf417 du mode d'encodage du code-barres. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Définit le type de symbologie Pdf417 du niveau de correction d'erreurs du code-barres, allant de level0 à level8, level0 signifie aucune information de correction d'erreurs, level8 signifie la meilleure correction d'erreurs, ce qui entraîne une image plus grande. |
| [setLinked(boolean value)](#setLinked-boolean-) | Définit les modes liés avec les codes-barres GS1MicroPdf417, MicroPdf417 et Pdf417. Avec la symbologie GS1MicroPdf417, encode 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d modes UCC/EAN-128. Avec les symbologies MicroPdf417 et Pdf417, encode le drapeau de liaison 918 vers le composant linéaire associé autre qu'un EAN.UCC. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Les valeurs des caractères macro 05 et 06 sont utilisées pour obtenir un encodage plus compact dans des modes spéciaux. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | Nom du destinataire du code-barres MacroPdf417 (champ optionnel). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | Somme de contrôle du code-barres MacroPdf417 (champ optionnel). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | Identifiants d'interprétation de canal étendu. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | Définit l'ID de fichier du code-barres macro Pdf417. |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | Nom de fichier du code-barres MacroPdf417 (champ optionnel). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | Taille du fichier MacroPdf417 (champ optionnel). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | Définit l'ID de segment du code-barres macro Pdf417, qui commence à 0, jusqu'à MacroSegmentsCount - 1. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | Définit le nombre de segments du code-barres macro Pdf417. |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | Nom de l'expéditeur du code-barres MacroPdf417 (champ optionnel). |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Utilisé pour indiquer à l'encodeur s'il faut ajouter le terminateur Macro PDF417 (codeword 922) au segment. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | Horodatage du code-barres MacroPdf417 (champ optionnel). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur. |
| [setRows(int value)](#setRows-int-) | Nombre de lignes. |
| [setTruncate(boolean value)](#setTruncate-boolean-) | Indique si le type de symbologie Pdf417 du code-barres est tronqué (pour réduire l'espace). |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters). |
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
### getColumns() {#getColumns--}
```
public final int getColumns()
```


Nombre de colonnes.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails concernant les références utilisées pour l'encodage des données dans le symbole. Non appliqué aux champs texte Macro PDF417. L'implémentation actuelle comprend tous les encodages de jeux de caractères bien connus.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


Type de symbologie Pdf417 du mode d'encodage du BarCode. Valeur par défaut : Pdf417EncodeMode.Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


Obtient le type de symbologie Pdf417 du niveau de correction d'erreurs du code-barres, allant de level0 à level8, level0 signifie aucune information de correction d'erreurs, level8 signifie la meilleure correction d'erreurs, ce qui entraîne une image plus grande.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Les valeurs des caractères macro 05 et 06 sont utilisées pour obtenir un encodage plus compact dans des modes spéciaux. Elles ne peuvent être utilisées qu'avec MicroPdf417 et encodent les modes MicroPdf417 916 et 917. Valeur par défaut : MacroCharacters.None.

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


Nom du destinataire du code-barres MacroPdf417 (champ optionnel). Nom du destinataire du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


Somme de contrôle du code-barres MacroPdf417 (champ optionnel). Somme de contrôle du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append). Le champ de somme de contrôle contient la valeur du CRC 16 bits (2 octets) utilisant le polynôme CCITT-16. x^16 + x^12 + x^5 + 1

**Returns:**
int
### getMacroPdf417ECIEncoding() {#getMacroPdf417ECIEncoding--}
```
public final int getMacroPdf417ECIEncoding()
```


Identifiants d'Interprétation de Canal Étendu. S'applique aux champs texte Macro PDF417.

**Returns:**
int
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


Obtient l'ID du fichier du code-barres macro Pdf417. Utilisé pour MacroPdf417.

**Returns:**
int - ID du fichier du code-barres macro Pdf417.
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


Nom de fichier du code-barres MacroPdf417 (champ optionnel). Nom de fichier du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public final int getMacroPdf417FileSize()
```


Taille du fichier MacroPdf417 (champ optionnel). Taille du fichier MicroPDF417 (champ optionnel pour le mode Structured Append). Le champ de taille du fichier contient la taille en octets du fichier source complet.

**Returns:**
int
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


Obtient l'ID de segment du code-barres macro Pdf417, qui commence à 0, jusqu'à MacroSegmentsCount - 1.

**Returns:**
int - ID du segment du code-barres macro Pdf417, qui commence à 0, jusqu'à MacroSegmentsCount - 1.
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


Obtient le nombre de segments du code-barres macro Pdf417.

**Returns:**
int - nombre de segments du code-barres macro Pdf417.
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


Nom de l'expéditeur du code-barres MacroPdf417 (champ optionnel). Nom de l'expéditeur du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


Utilisé pour indiquer à l'encodeur s'il faut ajouter le Terminator Macro PDF417 (code mot 922) au segment. Appliqué uniquement pour Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


Horodatage du code-barres MacroPdf417 (champ optionnel). Horodatage du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append).

**Returns:**
java.time.LocalDateTime
### getRows() {#getRows--}
```
public final int getRows()
```


Nombre de lignes.

**Returns:**
int
### getTruncate() {#getTruncate--}
```
public final boolean getTruncate()
```


Indique si le type de symbologie Pdf417 du code-barres est tronqué (pour réduire l'espace).

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCode128Emulation() {#isCode128Emulation--}
```
public final boolean isCode128Emulation()
```


Ne peut être utilisé qu'avec MicroPdf417 et encode les modes d'émulation Code 128. Peut encoder FNC1 en deuxième position dans les modes 908 et 909, peut également encoder 910 et 911 qui indiquent simplement que le MicroPdf417 reconnu peut être interprété comme Code 128.

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


Définit les modes liés avec les codes-barres GS1MicroPdf417, MicroPdf417 et Pdf417. Avec la symbologie GS1MicroPdf417, encode 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d modes UCC/EAN-128. Avec les symbologies MicroPdf417 et Pdf417, encode le drapeau de liaison 918 vers le composant linéaire associé autre qu'un EAN.UCC.

**Returns:**
boolean
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


Rapport hauteur/largeur du module de code-barres 2D.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


Ne peut être utilisé qu'avec MicroPdf417 et encode les modes d'émulation Code 128. Peut encoder FNC1 en deuxième position dans les modes 908 et 909, peut également encoder 910 et 911 qui indiquent simplement que le MicroPdf417 reconnu peut être interprété comme Code 128.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Nombre de colonnes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails concernant les références utilisées pour l'encodage des données dans le symbole. Non appliqué aux champs texte Macro PDF417. L'implémentation actuelle comprend tous les encodages de jeux de caractères bien connus.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


Type de symbologie Pdf417 du mode d'encodage du BarCode. Valeur par défaut : Pdf417EncodeMode.Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


Définit le type de symbologie Pdf417 du niveau de correction d'erreurs du code-barres, allant de level0 à level8, level0 signifie aucune information de correction d'erreurs, level8 signifie la meilleure correction d'erreurs, ce qui entraîne une image plus grande.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Type de symbologie Pdf417 du niveau de correction d'erreurs du BarCode, allant de level0 à level8, level0 signifie aucune information de correction d'erreurs, level8 signifie la meilleure correction d'erreurs, ce qui entraîne une image plus grande. |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Définit les modes liés avec les codes-barres GS1MicroPdf417, MicroPdf417 et Pdf417. Avec la symbologie GS1MicroPdf417, encode 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d modes UCC/EAN-128. Avec les symbologies MicroPdf417 et Pdf417, encode le drapeau de liaison 918 vers le composant linéaire associé autre qu'un EAN.UCC.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Les valeurs des caractères macro 05 et 06 sont utilisées pour obtenir un encodage plus compact dans des modes spéciaux. Elles ne peuvent être utilisées qu'avec MicroPdf417 et encodent les modes MicroPdf417 916 et 917. Valeur par défaut : MacroCharacters.None.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


Nom du destinataire du code-barres MacroPdf417 (champ optionnel). Nom du destinataire du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


Somme de contrôle du code-barres MacroPdf417 (champ optionnel). Somme de contrôle du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append). Le champ de somme de contrôle contient la valeur du CRC 16 bits (2 octets) utilisant le polynôme CCITT-16. x^16 + x^12 + x^5 + 1

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


Identifiants d'Interprétation de Canal Étendu. S'applique aux champs texte Macro PDF417.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


Définit l'ID du fichier du code-barres macro Pdf417. Utilisé pour MacroPdf417.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | ID du fichier du code-barres macro Pdf417. |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


Nom de fichier du code-barres MacroPdf417 (champ optionnel). Nom de fichier du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


Taille du fichier MacroPdf417 (champ optionnel). Taille du fichier MicroPDF417 (champ optionnel pour le mode Structured Append). Le champ de taille du fichier contient la taille en octets du fichier source complet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


Définit l'ID de segment du code-barres macro Pdf417, qui commence à 0, jusqu'à MacroSegmentsCount - 1.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | ID du segment du code-barres macro Pdf417, qui commence à 0, jusqu'à MacroSegmentsCount - 1. |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


Définit le nombre de segments du code-barres macro Pdf417.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nombre de segments du code-barres macro Pdf417. |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


Nom de l'expéditeur du code-barres MacroPdf417 (champ optionnel). Nom de l'expéditeur du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


Utilisé pour indiquer à l'encodeur s'il faut ajouter le Terminator Macro PDF417 (code mot 922) au segment. Appliqué uniquement pour Macro PDF417.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


Horodatage du code-barres MacroPdf417 (champ optionnel). Horodatage du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.time.LocalDateTime |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur.

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

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


Indique si le type de symbologie Pdf417 du code-barres est tronqué (pour réduire l'espace).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne lisible par l'homme de ce [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).

**Returns:**
java.lang.String - Une chaîne qui représente ce [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).
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

