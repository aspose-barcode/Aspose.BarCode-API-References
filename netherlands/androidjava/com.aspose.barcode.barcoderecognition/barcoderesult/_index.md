---
title: BarCodeResult
second_title: Aspose.BarCode for Android via Java API-referentie
description: Slaat herkende barcodegegevens op, zoals SingleDecodeType type string codetext BarCodeRegionParameters region en andere parameters
type: docs
weight: 18
url: /nl/androidjava/com.aspose.barcode.barcoderecognition/barcoderesult/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeResult
```

Slaat herkende barcode-gegevens op zoals type SingleDecodeType, string codetext, BarCodeRegionParameters regio en andere parameters

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

| Constructor | Beschrijving |
| --- | --- |
| [BarCodeResult(BarCodeResult result)](#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-) | Maakt een kopie van de BarCodeResult-klasse. |
## Methods

| Method | Beschrijving |
| --- | --- |
| [deepClone()](#deepClone--) | Maakt een kopie van de BarCodeResult-klasse. |
| [equals(Object obj)](#equals-java.lang.Object-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven BarCodeResult-waarde. |
| [getClass()](#getClass--) |  |
| [getCodeBytes()](#getCodeBytes--) | Haalt de gecodeerde codebytes op |
| [getCodeText()](#getCodeText--) | Haalt de code-tekst op |
| [getCodeText(Charset encoding)](#getCodeText-java.nio.charset.Charset-) | Haalt de code-tekst op met codering. |
| [getCodeType()](#getCodeType--) | Haalt het barcode-type op |
| [getCodeTypeName()](#getCodeTypeName--) | Haalt de naam van het barcode-type op |
| [getConfidence()](#getConfidence--) | Haalt het vertrouwensniveau van de herkenning van de herkende barcode op |
| [getExtended()](#getExtended--) | Haalt uitgebreide parameters van de herkende barcode op |
| [getReadingQuality()](#getReadingQuality--) | Haalt de leeskwaliteit op. |
| [getRegion()](#getRegion--) | Haalt de barcode-regio op |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze instantie. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze BarCodeResult. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeResult(BarCodeResult result) {#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-}
```
public BarCodeResult(BarCodeResult result)
```


Maakt een kopie van de BarCodeResult-klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| result | [BarCodeResult](../../com.aspose.barcode.barcoderecognition/barcoderesult) | Een kopie van een BarCodeResult-instantie. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Maakt een kopie van de BarCodeResult-klasse.

**Returns:**
java.lang.Object - Retourneert een kopie van de BarCodeResult-klasse.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven BarCodeResult-waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Een BarCodeResult-waarde om te vergelijken met deze instantie. |

**Returns:**
boolean -  **true**  als obj dezelfde waarde heeft als deze instantie; anders,  **false** .
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


Haalt de gecodeerde codebytes op

Waarde: De codebytes van de barcode

**Returns:**
byte[]
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


Haalt de code-tekst op

Waarde: De code-tekst van de barcode

**Returns:**
java.lang.String
### getCodeText(Charset encoding) {#getCodeText-java.nio.charset.Charset-}
```
public String getCodeText(Charset encoding)
```


Haalt de code-tekst op met codering.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| codering | java.nio.charset.Charset | De codering voor codetekst. |

**Returns:**
java.lang.String - Een string die herkende code-tekst bevat.
### getCodeType() {#getCodeType--}
```
public SingleDecodeType getCodeType()
```


Haalt het barcode-type op

Waarde: De type-informatie van de herkende barcode

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getCodeTypeName() {#getCodeTypeName--}
```
public String getCodeTypeName()
```


Haalt de naam van het barcode-type op

Waarde: De type-naam van de herkende barcode

**Returns:**
java.lang.String
### getConfidence() {#getConfidence--}
```
public int getConfidence()
```


Haalt het vertrouwensniveau van de herkenning van de herkende barcode op

Waarde:  BarCodeConfidence.Strong  heeft geen neppe of foutieve herkenningen,  BarCodeConfidence.Moderate  kan soms neppe of onjuiste codetekst hebben omdat dit vertrouwensniveau voor barcodes met een zwakke checksum of zelfs zonder,  BarCodeConfidence.None  heeft altijd onjuiste codetekst en kan neppe herkenningen zijn

**Returns:**
int
### getExtended() {#getExtended--}
```
public BarCodeExtendedParameters getExtended()
```


Haalt uitgebreide parameters van de herkende barcode op

Waarde: De uitgebreide parameters van de herkende barcode

**Returns:**
[BarCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/barcodeextendedparameters)
### getReadingQuality() {#getReadingQuality--}
```
public double getReadingQuality()
```


Haalt de leeskwaliteit op. Werkt voor 1D- en postbarcodes.

Waarde: Het leeskwaliteitspercentage

**Returns:**
double
### getRegion() {#getRegion--}
```
public BarCodeRegionParameters getRegion()
```


Haalt de barcode-regio op

Waarde: Het gebied van de herkende barcode

**Returns:**
[BarCodeRegionParameters](../../com.aspose.barcode.barcoderecognition/barcoderegionparameters)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode voor deze instantie.

**Returns:**
int - Een 32-bits ondertekend geheel getal hashcode.
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


Retourneert een menselijk leesbare tekenreeksrepresentatie van deze BarCodeResult.

**Returns:**
java.lang.String - Een string die dit  BarCodeResult  vertegenwoordigt.
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

