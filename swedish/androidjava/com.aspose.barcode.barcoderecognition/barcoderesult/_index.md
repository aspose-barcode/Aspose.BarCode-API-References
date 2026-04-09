---
title: BarCodeResult
second_title: Aspose.BarCode for Android via Java API-referens
description: Lagrar igenkända streckkoddata som SingleDecodeType typ string kodtext BarCodeRegionParameters region och andra parametrar.
type: docs
weight: 18
url: /sv/androidjava/com.aspose.barcode.barcoderecognition/barcoderesult/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeResult
```

Lagrar data för igenkänd streckkod såsom typ SingleDecodeType, sträng codetext, BarCodeRegionParameters region och andra parametrar

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

| Constructor | Beskrivning |
| --- | --- |
| [BarCodeResult(BarCodeResult result)](#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-) | Skapar en kopia av klassen BarCodeResult. |
## Methods

| Method | Beskrivning |
| --- | --- |
| [deepClone()](#deepClone--) | Skapar en kopia av klassen BarCodeResult. |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat BarCodeResult-värde. |
| [getClass()](#getClass--) |  |
| [getCodeBytes()](#getCodeBytes--) | Hämtar de kodade byte-värdena. |
| [getCodeText()](#getCodeText--) | Hämtar kodtexten. |
| [getCodeText(Charset encoding)](#getCodeText-java.nio.charset.Charset-) | Hämtar kodtexten med kodning. |
| [getCodeType()](#getCodeType--) | Hämtar streckkodstypen. |
| [getCodeTypeName()](#getCodeTypeName--) | Hämtar namnet på streckkodstypen. |
| [getConfidence()](#getConfidence--) | Hämtar igenkänningskonfidensnivån för den igenkända streckkoden. |
| [getExtended()](#getExtended--) | Hämtar utökade parametrar för den igenkända streckkoden. |
| [getReadingQuality()](#getReadingQuality--) | Hämtar läskvaliteten. |
| [getRegion()](#getRegion--) | Hämtar streckkodsområdet. |
| [hashCode()](#hashCode--) | Returnerar hash‑koden för detta objekt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta BarCodeResult. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeResult(BarCodeResult result) {#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-}
```
public BarCodeResult(BarCodeResult result)
```


Skapar en kopia av klassen BarCodeResult.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| result | [BarCodeResult](../../com.aspose.barcode.barcoderecognition/barcoderesult) | En kopia av BarCodeResult-instansen. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Skapar en kopia av klassen BarCodeResult.

**Returns:**
java.lang.Object - Returnerar en kopia av BarCodeResult-klassen.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat BarCodeResult-värde.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Ett BarCodeResult-värde att jämföra med detta objekt. |

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


Hämtar de kodade byte-värdena.

Värde: Kodbytena för streckkoden.

**Returns:**
byte[]
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


Hämtar kodtexten.

Värde: Kodtexten för streckkoden

**Returns:**
java.lang.String
### getCodeText(Charset encoding) {#getCodeText-java.nio.charset.Charset-}
```
public String getCodeText(Charset encoding)
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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| kodning | java.nio.charset.Charset | Kodningen för kodtexten. |

**Returns:**
java.lang.String - En sträng som innehåller igenkänd kodtext.
### getCodeType() {#getCodeType--}
```
public SingleDecodeType getCodeType()
```


Hämtar streckkodstypen.

Värde: Typinformationen för den igenkända streckkoden

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getCodeTypeName() {#getCodeTypeName--}
```
public String getCodeTypeName()
```


Hämtar namnet på streckkodstypen.

Värde: Typnamnet för den igenkända streckkoden

**Returns:**
java.lang.String
### getConfidence() {#getConfidence--}
```
public int getConfidence()
```


Hämtar igenkänningskonfidensnivån för den igenkända streckkoden.

Värde:  BarCodeConfidence.Strong  har inga falska eller felaktiga igenkänningar,  BarCodeConfidence.Moderate  kan ibland ha falska eller felaktiga kodtexter eftersom denna förtroendenivå för streckkoder med svag kontrollsumma eller utan den,  BarCodeConfidence.None  har alltid felaktig kodtext och kan vara falska igenkänningar

**Returns:**
int
### getExtended() {#getExtended--}
```
public BarCodeExtendedParameters getExtended()
```


Hämtar utökade parametrar för den igenkända streckkoden.

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


Hämtar streckkodsområdet.

Värde: Regionen för den igenkända streckkoden

**Returns:**
[BarCodeRegionParameters](../../com.aspose.barcode.barcoderecognition/barcoderegionparameters)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hash‑koden för detta objekt.

**Returns:**
int - En 32‑bitars signerad heltals‑hashkod.
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


Returnerar en människoläsbar strängrepresentation av detta BarCodeResult.

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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

