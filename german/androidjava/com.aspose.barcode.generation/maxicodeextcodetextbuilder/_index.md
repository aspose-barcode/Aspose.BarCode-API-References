---
title: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: "Erweiterter Codetext‑Generator für MaxiCode‑Barcodes für den ExtendedCodetext‑Modus von MaxiCodeEncodeMode. Verwenden Sie die TwoDDisplayText‑Eigenschaft von BarcodeGenerator, um den sichtbaren Text festzulegen und verwaltende Zeichen zu entfernen."
type: docs
weight: 54
url: /de/androidjava/com.aspose.barcode.generation/maxicodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class MaxiCodeExtCodetextBuilder extends ExtCodetextBuilder
```

Erweiterter Codetext-Generator für MaxiCode-Barcodes für den ExtendedCodetext‑Modus von MaxiCodeEncodeMode. Verwenden Sie die Eigenschaft TwoDDisplayText von BarcodeGenerator, um den sichtbaren Text festzulegen, indem verwaltende Zeichen entfernt werden. Dieses Beispiel zeigt, wie MaxiCodeExtCodetextBuilder im erweiterten Modus verwendet wird.

```
//create codetext
 MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
 textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
 textBuilder.addPlainCodetext("Plain text");

 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();

 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MaxiCodeExtCodetextBuilder()](#MaxiCodeExtCodetextBuilder--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Fügt Codetext mit Extended Channel Identifier hinzu |
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
### MaxiCodeExtCodetextBuilder() {#MaxiCodeExtCodetextBuilder--}
```
public MaxiCodeExtCodetextBuilder()
```


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

