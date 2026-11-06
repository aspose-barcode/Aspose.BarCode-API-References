---
title: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: 
type: docs
weight: 61
url: /de/androidjava/com.aspose.barcode.generation/qrextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class QrExtCodetextBuilder extends ExtCodetextBuilder
```

Erweiterter Codetext-Generator für 2D‑QR‑Barcodes für den ExtendedCodetext‑Modus von EncodeMode

Verwenden Sie die TwoDDisplayText‑Eigenschaft von BarcodeGenerator, um den sichtbaren Text festzulegen und verwaltende Zeichen zu entfernen.

Dieses Beispiel zeigt, wie die erste Position von FNC1 im Extended‑Modus verwendet wird.

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

Dieses Beispiel zeigt, wie die zweite Position von FNC1 im Extended‑Modus verwendet wird.

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

Dieses Beispiel zeigt, wie der Multi‑ECI‑Modus im Extended‑Modus verwendet wird.

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
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [QrExtCodetextBuilder()](#QrExtCodetextBuilder--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext)](#addCodetextWithCompactionMode-com.aspose.barcode.generation.QrExtCompactionMode-java.lang.String-) | Fügt den codetext mit dem angegebenen QR-Komprimierungsmodus zu den erweiterten codetext-Elementen hinzu. |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Fügt Codetext mit Extended Channel Identifier hinzu |
| [addFNC1FirstPosition()](#addFNC1FirstPosition--) | Setzt FNC1 an die erste Position. |
| [addFNC1GroupSeparator()](#addFNC1GroupSeparator--) | Fügt den Gruppentrenner (GS - '\\\\u001D') zu den erweiterten codetext-Elementen hinzu. |
| [addFNC1SecondPosition(String codetext)](#addFNC1SecondPosition-java.lang.String-) | Setzt FNC1 an die zweite Position. |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Fügt einfachen Codetext zu den erweiterten Codetext-Elementen hinzu |
| [clear()](#clear--) | Löscht erweiterte Codetext-Elemente |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Erzeugt erweiterten Codetext aus der erweiterten Codetext-Liste. |
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


Fügt den codetext mit dem angegebenen QR-Komprimierungsmodus zu den erweiterten codetext-Elementen hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mode | [QrExtCompactionMode](../../com.aspose.barcode.generation/qrextcompactionmode) | QR-Komprimierungsmodus für den codetext. |
| Codetext | java.lang.String | Codetext in Unicode, der als erweitertes codetext-Element hinzugefügt werden soll. |

### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public final void addECICodetext(int ECIEncoding, String codetext)
```


Fügt Codetext mit Extended Channel Identifier hinzu

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ECIEncoding | int | Erweiterter Kanalbezeichner |
| Codetext | java.lang.String | Codetext in Unicode, der als erweitertes Codetext-Element mit Extended Channel Identifier hinzugefügt wird |

### addFNC1FirstPosition() {#addFNC1FirstPosition--}
```
public final void addFNC1FirstPosition()
```


Setzt FNC1 an die erste Position. Wenn zuvor ein anderer FNC1‑Modus gesetzt wurde, wird er ersetzt.

### addFNC1GroupSeparator() {#addFNC1GroupSeparator--}
```
public final void addFNC1GroupSeparator()
```


Fügt den Gruppentrenner (GS - '\\\\u001D') zu den erweiterten codetext-Elementen hinzu.

### addFNC1SecondPosition(String codetext) {#addFNC1SecondPosition-java.lang.String-}
```
public final void addFNC1SecondPosition(String codetext)
```


Setzt FNC1 an die zweite Position. Wenn zuvor ein anderer FNC1‑Modus gesetzt wurde, wird er ersetzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Codetext | java.lang.String | Wert des FNC1 an der zweiten Position. Der Wert muss ein einzelner Buchstabe von a‑z oder A‑Z sein oder eine zweistellige Zahl von 00 bis 99. |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Fügt einfachen Codetext zu den erweiterten Codetext-Elementen hinzu

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Codetext | java.lang.String | Codetext in Unicode, der als erweitertes Codetext-Element hinzugefügt wird |

### clear() {#clear--}
```
public void clear()
```


Löscht erweiterte Codetext-Elemente

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


Erzeugt erweiterten Codetext aus der erweiterten Codetext-Liste.

**Returns:**
java.lang.String – erweiterter Codetext als Zeichenkette
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
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

