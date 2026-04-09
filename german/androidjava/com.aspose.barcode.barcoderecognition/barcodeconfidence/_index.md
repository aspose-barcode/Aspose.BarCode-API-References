---
title: BarCodeConfidence
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Enthält das Erkennungsvertrauensniveau
type: docs
weight: 13
url: /de/androidjava/com.aspose.barcode.barcoderecognition/barcodeconfidence/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeConfidence
```

Enthält das Erkennungsvertrauensniveau

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
## Felder

| Feld | Beschreibung |
| --- | --- |
| [MODERATE](#MODERATE) | Erkennungszuverlässigkeit des Barcodes (meist 1D-Barcodes) mit schwacher Prüfsumme oder sogar ohne sie. |
| [NONE](#NONE) | Erkennungszuverlässigkeit des Barcodes, bei dem der Codetext nicht korrekt erkannt wurde oder der Barcode als möglicher fakeBarCodeExtendedParameters erkannt wurde. |
| [STRONG](#STRONG) | Erkennungszuverlässigkeit, die mit BCH-Codes wie Reed\\u2013Solomon bestätigt wurde. |
## Methods

| Method | Beschreibung |
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


Erkennungszuverlässigkeit des Barcodes (meist 1D-Barcodes) mit schwacher Prüfsumme oder sogar ohne sie. Kann bei niedrigem Wert einige Fehlinterpretationen im Codetext oder sogar falsche Erkennungen enthalten.

### NONE {#NONE}
```
public static final int NONE
```


Erkennungszuverlässigkeit des Barcodes, bei dem der Codetext nicht korrekt erkannt wurde oder der Barcode als möglicher fakeBarCodeExtendedParameters erkannt wurde.

### STRONG {#STRONG}
```
public static final int STRONG
```


Erkennungszuverlässigkeit, die mit BCH-Codes wie Reed\\u2013Solomon bestätigt wurde. Es dürfen keine Fehler im gelesenen Codetext oder falsche Erkennungen auftreten.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschreibung |
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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

