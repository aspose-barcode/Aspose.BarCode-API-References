---
title: "DotCodeExtCodetextBuilder"
second_title: "Référence API d'Aspose.BarCode pour Java"
description: 
type: docs
weight: 33
url: /fr/java/com.aspose.barcode.generation/dotcodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DotCodeExtCodetextBuilder extends ExtCodetextBuilder
```

Générateur de texte de code étendu pour les codes-barres 2D DotCode en mode ExtendedCodetext de DotCodeEncodeMode.

--------------------

> ```
> //Extended codetext mode
>  //create codetext
>  DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
>  textBuilder.addPlainCodetext("Plain text");
>  textBuilder.addFNC3SymbolSeparator();
>  textBuilder.addFNC3ReaderInitialization();
>  textBuilder.addPlainCodetext("Reader initialization info");
>  //generate codetext
>  String codetext = textBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
>  generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DotCodeExtCodetextBuilder()](#DotCodeExtCodetextBuilder--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Ajoute du codetext avec l’identifiant de canal étendu |
| [addFNC1FormatIdentifier()](#addFNC1FormatIdentifier--) | Ajoute l\'identifiant de format FNC1 aux éléments de texte de code étendu. |
| [addFNC3ReaderInitialization()](#addFNC3ReaderInitialization--) | Ajoute l\'initialisation du lecteur FNC3 aux éléments de texte de code étendu. |
| [addFNC3SymbolSeparator()](#addFNC3SymbolSeparator--) | Ajoute le séparateur de symbole FNC3 aux éléments de texte de code étendu. |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Ajoute du codetext simple aux éléments de codetext étendu |
| [addStructuredAppendMode(int barcodeId, int barcodesCount)](#addStructuredAppendMode-int-int-) | Ajoute le mode d\'ajout structuré aux éléments de texte de code étendu. |
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
### DotCodeExtCodetextBuilder() {#DotCodeExtCodetextBuilder--}
```
public DotCodeExtCodetextBuilder()
```


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

### addFNC1FormatIdentifier() {#addFNC1FormatIdentifier--}
```
public final void addFNC1FormatIdentifier()
```


Ajoute l\'identifiant de format FNC1 aux éléments de texte de code étendu.

### addFNC3ReaderInitialization() {#addFNC3ReaderInitialization--}
```
public final void addFNC3ReaderInitialization()
```


Ajoute l\'initialisation du lecteur FNC3 aux éléments de texte de code étendu.

### addFNC3SymbolSeparator() {#addFNC3SymbolSeparator--}
```
public final void addFNC3SymbolSeparator()
```


Ajoute le séparateur de symbole FNC3 aux éléments de texte de code étendu.

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Ajoute du codetext simple aux éléments de codetext étendu

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| codetext | java.lang.String | Codetext en unicode à ajouter en tant qu'élément de texte de code étendu |

### addStructuredAppendMode(int barcodeId, int barcodesCount) {#addStructuredAppendMode-int-int-}
```
public final void addStructuredAppendMode(int barcodeId, int barcodesCount)
```


Ajoute le mode d\'ajout structuré aux éléments de texte de code étendu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| barcodeId | int | ID du code-barres |
| barcodesCount | int | Nombre de codes-barres |

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

