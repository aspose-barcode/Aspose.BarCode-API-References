---
title: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode for Java API-referentie"
description: 
type: docs
weight: 61
url: /nl/java/com.aspose.barcode.generation/qrextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class QrExtCodetextBuilder extends ExtCodetextBuilder
```

Uitgebreide codetekstgenerator voor 2D QR-barcodes voor ExtendedCodetext-modus van EncodeMode

Gebruik de TwoDDisplayText‑eigenschap van BarcodeGenerator om de zichtbare tekst in te stellen door beheer‑tekens te verwijderen.

Dit voorbeeld toont hoe FNC1 in de eerste positie te gebruiken in Extended Mode.

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

Dit voorbeeld toont hoe FNC1 in de tweede positie te gebruiken in Extended Mode.

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

Dit voorbeeld toont hoe de multi-ECI-modus te gebruiken in Extended Mode.

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
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [QrExtCodetextBuilder()](#QrExtCodetextBuilder--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext)](#addCodetextWithCompactionMode-com.aspose.barcode.generation.QrExtCompactionMode-java.lang.String-) | Voegt codetekst toe met de opgegeven QR-compressiemodus aan de uitgebreide codetekstitems. |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Voegt codetext toe met Extended Channel Identifier |
| [addFNC1FirstPosition()](#addFNC1FirstPosition--) | Stelt FNC1 in de eerste positie in. |
| [addFNC1GroupSeparator()](#addFNC1GroupSeparator--) | Voegt Group Separator (GS - '\\\\u001D') toe aan de uitgebreide codetekstitems |
| [addFNC1SecondPosition(String codetext)](#addFNC1SecondPosition-java.lang.String-) | Stelt FNC1 in de tweede positie in. |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Voegt platte codetext toe aan de uitgebreide codetext‑items |
| [clear()](#clear--) | Wis de uitgebreide codetext‑items |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Genereert Extended codetext uit de uitgebreide codetext‑lijst. |
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


Voegt codetekst toe met de opgegeven QR-compressiemodus aan de uitgebreide codetekstitems.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mode | [QrExtCompactionMode](../../com.aspose.barcode.generation/qrextcompactionmode) | QR-compressiemodus voor de codetekst. |
| codetext | java.lang.String | Codetekst in Unicode om toe te voegen als een uitgebreid codetekstitem. |

### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public final void addECICodetext(int ECIEncoding, String codetext)
```


Voegt codetext toe met Extended Channel Identifier

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ECIEncoding | int | Extended Channel Identifier |
| codetext | java.lang.String | Codetext in Unicode om toe te voegen als uitgebreid codetext‑item met Extended Channel Identifier |

### addFNC1FirstPosition() {#addFNC1FirstPosition--}
```
public final void addFNC1FirstPosition()
```


Stelt FNC1 in de eerste positie in. Als er eerder een andere FNC1-modus was ingesteld, wordt deze vervangen.

### addFNC1GroupSeparator() {#addFNC1GroupSeparator--}
```
public final void addFNC1GroupSeparator()
```


Voegt Group Separator (GS - '\\\\u001D') toe aan de uitgebreide codetekstitems

### addFNC1SecondPosition(String codetext) {#addFNC1SecondPosition-java.lang.String-}
```
public final void addFNC1SecondPosition(String codetext)
```


Stelt FNC1 in de tweede positie in. Als er eerder een andere FNC1-modus was ingesteld, wordt deze vervangen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| codetext | java.lang.String | Waarde van de FNC1 in de tweede positie. De waarde moet een enkele letter van a-z of A-Z zijn, of een tweecijferig getal van 00 tot 99. |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Voegt platte codetext toe aan de uitgebreide codetext‑items

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| codetext | java.lang.String | Codetext in Unicode om toe te voegen als uitgebreid codetext-item |

### clear() {#clear--}
```
public void clear()
```


Wis de uitgebreide codetext‑items

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Genereert Extended codetext uit de uitgebreide codetext‑lijst.

**Returns:**
java.lang.String - Uitgebreide codetext als string
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

