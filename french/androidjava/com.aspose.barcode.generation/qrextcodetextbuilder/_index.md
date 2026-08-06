---
title: QrExtCodetextBuilder
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Générateur de texte codé étendu pour les codes-barres QR 2D en mode ExtendedCodetext du QrEncodeMode. Utilisez la propriété TwoDDisplayText de BarcodeGenerator pour définir le texte visible en supprimant les caractères de gestion.
type: docs
weight: 63
url: /fr/androidjava/com.aspose.barcode.generation/qrextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class QrExtCodetextBuilder extends ExtCodetextBuilder
```

Extended codetext generator for 2D QR barcodes for ExtendedCodetext Mode of QrEncodeMode Use TwoDDisplayText property of BarcodeGenerator to set visible text to removing managing characters. This sample shows how to use FNC1 first position in Extended Mode: QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder(); lTextBuilder.addFNC1FirstPosition(); lTextBuilder.addPlainCodetext("000%89%%0"); lTextBuilder.addFNC1GroupSeparator(); lTextBuilder.addPlainCodetext("12345<FNC1>"); //generate codetext String lCodetext = lTextBuilder.getExtendedCodetext(); //generate BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.ExtendedCodetext); generator.getParameters().getBarcode().getQR().setQrErrorLevel(QRErrorLevel.LevelL); generator.setCodeText(lCodetext); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("test.bmp"); This sample shows how to use FNC1 second position in Extended Mode. //create codetext QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder(); TextBuilder.addFNC1SecondPosition("12"); TextBuilder.addPlainCodetext("TRUE3456"); //generate codetext String lCodetext = lTextBuilder.getExtendedCodetext(); //generate BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR); generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.ExtendedCodetext); generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LevelL); generator.setCodeText(lCodetext); generatorgenerator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("test.bmp"); This sample shows how to use multi ECI mode in Extended Mode. //create codetext QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder(); TextBuilder.addECICodetext(ECIEncodings.Win1251, "Will"); TextBuilder.addECICodetext(ECIEncodings.UTF8, "Right"); TextBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power"); TextBuilder.addPlainCodetext(@"t\\e\\\\st"); //generate codetext String lCodetext = lTextBuilder.getExtendedCodetext(); //generate BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR); generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.ExtendedCodetext); generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LevelL); generator.setCodeText(lCodetext); generatorgenerator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("test.bmp");
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [QrExtCodetextBuilder()](#QrExtCodetextBuilder--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Ajoute du codetext avec un identifiant de canal étendu. |
| [addFNC1FirstPosition()](#addFNC1FirstPosition--) | Adds FNC1 in first position to the extended codetext items |
| [addFNC1GroupSeparator()](#addFNC1GroupSeparator--) | Adds Group Separator (GS - '\\\\u001D') to the extended codetext items |
| [addFNC1SecondPosition(String codetext)](#addFNC1SecondPosition-java.lang.String-) | Adds FNC1 in second position to the extended codetext items |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Ajoute du texte de code simple aux éléments de texte de code étendu |
| [clear()](#clear--) | Efface les éléments de texte de code étendu |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Génère du texte de code étendu à partir de la liste de texte de code étendu. |
| [hashCode()](#hashCode--) |  |
| [isNeedToShieldItemFromPrevECI(int Index)](#isNeedToShieldItemFromPrevECI-int-) | Vérifie la nécessité de protéger l'élément précédent par "\\000000" |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### QrExtCodetextBuilder() {#QrExtCodetextBuilder--}
```
public QrExtCodetextBuilder()
```


### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public void addECICodetext(int ECIEncoding, String codetext)
```


Ajoute du codetext avec un identifiant de canal étendu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ECIEncoding | int | Identifiant de canal étendu |
| texte de code | java.lang.String | Texte de code en Unicode à ajouter en tant qu'élément de texte de code étendu avec l'identifiant de canal étendu |

### addFNC1FirstPosition() {#addFNC1FirstPosition--}
```
public void addFNC1FirstPosition()
```


Adds FNC1 in first position to the extended codetext items

### addFNC1GroupSeparator() {#addFNC1GroupSeparator--}
```
public void addFNC1GroupSeparator()
```


Adds Group Separator (GS - '\\\\u001D') to the extended codetext items

### addFNC1SecondPosition(String codetext) {#addFNC1SecondPosition-java.lang.String-}
```
public void addFNC1SecondPosition(String codetext)
```


Adds FNC1 in second position to the extended codetext items

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte de code | java.lang.String | Valeur du FNC1 dans la deuxième position |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public void addPlainCodetext(String codetext)
```


Ajoute du texte de code simple aux éléments de texte de code étendu

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte de code | java.lang.String | Texte de code en Unicode à ajouter en tant qu'élément de texte de code étendu |

### clear() {#clear--}
```
public void clear()
```


Efface les éléments de texte de code étendu

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
### getExtendedCodetext() {#getExtendedCodetext--}
```
public String getExtendedCodetext()
```


Génère du texte de code étendu à partir de la liste de texte de code étendu.

**Returns:**
java.lang.String - Texte de code étendu en tant que chaîne
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isNeedToShieldItemFromPrevECI(int Index) {#isNeedToShieldItemFromPrevECI-int-}
```
public boolean isNeedToShieldItemFromPrevECI(int Index)
```


Vérifie la nécessité de protéger l'élément précédent par "\\000000"

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| Indice | int | Indice dans m\_List |

**Returns:**
booléen - Nécessité de protéger
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




**Returns:**
java.lang.String
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

