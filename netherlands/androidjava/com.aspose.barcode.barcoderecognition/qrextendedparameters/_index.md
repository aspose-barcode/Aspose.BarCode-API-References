---
title: QRExtendedParameters
second_title: Aspose.BarCode for Android via Java API-referentie
description: Slaat QR Structured Append‑informatie op van de herkende barcode
type: docs
weight: 42
url: /nl/androidjava/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

Slaat QR Structured Append‑informatie op van de herkende barcode

Dit voorbeeld toont hoe QR Structured Append‑gegevens op te halen

```
{
```
## Methods

| Method | Beschrijving |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) waarde. |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | Reed‑Solomon‑foutcorrectieniveau van de herkende barcode. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Versie van de herkende MicroQR‑code. |
| [getQRErrorLevel()](#getQRErrorLevel--) | Reed‑Solomon‑foutcorrectieniveau van de herkende barcode. |
| [getQRStructuredAppendModeBarCodeIndex()](#getQRStructuredAppendModeBarCodeIndex--) | Haalt de index op van de QR structured append‑modusbarcode. |
| [getQRStructuredAppendModeBarCodesQuantity()](#getQRStructuredAppendModeBarCodesQuantity--) | Haalt de hoeveelheid QR structured append‑modusbarcodes op. |
| [getQRStructuredAppendModeParityData()](#getQRStructuredAppendModeParityData--) | Haalt de QR-gestructureerde append-modus pariteitsgegevens op. |
| [getQRVersion()](#getQRVersion--) | Versie van herkende QR-code. |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | Versie van herkende RectMicroQR-code. |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | Haalt de index op van de QR structured append‑modusbarcode. |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | Haalt de hoeveelheid QR structured append‑modusbarcodes op. |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | Haalt de QR-gestructureerde append-modus pariteitsgegevens op. |
| [getVersion()](#getVersion--) | Versie van herkende QR-code. |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze instantie. |
| [isEmpty()](#isEmpty--) | Test of alle parameters alleen standaardwaarden hebben |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(QRExtendedParameters first, QRExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | Retourneert een waarde die aangeeft of de eerste [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) waarde gelijk is aan de tweede. |
| [op_Inequality(QRExtendedParameters first, QRExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | Retourneert een waarde die aangeeft of de eerste [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) waarde verschilt van de tweede. |
| [toString()](#toString--) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) waarde.

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
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Reed-Solomon-foutcorrectieniveau van herkende barcode. Van laag naar hoog: LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Versie van herkende MicroQR-code. Van M1 tot M4.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQRErrorLevel() {#getQRErrorLevel--}
```
public final QRErrorLevel getQRErrorLevel()
```


Reed-Solomon-foutcorrectieniveau van herkende barcode. Van laag naar hoog: LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQRStructuredAppendModeBarCodeIndex() {#getQRStructuredAppendModeBarCodeIndex--}
```
public final int getQRStructuredAppendModeBarCodeIndex()
```


Haalt de index op van de QR-gestructureerde append-modus barcode. Index begint bij 0. Standaardwaarde is -1.

Waarde: De hoeveelheid van de QR-gestructureerde append-modus barcode.

**Returns:**
int - de index van de QR-gestructureerde append-modus barcode.
### getQRStructuredAppendModeBarCodesQuantity() {#getQRStructuredAppendModeBarCodesQuantity--}
```
public final int getQRStructuredAppendModeBarCodesQuantity()
```


Haalt de hoeveelheid QR-gestructureerde append-modus barcodes op. Standaardwaarde is -1.

Waarde: De hoeveelheid van de QR-gestructureerde append-modus barcode.

**Returns:**
int - de hoeveelheid QR-gestructureerde append-modus barcodes.
### getQRStructuredAppendModeParityData() {#getQRStructuredAppendModeParityData--}
```
public final int getQRStructuredAppendModeParityData()
```


Haalt de QR-gestructureerde append-modus pariteitsgegevens op. Standaardwaarde is -1.

Waarde: De index van de QR-gestructureerde append-modus barcode.

**Returns:**
int - de QR-gestructureerde append-modus pariteitsgegevens.
### getQRVersion() {#getQRVersion--}
```
public final QRVersion getQRVersion()
```


Versie van herkende QR-code. Van Version1 tot Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


Versie van herkende RectMicroQR-code. Van R7x43 tot R17x139.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


Haalt de index op van de QR-gestructureerde append-modus barcode. Index begint bij 0. Standaardwaarde is -1.

Waarde: De hoeveelheid van de QR-gestructureerde append-modus barcode.

**Returns:**
int - de index van de QR-gestructureerde append-modus barcode.
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


Haalt de hoeveelheid QR-gestructureerde append-modus barcodes op. Standaardwaarde is -1.

Waarde: De hoeveelheid van de QR-gestructureerde append-modus barcode.

**Returns:**
int - de hoeveelheid QR-gestructureerde append-modus barcodes.
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


Haalt de QR-gestructureerde append-modus pariteitsgegevens op. Standaardwaarde is -1.

Waarde: De index van de QR-gestructureerde append-modus barcode.

**Returns:**
int - de QR-gestructureerde append-modus pariteitsgegevens.
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Versie van herkende QR-code. Van Version1 tot Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(QRExtendedParameters first, QRExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Equality(QRExtendedParameters first, QRExtendedParameters second)
```


Retourneert een waarde die aangeeft of de eerste [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) waarde gelijk is aan de tweede.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Een eerste te vergelijken waarde |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Een tweede te vergelijken waarde |

**Returns:**
boolean -  **true**  als eerste dezelfde waarde heeft als tweede; anders,  **false** .
### op_Inequality(QRExtendedParameters first, QRExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Inequality(QRExtendedParameters first, QRExtendedParameters second)
```


Retourneert een waarde die aangeeft of de eerste [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) waarde verschilt van de tweede.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Een eerste te vergelijken waarde |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Een tweede te vergelijken waarde |

**Returns:**
boolean -  **true**  als eerste een andere waarde heeft dan tweede; anders,  **false** .
### toString() {#toString--}
```
public String toString()
```


Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).

**Returns:**
java.lang.String - Een tekenreeks die deze [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) representeert.
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

