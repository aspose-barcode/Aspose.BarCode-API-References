---
title: BarCodeConfidence
second_title: Aspose.BarCode for Android via Java API-referentie
description: Bevat het herkenningsvertrouwensniveau
type: docs
weight: 13
url: /nl/androidjava/com.aspose.barcode.barcoderecognition/barcodeconfidence/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeConfidence
```

Bevat het herkenningsvertrouwensniveau

--------------------

> ```
> This sample shows how BarCodeConfidence changed, depending on barcode type
>  
>  //Moderate confidence
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_STANDARD, DecodeType.CODE_128);
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode Type: " + result.getCodeTypeName());
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>          System.out.println("BarCode Confidence: " + result.getConfidence());
>          System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      }
>  //Strong confidence
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_STANDARD, DecodeType.QR);
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode Type: " + result.getCodeTypeName());
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>          System.out.println("BarCode Confidence: " + result.getConfidence());
>          System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      }
> ```
## Velden

| Veld | Beschrijving |
| --- | --- |
| [MODERATE](#MODERATE) | Herkenningsvertrouwen van de barcode (voornamelijk 1D-barcodes) met een zwakke checksum of zelfs zonder. |
| [NONE](#NONE) | Herkenningsvertrouwen van de barcode waarbij de codetekst niet correct werd herkend of de barcode werd gedetecteerd als mogelijk nepBarCodeExtendedParameters |
| [STRONG](#STRONG) | Herkenningsvertrouwen dat werd bevestigd met BCH-codes zoals Reed\\u2013Solomon. |
## Methods

| Method | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MODERATE {#MODERATE}
```
public static final int MODERATE
```


Herkenningsvertrouwen van de barcode (voornamelijk 1D-barcodes) met een zwakke checksum of zelfs zonder. Kan enkele misherkenningen in de codetekst bevatten of zelfs nepherkenningen als het laag is.

### NONE {#NONE}
```
public static final int NONE
```


Herkenningsvertrouwen van de barcode waarbij de codetekst niet correct werd herkend of de barcode werd gedetecteerd als mogelijk nepBarCodeExtendedParameters

### STRONG {#STRONG}
```
public static final int STRONG
```


Herkenningsvertrouwen dat werd bevestigd met BCH-codes zoals Reed\\u2013Solomon. Er mogen geen fouten zijn in de gelezen codetekst of nepherkenningen.

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

