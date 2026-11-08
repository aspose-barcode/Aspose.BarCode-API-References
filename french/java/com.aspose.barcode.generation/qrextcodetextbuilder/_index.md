---
title: "QrExtCodetextBuilder"
second_title: "Référence API d'Aspose.BarCode pour Java"
description: 
type: docs
weight: 61
url: /fr/java/com.aspose.barcode.generation/qrextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class QrExtCodetextBuilder extends ExtCodetextBuilder
```

Générateur de texte de code étendu pour les codes QR 2D pour le mode ExtendedCodetext d'EncodeMode

Utilisez la propriété TwoDDisplayText de BarcodeGenerator pour définir le texte visible en supprimant les caractères de gestion.

Cet exemple montre comment utiliser la première position FNC1 en mode étendu.

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1FirstPosition();
 textBuilder.addPlainCodetext("000%89%%0");
 textBuilder.addFNC1GroupSeparator();
 textBuilder.addPlainCodetext("12345<FNC1>");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```

Cet exemple montre comment utiliser la deuxième position FNC1 en mode étendu.

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1SecondPosition("12");
 textBuilder.addPlainCodetext("TRUE3456");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```

Cet exemple montre comment utiliser le mode multi ECI en mode étendu.

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.WIN_1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF_8, "Right");
 textBuilder.addECICodetext(ECIEncodings.UTF_16_BE, "Power");
 textBuilder.addPlainCodetext("t\\e\\\\st");
 textBuilder.addCodetextWithCompactionMode(QrExtCompactionMode.ALPHA_NUMERIC, "ASPOSE2001");
 textBuilder.addCodetextWithCompactionMode(QrExtCompactionMode.NUMERIC, "20012026");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [QrExtCodetextBuilder()](#QrExtCodetextBuilder--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext)](#addCodetextWithCompactionMode-com.aspose.barcode.generation.QrExtCompactionMode-java.lang.String-) | Ajoute du texte de code avec le mode de compaction QR spécifié aux éléments de texte de code étendu. |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Ajoute du codetext avec l’identifiant de canal étendu |
| [addFNC1FirstPosition()](#addFNC1FirstPosition--) | Définit FNC1 en première position. |
| [addFNC1GroupSeparator()](#addFNC1GroupSeparator--) | Ajoute le séparateur de groupe (GS - '\\\\u001D') aux éléments de texte de code étendu |
| [addFNC1SecondPosition(String codetext)](#addFNC1SecondPosition-java.lang.String-) | Définit FNC1 en deuxième position. |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Ajoute du codetext simple aux éléments de codetext étendu |
| [clear()](#clear--) | Efface les éléments de codetext étendu |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Génère le codetext étendu à partir de la liste de codetext étendu. |
| [hashCode()](#hashCode--) |  |
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


### addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext) {#addCodetextWithCompactionMode-com.aspose.barcode.generation.QrExtCompactionMode-java.lang.String-}
```
public final void addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext)
```


Ajoute du texte de code avec le mode de compaction QR spécifié aux éléments de texte de code étendu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mode | [QrExtCompactionMode](../../com.aspose.barcode.generation/qrextcompactionmode) | Mode de compaction QR pour le texte de code. |
| codetext | java.lang.String | Texte de code en Unicode à ajouter en tant qu'élément de texte de code étendu. |

### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public final void addECICodetext(int ECIEncoding, String codetext)
```


Ajoute du codetext avec l’identifiant de canal étendu

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ECIEncoding | int | Identifiant de canal étendu |
| codetext | java.lang.String | Codetext en Unicode à ajouter comme élément de codetext étendu avec l’identifiant de canal étendu |

### addFNC1FirstPosition() {#addFNC1FirstPosition--}
```
public final void addFNC1FirstPosition()
```


Définit FNC1 en première position. Si un autre mode FNC1 était déjà défini, il est remplacé.

### addFNC1GroupSeparator() {#addFNC1GroupSeparator--}
```
public final void addFNC1GroupSeparator()
```


Ajoute le séparateur de groupe (GS - '\\\\u001D') aux éléments de texte de code étendu

### addFNC1SecondPosition(String codetext) {#addFNC1SecondPosition-java.lang.String-}
```
public final void addFNC1SecondPosition(String codetext)
```


Définit FNC1 en deuxième position. Si un autre mode FNC1 était déjà défini, il est remplacé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| codetext | java.lang.String | Valeur du FNC1 en deuxième position. La valeur doit être une seule lettre de a-z ou A-Z, ou un nombre à deux chiffres de 00 à 99. |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Ajoute du codetext simple aux éléments de codetext étendu

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| codetext | java.lang.String | Codetext en unicode à ajouter en tant qu'élément de texte de code étendu |

### clear() {#clear--}
```
public void clear()
```


Efface les éléments de codetext étendu

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


Génère le codetext étendu à partir de la liste de codetext étendu.

**Returns:**
java.lang.String - Texte de code étendu sous forme de chaîne
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

