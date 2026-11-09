---
title: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode for Java API-referentie"
description: "Slaat speciale gegevens van een herkende DotCode-barcode op"
type: docs
weight: 31
url: /nl/java/com.aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DotCodeExtendedParameters extends BaseExtendedParameters
```

Slaat speciale gegevens van een herkende DotCode-barcode op

Dit voorbeeld laat zien hoe u de ruwe waarden van DotCode kunt ophalen

```

 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
 generator.save("c:\\test.png");
 
 BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.DOT_CODE);
 for (BarCodeResult result : reader.readBarCodes()
 {
      System.out.println("BarCode type: " + result.getCodeTypeName());
      System.out.println("BarCode codetext: " + result.getCodeText());
      System.out.println("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
      System.out.println("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
 }
 
```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) waarde. |
| [getClass()](#getClass--) |  |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Haalt de ID op van de DotCode gestructureerde append-modus barcode. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Haalt het aantal DotCode gestructureerde append-modus barcodes op. |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze instantie. |
| [isEmpty()](#isEmpty--) | Test of alle parameters alleen standaardwaarden hebben |
| [isReaderInitialization()](#isReaderInitialization--) | Geeft aan of de code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) waarde.

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
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Haalt de ID op van de DotCode gestructureerde append-modus barcode. ID begint bij 1 en moet kleiner of gelijk zijn aan het aantal barcodes. Standaardwaarde is -1.

Waarde: De ID van de DotCode gestructureerde append-modus barcode.

**Returns:**
int - de ID van de DotCode gestructureerde append-modus barcode.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Haalt het aantal DotCode gestructureerde append-modus barcodes op. Standaardwaarde is -1. Het aantal moet een waarde tussen 1 en 35 zijn.

Waarde: Het aantal van de DotCode gestructureerde append-modus barcode.

**Returns:**
int - het aantal DotCode gestructureerde append-modus barcodes.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode voor deze instantie.

**Returns:**
int - Een 32-bits ondertekend geheel getal hashcode.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Test of alle parameters alleen standaardwaarden hebben

Waarde: Retourneert **true** als alle parameters alleen standaardwaarden hebben; anders **false**.

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Geeft aan of de code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. Standaardwaarde is false.

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


Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters).

**Returns:**
java.lang.String - Een tekenreeks die dit [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) vertegenwoordigt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
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

