---
title: Pdf417ExtendedParameters
second_title: Aspose.BarCode for Android via Java API-referens
description: Lagrar metadatainformation för MacroPdf417 för en igenkänd streckkod
type: docs
weight: 40
url: /sv/androidjava/com.aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class Pdf417ExtendedParameters extends BaseExtendedParameters
```

Lagrar metadatainformation för MacroPdf417 för en igenkänd streckkod

--------------------

> ```
> This sample shows how to get Macro Pdf417 metadata
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MACRO_PDF_417);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
>      System.out.println("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
>      System.out.println("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
>  }
> ```
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat Pdf417ExtendedParameters‑värde. |
| [getClass()](#getClass--) |  |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Macro PDF417-mottagarnamn (valfritt). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Macro PDF417-kontrollsumma (valfritt). |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Hämtar fil‑ID för streckkoden, endast tillgängligt med MacroPdf417. |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Macro PDF417-filnamn (valfritt). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Macro PDF417-filstorlek (valfritt). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Hämtar segment‑ID för streckkoden, endast tillgängligt med MacroPdf417. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Hämtar antalet segment i macro pdf417‑streckkod. |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Macro PDF417-avsändarnamn (valfritt). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Indikerar om segmentet är det sista segmentet i en Macro PDF417‑fil. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Macro PDF417-tidsstämpel (valfritt). |
| [hashCode()](#hashCode--) | Returnerar hash‑koden för detta objekt. |
| [isCode128Emulation()](#isCode128Emulation--) | Flagga som indikerar att MicroPdf417‑streckkoden är kodad med 908, 909, 910 eller 911 Code 128‑emuleringskodord. |
| [isEmpty()](#isEmpty--) | Testar om alla parametrar endast har standardvärden |
| [isLinked()](#isLinked--) | Flagga som indikerar att streckkoden måste länkas till en 1D‑streckkod. |
| [isReaderInitialization()](#isReaderInitialization--) | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarens initiering. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta Pdf417ExtendedParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat Pdf417ExtendedParameters‑värde.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Ett System.Object‑värde att jämföra med detta objekt. |

**Returns:**
boolean -  **true**  om obj har samma värde som detta objekt; annars,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public String getMacroPdf417Addressee()
```


Macro PDF417-mottagarnamn (valfritt).

**Returns:**
java.lang.String - mottagarnamn.
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public int getMacroPdf417Checksum()
```


Macro PDF417-kontrollsumma (valfritt).

**Returns:**
int - kontrollsumma.
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public String getMacroPdf417FileID()
```


Hämtar fil‑ID för streckkoden, endast tillgängligt med MacroPdf417.

Värde: Fil‑ID för MacroPdf417

**Returns:**
java.lang.String
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public String getMacroPdf417FileName()
```


Macro PDF417-filnamn (valfritt).

**Returns:**
java.lang.String - filnamn.
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public int getMacroPdf417FileSize()
```


Macro PDF417-filstorlek (valfritt).

**Returns:**
int - filstorlek.
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public int getMacroPdf417SegmentID()
```


Hämtar segment‑ID för streckkoden, endast tillgängligt med MacroPdf417.

Värde: Segment‑ID för streckkoden.

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public int getMacroPdf417SegmentsCount()
```


Hämtar antalet segment i macro pdf417‑streckkod. Standardvärdet är -1.

Värde: Antal segment.

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public String getMacroPdf417Sender()
```


Macro PDF417-avsändarnamn (valfritt).

**Returns:**
java.lang.String - avsändarnamn
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public boolean getMacroPdf417Terminator()
```


Indikerar om segmentet är det sista segmentet i en Macro PDF417‑fil.

**Returns:**
boolean - terminator.
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public LocalDateTime getMacroPdf417TimeStamp()
```


Macro PDF417-tidsstämpel (valfritt).

**Returns:**
java.time.LocalDateTime - Time stamp.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hash‑koden för detta objekt.

**Returns:**
int - En 32‑bitars signerad heltals‑hashkod.
### isCode128Emulation() {#isCode128Emulation--}
```
public boolean isCode128Emulation()
```


Flagga som indikerar att MicroPdf417‑streckkoden är kodad med 908, 909, 910 eller 911 Code 128‑emuleringskodord.

**Returns:**
boolean - Code 128 emulation flag
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Testar om alla parametrar endast har standardvärden

Värde: Returnerar  **true**  om alla parametrar endast har standardvärden; annars,  **false** .

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public boolean isLinked()
```


Flagga som indikerar att streckkoden måste länkas till en 1D‑streckkod.

Value: Linkage flag

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarens initiering.

Value: Reader initialization flag

**Returns:**
boolean
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


Returnerar en människoläsbar strängrepresentation av detta Pdf417ExtendedParameters.

**Returns:**
java.lang.String - A string that represents this  Pdf417ExtendedParameters .
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

