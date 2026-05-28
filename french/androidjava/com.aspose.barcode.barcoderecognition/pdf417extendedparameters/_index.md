---
title: Pdf417ExtendedParameters
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Stocke les informations de métadonnées MacroPdf417 du code‑barres reconnu
type: docs
weight: 40
url: /fr/androidjava/com.aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class Pdf417ExtendedParameters extends BaseExtendedParameters
```

Stocke les informations de métadonnées MacroPdf417 du code‑barres reconnu

--------------------

> ```
> This sample shows how to get Macro Pdf417 metadata
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MACRO_PDF_417);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
>      System.out.println("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
>      System.out.println("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
>  }
> ```
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée de Pdf417ExtendedParameters. |
| [getClass()](#getClass--) |  |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Nom du destinataire Macro PDF417 (facultatif). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Somme de contrôle Macro PDF417 (facultatif). |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Obtient l'ID du fichier du code-barres, disponible uniquement avec MacroPdf417. |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Nom de fichier Macro PDF417 (facultatif). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Taille du fichier Macro PDF417 (facultatif). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Obtient l'ID du segment du code-barres, disponible uniquement avec MacroPdf417. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Obtient le nombre de segments du code-barres macro pdf417. |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Nom de l'expéditeur Macro PDF417 (facultatif). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Indique si le segment est le dernier segment d'un fichier Macro PDF417. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Horodatage Macro PDF417 (facultatif). |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette instance. |
| [isCode128Emulation()](#isCode128Emulation--) | Indicateur qui indique que le code-barres MicroPdf417 est encodé avec les mots de code d'émulation Code 128 908, 909, 910 ou 911. |
| [isEmpty()](#isEmpty--) | Teste si tous les paramètres n'ont que des valeurs par défaut |
| [isLinked()](#isLinked--) | Indicateur qui indique que le code-barres doit être lié à un code-barres 1D. |
| [isReaderInitialization()](#isReaderInitialization--) | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce Pdf417ExtendedParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée de Pdf417ExtendedParameters.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Une valeur System.Object à comparer à cette instance. |

**Returns:**
boolean -  **true**  si obj a la même valeur que cette instance ; sinon,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public String getMacroPdf417Addressee()
```


Nom du destinataire Macro PDF417 (facultatif).

**Returns:**
java.lang.String - Nom du destinataire.
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public int getMacroPdf417Checksum()
```


Somme de contrôle Macro PDF417 (facultatif).

**Returns:**
int - Somme de contrôle.
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public String getMacroPdf417FileID()
```


Obtient l'ID du fichier du code-barres, disponible uniquement avec MacroPdf417.

Valeur : L'ID du fichier pour MacroPdf417

**Returns:**
java.lang.String
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public String getMacroPdf417FileName()
```


Nom de fichier Macro PDF417 (facultatif).

**Returns:**
java.lang.String - Nom de fichier.
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public int getMacroPdf417FileSize()
```


Taille du fichier Macro PDF417 (facultatif).

**Returns:**
int - Taille du fichier.
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public int getMacroPdf417SegmentID()
```


Obtient l'ID du segment du code-barres, disponible uniquement avec MacroPdf417.

Valeur : L'ID du segment du code-barres.

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public int getMacroPdf417SegmentsCount()
```


Obtient le nombre de segments du code-barres macro pdf417. La valeur par défaut est -1.

Valeur : Nombre de segments.

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public String getMacroPdf417Sender()
```


Nom de l'expéditeur Macro PDF417 (facultatif).

**Returns:**
java.lang.String - Nom de l'expéditeur
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public boolean getMacroPdf417Terminator()
```


Indique si le segment est le dernier segment d'un fichier Macro PDF417.

**Returns:**
boolean - Terminateur.
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public LocalDateTime getMacroPdf417TimeStamp()
```


Horodatage Macro PDF417 (facultatif).

**Returns:**
java.time.LocalDateTime - Time stamp.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie le code de hachage pour cette instance.

**Returns:**
int - Un code de hachage entier signé de 32 bits.
### isCode128Emulation() {#isCode128Emulation--}
```
public boolean isCode128Emulation()
```


Indicateur qui indique que le code-barres MicroPdf417 est encodé avec les mots de code d'émulation Code 128 908, 909, 910 ou 911.

**Returns:**
boolean - Code 128 emulation flag
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Teste si tous les paramètres n'ont que des valeurs par défaut

Valeur : Renvoie  **true**  si tous les paramètres n'ont que des valeurs par défaut ; sinon,  **false** .

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public boolean isLinked()
```


Indicateur qui indique que le code-barres doit être lié à un code-barres 1D.

Value: Linkage flag

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur.

Value: Reader initialization flag

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




### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne lisible par l'homme de ce Pdf417ExtendedParameters.

**Returns:**
java.lang.String - A string that represents this  Pdf417ExtendedParameters .
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

