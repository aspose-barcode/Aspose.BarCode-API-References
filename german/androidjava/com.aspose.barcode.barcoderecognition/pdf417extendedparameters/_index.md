---
title: Pdf417ExtendedParameters
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Speichert Metadateninformationen von MacroPdf417 des erkannten Strichcodes
type: docs
weight: 40
url: /de/androidjava/com.aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class Pdf417ExtendedParameters extends BaseExtendedParameters
```

Speichert Metadateninformationen von MacroPdf417 des erkannten Strichcodes

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

| Method | Beschreibung |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen Pdf417ExtendedParameters-Wert entspricht. |
| [getClass()](#getClass--) |  |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Macro PDF417 Empfängername (optional). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Macro PDF417 Prüfsumme (optional). |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Liefert die Datei-ID des Barcodes, nur verfügbar mit MacroPdf417. |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Macro PDF417 Dateiname (optional). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Macro PDF417 Dateigröße (optional). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Liefert die Segment-ID des Barcodes, nur verfügbar mit MacroPdf417. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Liefert die Anzahl der macro pdf417 Barcode‑Segmente. |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Macro PDF417 Absendername (optional). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Gibt an, ob das Segment das letzte Segment einer Macro PDF417 Datei ist. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Macro PDF417 Zeitstempel (optional). |
| [hashCode()](#hashCode--) | Gibt den Hashcode für diese Instanz zurück. |
| [isCode128Emulation()](#isCode128Emulation--) | Flagge, die angibt, dass der MicroPdf417 Barcode mit 908, 909, 910 oder 911 Code‑128‑Emulationscodewörtern codiert ist. |
| [isEmpty()](#isEmpty--) | Prüft, ob alle Parameter nur Standardwerte haben |
| [isLinked()](#isLinked--) | Flagge, die angibt, dass der Barcode mit einem 1D‑Barcode verknüpft werden muss. |
| [isReaderInitialization()](#isReaderInitialization--) | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses Pdf417ExtendedParameters zurück. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen Pdf417ExtendedParameters-Wert entspricht.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Ein System.Object-Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolean -  **true**  wenn obj denselben Wert wie diese Instanz hat; andernfalls **false**.
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


Macro PDF417 Empfängername (optional).

**Returns:**
java.lang.String - Empfängername.
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public int getMacroPdf417Checksum()
```


Macro PDF417 Prüfsumme (optional).

**Returns:**
int - Prüfsumme.
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public String getMacroPdf417FileID()
```


Liefert die Datei-ID des Barcodes, nur verfügbar mit MacroPdf417.

Wert: Die Datei-ID für MacroPdf417

**Returns:**
java.lang.String
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public String getMacroPdf417FileName()
```


Macro PDF417 Dateiname (optional).

**Returns:**
java.lang.String - Dateiname.
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public int getMacroPdf417FileSize()
```


Macro PDF417 Dateigröße (optional).

**Returns:**
int - Dateigröße.
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public int getMacroPdf417SegmentID()
```


Liefert die Segment-ID des Barcodes, nur verfügbar mit MacroPdf417.

Wert: Die Segment-ID des Barcodes.

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public int getMacroPdf417SegmentsCount()
```


Liefert die Anzahl der macro pdf417 Barcode‑Segmente. Standardwert ist -1.

Wert: Segmentanzahl.

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public String getMacroPdf417Sender()
```


Macro PDF417 Absendername (optional).

**Returns:**
java.lang.String - Absendername
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public boolean getMacroPdf417Terminator()
```


Gibt an, ob das Segment das letzte Segment einer Macro PDF417 Datei ist.

**Returns:**
boolean - Terminator.
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public LocalDateTime getMacroPdf417TimeStamp()
```


Macro PDF417 Zeitstempel (optional).

**Returns:**
java.time.LocalDateTime - Time stamp.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese Instanz zurück.

**Returns:**
int - Ein 32-Bit vorzeichenbehafteter Ganzzahl-Hashcode.
### isCode128Emulation() {#isCode128Emulation--}
```
public boolean isCode128Emulation()
```


Flagge, die angibt, dass der MicroPdf417 Barcode mit 908, 909, 910 oder 911 Code‑128‑Emulationscodewörtern codiert ist.

**Returns:**
boolean - Code 128 emulation flag
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Prüft, ob alle Parameter nur Standardwerte haben

Wert: Gibt **true** zurück, wenn alle Parameter nur Standardwerte haben; andernfalls **false**.

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public boolean isLinked()
```


Flagge, die angibt, dass der Barcode mit einem 1D‑Barcode verknüpft werden muss.

Value: Linkage flag

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren.

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


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses Pdf417ExtendedParameters zurück.

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

