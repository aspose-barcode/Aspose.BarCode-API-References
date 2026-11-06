---
title: "AztecExtendedParameters"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: "Speichert spezielle Daten des erkannten Aztec-Barcodes"
type: docs
weight: 12
url: /de/androidjava/com.aspose.barcode.barcoderecognition/aztecextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class AztecExtendedParameters extends BaseExtendedParameters
```

Speichert spezielle Daten des erkannten Aztec-Barcodes

--------------------

> ```
> This sample shows how to get Aztec raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345");
>  generator.save("test.png");
> 
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.AZTEC);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode type: " + result.getCodeTypeName());
>      System.out.println("BarCode codetext: " + result.getCodeText());
>      System.out.println("Aztec barcode ID: " + result.getExtended().getAztec().getStructuredAppendBarcodeId());
>      System.out.println("Aztec barcodes count: " + result.getExtended().getAztec().getStructuredAppendBarcodesCount());
>      System.out.println("Aztec file ID: " + result.getExtended().getAztec().getStructuredAppendFileId());
>      System.out.println("Aztec is reader initialization: " + result.getExtended().getAztec().isReaderInitialization());
>  }
> ```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen AztecExtendedParameters-Wert entspricht. |
| [getClass()](#getClass--) |  |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Ermittelt die ID des Aztec Structured Append Mode Barcodes. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Ermittelt die Anzahl der Aztec Structured Append Mode Barcodes. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Ermittelt die Datei-ID des Aztec Structured Append Mode. |
| [hashCode()](#hashCode--) | Gibt den Hashcode für diese Instanz zurück. |
| [isEmpty()](#isEmpty--) | Prüft, ob alle Parameter nur Standardwerte haben. |
| [isReaderInitialization()](#isReaderInitialization--) | Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder das Re‑Programmieren des Barcodelesers zu interpretieren. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses AztecExtendedParameters zurück. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen AztecExtendedParameters-Wert entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Ein System.Object‑Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolean -  **true**, wenn obj denselben Wert wie diese Instanz hat; andernfalls **false**.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public int getStructuredAppendBarcodeId()
```


Ermittelt die ID des Aztec Structured Append Mode Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode-Anzahl sein. Der Standardwert ist 0.

Wert: Die Barcode-ID des Aztec Structured Append Mode.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public int getStructuredAppendBarcodesCount()
```


Ermittelt die Anzahl der Aztec Structured Append Mode Barcodes. Der Standardwert ist 0. Die Anzahl muss ein Wert zwischen 1 und 26 sein.

Wert: Die Barcode-Anzahl des Aztec Structured Append Mode.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public String getStructuredAppendFileId()
```


Ermittelt die Datei-ID des Aztec Structured Append Mode. Der Standardwert ist ein leerer String.

Wert: Die Datei-ID des Aztec Structured Append Mode.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese Instanz zurück.

**Returns:**
int - Ein 32‑Bit vorzeichenbehafteter Integer‑Hashcode.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Prüft, ob alle Parameter nur Standardwerte haben.

Wert: Gibt **true** zurück, wenn alle Parameter nur Standardwerte haben; andernfalls **false**.

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder das Re‑Programmieren des Barcodelesers zu interpretieren. Der Standardwert ist false.

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


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses AztecExtendedParameters zurück.

**Returns:**
java.lang.String – Eine Zeichenkette, die dieses AztecExtendedParameters darstellt.
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

