---
title: BarCodeResult
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Speichert erkannte Barcode-Daten wie SingleDecodeType Typ, string codetext, BarCodeRegionParameters region und andere Parameter
type: docs
weight: 18
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
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("BarCode Confidence: " + result.getConfidence());
>      System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>  }
> ```
## Constructors

| Constructor | Beschreibung |
| --- | --- |
| [BarCodeResult(BarCodeResult result)](#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-) | Erstellt eine Kopie der Klasse BarCodeResult. |
## Methods

| Method | Beschreibung |
| --- | --- |
| [deepClone()](#deepClone--) | Erstellt eine Kopie der Klasse BarCodeResult. |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen BarCodeResult-Wert entspricht. |
| [getClass()](#getClass--) |  |
| [getCodeBytes()](#getCodeBytes--) | Ermittelt die codierten Code-Bytes. |
| [getCodeText()](#getCodeText--) | Ermittelt den Code-Text. |
| [getCodeText(Charset encoding)](#getCodeText-java.nio.charset.Charset-) | Ermittelt den Code-Text mit Kodierung. |
| [getCodeType()](#getCodeType--) | Ermittelt den Barcode-Typ. |
| [getCodeTypeName()](#getCodeTypeName--) | Ermittelt den Namen des Barcode-Typs. |
| [getConfidence()](#getConfidence--) | Ermittelt das Erkennungs‑Vertrauensniveau des erkannten Barcodes. |
| [getExtended()](#getExtended--) | Ermittelt erweiterte Parameter des erkannten Barcodes. |
| [getReadingQuality()](#getReadingQuality--) | Ermittelt die Lesegüte. |
| [getRegion()](#getRegion--) | Ermittelt den Barcode-Bereich. |
| [hashCode()](#hashCode--) | Gibt den Hashcode für diese Instanz zurück. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses BarCodeResult zurück. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeResult(BarCodeResult result) {#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-}
```
public BarCodeResult(BarCodeResult result)
```


Erstellt eine Kopie der Klasse BarCodeResult.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| result | [BarCodeResult](../../com.aspose.barcode.barcoderecognition/barcoderesult) | Eine Kopie einer BarCodeResult-Instanz. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Erstellt eine Kopie der Klasse BarCodeResult.

**Returns:**
java.lang.Object – Gibt eine Kopie der Klasse BarCodeResult zurück.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen BarCodeResult-Wert entspricht.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Ein BarCodeResult-Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolean -  **true**  wenn obj denselben Wert wie diese Instanz hat; andernfalls **false**.
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


Ermittelt die codierten Code-Bytes.

Wert: Die Code-Bytes des Barcodes

**Returns:**
byte[]
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


Ermittelt den Code-Text.

Wert: Der Code-Text des Barcodes

**Returns:**
java.lang.String
### getCodeText(Charset encoding) {#getCodeText-java.nio.charset.Charset-}
```
public String getCodeText(Charset encoding)
```


Ermittelt den Code-Text mit Kodierung.

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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Kodierung | java.nio.charset.Charset | Die Kodierung für den Code-Text. |

**Returns:**
java.lang.String - Ein String, der den erkannten Code-Text enthält.
### getCodeType() {#getCodeType--}
```
public SingleDecodeType getCodeType()
```


Ermittelt den Barcode-Typ.

Wert: Die Typinformationen des erkannten Barcodes

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getCodeTypeName() {#getCodeTypeName--}
```
public String getCodeTypeName()
```


Ermittelt den Namen des Barcode-Typs.

Wert: Der Typname des erkannten Barcodes

**Returns:**
java.lang.String
### getConfidence() {#getConfidence--}
```
public int getConfidence()
```


Ermittelt das Erkennungs‑Vertrauensniveau des erkannten Barcodes.

Wert:  BarCodeConfidence.Strong  hat keine Fälschungen oder Fehlinterpretationen,  BarCodeConfidence.Moderate  kann manchmal Fälschungen oder falschen Code-Text enthalten, weil dieses Vertrauensniveau für Barcodes mit schwacher Prüfsumme oder sogar ohne sie gilt,  BarCodeConfidence.None  hat immer falschen Code-Text und kann falsche Erkennungen sein

**Returns:**
int
### getExtended() {#getExtended--}
```
public BarCodeExtendedParameters getExtended()
```


Ermittelt erweiterte Parameter des erkannten Barcodes.

Wert: Die erweiterten Parameter des erkannten Barcodes

**Returns:**
[BarCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/barcodeextendedparameters)
### getReadingQuality() {#getReadingQuality--}
```
public double getReadingQuality()
```


Ermittelt die Lesegüte. Funktioniert für 1D- und Post-Barcodes.

Wert: Der Prozentsatz der Lesegüte

**Returns:**
double
### getRegion() {#getRegion--}
```
public BarCodeRegionParameters getRegion()
```


Ermittelt den Barcode-Bereich.

Wert: Der Bereich des erkannten Barcodes

**Returns:**
[BarCodeRegionParameters](../../com.aspose.barcode.barcoderecognition/barcoderegionparameters)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese Instanz zurück.

**Returns:**
int - Ein 32-Bit vorzeichenbehafteter Ganzzahl-Hashcode.
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


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses BarCodeResult zurück.

**Returns:**
java.lang.String - Ein String, der dieses  BarCodeResult  darstellt.
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

