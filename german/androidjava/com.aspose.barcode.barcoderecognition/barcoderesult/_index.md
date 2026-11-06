---
title: "BarCodeResult"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: "Speichert erkannte Barcode-Daten wie SingleDecodeType, Typ, Zeichenkette, Codetext, BarCodeRegionParameters, Region und weitere Parameter."
type: docs
weight: 17
url: /de/androidjava/com.aspose.barcode.barcoderecognition/barcoderesult/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeResult
```

Speichert erkannte Barcode-Daten wie den Typ SingleDecodeType, den String codetext, die BarCodeRegionParameters-Region und weitere Parameter

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
| [getCodeBytes()](#getCodeBytes--) | Ruft die codierten Code-Bytes ab |
| [getCodeText()](#getCodeText--) | Ruft den Code-Text ab |
| [getCodeText(Charset charset)](#getCodeText-java.nio.charset.Charset-) | Ruft den Code-Text mit Kodierung ab. |
| [getCodeType()](#getCodeType--) | Ruft den Barcode-Typ ab |
| [getCodeTypeName()](#getCodeTypeName--) | Ruft den Namen des Barcode-Typs ab |
| [getConfidence()](#getConfidence--) | Ruft das Erkennungs‑Vertrauensniveau des erkannten Barcodes ab |
| [getExtended()](#getExtended--) | Ruft erweiterte Parameter des erkannten Barcodes ab |
| [getReadingQuality()](#getReadingQuality--) | Ruft die Lesegüte ab. |
| [getRegion()](#getRegion--) | Ruft den Barcode‑Bereich ab |
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
| result | [BarCodeResult](../../com.aspose.barcode.barcoderecognition/barcoderesult) | Eine Kopie  BarCodeResult  Instanz. |

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
boolean -  **true**, wenn obj denselben Wert wie diese Instanz hat; andernfalls **false**.
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


Ruft die codierten Code-Bytes ab

Wert: Die Code-Bytes des Barcodes

**Returns:**
byte[]
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


Ruft den Code-Text ab

Wert: Der Code-Text des Barcodes

**Returns:**
java.lang.String
### getCodeText(Charset charset) {#getCodeText-java.nio.charset.Charset-}
```
public String getCodeText(Charset charset)
```


Ruft den Code-Text mit Kodierung ab.

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
| charset | java.nio.charset.Charset | Die Kodierung für den Code-Text. |

**Returns:**
java.lang.String - Eine Zeichenkette, die den erkannten Code-Text enthält.
### getCodeType() {#getCodeType--}
```
public SingleDecodeType getCodeType()
```


Ruft den Barcode-Typ ab

Wert: Die Typinformation des erkannten Barcodes

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getCodeTypeName() {#getCodeTypeName--}
```
public String getCodeTypeName()
```


Ruft den Namen des Barcode-Typs ab

Wert: Der Typname des erkannten Barcodes

**Returns:**
java.lang.String
### getConfidence() {#getConfidence--}
```
public BarCodeConfidence getConfidence()
```


Ruft das Erkennungs‑Vertrauensniveau des erkannten Barcodes ab

Wert:  BarCodeConfidence.Strong  hat keine Fälschungen oder Fehlinterpretationen,  BarCodeConfidence.Moderate  kann manchmal Fälschungen oder falschen Codetext haben, weil dieses Vertrauensniveau für Barcodes mit schwacher Prüfsumme oder sogar ohne sie gilt,  BarCodeConfidence.None  hat immer falschen Codetext und kann falsche Erkennungen sein

**Returns:**
[BarCodeConfidence](../../com.aspose.barcode.barcoderecognition/barcodeconfidence)
### getExtended() {#getExtended--}
```
public BarCodeExtendedParameters getExtended()
```


Ruft erweiterte Parameter des erkannten Barcodes ab

Wert: Die erweiterten Parameter des erkannten Barcodes

**Returns:**
[BarCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/barcodeextendedparameters)
### getReadingQuality() {#getReadingQuality--}
```
public double getReadingQuality()
```


Liefert die Lesegüte. Funktioniert für 1D- und Post-Barcodes.

Wert: Der Prozentsatz der Lesegüte

**Returns:**
double
### getRegion() {#getRegion--}
```
public BarCodeRegionParameters getRegion()
```


Ruft den Barcode‑Bereich ab

Wert: Der Bereich des erkannten Barcodes

**Returns:**
[BarCodeRegionParameters](../../com.aspose.barcode.barcoderecognition/barcoderegionparameters)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese Instanz zurück.

**Returns:**
int - Ein 32‑Bit vorzeichenbehafteter Integer‑Hashcode.
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
java.lang.String - Eine Zeichenkette, die dieses  BarCodeResult  darstellt.
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

