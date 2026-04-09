---
title: Pdf417Parameters
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Paramètres PDF417.
type: docs
weight: 60
url: /fr/androidjava/com.aspose.barcode.generation/pdf417parameters/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417Parameters
```

Paramètres PDF417. Contient les paramètres PDF417, MacroPDF417, MicroPDF417 et GS1MicroPdf417. MacroPDF417 nécessite deux champs : Pdf417MacroFileID et Pdf417MacroSegmentID. Tous les autres champs sont facultatifs. MicroPDF417 en mode Structured Append (identique au mode MacroPDF417) nécessite deux champs : Pdf417MacroFileID et Pdf417MacroSegmentID. Tous les autres champs sont facultatifs.

Ces exemples montrent comment encoder les modes non liés UCC/EAN-128 dans GS1MicroPdf417.

```

 [C#]
 //Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes GS1 UCC/EAN-128 non Linked modes 903, 904 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Ratio hauteur/largeur du module du code-barres 2D. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Nombre de colonnes. |
| [getECIEncoding()](#getECIEncoding--) | Identifiants d'interprétation de canal étendu. |
| [getEncodeMode()](#getEncodeMode--) | Identifie le mode d’encodage Pdf417. |
| [getErrorLevel()](#getErrorLevel--) | Obtient le type de symbologie Pdf417 du niveau de correction d’erreurs du code-barres, allant de level0 à level8, level0 signifie aucune information de correction d’erreurs, level8 signifie la meilleure correction d’erreurs, ce qui entraîne une image plus grande. |
| [getMacroCharacters()](#getMacroCharacters--) | Les valeurs des caractères macro 05 et 06 sont utilisées pour obtenir un encodage plus compact dans les modes spéciaux. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Nom du destinataire du code-barres MacroPdf417 (champ facultatif). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Somme de contrôle du code-barres MacroPdf417 (champ facultatif). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | Identifiants d'interprétation de canal étendu. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Identifiant de fichier du code-barres MacroPdf417 (champ obligatoire). |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Nom de fichier du code-barres MacroPdf417 (champ facultatif). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Taille du fichier MacroPdf417 (champ facultatif). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | ID de segment du code-barres MacroPdf417 (champ requis), qui commence à 0, jusqu'à MacroSegmentsCount - 1. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Nombre de segments du code-barres MacroPdf417 (champ facultatif). |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Nom de l'expéditeur du code-barres MacroPdf417 (champ facultatif). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Utilisé pour indiquer à l'encodeur s'il faut ajouter le Terminator Macro PDF417 (code mot 922) au segment. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Horodatage du code-barres MacroPdf417 (champ facultatif). |
| [getPdf417CompactionMode()](#getPdf417CompactionMode--) | Type de symbologie Pdf417 du mode de compaction du BarCode. |
| [getPdf417ECIEncoding()](#getPdf417ECIEncoding--) | Identifiants d'interprétation de canal étendu. |
| [getPdf417EncodeMode()](#getPdf417EncodeMode--) | Identifie le mode d’encodage Pdf417. |
| [getPdf417ErrorLevel()](#getPdf417ErrorLevel--) | Obtient le type de symbologie Pdf417 du niveau de correction d’erreurs du code-barres, allant de level0 à level8, level0 signifie aucune information de correction d’erreurs, level8 signifie la meilleure correction d’erreurs, ce qui entraîne une image plus grande. |
| [getPdf417MacroAddressee()](#getPdf417MacroAddressee--) | Nom du destinataire du code-barres MacroPdf417 (champ facultatif). |
| [getPdf417MacroChecksum()](#getPdf417MacroChecksum--) | Somme de contrôle du code-barres MacroPdf417 (champ facultatif). |
| [getPdf417MacroECIEncoding()](#getPdf417MacroECIEncoding--) | Identifiants d'interprétation de canal étendu. |
| [getPdf417MacroFileID()](#getPdf417MacroFileID--) | Identifiant de fichier du code-barres MacroPdf417 (champ obligatoire). |
| [getPdf417MacroFileName()](#getPdf417MacroFileName--) | Nom de fichier du code-barres MacroPdf417 (champ facultatif). |
| [getPdf417MacroFileSize()](#getPdf417MacroFileSize--) | Taille du fichier MacroPdf417 (champ facultatif). |
| [getPdf417MacroSegmentID()](#getPdf417MacroSegmentID--) | ID de segment du code-barres MacroPdf417 (champ requis), qui commence à 0, jusqu'à MacroSegmentsCount - 1. |
| [getPdf417MacroSegmentsCount()](#getPdf417MacroSegmentsCount--) | Nombre de segments du code-barres MacroPdf417 (champ facultatif). |
| [getPdf417MacroSender()](#getPdf417MacroSender--) | Nom de l'expéditeur du code-barres MacroPdf417 (champ facultatif). |
| [getPdf417MacroTerminator()](#getPdf417MacroTerminator--) | Utilisé pour indiquer à l'encodeur s'il faut ajouter le Terminator Macro PDF417 (code mot 922) au segment. |
| [getPdf417MacroTimeStamp()](#getPdf417MacroTimeStamp--) | Horodatage du code-barres MacroPdf417 (champ facultatif). |
| [getPdf417Truncate()](#getPdf417Truncate--) | Indique si le type de symbologie Pdf417 du BarCode est tronqué (pour réduire l'espace). |
| [getRows()](#getRows--) | Nombre de lignes. |
| [getTruncate()](#getTruncate--) | Indique si le type de symbologie Pdf417 du BarCode est tronqué (pour réduire l'espace). |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | Ne peut être utilisé qu'avec MicroPdf417 et encode les modes d'émulation Code 128. Peut encoder FNC1 en deuxième position dans les modes 908 et 909, peut également encoder 910 et 911 qui indiquent simplement que le MicroPdf417 reconnu peut être interprété comme Code 128. |
| [isLinked()](#isLinked--) | Définit les modes liés avec les codes-barres GS1MicroPdf417, MicroPdf417 et Pdf417. Avec la symbologie GS1MicroPdf417, encode les modes UCC/EAN-128 "Linked" 906, 907, 912, 913, 914, 915. Avec les symbologies MicroPdf417 et Pdf417, encode le drapeau de liaison 918 vers le composant linéaire associé autre qu'un EAN.UCC. |
| [isReaderInitialization()](#isReaderInitialization--) | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Ratio hauteur/largeur du module du code-barres 2D. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | Ne peut être utilisé qu'avec MicroPdf417 et encode les modes d'émulation Code 128. Peut encoder FNC1 en deuxième position dans les modes 908 et 909, peut également encoder 910 et 911 qui indiquent simplement que le MicroPdf417 reconnu peut être interprété comme Code 128. |
| [setColumns(int value)](#setColumns-int-) | Nombre de colonnes. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identifiants d'interprétation de canal étendu. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Identifie le mode d’encodage Pdf417. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Définit le niveau de correction d'erreur du type de symbologie Pdf417 du BarCode, allant de level0 à level8 ; level0 signifie aucune information de correction d'erreur, level8 signifie la meilleure correction d'erreur, ce qui implique une image plus grande. |
| [setLinked(boolean value)](#setLinked-boolean-) | Définit les modes liés avec les codes-barres GS1MicroPdf417, MicroPdf417 et Pdf417. Avec la symbologie GS1MicroPdf417, encode les modes UCC/EAN-128 "Linked" 906, 907, 912, 913, 914, 915. Avec les symbologies MicroPdf417 et Pdf417, encode le drapeau de liaison 918 vers le composant linéaire associé autre qu'un EAN.UCC. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Les valeurs des caractères macro 05 et 06 sont utilisées pour obtenir un encodage plus compact dans les modes spéciaux. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | Nom du destinataire du code-barres MacroPdf417 (champ facultatif). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | Somme de contrôle du code-barres MacroPdf417 (champ facultatif). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | Identifiants d'interprétation de canal étendu. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | Identifiant de fichier du code-barres MacroPdf417 (champ obligatoire). |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | Nom de fichier du code-barres MacroPdf417 (champ facultatif). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | Taille du fichier MacroPdf417 (champ facultatif). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | ID de segment du code-barres MacroPdf417 (champ requis), qui commence à 0, jusqu'à MacroSegmentsCount - 1. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | Nombre de segments du code-barres MacroPdf417 (champ facultatif). |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | Nom de l'expéditeur du code-barres MacroPdf417 (champ facultatif). |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Utilisé pour indiquer à l'encodeur s'il faut ajouter le Terminator Macro PDF417 (code mot 922) au segment. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | Horodatage du code-barres MacroPdf417 (champ facultatif). |
| [setPdf417CompactionMode(Pdf417CompactionMode value)](#setPdf417CompactionMode-com.aspose.barcode.generation.Pdf417CompactionMode-) | Type de symbologie Pdf417 du mode de compaction du BarCode. |
| [setPdf417ECIEncoding(int value)](#setPdf417ECIEncoding-int-) | Identifiants d'interprétation de canal étendu. |
| [setPdf417EncodeMode(Pdf417EncodeMode value)](#setPdf417EncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Identifie le mode d’encodage Pdf417. |
| [setPdf417ErrorLevel(Pdf417ErrorLevel value)](#setPdf417ErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Définit le niveau de correction d'erreur du type de symbologie Pdf417 du BarCode, allant de level0 à level8 ; level0 signifie aucune information de correction d'erreur, level8 signifie la meilleure correction d'erreur, ce qui implique une image plus grande. |
| [setPdf417MacroAddressee(String value)](#setPdf417MacroAddressee-java.lang.String-) | Nom du destinataire du code-barres MacroPdf417 (champ facultatif). |
| [setPdf417MacroChecksum(int value)](#setPdf417MacroChecksum-int-) | Somme de contrôle du code-barres MacroPdf417 (champ facultatif). |
| [setPdf417MacroECIEncoding(int value)](#setPdf417MacroECIEncoding-int-) | Identifiants d'interprétation de canal étendu. |
| [setPdf417MacroFileID(int value)](#setPdf417MacroFileID-int-) | Identifiant de fichier du code-barres MacroPdf417 (champ obligatoire). |
| [setPdf417MacroFileName(String value)](#setPdf417MacroFileName-java.lang.String-) | Nom de fichier du code-barres MacroPdf417 (champ facultatif). |
| [setPdf417MacroFileSize(int value)](#setPdf417MacroFileSize-int-) | Taille du fichier MacroPdf417 (champ facultatif). |
| [setPdf417MacroSegmentID(int value)](#setPdf417MacroSegmentID-int-) | ID de segment du code-barres MacroPdf417 (champ requis), qui commence à 0, jusqu'à MacroSegmentsCount - 1. |
| [setPdf417MacroSegmentsCount(int value)](#setPdf417MacroSegmentsCount-int-) | Nombre de segments du code-barres MacroPdf417 (champ facultatif). |
| [setPdf417MacroSender(String value)](#setPdf417MacroSender-java.lang.String-) | Nom de l'expéditeur du code-barres MacroPdf417 (champ facultatif). |
| [setPdf417MacroTerminator(Pdf417MacroTerminator value)](#setPdf417MacroTerminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Utilisé pour indiquer à l'encodeur s'il faut ajouter le Terminator Macro PDF417 (code mot 922) au segment. |
| [setPdf417MacroTimeStamp(LocalDateTime value)](#setPdf417MacroTimeStamp-java.time.LocalDateTime-) | Horodatage du code-barres MacroPdf417 (champ facultatif). |
| [setPdf417Truncate(boolean value)](#setPdf417Truncate-boolean-) | Indique si le type de symbologie Pdf417 du BarCode est tronqué (pour réduire l'espace). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur. |
| [setRows(int value)](#setRows-int-) | Nombre de lignes. |
| [setTruncate(boolean value)](#setTruncate-boolean-) | Indique si le type de symbologie Pdf417 du BarCode est tronqué (pour réduire l'espace). |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible de cet [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters). |
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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails concernant les références utilisées pour encoder les données dans le symbole. Non appliqué aux champs texte Macro PDF417. L'implémentation actuelle comprend tous les encodages de jeu de caractères bien connus.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


Identifie le mode d'encodage Pdf417. Valeur par défaut : Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


Obtient le type de symbologie Pdf417 du niveau de correction d’erreurs du code-barres, allant de level0 à level8, level0 signifie aucune information de correction d’erreurs, level8 signifie la meilleure correction d’erreurs, ce qui entraîne une image plus grande.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Les valeurs des Macro Caractères 05 et 06 sont utilisées pour obtenir un encodage plus compact dans des modes spéciaux. Ne peut être utilisé qu'avec MicroPdf417 et encode les modes MicroPdf417 916 et 917. Valeur par défaut : MacroCharacters.None.

Ces exemples montrent comment encoder les Macro Caractères dans MicroPdf417.

```

 [C#]
 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
     using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
       foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


Nom du destinataire du code-barres MacroPdf417 (champ facultatif). Nom du destinataire du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


Somme de contrôle du code-barres MacroPdf417 (champ facultatif). Somme de contrôle du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append). Le champ de somme de contrôle contient la valeur de la somme de contrôle CRC 16 bits (2 octets) utilisant le polynôme CCITT-16. x^16 + x^12 + x^5 + 1

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


ID de fichier du code-barres MacroPdf417 (champ requis). ID de fichier du code-barres MicroPDF417 (champ requis pour le mode Structured Append).

**Returns:**
int
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


Nom de fichier du code-barres MacroPdf417 (champ facultatif). Nom de fichier du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public final int getMacroPdf417FileSize()
```


Taille du fichier MacroPdf417 (champ facultatif). Taille du fichier MicroPDF417 (champ facultatif pour le mode Structured Append). Le champ taille du fichier contient la taille en octets du fichier source complet.

**Returns:**
int
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


ID de segment du code-barres MacroPdf417 (champ requis), qui commence à 0, jusqu'à MacroSegmentsCount - 1. ID de segment du code-barres MicroPDF417 (champ requis pour le mode Structured Append).

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


Nombre de segments du code-barres MacroPdf417 (champ facultatif). Nombre de segments du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append).

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


Nom de l'expéditeur du code-barres MacroPdf417 (champ facultatif). Nom de l'expéditeur du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


Utilisé pour indiquer à l'encodeur s'il faut ajouter le Macro PDF417 Terminator (codeword 922) au segment. Appliqué uniquement pour Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


Horodatage du code-barres MacroPdf417 (champ facultatif). Horodatage du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append).

**Returns:**
java.time.LocalDateTime
### getPdf417CompactionMode() {#getPdf417CompactionMode--}
```
public final Pdf417CompactionMode getPdf417CompactionMode()
```


Type de symbologie Pdf417 du mode de compaction du code-barres. Valeur par défaut : Pdf417CompactionMode.Auto.

**Returns:**
[Pdf417CompactionMode](../../com.aspose.barcode.generation/pdf417compactionmode)
### getPdf417ECIEncoding() {#getPdf417ECIEncoding--}
```
public final int getPdf417ECIEncoding()
```


Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails concernant les références utilisées pour encoder les données dans le symbole. Non appliqué aux champs texte Macro PDF417. L'implémentation actuelle comprend tous les encodages de jeu de caractères bien connus.

**Returns:**
int
### getPdf417EncodeMode() {#getPdf417EncodeMode--}
```
public final Pdf417EncodeMode getPdf417EncodeMode()
```


Identifie le mode d'encodage Pdf417. Valeur par défaut : Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getPdf417ErrorLevel() {#getPdf417ErrorLevel--}
```
public final Pdf417ErrorLevel getPdf417ErrorLevel()
```


Obtient le type de symbologie Pdf417 du niveau de correction d’erreurs du code-barres, allant de level0 à level8, level0 signifie aucune information de correction d’erreurs, level8 signifie la meilleure correction d’erreurs, ce qui entraîne une image plus grande.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getPdf417MacroAddressee() {#getPdf417MacroAddressee--}
```
public final String getPdf417MacroAddressee()
```


Nom du destinataire du code-barres MacroPdf417 (champ facultatif). Nom du destinataire du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append).

**Returns:**
java.lang.String
### getPdf417MacroChecksum() {#getPdf417MacroChecksum--}
```
public final int getPdf417MacroChecksum()
```


Somme de contrôle du code-barres MacroPdf417 (champ facultatif). Somme de contrôle du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append). Le champ de somme de contrôle contient la valeur de la somme de contrôle CRC 16 bits (2 octets) utilisant le polynôme CCITT-16. x^16 + x^12 + x^5 + 1

**Returns:**
int
### getPdf417MacroECIEncoding() {#getPdf417MacroECIEncoding--}
```
public final int getPdf417MacroECIEncoding()
```


Identifiants d'Interprétation de Canal Étendu. S'applique aux champs texte Macro PDF417.

**Returns:**
int
### getPdf417MacroFileID() {#getPdf417MacroFileID--}
```
public final int getPdf417MacroFileID()
```


ID de fichier du code-barres MacroPdf417 (champ requis). ID de fichier du code-barres MicroPDF417 (champ requis pour le mode Structured Append).

**Returns:**
int
### getPdf417MacroFileName() {#getPdf417MacroFileName--}
```
public final String getPdf417MacroFileName()
```


Nom de fichier du code-barres MacroPdf417 (champ facultatif). Nom de fichier du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append).

**Returns:**
java.lang.String
### getPdf417MacroFileSize() {#getPdf417MacroFileSize--}
```
public final int getPdf417MacroFileSize()
```


Taille du fichier MacroPdf417 (champ facultatif). Taille du fichier MicroPDF417 (champ facultatif pour le mode Structured Append). Le champ taille du fichier contient la taille en octets du fichier source complet.

**Returns:**
int
### getPdf417MacroSegmentID() {#getPdf417MacroSegmentID--}
```
public final int getPdf417MacroSegmentID()
```


ID de segment du code-barres MacroPdf417 (champ requis), qui commence à 0, jusqu'à MacroSegmentsCount - 1. ID de segment du code-barres MicroPDF417 (champ requis pour le mode Structured Append).

**Returns:**
int
### getPdf417MacroSegmentsCount() {#getPdf417MacroSegmentsCount--}
```
public final int getPdf417MacroSegmentsCount()
```


Nombre de segments du code-barres MacroPdf417 (champ facultatif). Nombre de segments du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append).

**Returns:**
int
### getPdf417MacroSender() {#getPdf417MacroSender--}
```
public final String getPdf417MacroSender()
```


Nom de l'expéditeur du code-barres MacroPdf417 (champ facultatif). Nom de l'expéditeur du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append).

**Returns:**
java.lang.String
### getPdf417MacroTerminator() {#getPdf417MacroTerminator--}
```
public final Pdf417MacroTerminator getPdf417MacroTerminator()
```


Utilisé pour indiquer à l'encodeur s'il faut ajouter le Macro PDF417 Terminator (codeword 922) au segment. Appliqué uniquement pour Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getPdf417MacroTimeStamp() {#getPdf417MacroTimeStamp--}
```
public final LocalDateTime getPdf417MacroTimeStamp()
```


Horodatage du code-barres MacroPdf417 (champ facultatif). Horodatage du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append).

**Returns:**
java.time.LocalDateTime
### getPdf417Truncate() {#getPdf417Truncate--}
```
public final boolean getPdf417Truncate()
```


Indique si le type de symbologie Pdf417 du code-barres est tronqué (pour réduire l'espace). Aussi connu sous le nom de CompactPDF417. L'indicateur de ligne droite et le motif d'arrêt droit sont supprimés dans ce mode.

**Returns:**
boolean
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


Indique si le type de symbologie Pdf417 du code-barres est tronqué (pour réduire l'espace). Aussi connu sous le nom de CompactPDF417. L'indicateur de ligne droite et le motif d'arrêt droit sont supprimés dans ce mode.

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

Ces exemples montrent comment encoder les modes d'émulation Code 128 avec FNC1 en deuxième position et sans. De cette façon, MicroPdf417 peut être décodé comme un code-barres Code 128.

```

 [C#]
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a1222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "991222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 
```

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


Définit les modes liés avec les codes-barres GS1MicroPdf417, MicroPdf417 et Pdf417. Avec la symbologie GS1MicroPdf417, encode les modes UCC/EAN-128 "Linked" 906, 907, 912, 913, 914, 915. Avec les symbologies MicroPdf417 et Pdf417, encode le drapeau de liaison 918 vers le composant linéaire associé autre qu'un EAN.UCC.

Ces exemples montrent comment encoder les modes "Linked" UCC/EAN-128 dans GS1MicroPdf417 et le drapeau de liaison (918) dans les codes-barres MicroPdf417 et Pdf417.

```

 [C#]
 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked modes 906, 907 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 
```

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


Ratio hauteur/largeur du module du code-barres 2D.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


Ne peut être utilisé qu'avec MicroPdf417 et encode les modes d'émulation Code 128. Peut encoder FNC1 en deuxième position dans les modes 908 et 909, peut également encoder 910 et 911 qui indiquent simplement que le MicroPdf417 reconnu peut être interprété comme Code 128.

Ces exemples montrent comment encoder les modes d'émulation Code 128 avec FNC1 en deuxième position et sans. De cette façon, MicroPdf417 peut être décodé comme un code-barres Code 128.

```

 [C#]
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a1222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "991222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 
```

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


Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails concernant les références utilisées pour encoder les données dans le symbole. Non appliqué aux champs texte Macro PDF417. L'implémentation actuelle comprend tous les encodages de jeu de caractères bien connus.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


Identifie le mode d'encodage Pdf417. Valeur par défaut : Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


Définit le niveau de correction d'erreur du type de symbologie Pdf417 du BarCode, allant de level0 à level8 ; level0 signifie aucune information de correction d'erreur, level8 signifie la meilleure correction d'erreur, ce qui implique une image plus grande.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Type de symbologie Pdf417 du niveau de correction d'erreurs du code-barres, allant de level0 à level8, level0 signifie aucune information de correction d'erreurs, level8 signifie la meilleure correction d'erreurs, ce qui entraîne une image plus grande. |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Définit les modes liés avec les codes-barres GS1MicroPdf417, MicroPdf417 et Pdf417. Avec la symbologie GS1MicroPdf417, encode les modes UCC/EAN-128 "Linked" 906, 907, 912, 913, 914, 915. Avec les symbologies MicroPdf417 et Pdf417, encode le drapeau de liaison 918 vers le composant linéaire associé autre qu'un EAN.UCC.

Ces exemples montrent comment encoder les modes "Linked" UCC/EAN-128 dans GS1MicroPdf417 et le drapeau de liaison (918) dans les codes-barres MicroPdf417 et Pdf417.

```

 [C#]
 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked modes 906, 907 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Les valeurs des Macro Caractères 05 et 06 sont utilisées pour obtenir un encodage plus compact dans des modes spéciaux. Ne peut être utilisé qu'avec MicroPdf417 et encode les modes MicroPdf417 916 et 917. Valeur par défaut : MacroCharacters.None.

Ces exemples montrent comment encoder les Macro Caractères dans MicroPdf417.

```

 [C#]
 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
     using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
       foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


Nom du destinataire du code-barres MacroPdf417 (champ facultatif). Nom du destinataire du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


Somme de contrôle du code-barres MacroPdf417 (champ facultatif). Somme de contrôle du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append). Le champ de somme de contrôle contient la valeur de la somme de contrôle CRC 16 bits (2 octets) utilisant le polynôme CCITT-16. x^16 + x^12 + x^5 + 1

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


ID de fichier du code-barres MacroPdf417 (champ requis). ID de fichier du code-barres MicroPDF417 (champ requis pour le mode Structured Append).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


Nom de fichier du code-barres MacroPdf417 (champ facultatif). Nom de fichier du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


Taille du fichier MacroPdf417 (champ facultatif). Taille du fichier MicroPDF417 (champ facultatif pour le mode Structured Append). Le champ taille du fichier contient la taille en octets du fichier source complet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


ID de segment du code-barres MacroPdf417 (champ requis), qui commence à 0, jusqu'à MacroSegmentsCount - 1. ID de segment du code-barres MicroPDF417 (champ requis pour le mode Structured Append).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


Nombre de segments du code-barres MacroPdf417 (champ facultatif). Nombre de segments du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


Nom de l'expéditeur du code-barres MacroPdf417 (champ facultatif). Nom de l'expéditeur du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


Utilisé pour indiquer à l'encodeur s'il faut ajouter le Macro PDF417 Terminator (codeword 922) au segment. Appliqué uniquement pour Macro PDF417.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


Horodatage du code-barres MacroPdf417 (champ facultatif). Horodatage du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.time.LocalDateTime |  |

### setPdf417CompactionMode(Pdf417CompactionMode value) {#setPdf417CompactionMode-com.aspose.barcode.generation.Pdf417CompactionMode-}
```
public final void setPdf417CompactionMode(Pdf417CompactionMode value)
```


Type de symbologie Pdf417 du mode de compaction du code-barres. Valeur par défaut : Pdf417CompactionMode.Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Pdf417CompactionMode](../../com.aspose.barcode.generation/pdf417compactionmode) |  |

### setPdf417ECIEncoding(int value) {#setPdf417ECIEncoding-int-}
```
public final void setPdf417ECIEncoding(int value)
```


Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails concernant les références utilisées pour encoder les données dans le symbole. Non appliqué aux champs texte Macro PDF417. L'implémentation actuelle comprend tous les encodages de jeu de caractères bien connus.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPdf417EncodeMode(Pdf417EncodeMode value) {#setPdf417EncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setPdf417EncodeMode(Pdf417EncodeMode value)
```


Identifie le mode d'encodage Pdf417. Valeur par défaut : Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setPdf417ErrorLevel(Pdf417ErrorLevel value) {#setPdf417ErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setPdf417ErrorLevel(Pdf417ErrorLevel value)
```


Définit le niveau de correction d'erreur du type de symbologie Pdf417 du BarCode, allant de level0 à level8 ; level0 signifie aucune information de correction d'erreur, level8 signifie la meilleure correction d'erreur, ce qui implique une image plus grande.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Type de symbologie Pdf417 du niveau de correction d'erreurs du code-barres, allant de level0 à level8, level0 signifie aucune information de correction d'erreurs, level8 signifie la meilleure correction d'erreurs, ce qui entraîne une image plus grande. |

### setPdf417MacroAddressee(String value) {#setPdf417MacroAddressee-java.lang.String-}
```
public final void setPdf417MacroAddressee(String value)
```


Nom du destinataire du code-barres MacroPdf417 (champ facultatif). Nom du destinataire du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setPdf417MacroChecksum(int value) {#setPdf417MacroChecksum-int-}
```
public final void setPdf417MacroChecksum(int value)
```


Somme de contrôle du code-barres MacroPdf417 (champ facultatif). Somme de contrôle du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append). Le champ de somme de contrôle contient la valeur de la somme de contrôle CRC 16 bits (2 octets) utilisant le polynôme CCITT-16. x^16 + x^12 + x^5 + 1

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPdf417MacroECIEncoding(int value) {#setPdf417MacroECIEncoding-int-}
```
public final void setPdf417MacroECIEncoding(int value)
```


Identifiants d'Interprétation de Canal Étendu. S'applique aux champs texte Macro PDF417.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPdf417MacroFileID(int value) {#setPdf417MacroFileID-int-}
```
public final void setPdf417MacroFileID(int value)
```


ID de fichier du code-barres MacroPdf417 (champ requis). ID de fichier du code-barres MicroPDF417 (champ requis pour le mode Structured Append).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPdf417MacroFileName(String value) {#setPdf417MacroFileName-java.lang.String-}
```
public final void setPdf417MacroFileName(String value)
```


Nom de fichier du code-barres MacroPdf417 (champ facultatif). Nom de fichier du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setPdf417MacroFileSize(int value) {#setPdf417MacroFileSize-int-}
```
public final void setPdf417MacroFileSize(int value)
```


Taille du fichier MacroPdf417 (champ facultatif). Taille du fichier MicroPDF417 (champ facultatif pour le mode Structured Append). Le champ taille du fichier contient la taille en octets du fichier source complet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPdf417MacroSegmentID(int value) {#setPdf417MacroSegmentID-int-}
```
public final void setPdf417MacroSegmentID(int value)
```


ID de segment du code-barres MacroPdf417 (champ requis), qui commence à 0, jusqu'à MacroSegmentsCount - 1. ID de segment du code-barres MicroPDF417 (champ requis pour le mode Structured Append).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPdf417MacroSegmentsCount(int value) {#setPdf417MacroSegmentsCount-int-}
```
public final void setPdf417MacroSegmentsCount(int value)
```


Nombre de segments du code-barres MacroPdf417 (champ facultatif). Nombre de segments du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPdf417MacroSender(String value) {#setPdf417MacroSender-java.lang.String-}
```
public final void setPdf417MacroSender(String value)
```


Nom de l'expéditeur du code-barres MacroPdf417 (champ facultatif). Nom de l'expéditeur du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setPdf417MacroTerminator(Pdf417MacroTerminator value) {#setPdf417MacroTerminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setPdf417MacroTerminator(Pdf417MacroTerminator value)
```


Utilisé pour indiquer à l'encodeur s'il faut ajouter le Macro PDF417 Terminator (codeword 922) au segment. Appliqué uniquement pour Macro PDF417.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setPdf417MacroTimeStamp(LocalDateTime value) {#setPdf417MacroTimeStamp-java.time.LocalDateTime-}
```
public final void setPdf417MacroTimeStamp(LocalDateTime value)
```


Horodatage du code-barres MacroPdf417 (champ facultatif). Horodatage du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.time.LocalDateTime |  |

### setPdf417Truncate(boolean value) {#setPdf417Truncate-boolean-}
```
public final void setPdf417Truncate(boolean value)
```


Indique si le type de symbologie Pdf417 du code-barres est tronqué (pour réduire l'espace). Aussi connu sous le nom de CompactPDF417. L'indicateur de ligne droite et le motif d'arrêt droit sont supprimés dans ce mode.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

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


Indique si le type de symbologie Pdf417 du code-barres est tronqué (pour réduire l'espace). Aussi connu sous le nom de CompactPDF417. L'indicateur de ligne droite et le motif d'arrêt droit sont supprimés dans ce mode.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne lisible de cet [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).

**Returns:**
java.lang.String - Une chaîne qui représente ce [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).
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

