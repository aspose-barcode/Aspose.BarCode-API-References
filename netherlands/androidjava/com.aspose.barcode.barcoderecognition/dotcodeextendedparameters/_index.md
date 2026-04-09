---
title: DotCodeExtendedParameters
second_title: Aspose.BarCode for Android via Java API-referentie
description: Slaat speciale gegevens op van de herkende DotCode barcode
type: docs
weight: 33
url: /nl/androidjava/com.aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DotCodeExtendedParameters extends BaseExtendedParameters
```

Slaat speciale gegevens op van de herkende DotCode barcode

Deze voorbeeld toont hoe je de ruwe DotCode‑waarden krijgt

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
## Methods

| Method | Beschrijving |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters)-waarde. |
| [getClass()](#getClass--) |  |
| [getDotCodeIsReaderInitialization()](#getDotCodeIsReaderInitialization--) | Geeft aan of code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. |
| [getDotCodeStructuredAppendModeBarcodeId()](#getDotCodeStructuredAppendModeBarcodeId--) | Haalt de ID op van de DotCode gestructureerde append-modus barcode. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getDotCodeStructuredAppendModeBarcodesCount--) | Haalt het aantal DotCode gestructureerde append-modus barcodes op. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Haalt de ID op van de DotCode gestructureerde append-modus barcode. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Haalt het aantal DotCode gestructureerde append-modus barcodes op. |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze instantie. |
| [isEmpty()](#isEmpty--) | Test of alle parameters alleen standaardwaarden hebben |
| [isReaderInitialization()](#isReaderInitialization--) | Geeft aan of code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-) | Retourneert een waarde die aangeeft of de eerste [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) waarde gelijk is aan de tweede. |
| [op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-) | Retourneert een waarde die aangeeft of de eerste [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) waarde verschilt van de tweede. |
| [toString()](#toString--) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters)-waarde.

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
### getDotCodeIsReaderInitialization() {#getDotCodeIsReaderInitialization--}
```
public final boolean getDotCodeIsReaderInitialization()
```


Geeft aan of code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. Standaardwaarde is false.

**Returns:**
boolean
### getDotCodeStructuredAppendModeBarcodeId() {#getDotCodeStructuredAppendModeBarcodeId--}
```
public final int getDotCodeStructuredAppendModeBarcodeId()
```


Haalt de ID op van de DotCode gestructureerde append-modus barcode. ID begint bij 1 en moet kleiner of gelijk zijn aan het aantal barcodes. Standaardwaarde is -1.

Waarde: De ID van de DotCode gestructureerde append-modus barcode.

**Returns:**
int - de ID van de DotCode gestructureerde append-modus barcode.
### getDotCodeStructuredAppendModeBarcodesCount() {#getDotCodeStructuredAppendModeBarcodesCount--}
```
public final int getDotCodeStructuredAppendModeBarcodesCount()
```


Haalt het aantal DotCode gestructureerde append-modus barcodes op. Standaardwaarde is -1. Het aantal moet een waarde zijn van 1 tot 35.

Waarde: Het aantal van de DotCode gestructureerde append-modus barcode.

**Returns:**
int - het aantal DotCode gestructureerde append-modus barcodes.
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


Haalt het aantal DotCode gestructureerde append-modus barcodes op. Standaardwaarde is -1. Het aantal moet een waarde zijn van 1 tot 35.

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

Waarde: Retourneert  **true**  als alle parameters alleen standaardwaarden hebben; anders,  **false** .

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Geeft aan of code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. Standaardwaarde is false.

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




### op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-}
```
public static boolean op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)
```


Retourneert een waarde die aangeeft of de eerste [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) waarde gelijk is aan de tweede.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| first | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Een eerste te vergelijken waarde |
| second | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Een tweede te vergelijken waarde |

**Returns:**
boolean -  **true**  als eerste dezelfde waarde heeft als tweede; anders,  **false** .
### op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-}
```
public static boolean op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)
```


Retourneert een waarde die aangeeft of de eerste [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) waarde verschilt van de tweede.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| first | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Een eerste te vergelijken waarde |
| second | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Een tweede te vergelijken waarde |

**Returns:**
boolean -  **true**  als eerste een andere waarde heeft dan tweede; anders,  **false** .
### toString() {#toString--}
```
public String toString()
```


Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters).

**Returns:**
java.lang.String - Een tekenreeks die deze [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) vertegenwoordigt.
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

