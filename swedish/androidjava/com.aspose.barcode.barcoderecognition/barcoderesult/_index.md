---
title: "BarCodeResult"
second_title: "Aspose.BarCode för Android via Java API-referens"
description: "Lagrar igenkända streckkoddata som SingleDecodeType-typ, sträng, kodtext, BarCodeRegionParameters-region och andra parametrar"
type: docs
weight: 17
url: /sv/androidjava/com.aspose.barcode.barcoderecognition/barcoderesult/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeResult
```

Lagrar igenkända streckkodsdata såsom  SingleDecodeType  typ,  string  kodtext,  BarCodeRegionParameters  region och andra parametrar

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
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [BarCodeResult(BarCodeResult result)](#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-) | Skapar en kopia av  BarCodeResult  klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone()](#deepClone--) | Skapar en kopia av  BarCodeResult  klassen. |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat  BarCodeResult  värde. |
| [getClass()](#getClass--) |  |
| [getCodeBytes()](#getCodeBytes--) | Hämtar de kodade kodbytena |
| [getCodeText()](#getCodeText--) | Hämtar kodtexten |
| [getCodeText(Charset charset)](#getCodeText-java.nio.charset.Charset-) | Hämtar kodtexten med kodning. |
| [getCodeType()](#getCodeType--) | Hämtar streckkodstypen |
| [getCodeTypeName()](#getCodeTypeName--) | Hämtar namnet på streckkodstypen |
| [getConfidence()](#getConfidence--) | Hämtar igenkänningskonfidensnivån för den identifierade streckkoden |
| [getExtended()](#getExtended--) | Hämtar utökade parametrar för identifierad streckkod |
| [getReadingQuality()](#getReadingQuality--) | Hämtar läskvaliteten. |
| [getRegion()](#getRegion--) | Hämtar streckkodsområdet |
| [hashCode()](#hashCode--) | Returnerar hash‑koden för detta objekt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta  BarCodeResult . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeResult(BarCodeResult result) {#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-}
```
public BarCodeResult(BarCodeResult result)
```


Skapar en kopia av  BarCodeResult  klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| result | [BarCodeResult](../../com.aspose.barcode.barcoderecognition/barcoderesult) | En kopia av  BarCodeResult  instans. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Skapar en kopia av  BarCodeResult  klassen.

**Returns:**
java.lang.Object - Returnerar en kopia av  BarCodeResult  klassen.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat  BarCodeResult  värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Ett  BarCodeResult  värde att jämföra med detta objekt. |

**Returns:**
boolean -  **true**  om obj har samma värde som detta objekt; annars,  **false** .
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


Hämtar de kodade kodbytena

Värde: Kodbytena för streckkoden

**Returns:**
byte[]
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


Hämtar kodtexten

Värde: Kodtexten för streckkoden

**Returns:**
java.lang.String
### getCodeText(Charset charset) {#getCodeText-java.nio.charset.Charset-}
```
public String getCodeText(Charset charset)
```


Hämtar kodtexten med kodning.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| charset | java.nio.charset.Charset | Kodningen för kodtexten. |

**Returns:**
java.lang.String - En sträng som innehåller identifierad kodtext.
### getCodeType() {#getCodeType--}
```
public SingleDecodeType getCodeType()
```


Hämtar streckkodstypen

Värde: Typinformationen för den identifierade streckkoden

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getCodeTypeName() {#getCodeTypeName--}
```
public String getCodeTypeName()
```


Hämtar namnet på streckkodstypen

Värde: Typnamnet för den identifierade streckkoden

**Returns:**
java.lang.String
### getConfidence() {#getConfidence--}
```
public BarCodeConfidence getConfidence()
```


Hämtar igenkänningskonfidensnivån för den identifierade streckkoden

Värde:  BarCodeConfidence.Strong  har inga falska eller felaktiga igenkänningar,  BarCodeConfidence.Moderate  kan ibland ha falska eller felaktiga kodtexter eftersom denna förtroendenivå för streckkoder med svag kontrollsumma eller utan den,  BarCodeConfidence.None  har alltid felaktig kodtext och kan vara falska igenkänningar

**Returns:**
[BarCodeConfidence](../../com.aspose.barcode.barcoderecognition/barcodeconfidence)
### getExtended() {#getExtended--}
```
public BarCodeExtendedParameters getExtended()
```


Hämtar utökade parametrar för identifierad streckkod

Värde: De utökade parametrarna för den igenkända streckkoden

**Returns:**
[BarCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/barcodeextendedparameters)
### getReadingQuality() {#getReadingQuality--}
```
public double getReadingQuality()
```


Hämtar läskvaliteten. Fungerar för 1D- och poststreckkoder.

Värde: Läsningskvalitetens procent

**Returns:**
double
### getRegion() {#getRegion--}
```
public BarCodeRegionParameters getRegion()
```


Hämtar streckkodsområdet

Värde: Regionen för den igenkända streckkoden

**Returns:**
[BarCodeRegionParameters](../../com.aspose.barcode.barcoderecognition/barcoderegionparameters)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hash‑koden för detta objekt.

**Returns:**
int - En 32‑bit signerad heltals‑hashkod.
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


Returnerar en människoläsbar strängrepresentation av detta  BarCodeResult .

**Returns:**
java.lang.String - En sträng som representerar detta  BarCodeResult .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

