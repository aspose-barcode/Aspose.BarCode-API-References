---
title: Pdf417ExtendedParameters
second_title: Aspose.BarCode for Android via Java API-referentie
description: Slaat macro‑Pdf417‑metadata‑informatie op van de herkende barcode
type: docs
weight: 40
url: /nl/androidjava/com.aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class Pdf417ExtendedParameters extends BaseExtendedParameters
```

Slaat macro‑Pdf417‑metadata‑informatie op van de herkende barcode

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

| Method | Beschrijving |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven Pdf417ExtendedParameters-waarde. |
| [getClass()](#getClass--) |  |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Macro PDF417 geadresseerde naam (optioneel). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Macro PDF417 controlesom (optioneel). |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Haalt de bestands-ID van de barcode op, alleen beschikbaar met MacroPdf417. |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Macro PDF417 bestandsnaam (optioneel). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Macro PDF417 bestandsgrootte (optioneel). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Haalt de segment-ID van de barcode op, alleen beschikbaar met MacroPdf417. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Haalt het aantal segmenten van de macro pdf417 barcode op. |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Macro PDF417 afzendernaam (optioneel). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Geeft aan of het segment het laatste segment van een Macro PDF417-bestand is. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Macro PDF417 tijdstempel (optioneel). |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze instantie. |
| [isCode128Emulation()](#isCode128Emulation--) | Vlag die aangeeft dat de MicroPdf417 barcode is gecodeerd met 908, 909, 910 of 911 Code 128-emulatiecodewoorden. |
| [isEmpty()](#isEmpty--) | Test of alle parameters alleen standaardwaarden hebben |
| [isLinked()](#isLinked--) | Vlag die aangeeft dat de barcode gekoppeld moet worden aan een 1D-barcode. |
| [isReaderInitialization()](#isReaderInitialization--) | Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze Pdf417ExtendedParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven Pdf417ExtendedParameters-waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Een System.Object-waarde om te vergelijken met deze instantie. |

**Returns:**
boolean -  **true**  als obj dezelfde waarde heeft als deze instantie; anders,  **false** .
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


Macro PDF417 geadresseerde naam (optioneel).

**Returns:**
java.lang.String - Geadresseerde naam.
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public int getMacroPdf417Checksum()
```


Macro PDF417 controlesom (optioneel).

**Returns:**
int - Controlesom.
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public String getMacroPdf417FileID()
```


Haalt de bestands-ID van de barcode op, alleen beschikbaar met MacroPdf417.

Waarde: De bestands-ID voor MacroPdf417

**Returns:**
java.lang.String
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public String getMacroPdf417FileName()
```


Macro PDF417 bestandsnaam (optioneel).

**Returns:**
java.lang.String - Bestandsnaam.
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public int getMacroPdf417FileSize()
```


Macro PDF417 bestandsgrootte (optioneel).

**Returns:**
int - Bestandsgrootte.
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public int getMacroPdf417SegmentID()
```


Haalt de segment-ID van de barcode op, alleen beschikbaar met MacroPdf417.

Waarde: De segment-ID van de barcode.

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public int getMacroPdf417SegmentsCount()
```


Haalt het aantal segmenten van de macro pdf417 barcode op. Standaardwaarde is -1.

Waarde: Aantal segmenten.

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public String getMacroPdf417Sender()
```


Macro PDF417 afzendernaam (optioneel).

**Returns:**
java.lang.String - Afzendernaam
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public boolean getMacroPdf417Terminator()
```


Geeft aan of het segment het laatste segment van een Macro PDF417-bestand is.

**Returns:**
boolean - Terminator.
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public LocalDateTime getMacroPdf417TimeStamp()
```


Macro PDF417 tijdstempel (optioneel).

**Returns:**
java.time.LocalDateTime - Time stamp.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode voor deze instantie.

**Returns:**
int - Een 32-bits ondertekend geheel getal hashcode.
### isCode128Emulation() {#isCode128Emulation--}
```
public boolean isCode128Emulation()
```


Vlag die aangeeft dat de MicroPdf417 barcode is gecodeerd met 908, 909, 910 of 911 Code 128-emulatiecodewoorden.

**Returns:**
boolean - Code 128 emulation flag
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Test of alle parameters alleen standaardwaarden hebben

Waarde: Retourneert  **true**  als alle parameters alleen standaardwaarden hebben; anders,  **false** .

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public boolean isLinked()
```


Vlag die aangeeft dat de barcode gekoppeld moet worden aan een 1D-barcode.

Value: Linkage flag

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie.

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


Retourneert een menselijk leesbare tekenreeksrepresentatie van deze Pdf417ExtendedParameters.

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

