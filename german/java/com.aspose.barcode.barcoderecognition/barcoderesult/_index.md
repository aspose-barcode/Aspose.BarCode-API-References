---
title: "BarCodeResult"
second_title: "Aspose.BarCode für Java API-Referenz"
description: "Speichert erkannte Barcode-Daten wie SingleDecodeType Typ Zeichenkette codetext BarCodeRegionParameters Region und andere Parameter"
type: docs
weight: 17
url: /de/java/com.aspose.barcode.barcoderecognition/barcoderesult/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeResult
```

Speichert erkannte Barcode‑Daten wie den Typ SingleDecodeType, den String codetext, die BarCodeRegionParameters‑Region und weitere Parameter.

--------------------

> ```
> This sample shows how to obtain BarCodeResult.
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("BarCode Confidence: " + result.getConfidence());
>      System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>  }
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BarCodeResult(BarCodeResult result)](#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-) | Erstellt eine Kopie der  BarCodeResult  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone()](#deepClone--) | Erstellt eine Kopie der  BarCodeResult  Klasse. |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt einen Wert zurück, der angibt, ob diese Instanz gleich einem angegebenen  BarCodeResult  Wert ist. |
| [getClass()](#getClass--) |  |
| [getCodeBytes()](#getCodeBytes--) | Liefert die codierten Code-Bytes |
| [getCodeText()](#getCodeText--) | Liefert den Code-Text |
| [getCodeText(Charset charset)](#getCodeText-java.nio.charset.Charset-) | Liefert den Code-Text mit Kodierung. |
| [getCodeType()](#getCodeType--) | Liefert den Barcode-Typ |
| [getCodeTypeName()](#getCodeTypeName--) | Liefert den Namen des Barcode-Typs |
| [getConfidence()](#getConfidence--) | Liefert das Erkennungs‑Vertrauensniveau des erkannten Barcodes |
| [getExtended()](#getExtended--) | Liefert erweiterte Parameter des erkannten Barcodes |
| [getReadingQuality()](#getReadingQuality--) | Liefert die Lesungsqualität. |
| [getRegion()](#getRegion--) | Liefert den Barcode-Bereich |
| [hashCode()](#hashCode--) | Gibt den Hashcode für diese Instanz zurück. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses  BarCodeResult  zurück. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeResult(BarCodeResult result) {#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-}
```
public BarCodeResult(BarCodeResult result)
```


Erstellt eine Kopie der  BarCodeResult  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| result | [BarCodeResult](../../com.aspose.barcode.barcoderecognition/barcoderesult) | Eine Kopie einer  BarCodeResult  Instanz. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Erstellt eine Kopie der  BarCodeResult  Klasse.

**Returns:**
java.lang.Object - Gibt eine Kopie der  BarCodeResult  Klasse zurück.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Gibt einen Wert zurück, der angibt, ob diese Instanz gleich einem angegebenen  BarCodeResult  Wert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Ein  BarCodeResult  Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolesch -  **true**  wenn obj denselben Wert wie diese Instanz hat; andernfalls **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodeBytes() {#getCodeBytes--}
```
public byte[] getCodeBytes()
```


Liefert die codierten Code-Bytes

Wert: Die Code-Bytes des Barcodes

**Returns:**
byte[]
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


Liefert den Code-Text

Wert: Der Code-Text des Barcodes

**Returns:**
java.lang.String
### getCodeText(Charset charset) {#getCodeText-java.nio.charset.Charset-}
```
public String getCodeText(Charset charset)
```


Liefert den Code-Text mit Kodierung.

--------------------

> ```
> This example shows how to use ```
> GetCodeText
> ```:
>   
>   BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	gen.setCodeText("\u8eca\u7a2e\u540d", Charset.forName("932"));
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DATA_MATRIX);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText(Charset.forName("932")));
> ```

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| charset | java.nio.charset.Charset | Die Kodierung für codetext. |

**Returns:**
java.lang.String - Ein String, der erkannten Code-Text enthält.
### getCodeType() {#getCodeType--}
```
public SingleDecodeType getCodeType()
```


Liefert den Barcode-Typ

Wert: Die Typinformation des erkannten Barcodes

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getCodeTypeName() {#getCodeTypeName--}
```
public String getCodeTypeName()
```


Liefert den Namen des Barcode-Typs

Wert: Der Typname des erkannten Barcodes

**Returns:**
java.lang.String
### getConfidence() {#getConfidence--}
```
public BarCodeConfidence getConfidence()
```


Liefert das Erkennungs‑Vertrauensniveau des erkannten Barcodes

Wert:  BarCodeConfidence.Strong  hat keine Fälschungen oder Fehlinterpretationen,  BarCodeConfidence.Moderate  kann manchmal Fälschungen oder falschen Codetext aufweisen, weil dieses Vertrauensniveau bei Barcodes mit schwacher Prüfsumme oder sogar ohne sie gilt,  BarCodeConfidence.None  hat stets falschen Codetext und kann falsche Erkennungen sein

**Returns:**
[BarCodeConfidence](../../com.aspose.barcode.barcoderecognition/barcodeconfidence)
### getExtended() {#getExtended--}
```
public BarCodeExtendedParameters getExtended()
```


Liefert erweiterte Parameter des erkannten Barcodes

Wert: Die erweiterten Parameter des erkannten Barcodes

**Returns:**
[BarCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/barcodeextendedparameters)
### getReadingQuality() {#getReadingQuality--}
```
public double getReadingQuality()
```


Ermittelt die Lesegüte. Funktioniert für 1D- und Postbarcodes.

Wert: Der Prozentsatz der Lesegüte

**Returns:**
double
### getRegion() {#getRegion--}
```
public BarCodeRegionParameters getRegion()
```


Liefert den Barcode-Bereich

Wert: Die Region des erkannten Barcodes

**Returns:**
[BarCodeRegionParameters](../../com.aspose.barcode.barcoderecognition/barcoderegionparameters)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese Instanz zurück.

**Returns:**
int - Ein 32‑Bit vorzeichenbehafteter Ganzzahl-Hashcode.
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


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses  BarCodeResult  zurück.

**Returns:**
java.lang.String - Ein String, der dieses  BarCodeResult  darstellt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
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

